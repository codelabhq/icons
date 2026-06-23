# Icons

Набор иконок для `proxy-groups` в [Clash Verge](https://github.com/clash-verge-rev/clash-verge-rev) и любых других клиентах на базе Clash (Clash Meta, Mihomo, FlClash и т.д.).

Каждую иконку можно подключить по прямой ссылке на raw-файл — просто укажите её в поле `icon` нужной группы прокси.

## Иконки

| Иконка | Сервис | Ссылка |
|:------:|--------|--------|
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/cloudflare-icon.svg" width="32" height="32"> | Cloudflare | [cloudflare-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/cloudflare-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/discord-icon.svg" width="32" height="32"> | Discord | [discord-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/discord-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/geoblock-icon.svg" width="32" height="32"> | GeoBlock | [geoblock-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/geoblock-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/global-icon.svg" width="32" height="32"> | Global | [global-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/global-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/google-icon.svg" width="32" height="32"> | Google | [google-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/google-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/steampowered-icon.svg" width="32" height="32"> | Steam | [steampowered-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/steampowered-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/telegram-icon.svg" width="32" height="32"> | Telegram | [telegram-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/telegram-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/torrent-icon.svg" width="32" height="32"> | Torrent | [torrent-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/torrent-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/twitch-icon.svg" width="32" height="32"> | Twitch | [twitch-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/twitch-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/twitter-official.svg" width="32" height="32"> | Twitter / X | [twitter-official.svg](https://raw.githubusercontent.com/codelabhq/icons/main/twitter-official.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/whatsapp-icon.svg" width="32" height="32"> | WhatsApp | [whatsapp-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/whatsapp-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/meta-icon.svg" width="32" height="32"> | Meta | [meta-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/meta-icon.svg) |
| <img src="https://raw.githubusercontent.com/codelabhq/icons/main/youtube-icon.svg" width="32" height="32"> | YouTube | [youtube-icon.svg](https://raw.githubusercontent.com/codelabhq/icons/main/youtube-icon.svg) |

## Использование

```yaml
proxy-groups:
  - name: YouTube
    type: select
    icon: https://raw.githubusercontent.com/codelabhq/icons/main/youtube-icon.svg
    proxies:
      - DIRECT
      - PROXY
```
