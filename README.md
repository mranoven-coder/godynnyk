# Навчальний годинник / Learning Clock

**Версія / Version:** 2.6 (20.09.2026)
**Онлайн / Live:** https://mranoven-coder.github.io/godynnyk/

🇺🇦 Інтерактивний аналоговий годинник, який вчить дітей визначати час. Безкоштовно, працює офлайн у будь-якому браузері, можна встановити як застосунок на телефон.

🇬🇧 An interactive analog clock that teaches children to tell the time. Free, works offline in any browser, can be installed as an app on a phone.

## Можливості / Features

- Стрілки можна тягнути пальцем або мишкою / Drag the hands with a finger or the mouse
- 12- і 24-годинний формат на одному циферблаті / 12-hour and 24-hour formats on one dial
- Показ і приховування стрілок, пауза, хід назад / Show or hide hands, pause, run backward
- Швидкість ходу: повзунок і вибір максимуму x300 / x600 / x1200 / Clock speed: slider with a maximum of x300 / x600 / x1200
- Поле для встановлення часу (на телефоні — системне вікно вибору, оформлене як на комп'ютері) / A field to set the time (on a phone — the system picker, styled like on a computer)
- Українська та англійська мови (UA / EN) / Ukrainian and English (UA / EN)
- Інструкція для батьків і вчителів обома мовами / Guide for parents and teachers in both languages
- Підказки зі списком функцій при кожному відкритті чи оновленні сторінки (тап закриває) / Tips listing all functions on every open or refresh (tap to close)
- Кнопка налаштувань ⚙: підказки при запуску, розмір годинника (100–175 %) та приховування блоку «Показати стрілки» / A ⚙ settings button: startup tips, clock size (100–175%) and hiding the "Show the hands" block
- Розділ «Що нового» на сторінці; про нову версію повідомляє позначка «NEW» на кнопці та анонс у вікні підказок / "What's new" section on the page; a new version is announced by a "NEW" mark on the button and a notice in the tips window
- Кнопка «Залишити побажання» відкриває анонімну форму для відгуків / "Send feedback" button opens an anonymous feedback form
- Кнопка «Встановити застосунок» (одним кліком на Android/комп'ютері, підказка для iPhone) / "Install app" button (one click on Android/desktop, instructions for iPhone)
- Доступність: достатня контрастність, керування спливаючими вікнами з клавіатури, масштабування жестом / Accessibility: sufficient contrast, keyboard-friendly pop-ups, pinch-to-zoom
- Пошукова оптимізація (SEO): мета-теги, Open Graph, структуровані дані, canonical, `sitemap.xml`, короткий розділ «Про годинник» / Search engine optimization (SEO): meta tags, Open Graph, structured data, canonical, `sitemap.xml`, a short "About the clock" section

## Побажання та відповіді / Feedback and replies

Кнопка «Залишити побажання» на сторінці відкриває анонімну форму: ми не збираємо ні імені, ні пошти, тому не можемо відповісти особисто. Проте кожне побажання прочитано, а зміни за вашими ідеями публікуються в історії змін нижче та позначаються 💌.

The "Send feedback" button on the page opens an anonymous form: we collect no names or emails, so we cannot reply personally. Every wish is read, and changes made following your ideas are published in the changelog below and marked with 💌.

## Для розробників / For maintainers

Список версій `RELEASES` на початку `index.html` — єдине джерело для сторінки. Щоб випустити нову версію, додайте новий запис ПЕРШИМ (номер, дата, пункти змін і короткий анонс двома мовами). Автоматично підхоплюються: історія змін «Що нового», версія внизу сторінки, мета-тег версії, `softwareVersion` і `dateModified` у структурованих даних, позначка «NEW» та анонс.
Вручну треба оновити лише: коментар на початку файлу, запасні значення версії в HTML (мета-тег, нижній рядок, JSON-LD), `<lastmod>` у `sitemap.xml` і цей файл (версія й історія змін).

The `RELEASES` list at the top of `index.html` is the single source for the page. To publish a new version, add a new entry FIRST (number, date, change items and a short announcement in both languages). Picked up automatically: the "What's new" changelog, the version at the bottom of the page, the version meta tag, `softwareVersion` and `dateModified` in the structured data, the "NEW" mark and the notice.
Only these need updating by hand: the comment at the top of the file, the fallback version values in the HTML (meta tag, footer, JSON-LD), `<lastmod>` in `sitemap.xml`, and this file (version and changelog).

## Ліцензія / License

© 2026 Anatolii Bondarenko. [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) — повний текст у файлі [LICENSE](LICENSE) / full text in [LICENSE](LICENSE).

## Історія змін / Changelog

### v2.6 — 20.09.2026

- Поле часу на телефонах і планшетах має той самий компактний вигляд, що й на комп'ютері: вужча біла картка, світла рамка та іконка годинника замість системної стрілки / The time field on phones and tablets has the same compact look as on a computer: a narrower white card, a light border and a clock icon instead of the system arrow
- Інструкцію та підказки оновлено: на телефоні тап по полю часу відкриває системне вікно вибору часу / Updated the guide and the tips: on a phone, tapping the time field opens the system time picker

### v2.5 — 20.09.2026

- У налаштуваннях (⚙) додано вибір розміру годинника: 100 %, 125 %, 150 % або 175 % — збільшується весь циферблат разом зі стрілками й цифрами; вибір зберігається в браузері / Added a clock size choice in settings (⚙): 100%, 125%, 150% or 175% — the whole clock face grows together with the hands and numbers; the choice is saved in the browser
- Розмір годинника тепер задається явно (за замовчуванням 420 px, на вузьких екранах — за шириною екрана) і не залежить від ширини поля часу під ним — після спрощення блоку у версії 2.3 циферблат став меншим, ніж задумано / The clock size is now set explicitly (420 px by default, limited by the screen width on narrow screens) and no longer depends on the width of the time field under it — after the block was simplified in version 2.3 the clock face had become smaller than intended
- На невисоких екранах збільшений годинник додатково обмежується висотою вікна, щоб кнопки не йшли далеко вниз / On short screens the enlarged clock is also limited by the window height, so the buttons do not end up far below
- Інструкцію й підказки оновлено: описано вибір розміру / Updated the guide and the tips: described the size choice

### v2.4 — 20.09.2026

- Інструкцію уточнено: крок 4 тепер посилається на поле часу під циферблатом (великого цифрового годинника вже немає) / Clarified the guide: step 4 now refers to the time field under the clock face (the large digital clock is gone)
- Версія та дата останнього оновлення в структурованих даних (JSON-LD) тепер підставляються автоматично зі списку версій — пошукові системи завжди бачать актуальні дані / The version and last-updated date in the structured data (JSON-LD) are now filled in automatically from the list of releases — search engines always see current data

### v2.3 — 20.09.2026

- Прибрано великий цифровий час, день тижня і дату під годинником, а також поле дати — залишилось тільки поле для встановлення часу / Removed the large digital time, weekday and date under the clock, and the date field — only the time-setting field remains

### v2.2 — 20.09.2026

- У налаштуваннях (⚙) додано галочку «Приховати блок «Показати стрілки»» — увімкнена галочка ховає весь цей блок (заголовок і три чекбокси стрілок) разом / Added a "Hide the 'Show the hands' block" toggle in settings (⚙) — when checked, it hides that whole block (the heading and all three hand checkboxes) together
- Аналоговий циферблат зі стрілками завжди залишається видимим і не змінює розмір, незалежно від цього налаштування / The analog clock face with the hands always stays visible and never changes size, regardless of this setting

### v2.1 — 20.09.2026

- Додано керування фокусом у всіх спливаючих вікнах (інструкція, «Що нового», підказки, налаштування): Tab більше не виходить за межі вікна, Escape закриває його, а фокус повертається на кнопку, яка його відкрила / Added focus management to all pop-up windows (guide, what's new, tips, settings): Tab no longer leaves the window, Escape closes it, and focus returns to the button that opened it

### v2.0 — 19.09.2026

- Проведено аудит доступності (за критеріями Lighthouse) і виправлено недостатню контрастність: помаранчеві цифри циферблата, внутрішнє коло 24-годинного формату, кнопки «Інструкція» та «Пауза», а також дрібний підписовий текст / Ran an accessibility audit (Lighthouse criteria) and fixed low-contrast text: the clock's orange numbers, the 24-hour inner ring, the "Guide" and "Pause" buttons, and small caption text

### v1.9 — 19.09.2026

- У структуровані дані (JSON-LD) додано дату публікації та номер версії — точніше для пошукових систем / Added a publish date and version number to the structured data (JSON-LD) — more precise for search engines

### v1.8 — 19.09.2026

- Дозволено масштабування сторінки жестом (прибрано заборону user-scalable) — покращення доступності / Allowed pinch-to-zoom on the page (removed the user-scalable restriction) — an accessibility improvement

### v1.7 — 19.09.2026

- Покращено пошукову оптимізацію (SEO): точніші заголовок і опис, мета-теги, структуровані дані та карта сайту / Improved search engine optimization (SEO): more precise title and description, meta tags, structured data and a sitemap
- Посилання на годинник гарніше виглядає при поширенні в месенджерах і соцмережах / The clock's link looks better when shared in messengers and social networks
- Додано короткий розділ «Про годинник» із відповідями на поширені запитання / Added a short "About the clock" section with answers to common questions
- Інструкцію оновлено: згадано розділ «Про годинник» / Updated the guide: mentioned the "About the clock" section

### v1.6 — 19.09.2026

- Повідомлення про оновлення: позначка «NEW» на кнопці «Що нового» та короткий анонс у вікні підказок / Update notices: a "NEW" mark on the "What's new" button and a short announcement in the tips window
- Інструкцію оновлено: описано повідомлення про оновлення / Updated the guide: described the update notices

### v1.5 — 19.09.2026

- Підказки тепер з'являються при кожному відкритті чи оновленні сторінки або застосунку (їх можна вимкнути в ⚙) / The tips now appear every time the page or the app is opened or refreshed (they can be turned off in ⚙)

### v1.4 — 19.09.2026

- Підказки при запуску: вікно зі списком усіх функцій годинника, закривається тапом у будь-якому місці / Tips at startup: a window listing all the clock's functions, closed by tapping anywhere
- Кнопка ⚙ «Налаштування»: підказки можна вимкнути, знову ввімкнути або показати одразу / ⚙ "Settings" button: the tips can be turned off, turned on again or shown right away
- Інструкцію оновлено: описано підказки й налаштування / Updated the guide: described the tips and the settings

### v1.3 — 19.09.2026

- Додано кнопку «Встановити застосунок» — на Android і комп'ютері встановлює одним кліком, на iPhone показує підказку / Added an "Install app" button — installs with one click on Android and desktop, shows instructions on iPhone
- Інструкцію оновлено: додано опис тапу по циферблату (пауза/старт) і уточнено спосіб встановлення / Updated the guide: added tapping the clock face (pause/start) and clarified how to install

### v1.2 — 19.09.2026

- Додано розділ «Що нового» / Added the "What's new" section

### v1.1 — 19.09.2026

- Кнопка «Залишити побажання» (анонімна форма) / "Send feedback" button (anonymous form)
- Кнопку інструкції перенесено під блок з годинником / Moved the guide button below the clock block

### v1.0 — 19.09.2026

- Українська й англійська мови (UA / EN), переклад інструкції для батьків і вчителів / Ukrainian and English (UA / EN), translated guide for parents and teachers
- Галочки швидкості x300, x600, x1200 / Speed checkboxes x300, x600, x1200
- Кнопки «Підтримати проєкт» і «Поділитися» / "Support the project" and "Share" buttons
- Авторство, ліцензія CC BY-NC-ND 4.0 і номер версії / Authorship, CC BY-NC-ND 4.0 license and version number

## Автор / Author

Anatolii Bondarenko
