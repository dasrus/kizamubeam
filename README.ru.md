# KizamuBeam

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/brand/kizamubeam-logo-dark.png">
    <img src="docs/brand/kizamubeam-logo.png" alt="KizamuBeam" width="520">
  </picture>
</p>

<p align="center">
  <b>Проектируйте, гравируйте, режьте. Бесплатная лазерная программа для macOS, Windows и Linux.</b>
</p>

<p align="center">
  <a href="https://github.com/negurvulkan/kizamubeam/releases"><b>Скачать</b></a> ·
  <a href="https://negurvulkan.github.io/kizamubeam/ru/">Веб-сайт</a> ·
  <a href="docs/features.ru.md">Все возможности</a> ·
  <a href="https://discord.gg/SSr8VHh7EJ">Discord</a> ·
  <a href="README.md">English</a> ·
  <a href="README.de.md">Deutsch</a> ·
  <a href="README.it.md">Italiano</a>
</p>

KizamuBeam проведёт вас от первой идеи до готового изделия в одной программе: рисуйте и пишите прямо на рабочей области, превращайте фотографии в гравировку, создавайте коробки, шестерни и модели на пазовых соединениях, проверяйте всё в 3D и отправляйте задание прямо на лазер. Если вы раньше пользовались LightBurn, вы сразу освоитесь.

Программа с открытым кодом (GPL-3.0), бесплатна и не требует ни аккаунта, ни лицензионного ключа.

<p align="center">
  <img src="docs/screenshots/design-en.png" alt="Главное окно KizamuBeam с набором подстаканников и деревянной табличкой на рабочей области, слои справа" width="900">
</p>

## Скачать

| Система | Файл |
|---|---|
| **macOS** (Apple Silicon и Intel) | `KizamuBeam_…_universal.dmg` |
| **Windows** (64-бит) | `KizamuBeam_…_x64-setup.exe` |
| **Linux** (64-бит) | `KizamuBeam_…_amd64.AppImage`, `.deb` или `.rpm` |

