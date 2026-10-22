# Аватарки «Профілю» (BIG-40): джерела й ліцензії

Усі файли — 256×256 PNG, коло з прозорими кутами, ≤ 40 КБ (quantize). Хостинг: `https://alexanderborysenko.github.io/potuzhnyi-icons/avatars/<id>.png`.
Збірка: рендери гри `-executeMethod PotuzhnyiAvatars.Render` (`mod/unity/Build/Avatars`) + скрипт композиції (коло з палітри, кроп фото, quantize) — див. рядок у `docs/gotchas.md` / `docs/STATE.md`.
Доступ (tier) — `StyleService.Avatars` у KozakCore = `KozakTheme.StyleAvatars` у моді.

**Атрибуція в UI не потрібна:** ліцензія Unsplash її не вимагає (вказуємо авторів тут з поваги), Noto Emoji — Apache-2.0 / OFL-1.1 (копія ліцензії — `potuzhnyi-icons/avatars/LICENSE-noto-emoji.txt`, нотис — цей файл).
Копірайтних мем-шаблонів (Doge, Pepe, кадри з фільмів) немає.

## 1. Рендери гри (30) — власні рендери ассетів Unturned (`core.masterbundle`), як решта графіки сервера

| Файл | Що | Tier |
|---|---|---|
| chef, bucket, carrot, cinema, chemist, pirate, mime | портрет у шапці/масці гри + худі | 0 |
| animal_cow, animal_pig, animal_deer | тварини гри | 0 |
| sombrero, pineapple, squid, snowman, robot, pumpkin, raider, fishbowl, tiki, yeti, viking | портрет | 2 (Куркуль) |
| animal_bear, animal_wolf, animal_moose | тварини гри | 2 |
| stalker, jester, hutsul | портрет | 5 (Шляхтич) |
| burzhui, king, moai | портрет | 7 (Олігарх) |

## 2. Noto Emoji 3D (21) — Google, `googlefonts/noto-emoji`, тека `3D/png/512`

Ліцензія: README репозиторію — «tools and most image resources are under Apache license 2.0», файл `LICENSE` — SIL OFL 1.1. Обидві дозволяють використання й зміни; атрибуція в UI не обов'язкова.
Джерело: `https://raw.githubusercontent.com/googlefonts/noto-emoji/main/3D/png/512/emoji_u<код>.png` (завантажено 2026-10-22).

| Файл | Емодзі | Код | Tier |
|---|---|---|---|
| e_cool | 😎 | 1f60e | 0 |
| e_frog | 🐸 | 1f438 | 0 |
| e_duck | 🦆 | 1f986 | 0 |
| e_cat | 😼 | 1f63c | 0 |
| e_nerd | 🤓 | 1f913 | 0 |
| e_cold | 🥶 | 1f976 | 0 |
| e_pig | 🐷 | 1f437 | 0 |
| e_clown | 🤡 | 1f921 | 2 |
| e_cowboy | 🤠 | 1f920 | 2 |
| e_disguise | 🥸 | 1f978 | 2 |
| e_salute | 🫡 | 1fae1 | 2 |
| e_alien | 👽 | 1f47d | 2 |
| e_melt | 🫠 | 1fae0 | 2 |
| e_goat | 🐐 | 1f410 | 2 |
| e_skull | 💀 | 1f480 | 5 |
| e_pinch | 🤌 | 1f90c | 5 |
| e_fire | 🔥 | 1f525 | 5 |
| e_troll | 🧌 | 1f9cc | 5 |
| e_devil | 😈 | 1f608 | 5 |
| e_moai | 🗿 | 1f5ff | 7 |
| e_money | 🤑 | 1f911 | 7 |

## 3. Фото Unsplash (11) — Unsplash License (безкоштовно, комерційно, без обов'язкової атрибуції)

Завантаження зафіксоване через Unsplash API (download endpoint). Кроп — квадрат по морді, коло.

| Файл | Джерело | Автор | Tier |
|---|---|---|---|
| p_capy | https://unsplash.com/photos/oDsLyb_H92k | Hoyoun Lee | 0 |
| p_cat | https://unsplash.com/photos/IuJc2qh2TcA | Cédric VT | 0 |
| p_frog | https://unsplash.com/photos/EP_OHkgn1JI | Jack Hamilton | 0 |
| p_goose | https://unsplash.com/photos/bnJQxin8R7M | Joshua Ralph | 0 |
| p_dog_shades | https://unsplash.com/photos/ts1zXzsD7xc | Mollie Sivaram | 0 |
| p_dog_glam | https://unsplash.com/photos/q_FTiHRCeJo | wooof woof | 2 |
| p_goose_white | https://unsplash.com/photos/g_egdHwa5xk | Amit Talwar | 2 |
| p_llama | https://unsplash.com/photos/Fjn756Sj6bk | Tarryn Grignet | 2 |
| p_pug_tongue | https://unsplash.com/photos/85XqQOx4dyg | Osman Espinoza Franco | 2 |
| p_dog_beach | https://unsplash.com/photos/hhegBj6iJ5E | Mel Elías | 2 |
| p_pug | https://unsplash.com/photos/DziZIYOGAHc | charlesdeluvio | 5 |

## Розподіл (62 + «Steam»)
- tier 0 (усім): 22 + Steam
- 2 Куркуль: 26
- 5 Шляхтич: 9
- 7 Олігарх: 5 (буржуй, король, моаї гри, 🗿, 🤑)
