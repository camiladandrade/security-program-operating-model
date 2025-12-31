# Modelo de Governança — Programa de Segurança da Informação

Este documento define um modelo prático de **governança** para um programa de Segurança, conectando:
- responsabilidades (RACI)
- cadências e rituais
- fluxo de decisão e escalonamento
- reporting executivo e transparência

> Objetivo: garantir que Segurança tenha **direção, ritmo e decisão**, não apenas atividades soltas.

---

## 1) Princípios de governança

- Governança deve **habilitar execução**, não criar burocracia
- Decisão precisa de: **dono**, **critério** e **registro**
- Segurança opera em dois ritmos:
  - **Operacional:** execução semanal (VM/IR/detecções)
  - **Executivo:** decisões mensais/trimestrais (riscos, investimentos)
- Transparência: métricas e riscos claros para stakeholders

---

## 2) Estrutura de governança (camadas)

### 2.1 Operação (semanal)
**Foco:** execução, backlog e remoção de bloqueios  
**Exemplos:**
- reunião semanal de VM/exposição
- revisão rápida SOC/IR (quando aplicável)
- acompanhamento de ações pós-incidente

**Entradas:** backlog, SLAs, alerts, mudanças relevantes  
**Saídas:** ações com owner/prazo, ajustes de prioridade

---

### 2.2 Gestão (mensal)
**Foco:** performance do programa e riscos  
**Exemplos:**
- revisão mensal de KPIs
- revisão mensal de riscos (top risks)
- status de auditorias e evidências (quando aplicável)

**Entradas:** KPIs, top riscos, exceções/aceites, incidentes relevantes  
**Saídas:** prioridades do mês, escalonamentos, ajustes de governança

---

### 2.3 Direção (mensal/trimestral)
**Foco:** decisões e trade-offs executivos  
**Exemplos:**
- steering committee de Segurança (mensal)
- QBR de Segurança (trimestral)

**Entradas:** 1-pager executivo, top riscos, pedidos de decisão  
**Saídas:** decisões, aprovação de recursos, direcionamento estratégico

---

## 3) Papéis e responsabilidades (visão resumida)

Este modelo assume que responsabilidades detalhadas estão em:
- `../03-raci/raci-by-process.md` (modelo preenchido por processo)
- `../03-raci/raci-template.md` (modelo em branco)

Papéis típicos:
- Segurança (GRC)
- Segurança (VM/Exposição)
- Segurança (IR/SOC)
- TI/Infra
- IAM/Identidade
- Negócio (Donos de processo)
- Compliance/Privacidade
- Liderança (Diretoria/VP)

---

## 4) Cadências e rituais oficiais

Referência principal:
- `committees-and-rituals.md`

### 4.1 Ritual semanal — Exposição/VM (30–45 min)
**Objetivo:** SLA, priorização e desbloqueios  
**Saídas:** tickets priorizados + owners + prazos

### 4.2 Ritual mensal — KPIs + Risco (45–60 min)
**Objetivo:** tendências, top riscos, plano do mês  
**Saídas:** prioridades + escalonamentos

### 4.3 Steering Committee (mensal) (30–45 min)
**Objetivo:** decisões (máx. 3) e trade-offs  
**Saídas:** decisões registradas + aprovações

### 4.4 QBR (trimestral) (60–90 min)
**Objetivo:** resultados, roadmap e investimentos  
**Saídas:** metas trimestrais + roadmap atualizado

---

## 5) Fluxo de decisão e escalonamento

### 5.1 Quando escalar (gatilhos)
- vulnerabilidades críticas fora do SLA sem janela
- risco alto sem mitigação viável no prazo
- exceções/aceites que aumentem risco relevante
- incidentes severos ou recorrentes
- necessidade de investimento (ferramenta/serviço/time)

### 5.2 Caminho de escalonamento (modelo)
1. **Operação:** tentativa de resolver no ritual semanal (VM/IR)
2. **Gestão:** se persistir, vai para revisão mensal (KPIs + risco)
3. **Executivo:** se exigir trade-off/recurso, vai para Steering

### 5.3 Registro de decisões (obrigatório)
Toda decisão executiva deve ser registrada em:
- `../05-templates/decision-log-template.md` (quando criado)

Campos mínimos:
- decisão
- por que (racional)
- risco/trade-off
- owner
- prazo
- evidência de acompanhamento

---

## 6) Artefatos de governança (o que precisa existir)

### Operacionais
- backlog priorizado (por risco)
- SLA e status de VM
- registro de incidentes e pós-incidente
- lista de exceções e aceites com expiração

### Executivos
- 1-pager mensal (semáforo + top riscos + decisões)
- relatório mensal (KPIs + riscos + roadmap)
- QBR trimestral (resultados + investimentos)

> Dica: templates executivos podem ficar no repo de métricas (`security-metrics-and-kpis`) e serem referenciados aqui.

---

## 7) Métricas mínimas para governança (baseline)

- % de vulnerabilidades críticas corrigidas no SLA
- tempo de resposta/contensão de incidentes (MTTR)
- nº de exceções/aceites ativos (e expirados)
- status de auditorias/evidências (quando aplicável)
- progresso do roadmap (% concluído / bloqueios)

---

## 8) Revisão e melhoria contínua

- revisão mensal do operating model (o que trava? o que gera ruído?)
- revisão trimestral do RACI e cadências
- lições aprendidas pós-incidente alimentam:
  - backlog
  - detecções
  - governança (processos e controles)

---

