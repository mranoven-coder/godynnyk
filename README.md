# Навчальний годинник / Learning Clock

**Версія / Version:** 3.03 (24.09.2026)
**Онлайн / Live:** https://mranoven-coder.github.io/godynnyk/

🇺🇦 Інтерактивний аналоговий годинник, який вчить дітей визначати час. Безкоштовно, працює офлайн у будь-якому браузері, можна встановити як застосунок на телефон.

🇬🇧 An interactive analog clock that teaches children to tell the time. Free, works offline in any browser, can be installed as an app on a phone.

## Можливості / Features

- Стрілки можна тягнути пальцем або мишкою / Drag the hands with a finger or the mouse
- 12- і 24-годинний формат на одному циферблаті / 12-hour and 24-hour formats on one dial
- Показ і приховування стрілок, пауза, хід назад / Show or hide hands, pause, run backward
- Швидкість ходу: повзунок і вибір максимуму x300 / x600 / x1200 / Clock speed: slider with a maximum of x300 / x600 / x1200
- Поле для встановлення часу (на телефоні — системне вікно вибору, оформлене як на комп'ютері) / A field to set the time (on a phone — the system picker, styled like on a computer)
- Українська, англійська й іспанська (UA / EN / ES): повний переклад інтерфейсу, інструкції та всієї історії версій / Ukrainian, English and Spanish (UA / EN / ES): full translation of the interface, the guide, and the entire version history
- Інструкція для батьків і вчителів обома мовами / Guide for parents and teachers in both languages
- Підказки зі списком функцій при кожному відкритті чи оновленні сторінки (тап закриває) / Tips listing all functions on every open or refresh (tap to close)
- Кнопка налаштувань ⚙: підказки при запуску, розмір годинника (100–175 %), розблокування руху пальцем, «Не вимикати екран» та приховування блоку «Показати стрілки» / A ⚙ settings button: startup tips, clock size (100–175%), finger-movement unlock, keep-screen-on and hiding the "Show the hands" block
- Мітка версії поруч із заголовком (дотик відкриває «Що нового») / A version badge next to the title (tap opens "What's new")
- Розділ «Що нового» на сторінці; про нову версію повідомляє позначка «NEW» на кнопці та анонс у вікні підказок / "What's new" section on the page; a new version is announced by a "NEW" mark on the button and a notice in the tips window
- Кнопка «Залишити побажання» відкриває анонімну форму для відгуків / "Send feedback" button opens an anonymous feedback form
- Кнопка «Встановити застосунок»: системне вікно встановлення, а якщо браузер його не дає — підказка, як встановити вручну / "Install app" button: the system install window, or instructions for installing manually if the browser does not provide one
- Доступність: достатня контрастність, керування спливаючими вікнами з клавіатури, масштабування жестом / Accessibility: sufficient contrast, keyboard-friendly pop-ups, pinch-to-zoom
- Пошукова оптимізація (SEO): мета-теги, Open Graph, структуровані дані, canonical, `sitemap.xml`, короткий розділ «Про годинник» / Search engine optimization (SEO): meta tags, Open Graph, structured data, canonical, `sitemap.xml`, a short "About the clock" section

## Побажання та відповіді / Feedback and replies

Кнопка «Залишити побажання» на сторінці відкриває анонімну форму: ми не збираємо ні імені, ні пошти, тому не можемо відповісти особисто. Проте кожне побажання прочитано, а зміни за вашими ідеями публікуються в історії змін нижче та позначаються 💌.

The "Send feedback" button on the page opens an anonymous form: we collect no names or emails, so we cannot reply personally. Every wish is read, and changes made following your ideas are published in the changelog below and marked with 💌.

## Для розробників / For maintainers

Список версій `RELEASES` на початку `index.html` — єдине джерело для сторінки. Щоб випустити нову версію, додайте новий запис ПЕРШИМ (номер, дата, пункти змін і короткий анонс двома мовами). Автоматично підхоплюються: історія змін «Що нового», версія внизу сторінки, мітка версії біля заголовка, мета-тег версії, `softwareVersion` і `dateModified` у структурованих даних, позначка «NEW» та анонс.
Вручну треба оновити лише: коментар на початку файлу, запасні значення версії в HTML (мета-тег, нижній рядок, JSON-LD), `<lastmod>` у `sitemap.xml` і цей файл (версія й історія змін).

The `RELEASES` list at the top of `index.html` is the single source for the page. To publish a new version, add a new entry FIRST (number, date, change items and a short announcement in both languages). Picked up automatically: the "What's new" changelog, the version at the bottom of the page, the version badge next to the title, the version meta tag, `softwareVersion` and `dateModified` in the structured data, the "NEW" mark and the notice.
Only these need updating by hand: the comment at the top of the file, the fallback version values in the HTML (meta tag, footer, JSON-LD), `<lastmod>` in `sitemap.xml`, and this file (version and changelog).

## Ліцензія / License

© 2026 Anatolii Bondarenko. [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) — повний текст у файлі [LICENSE](LICENSE) / full text in [LICENSE](LICENSE).

## Історія змін / Changelog

### v3.03 — 24.09.2026

- Виправлено кнопку «Підтримати проєкт»: на комп'ютері вона розтягувалась на весь вільний простір ряду замість природної ширини, як у сусідніх кнопок. Помилка з'явилася у версії 2.96, коли кнопку перетворили з посилання на звичайну кнопку, і була непомітна на телефоні, де ряд кнопок і так переноситься по одній в рядок / Fixed the "Support the project" button: on desktop it used to stretch to fill the whole row instead of its natural width, unlike its neighboring buttons. The bug appeared in version 2.96, when the button was changed from a link to a regular button, and stayed unnoticed on phones, where the button row already wraps one per line

### v3.02 — 24.09.2026

- Прибрано гру «Постав час», додану у версії 3.01: спливаюче вікно гри закривало циферблат, тож доводилось раз у раз відкривати й закривати вікно, щоб побачити стрілки й результат. Такий тип завдання вчитель чи батьки можуть дати дитині усно й перевірити самі — окрема гра для цього не потрібна / Removed the "Set the time" game added in version 3.01: the game's pop-up window covered the clock face, so it had to be opened and closed repeatedly to see the hands and the result. A teacher or parent can give this kind of task out loud and check it themselves — a separate in-app game isn't needed for it

### v3.01 — 23.09.2026

- Додано гру-нагадування «Постав час»: годинник показує випадковий час, дитина виставляє його стрілками чи полем часу і натискає «Перевірити» — гра підтверджує правильну відповідь або підказує напрямок (вперед/назад) при помилці / Added a "Set the time" reminder game: the clock shows a random time, the child sets it with the hands or the time field and presses "Check" — the game confirms a correct answer or hints at the direction (forward/back) on a miss
- Гра не залежить від швидкості ходу: під час неї годинник автоматично стає на паузу, щоб виставлений час не «втікав» / The game does not depend on the clock speed: it auto-pauses the clock while playing, so the time you set does not drift away
- Інструкцію оновлено: описано нову гру / Updated the guide: described the new game

### v3.00 — 22.09.2026

- Іспанською перекладено всі записи «Що нового» для версій 1.0–2.9 (раніше було перекладено лише 2.91–2.99) — тепер уся історія версій доступна трьома мовами без фолбеку на англійську / Translated all remaining "What's new" entries for versions 1.0–2.9 into Spanish (previously only 2.91–2.99 were translated) — the entire version history is now available in all three languages with no English fallback

### v2.99 — 22.09.2026

- Іспанською перекладено повну інструкцію для батьків і вчителів / Translated the full parent/teacher guide into Spanish
- Іспанською перекладено записи «Що нового» для версій 2.91–2.99; старіші версії поки показуються англійською (працює автоматичний перехід на англійську, якщо перекладу ще немає) / Translated the "What's new" entries for versions 2.91–2.99 into Spanish; older versions still show in English (an automatic fallback to English kicks in wherever a translation isn't ready yet)

### v2.98 — 22.09.2026

- Іспанською перекладено: підказки при запуску, розділ «Про годинник» і вікно вибору способу підтримки / Translated into Spanish: the startup tips, the "About the clock" section and the donation-choice window
- Інструкція для батьків і вчителів та історія версій («Що нового») поки показуються англійською, коли обрано ES; їх переклад — наступний крок / The parent/teacher guide and the version history ("What's new") still show in English when ES is selected; translating them is the next step

### v2.97 — 22.09.2026

- Додано перемикач ES: основний інтерфейс годинника (заголовок, кнопки, налаштування, підказка ⚙) тепер доступний іспанською / Added an ES switch: the clock's main interface (title, buttons, settings, ⚙ hint) is now available in Spanish
- Довгі розділи — інструкція для батьків і вчителів, підказки при запуску, «Що нового», «Про годинник», вибір способу підтримки — поки показуються англійською, коли обрано ES; іспанський переклад цих розділів додамо окремим оновленням / Long sections — the parent/teacher guide, startup tips, "What's new", "About the clock", the donation choice — still show in English when ES is selected; their Spanish translation will be added in a separate update

### v2.96 — 22.09.2026

- Кнопка «Підтримати проєкт» тепер відкриває вікно з вибором способу: банка monobank (гривня), Buy Me a Coffee або Ko-fi (картка, PayPal, долари/євро) — зручно для тих, хто підтримує проєкт з-за кордону / The "Support the project" button now opens a window to choose a way to donate: monobank jar (UAH), Buy Me a Coffee, or Ko-fi (card, PayPal, USD/EUR) — handy for supporters abroad
- Інструкцію оновлено: описано нове вікно вибору / Updated the guide: described the new choice window

### v2.95 — 22.09.2026

- Галочку в ⚙ перейменовано на «Розблокувати рух пальцем по годиннику» з простішим описом: за замовчуванням годинник заблокований від руху пальцем угору-вниз, галочка це розблоковує / Renamed the checkbox in ⚙ to "Unlock moving your finger over the clock" with a simpler description: by default the clock is locked against an up-and-down finger movement, the checkbox unlocks it
- Поведінка галочки не змінилась — уточнено лише назву й текст / The checkbox's behavior has not changed — only the name and text were clarified

### v2.94 — 21.09.2026

- Повернено поведінку версії 2.91: за замовчуванням дотик до циферблата не гортає сторінку — так виставлений час не зіб'ється випадковим рухом пальця / Restored the behavior of version 2.91: by default, touching the clock face does not scroll the page — so the time you have set is not disturbed by an accidental swipe
- У налаштуваннях (⚙) додано галочку «Розблокувати прокручування над годинником»: вмикає звичайне гортання пальцем над порожньою частиною циферблата, як у версії 2.92. Перетягування стрілок і тап по циферблату (пауза / старт) не залежать від цієї галочки / Added a "Unlock scrolling over the clock" checkbox in settings (⚙): turns on ordinary swipe-scrolling over the empty part of the face, like in version 2.92. Dragging the hands and tapping the clock face (pause / start) do not depend on this checkbox
- Інструкцію оновлено: описано нову галочку / Updated the guide: described the new checkbox

### v2.93 — 21.09.2026

- Поле часу на телефонах і планшетах тепер розширюється разом зі шрифтом, тож цифри (зокрема секунди) більше не обрізаються при більшому чи ширшому шрифті / The time field on phones and tablets now widens together with the font, so the digits (including the seconds) are no longer cut off with a larger or wider font
- Цифри в полі часу мають однакову ширину, тому поле не «стрибає» під час ходу годинника / The digits in the time field have equal width, so the field does not "jump" while the clock runs

### v2.92 — 21.09.2026

- Проведення пальцем по порожній частині циферблата тепер прокручує сторінку, як і на решті екрана; раніше весь циферблат «блокував» прокручування / Swiping a finger over the empty part of the clock face now scrolls the page like the rest of the screen; before, the whole clock face blocked scrolling
- Перетягування стрілок і тап по порожньому циферблату (пауза / старт) працюють, як і раніше / Dragging the hands and tapping the empty clock face (pause / start) work as before
- Інструкцію оновлено: описано прокручування над циферблатом / Updated the guide: described scrolling over the clock face

### v2.91 — 21.09.2026

- У налаштуваннях (⚙) додано галочку «Не вимикати екран»: поки вона стоїть, екран телефона не гасне, а комп'ютер не вимикає екран (якщо браузер це підтримує) / Added a "Keep the screen on" checkbox in settings (⚙): while it is ticked, a phone screen does not dim and a computer does not turn its display off (if the browser supports it)
- Галочка знімається щоразу, коли годинник відкривають чи оновлюють, тож блокування не лишається ввімкненим випадково; якщо годинник згорнути, блокування відновиться, коли ви повернетесь / The checkbox is cleared every time the clock is opened or refreshed, so the lock does not stay on by accident; if the clock is minimized, the lock comes back when you return
- Інструкцію й підказки оновлено: описано нову галочку / Updated the guide and the tips: described the new checkbox

### v2.9 — 21.09.2026

- Номер версії тепер показується поруч із заголовком маленькою міткою; дотик до неї відкриває «Що нового». Номер береться зі списку версій автоматично / The version number is now shown next to the title as a small badge; tapping it opens "What's new". The number is taken from the list of releases automatically
- Інструкцію оновлено: згадано мітку версії / Updated the guide: mentioned the version badge

### v2.8 — 21.09.2026

- Кнопка «Встановити застосунок» тепер завжди видима, доки годинник відкрито в браузері: якщо браузер дає системне вікно встановлення — вона відкриває його, якщо ні — показує підказку, як встановити вручну (Android, комп'ютер, iPhone) / The "Install app" button is now always visible while the clock is open in a browser: if the browser provides a system install window it opens it, otherwise it shows instructions for installing manually (Android, desktop, iPhone)
- У вже встановленому застосунку кнопка, як і раніше, прихована / In an already installed app the button is still hidden
- Інструкцію оновлено: описано нову поведінку кнопки / Updated the guide: described the button's new behavior

### v2.7 — 20.09.2026

- На комп'ютері кнопку ⚙ перенесено в ряд верхніх кнопок, праворуч від «Поділитися»; на телефонах і планшетах вона лишилась у правому верхньому куті / On a computer the ⚙ button has moved into the row of top buttons, to the right of "Share"; on phones and tablets it stays in the top right corner
- Інструкцію та підказки оновлено: описано розташування кнопки ⚙ / Updated the guide and the tips: described where the ⚙ button is

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
