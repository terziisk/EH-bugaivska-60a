# Phase 3 — runtime-прогресс (для продолжения в новой сессии)

> **Дата создания:** 2026-05-07. Phase 3 ещё **не закрыта** (`CURRENT_PHASE.md` = `phase_3`).
> Этот файл — служебный, для самопередачи между сессиями.

---

## Что уже готово (32 профиля)

Лежат в `01_research/phase2_companies/by_company/`. Все имеют YAML-frontmatter с `fit_score_1_to_10`, контактами и разделом «Контактна стратегія».

**Batch 1 (10):** foxtrot, comfy, avdtrade, jysk, rozetka, vianor, autobaza-avtozvuk, elit-ukraine, bosch-car-service, masterzoo

**Batch 2 (10):** e-zoo, suziria-distribution, flagman, extremstyle, veloplaneta, helpware-odesa, sigma-software, dataart, infopulse, adelina-call-center

**Batch 3 (11):** epam-odesa, swarmer, ciklum, intellias, miratech, telesens, mindy-support, globallogic-odesa, supportyourapp, taf-industries, m-tac

**Бонус (1):** sts-gear — собрано инициативно одним из агентов Batch 3 (вероятно, M-TAC или TAF Industries увидел STS как смежного игрока). Fit 3/10. **Из Batch 4 теперь исключить — уже сделано.**

---

## ⚠️ КРИТИЧЕСКОЕ ПРАВИЛО для следующей сессии

**Запускай company-researcher только в foreground** (без `run_in_background: true`). 

В Batch 2 первая попытка была в background — task harness прибил все 10 агентов во время паузы в диалоге. `TaskOutput` показал «No task found», ни одного `.md` создано не было. Перезапуск в foreground решил проблему — все 10 завершились в активной сессии за ~5 минут.

Параллельность 10–11 агентов foreground одним сообщением — рабочая, проверена 3 раза.

---

## Что осталось (Batch 4–8, 45 компаний)

Ниже полный список. Slug = имя файла в `by_company/`. Контекст-строки см. в `niches_master.md` и в `00_object/object_specification.md`.

### Batch 4 — Tactical/Defense (10) — STS уже готов!

| # | Компания | Slug | Ниша | Сценарий | Фит из niches | Контекст |
|---|---|---|---|---|---|---|
| 1 | TTX (ТТХ) | `ttx` | tactical | production | 5 | Производство в Запорожье (прифронт), мотив релокации высокий; стратегия PatchEra |
| 2 | Camotec | `camotec` | tactical/defense | production | 5 | HQ Одеса (вул. Вернадського, 54); відкрив флагман у Києві 12.2024; B2B-виробництво для зовнішніх замовників |
| 3 | UATAC | `uatac` | tactical | production | 4 | Нові колекції LEVEL 5 S.W.R.S., Multicam; колаборація з ukrarmor (бронесистема «Hром») |
| 4 | Wild Hornets | `wild-hornets` | defense | production | 4 | >10 000 FPV/місяць (03.2025); нові моделі-перехоплювачі Sting, Queen Hornets |
| 5 | Vyriy Industries | `vyriy-industries` | defense | production | 4 | $4M інвестицій; 100% укр. компоненти; прибуток $5M/міс |
| 6 | SkyFall (Vampire/Shrike) | `skyfall` | defense | production | 4 | Перший резидент Defence City (01.2026); переговори з Данією; 2,5 млн вильотів у 2025 |
| 7 | Velmet | `velmet` | tactical/defense | production | 3 | Власне виробництво форми, тактспорядження; B2B + роздріб; HQ Хмельницький |
| 8 | P1G / PROF1Group | `p1g-prof1group` | tactical | production | 3 | Засновано 2012; шиє в Україні; матеріали Cordura, Nomex, Kevlar; мережа магазинів |
| 9 | Momentum | `momentum` | tactical | production | 3 | Власне виробництво в Україні (Київ); тактичні штани, фліс, взуття 2025 |
| 10 | Tekstyl-Kontakt / TK-Style | `tekstyl-kontakt` | tactical | production | 3 | $15M інвестицій; перевезли фабрику з Польщі в Чернігів 04.2025; 13 заводів в групі |

