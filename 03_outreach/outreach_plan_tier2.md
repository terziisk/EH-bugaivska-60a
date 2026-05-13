# Outreach Plan — Tier 2

Дата підготовки: 2026-05-11
Готово до відправки: **15 пакетів** (з 20 в Tier 2 — 5 в hold-list, див. `contact_audit_tier2.md`)

## Універсальне collateral (загальний PDF)

`Фасад + склад на Дальницкой 1500кв.м..pdf` — 19 стор., 8 концепт-візуалізацій. **Прикладається до КОЖНОГО листа** Tier 2.

## Додаткові категоріальні рендери

Файли вже є в `03_outreach/missing_renders/` (зроблено для Tier 1). Оператор підкладає JPG, якщо у компанії ніша:

| Категоріальний рендер | Компанії Tier 2, для яких використати |
|---|---|
| `defense_production.jpg` | Wild Hornets, Swarmer, UATAC |
| `bpo_office.jpg` | EPAM Одеса, Mindy Support, Adelina Call Center, GlobalLogic Одеса |
| `printing.jpg` | Артель, Gift-K, Фабрика реклами |
| `self_storage.jpg` | — (немає Tier 2 кандидатів) |

VIYAR, Comfy, E-Zoo, Bosch CS, Delavega — категоріальний рендер не підбираємо: для них достатньо PDF (там є меблеву / електроніку / зоо / автоформат концепти).

## Список пакетів Tier 2 (15)

Сортовано за скором з priority_matrix (вищий скор — раніше у хвилі).

| # | Компанія | Папка | Скор | Канал #1 (verified email) | Доп. рендер | Статус |
|---|---|---|---|---|---|---|
| 1 | SkyFall | tier2/skyfall/ | 18 | — | — | **HOLD** (див. audit) |
| 2 | Wild Hornets | tier2/wild-hornets/ | 17 | info@wildhornets.com | defense_production | готовий |
| 3 | Vyriy Industries | tier2/vyriy-industries/ | 17 | — | — | **HOLD** |
| 4 | VIYAR (ВіЯр) | tier2/viyar/ | 17 | office@viyar.ua | — (PDF: меблевий) | готовий |
| 5 | Фабрика реклами | tier2/fabrika-reklamy/ | 17 | fr@fr-od.com.ua | printing | готовий |
| 6 | EPAM Одеса | tier2/epam-odesa/ | 16 | info@epam.com | bpo_office | готовий |
| 7 | M-TAC | tier2/m-tac/ | 16 | — | — | **HOLD** |
| 8 | Comfy | tier2/comfy/ | 16 | info@comfy.ua | — (PDF: електроніка) | готовий |
| 9 | E-Zoo (Fozzy) | tier2/e-zoo/ | 16 | realty@fozzy.ua | — (PDF: зоомаркет можна) | готовий |
| 10 | Swarmer | tier2/swarmer/ | 16 | information@swarmer.tech | defense_production | готовий |
| 11 | Mindy Support | tier2/mindy-support/ | 15 | hello@mindy-support.com | bpo_office | готовий |
| 12 | DataArt | tier2/dataart/ | 15 | — | — | **HOLD** |
| 13 | Delavega | tier2/delavega/ | 15 | founder@delavega.ua | — (PDF: меблевий) | готовий |
| 14 | Артель | tier2/artel/ | 15 | print@artel.ua | printing | готовий |
| 15 | Gift-K | tier2/gift-k/ | 15 | gift-k@ukr.net | printing | готовий |
| 16 | UATAC | tier2/uatac/ | 15 | uatacteam@gmail.com | defense_production | готовий |
| 17 | Extremstyle | tier2/extremstyle/ | 14 | — | — | **HOLD** |
| 18 | Adelina Call Center | tier2/adelina-call-center/ | 13 | sales@adelinacallcenter.com | bpo_office | готовий |
| 19 | Bosch Car Service | tier2/bosch-car-service/ | 13 | Konstantin.Klyahin@ua.bosch.com | — (PDF: автосалон) | готовий |
| 20 | GlobalLogic Одеса | tier2/globallogic-odesa/ | 13 | pr@globallogic.com | bpo_office | готовий |

## Hold-list (5) — лист НЕ відправляється до пошуку email

| Компанія | Папка | Що шукати | Де шукати |
|---|---|---|---|
| **SkyFall** | tier2/skyfall/ | Verified email відділу розвитку / директора Краєвського | skyfall.com.ua → /contacts; Brave1 Marketplace профіль; defencecity.gov.ua (SkyFall — перший резидент); media@brave1.gov.ua з проханням передати контакт |
| **Vyriy Industries** | tier2/vyriy-industries/ | Verified email (сайт vyriy.com на момент audit повертав 403) | vyriy.com → повторити, перевірити /contact / footer; LinkedIn vyriy-drone → «Contact»; Brave1 Marketplace; FB vyriy.drone → «Про» / Page Transparency |
| **M-TAC** | tier2/m-tac/ | Verified email засновника Карасьова / маркетинг-директора Донченка / відділу розвитку | mtac.ua → Contact / About / Footer; mtac.eu європейський сайт → footer; youcontrol.com.ua ЄДРПОУ «М-ТАС» — реєстраційні контакти; LinkedIn-пости Карасьова |
| **DataArt** | tier2/dataart/ | Verified email одеського R&D / Head of Office Сильчука (без розрахункових!) | dataart.com/about/offices/odesa → footer; it-family.od.ua сторінка DataArt — можливо є office@odesa.dataart.com; підпис у листі від співробітників (DOU, lun) |
| **Extremstyle** | tier2/extremstyle/ | Будь-який verified email (info@, sales@, відділу розвитку) | extremstyle.ua/ua/site/page/kontakti → **відкрити вручну** в браузері (сайт повертає 403 на auto-запити); footer головної; FB → «Про» / «Page Transparency»; дзвінок на 0-800-33-76-72 |

