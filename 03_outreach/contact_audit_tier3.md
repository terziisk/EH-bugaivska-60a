# Contact Audit — Tier 3 (підгрупа 3D long-shot)

> Дата: 2026-05-13. Об'єкт: Дальницька 48 / Бугаївська 60А.
>
> Шаг 0 валідації згідно з `.claude/commands/generate-outreach.md`.
> Скоп: **28 компаній** з підгрупи 3D long-shot (за `priority_matrix.md`).
> Підгрупи 3A (сусіди), 3B (техблокери), 3C (принципові блокери) — **не входять**
> у цей раунд outreach.

## Підсумок

| Група | К-сть | Дія |
|---|---|---|
| ✅ READY | **23** | `letter-writer` запускається з verified email Канал #1 |
| ⏸ HOLD | **4** | Лист НЕ генерується — оператор шукає verified email |
| ⛔ BLOCKED | **1** | Виключається з раунду до юр.перевірки |

---

## ✅ READY (23) — verified email, готові до генерації

| # | Slug | Ніша | Verified email (Канал #1) | Резервний email |
|---|---|---|---|---|
| 1 | `autobaza-avtozvuk` | auto retail | **pr@avtozvuk.ua** | HR@avtozvuk.ua |
| 2 | `elit-ukraine` | auto distrib | **elit@elit.ua** | odessa@elit.ua |
| 3 | `suziria-distribution` | pet 3PL | **feedback@suziria.ua** | odesa@suziria.ua |
| 4 | `lios` | furniture | **lios@email.ua** | — |
| 5 | `ocean-group` | furniture | **dir@ocean-group.od.ua** | — |
| 6 | `colorit-mebel` | furniture | **info@colorit-mebel.od.ua** | — |
| 7 | `svit-mebliv` | furniture | **info.svitmebliv.uman@gmail.com** | sekretar150292@gmail.com |
| 8 | `rs-abris-m` | outdoor adv | **reklama@abris-m.od.ua** | — |
| 9 | `studio-pechat` | printing | **info@pechat.od.ua** | pechat.office@gmail.com |
| 10 | `sigma-software` | IT/office | **odesa@sigma.software** | info@sigma.software |
| 11 | `miratech` | IT/office | **hr@miratech.ua** | — |
| 12 | `supportyourapp` | BPO | **hi@supportyourapp.com** | pr@supportyourapp.com |
| 13 | `velmet` | tactical | **armor@velmet.ua** | info@velmet.ua |
| 14 | `momentum` | tactical | **info@momentum.in.ua** | opt.momentum@gmail.com |
| 15 | `ukrarmor` | tactical | **info@ukrarmor.com.ua** | — |
| 16 | `sts-gear` | tactical | **prom@sts-gear.com** | ststactic1@gmail.com |
| 17 | `skycraft-systems` | defense_drones | **info@skycraftua.com** | systemzir@gmail.com |
| 18 | `skylab-ua` | defense_drones | **info@skylab-ua.com** | — |
| 19 | `ua-dynamics-punisher` | defense_drones | **info@uadynamics.com** | — |
| 20 | `mysmak` | food_b2b | **info@mysmak.com.ua** | info@mycmak.com (опечатка на сайті — дублювати) |
| 21 | `grand-distribution` | 3PL/FMCG | **office@gd-group.com.ua** | personal@gd-group.com.ua |
| 22 | `mybox` | self-storage | **mybox.sklad@gmail.com** | — |
| 23 | `komora` | self-storage | **komora4u@gmail.com** | komora31storage@gmail.com |

### Примітка по defense-кластеру в READY

5 defense/tactical компаній (velmet, momentum, ukrarmor, sts-gear, skycraft-systems,
skylab-ua, ua-dynamics-punisher) мають публічно підтверджені generic-email на сайті —
це **дозволений канал** за нашими правилами. На відміну від `kvertus` (HOLD), у цих
компаній email-канал відкритий публічно і вживається для B2B-запитів.

---

## ⏸ HOLD (4) — verified email відсутній

| # | Slug | Чого бракує | Де оператору шукати |
|---|---|---|---|
| 1 | `veloplaneta` | Лише маскований `z***@veloplaneta.com.ua` (ZoomInfo) | [veloplaneta.ua/contacts](https://veloplaneta.ua/) — головна / Contacts; може бути generic info@/sales@ |
| 2 | `intellias` | Лише реконструйовані за шаблоном `first.last@intellias.com` (заборонені правилами) | [intellias.com/contact-us](https://intellias.com/contact-us/) — generic info@ / hr@; LinkedIn Odesa lead |
| 3 | `kvertus` | Лише LinkedIn CEO/Founder + форма на сайті (нема publicного email); по правилам — LinkedIn не використовуємо | [kvertus.ua](https://kvertus.ua/) — Contacts; форма заборонена правилами outreach; реальний канал — Brave1 нетворк (не email) |
| 4 | `lukas` | Регіональні email є (chernovtsy@, lvov@, kharkov@…), але **для Одеської області email відсутній**; основний `info@lukas.ua` публічно не підтверджено | [lukas.ua/en/contact-us](https://lukas.ua/en/contact-us/) — пошукати info@/office@; франшизний канал [franchise.lukas.ua](https://franchise.lukas.ua) |

### Якщо оператор знайде email — додати в `profile.md` → розділ Контакти, потім запустити `/generate-outreach tier3` повторно (агент створить лист тільки для нових READY).

---

## ⛔ BLOCKED (1) — виключено з раунду

| Slug | Причина | Що потрібно для розблокування |
|---|---|---|
| `embawood` | У `priority_matrix.md` явно зазначено: **34% власник — громадянка РФ — перевірити санкції перед outreach**. Юр.перевірка не зроблена. Окрім того, `magazin@verita.com.ua` — це дистрибьютор, не сам Embawood. | Юр.чек: чи дозволено комерційні відносини; якщо так — окремий outreach на дистрибьютор, а не на Embawood напряму |

---

## Що далі

1. **Генеруємо 23 листи** через `letter-writer` (батчами 4–6, foreground, як у Tier 2)
2. **Створюємо** `03_outreach/outreach_plan_tier3.md` зі списком пакетів і hold-list
3. **CURRENT_PHASE.md не змінюється** — лишаємось у `phase_6`