### Batch 5 — Tactical/Defense + Print/Furniture (10)

| # | Компания | Slug | Ниша | Сценарий | Фит | Контекст |
|---|---|---|---|---|---|---|
| 1 | ukrarmor | `ukrarmor` | tactical | production | 3 | Власне виробництво + ритейл + ЗСУ/СБУ/СОС; 3000+ SKU; колаборація з UATAC |
| 2 | STB / Startwear | `stb-startwear` | tactical | production | 3 | Швейна фабрика тактспорядження за ТУ Міноборони; ISO 9001 |
| 3 | Kvertus (РЕБ) | `kvertus` | defense | production | 3 | Контракт з «Українська Броня» 2025; 47 сертифікованих продуктів |
| 4 | SkyCraft Systems | `skycraft-systems` | defense | production | 3 | B2B-постачання для ЗСУ; системи наведення для FPV |
| 5 | SkyLab UA | `skylab-ua` | defense | production | 3 | UGV Sirko-S1, мультикоптер Shoolika mk6 |
| 6 | UA Dynamics (Punisher) | `ua-dynamics-punisher` | defense | production | 3 | Ударний дрон Punisher — $50K/комплекс; держзамовлення ЗСУ |
| 7 | UFORCE / MAGURA | `uforce-magura` | defense | production | 3 | Морські дрони; Magura V7 збив 2 Су-30; статус «єдинорога» 2025 |
| 8 | New Media (Друкарня) | `new-media-drukarnya` | printing | production | **5** | Крупнейшая цифровая типография юга; **уже на Дальницкой 25/3** (500 м от объекта); MGI JetVarnish 3DS |
| 9 | Accord Import | `accord-import` | furniture | production | 4 | Будує 2-й завод за $14M; контракт з JYSK на €80M |
| 10 | Delavega | `delavega` | furniture | production | 4 | Одесская фабрика мягкой мебели; B2B (Wall Street Hotel, рестораны) |

### Batch 6 — Furniture + Printing (11)

| # | Компания | Slug | Ниша | Сценарий | Фит | Контекст |
|---|---|---|---|---|---|---|
| 1 | ВіЯр (VIYAR) | `viyar` | furniture | production | 4 | 20+ шоурумов; крупнейший шоурум Украины 4000+ м²; **склад уже на Дальницкой** |
| 2 | Артель | `artel` | printing | production | 4 | 1 производство в Одессе с 1998+; нем./яп. парк (RICOH PRO C 9200, INCA HP UV) |
| 3 | Gift-K | `gift-k` | printing | production | 4 | 5 региональных офисов, 44 сотрудника; брендированная упаковка; 2 адреса в Одессе |
| 4 | Фабрика реклами | `fabrika-reklamy` | printing | production | 4 | 20+ лет, лидер сегмента в Одессе, штат утроился; полный цикл (сварка + печать + фрезеровка + монтаж) |
| 5 | LIOS (Ліос) | `lios` | furniture | production | 3 | 3 шоурума: Київ, Дніпро, Одеса (МГ «Шостий елемент»); фабрика м'яких меблів |
| 6 | KRONAS | `kronas` | furniture | production | 3 | 9 подразделений; 27 лет; **уже на Дальницкой 39** (рядом с объектом!) |
| 7 | Ocean Group | `ocean-group` | furniture | production | 3 | Одесский производитель корпусной мебели; B2B (отели, рестораны, офисы) |
| 8 | Colorit Мебель | `colorit-mebel` | furniture | production | 3 | 20+ лет в Одессе; кухни, шкафы-купе, гардеробные на заказ |
| 9 | Embawood | `embawood` | furniture | production | 3 | 9 заводов в 5 странах; продажи через Епіцентр; расширение дилерской сети |
| 10 | Світ Меблів | `svit-mebliv` | furniture | production | 3 | Завод 9+ га в Черкасской обл.; 3 цеха; экспорт в Грузию, Балтию, Болгарию |
| 11 | Студія Печать | `studio-pechat` | printing | production | 3 | 2 адреса в Одессе с 2008; упаковка, вывески, стенды; обновляет парк оборудования |

