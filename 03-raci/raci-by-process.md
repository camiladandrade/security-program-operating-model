# RACI por Processo — Segurança da Informação (Modelo)

Este documento define um modelo de **RACI por processo** para um programa de Segurança, deixando claro:
- quem **faz** (Responsável)
- quem **aprova** (Aprovador / Accountable)
- quem **apoia** (Consultado)
- quem **precisa saber** (Informado)

> Objetivo: reduzir gargalos, eliminar “terra de ninguém” e acelerar execução.

---

## 1) Como usar este documento

1. Selecione os **processos prioritários** do seu programa (Top 8–12).
2. Preencha a matriz com os papéis reais da organização.
3. Valide em steering (ou liderança de TI/negócio).
4. Publique e use como base para cadências, SLAs e decisões.

---

## 2) Legenda RACI (padrão)

- **R — Responsável:** executa o trabalho.
- **A — Aprovador (Accountable):** dono do resultado; aprova e responde.
- **C — Consultado:** contribui com conhecimento/inputs.
- **I — Informado:** precisa ser comunicado.

> Regra prática:  
> - cada atividade deve ter **1 (um) A**  
> - evite múltiplos “A” (cria disputa e travas)  
> - “R” pode ter mais de um, se houver divisão clara.

---

## 3) Papéis (ajuste conforme sua realidade)

Sugestão de papéis para o modelo (exemplo):
- **Segurança (GRC)**
- **Segurança (Exposição/VM)**
- **Segurança (IR/SOC)** (ou “SOC/MDR”, se terceirizado)
- **TI/Infra**
- **Produto/Engenharia** (quando aplicável)
- **IAM/Identidade**
- **Compliance/Privacidade**
- **Jurídico**
- **Negócio (Dono do Processo)**
- **Liderança (Diretoria/VP)**

> Você pode substituir/compactar papéis (ex.: “Segurança” como único time) conforme tamanho da organização.

---

## 4) Matriz RACI (modelo principal)

> Dica: comece simples e refine depois.

| Processo | GRC | VM/Exposição | IR/SOC | TI/Infra | IAM | Produto/Eng | Privacidade/Compliance | Jurídico | Negócio (Dono) | Liderança |
|---|---|---|---|---|---|---|---|---|---|---|
| 1) Gestão de Vulnerabilidades (ciclo completo) | C | **A/R** | C | **R** | C | C | I | I | C | I |
| 2) Priorização e SLA de remediação | C | **A/R** | C | **R** | C | C | I | I | **C** | I |
| 3) Gestão de Incidentes (processo + playbooks) | C | C | **A/R** | R | C | C | C | C | I | I |
| 4) Comunicação de incidente (stakeholders) | C | I | **A/R** | C | I | I | C | **C** | **I** | **I** |
| 5) Gestão de Riscos de Segurança | **A/R** | C | C | C | C | C | C | C | **C** | I |
| 6) Aceite de risco (risk acceptance) | **R** | C | C | C | C | C | C | C | **A** | I |
| 7) Exceções temporárias de controle (risk exception) | **R** | C | C | C | C | C | C | C | **A** | I |
| 8) Gestão de Políticas e Padrões | **A/R** | C | C | C | C | C | C | C | I | I |
| 9) Auditoria interna/externa (evidências) | **A/R** | C | C | C | C | C | C | C | I | I |
| 10) Gestão de Terceiros (segurança em fornecedores) | **A/R** | C | C | C | C | C | **C** | **C** | **C** | I |
| 11) IAM — revisões de acesso e privilégios | C | I | C | R | **A/R** | C | C | I | C | I |
| 12) Resiliência (BIA/BCP/DR e testes) | **A/R** | I | C | **R** | C | C | C | I | **C** | I |

> Observação: esta matriz é um modelo. Ajuste “A” conforme governança real da empresa.

---

## 5) Atividades detalhadas (quando precisar de granularidade)

Se você quiser detalhar um processo, use a matriz por atividade.

### Exemplo — Gestão de Vulnerabilidades (atividades)
| Atividade | GRC | VM/Exposição | IR/SOC | TI/Infra | IAM | Produto/Eng | Negócio (Dono) |
|---|---|---|---|---|---|---|---|
| Definir escopo e frequência de scans | C | **A/R** | C | **R** | C | C | I |
| Triagem e priorização por risco | C | **A/R** | C | C | C | C | C |
| Abrir tickets e negociar janelas | I | **R** | I | **A/R** | I | **A/R** | C |
| Validar correção (re-scan) | I | **A/R** | I | C | I | C | I |
| Reporting mensal e escalonamento | **C** | **A/R** | C | C | C | C | I |

---

## 6) Regras de governança (para o RACI funcionar)

- o RACI deve ser revisado **trimestralmente** (ou quando houver reorg/mudança)
- escalonamento de bloqueios (quem decide trade-off) deve estar claro
- decisões de “aceitar risco” devem ter:
  - prazo de expiração
  - justificativa
  - compensating controls (quando aplicável)
  - aprovador (A)

---

