---
id: BINDING
type: vault-binding
metavault: ../metavault
rules_mode: current
# Аудитория: какие классы правил (теги agent/*) компилируются в этот вольт.
# Без rule_classes — все классы, кроме agent/reference. Здесь исключён agent/profile:
# правила софтового профиля (cut, code-links, software-profile) вольту философии не нужны.
rule_classes: [agent/governance, agent/model, agent/storage, agent/ingest, agent/retrieval, agent/workflow]
local_additions: []
bound_by: tuvastamata
created: 2026-09-04
status: proposed
---

# Binding — привязка vault-philosophy к мета-вольту

Рабочий вольт богословия и философии; живёт по правилам мета-вольта ([[CON-vault-binding]]).
Свод правил: `python3 ../metavault/tools/compile-agents.py .`