### Batch 7 — Printing + Food + Warehouse (11)

| # | Компания | Slug | Ниша | Сценарий | Фит | Контекст |
|---|---|---|---|---|---|---|
| 1 | Інтегра (типография) | `integra` | printing | production | 3 | 10+ лет в Одессе; УФ-печать, лазерная резка, печать на тканях |
| 2 | Lucky Print (LPR) | `lucky-print-lpr` | printing | production | 3 | Лидер промо-продукции в Украине; собственная технология производства бейджей |
| 3 | Simex Print | `simex-print` | printing | production | 3 | Одесса (**Дальницкая 53 — рядом!**); офсет + цифра, Xerox D95 + Versant 180 |
| 4 | РВК Арт-Лайт | `rvk-art-light` | printing | production | 3 | Производство наружной рекламы с 2007; LED-конструкции, баннеры до 2000 м² |
| 5 | РС АБРИС М | `rs-abris-m` | printing | production | 3 | 25+ лет в Одессе; вакуумное формование, LED-панели, ценовые стелы для АЗС |
| 6 | Lukas (ВТК Лукас) | `lukas` | food_b2b | production | 3 | Виторг 2,1 млрд грн; экспорт в Швецию, Ирак, Прибалтику; листкове тісто, круасани |
| 7 | Frozenfood UA | `frozenfood-ua` | food_b2b | production | 3 | B2B-дистрибьютор замороженных кондитерских изделий для HoReCa |
| 8 | MySmak | `mysmak` | food_b2b | production | 3 | Сеть столовых под ключ + корпоративное питание; франшизная модель |
| 9 | TetrisBOX | `tetrisbox` | self_storage | warehouse_b2b | **5** | 4+ города (Киев, Львов, Ивано-Франковск, Одесса); новый склад во Львове 2025 |
| 10 | MyBox | `mybox` | self_storage / 3pl | warehouse_b2b | 4 | 10+ точек в Киеве + 1 в Одессе |
| 11 | OMNI-LOGISTIC | `omni-logistic` | 3pl | warehouse_b2b | 3 | Lite-fulfilment с присутствием в Одессе; модель без высоких стеллажей |

### Batch 8 — Final (4)

| # | Компания | Slug | Ниша | Сценарий | Фит | Контекст |
|---|---|---|---|---|---|---|
| 1 | Grand Distribution | `grand-distribution` | 3pl | warehouse_b2b | 3 | Крупнейший FMCG-дистрибьютор; объединяет региональных игроков; Одесса — стратегический хаб |
| 2 | KOMORA | `komora` | self_storage | warehouse_b2b | 3 | Активно расширяется (Киев+Львов); планы 1000 м² во Львове; Одесса — логичный 3-й город |
| 3 | Into-Sana | `into-sana` | medical | mixed | 3 | 10 МЦ + 5 диагностических в Одессе и Киеве; куплена инвестфондом Siguler Guff; новый МЦ на Філатова, 2 |
| 4 | Oxford Medical | `oxford-medical` | medical | mixed | 3 | 50 МЦ в 19 городах (UBA 2025 — крупнейшая сеть); в 2025 открыли МЦ на Русанівській Гавані Київ |

---

## Сегменты, которые НЕ ресерчим как отдельные компании (передать в companies_master напрямую)

Из решения LOG: эти три «компании» из niches_master — это **каналы/сегменты**, не отдельные арендаторы. Обработать на этапе сводного отчёта.