**Цикл пошуку для HOLD:** 1–2 дні. Якщо email знайдено — додати до `profile.md` (секція «Контакти» + джерело + дата), і запустити `/generate-outreach tier2` ще раз — буде згенеровано лист тільки для цієї компанії.

## Що повинен зробити оператор перед відправкою

Для кожної папки `02_priority/tier2/<slug>/` зі статусом «готовий»:

1. **Відкрити `letter_uk.md`**, перевірити hook на актуальність (новини компанії можуть бути свіжіші за профіль).
2. **Контакт отримувача** уже зафіксовано в `letter_uk.md` (чек-лист внизу, Канал #1) — це **verified email**.
3. **Сформувати вкладення:**
   - **Обов'язково:** `Фасад + склад на Дальницкой 1500кв.м..pdf`
   - **За потреби:** категоріальний рендер з `03_outreach/missing_renders/` (див. колонку «Доп. рендер» у таблиці вище).
4. **Відправити ТІЛЬКИ email** (LinkedIn / FB / IG / Telegram не використовуємо — у нас немає прокачаних корпоративних профілів, холодний лист з порожнього акаунту не читається).
5. **Зафіксувати в `03_outreach/sent_log.csv`:** `<дата>;<компанія>;<канал>;<контакт>;<статус>`.

## Послідовність відправки (рекомендована)

**Хвиля 1 (день 1–3) — скор 16–17, defense/виробництво + локальні з прямим каналом (6 листів):**
1. Wild Hornets (defense, 17) — info@wildhornets.com + defense_production.jpg
2. VIYAR (furniture, 17) — office@viyar.ua
3. Фабрика реклами (printing, 17) — fr@fr-od.com.ua + printing.jpg
4. Delavega (furniture, 15) — founder@delavega.ua **← найбільш «теплий» прямий канал**
5. Swarmer (defense, 16) — information@swarmer.tech + defense_production.jpg
6. E-Zoo (pet, 16) — realty@fozzy.ua

**Хвиля 2 (день 4–6) — IT/BPO (4 листи):**
7. EPAM Одеса (IT, 16) — info@epam.com + bpo_office.jpg
8. Comfy (electronics, 16) — info@comfy.ua
9. Mindy Support (BPO, 15) — hello@mindy-support.com + bpo_office.jpg
10. GlobalLogic Одеса (IT, 13) — pr@globallogic.com + bpo_office.jpg

**Хвиля 3 (день 7–10) — локальні виробники + інші:**
11. Артель (printing, 15) — print@artel.ua + printing.jpg
12. Gift-K (printing, 15) — gift-k@ukr.net + printing.jpg
13. UATAC (tactical, 15) — uatacteam@gmail.com + defense_production.jpg
14. Adelina (BPO, 13) — sales@adelinacallcenter.com + bpo_office.jpg
15. Bosch Car Service (auto, 13) — Konstantin.Klyahin@ua.bosch.com

## Follow-up

Через **7 днів** на неотриманні відповіді — коротке follow-up письмо (англомовний еквівалент шаблону Tier 1):
> «Шановні пані та панове, чи встигли подивитися матеріали, які я надсилала тиждень тому щодо приміщення 1500 м² на Дальницькій, 48 в Одесі? Готові на огляд у зручний для вас час. З повагою, Тетяна»

Через **14 днів** без відповіді на основний verified email — спроба на **резервний verified** (де він є; розрахункові адреси НЕ використовуємо):
- VIYAR → перевірити, чи з'явився інший verified email на сайті (не використовувати LinkedIn).
- Comfy → перевірити, чи з'явилася публічна адреса leasing/development.
- EPAM → перевірити, чи з'явився відомий email конкретно Бабейко.

**LinkedIn fallback — НЕ використовується** (правило з letter-writer.md після зворотного зв'язку власника від 2026-05-11).

## Hold-list — алгоритм follow-up

Якщо за 2 дні оператор не зміг знайти verified email для компанії з hold-list — повертаємо в `research-companies` через окрему задачу:

> «Прохання провести повторний прохід по [Компанія] з фокусом на пошук verified email відділу розвитку / партнерств. Перевірити: новий сайт (якщо у нас фіксувалося 403), LinkedIn-профіль ЛПР, нові публічні згадки в медіа (2026), реєстрові джерела (YouControl, Opendatabot). Якщо email не знайдено — позначити в profile.md як остаточно недоступний для email-каналу, перенести в Tier 3.»

---

*Документ підготовлено `/generate-outreach tier2` на 2026-05-11. Жодних правок цього файлу руками — все генерується через команду.*
