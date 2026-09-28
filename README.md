<div align="center">

![Alpha Phone](docs/banner.png)

# 📱 Alpha Phone

**An iPhone-style phone for FiveM with 40+ apps: radio groups, live co-editing, ranked PvP, a casino, social media, live streaming, a real battery, Dual SIM, and in-world devices.**

هاتف احترافي بتصميم iPhone لسيرفرات FiveM، فيه أكثر من 40 تطبيق، منها راديو بمجموعات، وتحرير مشترك مباشر، وساحات قتال مصنّفة، وكازينو، وتواصل اجتماعي، وبث مباشر، وأجهزة حقيقية داخل اللعبة.

![Version](https://img.shields.io/badge/version-1.1.0-c1121f?style=for-the-badge)
![FiveM](https://img.shields.io/badge/FiveM-cerulean-1f1f1f?style=for-the-badge)
![Lua](https://img.shields.io/badge/Lua-5.4-2c2d72?style=for-the-badge&logo=lua)
![Frameworks](https://img.shields.io/badge/QBox%20%7C%20QB--Core%20%7C%20ESX%20%7C%20OX-supported-8d0b14?style=for-the-badge)

[Store](https://alphastorefivem.store) · [Discord](https://discord.gg/CGnrJGVX6k)

</div>

---

## 📑 Contents

- [Preview](#-المعاينة-preview)
- [Features](#-المميزات-features)
- [Dependencies](#-المتطلبات-dependencies)
- [Installation](#️-التثبيت-installation)
- [Configuration](#️-الإعدادات-configuration)
- [Inventory items](#-العناصر-inventory-items)
- [Battery & charging](#-البطارية-والشحن-battery--charging)
- [Developer API](#-للمطورين-developer-api)
- [Troubleshooting](#-حل-المشاكل-troubleshooting)
- [Support](#-الدعم-support)

---

## 📸 المعاينة (Preview)

<div align="center">

<img src="docs/screenshots/home.jpg" width="720" alt="Home screen in game">

</div>

<!--
Add more in-game shots to docs/screenshots/ and list them here, e.g.:
| Camera | Messages | WatchMe |
|:---:|:---:|:---:|
| <img src="docs/screenshots/camera.jpg" width="240"> | <img src="docs/screenshots/messages.jpg" width="240"> | <img src="docs/screenshots/watchme.jpg" width="240"> |
-->

---

## ✨ المميزات (Features)

### ⚡ Highlights
- **40+ apps**, each one server-authoritative and backed by MySQL, in a full iPhone-style shell with first-boot setup, Face ID, and auto dark mode.
- **Real multiplayer:** radio channels, group chats, shared albums, shared notes with live co-editing, crews, poker tables, ranked PvP arenas, races, and group skydives.
- **Real economy:** transfers, company accounts, fares, rentals, entry fees, bets, and house cuts, all paid through your framework's cash and bank.
- **Physical devices in the world:** a live phone prop in four colours, a chest BodyCam, Bluetooth earbuds, a placeable speaker, and AirPrint printers.
- **Staff tools:** an admin app, a content moderation panel for every social app, a report inbox, and cell broadcasts.
- **Languages:** full Arabic and English UI.

---

### 📞 Phone & communication

<details open>
<summary><b>📻 Radio: a full walkie-talkie system</b></summary>

- Tune any frequency from **1 to 500** (decimals optional), and everyone on the same frequency talks together as a group.
- **Live member list** and a **talking indicator** that shows who is speaking right now.
- **Job- and grade-locked ranges and channels** (for example, 1–10 for government only). Players are removed automatically when they lose the job.
- Named channels and up to **12 favourites**.
- Works with **pma-voice, mm_radio, SaltyChat, TokoVOIP, and mumble-voip** (auto-detected), with a volume setting from 1 to 100.

</details>

<details>
<summary><b>📞 Calls & FaceTime</b></summary>

- Voice calls with in-call effects, **anonymous calls**, mute, speaker, and blocked numbers.
- **FaceTime video calls** over WebRTC, with the option to switch from voice to video in the middle of a call.
- **Voicemail:** record, list, delete, and get notified.
- **Company lines:** calling a job rings every employee on duty, and the first one to answer takes the call.
- Airplane mode, a dead battery, or no signal make you unreachable.

</details>

<details>
<summary><b>💬 Messages, ChatWave, Contacts & Mail</b></summary>

- **Messages:** direct messages and **group chats of up to 32 people** with an owner, rename, add members, leave, and ownership transfer. Supports attachments, location tags, GIFs, voice, and in-chat payments.
- **ChatWave (WhatsApp-style):** 1:1 chats and groups with admins (promote, demote, and remove). Includes photos, location, replies, read receipts, mute, delete for everyone, and voice and video calls.
- **Contacts:** avatars, email, address, favourites, and blocking.
- **Mail:** accounts at your city domain, attachments, search, and real-time push.

</details>

<details>
<summary><b>📷 Camera, ProCam & Gallery</b></summary>

- **Camera:** photo, video, selfie, portrait, panorama and slow-mo modes.
- **Digital zoom up to 10×:** Catmull-Rom upscaling with adaptive sharpening. The zoom happens inside the preview, so the world camera never zooms. Control it with the mouse wheel, by dragging, or with quick chips.
- **ProCam:** photo, portrait, cinematic, pro, video and burst modes; 10+ colour looks with strength control; stabilisation, depth of field, tap-to-focus, torch, landscape mode, and saved presets.
- **Gallery:** favourites, albums, and **shared albums** with members you invite over AirShare. Updates reach members live.
- **Uploads:** through Fivemanage, a local folder, or your own uploader.

</details>

<details>
<summary><b>⚙️ Settings, security & signal</b></summary>

- **Security:** Face ID, a passcode with escalating lockout, and per-app locks for Messages, Photos, and WatchMe.
- **Streamer Mode:** hides numbers, balances, and names, blurs photos, and hides notification previews.
- **Connectivity:** airplane mode, Wi-Fi (city-wide, areas, or hotspots), Bluetooth, and **signal bars from real cell towers**.
- **Personalisation:** themes (Alpha, Orange, Blush, Frost, Emerald, Royal, Carbon), wallpapers, brightness, and light, dark, or automatic mode that follows the game clock.
- **More:** Focus / Do Not Disturb, AirDrop (off, contacts, or everyone), and an About page with IMEI and serial.
- **First boot:** a full iPhone-style setup covering language, Wi-Fi, Face ID, passcode, Alpha ID, iCloud restore, and appearance.

</details>

---

### 🔋 Hardware & devices

- **Battery:**
  - Active and idle drain, battery health that wears down, and charge cycles. The phone shuts off at 0%.
  - A **USB cable** charges it in vehicles, and a **power bank** holds 10 full charges.
- **Dual SIM:** two lines in one phone with an active-line switcher. Insert or eject SIMs, and change your number with `/lfchangenumber` (price and cooldown configurable).
- **Phone prop:** a live prop in your hand in 4 colours, and the on-screen frame colour follows the one you hold. Screen cracks and a repair kit are optional.
- **BodyCam:**
  - Pair it over Bluetooth and it's worn on your chest.
  - Go live on **WatchMe**, or record in **CamLink**, where police and EMS can watch it or cast it to a TV or tablet.
- **Alpha Pods:** Bluetooth earbuds for hands-free calls, with a tap key to answer or hang up.
- **Speaker:** place a Bluetooth speaker in the world and play YouTube or any URL in **3D audio** (xsound). It can be locked with a PIN, and only the owner can pick it up.
- **Print:** AirPrint to printers in the world. Print photos, images, or typed documents, which become an inventory item. You're charged per page.

---

### 🏙️ City & jobs

| App | Features |
|---|---|
| **TaxiGo** | Go on duty as a driver (optionally locked to a job and vehicle). Take NPC fares with GPS and a live meter. Fares are paid per kilometre. Tracks rating, rides, and earnings. |
| **Hop** | Uber-style **player rides and food delivery** (Burger Shot, Cluckin' Bell, Bean Machine). Payment is taken upfront, and a 4-digit PIN confirms pickup and drop-off. |
| **Alpha Motors** | Hourly car and bike rentals. Pick up from the garage or have a **bot deliver the car to you**. Keys and fuel are included, with an expiry warning before it's reclaimed. |
| **Work** | City services directory. Duty hours and company announcements. **Boss tools:** hire, fire, and promote nearby players, set salaries, payroll, company ledger, society bank, and bonuses. |
| **Crew** | Gang members and online count, crew chat, crew bank, invite and kick, **live member locations**, and alerts with map blips. Works with qbx, qb, esx, rcore, or built-in crews. |
| **Banking** | Bank and cash balances, a virtual card, transfers by phone number (even offline) or ID, deposits and withdrawals, business accounts, and history. Auto-detects your bank script. |
| **Notebook** | Notes, **Word-style documents**, and **Excel-style sheets with formulas**. Folders, pins, reminders, and a journal. **Share with contacts (read or write) with live co-editing.** |
| **Calendar** | Month view with events and notes. |
| **iCloud** | Storage usage, sync toggles, device list, and Find My. |
| **Maps** | Personal pins with icons, GPS waypoints, and live position. Share pins. |
| **Home** | Owned and shared properties, lock and unlock, GPS, and keyholders. Supports qbx_properties, qb-houses, qs-housing, or a custom adapter. |
| **Safari** | In-phone web browser with search, history, and favourites. |
| **News** | LS Times with categories. **Job-gated publishing** (reporters, police, EMS, government). Pinning, moderation, and breaking-news alerts to every phone. |
| **Report** | Players send reports with photos. Staff get an inbox with claim, reply, status, and goto or bring. |
| **MarketPlace · Pages · Secret** | Buy and sell listings, classified ads, and anonymous chat channels. |

---

### 🎮 Games & competition

| App | Features |
|---|---|
| **Casino** | Deposit cash or bank money into the casino wallet. **Solo games:** Dice, Slots, Mines, Plinko, Blackjack, Roulette, Video Poker, and Hi-Lo. **Live multiplayer:** Crash, Live Roulette, Jackpot, Coin Flip 1v1, and **Texas Hold'em (2–6 seats, side pots, spectators)**. Also Baccarat and Horse Racing. Includes leaderboards and a big-win feed. |
| **ARENA** | **In-world PvP:** boxing, melee, gunfights from 1v1 up to 5v5 (elimination, TDM, zone), and FFA. Matchmaking, private lobbies, challenges, and **ranked Elo from Bronze to Champion**. Wagers, spectating, and leaderboards. |
| **Racing** | Build your own tracks, circuits, and sprints. Host races with buy-ins, up to 12 racers, and **1v1 bets**. Track records, best laps, and anti-cheat checks. |
| **8 Ball Pool** | A server-refereed game with ranked rooms and entry fees. Money challenges with friends, spectating, and AI practice. Leaderboard. |
| **Skydive** | Book group jumps (up to 6) with a real plane and pilot. Scoring for accuracy and freefall, with money rewards and a leaderboard. |
| **Bluff Bar** | Liar's cards or liar's dice for 2–4 players with stakes. **The loser faces revolver roulette.** Spectators and bots. |
| **Slap** | An endurance slap duel in the world against nearby players, with a stake. Uses charge-and-brace timing, crits, and KO animations. |
| **Metro Dash** | An endless runner with upgrades, skins, missions, daily streaks, and a high-score leaderboard checked by the server. |
| **Roulette** | GPS guide to Russian roulette tables in the city. |

---

### 📱 Social media

| App | Features |
|---|---|
| **FaceWorld** | Public city feed with text and photo posts, locations with GPS, likes and comments, trending, **job-verified badges**, and official announcements. |
| **PhotoFlow** | Instagram-style. Private accounts and follow requests, posts with up to 5 photos, **stories with view counts**, DMs, explore, activity feed, and verified badges. |
| **Snapster** | Snapchat-style. **Disappearing snaps**, streaks, 24-hour stories, **Snap Map with Ghost Mode**, and friends. |
| **ClipTok** | TikTok-style. For You and Following feeds, likes, saves, comments, sounds, pinned clips, and verified badges. |
| **WatchMe** | Live streaming from your **phone camera or a chest BodyCam**. Viewers watch through your camera and hear your voice. Includes live comments, follows with "went live" alerts, and replays with peak viewers. |

All social apps can be moderated from the admin panel.

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

---

## 📦 المتطلبات (Dependencies)

| Resource | Required | Why |
|---|:---:|---|
| [oxmysql](https://github.com/overextended/oxmysql) | ✅ | Database |
| [ox_lib](https://github.com/overextended/ox_lib) | ✅ | Callbacks, notify, helpers |
| `alpha-phone-props` | ✅ | Phone, BodyCam, speaker & pods models (ships with this script) |
| Framework: `qbx_core` / `qb-core` / `es_extended` / `ox_core` | ✅ | One of them, or `standalone` |
| [ox_inventory](https://github.com/overextended/ox_inventory) | ⭐ Recommended | Unique phones with metadata (other inventories supported) |
| [pma-voice](https://github.com/AvarianKnight/pma-voice) | ⭐ Recommended | Calls, live voice, nearby voice in recordings |

---

## ⚙️ التثبيت (Installation)

### 1. Copy the folders
Put both folders inside `resources`. The folder names **must stay exactly** as below:

```
resources/
└── [script]/
    ├── alpha-phone/
    └── alpha-phone-props/
```

### 2. `server.cfg`
Order matters: dependencies first, then the props, then the phone.

```cfg
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

### 3. Database
Pick **one** of these:

- **Automatic (recommended):** leave `Config.DatabaseChecker.AutoFix = true` in `config/config.lua` and restart once. The tables are created and repaired on boot.
- **Manual:** import `sql/INSTALL_ON_NEW_SERVER.sql` into the same database as your `mysql_connection_string`.

> [!CAUTION]
> The SQL file is meant for a **new** server. It drops `phone_crypto` and also creates the `lh-phonestores` tables. Back up your database before importing on an existing city.

### 4. Inventory items
- **ox_inventory:** paste `install/ox_inventory_items.lua` into `ox_inventory/data/items.lua`.
- **QB-Core:** paste `install/qb-core_shared_items.lua` into `qb-core/shared/items.lua`.
- Copy the images from `install/inventory-images/` into `ox_inventory/web/images/` (or your inventory's image folder). The file name must match the item id.

### 5. API keys
Put your Fivemanage / Discord tokens in `modules/secrets/api_keys.lua` **only**.

> [!IMPORTANT]
> Never commit real keys to GitHub. Add `modules/secrets/api_keys.lua` to `.gitignore` or publish it empty.

### 6. Configure & restart
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
Config.FrameColor    = "#8B1518"

Config.KeyBinds.Open = { Command = "phone", Bind = "M" }

Config.Camera.DigitalOnly    = true  -- zoom inside the preview, world FOV untouched
Config.Camera.ZoomLevels     = { 1.0, 2.0, 3.0, 5.0, 10.0 }
Config.Camera.MaxDigitalZoom = 10.0

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
| `config.city.lua` | Enable / disable each city & social app, labels, icons |
| `config.battery.lua` | Drain rate, USB cable, power bank |
| `config.sim.lua` | Dual SIM |
| `config.calls.lua` | Calls and FaceTime |
| `config.bodycam.lua` | BodyCam item, Bluetooth pairing, chest model |
| `config.pods.lua` | Alpha Pods (earbuds) |
| `config.speaker.lua` / `config.printer.lua` | Bluetooth speaker and AirPrint |
| `config.banking.lua` | Banking app and transfers |
| `config.integrations.lua` | Garage, housing, fuel, valet, company money |
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
| Phone doesn't open | Check the `ensure` order, and that you hold a `phone` item that matches `Config.Item.Names`. |
| Phone prop is invisible | `alpha-phone-props` must start **before** `alpha-phone`. Check F8 for `[alpha-phone-props] ... valid=true`. |
| No voice in calls | Install pma-voice and set `Config.Voice.System = "pma"`. |
| Photos don't upload | Set your Fivemanage key in `modules/secrets/api_keys.lua`, or use `Config.UploadMethod = "Local"`. |
| BodyCam doesn't show on the chest | Rejoin the server after restarting the props. If it still doesn't show, run `/bodycamprobe` and set `Config.BodyCam.Clothing.Drawable`. |
| Missing tables | Keep `Config.DatabaseChecker.AutoFix = true` and restart, or import the SQL file. |

---

## 💬 الدعم (Support)

- 🛒 Store: [alphastorefivem.store](https://alphastorefivem.store)
- 💬 Discord: [discord.gg/CGnrJGVX6k](https://discord.gg/CGnrJGVX6k)

When you report a bug, include your framework, inventory, `ensure` order, and the F8 or server console error, not just a screenshot of the phone.

---

<div align="center">

**Made with ❤️ by [Alpha Store](https://alphastorefivem.store)**

Escrowed files are protected. `config/`, `modules/bridge/`, `shared/`, and the iframe apps stay editable.

</div>
