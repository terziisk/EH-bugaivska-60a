# Contact Audit — Tier 2

Дата: 2026-05-11
Всього компаній: 20
- **READY** (verified email знайдено): 15
- **HOLD** (потрібен пошук verified email оператором): 5
- **BLOCKED** (немає жодного каналу): 0

Правило `letter-writer.md` → «Канал для відправки — тільки verified email». Letter-writer запускається тільки для READY. HOLD-компанії — лист не генеруємо, оператор шукає email вручну.

---

## READY (15) — letter-writer запускається

| # | Компанія | Slug | Канал #1 (verified email) | Джерело верифікації |
|---|---|---|---|---|
| 1 | Wild Hornets | wild-hornets | info@wildhornets.com | Profile: «єдиний підтверджений email для нерекламних запитів» |
| 2 | VIYAR (ВіЯр) | viyar | office@viyar.ua | Корпоративний, з сайту viyar.ua |
| 3 | Фабрика реклами | fabrika-reklamy | fr@fr-od.com.ua | fr-od.com.ua/kontakty |
| 4 | EPAM Одеса | epam-odesa | info@epam.com | Публічно вказаний на сторінці контактів epam.com |
| 5 | Comfy | comfy | info@comfy.ua | comfy.ua/ua/contact.html |
| 6 | E-Zoo (Fozzy) | e-zoo | realty@fozzy.ua | fozzy.ua/en/contacts/ — публічний email відділу нерухомості Fozzy Group; контактна особа: **Mariia Savitskas** (Head of Real Estate) |
| 7 | Swarmer | swarmer | information@swarmer.tech | Загальний з сайту swarmer.tech |
| 8 | Mindy Support | mindy-support | hello@mindy-support.com | mindy-teams.com / outsourceaccelerator.com |
| 9 | Delavega | delavega | founder@delavega.ua | На сайті delavega.ua — окремий канал для прямого звернення до засновника |
| 10 | Артель (типографія) | artel | print@artel.ua | artel.ua/ru/kontakty/ |
| 11 | Gift-K | gift-k | gift-k@ukr.net | Загальний email з офіційного сайту |
| 12 | UATAC | uatac | uatacteam@gmail.com | uatac.com.ua — основний загальний канал |
| 13 | Adelina Call Center | adelina-call-center | sales@adelinacallcenter.com | Публічна generic-адреса B2B/партнерств |
| 14 | Bosch Car Service | bosch-car-service | Konstantin.Klyahin@ua.bosch.com | З розділу офіційних контактів Bosch Ukraine — менеджер Bosch Service (профільний) |
| 15 | GlobalLogic Одеса | globallogic-odesa | pr@globallogic.com | З публічної dev.ua-статті 2025 (media press) |

### Примітки до окремих READY

- **Bosch Car Service** — у профілі **також** є verified `info@ua.bosch.com` як резервний на випадок, якщо Klyahin не той менеджер. Перший контакт — на Klyahin (профільний), резервний — на info@.
- **GlobalLogic Одеса** — Канал #1 (pr@) це **media-press** контакт. Це verified, але потенційно «не той відділ». У темі листа явно вказати: «Прохання переадресувати до VP Operations / Facilities в Одесі». Резервний verified email — info@globallogic.com.
- **EPAM Одеса** — info@epam.com — глобальний загальний адрес EPAM. Лист буде маршрутизований централізованим support'ом. У темі явно вказати: «До GM Ukraine / Country Manager — пропозиція приміщення в Одесі».
- **Delavega** — founder@delavega.ua — це найбільш персональний прямий канал серед усіх READY. Лист читає засновник особисто (за стратегією у profile.md).
- **Mindy Support, Comfy, EPAM** — verified generic emails, не персональні. Виставити тему та звертання, які допоможуть листу пройти через фільтри support'у та потрапити до відповідального за expansion.

---

## HOLD (5) — лист не генеруємо, оператору шукати email

