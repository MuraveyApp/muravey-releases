# Наши приложения / Our Apps

---

## 🐜 Муравей — AI-помощник для текста

AI-помощник для обработки текста. Работает в macOS и Windows.

### Скачать v3.19.0

**Windows:**

- [**Muravey-3.19.0-windows-installer.exe**](https://github.com/MuraveyApp/muravey-releases/releases/download/v3.19.0/Muravey-3.19.0-windows-installer.exe) — установщик (рекомендуется)
- [**Muravey.exe**](https://github.com/MuraveyApp/muravey-releases/releases/download/v3.19.0/Muravey.exe) — portable, без установки

**macOS:**

- [**Muravey-3.19.0-macos.dmg**](https://github.com/MuraveyApp/muravey-releases/releases/download/v3.19.0/Muravey-3.19.0-macos.dmg) — DMG установщик

**Что нового в v3.19.0:**

- Определение версии SEB (macOS + Windows)
- Биометрический режим набора текста с имитацией человеческой клавиатуры
- 61 новый тест (всего 3854)

---

## 🦉 OwlMind VPN — Обход Великого файрвола Китая

**One-click VPN.** Скачал → ввёл email → нажал Connect → готово.
Никакого Clash Verge, v2rayNG или других программ — всё встроено.

### Цены

| Тариф | Цена | Что включено |
|-------|------|--------------|
| 🎁 **Trial** | **$0 на 3 дня** | 50 GB · 2 устройства · без карты |
| ⚡ **Pro** | **$5 / месяц** | Безлимит · 5 устройств · приоритетная поддержка |

### Скачать v1.2.0

**Через сайт (рекомендуется):**

- 🌐 **<https://license.muravey.app/owlmind>** — главная страница со всеми ссылками

**Прямые ссылки (работают из Китая):**

- 🍎 [**OwlMind-VPN-macos.dmg**](https://vpn.muravey.app:8443/clients/OwlMind-VPN-macos.dmg) — Mac (61 MB)
- 🪟 [**OwlMind.VPN.exe**](https://vpn.muravey.app:8443/clients/OwlMind.VPN.exe) — Windows (37 MB)
- 🤖 [**v2rayng-arm64.apk**](https://vpn.muravey.app:8443/clients/v2rayng-arm64.apk) — Android (через v2rayNG, native в разработке)
- 📱 iPhone — [Streisand](https://apps.apple.com/app/streisand/id6450534064) из App Store

**Mac — установка одной командой:**

```bash
curl -fsSL https://vpn.muravey.app:8443/install.sh | bash
```

Скрипт автоматически: скачает → установит → обойдёт Gatekeeper → запустит.

### Технологии

- **VLESS + REALITY + Vision** (Xray-core 26.4) — маскировка под обычный HTTPS
- **Встроенный xray-core** — никаких сторонних программ не нужно
- **System tray** — приложение работает в фоне
- **Auto-reconnect** — автоматическое переподключение при разрыве
- **CN2 GIA Premium** routing — 20-35ms пинг из Китая, до 4 Gbps
- **97% uptime** даже во время "закруток" GFW

### Как пользоваться

1. **Скачай** OwlMind VPN для своей системы (Mac/Win)
2. **Открой** приложение
3. **Нажми "Get Trial"** → введи email
4. **Жми ⚡ Connect** → готово, VPN включён
5. На телефоне (Android/iOS) — используй v2rayNG/Streisand с subscription URL из приложения

### Защита от обмана

5 уровней защиты:

- Блок одноразовых email (28 доменов)
- 1 пробный на IP за 30 дней
- Device fingerprint — 1 пробный на устройство
- Лимит 2 одновременных IP на конфиг (нельзя расшарить)
- Лимит 50GB трафика на пробный период

---

[Все релизы](https://github.com/MuraveyApp/muravey-releases/releases) · [Сайт](https://muravey.app) · [Поддержка](mailto:support@muravey.app)