Последнюю версию можно получить на [странице релизов](https://github.com/negurvulkan/kizamubeam/releases) или на [веб-сайте](https://negurvulkan.github.io/kizamubeam/ru/#download). Текущая версия: **2.8.0** (стабильная). После установки KizamuBeam обновляется сама (Справка → Проверить обновления).

> **Первый запуск на macOS:** если macOS сообщает, что приложение невозможно проверить, откройте «Системные настройки → Конфиденциальность и безопасность» и нажмите «Всё равно открыть».

## Что можно делать

### Проектирование прямо в программе
Линии, кривые, фигуры и текст любым шрифтом, в том числе всеми Google Fonts в один клик. Объединяйте фигуры, смещайте их, редактируйте узлы (сразу в нескольких объектах), упрощайте и сглаживайте контуры, изгибайте текст по контуру, скругляйте углы. Привязка, выравнивание, массивы и автоматическая раскладка наводят порядок, а результат всегда остаётся чистой редактируемой кривой. Библиотека с **400 встроенными мотивами и элементами оформления** поможет начать.

### Импорт ваших изображений
Открывайте файлы SVG, DXF, PDF и Illustrator, проекты LightBurn (`.lbrn2`) и все распространённые форматы изображений. Для фотографий есть дизеринг, газетный и эскизный эффекты, удаление фона, обрезка и маски, а также перевод в векторы, включая осевые линии для одноштриховой гравировки.

### Генерация деталей вместо рисования
Введите размеры — и получите готовые детали: **коробки с пальцевыми соединениями, ящики, разделители, полки, шестерни, рейки, шкивы, кулачки и петли крышек**. Соединения, пазы и живые шарниры можно добавить к любой фигуре. Превращайте 3D-модели (STL/OBJ) в слоистые, рёберные или дисковые модели из плоских деталей. Двойной клик по детали позже — и всё пересчитается.

<p align="center">
  <img src="docs/screenshots/box-3d-en.png" alt="Набор инструментов с генераторами слева, коробка с пальцевыми соединениями и гравированной лисой в 3D-виде" width="900">
</p>

### Увидеть результат до выжигания
**3D-вид** собирает детали точно так, как они будут собраны, с материалом, текстурой и гравировкой, и показывает, не сталкивается ли что-нибудь. **Проверка макета** находит незамкнутые контуры, мелкие детали и проблемы посадки до начала работы. **Предпросмотр** проигрывает задание с точной оценкой времени.

<p align="center">
  <img src="docs/screenshots/preview-en.png" alt="Предпросмотр задания с ползунком воспроизведения, расчётным временем и длиной реза" width="900">
</p>

### Запуск лазера
Работает с **FluidNC, GRBL, grblHAL, Marlin и Smoothieware** по USB или Wi-Fi. Мастер настройки определяет контроллер, проверяет его настройки и выполняет первое тестовое задание. Рамка, запуск, пауза, изменение мощности и скорости во время гравировки, запуск с любого места задания. Перед каждым заданием KizamuBeam проверяет, что всё помещается на столе. Поддерживаются поворотные модули, моторизованная ось Z и обдув.

### Правильные настройки
Библиотека материалов хранит проверенные настройки. Тест материала, тест фокуса и калибровка посадки помогут их найти, а тест можно оценить прямо по фотографии. На слой: несколько проходов, подслои, перемычки, компенсация ширины реза, перфорация, подвод/отвод и нарастание мощности.

### Производство партий
Шаблоны с параметрами, переменный текст и серийные номера из CSV, QR-коды и штрихкоды, многостраничные проекты, приспособления для партий заготовок, **«Печать и резка»** с метками совмещения и камерой для точного размещения макета на заготовке.

### Сделайте программу своей
Открепляемые окна и настраиваемые панели инструментов, светлая и тёмная темы, интерфейс на английском, немецком, итальянском и русском. Набор инструментов собирает все генераторы и специальные инструменты в одном месте. Расширения добавляют шаблоны устройств, шаблоны, материалы и мотивы. Настройки, устройства и библиотеки можно сохранить в резервную копию или перенести файлом, либо синхронизировать между компьютерами через свою папку (iCloud, Dropbox, Nextcloud). ИИ-агенты, такие как Claude Code или Codex, могут работать с вашим проектом через встроенный MCP-сервер с выбранным вами уровнем доступа.

**→ [Полный список возможностей](docs/features.ru.md)**

## Сборка своими силами

Понадобится Node.js 20+ и Rust (стабильная); на Linux также [необходимые зависимости Tauri](https://v2.tauri.app/start/prerequisites/).

```bash
npm install
npm run tauri dev      # настольное приложение с живой перезагрузкой
npm run tauri build    # установщик для вашей системы
```

Релизы, обновления, переводы и структура кода описаны в [руководстве разработчика](docs/development.md). Вклад приветствуется, см. [CONTRIBUTING.md](CONTRIBUTING.md); о переводе KizamuBeam на ваш язык — см. [TRANSLATION.md](TRANSLATION.md).

## Сообщество

Вопросы, идеи или что-то, что вы сделали с KizamuBeam? Присоединяйтесь к нам в [Discord](https://discord.gg/SSr8VHh7EJ). Ошибки и запросы функций лучше всего оформлять как [issues на GitHub](https://github.com/negurvulkan/kizamubeam/issues).

## Участники

Спасибо этим замечательным людям ([таблица эмодзи](https://allcontributors.org/docs/en/emoji-key)). Код, переводы, тестирование на реальных станках, отчёты об ошибках и идеи — всё это ценно. О том, как попасть в список, см. [CONTRIBUTING.md](CONTRIBUTING.md#credits).

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/negurvulkan"><img src="https://avatars.githubusercontent.com/u/61453878?v=4?s=80" width="80px;" alt="Hanjo Winter"/><br /><sub><b>Hanjo Winter</b></sub></a><br /><a href="#projectManagement-negurvulkan" title="Project Management">📆</a> <a href="#maintenance-negurvulkan" title="Maintenance">🚧</a> <a href="https://github.com/negurvulkan/kizamubeam/commits?author=negurvulkan" title="Code">💻</a> <a href="https://github.com/negurvulkan/kizamubeam/commits?author=negurvulkan" title="Documentation">📖</a> <a href="#design-negurvulkan" title="Design">🎨</a> <a href="#ideas-negurvulkan" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/negurvulkan/kizamubeam/commits?author=negurvulkan" title="Tests">⚠️</a> <a href="#translation-negurvulkan" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/liquid-light"><img src="https://avatars.githubusercontent.com/u/21311036?v=4?s=80" width="80px;" alt="liquid-light"/><br /><sub><b>liquid-light</b></sub></a><br /><a href="https://github.com/negurvulkan/kizamubeam/commits?author=liquid-light" title="Code">💻</a> <a href="#ideas-liquid-light" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/negurvulkan/kizamubeam/issues?q=author%3Aliquid-light" title="Bug reports">🐛</a> <a href="https://github.com/negurvulkan/kizamubeam/commits?author=liquid-light" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/SimoCassan"><img src="https://avatars.githubusercontent.com/u/96295007?v=4?s=80" width="80px;" alt="SimoCassan"/><br /><sub><b>SimoCassan</b></sub></a><br /><a href="#translation-SimoCassan" title="Translation">🌍</a> <a href="https://github.com/negurvulkan/kizamubeam/commits?author=SimoCassan" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Asiak3"><img src="https://avatars.githubusercontent.com/u/71585581?v=4?s=80" width="80px;" alt="Asiak C."/><br /><sub><b>Asiak C.</b></sub></a><br /><a href="https://github.com/negurvulkan/kizamubeam/commits?author=Asiak3" title="Code">💻</a> <a href="#ideas-Asiak3" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/negurvulkan/kizamubeam/issues?q=author%3AAsiak3" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Pietrogramma"><img src="https://avatars.githubusercontent.com/u/11855652?v=4?s=80" width="80px;" alt="Pietrogramma"/><br /><sub><b>Pietrogramma</b></sub></a><br /><a href="#translation-Pietrogramma" title="Translation">🌍</a> <a href="https://github.com/negurvulkan/kizamubeam/commits?author=Pietrogramma" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Лицензия

KizamuBeam — свободная программа под [GNU General Public License v3.0 или новее](LICENSE). Создана на Tauri 2, TypeScript и Rust. «Kizamu» (刻む) по-японски означает «резать, гравировать, тонко вырезать».

Copyright © 2026 [Hanjo Winter](https://github.com/negurvulkan). Разработано при содействии [Claude Code](https://claude.com/claude-code).

## Товарные знаки

LightBurn — товарный знак LightBurn Software, LLC. KizamuBeam — независимый проект и не связан с LightBurn Software и не одобрен ею.