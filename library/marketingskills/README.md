# Справочная библиотека SEO/GEO

Три скилла из [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (коммит `365b412`, 15.10.2026, лицензия MIT — см. `LICENSE`): `ai-seo`, `schema`, `seo-audit`. Скопированы без изменений, без папок `evals`.

Это справочник, а не автоматически подключаемые скиллы: папка намеренно лежит вне `.agents/skills/` и `.claude/skills/`, чтобы они не запускались сами и не задавали вопросы аудита существующего сайта. Порядок работы задают `../../rules/SEO_GEO.md` и `../../prompts/SEO_GEO.md`; оттуда сюда отправляют за деталями.

Скиллы написаны для действующих сайтов на английском. Для нового сайта пропускай разделы аудита видимости, мониторинга и сторонних площадок, а файл `.agents/product-marketing.md`, о котором они упоминают, заменяет `PROJECT.md` активного проекта.

Полезное для нового сайта:

- `ai-seo/SKILL.md` — разделы Optimization Strategy (три опоры), Machine-Readable Files, What NOT to Do
- `ai-seo/references/content-patterns.md` — шаблоны блоков-ответов: определение, шаги, сравнение, FAQ
- `ai-seo/references/content-types.md` — особенности локального бизнеса, товаров, услуг
- `ai-seo/references/agent-readiness.md` — доступ ИИ-краулеров, robots.txt, llms.txt
- `schema/SKILL.md` и `schema/references/schema-examples.md` — JSON-LD
- `seo-audit/SKILL.md`, `seo-audit/references/title-tags.md`, `seo-audit/references/local-seo.md` — on-page и локальное SEO