- **Релоканти-інжиніринг з Харкова, Запоріжжя, Миколаєва** (фит 5, reloc) — outreach через Дія.Бізнес, ТПП регионов, программу Минэкономики.
- **Региональная B2B-пекарня (5–10 одесских пекарен)** (фит 4, food_b2b) — outreach через METRO HoReCa-менеджера.
- **Производители полуфабрикатов** (фит 4, food_b2b) — outreach через дистрибуцию HoReCa.

---

## ТОП-кандидаты по результатам Batch 1–3 (для приоритизации в Phase 4)

Эти ребята должны попасть в Tier 1 без дополнительной валидации (фит и/или сильные контакты подтверждены).

1. **TAF Industries** — fit 9/10. Подтверждённая боль с арендодателями, основатель одессит, контакты `partnerships@taf-ua.com` + Yakovenko LinkedIn.
2. **MasterZoo** — прямой канал через эксклюзивного агента RDA: `a_abramtseva@rda.ua`. В Одессе нет флагмана 500+ м² — точная лакуна.
3. **Helpware** — fit 7/10. Уже есть backup-офис в Одессе. `hello@helpware.com` + Yehor Bielikov (VP Bus.Ops EMEA).
4. **JYSK** — `expansionua@jysk.com` (официальный канал) + Country Director + Development Manager (LinkedIn). Hooks: терраса 1028 м², глобальный city-stores формат май 2026.
5. **EPAM Одесса** — fit 6/10. Текущий офис на 120 мест перевантажений; нужен апгрейд. Ганенко (LinkedIn) + Бабейко (новая GM Ukraine).
6. **Foxtrot** — формат email подтверждён, ключевой Шургот; есть прямой прецедент (стрит-флагман в Днепре).
7. **AVDtrade** — `sale@avdtrade.com.ua` + Дудинець. В Одессе у них филиала нет — лакуна.
8. **AutoBaza** — `pr@avtozvuk.ua`. Hook: трассовый флагман на Колоса 177 (Киев) как прямой аналог Дальницкой.
9. **Comfy** — окно: Тетяна Лахтадир, новая Голова розвитку мережі с 27.04.2026. Pitch — drive-through digital flagship по образцу White Lines.
10. **ELIT-Україна** — `odessa@elit.ua` + Олександр Васюта (BD Director).
11. **Bosch Car Service** — нестандартный канал: pitch на пул из 100+ Bosch-партнёров под формат «магазин+склад без ремпостов» (потолки блокируют подъёмники).

## Кандидаты, которых ресерч пересмотрел вниз (НЕ в Tier 1)

- **Rozetka** — fit 2/10. Стратегия с 2024: «закрываем флагманы → плодим мелкие пункты», прямо противоречит формату.
- **Ciklum** — fit 2/10. Одесский офис фактически закрыт с 2024.
- **Telesens** — fit 2/10. Стагнация с 2022, всего 24 сотрудника, Telesens Ventures — арендодатель.
- **Infopulse** — компания **больше не существует** под этим именем. Реинтегрирована в Tietoevry Create Ukraine с 06.2025.
- **Vianor** — критическое ограничение: потолки 2,8–3,0 м не подходят под стандартные подъёмники.

---

## Шаги для следующей сессии

1. Прочитать `@CURRENT_PHASE.md` (= phase_3), `@PLAN.md`, последние записи `@LOG.md`, и **этот файл целиком**.
2. Подтвердить пользователю статус (32 профиля готовы из 77+ запланированных, осталось 45) — ждать «ок, продолжаем».
3. Запустить **Batch 4 в foreground** (10 компаний из таблицы выше). НЕ background.
4. Потом Batch 5, 6, 7, 8 (тоже foreground, по 10–11 параллельно одним сообщением).
5. После всех — собрать `01_research/phase2_companies/companies_master.md` по шаблону из `.claude/commands/research-companies.md`.
6. Обновить `LOG.md` финальной записью Phase 3.
7. Переключить `CURRENT_PHASE.md` → `phase_4`.

---

*Документ актуален на 2026-05-07 ~16:30 локального времени. После запуска Batch 4 — обновить.*
