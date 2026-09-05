---
id: README
type: guide
status: proposed
created: 2026-09-04
---

# vault-philosophy — богословие и философия

Рабочий вольт, привязанный к мета-вольту по [[CON-vault-binding]] (`_meta/BINDING.md`; профиль софтового проекта отключён через `rule_classes`). Язык — русский.

Здесь живут **external-концепты** — рефераты чужих идей с обязательным `primary_source` ([[CON-concept-origin]]) — и собственные концепты, рождённые в обсуждениях. Первый узел — [[CON-lacanian-gap]], переехавший из мета-вольта 2026-09-04: в мета-вольте external-концептов не бывает, там правила цитируют чужие идеи текстом.

## Что внутри (2026-09-04)

Carve-out из вольта `road-to-emmaus` — линии, не предназначенные коллегам (ветка `inceste` сверх `main@59fad0f`), отчёт: [[INGEST-20260904]].

- `lines/` — три линии: [[LINE-pain-of-thou]] (боль от прикосновения к Ты), [[LINE-incest-power]] (инцест и власть), [[LINE-psychotic-orthodoxy]] (психотическое православие).
- `sources/` — raw: беседа «Церковь и страдание» 10.05.2026 ([[SRC-20260510-church-suffering]] + транскрипт с якорями) и рукописная заметка «Власть» 27.08.2026 ([[SRC-20260827-note-power]] + скан); nominal: текстовые сессии [[SRC-20260825-text]], [[SRC-20260827-text]].
- `statements/` — семь высказываний: шесть тезисов Андрея и один разбор-кейс агента ([[STM-20260827-claude-hilarion-case]]).
- `persons/` — лица (заявка [[VER-node-types-v2]]): [[PER-kireev]], [[PER-hilarion]] (human), [[PER-eoc-mp]] (organization).
- `concepts/` + `versions/` — 13 концептов с телами v1 (плюс [[CON-lacanian-gap]]); все `proposed`: одобрение страниц в исходном вольте записано полем `approved_in_source`, канонизация здесь — отдельный акт: `python3 ../metavault/tools/canonize.py . --list`, затем `--all --by tuvastamata --yes` или выборочно `--ids`.

Ссылки на страницы, оставшиеся в `road-to-emmaus` ([[Эммаус]], [[Незаслуженное короткого замыкания]], [[Расслышать зов Бытия]] и др.), — межвольтовые: приватный вольт ссылается на shared, это законное направление ([[CON-vault-sharing]]); обратных ссылок быть не должно.

Наполнение дальше — по базовым правилам: `sources/` → `statements/` → `concepts/` + `versions/`; линии в `lines/`, игры в `sandbox/`. `AGENTS.md` — производная, пересобирается компилятором.
