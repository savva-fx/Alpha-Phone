<div align="center">

![Alpha Phone](docs/banner.png)

# 📱 Alpha Phone

**An iPhone-style phone for FiveM: calls, messages, 30+ city & social apps, a real battery, Dual SIM, and a live in-hand prop.**

هاتف احترافي بتصميم iPhone لسيرفرات FiveM، فيه مكالمات ورسائل وأكثر من 30 تطبيق مدينة وتواصل اجتماعي.

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

### 📞 Core phone
- **Calls:** voice calls with call effects (pma-voice), FaceTime video, voicemail-style missed calls.
- **Messages:** SMS, groups, media, and location sharing.
- **Contacts:** contacts, favourites, and blocking.
- **Dual SIM:** a second number on the same handset (`lf_sim_card`).
- **Real battery:** drain, health, charge cycles, a USB cable for cars, and a 5-charge power bank.
- **Live hand prop:** four colourways of the phone model, plus a cracked screen and a repair kit.
- **Face ID and PIN lock**, with auto dark mode that follows the in-game clock.
- **Languages:** full Arabic and English UI (`config/locales/ar.json`, `en.json`).

### 📷 Camera & media
- **Camera:** photo, video, portrait, panorama and selfie modes.
- **Smooth digital zoom up to 10×:** Catmull-Rom upscaling with adaptive sharpening. The zoom stays inside the phone preview and never touches the world FOV.
- **Zoom controls:** mouse wheel, drag, and quick zoom chips.
- **ProCam:** landscape & portrait shooting, grading, and looks.
- **Gallery, albums and shared albums**, uploaded through Fivemanage, a local folder, or a custom uploader.

### 🏙️ City apps
| App | What it does |
|---|---|
| **TaxiGo** | Go online, take fares, track earnings |
| **Hop** | Player rides & food delivery (Uber-style) |
| **Alpha Motors** | Hourly car & bike rentals |
| **Work** | Job, duty, boss tools, city services |
| **Crew** | Gang members, missions, turf, chat |
| **Banking** | Balance, transfers, company money |
| **Notebook** | Notes, Word-style docs, Excel-style sheets, **live shared editing** |
| **Calendar / Reminders** | Appointments and lists |
| **iCloud** | Storage and Apple-style account |
| **Music / Radio / Speaker** | Songs, YouTube, and a Bluetooth speaker placed in the world |
| **Print** | AirPrint to a nearby Bluetooth printer |
| **CamLink** | BodyCam recorder and receiver, cast to a TV or tablet |
| **News / Report** | City news and reports to staff |

### 🎮 Games
Casino (Crash, Roulette, Blackjack, Slots, Mines, Plinko, Dice…), 8 Ball Pool, ARENA (boxing, gunfight, ranked), Racing, Skydive, Slap, Roulette, Bluff Bar, Metro Dash.

### 💬 Social
| App | Style |
|---|---|
| **FaceWorld** | Posts, stories, city feed |
| **PhotoFlow** | Photos, stories, likes |
| **Snapster** | Camera, chats, stories |
| **ClipTok** | Short clips |
| **ChatWave** | Chats and calls |
| **WatchMe** | Live streaming from the phone camera **or a chest BodyCam**, with comments and reactions |

### 🔌 Integrations (auto-detected)
- **Garages:** jg-advancedgarages, cd_garage, qs-advancedgarages, okokGarage, qbx_garages…
- **Housing:** qbx_properties, ps-housing, qb-houses, qs-housing…
- **Fuel:** ox_fuel, cdn-fuel, LegacyFuel, Renewed-Fuel, ps-fuel, lc_fuel…
- **Inventories:** ox_inventory, qs-inventory, codem-inventory, tgiann-inventory, origen_inventory…

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
| `lf_powerbank` | Portable charger with 5 full charges; refill it with the USB cable in a car |
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

**Power bank:** works anywhere and holds 5 full charges (`Charges: 5/5` in metadata). One charge is used every time the phone reaches 100% from the bank.

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
