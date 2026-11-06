# CivitGallery

Android gallery for browsing images from Civitai.

**[Download the latest APK](https://github.com/greyowlsteam/CivitGallery/releases/latest/download/CivitGallery.apk)** · [All releases](https://github.com/greyowlsteam/CivitGallery/releases)

<a href="https://github.com/greyowlsteam/CivitGallery/releases/latest/download/CivitGallery.apk"><img src="qr-download.svg" width="200" alt="QR code: download the latest CivitGallery APK"></a>

Scan with your phone camera to download · Наведите камеру телефона, чтобы скачать

[Инструкция на русском ↓](#установка)

## Install

Android 8.0 or newer.

1. Download `CivitGallery.apk` on your phone and open it (from the download notification or the Downloads folder).
2. Android asks to allow installing apps from your browser: tap **Settings**, turn on **Allow from this source**, go back.
3. Tap **Install**.
4. **Google Play Protect** may say the app could be harmful. **Do not tap OK — it cancels the installation.**
   Tap **More details**, then **Install anyway**. On some phones *Install anyway* is a text link above the OK button.

### Why Play Protect warns

CivitGallery is not on Google Play, and Play Protect judges such apps by reputation: a new app with few installs gets this warning
regardless of what it does. It is a warning about an unknown app, not a detected threat.
The app needs only internet access, and every release lists the SHA-256 of the APK so you can check your download.

### Updates

The app checks for a new version once a day (and in Settings → About). Tap **Update**, the APK downloads in your browser —
install it over the current version the same way. Your settings and sign-in stay.

## Privacy

No ads, analytics or trackers. You don't need an account to browse.

**Only on your phone:** settings, hidden tags and authors, the image cache, sign-in tokens (encrypted with a key in Android Keystore).
App data is excluded from Android backups.

**Civitai** (civitai.com): images and their data are loaded directly from Civitai. If you sign in with Civitai, you do it on Civitai's own page —
your password never passes through the app. After that your reactions, collections, follows and hidden tags are read and changed
in your Civitai account, under Civitai's privacy policy.

**Our server** (extended tags). After you accept the rules, the app creates a guest profile with:

- a device key — only the public part; the private key is created in Android Keystore and never leaves the phone;
- the phone model name and the interface language;
- your age confirmation and content consents, with the rules version and date;
- a random nickname (`user-123456`) that you can change;
- the tags you add, your votes and reports, and the IDs of the Civitai images they belong to;
- when you hide extended tags, the IDs of those tags and of the images on the feed page, to find which images to hide or blur;
- only if you link them: your email (the sign-in code is sent by email; only a hash of the code is kept) and your Telegram ID, username and name.

The hosting keeps technical request logs, including IP addresses.

**GitHub:** once a day the app asks GitHub for the latest release. No personal data is sent; GitHub sees your IP address.

**Deleting your data:** Settings → App profile → **Delete profile** deletes your votes, reports, sign-in methods and device keys.
Tags you added stay on the images without your name. To remove data from the phone, uninstall the app.
To disconnect Civitai, sign out in Settings → Civitai account.

---

# CivitGallery (RU)

Android-галерея для просмотра картинок с Civitai.

**[Скачать последнюю версию](https://github.com/greyowlsteam/CivitGallery/releases/latest/download/CivitGallery.apk)** · [Все релизы](https://github.com/greyowlsteam/CivitGallery/releases)

## Установка

Нужен Android 8.0 или новее.

1. Скачайте `CivitGallery.apk` на телефон и откройте его — из уведомления о загрузке или из папки «Загрузки».
2. Android попросит разрешить установку из браузера: нажмите **Настройки**, включите **Разрешить из этого источника**, вернитесь назад.
3. Нажмите **Установить**.
4. **Play Защита** может написать, что приложение может навредить. **Не нажимайте «ОК» — это отменяет установку.**
   Нажмите **Подробнее**, затем **Всё равно установить**. На некоторых телефонах «Всё равно установить» — надпись-ссылка над кнопкой «ОК».

### Почему Play Защита предупреждает

CivitGallery нет в Google Play, а такие приложения Play Защита оценивает по известности: новое приложение с небольшим числом установок
получает это предупреждение, что бы оно ни делало. Это предупреждение о незнакомом приложении, а не найденная угроза.
Приложению нужен только доступ в интернет, а в описании каждого релиза есть SHA-256 файла для проверки.

### Обновления

Приложение раз в сутки проверяет новую версию (и по кнопке в «Настройки → О приложении»). Нажмите **Обновить** — APK скачается
в браузере, установите его поверх так же. Настройки и вход сохранятся.

## Конфиденциальность

Без рекламы, аналитики и трекеров. Для просмотра аккаунт не нужен.

**Только на телефоне:** настройки, скрытые теги и авторы, кэш картинок, токены входа (зашифрованы ключом в Android Keystore).
Данные приложения не попадают в резервные копии Android.

**Civitai** (civitai.com): картинки и данные о них загружаются напрямую с Civitai. Вход через Civitai происходит на странице самого Civitai —
пароль через приложение не проходит. После входа ваши реакции, коллекции, подписки и скрытые теги читаются и меняются
в вашем аккаунте Civitai, по правилам конфиденциальности Civitai.

**Наш сервер** (расширенные теги). После принятия правил приложение создаёт гостевой профиль, в нём:

- ключ устройства — только открытая часть; закрытый ключ создаётся в Android Keystore и не покидает телефон;
- название модели телефона и язык интерфейса;
- подтверждение возраста и согласия на контент — с версией правил и датой;
- случайный ник (`user-123456`), его можно сменить;
- добавленные вами теги, голоса и жалобы, а также ID картинок Civitai, к которым они относятся;
- если вы скрываете расширенные теги — ID этих тегов и картинок страницы ленты, чтобы найти, какие картинки скрыть или размыть;
- только если вы их привяжете: почта (код входа приходит письмом, хранится только хэш кода) и ID, имя пользователя и имя в Telegram.

Хостинг ведёт технические журналы запросов, включая IP-адреса.

**GitHub:** раз в сутки приложение спрашивает у GitHub последнюю версию. Личные данные не передаются, GitHub видит ваш IP-адрес.

**Удаление данных:** «Настройки → Профиль приложения → **Удалить профиль**» удаляет голоса, жалобы, способы входа и ключи устройств.
Добавленные теги остаются на картинках без вашего имени. Чтобы удалить данные с телефона, удалите приложение.
Отключить Civitai — выйти из аккаунта в «Настройки → Аккаунт Civitai».