| # | Компанія | Slug | Що ШУКАТИ | Де шукати (конкретні URL) |
|---|---|---|---|---|
| 1 | SkyFall | skyfall | Verified прямий email відділу розвитку / партнерств / директора Сергія Краєвського | (1) skyfall.com.ua → перевірити /contacts, /partnerships, footer; (2) Brave1 Marketplace профіль skyfall — `brave1.gov.ua`; (3) Defense City — `defencecity.gov.ua` (SkyFall — перший резидент); (4) запит через media@brave1.gov.ua з проханням передати контакт |
| 2 | Vyriy Industries | vyriy-industries | Verified прямий email (сайт vyriy.com на момент аудита повертав 403) | (1) vyriy.com → повторити спробу зайти через ~1 тиждень або через VPN/інший браузер, перевірити /contact, /about, footer; (2) LinkedIn-сторінка [vyriy-drone](https://www.linkedin.com/company/vyriy-drone) → перевірити секцію «Contact»; (3) форма на Brave1 Marketplace — vyriy профіль; (4) FB [vyriy.drone](https://www.facebook.com/vyriy.drone/) → у «Про» / Page Transparency інколи бувають email-и |
| 3 | M-TAC | m-tac | Verified прямий email відділу розвитку / засновника Олександра Карасьова / маркетинг-директора Олексія Донченка | (1) mtac.ua → відкрити Contact / About / Footer (нинішня перевірка повертала лише форму, без email); (2) mtac.eu — європейський сайт, у footer'і часто є email; (3) ЄДРПОУ ТОВ «М-ТАС» — youcontrol.com.ua → реєстраційні контакти; (4) виставка LinkedIn-постів Карасьова: інколи у дописах є email-контакт для партнерств |
| 4 | DataArt | dataart | Verified прямий email одеського R&D центру / Head of Office Андрія Сильчука | (1) dataart.com/about/offices/odesa → footer, contacts; (2) it-family.od.ua сторінка DataArt → можливо є office@odesa.dataart.com або інший локальний email; (3) перевірити підпис у листі від андрій@... через будь-яку публічну переписку (DOU, lun) |
| 5 | Extremstyle | extremstyle | Будь-який verified email (загальний info@, sales@, або відділу розвитку) | (1) extremstyle.ua/ua/site/page/kontakti → **відкрити вручну в браузері** (сайт повертає 403 на автоматичні запити, але в браузері може показати email); (2) перевірити footer головної; (3) Facebook [extremstyle.ua](https://www.facebook.com/extremstyle.ua/) → секція «Про» / «Page Transparency»; (4) дзвінок на гарячу лінію 0-800-33-76-72 з проханням дати email відділу розвитку |

### Підказка для оператора по HOLD

- Цикл пошуку — **1–2 дні**. Якщо за цей час email не знаходиться — компанія повертається `research-companies` для повторного проходу (можливо, з'явились нові публічні джерела за останній тиждень).
- **НЕ використовувати «розрахункові» формати** типу `andrey.sylchuk@dataart.com` або `o.chornobryvtsev@adelinacallcenter.com` навіть якщо ZoomInfo підтвердив частково замаскований префікс. Половина таких листів іде в bounce; решта читається з мінусом довіри.
- Якщо знаходите email — додати в `profile.md` у секцію «Контакти» з підтверджуючим джерелом і датою, і повернутися до команди `/generate-outreach tier2`, щоб згенерувати лист для цієї компанії.

---

## BLOCKED (0)

Жодна компанія Tier 2 повністю не заблокована — у всіх є щонайменше LinkedIn-сторінка або форма. HOLD-компанії — це випадки, коли email потенційно знаходиться, але потрібен ручний крок оператора.

---

## Зауваження по якості Tier 2 списку

- **Defense-кластер** (SkyFall, Vyriy, Wild Hornets, Swarmer) — як і очікувалось, найбільш «закритий» сегмент. З 4 компаній лише 2 (Wild Hornets, Swarmer) мають verified email. SkyFall і Vyriy в HOLD.
- **IT-сегмент** (EPAM, GlobalLogic, DataArt, Mindy) — verified emails переважно generic, не персональні. Лист потрібно писати, припускаючи, що його прочитає support, а не ЛПР. Тема має зробити маршрутизацію очевидною.
- **Сегмент «локальні виробники» з прямим прямим email засновника** (Delavega, Артель, Gift-K, UATAC) — найбільш «теплі» цілі за каналом. Якщо першим відповідатимуть саме вони — це підтвердить гіпотезу, що для Tier 2 локальні виробники дають вищий response rate, ніж сітьові гіганти.

---

*Документ підготовлено в межах `/generate-outreach tier2` на 2026-05-11.*
