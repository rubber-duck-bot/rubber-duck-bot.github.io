# 🦆 RubberDuck Bot — Hivatalos Weboldal & Dokumentáció

[![GitHub Pages Deployment](https://img.shields.io/badge/GitHub%20Pages-Online-22c55e?style=for-the-badge&logo=github)](https://rubber-duck-bot.github.io)
[![Discord Developer Compliant](https://img.shields.io/badge/Discord%20API-Compliant-5865F2?style=for-the-badge&logo=discord)](https://discord.com)
[![Bilingual](https://img.shields.io/badge/Language-HU%20%7C%20EN-FBBF24?style=for-the-badge)](#)

Ez a tárhely tartalmazza a **RubberDuck Bot** hivatalos, modern, reszponzív és kétnyelvű (magyar / angol) bemutató weboldalát, amely GitHub Pages-en keresztül érhető el. Az oldal magában foglalja az interaktív parancsközpontot, a biztonsági architektúra leírását, valamint a Discord bot ellenőrzéséhez (Verification) szükséges hivatalos **Privacy Policy** (Adatkezelési Tájékoztató) és **Terms of Service** (Felhasználási Feltételek) dokumentációt.

---

## 🌐 Élő weboldal URL-ek

* **Központi Weboldal:** [https://rubber-duck-bot.github.io](https://rubber-duck-bot.github.io)
* **Adatvédelmi Tájékoztató (Privacy Policy):** [https://rubber-duck-bot.github.io/#privacy](https://rubber-duck-bot.github.io/#privacy)
* **Felhasználási Feltételek (Terms of Service):** [https://rubber-duck-bot.github.io/#terms](https://rubber-duck-bot.github.io/#terms)

> 💡 **Megjegyzés:** Ha a repó neve nem `rubber-duck-bot.github.io`, hanem például `rubber-duck-bot/web`, akkor a link: `https://rubber-duck-bot.github.io/web/`.

---

## 📋 Beállítás a Discord Developer Portalon

Amikor a botot publikálod és hitelesíted a **[Discord Developer Portal](https://discord.com/developers/applications)** felületén:

1. Nyisd meg a botod alkalmazását a Developer Portalon.
2. Lépj az **Application** -> **General Information** menüpontra.
3. Másold be az alábbi linkeket a megfelelő mezőkbe:

| Mező neve a Discordon | Beillesztendő URL |
| :--- | :--- |
| **Privacy Policy URL** | `https://rubber-duck-bot.github.io/#privacy` |
| **Terms of Service URL** | `https://rubber-duck-bot.github.io/#terms` |
| **Interactions Endpoint URL / Website** | `https://rubber-duck-bot.github.io` |

---

## 🚀 GitHub Pages bekapcsolása lépésről lépésre

Ha most hozod létre a tárhelyet, a weboldal azonnali élesítéséhez kövesd az alábbi lépéseket:

1. **Fájlok feltöltése:**
   * Másold be az elkészült `index.html` fájlt a repó gyökerébe (`root`).
   * Helyezd el ezt a `README.md` fájlt a gyökérben.
2. **Commit & Push:**
   ```bash
   git add index.html README.md
   git commit -m "feat: RubberDuck Bot bemutató weboldal publikálása"
   git push origin main