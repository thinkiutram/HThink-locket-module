# HThink v4.0.4 Telegram overlay report

- Brand: **HThink Locket**
- Telegram caption: **@hthinklocket**
- Source protected file: `scripts/protected/locket-v4.0.4-15f350254cfd.js`
- Source SHA-256: `15f350254cfd8840b959db085705396d26a6b386a451cdf349b57259a47b99d7`
- Wrapped runtime: `scripts/releases/hthink-v404-telegram.js`
- Module: `HThink_Locket_Telegram_v404.sgmodule`
- Original archived v4.0.4 file remains unchanged
- Adapter only changes matching caption items in Firebase response; it does not modify video, mic or Gold configuration fields
- Confirm actual effect using `[HThink] updated caption overlay fields` in Shadowrocket logs. If `no matching caption overlay`, branding was not applied
- Wrapper has only been syntax-checked until tested on a real iPhone
- Keep original Cuios MIT LICENSE and notices for redistributed source
