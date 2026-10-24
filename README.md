**The ultimate identification card and license experience for FiveM servers.** Elevate your server's roleplay realism with a cutting-edge identification card system featuring real-time automated mugshot generation, automatic green-screen background removal, and custom 3D card props with synchronized holding animations. Powered by a sleek, modern React UI, players can view their detailed ID or show it directly to nearby citizens with full metadata persistence. Backed by `ak47_lib`, it delivers native multi-framework compatibility across ESX, QBCore, and QBX alongside extensive inventory and target system support.

---

## 🎥 Showcase
<img width="1920" height="1080" alt="thumbnail" src="https://github.com/user-attachments/assets/cf8de4ed-7868-44e8-a2e5-508961f3504e" />

> **[Click here to watch the full feature showcase on YouTube](https://youtu.be/BykldtEC4cw)**

---


## 🔥 Key Features

Designed to improve roleplay immersion and economy balancing:

### 📸 Automated Mugshots & Studio Photography

* **Automated Green Screen Studio:** When issuing or purchasing an ID, the script automatically clones the player's ped into an isolated camera setup with a custom 3D green-screen prop (`prop_greenscreen`), professional studio lighting (`DrawLightWithRange`), and daytime synchronization for consistent portrait quality.
* **Smart Chromakey & Cloud CDN:** An integrated client-side canvas algorithm removes the green screen background in real time and uploads the portrait straight to FiveManage cloud hosting (`fmapi.net`), embedding a persistent image URL directly into the card's item metadata.

### 🪪 Comprehensive Card & License Variety

* **8 Pre-Configured Identification Cards:** Ready-to-use Citizen ID, Police Badge, Sheriff ID, Driver License, Paramedic ID, Firefighter ID, Weapon Permit, and Weed License—each featuring unique visual themes, custom badge backgrounds, text styling, and colors.
* **Configurable License Sub-Classes:** Assign specific classes to licenses, such as weapon permits (Pistol, Shotgun, SMG, AR, Sniper) and driver licenses (A, A1, BE, C, CE, D, DE), completely configurable through `config.lua`.

### 🎭 Custom 3D Props & Immersive Animations

* **Custom Streamed 3D Props:** Includes dedicated 3D models for every card type (`prop_idcard`, `prop_policeid`, `prop_sheriffid`, `prop_driverlicense`, `prop_emsid`, `prop_fireid`, `prop_weaponlicense`, `prop_weedlicense`).
* **Synced Roleplay Animations & Distance Showing:** Players play authentic badge/card-holding animations when presenting their ID. Cards can either be inspected privately or shown directly to the closest player within configurable proximity (`Config.ShowDistance`).

### 🏪 In-Game Shops & Administrative Issuance

* **Configurable ID Shops:** Set up custom purchase locations with NPC peds, animation scenarios (`WORLD_HUMAN_COP_IDLES`), map blips, and target polyzones. Supports payments via cash, bank balance, black money, or custom coin database tables.
* **Role-Based `/giveid` Command:** Authorize Admins (Ace, License, Identifier, or Group), Police, Sheriff, Paramedics, and Gangs to issue specific cards to nearby players with rank thresholds and custom input dialogs for address, issue date, and expiration.

### 🛠️ Technical Excellence

* **Multi-Framework & Target Support:** Seamlessly works with ESX, QB, QBX, and various target systems (ox_target, qb-target, qtarget).
* **Highly Secure:** Built-in server-side exploit checks, including distance validation and trigger authentication, to prevent cheating.
* **Developer Exports & Metadata Persistence:** Features client and server exports (`HasLicense`, `GetLicenseLabel`, `GiveIdCard`) for seamless integration with police MDTs, gun shops, DMV scripts, and all major inventory systems (`ox_inventory`, `qb-inventory`, `ak47_inventory`, `qs-inventory`, `codem-inventory`, and more).

---

## 💻 Framework:

* ESX, QB, QBX

---

## ⚙️ Dependencies:

* ak47_lib: https://github.com/MenanAk47/ak47_lib/releases/latest

---

## ⚙️ How To Install:

* Download ak47_idcardv2 from your cfx portal.
* Add the script in your resources folder.
* Add items based on your framework instruction.
* Add item images into inventory.
* Start the script in your server.cfg below framework files.
* Make sure you have all dependencies.
* Restart the server.

---

## 🔗 Links & Support:

* **📖 Documentation:** [https://docs.menanak47.com/multi-framework/ak47_idcardv2](https://docs.menanak47.com/multi-framework/ak47_idcardv2)
* **🛒 Buy Now (Tebex):** [https://menanak47.tebex.io/package/6516102](https://menanak47.tebex.io/package/6516102)
* **💬 Discord Support:** [https://discord.gg/menanak47](https://discord.gg/menanak47)

---

## 📝 Note:
* We don't support custom framework. Make sure you are using official framework update.
* Renaming the script is not allowed. It may break the functionalities.
* Don't upload the script with FileZilla, Use Winscp if you are using FTP for file uploading
