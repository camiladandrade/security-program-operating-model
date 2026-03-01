# 🗺️ ROADMAP — Security Program Operating Model

Este roadmap organiza as entregas do repositório em **milestones** para construir um Operating Model de Segurança com foco em **liderança**, **governança operável**, **execução por processos** e **decisão executiva**.

📌 Objetivo do repositório:
Demonstrar como estruturar e operar um programa de Segurança:
**capabilities → governança/cadência → execução (RACI) → OKRs/KPIs → reporting/QBR → plano 30-60-90**.

---

## ✅ Definição de pronto (Definition of Done)

Uma entrega está “pronta” quando:
- Está em **PT-BR**, clara e aplicável.
- Tem **objetivo + quando usar + outputs** no topo.
- Indica **owners/hand-offs** quando aplicável (processos).
- Conecta **métrica → decisão → rotina** quando aplicável.
- Inclui exemplo fictício (template preenchido ou exemplo de decisão) quando fizer sentido.
- Está **linkada** no README raiz e no README da pasta correspondente.

---

## 🧱 M0 — Repo Product Ready (higiene + navegação)
**Objetivo:** repo com cara de produto (navegável e rastreável).

### Entregas
- [x] `ROADMAP.md` (este arquivo)
- [x] `CHANGELOG.md`
- [x] `LICENSE`
- [x] `DISCLAIMERS.md`
- [x] README raiz com Quick Start + links válidos
- [ ] Padronizar cabeçalho dos docs (Objetivo / Quando usar / Outputs)

### Pacote de commits sugerido
- `chore: add roadmap, changelog, license and disclaimers`
- `docs: update root README quickstart + repo map`
- `docs: standardize document headers (purpose/when to use/outputs)`

---

## 🧭 M1 — Capabilities Model v2 (mapa do programa)
**Objetivo:** capabilities + maturidade + priorização + roadmap.

### Entregas (01-program-structure/)
- [ ] Revisar `security-capabilities-model.md`
- [ ] `capability-maturity-levels.md`
- [ ] `capability-prioritization-framework.md`
- [ ] `operating-model-one-pager.md`
- [ ] Revisar `security-roadmap-template.md` (dependências + métricas)

### Pacote de commits sugerido
- `docs: upgrade security capabilities model + maturity levels`
- `docs: add capability prioritization framework + 1pager`
- `templates: upgrade security roadmap template (dependencies + metrics)`

---

## 🏛️ M2 — Governança v2 (cadência, comitês, decision rights)
**Objetivo:** fóruns, pauta, outputs, escalonamento e decisões.

### Entregas (02-governance/)
- [ ] Revisar `governance-model.md` (camadas: operacional/tático/executivo)
- [ ] Revisar `committees-and-rituals.md` (agenda + outputs)
- [ ] Evoluir `steering-committee-pack-template.md`
- [ ] `steering-agenda-template.md`
- [ ] `escalation-and-decision-rights.md`
- [ ] `risk-acceptance-governance.md` (integração com GRC)

### Pacote de commits sugerido
- `docs: upgrade governance model (ops/tactical/executive layers)`
- `docs: upgrade committees and rituals (agenda + outputs)`
- `templates: add steering agenda + decision rights/escalation`

---

## 👥 M3 — RACI v2 (execução por processo)
**Objetivo:** ownership e handoffs claros (execução sustentável).

### Entregas (03-raci/)
- [ ] Revisar `raci-template.md`
- [ ] Expandir `raci-by-process.md` (GRC/VM/IR/IAM/TPRM/Awareness)
- [ ] `roles-and-accountabilities.md` (papéis do programa)

### Pacote de commits sugerido
- `docs: upgrade RACI template for auditability`
- `docs: expand RACI by process (GRC/VM/IR/IAM/TPRM)`
- `docs: add roles and accountabilities for the security program`

---

## 🎯 M4 — OKRs & KPIs v2 (estratégia → execução → evidência)
**Objetivo:** metas mensuráveis e reportáveis.

### Entregas (01-program-structure/)
- [ ] Revisar `okrs-and-kpis-structure.md` (com exemplos por domínio)
- [ ] `okr-examples-by-domain.md`
- [ ] `kpi-kri-minimum-pack.md`
- [ ] `metrics-governance.md` (cadência, owners, qualidade do dado)
- [ ] Linkar com `security-metrics-and-kpis` (cross-repo)

### Pacote de commits sugerido
- `docs: upgrade OKRs/KPIs structure with examples + thresholds`
- `docs: add minimum KPI/KRI pack + metrics governance`
- `docs: link operating model to metrics repo (cross-repo navigation)`

---

## 🚀 M5 — Plano 30-60-90 v2 (entrada com impacto)
**Objetivo:** material de entrevista (diagnóstico + quick wins + métricas).

### Entregas (04-30-60-90/)
- [ ] Revisar `30-60-90-days-plan.md` (métricas e evidências por fase)
- [ ] `first-30-days-assessment-checklist.md`
- [ ] `stakeholder-map-template.md`
- [ ] `90-day-backlog-template.md`

### Pacote de commits sugerido
- `docs: upgrade 30-60-90 plan to include metrics and evidence`
- `templates: add 30-day assessment checklist + stakeholder map`
- `templates: add 90-day backlog template`

---

## 📦 M6 — Templates executivos v2 (QBR, status, decisões)
**Objetivo:** sustentar governança com templates “do mundo real”.

### Entregas (05-templates/)
- [ ] Revisar `decision-log-template.md`
- [ ] Revisar `quarterly-business-review-qbr-template.md`
- [ ] `monthly-security-program-review-template.md`
- [ ] `exec-1pager-template.md`
- [ ] `program-status-weekly-template.md` (opcional)
- [ ] `risk-acceptance-decision-template.md`

### Pacote de commits sugerido
- `templates: upgrade QBR + decision log templates`
- `templates: add monthly program review + exec 1pager`
- `templates: add risk acceptance decision template`

---

## 🗂️ M7 — Case Studies (3 casos “pasta de entrevista”)
**Objetivo:** provar execução com resultados (métricas + decisões + evidências).

### Entregas (criar 06-case-studies/)
- [ ] `06-case-studies/README.md`
- [ ] `case-01-program-turnaround-90-days/`
- [ ] `case-02-governance-and-steering-implementation/`
- [ ] `case-03-metrics-to-investment-prioritization/`

**Formato padrão**
- `contexto.md` • `diagnostico.md` • `decisoes-e-trade-offs.md` • `execucao-e-rituais.md` • `metricas-e-evidencias.md` • `resultado.md` • `next-steps.md`

### Pacote de commits sugerido
- `cases: add case studies structure + template`
- `cases: add case 01 (90-day program turnaround)`
- `cases: add case 02 (governance + steering implementation)`
- `cases: add case 03 (metrics -> investment prioritization)`
