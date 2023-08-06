# Iran Sing-Box Rules
This is an Enhanced and All-in-One "geosite.db" routing file to use in sing-box and all it's compatible clients.

# Categories
`geosite:ir`
: Includes non-ir TLD Iranian domains (e.g. `.com` `.net` `.org` etc.) and rules to bypass all `.ir` domains.

`geosite:ads`
: Includes a curated list of Persian and Foreign advertisement and tracking domains based on multiple sources. It is optimized to has as low as possible false positives while also retain small size and efficiency.

`geosite:malware`
: Includes a list of active malware domains.

`geosite:phishing`
: Includes a list of scam and phishing domains.

`geosite:cryptominers`
: Includes a list of cryptocurrency miners that run in the background of a web browser and affect system performance.

# How to download
[https://github.com/chocolate4u/Iran-sing-box-rules/releases/latest/download/geosite.db](https://github.com/chocolate4u/Iran-sing-box-rules/releases/latest/download/geosite.db)

Or

[https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geosite.db](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geosite.db)

# Usage
## sing-box core
Add the following to your sing-box client configuration:
```
"outbounds": [
  {
    "type": "direct",
    "tag": "direct"
  },
  {
    "type": "block",
    "tag": "block"
  }
],
"route": {
  "geosite": {
    "download_url": "https://github.com/Chocolate4U/Iran-sing-box-rules/releases/latest/download/geosite.db"
  },
  "rules": [
    {
      "geosite": [
        "ads",
        "malware",
        "phishing",
        "cryptominers"
      ],
      "outbound": "block"
    },
    {
      "geosite": "ir",
      "outbound": "direct"
    }
  ]
},
```

# License
This project, EXECPT for upstream sources, is licensed under the GNU GPLv3 License - see the [LICENSE](https://github.com/Chocolate4U/Iran-sing-box-rules/blob/main/LICENSE) file for details.

All rights are reserved for All upstream sources used in this project according to their respective licenses. Please refer to [Sources](#sources) section for more details.

# Sources
| Source | Maintainer | Home Page | License | Category |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| Iran Hosted Domains | bootmortis | [Home Page](https://github.com/bootmortis/iran-hosted-domains) | [MIT](https://github.com/bootmortis/iran-hosted-domains/blob/main/LICENSE) | ir |
| PersianBlocker | MasterKia | [Home Page](https://github.com/MasterKia/PersianBlocker) | [AGPL-3.0](https://github.com/MasterKia/PersianBlocker/blob/main/LICENSE) | ads |
| DNS Blocklists | Hagezi | [Home Page](https://github.com/hagezi/dns-blocklists) | All rights reserved | ads |
| Ad and tracking server list | Peter Lowe | [Home Page](https://pgl.yoyo.org/adservers) | [McRae GPL](https://pgl.yoyo.org/license) | ads |
| GoodbyeAds | jerryn70 | [Home Page](https://github.com/jerryn70/GoodbyeAds) | [MIT](https://github.com/jerryn70/GoodbyeAds/blob/master/LICENSE) | ads |
| AdGuard DNS filter | Adguard Team | [Home Page](https://github.com/AdguardTeam/AdGuardSDNSFilter) | [GPL-3.0](https://github.com/AdguardTeam/AdGuardSDNSFilter/blob/master/LICENSE) | ads |
| URLhaus | abuse.ch | [Home Page](https://urlhaus.abuse.ch) | [CC0](https://urlhaus.abuse.ch/api/#tos) | malware |
| Phishing URL Blocklist | malware-filter Group | [Home Page](https://gitlab.com/malware-filter/phishing-filter) | [MIT](https://gitlab.com/malware-filter/phishing-filter/-/blob/main/LICENSE) | phishing |
| NoCoin adblock list | hoshsadiq | [Home Page](https://github.com/hoshsadiq/adblock-nocoin-list) | [MIT](https://github.com/hoshsadiq/adblock-nocoin-list/blob/master/LICENSE) | cryptominers |

# Special Thanks
- All list maintainers that mentioned in this project.
- [Project S](https://github.com/SagerNet)
- [Loyalsoldier](https://github.com/Loyalsoldier)
