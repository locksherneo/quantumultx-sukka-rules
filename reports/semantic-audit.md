# Quantumult X Sukka semantic audit

- Sources: 67
- Native filter rules: 380083
- Removed Sukka markers: 64
- Removed duplicate rules: 0
- Deferred IP rules: 48
- URL rewrite rules: 179
- Unsupported no-resolve options: 186

| Source | Policy | Rules | Deferred IP | Rewrite |
| --- | --- | ---: | ---: | ---: |
| `domainset/apple_cdn` | `direct` | 158 | 0 | 0 |
| `domainset/cdn` | `direct` | 4631 | 0 | 0 |
| `domainset/download` | `direct` | 1965 | 0 | 0 |
| `domainset/game-download` | `direct` | 52 | 0 | 0 |
| `domainset/icloud_private_relay` | `reject` | 6 | 0 | 0 |
| `domainset/reject` | `reject` | 134887 | 0 | 0 |
| `domainset/reject_extra` | `reject` | 75633 | 0 | 0 |
| `domainset/reject_phishing` | `reject` | 147482 | 0 | 0 |
| `domainset/speedtest` | `direct` | 3348 | 0 | 0 |
| `non_ip/ai` | `proxy` | 49 | 0 | 0 |
| `non_ip/apple_cdn` | `direct` | 0 | 0 | 0 |
| `non_ip/apple_cn` | `direct` | 9 | 0 | 0 |
| `non_ip/apple_intelligence` | `proxy` | 5 | 0 | 0 |
| `non_ip/apple_services` | `proxy` | 16 | 1 | 0 |
| `non_ip/cdn` | `direct` | 83 | 0 | 0 |
| `non_ip/cloudmounter` | `proxy` | 0 | 0 | 0 |
| `non_ip/direct` | `direct` | 182 | 0 | 0 |
| `non_ip/domestic` | `direct` | 868 | 0 | 0 |
| `non_ip/download` | `direct` | 9 | 0 | 0 |
| `non_ip/gitlab` | `proxy` | 1 | 0 | 0 |
| `non_ip/global` | `proxy` | 1269 | 0 | 0 |
| `non_ip/global_plus` | `proxy` | 0 | 0 | 0 |
| `non_ip/lan` | `direct` | 49 | 0 | 0 |
| `non_ip/microsoft` | `proxy` | 83 | 0 | 0 |
| `non_ip/microsoft_cdn` | `direct` | 52 | 0 | 0 |
| `non_ip/my_direct` | `direct` | 1 | 0 | 0 |
| `non_ip/my_git` | `proxy` | 7 | 0 | 0 |
| `non_ip/my_plus` | `proxy` | 14 | 0 | 0 |
| `non_ip/my_proxy` | `proxy` | 16 | 0 | 0 |
| `non_ip/my_reject` | `reject` | 45 | 0 | 0 |
| `non_ip/my_tw` | `proxy` | 13 | 0 | 0 |
| `non_ip/my_us` | `proxy` | 6 | 0 | 0 |
| `non_ip/neteasemusic` | `direct` | 4 | 0 | 0 |
| `non_ip/reject-drop` | `reject` | 27 | 0 | 0 |
| `non_ip/reject-no-drop` | `reject` | 43 | 0 | 0 |
| `non_ip/reject-url-regex` | `reject` | 0 | 0 | 176 |
| `non_ip/reject` | `reject` | 319 | 47 | 3 |
| `non_ip/sogouinput` | `direct` | 11 | 0 | 0 |
| `non_ip/stream` | `proxy` | 321 | 0 | 0 |
| `non_ip/stream_biliintl` | `proxy` | 6 | 0 | 0 |
| `non_ip/stream_eu` | `proxy` | 10 | 0 | 0 |
| `non_ip/stream_hk` | `proxy` | 31 | 0 | 0 |
| `non_ip/stream_jp` | `proxy` | 27 | 0 | 0 |
| `non_ip/stream_kr` | `proxy` | 3 | 0 | 0 |
| `non_ip/stream_tw` | `proxy` | 37 | 0 | 0 |
| `non_ip/stream_us` | `proxy` | 51 | 0 | 0 |
| `non_ip/telegram` | `proxy` | 14 | 0 | 0 |
| `ip/ai` | `proxy` | 23 | 0 | 0 |
| `ip/apple_services` | `proxy` | 10 | 0 | 0 |
| `ip/cdn` | `direct` | 3 | 0 | 0 |
| `ip/china_ip` | `direct` | 3917 | 0 | 0 |
| `ip/china_ip_ipv6` | `direct` | 3429 | 0 | 0 |
| `ip/domestic` | `direct` | 2 | 0 | 0 |
| `ip/download` | `direct` | 11 | 0 | 0 |
| `ip/lan` | `direct` | 11 | 0 | 0 |
| `ip/neteasemusic` | `direct` | 17 | 0 | 0 |
| `ip/reject` | `reject` | 779 | 0 | 0 |
| `ip/stream` | `proxy` | 19 | 0 | 0 |
| `ip/stream_biliintl` | `proxy` | 0 | 0 | 0 |
| `ip/stream_eu` | `proxy` | 0 | 0 | 0 |
| `ip/stream_hk` | `proxy` | 0 | 0 | 0 |
| `ip/stream_jp` | `proxy` | 0 | 0 | 0 |
| `ip/stream_kr` | `proxy` | 0 | 0 | 0 |
| `ip/stream_tw` | `proxy` | 0 | 0 | 0 |
| `ip/stream_us` | `proxy` | 0 | 0 | 0 |
| `ip/telegram` | `proxy` | 14 | 0 | 0 |
| `ip/telegram_asn` | `proxy` | 5 | 0 | 0 |
