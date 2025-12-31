# OKRs e KPIs — Estrutura para Execução (Programa de Segurança)

Este documento define como estruturar **OKRs (objetivos e resultados-chave)** e conectar com **KPIs** para garantir execução e reporting consistente no programa de Segurança.

> Objetivo: transformar “segurança como intenção” em metas mensuráveis, iniciativas claras e decisões baseadas em dados.

---

## 1) Diferença prática: OKR vs KPI

### OKR (mudança / resultado)
- foco em **transformação** e impacto
- orientado a objetivos de curto/médio prazo (trimestre/semestre)
- define “onde queremos chegar” + “como vamos medir o sucesso”

Ex.: “Reduzir exposição crítica em ativos Tier-0”.

### KPI (saúde / performance contínua)
- mede performance recorrente do processo
- mostra tendência e estabilidade do programa
- usado para governança mensal (painel)

Ex.: “% de vulnerabilidades críticas corrigidas no SLA”.

> Regra simples:
- **OKR** = mudança / avanço de maturidade  
- **KPI** = operação / saúde contínua

---

## 2) Modelo de cascata (do objetivo ao dado)

Use esta cadeia:

**Risco/Objetivo do Negócio → Objetivo de Segurança (OKR) → Iniciativas → KPIs → Report Executivo**

### Exemplo (alto nível)
- Risco: exploração de vulnerabilidades em ativos críticos  
- OKR: reduzir exposição crítica  
- Iniciativas: definir SLA, priorização, cadência semanal, automação  
- KPIs: SLA de críticas, aging, cobertura de scans  
- Report: 1-pager mensal e relatório mensal

---

## 3) Estrutura recomendada de OKRs (por trimestre)

### 3.1 Quantidade e foco
- **2 a 4 objetivos no máximo** por trimestre
- **2 a 4 KRs por objetivo**
- cada KR precisa ser mensurável, com baseline e meta

### 3.2 Qualidade dos KRs (boas práticas)
KRs bons são:
- mensuráveis (número, %, prazo)
- relevantes para risco/negócio
- com baseline e meta clara
- possíveis com a capacidade atual (ou explicitando necessidade)

KRs ruins:
- “Melhorar segurança”
- “Aumentar maturidade”
- “Fazer treinamentos” (sem efeito mensurável)

---

## 4) Templates

### 4.1 Template de OKR (por objetivo)
- **Objetivo (O):** ___________________________________________
- **Por que importa (risco/negócio):** _________________________
- **Escopo:** (área, ativos, processos) _________________________
- **Prazo:** (trimestre) _______________________________________

**Resultados-chave (KRs):**
1) KR1: ___________________________________ (baseline: ___ / meta: ___)
2) KR2: ___________________________________ (baseline: ___ / meta: ___)
3) KR3: ___________________________________ (baseline: ___ / meta: ___)

**Iniciativas (como vamos fazer):**
- __________________________________________
- __________________________________________
- __________________________________________

**Dependências e riscos:**
- __________________________________________

**Owner:** _______________________

---

### 4.2 Template de governança de OKR (check-in mensal)
- Objetivo: _______________________
- Status: 🟢/🟡/🔴
- O que avançou:
- O que travou:
- Decisões necessárias:
- Próximas ações (owner/prazo):

---

## 5) Catálogo de áreas para OKRs (sugestões)

### Governança (GRC)
- reduzir gaps de políticas/auditoria
- acelerar evidências e rastreabilidade
- melhorar gestão de riscos (aceites/exceções)

### Exposição e Vulnerabilidades (VM)
- reduzir backlog crítico
- melhorar cobertura de scans e inventário
- reduzir tempo de remediação

### Incidentes e Detecção (IR/SOC)
- reduzir MTTR
- aumentar cobertura de detecção por TTP
- reduzir incidentes recorrentes (mesma causa)

### IAM
- aumentar cobertura de MFA e hardening de acesso privilegiado
- reduzir contas órfãs e acessos excessivos

### Resiliência (BCP/DR)
- completar BIA e validar RTO/RPO
- aumentar execução de testes e evidências

---

## 6) Conectar OKRs com KPIs (modelo prático)

Para cada OKR, defina:
- 1–2 **KPIs de resultado** (efeito)
- 2–4 **KPIs de processo** (saúde)

### Exemplo — OKR de VM
**KR (resultado):** “Atingir 90% de críticas corrigidas no SLA”  
KPIs associados:
- Resultado: % críticas no SLA
- Processo: aging médio de críticas, cobertura de scan, nº de exceções

---

## 7) Reporting e transparência

### 7.1 Report mensal (sugestão)
- top 3 mudanças do mês
- status de OKRs (🟢🟡🔴)
- KPIs essenciais (GRC/VM/IR)
- top riscos e decisões necessárias

> Você pode usar os templates do repositório `security-metrics-and-kpis` como padrão de reporting executivo.

---

