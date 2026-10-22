# Іконки гравця (BIG-40, «Профіль» → «Оформлення» → «Іконка»): джерела, ліцензії, доступ

Одна сутність «Іконка» (колишні 7 «значків» прибрано): показується **в чаті біля повідомлень** (iconURL) і **в колі картки гравця** —
«Профіль», привітання на Головній, рейтинг сезону, «Так виглядатимеш» у «Буржуях». «Стандартна» (none) — Steam-аватарка в чаті, сіра заглушка на картці.
Файли — `potuzhnyi-icons/avatars/<id>.png` (назва теки історична): 256×256 PNG, коло з прозорими кутами, ≤ 40 КБ (quantize).
Збірка: рендери гри `-executeMethod PotuzhnyiAvatars.Render` → `tools/make_avatars.py` (коло з палітри, кроп фото, quantize).
Доступ — `StyleService.Avatars` у KozakCore = `KozakTheme.StyleAvatars` у моді (той самий порядок; вищий статус бачить і всі нижчі порції).

**Атрибуція в UI не потрібна:** ліцензія Unsplash її не вимагає (авторів вказуємо тут з поваги); Noto Emoji — Apache-2.0 (README: зображення) / OFL-1.1 (`LICENSE`), копія — `potuzhnyi-icons/avatars/LICENSE-noto-emoji.txt`.
Копірайтних мем-шаблонів (Doge, Pepe, кадри з фільмів) немає.

## Драбина доступу (62 + стандартна)

| Tier | Статус | Скільки | Що |
|---|---|---|---|
| 0 | без статусу | 8 | плоскі емодзі: e_cool, e_frog, e_duck, e_cat, e_nerd, e_cold, e_pig, e_salute |
| 1 | Ґазда (silver) | 8 | емодзі: e_clown, e_cowboy, e_disguise, e_alien, e_melt, e_goat, e_skull, e_fire |
| 2 | Куркуль (gold) | 8 | e_pinch, e_troll, e_devil + тварини гри: animal_cow, animal_pig, animal_deer, animal_bear, animal_wolf |
| 3 | Підпанок (platinum) | 8 | animal_moose + портрети гри: chef, bucket, carrot, cinema, chemist, mime, pirate |
| 4 | Пан (vip) | 8 | портрети гри: sombrero, pineapple, squid, snowman, robot, pumpkin, fishbowl, tiki |
| 5 | Шляхтич (diamond) | 8 | yeti, viking, raider, stalker, jester + фото: p_capy, p_cat, p_frog |
| 6 | Магнат (titan) | 7 | фото: p_goose, p_dog_shades, p_dog_glam, p_goose_white, p_llama, p_pug_tongue, p_dog_beach |
| 7 | Олігарх (ruby) | 7 | p_pug + рідкісні: hutsul, burzhui, king, moai (рендери гри), e_moai 🗿, e_money 🤑 |

## 1. Рендери гри (30) — власні рендери ассетів Unturned (`core.masterbundle`), як решта графіки сервера
Портрети в шапках/масках гри + худі гри; тварини гри цілим тілом. id: chef, bucket, carrot, cinema, chemist, pirate, mime, sombrero, pineapple, squid,
snowman, robot, pumpkin, raider, fishbowl, tiki, yeti, viking, stalker, jester, hutsul, burzhui, king, moai, animal_cow/pig/deer/bear/wolf/moose. Tier — у таблиці вище.

## 2. Noto Emoji 3D (21) — Google, `googlefonts/noto-emoji`, `3D/png/512` (завантажено 2026-10-22)
Джерело: `https://raw.githubusercontent.com/googlefonts/noto-emoji/main/3D/png/512/emoji_u<код>.png`.

| Файл | Емодзі | Код | Tier |
|---|---|---|---|
| e_cool | 😎 | 1f60e | 0 |
| e_frog | 🐸 | 1f438 | 0 |
| e_duck | 🦆 | 1f986 | 0 |
| e_cat | 😼 | 1f63c | 0 |
| e_nerd | 🤓 | 1f913 | 0 |
| e_cold | 🥶 | 1f976 | 0 |
| e_pig | 🐷 | 1f437 | 0 |
| e_salute | 🫡 | 1fae1 | 0 |
| e_clown | 🤡 | 1f921 | 1 |
| e_cowboy | 🤠 | 1f920 | 1 |
| e_disguise | 🥸 | 1f978 | 1 |
| e_alien | 👽 | 1f47d | 1 |
| e_melt | 🫠 | 1fae0 | 1 |
| e_goat | 🐐 | 1f410 | 1 |
| e_skull | 💀 | 1f480 | 1 |
| e_fire | 🔥 | 1f525 | 1 |
| e_pinch | 🤌 | 1f90c | 2 |
| e_troll | 🧌 | 1f9cc | 2 |
| e_devil | 😈 | 1f608 | 2 |
| e_moai | 🗿 | 1f5ff | 7 |
| e_money | 🤑 | 1f911 | 7 |

## 3. Фото Unsplash (11) — Unsplash License (безкоштовно, комерційно, без обов'язкової атрибуції)
Завантаження зафіксоване через Unsplash API (download endpoint). Кроп — квадрат по морді, коло.

| Файл | Джерело | Автор | Tier |
|---|---|---|---|
| p_capy | https://unsplash.com/photos/oDsLyb_H92k | Hoyoun Lee | 5 |
| p_cat | https://unsplash.com/photos/IuJc2qh2TcA | Cédric VT | 5 |
| p_frog | https://unsplash.com/photos/EP_OHkgn1JI | Jack Hamilton | 5 |
| p_goose | https://unsplash.com/photos/bnJQxin8R7M | Joshua Ralph | 6 |
| p_dog_shades | https://unsplash.com/photos/ts1zXzsD7xc | Mollie Sivaram | 6 |
| p_dog_glam | https://unsplash.com/photos/q_FTiHRCeJo | wooof woof | 6 |
| p_goose_white | https://unsplash.com/photos/g_egdHwa5xk | Amit Talwar | 6 |
| p_llama | https://unsplash.com/photos/Fjn756Sj6bk | Tarryn Grignet | 6 |
| p_pug_tongue | https://unsplash.com/photos/85XqQOx4dyg | Osman Espinoza Franco | 6 |
| p_dog_beach | https://unsplash.com/photos/hhegBj6iJ5E | Mel Elías | 6 |
| p_pug | https://unsplash.com/photos/DziZIYOGAHc | charlesdeluvio | 7 |
