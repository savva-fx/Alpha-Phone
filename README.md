<div align="center">

![Alpha Phone](docs/banner.png)

# 📱 Alpha Phone

### The most complete phone for FiveM.

**53 apps · a full staff Admin app · ranked PvP · a casino with live poker · 6 social apps · live streaming from a BodyCam · a real battery · Dual SIM · devices you can hold in the world**

هاتف بتصميم iPhone لسيرفرات FiveM فيه **53 تطبيق**، وكل تطبيق شغال على السيرفر وقاعدة البيانات. مش مجرد واجهة، هو نظام كامل للسيرفر: راديو بمجموعات، شغل وشركات، بنك، كازينو ببوكر مباشر، ساحات قتال بتصنيف، سباقات، 6 تطبيقات تواصل، بث مباشر من كاميرا الصدر، تطبيق أدمن كامل للستاف، وأجهزة حقيقية داخل اللعبة.

![Version](https://img.shields.io/badge/version-1.1.0-c1121f?style=for-the-badge)
![Apps](https://img.shields.io/badge/apps-53-8d0b14?style=for-the-badge)
![FiveM](https://img.shields.io/badge/FiveM-cerulean-1f1f1f?style=for-the-badge)
![Lua](https://img.shields.io/badge/Lua-5.4-2c2d72?style=for-the-badge&logo=lua)
![Keymaster](https://img.shields.io/badge/Cfx.re-Keymaster-f40552?style=for-the-badge)
![Frameworks](https://img.shields.io/badge/QBox%20%7C%20QB--Core%20%7C%20ESX%20%7C%20OX-supported-8d0b14?style=for-the-badge)

**[🛒 Buy on the official store](https://alphastorefivem.store)** · **[💬 Discord](https://discord.gg/CGnrJGVX6k)**

</div>

---

## 📑 Contents

- [Why Alpha Phone](#-ليش-alpha-phone-why-alpha-phone)
- [Purchase (Keymaster)](#-الشراء-purchase--cfxre-keymaster)
- [Preview](#-المعاينة-preview)
- [All 53 apps at a glance](#-كل-التطبيقات-all-apps-at-a-glance)
- [Features in detail](#-المميزات-بالتفصيل-features-in-detail)
  - [Phone & communication](#-phone--communication)
  - [Camera & media](#-camera--media)
  - [System apps](#-system-apps)
  - [iPhone-style OS](#-iphone-style-os)
  - [City, jobs & economy](#️-city-jobs--economy)
  - [Games & competition](#-games--competition)
  - [Social media](#-social-media)
  - [Hardware & devices](#-hardware--devices)
  - [Admin app & staff tools](#️-admin-app--staff-tools)
- [Integrations](#-integrations-auto-detected)
- [Dependencies](#-المتطلبات-dependencies)
- [Installation](#️-التثبيت-installation)
- [Configuration](#️-الإعدادات-configuration)
- [Inventory items](#-العناصر-inventory-items)
- [Battery & charging](#-البطارية-والشحن-battery--charging)
- [Developer API](#-للمطورين-developer-api)
- [Troubleshooting](#-حل-المشاكل-troubleshooting)
- [Support](#-الدعم-support)

---

## 🔥 ليش Alpha Phone؟ (Why Alpha Phone)

Most phones give you a nice screen and a few basic apps. **Alpha Phone runs your whole city from the phone.**

- 🧠 **Server-authoritative:** every app runs on the server and stores its data in MySQL. Money, bets, rides, and moderation are checked on the server, not trusted from the client.
- 🏙️ **An economy that uses your framework:** bank transfers, company accounts, salaries, bonuses, taxi and ride fares, rentals, entry fees, bets, and house cuts. All of it goes through your framework's cash and bank.
- 👥 **Real multiplayer:** radio groups, group chats of up to 50, shared albums, documents you edit together live, crews with live locations, poker tables, 5v5 arenas, 12-car races, and group skydives.
- 🎥 **Devices in the world:** a live phone prop in several colours, a **chest BodyCam** you stream from, **Bluetooth earbuds**, a **speaker** that plays 3D audio in the world, and **printers** that print real inventory items.
- 🛡️ **Staff tools built in:** an **Admin app** on staff phones with player tools, SIM tools, moderation of every social app, app on/off switches for the whole server, full-screen announcements, and an audit log. There's also a **Report** app with a staff inbox.
- 🔋 **A real battery:** drain, battery health, charge cycles, charging with a USB cable in cars, and a power bank.
- 🌍 **Arabic and English:** the full UI in both languages, with right-to-left support.
- 🔌 **Works with what you already run:** it auto-detects your framework, inventory, garage, housing, fuel, bank, and voice scripts.
- 🔐 **Official & protected:** sold only through **Cfx.re Keymaster**. Updates reach your account directly, and you get support.

---

## 🛒 الشراء (Purchase — Cfx.re Keymaster)

> [!IMPORTANT]
> Alpha Phone is sold **only** through the official store, and it's delivered through **Cfx.re Keymaster**, the official FiveM system for paid resources. The protected (escrowed) files run only on a server whose license key belongs to the Cfx.re account that bought the script.
>
> السكربت بينباع **بس** من المتجر الرسمي، وبيوصلك عن طريق **Keymaster** الرسمي تبع Cfx.re. الملفات المحمية بتشتغل بس على سيرفر مفتاحه من نفس الحساب اللي اشترى.

**How to buy and download**

1. Open the official store: **[alphastorefivem.store](https://alphastorefivem.store)**.
2. Add **Alpha Phone** to your cart and log in with your **Cfx.re (FiveM forum) account** at checkout.
3. After you pay, open **[keymaster.fivem.net](https://keymaster.fivem.net)**, log in with the **same account**, and go to **Granted Assets**.
4. Download **Alpha Phone** (it includes `alpha-phone` and `alpha-phone-props`).
5. Your server's `sv_licenseKey` must come from **the same Cfx.re account**. If it doesn't, the server shows `You lack the required entitlement`.

**Why only the official way**

- ✅ Updates appear in Keymaster on your account, so you can download each new version.
- ✅ You get support on Discord (open a ticket with the Cfx.re account name you bought with).
- ❌ Leaked or resold copies won't run, because the escrow is tied to the buyer's account. They also get no updates and no support.

> [!NOTE]
> Want to move the script to a server that's owned by another account? You can transfer the asset from Keymaster, following Cfx.re's transfer rules.

---

## 📸 المعاينة (Preview)

<div align="center">

<img src="docs/screenshots/home.jpg" width="720" alt="Home screen in game">

</div>

<!--
Add more in-game shots to docs/screenshots/ and list them here, e.g.:
| Camera | Admin | Casino |
|:---:|:---:|:---:|
| <img src="docs/screenshots/camera.jpg" width="240"> | <img src="docs/screenshots/admin.jpg" width="240"> | <img src="docs/screenshots/casino.jpg" width="240"> |
-->

---

## 📲 كل التطبيقات (All apps at a glance)

**53 apps for players**, plus **Home** (appears when a housing script is detected) and **Admin** (staff only). The names below are the ones players see on the home screen.

| Category | Apps |
|---|---|
| 📞 **Communication** (6) | Phone · Contacts · Messages · FaceTime · Mail · Radio |
| 📷 **Camera & media** (6) | Camera · ProCam · Photos · CamLink · Music · Music *(Play)* |
| 🧰 **System** (13) | Settings · App Store · Wallet · Garage · Maps · Weather · Clock · Calculator · Voice Memos · Safari · iCloud · Calendar *(التقويم)* · Themes *(ثيم)* |
| 📝 **Productivity** (1) | Notebook *(notes, Word-style docs, Excel-style sheets, reminders, journal)* |
| 🏙️ **City & jobs** (12) | Work · Bank · TaxiGo · Hop · Alpha Motors · Crew · News · Report · MarketPlace · Secret · Print · Speaker |
| 🎮 **Games** (9) | Casino · ARENA · Racing · 8 Ball · Skydive · Bluff Bar · Slap · Metro Dash · Roulette |
| 💬 **Social** (6) | FaceWorld · PhotoFlow · Snapster · ClipTok · ChatWave · WatchMe |
| ➕ **Conditional** | Home *(housing)* · **Admin** *(staff only)* |

Apps that are installed by default: Phone, Messages, Safari, Music, Camera, App Store, Contacts, Settings, Photos, Calendar, Notebook, Wallet, Mail, Maps, Clock, Report, iCloud, FaceTime, and Work. Players install everything else from the **App Store**, and you can change the defaults in `config/config.city.lua`.

---

## ✨ المميزات بالتفصيل (Features in detail)

> The numbers below are the **default** values. Almost all of them can be changed in `config/`.

### 📞 Phone & communication

<details open>
<summary><b>📞 Phone & Voicemail</b></summary>

- Keypad, recents, favourites, and **voicemail** (record, list, delete, and get notified).
- In-call effects, **anonymous calls**, mute, speaker, and blocked numbers.
- **Company lines:** calling a job rings every employee on duty, and the first one to answer takes the call.
- You can't be reached in airplane mode, with a dead battery, or with no signal.
- Works with pma-voice, mumble-voip, SaltyChat, and TokoVOIP.

</details>

<details>
<summary><b>🎥 FaceTime</b></summary>

- **Video and voice calls** over WebRTC, and you can switch a voice call to video in the middle of it.
- Uses your **Alpha ID** (iCloud account), with favourites, recents, and blocking.

</details>

<details>
<summary><b>💬 Messages & 👤 Contacts</b></summary>

- **Messages:** direct messages and **group chats of up to 32 people** with an owner, rename, add members, leave, and ownership transfer.
- Photos, **voice messages**, GIFs, location tags, and **sending money inside a chat**.
- **Contacts:** avatars, email, address, favourites, and blocking, shared with Phone, Messages, FaceTime, and ChatWave.

</details>

<details>
<summary><b>📧 Mail</b></summary>

- Accounts at your city domain (`@mycloud.com` by default), tied to your Alpha ID.
- Attachments, search, delete, and real-time push notifications.

</details>

<details>
<summary><b>📻 Radio: a full walkie-talkie system</b></summary>

- Tune any frequency from **1 to 500** (decimals allowed), and everyone on the same frequency talks together as a group.
- A **live member list** and a **talking indicator** that shows who is speaking right now.
- **Job- and grade-locked channels:** 1–10 for government, 2 for LSPD, and 3 for EMS by default. Players are removed automatically when they lose the job.
- Named channels, up to **12 favourites**, and push-to-talk (ALT by default).
- Works with **pma-voice, mm_radio, SaltyChat, TokoVOIP, and mumble-voip** (auto-detected), with a volume setting from 1 to 100.

</details>

---

### 📷 Camera & media

<details open>
<summary><b>📷 Camera</b></summary>

- Photo, video, selfie, portrait, panorama and slow-mo modes.
- **Hybrid zoom up to 10×:**
  - Up to 2× the zoom is digital, using Catmull-Rom upscaling with adaptive sharpening inside the preview, so the world is untouched.
  - Above 2× it switches to an optical zoom that stays sharp, and the screen outside the phone is dimmed.
  - Control it with the mouse wheel, by dragging, or with quick chips.
- Videos up to 60 seconds, and you can walk around while recording.
- **Uploads:** through Fivemanage, a local folder, or your own uploader.

</details>

<details>
<summary><b>🎞️ ProCam: a professional camera app</b></summary>

- Photo, portrait, cinematic, pro, video, and burst modes.
- **14 colour looks** with strength control, plus pro grading (EV, white balance, and more).
- Grids, portrait or landscape framing, stabilisation, depth of field, tap-to-focus, torch, and saved presets.

</details>

<details>
<summary><b>🖼️ Photos</b></summary>

- One gallery for Camera, ProCam, social apps, Print, and Report.
- Favourites, albums, and **shared albums** with members you invite. Updates reach members live.
- AirDrop to nearby players (off, contacts only, or everyone).

</details>

<details>
<summary><b>📹 CamLink: BodyCam recording & live watch</b></summary>

- **Record**, **Watch**, and **Screen** modes.
- Records from the chest **BodyCam** item.
- **Police, sheriff, and EMS** can watch live BodyCams, or cast them to a screen in the world (18 m range).

</details>

<details>
<summary><b>🎵 Music & Play</b></summary>

- **Music:** playlists, a song catalogue from `config/music.lua` or from URLs, and Now Playing.
- **Play:** YouTube, MP3 links, Jamendo, Internet Archive, and **world radio stations** (radio-browser). Up to 20 playlists, 10 genres, likes, and a queue. **It keeps playing after you close the phone.**

</details>

---

### 🧰 System apps

| App | Features |
|---|---|
| **⚙️ Settings** | Alpha ID & iCloud, airplane mode, Cellular (with SIM), Wi-Fi, Bluetooth (BodyCam and Pods), Sounds & Haptics, Focus / Do Not Disturb, General (AirDrop, keyboard), Display & Brightness, Wallpaper, **Face ID & Passcode**, Battery, Privacy & Security, **Streamer Mode**, and About (IMEI and serial). |
| **🛍️ App Store** | Social, City, Entertainment, Productivity, Lifestyle, and Games categories. Search, app details, free or **paid apps**, and uninstall. **Your own custom apps** show up here too. |
| **💳 Wallet** | Bank and cash balance, a card with your account number and name, paginated history, **transfers by phone number**, and **handing cash to a player next to you** (up to $50,000 within 3 m by default). |
| **🚗 Garage** | All your vehicles with their status and **impound details** (reason, officer, and price). Waypoint, lock or unlock, and **Valet**: an NPC drives the car to you for $100, and you get a refund if it fails. |
| **🗺️ Maps** | GTA map in Satellite, Atlas, or Paper style. **Up to 40 saved pins** with icons, sharing, GPS routes, and your live position. |
| **🌤️ Weather** | City weather, hourly forecast, feels-like, and wind, in °C or °F. Also available as home and lock screen widgets. |
| **⏰ Clock** | World Clock, **Alarms** (repeat, label, sound, and snooze), Stopwatch with laps, and Timer. |
| **🎙️ Voice Memos** | Record, folders, favourites, rename, duplicate, a trash with restore, and sharing. |
| **🧮 Calculator** | Basic arithmetic, `+/-`, `%`, and keyboard input. |
| **🧭 Safari** | An in-phone web browser with back and forward, favourites (Google, YouTube, Wikipedia, Twitch, Reddit, GitHub, and more), and history. |
| **☁️ iCloud** | Sign in with Alpha ID. Sync photos, contacts, messages, and notes. **Find My**, storage usage, and a device list. |
| **📅 Calendar** *(التقويم)* | Month view where you create and delete events. Also available as a widget. |
| **🎨 Themes** *(ثيم)* | **7 theme packs** (Alpha, Orange, Blush, Frost, Emerald, Royal, and Carbon), each with its own wallpaper, icons, and accent colour. Grid or list view, and a reset to the original. |
| **📝 Notebook** | Notes (up to 200), **Word-style documents**, and **Excel-style sheets with formulas**. Up to 12 folders, pins, **reminders** (up to 200), and a journal. **Share with contacts for reading or writing, with live co-editing.** |

---

### 📱 iPhone-style OS

- **First-boot setup:** Hello, language, region, Wi-Fi, activation, Face ID, passcode, Alpha ID, apps & data, location, appearance, and welcome.
- **Home screen:** multiple pages, a dock, folders, drag-to-rearrange, and widgets (Weather, Calendar, and Clock in several sizes).
- **Control Center:** airplane mode, cellular, Wi-Fi, Bluetooth, Focus, orientation lock, silent mode, flashlight, brightness, volume, and shortcuts to Clock, Calculator, and Camera.
- **Notification Center** and a **Dynamic Island** for calls, timers, and ring or silent state (it can be turned off).
- **Lock screen:** digital or analog clock styles and colours, mini widgets (battery, weather, calendar, world clock), and optional Control Center, camera, and flashlight access while locked.
- **Security:** Face ID, a passcode with escalating lockout, and per-app locks for Messages, Photos, and WatchMe.
- **Streamer Mode:** hides numbers, balances, and names, blurs photos, and hides notification previews.
- **Signal:** Wi-Fi (city-wide, areas, or hotspots) and **signal bars from real cell towers**.
- **Appearance:** wallpapers, brightness, and light, dark, or **automatic mode that follows the game clock**.

---

### 🏙️ City, jobs & economy

<details open>
<summary><b>💼 Work: your job, from the phone</b></summary>

- Go on or off duty, see your salary and **weekly hours**, and get GPS to your workplace.
- **Boss tools:** hire players nearby, promote and demote, fire, give bonuses (up to $50,000), use the **company bank**, and post announcements.
- **City directory:** Police, Ambulance, Mechanic, Taxi, Car Dealer, and Real Estate, with call, message, and GPS buttons.
- A company inbox, with an option to message anonymously.

</details>

<details>
<summary><b>🏦 Bank</b></summary>

- Bank and cash balance, a virtual card, deposits and withdrawals.
- **Transfers by phone number or ID**, even to offline players (up to $1,000,000, with a fee and cooldown you can set).
- **Business accounts** and a history of the last 50 transactions.
- Auto-detects your bank script (Renewed-Banking, qb-banking, okokBanking, and more).

</details>

<details>
<summary><b>🚕 TaxiGo · 🛵 Hop · 🚙 Alpha Motors</b></summary>

- **TaxiGo:** go on duty as a taxi driver (optionally locked to a job and vehicle). Take NPC fares with GPS and a live meter. Fares are $25 per km (minimum $5), cancelling costs a 50% fee, and you can take up to 3 jobs at a time. Tracks rating, rides, and earnings.
- **Hop:** Uber-style **player rides and food delivery** from Burger Shot, Cluckin' Bell, and Bean Machine. Rides are $22 per km (minimum $35), payment is taken upfront, and a **4-digit PIN** confirms pickup and drop-off.
- **Alpha Motors:** hourly rentals of **10 vehicles** ($50–$600) in 5 colours, for up to 4 hours, with a driver's licence required. Pick up at one of 3 locations or have a **bot deliver the car to you** (+$200). Keys and fuel are included, and you get a warning before the car is reclaimed.

</details>

<details>
<summary><b>👥 Crew</b></summary>

- Uses your gang automatically, or players create crews on the phone (up to 30 members).
- Crew chat, a **crew bank** (up to $1,000,000; the boss can withdraw), invite and kick.
- **Live member locations** and **alerts with map blips**.
- Works with qbx, qb, esx, rcore, or the built-in crews.

</details>

<details>
<summary><b>📰 News · 🆘 Report</b></summary>

- **News (LS Times):** categories (Breaking, City, LSPD, EMS, Sports, Business, and Official). **Job-gated publishing** for reporters, police, EMS, and government. Stories are up to 2,000 characters, and you can **pin them and send breaking alerts to every phone**.
- **Report:** players open tickets (player, bug, question, vehicle, or refund) with up to **4 photos or videos** and a location. They see how many staff are online, and they chat with the staff member handling the ticket.

</details>

<details>
<summary><b>🛒 MarketPlace · 🕶️ Secret · 🏠 Home</b></summary>

- **MarketPlace:** post listings with a title, price, and photos. Search, manage your own listings, and **call the seller** directly.
- **Secret:** anonymous chat channels. Join and leave, and switch between several accounts.
- **Home:** your owned and shared properties, lock and unlock, GPS, and keyholders. Supports qbx_properties, qb-houses, ps-housing, and qs-housing, or a custom adapter.

</details>

<details>
<summary><b>🖨️ Print · 🔊 Speaker</b></summary>

- **Print:** send photos, documents, or links to a **Bluetooth printer in the world**. Up to 5 copies, and you're charged per page. The printout becomes an **inventory item**.
- **Speaker:** place a **Bluetooth speaker** in the world and play YouTube or any audio in **3D sound** (xsound). It has a library, a **4-digit PIN lock**, and only the owner can pick it up.

</details>

---

### 🎮 Games & competition

| App | Features |
|---|---|
| **🎰 Casino** | A casino wallet funded from cash or bank. **Solo games:** Dice, Slots, Mines, Plinko, Blackjack, Roulette, Video Poker, and Hi-Lo. **Live multiplayer:** Crash, Live Roulette, Jackpot, Coin Flip 1v1, and **Texas Hold'em (2–6 seats, side pots, spectators)**. Also Baccarat and Horse Racing. Bets from $10 to $25,000, leaderboards, and a big-win feed. Each game has a portrait and landscape button. |
| **⚔️ ARENA** | **PvP in the world:** boxing, melee, gunfights from 1v1 up to 5v5 (elimination, TDM, and zone), and FFA. Matchmaking, private lobbies, challenges, and **ranked Elo from Bronze to Champion**, with seasons. Wagers up to $50,000, spectating, and leaderboards. |
| **🏁 Racing** | **Build your own tracks** (circuits and sprints, up to 10 per player). Host races with buy-ins, up to **12 racers**, and 1v1 bets. The prize split is 60/25/15, with driver ratings, track records, best laps, and anti-cheat checks. |
| **🎱 8 Ball** | A pool game refereed by the server, with rooms from $100 to $50,000, a 30-second shot clock, money challenges with friends, spectating, AI practice, and a leaderboard. |
| **🪂 Skydive** | Book group jumps (up to 6) from 3 airfields, with a real plane and pilot. Land on one of 6 targets. You're scored on accuracy and freefall, with chute colours, money rewards, and a leaderboard. |
| **🃏 Bluff Bar** | Liar's cards or liar's dice for 2–4 players, with stakes and bots. **The loser faces revolver roulette.** Spectators are welcome. |
| **👋 Slap** | A slap duel in the world against a player nearby, with a stake. Charge and brace timing, critical hits, and KO animations. |
| **🚇 Metro Dash** | An endless runner with 6 upgrade levels, 6 skins, missions, daily streaks, and a high-score leaderboard checked by the server. |
| **🔫 Roulette** | GPS guide to the Russian roulette tables in the city. |

---

### 💬 Social media

Each social app has **its own username and password**, and one profile photo and cover per phone number is shared across them.

| App | Features |
|---|---|
| **🌍 FaceWorld** | A public city feed with text and photo posts, locations with GPS, likes and comments, trending, **job-verified badges**, and official announcements. |
| **📸 PhotoFlow** | Instagram-style. Private accounts and follow requests, posts with up to 5 photos, **stories with view counts**, DMs, explore, an activity feed, and verified badges. |
| **👻 Snapster** | Snapchat-style. **Disappearing snaps** (3, 5, or 10 seconds), streaks, 24-hour stories, up to 150 friends, and a **Snap Map with Ghost Mode**. |
| **🎬 ClipTok** | TikTok-style. For You and Following feeds, likes, saves, comments, sounds, pinned clips, and verified badges. |
| **🟢 ChatWave** | WhatsApp-style, using your phone number. 1:1 chats and **groups of up to 50** with admins. Photos, location, replies, read receipts, mute, **delete for everyone**, and voice and video calls. |
| **🔴 WatchMe** | Live streaming from your **phone camera or chest BodyCam**. Viewers watch through your camera and hear your voice. Live comments, **8 reactions**, follows with "went live" alerts, and replays (Moments) with peak viewers. |

Staff can moderate all of them from the **Admin** app (see below).

---

### 🔋 Hardware & devices

- **Battery:**
  - Active and idle drain, battery health that wears down, and charge cycles. The phone shuts off at 0%.
  - A **USB cable** charges it in vehicles, and a **power bank** holds 10 full charges.
- **Dual SIM:** two lines in one phone with an active-line switcher. Insert or eject SIMs, and change your number with `/lfchangenumber` (price and cooldown configurable).
- **Phone prop:** a live prop in your hand in several colours, and the on-screen frame colour follows the one you hold. Screen cracks (4 levels) and a repair kit are included.
- **BodyCam:**
  - Pair it over Bluetooth and it's worn on the upper chest, police style.
  - Go live on **WatchMe**, or record in **CamLink**, where police and EMS can watch it.
- **Alpha Pods:** Bluetooth earbuds for hands-free calls, with a tap key to answer or hang up.
- **Speaker & printer:** placeable Bluetooth devices in the world (see City above).

---

### 🛡️ Admin app & staff tools

The **Admin** app is a full staff control panel inside the phone. **It only appears on staff phones.**

<details open>
<summary><b>🔐 Access</b></summary>

- ACE permissions: `admin`, `god`, `command.lfphone_admin`, `qbcore.admin`, or `qbcore.god`. Also the Qbox/QB `admin` or `god` permission, or your ESX or vRP admin group.
- **Every action is checked again on the server**, so a player can't call an admin action by faking the UI.
- Turn it on or off, and set its name, description, and icon, in `config/config.admin.lua`.

</details>

<details open>
<summary><b>🎯 Player picker</b></summary>

- Search every online player by **name, ID, or phone number**.
- A player card shows the name, server ID, phone number, ping, **passcode and Face ID status**, **battery %** and **battery health** with a bar.
- Header buttons: **txAdmin** (closes the phone and opens txAdmin) and **refresh**.

</details>

<details>
<summary><b>📱 Device tab</b></summary>

| Action | What it does |
|---|---|
| **Change number** | Set a new number, or leave it empty for a random one. |
| **Clear passcode & Face ID** | Unlocks a player who forgot their code, instantly and live. |
| **Repair screen** | Removes all cracks. |
| **Crack screen** | Sets screen damage from level 0 to 3. |
| **Set battery** | Any level from 0 to 100%, saved to the database. |
| **Find linked Mail** | Finds the Mail accounts on the player's phone. |
| **Factory reset** ⚠️ | Fully erases the phone. You have to type `RESET` to confirm. |

</details>

<details>
<summary><b>💳 SIM tab</b></summary>

- **Create SIM** for the player, with a number you choose or a random one.
- **Change SIM number.**
- **Recover SIM** by number and IMEI, for a lost or stolen SIM.

</details>

<details>
<summary><b>💬 Social tab: moderation for every app</b></summary>

Browse the content of **one player or everyone**, search by text or account name, then **edit** or **delete** any item (25 per page, with Load more).

| App | What staff can moderate | Account tools |
|---|---|---|
| **PhotoFlow** | Posts, comments, direct messages | Verify / unverify, reset password |
| **ClipTok** | Videos, comments, direct messages | Verify / unverify, reset password |
| **FaceWorld** | Posts, comments | Verify / unverify, reset password |
| **ChatWave** | Messages | — |
| **Snapster** | Stories | — |
| **Secret** | Messages | Reset password |
| **Messages** | Text messages | — |
| **Mail** | Mail | Reset password, find linked Mail |
| **News** | Articles | — |

> Opening **private messages** is always written to the staff log, so staff privacy access is accountable.

</details>

<details>
<summary><b>🧩 Apps tab: server-wide app switches</b></summary>

- **Turn any app off for every player** on the server, with search and a counter of how many apps are off.
- Apps stay off **after a server restart**.
- **Settings** and **Admin** are protected and can't be turned off.

</details>

<details>
<summary><b>📢 Broadcast tab</b></summary>

- A title (optional, up to 60 characters) and a message (up to 500), with a **live preview**.
- **Send to everyone** or **to the selected player**.
- Shows as a **full-screen announcement** on the phone, plus a notification.

</details>

<details>
<summary><b>📜 Log tab: audit trail</b></summary>

- The **last 60 staff actions**: the action, staff member → target, details, and time.
- Every action is also sent to your server logs.

</details>

<details>
<summary><b>🆘 Report staff inbox · 📰 News moderation · ⌨️ commands</b></summary>

**Report app (staff side)**

- **Inbox** with an open-reports badge and **Open / Mine / Resolved** filters.
- **Claim / Release** a report (the player is told who is handling it), **Resolve / Reopen**, and a reply chat.
- **Go to player** and **Bring player** buttons from inside the report.
- New reports notify every online staff member.

**News moderation**

- Staff can **pin, unpin, and delete** any story, and publish **Official briefs** that are pinned and sent to the whole city.

**In-app power**

- Staff can delete any post, video, or comment in PhotoFlow, FaceWorld, and ClipTok, and any MarketPlace listing, directly from the app.

**Staff commands**

| Command | Use |
|---|---|
| `/lfbroadcast [id] Title \| Message` | Send an announcement (to everyone, or to one ID) |
| `/lfverify [app] [username] [on\|off]` | Verified badge on PhotoFlow, ClipTok, or FaceWorld |
| `/changepassword [app] [username] [password]` | Reset a social, Mail, or Secret password |
| `/lfsetnumber [id] [number]` | Change a player's number |
| `/lfresetpin [id or number]` | Clear passcode and Face ID |
| `/lfscreendamage [id] [level]` | Set screen damage |
| `/lfcreatesim` · `/lfchangesim` · `/lfrecoversim` | SIM tools |

</details>

---

### 🔌 Integrations (auto-detected)
- **Frameworks:** qbox, qb-core, esx, ox_core, vrp, standalone
- **Inventories:** ox_inventory, qs-inventory, codem-inventory, tgiann-inventory, ak47_inventory, origen_inventory…
- **Garages:** jg-advancedgarages, cd_garage, qs-advancedgarages, okokGarage, qbx_garages…
- **Housing:** qbx_properties, ps-housing, qb-houses, qs-housing, or `RegisterHousing` for anything else
- **Fuel:** ox_fuel, cdn-fuel, LegacyFuel, Renewed-Fuel, ps-fuel, lc_fuel, and 10+ more
- **Banking:** Renewed-Banking, qb-banking, okokBanking, fd_banking, esx…
- **Voice:** pma-voice, mm_radio, SaltyChat, TokoVOIP, mumble-voip
- **Custom apps:** add your own apps to the home screen and App Store with `config.custom_apps.lua`.

<details>
<summary><b>Optional extras (off by default)</b></summary>

- **Licensed HTML5 games pack:** off by default. Only turn it on if you own the rights to those games (`config.licensed_games.lua`).
- **Standalone Reminders app:** off, because reminders are already inside Notebook.

</details>

---

## 📦 المتطلبات (Dependencies)

| Resource | Required | Notes |
|---|:---:|---|
| [oxmysql](https://github.com/overextended/oxmysql) | ✅ | Database |
| [ox_lib](https://github.com/overextended/ox_lib) | ✅ | Callbacks, notify, helpers |
| `alpha-phone-props` | ✅ | Phone, BodyCam, speaker & pods models (ships with this script) |
| Framework: `qbx_core` / `qb-core` / `es_extended` / `ox_core` | ✅ | One of them, or `standalone` |
| [ox_inventory](https://github.com/overextended/ox_inventory) | ⭐ Recommended | Unique phones with metadata (other inventories supported) |
| [pma-voice](https://github.com/AvarianKnight/pma-voice) | ⭐ Recommended | Calls, radio, live voice |
| [xsound](https://github.com/Xogy/xsound) | Optional | 3D audio for the Speaker |

Server artifacts must support Asset Escrow. Use a recent FiveM server build.

---

## ⚙️ التثبيت (Installation)

### 1. Download from Keymaster
Download **Alpha Phone** from **[keymaster.fivem.net](https://keymaster.fivem.net) → Granted Assets** (see [Purchase](#-الشراء-purchase--cfxre-keymaster)).

### 2. Copy the folders
Put both folders inside `resources`. The folder names **must stay exactly** as below:

```
resources/
└── [script]/
    ├── alpha-phone/
    └── alpha-phone-props/
```

### 3. `server.cfg`
Order matters: dependencies first, then the props, then the phone. `sv_licenseKey` must come from the account that bought the script.

```cfg
sv_licenseKey "your_key_from_the_buyer_account"

ensure oxmysql
ensure ox_lib
ensure ox_inventory
ensure qbx_core            # or qb-core / es_extended / ox_core

ensure pma-voice

ensure alpha-phone-props
ensure alpha-phone
```

> [!WARNING]
> `alpha-phone-sandbox` (`/phbot`) is a solo testing lab. **Do not** start it on a live server.

### 4. Database
Pick **one** of these:

- **Automatic (recommended):** leave `Config.DatabaseChecker.AutoFix = true` in `config/config.lua` and restart once. The tables are created and repaired on boot.
- **Manual:** import `sql/INSTALL_ON_NEW_SERVER.sql` into the same database as your `mysql_connection_string`.

> [!CAUTION]
> The SQL file is meant for a **new** server. It drops `phone_crypto` and also creates the `lh-phonestores` tables. Back up your database before importing on an existing city.

### 5. Inventory items
- **ox_inventory:** paste `install/ox_inventory_items.lua` into `ox_inventory/data/items.lua`.
- **QB-Core:** paste `install/qb-core_shared_items.lua` into `qb-core/shared/items.lua`.
- Copy the images from `install/inventory-images/` into `ox_inventory/web/images/` (or your inventory's image folder). The file name must match the item id.

### 6. API keys
Put your Fivemanage / Discord tokens in `modules/secrets/api_keys.lua` **only**.

> [!IMPORTANT]
> Never commit real keys to GitHub. Add `modules/secrets/api_keys.lua` to `.gitignore` or publish it empty.

### 7. Staff access
Give your staff the Admin app with an ACE permission, for example:

```cfg
add_ace group.admin command.lfphone_admin allow
```

### 8. Configure & restart
Set your framework in `config/config.lua` (next section), then restart the server.

---

## 🛠️ الإعدادات (Configuration)

All settings live in `config/`. The load order is listed in `config/00_index.lua`.

### Main options (`config/config.lua`)

```lua
Config.Framework = "qbox"            -- auto | qbox | qb | esx | ox | vrp | standalone

Config.Item.Require   = true         -- a phone item is needed to open the phone
Config.Item.Unique    = true         -- every phone item has its own number (metadata)
Config.Item.Inventory = "ox_inventory"

Config.Voice.System = "auto"         -- pma (recommended) | mumble | ...

Config.DefaultLocale = "en"          -- "ar" for the Arabic UI
Config.CityName      = "Los Santos"
Config.FrameColor    = "#8B1518"     -- fallback; each phone item sets its own frame colour

Config.KeyBinds.Open = { Command = "phone", Bind = "M" }

Config.Camera.DigitalOnly    = true  -- zoom inside the preview, world FOV untouched
Config.Camera.ZoomLevels     = { 1.0, 2.0, 3.0, 5.0, 10.0 }
Config.Camera.MaxDigitalZoom = 10.0
Config.Camera.Hybrid = { Enabled = true, DigitalMax = 2.0, DimOutside = 0.88 }  -- digital up to 2x, then optical

Config.UploadMethod.Image = "Fivemanage"   -- Fivemanage | Local | Custom
Config.UploadMethod.Video = "Fivemanage"
Config.UploadMethod.Audio = "Fivemanage"

Config.Garages     = "auto"
Config.HouseScript = "auto"
Config.Fuel        = "auto"
```

### Config file map

| File | Purpose |
|---|---|
| `config.lua` | Framework, items, voice, camera, uploads, key binds |
| `config.city.lua` | Enable / disable each city & social app, names, icons, default apps, and each app's limits and prices |
| `config.admin.lua` | Admin app (staff tools) |
| `config.broadcast.lua` | Cell broadcast title and command |
| `config.battery.lua` | Drain rate, USB cable, power bank |
| `config.sim.lua` | Dual SIM |
| `config.calls.lua` | Calls and FaceTime |
| `config.bodycam.lua` | BodyCam item, Bluetooth pairing, chest model |
| `config.pods.lua` | Alpha Pods (earbuds) |
| `config.speaker.lua` / `config.printer.lua` | Bluetooth speaker and printer |
| `config.banking.lua` | Bank app and transfers |
| `config.integrations.lua` | Garage, housing, fuel, valet, company money |
| `music.lua` | Song catalogue for the Music app |
| `config.custom_apps.lua` | Your own App Store / home screen apps |
| `config.hooks.lua` | `CanOpenPhone`, `OnPhoneOpen`, `OnPhoneClose` |
| `config.licensed_games.lua` | Third-party HTML5 games (keep **off** unless you own the rights) |
| `config.developer.lua` | Debug options (dev servers only) |
| `config.json` · `locales/*.json` | Wallpapers, ringtones, UI text |

---

## 🎒 العناصر (Inventory items)

| Item id | Role |
|---|---|
| `phone` | Default handset (Alpha Red). Use it to open the phone. |
| `phone_blue` · `phone_orange` · `phone_alpha` · `phone_obsidian` · `phone_midnight` · `phone_ember` · `phone_green` | Colourways |
| `lf_sim_card` | Dual SIM |
| `usb_cable` | Charges the phone **while seated in a vehicle** |
| `lf_powerbank` | Portable charger with 10 full charges; refill it with the USB cable in a car |
| `phone_repair_kit` | Repairs a cracked screen |
| `bodycam` | Chest camera: pair it over Bluetooth, then stream on WatchMe or record in CamLink |
| `printerdocument` | Printed document from the Print app |

---

## 🔋 البطارية والشحن (Battery & charging)

**USB cable:** sit in a car (the engine doesn't need to be on) and use the cable. The phone shows a green battery with a bolt and gains about 1% every 5–10 s (0 → 100% in about 12 minutes). Leaving the vehicle unplugs it.

Charging priority while plugged in:
1. Phone below 100% → charge the phone.
2. Phone full and power bank not full → charge the power bank.
3. Both full → notify and unplug.

**Power bank:** works anywhere and holds 10 full charges (`Charges: 10/10` in metadata). One charge is used every time the phone reaches 100% from the bank.

---

## 🧑‍💻 للمطورين (Developer API)

```lua
-- Client
exports["alpha-phone"]:ToggleOpen(true)
exports["alpha-phone"]:IsOpen()
exports["alpha-phone"]:GetBattery()
exports["alpha-phone"]:IsCharging()
exports["alpha-phone"]:GetChargeSource()   -- "vehicle" | "powerbank" | nil
exports["alpha-phone"]:GetBodyCam()

-- Server
exports["alpha-phone"]:SendNotification(source, { app = "Messages", title = "Hi", content = "..." })
exports["alpha-phone"]:GetBatteryInfo(source)
exports["alpha-phone"]:ReplacePhoneBattery(source)
exports["alpha-phone"]:RepairScreen(source)
```

**Usable-item events** (ox `client.event` / qb `CreateUsableItem`):
`lf-phone:client:usePhoneItem` · `lf-phone:client:useUsbCable` · `lf-phone:client:usePowerBank` · `lf-phone:client:useSimCard` · `lf-phone:client:useRepairKit` · `lf-phone:client:useBodyCam`

<details>
<summary><b>Project structure</b></summary>

```
alpha-phone/
├── config/            Owner settings + locales (editable)
├── shared/            Helpers, framework glue, media upload
├── modules/
│   ├── bridge/        Framework & inventory adapters (editable)
│   ├── systems/       Battery, charging, Bluetooth, BodyCam, notifications…
│   ├── apps/          System / city / social app logic
│   └── secrets/       API keys (never publish real ones)
├── ui/dist/           NUI: React shell + iframe city apps
├── install/           Inventory items + images
├── sql/               Manual install SQL
└── docs/              Banner & screenshots for this README
```

- Events use the `lf-phone:` prefix, and `provide 'lf-phone'` keeps older scripts working.
- City and social apps load in iframes from `ui/dist/apps/<app>/`.
- The SQL keeps the original engine names, while the UI shows the new brands. PhotoFlow uses the `phone_instagram_*` tables and ClipTok uses `phone_tiktok_*`. Don't rename the tables.

</details>

---

## 🩺 حل المشاكل (Troubleshooting)

| Problem | Fix |
|---|---|
| `You lack the required entitlement` | Your `sv_licenseKey` isn't from the Cfx.re account that bought the script. Use a key from that account, or transfer the asset in Keymaster. |
| Phone doesn't open | Check the `ensure` order, and that you hold a `phone` item that matches `Config.Item.Names`. |
| Admin app doesn't show | Give the ACE `command.lfphone_admin` (or the framework `admin` permission), then reopen the phone. |
| Phone prop is invisible | `alpha-phone-props` must start **before** `alpha-phone`. Check F8 for `[alpha-phone-props] ... valid=true`. |
| No voice in calls | Install pma-voice and set `Config.Voice.System = "pma"`. |
| Photos don't upload | Set your Fivemanage key in `modules/secrets/api_keys.lua`, or use `Config.UploadMethod = "Local"`. |
| BodyCam doesn't show on the chest | Rejoin the server after restarting the props. If it still doesn't show, run `/bodycamprobe` and set `Config.BodyCam.Clothing.Drawable`. |
| An app is missing for everyone | It may be turned off in **Admin → Apps**, or disabled in `config.city.lua`. |
| Missing tables | Keep `Config.DatabaseChecker.AutoFix = true` and restart, or import the SQL file. |

---

## 💬 الدعم (Support)

- 🛒 Official store: [alphastorefivem.store](https://alphastorefivem.store)
- 🔑 Downloads & updates: [keymaster.fivem.net](https://keymaster.fivem.net) → Granted Assets
- 💬 Discord: [discord.gg/CGnrJGVX6k](https://discord.gg/CGnrJGVX6k)

When you report a bug, include your **Cfx.re account name**, framework, inventory, `ensure` order, and the F8 or server console error, not just a screenshot of the phone.

---

<div align="center">

**Made with ❤️ by [Alpha Store](https://alphastorefivem.store)**

Protected with Cfx.re Asset Escrow. `config/`, `modules/bridge/`, `shared/`, and the iframe apps stay editable.

</div>
