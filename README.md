# vault-philosophy — богословие и философия

Рабочий вольт, привязанный к метавольту (`_meta/BINDING.md`, профиль `core`, язык русский, принимаемый эстонский). Здесь живут внешние концепты (рефераты чужих идей с первоисточником) и собственные, рождённые в обсуждениях. Точка входа — [[00 Карта философии]].

Схема полей — ядро v2 (`../metavault/_meta/context.jsonld`): тела всех узлов перенесены из v1 байт в байт, изменился только frontmatter (2026-09-09). Обсуждение и применения концепта не ведутся списками — это обратные ссылки (панель Obsidian, Bases).

- `lines/` — три линии: [[LINE-pain-of-thou]], [[LINE-incest-power]], [[LINE-psychotic-orthodoxy]].
- `sources/` — беседа «Церковь и страдание» 10.05.2026 с транскриптом, рукописная заметка «Власть» 27.08.2026 со сканом, текстовые сессии 25.08 и 27.08.
- `statements/` — тезисы Андрея, разбор-кейс агента, отчёты ingest (`fed_kind: report`).
- `persons/` — [[PER-kireev]], [[PER-hilarion]], [[PER-eoc-mp]].
- `concepts/` + `versions/` — 14 концептов с телами v1; `translations/` — 18 эстонских пар.

Правила — в метавольте; свод `metavault/AGENTS.md` производный (`python3 metavault/tools/fed.py compile --federation .` из корня федерации), в вольте свода нет; проверка — `python3 metavault/tools/fed.py lint vault-philosophy --federation .`.
