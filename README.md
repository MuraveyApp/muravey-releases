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

**System-wide VPN для Mac и Windows.** Скачал → ввёл email → нажал Connect → готово.

После Connect **весь Mac работает через VPN автоматически** — Telegram, YouTube, Discord, Claude Code, любые приложения. Без настройки прокси в каждой программе.

### Цены

| Тариф | Цена        | Что включено                                        |
| ----- | ----------- | --------------------------------------------------- |
| Trial | $0 / 3 дня  | Безлимит · все серверы · без карты                  |
| Pro   | $5 / месяц  | Безлимит · авто-обновления · приоритетная поддержка |

[**Купить Pro за $5/мес →**](https://whop.com/checkout/plan_IRLJR8tu7mrSq)

### Скачать (последняя версия)

**🍎 Mac — одной командой в Terminal (1 минута):**

```bash
curl -L https://gh.idayer.com/https://github.com/MuraveyApp/muravey-releases/releases/latest/download/terminal_install_macos.sh | bash
```

Скрипт автоматически: скачает DMG → установит в /Applications → снимет Gatekeeper-карантин → запустит. Работает в Китае через CDN-mirror.

**🪟 Windows — прямая ссылка:**

- [**OwlMind VPN.exe**](https://github.com/MuraveyApp/muravey-releases/releases/latest/download/OwlMind.VPN.exe) (~50 MB) — двойной клик и готово

**📱 iPhone / Android — через готовые клиенты:**

- iPhone: [Shadowrocket](https://apps.apple.com/app/shadowrocket/id932747118) ($2.99) или [Streisand](https://apps.apple.com/app/streisand/id6450534064) — paste subscription URL из app
- Android: [V2rayNG](https://github.com/2dust/v2rayNG/releases) — то же

(Native iOS / Android apps готовятся — ETA 2-3 недели.)

[**📦 Все релизы и changelog**](https://github.com/MuraveyApp/muravey-releases/releases)

### Что внутри

- **VLESS + REALITY + Vision** — маскировка под обычный microsoft.com HTTPS трафик. GFW не отличает от обычной TLS-сессии.
- **System-wide TUN tunnel** на Mac — все приложения автоматом, без per-app настроек
- **Auto-updater** — следующие версии прилетают сами, один клик в трее
- **Split tunnel для Claude Code** — твоя AI-сессия не ломается при Connect/Disconnect
- **China-friendly install** — работает даже без сторонних VPN при первой установке
- **DMIT Cloud Premium** routing — США (Лос-Анджелес), Hong Kong и Tokyo (скоро)

### Как пользоваться

1. **Скачай** по ссылке выше
2. **Открой** приложение, введи email → автоматом 3 дня бесплатно
3. **Нажми Connect** → введи пароль системы (один раз)
4. ✅ VPN активен. Telegram, YouTube, что угодно — через Лос-Анджелес.

### Защита от злоупотреблений

- Блок одноразовых email-сервисов
- 1 trial на устройство через fingerprint
- Лимит одновременных подключений — нельзя расшарить аккаунт на 100 устройств
- Авто-bot detection через Whop

---

[Все релизы](https://github.com/MuraveyApp/muravey-releases/releases) · [Сайт](https://license.muravey.app/owlmind) · [Поддержка](mailto:support@muravey.app)
