# CivitGallery в VR — инструкция / VR guide

[Русский](#ru) · [English](#en)

<a name="ru"></a>

## Русский

### Что нужно

- Очки Cardboard или любые VR-очки, в которые вставляется телефон.
- Телефон с гироскопом. Если гироскопа нет, кнопки VR в приложении просто не будет.
- Для коллекций, подписок и «Моей галереи» нужен вход в Civitai (Настройки → аккаунт Civitai).

### Первый запуск

1. Откройте ленту или картинку и нажмите кнопку **«Открыть в VR»** (значок-кубик):
   - в ленте — маленькая кнопка внизу экрана: VR откроется с сеткой превью с того места, где вы листали;
   - в просмотре картинки — значок вверху: VR откроется сразу на этой картинке.
2. Вставьте телефон в очки и наденьте их.
3. Перед глазами появится надпись **«Центрирование: держите голову неподвижно»** и отсчёт 3-2-1.
   Смотрите прямо туда, где вам удобно, и не двигайте головой. Когда отсчёт закончится, сцена встанет
   ровно перед вами.

> Сидеть удобнее, чем стоять. Если сцена оказалась не там, где хочется, — коснитесь экрана телефона
> (или нажмите кнопку на очках, если она есть), и центрирование повторится.

### Как нажимать: взглядом

Рук не нужно. В центре зрения — **точка-прицел**.

- **Кнопки.** Наведите точку на кнопку и задержите взгляд: вокруг точки заполняется кольцо, через
  ~1,5 секунды — нажатие.
- **Превью и строки меню.** Сначала даётся ~2 секунды присмотреться (превью под взглядом увеличивается),
  потом бежит кольцо. Так картинки не открываются случайно, пока вы просто разглядываете сетку.
- Чтобы нажать ту же кнопку ещё раз, отведите взгляд и верните обратно.
- Если смотреть на картинку в режиме 3D, точка через полсекунды сама гаснет, чтобы не мешать. Стоит
  отвести взгляд за край картинки — точка вернётся.

### Сетка превью

- Сетка 5×5. **‹ ›** по бокам — предыдущая и следующая страница.
- Взгляд на превью → оно увеличивается → кольцо → картинка открывается во весь экран.
- Сверху **«☰ Ленты»** — меню лент (см. ниже) и **«✓»** — выбор нескольких картинок для коллекций.
- Снизу, ниже всего, — служебные кнопки: **магнит**, **центрирование** и **выход** (см. «Служебные кнопки»).

### Открытая картинка

- **‹ ›** по бокам — предыдущая и следующая картинка ленты.
- Снизу **«✕ Закрыть»** — назад к сетке. Рядом с ней, когда доступно:
  - **«3D»** слева — объём (см. «3D»), **«⇄»** — поменять глаза местами у стереопары;
  - **«360°»** справа — для сферических панорам;
  - **динамик** справа — звук видео;
  - **закладка с плюсом** — положить картинку в коллекцию.
- Сверху **▶** — слайдшоу, рядом интервалы **3 / 5 / 10 / 20 с**. Слайдшоу само ставится на паузу,
  пока вы смотрите в сторону от картинки, и продолжается, когда взгляд вернулся.
- Размытая картинка (18+, если вы включили размытие) показывается заглушкой с кнопкой **«Показать»**.
- Видео играют по кругу. Звук включается кнопкой-динамиком (по умолчанию — как в настройках приложения).

### 3D

- **Готовые стереопары** (две картинки рядом, «SBS») распознаются сами и сразу показываются объёмно.
  Кнопка «3D» выключает/включает объём, **«⇄»** — если объём «вывернут» (перекрёстная стереопара).
- **Обычные картинки** тоже можно сделать объёмными: нажмите «3D». Для этого один раз скачайте модель
  глубины: *Настройки → Псевдо-3D* или *Профиль → Псевдо-3D* (50–99 МБ, моделей несколько — считает
  выбранная там; работает без интернета, фото никуда не отправляются). Пока строится карта глубины (несколько секунд), справа от картинки горит
  «3D …», когда готово — синий значок «3D».
- Включённое 3D остаётся включённым, пока листаете, — можно смотреть подряд.
- **Сила объёма** — пока 3D включено, над картинкой качелька **«−» ×1 «+»**: «−» слева уменьшает,
  «+» справа увеличивает (×0.25 … ×1.5). Подберите под свои глаза — выбор запоминается. Если картинка
  двоится или глаза устают, уменьшите; обычно удобно ×0.5–×1.
- **Модель глубины** — кнопка правее «▶» (если скачано больше одной модели или есть своя карта):
  перебирает «Своя» → DA2 → DA3 → DAD, картинка сразу пересчитывается.
- **Своя карта глубины** — делается на телефоне: экран 3D → кнопка «Своя карта глубины» → чёрно-белая
  карта из галереи (белое — ближе). В VR она показывается вместо посчитанной.
- Пока идёт слайдшоу, над картинкой интервалы — кнопки глубины скрыты.

### Панорамы 360°

- У широких сферических панорам (2:1) появляется кнопка **«360°»** — вы оказываетесь внутри панорамы
  и можете смотреть во все стороны.
- Кнопки в этом режиме — **под ногами**: посмотрите вниз — там **‹**, **«✕ Выйти из 360°»** и **›**.

### Меню лент «☰ Ленты»

- Первая строка — **«Показывать: картинки / видео»**, переключается кликом.
- Дальше ленты: **Открытая лента** (та, из которой вы пришли), **Главная**, после входа — **Подписки**,
  **Моя галерея** и все ваши **коллекции**.
- Если строк много — листайте кнопками **▲ ▼** справа. Закрыть меню — ещё раз «☰ Ленты».

### Коллекции

Класть можно только в **уже существующие** коллекции: набрать название взглядом нельзя, новые
коллекции создаются в приложении. Нужен вход в Civitai.

**Одна картинка.** Откройте её и нажмите **закладку с плюсом** внизу справа. Появится список коллекций:

- **«+ Название»** — клик кладёт картинку туда;
- **«✓ Название»** (синяя строка) — картинка уже там, клик убирает её;
- **«… Название»** — сохраняется.

Сохраняется сразу по клику. Можно отметить несколько коллекций подряд. Закончили — нажмите
**«✓ Готово»** над списком.

**Несколько картинок.** В сетке нажмите **«✓»** сверху — включится выбор. Теперь взгляд на превью не
открывает его, а отмечает **синей рамкой** (повторно — снимает). Выбор сохраняется, если листать
страницы и даже менять ленты. Когда что-то отмечено, рядом с «✓» появляется **закладка**: нажмите её
и кликните по нужным коллекциям — в каждую лягут все отмеченные картинки. Нажмите **«✓ Готово»** —
отметки снимутся.

### Служебные кнопки (внизу, под сценой)

- **Центрирование** (◎) — сцена заново встанет перед вами после отсчёта 3-2-1.
- **Магнит** — «взять» сцену и перенести: нажмите магнит, поверните голову туда, где хотите видеть
  сцену, и замрите на ~1,5 секунды — сцена останется там. Удобно, если устала шея или вы легли.
- **Выход** (⏻) — сцена гаснет, появляется **«Снимите очки и коснитесь экрана»**. Коснитесь экрана —
  VR закроется, а приложение откроется на последней просмотренной картинке. Передумали — посмотрите на
  **«Вернуться в VR»**.

### Если что-то пошло не так

- **Сцена уплыла или потерялась.** Посмотрите в любую сторону и замрите: если сцены не видно, через
  пару секунд центрирование запустится само. Или коснитесь экрана телефона.
- **Двоится в глазах.** Поправьте телефон в очках, чтобы его центр был точно между линзами.
- **Объём «вывернут»** у стереопары — нажмите **«⇄»**.
- **Нет кнопки «3D» у обычной картинки** — скачайте модель (*Настройки → Псевдо-3D*).
- **Нет кнопок «✓» и закладки** — войдите в Civitai в настройках приложения.
- **Выйти быстро** — снимите очки и нажмите «назад» на телефоне.

---

<a name="en"></a>

## English

### What you need

- A Cardboard viewer or any VR headset that holds a phone.
- A phone with a gyroscope. Without one, the app simply doesn't show the VR button.
- Collections, Following and My gallery need a Civitai sign-in (Settings → Civitai account).

### First launch

1. Open a feed or a picture and tap **Open in VR** (the cube icon):
   - in a feed — the small button at the bottom: VR opens with a grid of thumbnails where you were scrolling;
   - in the picture viewer — the icon at the top: VR opens right on that picture.
2. Put the phone into the headset and put it on.
3. You'll see **"Centering: keep your head still"** and a 3-2-1 countdown. Look straight where it's
   comfortable and don't move. When the countdown ends, the scene appears right in front of you.

> Sitting is more comfortable than standing. If the scene isn't where you want it, tap the phone screen
> (or press the headset button, if it has one) and centering starts again.

### How to click: with your gaze

No hands needed. There's a **dot** in the middle of your view.

- **Buttons.** Put the dot on a button and hold your gaze: a ring fills around the dot, and after
  ~1.5 seconds the button is pressed.
- **Thumbnails and menu rows.** You first get ~2 seconds to look (the thumbnail under your gaze grows),
  then the ring starts. This way pictures don't open by accident while you're just looking around.
- To press the same button again, look away and back.
- While you look at a picture in 3D, the dot fades out after half a second so it doesn't get in the way.
  Look past the picture's edge, and the dot comes back.

### Thumbnail grid

- A 5×5 grid. **‹ ›** on the sides — previous and next page.
- Look at a thumbnail → it grows → ring → the picture opens full size.
- At the top: **"☰ Feeds"** — the feeds menu (see below), and **"✓"** — select several pictures for collections.
- At the very bottom — utility buttons: **magnet**, **center** and **exit** (see "Utility buttons").

### An open picture

- **‹ ›** on the sides — previous and next picture in the feed.
- At the bottom, **"✕ Close"** — back to the grid. Next to it, when available:
  - **"3D"** on the left — depth (see "3D"), **"⇄"** — swap eyes for a stereo pair;
  - **"360°"** on the right — for spherical panoramas;
  - **speaker** on the right — video sound;
  - **bookmark with a plus** — add the picture to a collection.
- At the top, **▶** — slideshow, with intervals **3 / 5 / 10 / 20 s** next to it. The slideshow pauses
  while you look away from the picture and goes on when you look back.
- A blurred picture (18+, if you turned blurring on) shows a placeholder with a **"Show"** button.
- Videos loop. Sound is toggled with the speaker button (it starts as set in the app settings).

### 3D

- **Ready-made stereo pairs** (two pictures side by side, "SBS") are detected automatically and shown in
  3D right away. The "3D" button turns depth off/on; **"⇄"** fixes "inside-out" depth (cross-eyed pairs).
- **Ordinary pictures** can be made 3D too: press "3D". For this, download the depth model once:
  *Settings → Pseudo-3D* or *Profile → Pseudo-3D* (50–99 MB; there are several models, the one selected
  there is used; works offline, photos never leave the phone).
  While the depth map is being built (a few seconds), "3D …" shows to the right of the picture; when
  it's ready, the blue "3D" badge appears.
- 3D stays on as you move through pictures, so you can watch them one after another.
- **Depth strength** — while 3D is on, a seesaw sits above the picture: **"−" ×1 "+"**. "−" on the left
  lowers it, "+" on the right raises it (×0.25 … ×1.5). Pick what suits your eyes — the choice is
  remembered. If the picture doubles or your eyes get tired, turn it down; ×0.5–×1 is usually comfortable.
- **Depth model** — the button right of "▶" (when more than one model is downloaded or you have your own
  map): cycles Mine → DA2 → DA3 → DAD, and the picture is recomputed right away.
- **Your own depth map** — made on the phone: 3D screen → "Your own depth map" → a black-and-white map from
  your gallery (white is nearer). In VR it is shown instead of the computed one.
- During a slideshow the row above the picture shows intervals, so the depth buttons are hidden.

### 360° panoramas

- Wide spherical panoramas (2:1) get a **"360°"** button — you find yourself inside the panorama and
  can look all around.
- In this mode the buttons are **at your feet**: look down to find **‹**, **"✕ Exit 360°"** and **›**.

### Feeds menu "☰ Feeds"

- The first row is **"Show: images / videos"**, switched with a click.
- Then the feeds: **Opened feed** (the one you came from), **Main feed**, and after sign-in **Following**,
  **My gallery** and all your **collections**.
- If there are many rows, page with **▲ ▼** on the right. Close the menu with "☰ Feeds" again.

### Collections

You can add only to **existing** collections: you can't type a name with your gaze, so new collections
are created in the app. A Civitai sign-in is required.

**One picture.** Open it and press the **bookmark with a plus** at the bottom right. A list of your
collections appears:

- **"+ Name"** — a click adds the picture there;
- **"✓ Name"** (blue row) — the picture is already there, a click removes it;
- **"… Name"** — saving.

It's saved right away on each click; you can tick several collections in a row. When done, press
**"✓ Done"** above the list.

**Several pictures.** In the grid, press **"✓"** at the top to turn on selection. Now looking at a
thumbnail doesn't open it — it marks it with a **blue frame** (again — unmarks). The selection is kept
when you change pages and even feeds. Once something is selected, a **bookmark** appears next to "✓":
press it and click the collections you want — all selected pictures go into each of them. Press
**"✓ Done"** and the selection is cleared.

### Utility buttons (at the bottom, below the scene)

- **Center** (◎) — the scene is placed in front of you again after a 3-2-1 countdown.
- **Magnet** — "grab" the scene and move it: press the magnet, turn your head to where you want the
  scene, and hold still for ~1.5 seconds — the scene stays there. Handy if your neck is tired or you're
  lying down.
- **Exit** (⏻) — the scene fades and **"Take off the headset and tap the screen"** appears. Tap the
  screen to close VR; the app opens on the last picture you viewed. Changed your mind? Look at
  **"Back to VR"**.

### Troubleshooting

- **The scene drifted away or got lost.** Look anywhere and hold still: if the scene isn't in view,
  centering starts by itself in a couple of seconds. Or tap the phone screen.
- **You see double.** Adjust the phone in the headset so its center is exactly between the lenses.
- **A stereo pair's depth is inside out** — press **"⇄"**.
- **No "3D" button on an ordinary picture** — download the model (*Settings → Pseudo-3D*).
- **No "✓" and bookmark buttons** — sign in to Civitai in the app settings.
- **Quick exit** — take off the headset and press Back on the phone.
