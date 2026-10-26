# Sonelo - политика конфиденциальности / Privacy Policy

Действует с 26.10.2026, версия приложения 1.0.0.

## Русский

Sonelo - независимый клиент музыкального сервиса YouTube Music для Windows. У разработчика нет своих серверов:
приложение не собирает телеметрию, не показывает рекламу и не передаёт разработчику никаких данных.

**Что хранится на вашем компьютере** (папка приложения в `%LOCALAPPDATA%`):

- cookies входа в аккаунт Google - в профиле WebView2. Пароль вводится на странице Google, приложение его не видит и не хранит;
- настройки, очередь воспроизведения, закреплённое, история поиска внутри приложения, скрытые исполнители;
- расширенный кэш (если включён): ответы сервиса, обложки, тексты песен. Звук не сохраняется. Кэш очищается кнопкой
  в настройках и при выходе из аккаунта;
- ключ сессии Last.fm (если вы подключили Last.fm) - в диспетчере учётных данных Windows.

**Куда приложение обращается по сети:**

- music.youtube.com, youtube.com, accounts.google.com - каталог, поиск, воспроизведение и действия с вашим аккаунтом
  (лайки, плейлисты, библиотека). Действуют [политика конфиденциальности Google](https://policies.google.com/privacy)
  и [условия YouTube](https://www.youtube.com/t/terms);
- lrclib.net - поиск текста песни: отправляются название трека, исполнитель, альбом и длительность;
- last.fm (только если вы подключили Last.fm) - «Сейчас играет» и скробблы: исполнитель, трек, альбом, время прослушивания.
  Действует [политика Last.fm](https://www.last.fm/legal/privacy).

Удалить все данные приложения: выйти из аккаунта в настройках, отключить Last.fm и удалить приложение
(или папку `%LOCALAPPDATA%\Sonelo`).

Вопросы: через страницу приложения в Microsoft Store.

## English

Sonelo is an independent YouTube Music client for Windows. The developer runs no servers: the app collects no
telemetry, shows no ads of its own and sends no data to the developer.

**Stored on your computer** (the app folder in `%LOCALAPPDATA%`): Google sign-in cookies in the WebView2 profile
(your password is entered on Google's page and is never seen or stored by the app); settings, playback queue,
pinned items, in-app search history, hidden artists; the extended cache if enabled (service responses, cover art,
lyrics - never audio); the Last.fm session key, if connected, in Windows Credential Manager.

**Network access:** music.youtube.com, youtube.com and accounts.google.com for browsing, search, playback and account
actions ([Google Privacy Policy](https://policies.google.com/privacy), [YouTube Terms](https://www.youtube.com/t/terms));
lrclib.net for lyrics (track title, artist, album and duration are sent); last.fm only if you connect it
(now playing and scrobbles; [Last.fm Privacy Policy](https://www.last.fm/legal/privacy)).

To remove all data: sign out in Settings, disconnect Last.fm and uninstall the app (or delete `%LOCALAPPDATA%\Sonelo`).

Contact: via the app's Microsoft Store page.
