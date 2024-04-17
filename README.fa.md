<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-white.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/logo-dark.png">
  <img alt="a logo for iran sing-box rules in both dark and light mode" src="assets/logo-dark.png">
</picture>

<p align="center">
<img alt="GitHub Workflow Status" src="https://img.shields.io/github/actions/workflow/status/Chocolate4U/Iran-sing-box-rules/release.yml?event=schedule&style=for-the-badge&logo=github&cacheSeconds=3600">
<img alt="GitHub release" src="https://img.shields.io/github/v/release/Chocolate4U/Iran-sing-box-rules?style=for-the-badge&cacheSeconds=3600">
<img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/Chocolate4U/Iran-sing-box-rules?display_date=published_at&style=for-the-badge&cacheSeconds=3600">
<img alt="License" src="https://img.shields.io/github/license/Chocolate4U/Iran-sing-box-rules?style=for-the-badge&color=blue&cacheSeconds=3600">
</p>

# :writing_hand: معرفی

مجموعه ای از قوانین مسیریابی بهبود یافته و جامع که برای کاربران ایرانی بهینه شده و قابل استفاده در هسته sing-box و کلیه کلاینت های آن میباشد.

:bulb: برای قوانین مسیریابی v2ray به اینجا مراجعه کنید [Iran V2Ray Rules](https://github.com/Chocolate4U/Iran-v2ray-rules)  
:bulb: برای قوانین مسیریابی Clash به اینجا مراجعه کنید [Iran Clash Rules](https://github.com/Chocolate4U/Iran-clash-rules)

# :arrow_down: نحوه دانلود

## <picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/white"><source media="(prefers-color-scheme: light)" srcset="https://cdn.simpleicons.org/github/dark"><img height="32" width="32" alt="github logo in dark and light mode." src="https://cdn.simpleicons.org/github/dark"></picture> از گیت هاب

### Rule-Set

فرمت جدید قوانین مسیریابی که در نسخه sing-box 1.8.0 معرفی شده و جایگزین فرمت قدیمی `db.` شده است.  
برای اطلاعات بیشتر به این لینک رجوع کنید. [rule-set](https://sing-box.sagernet.org/configuration/rule-set/)  

برای دیدن لیست کامل فایل های جدید [اینجا](https://github.com/Chocolate4U/Iran-sing-box-rules/tree/rule-set) را ببینید.

> [!WARNING]
> فرمت قدیمی `db.`, `geosite.db` و `geoip.db` در نسخه +1.8.0 منسخوخ شده اند و باید از فرمت Rule-Set استفاده کنید. تنها در حالتی از فرمت قدیمی استفاده کنید که از نسخه سینگ باکس 1.7 به پایین استفاده میکنید.

:bulb: فرمت کلی فایل های جدید به صورت `geoip-xx.srs` و `geosite-xx.srs` است. قسمت `xx` را با دسته بندی مورد نظر خود جایگزین کنید و مثل مثال زیر دانلود کنید:

`Rule-Set` [https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geoip-ir.srs](https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geoip-ir.srs)  
`Rule-Set` [https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geosite-ir.srs](https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geosite-ir.srs)

### DB

`GeoIP` [https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geoip.db](https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geoip.db)  
`GeoSite` [https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geosite.db](https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geosite.db)

`GeoIP-Lite` [https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geoip-lite.db](https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geoip-lite.db)  
`GeoSite-Lite` [https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geosite-lite.db](https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geosite-lite.db)

`Security-IP` [https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/security-ip.db](https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/security-ip.db)  
`Security` [https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/security.db](https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/security.db)

## <picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/jsdelivr/white"><source media="(prefers-color-scheme: light)" srcset="https://cdn.simpleicons.org/jsdelivr/dark"><img height="32" width="32" alt="github logo in dark and light mode." src="https://cdn.simpleicons.org/jsdelivr/dark"></picture> از سرویس توزیع محتوای jsDelivr

### Rule-Set

`Rule-Set` [https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@rule-set/geoip-ir.srs](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@rule-set/geoip-ir.srs)  
`Rule-Set` [https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@rule-set/geosite-ir.srs](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@rule-set/geosite-ir.srs)

### DB

`GeoIP` [https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geoip.db](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geoip.db)  
`GeoSite` [https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geosite.db](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geosite.db)

`GeoIP-Lite` [https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geoip-lite.db](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geoip-lite.db)  
`GeoSite-Lite` [https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geosite-lite.db](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/geosite-lite.db)

`Security-IP` [https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/security-ip.db](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/security-ip.db)  
`Security` [https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/security.db](https://cdn.jsdelivr.net/gh/chocolate4u/Iran-sing-box-rules@release/security.db)

# :computer: نحوه استفاده

## هسته sing-box

<details>
  <summary><strong>با استفاده از Rule-Set (نیاز به ورژن 1.8.0 به بالا)</strong></summary>

قسمت زیر را به قسمت مسیریابی فایل کانفیگ خود اضافه کنید:

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
    "rules": [
      {
        "ip_is_private": true,
        "outbound": "direct"
      },
      {
        "rule_set": [
          "geosite-category-ads-all",
          "geosite-malware",
          "geosite-phishing",
          "geosite-cryptominers",
          "geoip-malware",
          "geoip-phishing"
        ],
        "outbound": "block"
      },
      {
        "rule_set": [
          "geosite-ir",
          "geoip-ir"
        ],
        "outbound": "direct"
      }
    ],
    "rule_set": [
      {
        "tag": "geosite-ir",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geosite-ir.srs"
      },
      {
        "tag": "geosite-category-ads-all",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geosite-category-ads-all.srs"
      },
      {
        "tag": "geosite-malware",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geosite-malware.srs"
      },
      {
        "tag": "geosite-phishing",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geosite-phishing.srs"
      },
      {
        "tag": "geosite-cryptominers",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geosite-cryptominers.srs"
      },
      {
        "tag": "geoip-ir",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geoip-ir.srs"
      },
      {
        "tag": "geoip-malware",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geoip-malware.srs"
      },
      {
        "tag": "geoip-phishing",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/rule-set/geoip-phishing.srs"
      }
    ]
  },
  "experimental": {
    "cache_file": {
      "enabled": true
    }
  }
```
</details>

<details>
  <summary><strong>با استفاده از فایل‌های DB</strong></summary>

قسمت زیر را به قسمت مسیریابی فایل کانفیگ خود اضافه کنید:

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
  "geoip": {
      "download_url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geoip.db"
  },
  "geosite": {
    "download_url": "https://raw.githubusercontent.com/Chocolate4U/Iran-sing-box-rules/release/geosite.db"
  },
  "rules": [
    {
      "geosite": [
        "category-ads-all",
        "malware",
        "phishing",
        "cryptominers"
      ],
      "outbound": "block"
    },
    {
      "geoip": [
        "malware",
        "phishing"
      ],
      "outbound": "block"
    },
    {
      "geosite": "ir",
      "outbound": "direct"
    },
    {
      "geoip": [
        "ir",
        "private"
      ],
      "outbound": "direct"
    }
  ]
}
```
</details>

# :page_with_curl: دسته بندی ها

<h2 dir="rtl">GeoIP</h2>
<details dir="rtl">
  <summary><strong>دسته‌های موجود در<code>geoip.db</code></strong></summary>

<ul dir="rtl">
<li>شامل کلیه IP های تمامی کشورها از هر دو دیتابیس Maxmind و IP2Location.</li>

<li><code>geoip:ir</code></li>
  <p align="right">دربر گیرنده IP های ایران استخراج شده از دیتابیس Maxmind و IP2Location به علاوه IP های پیامرسان های ایرانی از جمله "ایتا"، "روبیکا" و غیره.</p>

<li><code>geoip:private</code></li>
  <p align="right">دربر گیرنده IP های ایالات متحده استخراج شده از دیتابس MaxMind.</p>

<li><code>geoip:arvancloud</code></li>
  <p align="right">دربر گیرنده IP های سرویس توزیع محتوای ابرآروان. :information_source: این دسته بندی در "geoip:ir" ادغام شده و در صورت استفاده از "geoip:ir"، نیازی به این دسته بندی نیست.</p>

<li><code>geoip:derakcloud</code></li>
  <p align="right">دربر گیرنده IP های سرویس توزیع محتوای ابردراک. :information_source: این دسته بندی در "geoip:ir" ادغام شده و در صورت استفاده از "geoip:ir"، نیازی به این دسته بندی نیست.</p>

<li><code>geoip:iranserver</code></li>
  <p align="right">دربر گیرنده IP های سرویس توزیع محتوای ایران سرور. :information_source: این دسته بندی در "geoip:ir" ادغام شده و در صورت استفاده از "geoip:ir"، نیازی به این دسته بندی نیست.</p>

<li><code>geoip:parspack</code></li>
  <p align="right">دربر گیرنده IP های سرویس توزیع محتوای پارس پک. :information_source: این دسته بندی در "geoip:ir" ادغام شده و در صورت استفاده از "geoip:ir"، نیازی به این دسته بندی نیست.</p>

<li><code>geoip:cloudflare</code></li>
  <p align="right">دربرگیرنده IP های سرویس توزیع محتوای کلودفلر.</p>

<li><code>geoip:google</code></li>
  <p align="right">دربر گیرنده IP های گوگل، گوگل کلود و گوگل بات.</p>

<li><code>geoip:amazon</code></li>
  <p align="right">در برگیرنده IP های آمازون و سرویس ابری آمازون(AWS).</p>

<li><code>geoip:microsoft</code></li>
  <p align="right">دربر گیرنده IP های مایکروسافت و سرویس ابری آژور.</p>

<li><code>geoip:bing</code></li>
  <p align="right">دربر گیرنده IP های موتور جستجوی بینگ.</p>

<li><code>geoip:github</code></li>
  <p align="right">دربر گیرنده IP های گیت هاب.</p>

<li><code>geoip:facebook</code></li>
  <p align="right">دربر گیرنده IP های اکوسیستم متا، از جمله فیسبوک، اینستاگرام و واتس اپ.</p>

<li><code>geoip:twitter</code></li>
  <p align="right">دربر گیرنده IP های توییتر (یا به عبارتی X!).</p>

<li><code>geoip:telegram</code></li>
  <p align="right">دربر گیرنده IP های تلگرام.</p>

<li><code>geoip:oracle</code></li>
  <p align="right">دربر گیرنده IP های سرویس ابری اوراکل.</p>

<li><code>geoip:digitalocean</code></li>
  <p align="right">دربر گیرنده IP سرویس های ابری دیجیتال اوشن.</p>

<li><code>geoip:linode</code></li>
  <p align="right">دربر گیرنده IP سرویس ابری لینود.</p>

<li><code>geoip:openai</code></li>
  <p align="right">دربر گیرنده IP های OpenAI و ChatGPT.</p>

<li><code>geoip:phishing</code></li>
  <p align="right">دربر گینده IP های فیشینگ.</p>

<li><code>geoip:malware</code></li>
  <p align="right">دربر گیرنده IP های بدافزار.</p>
</ul>
</details>

<h2 dir="rtl">GeoIP-Lite</h2>
<details dir="rtl">
  <summary><strong>دسته‌های موجود در<code>geoip-lite.db</code></strong></summary>

<ul dir="rtl">
<li><code>geoip:ir</code></li>
  <p align="right">دربر گیرنده IP های ایران استخراج شده از دیتابیس Maxmind و IP2Location به علاوه IP های پیامرسان های ایرانی از جمله "ایتا"، "روبیکا" و غیره.</p>

<li><code>geoip:private</code></li>
  <p align="right">دربر گیرنده IP های شبکه محلی (LAN).</p>
</ul>
</details>

<h2 dir="rtl">Security-IP</h2>
<details dir="rtl">
  <summary><strong>دسته‌های موجود در<code>security-ip.db</code></strong></summary>

<ul dir="rtl">
<li><code>geoip:phishing</code></li>
  <p align="right">دربر گینده IP های فیشینگ.</p>

<li><code>geoip:malware</code></li>
  <p align="right">دربر گیرنده IP های بدافزار.</p>
</ul>
</details>

<h2 dir="rtl">GeoIP-Services</h2>
<details dir="rtl">
  <summary><strong>دسته‌های موجود در<code>geoip-services.db</code></strong></summary>

<ul dir="rtl">
<li><code>geoip:arvancloud</code></li>
  <p align="right">دربر گیرنده IP های سرویس توزیع محتوای ابرآروان.</p>

<li><code>geoip:derakcloud</code></li>
  <p align="right">دربر گیرنده IP های سرویس توزیع محتوای ابردراک.</p>

<li><code>geoip:iranserver</code></li>
  <p align="right">دربر گیرنده IP های سرویس توزیع محتوای ایران سرور.</p>

<li><code>geoip:parspack</code></li>
  <p align="right">دربر گیرنده IP های سرویس توزیع محتوای پارس پک.</p>

<li><code>geoip:cloudflare</code></li>
  <p align="right">دربرگیرنده IP های سرویس توزیع محتوای کلودفلر.</p>

<li><code>geoip:google</code></li>
  <p align="right">دربر گیرنده IP های گوگل، گوگل کلود و گوگل بات.</p>

<li><code>geoip:amazon</code></li>
  <p align="right">در برگیرنده IP های آمازون و سرویس ابری آمازون(AWS).</p>

<li><code>geoip:microsoft</code></li>
  <p align="right">دربر گیرنده IP های مایکروسافت و سرویس ابری آژور.</p>

<li><code>geoip:bing</code></li>
  <p align="right">دربر گیرنده IP های موتور جستجوی بینگ.</p>

<li><code>geoip:github</code></li>
  <p align="right">دربر گیرنده IP های گیت هاب.</p>

<li><code>geoip:facebook</code></li>
  <p align="right">دربر گیرنده IP های اکوسیستم متا، از جمله فیسبوک، اینستاگرام و واتس اپ.</p>

<li><code>geoip:twitter</code></li>
  <p align="right">دربر گیرنده IP های توییتر (یا به عبارتی X!).</p>

<li><code>geoip:telegram</code></li>
  <p align="right">دربر گیرنده IP های تلگرام.</p>

<li><code>geoip:oracle</code></li>
  <p align="right">دربر گیرنده IP های سرویس ابری اوراکل.</p>

<li><code>geoip:digitalocean</code></li>
  <p align="right">دربر گیرنده IP سرویس های ابری دیجیتال اوشن.</p>

<li><code>geoip:linode</code></li>
  <p align="right">دربر گیرنده IP سرویس ابری لینود.</p>

<li><code>geoip:openai</code></li>
  <p align="right">دربر گیرنده IP های OpenAI و ChatGPT.</p>
</ul>
</details>

<h2 dir="rtl">GeoSite</h2>
<details dir="rtl">
  <summary><strong>دسته‌های موجود در<code>geosite.db</code></strong></summary>

<ul dir="rtl">
<li>کلیه دسته بندی ها موجود در مخزن <a href="https://github.com/v2fly/domain-list-community">domain-list-community</a> پشتبانی می شوند، به علاوه موارد زیر:</li>

<li><code>geosite:ir</code></li>
  <p align="right">دربر گیرنده وبسایت های ایرانی به غیر از دامنه های "ir." و قوانینی جهت بایپس کردن کلیه دامنه های "ir.".</p>

<li><code>geosite:ads</code></li>
  <p align="right">دربر گیرنده لیستی از دامنه های تبلیغاتی ایرانی.</p>

<li><code>geosite:category-ads-all</code></li>
  <p align="right">دربر گیرنده لیستی سفارشی شده از دامنه های تبلیغاتی ایرانی و خارجی. این لیست به گونه ای بهینه شده که تا حد امکان خالی از اشتباه باشد در حالی که سبک بودن و موثر بودن خود را نیز حفظ کند.</p>

<li><code>geosite:malware</code></li>
  <p align="right">دربر گیرنده لیستی از دامنه های حاوی بدافزار.</p>

<li><code>geosite:phishing</code></li>
  <p align="right">دربر گیرنده لیستی از دامنه های تقلبی و فیشینگ.</p>

<li><code>geosite:cryptominers</code></li>
  <p align="right">دربر گیرنده لیستی از استخراج کننده های رمزارز که در پس زمینه مرورگر شروع به استخراج کرده و بر کارایی سیستم کاربر تاثیر منفی می گزارند.</p>

<li><code>geosite:social</code></li>
  <p align="right">دربر گیرنده لیستی از دامنه های شبکه های اجتماعی از جمله "Facebook", "Instagram", "Whatsapp", "Twitter", "LinkedIn", "MySpace", "Pinterest", "Tumblr", "Reddit", "TikTok", "clubhouse".</p>

<li><code>geosite:nsfw</code></li>
  <p align="right">دربر گیرنده لیستی از دامنه های محتوای بزرگسال و قمار.</p>
</ul>
</details>

<h2 dir="rtl">GeoSite-Lite</h2>
<details dir="rtl">
  <summary><strong>دسته‌های موجود در<code>geosite-lite.db</code></strong></summary>

<ul dir="rtl">
<li><code>geosite:ir</code></li>
<p align="right">
  دربر گیرنده وبسایت های ایرانی فعال به غیر از دامنه های "ir." و قوانینی جهت بایپس کردن کلیه دامنه های "ir.".<br>
  همه دامنه های ایرانی در لیست معمولی هر 24 ساعت یکبار بررسی شده و پس از حذف دامنه های غیرفعال به این لیست راه میابند.<br>
  این تست ممکن است زیاد دقیق نباشد، به همین دلیل پیشنهاد میکنم هر روز و یا به طور مرتب این لیست را بروزرسانی کنید.
</p>

<li><code>geosite:ads</code></li>
  <p align="right">دربر گیرنده لیستی از دامنه های تبلیغاتی ایرانی.</p>
</ul>
</details>

<h2 dir="rtl">Security</h2>
<details dir="rtl">
  <summary><strong>دسته‌های موجود در<code>security.db</code></strong></summary>

<ul dir="rtl">
<li><code>geosite:category-ads-all</code></li>
  <p align="right">دربر گیرنده لیستی سفارشی شده از دامنه های تبلیغاتی ایرانی و خارجی. این لیست به گونه ای بهینه شده که تا حد امکان خالی از اشتباه باشد در حالی که سبک بودن و موثر بودن خود را نیز حفظ کند.</p>

<li><code>geosite:malware</code></li>
  <p align="right">دربر گیرنده لیستی از دامنه های حاوی بدافزار.</p>

<li><code>geosite:phishing</code></li>
  <p align="right">دربر گیرنده لیستی از دامنه های تقلبی و فیشینگ.</p>

<li><code>geosite:cryptominers</code></li>
  <p align="right">دربر گیرنده لیستی از استخراج کننده های رمزارز که در پس زمینه مرورگر شروع به استخراج کرده و بر کارایی سیستم کاربر تاثیر منفی می گزارند.</p>
</ul>
</details>

# :information_desk_person: این ها چطوری ساخته شدن؟

فایل های `geoip.db`,`geoip-lite.db` با استفاده از سورس کد موجود در [فورک](https://github.com/Chocolate4U/sing-geoip) من از [sing-geoip](https://github.com/SagerNet/sing-geoip) ساخته شدن. از فایل `Country.mmdb`,`Country-lite.mmdb` موجود در مخزن [Iran V2Ray Rules](https://github.com/Chocolate4U/Iran-v2ray-rules) برای ساخت این فایل ها استفاده می شود.  
فایل های `geosite.db`,`geosite-lite.db` با استفاده از سورس کد موجود در [فورک](https://github.com/Chocolate4U/sing-geosite) من از [sing-geosite](https://github.com/SagerNet/sing-geosite) ساخته شده. از فایل `geosite.dat`,`geosite-lite.dat` موجود در مخزن [Iran V2Ray Rules](https://github.com/Chocolate4U/Iran-v2ray-rules) برای ساخت این فایل ها استفاده می شود.

# :handshake: مشارکت

هرگونه مشارکتی در این مخزن مورد استقبال قرار میگیرد. شما به دو روش میتوانید در این مخزن مشارکت داشته باشید:

1. مشارکت در سورس های مورد استفاده این مخزن  
   دامنه ای میشناسید که باید بایپس شود؟ به اینجا گزارش بدهید [Iran Hosted Domains](https://github.com/bootmortis/iran-hosted-domains)  
   دامنه تبلیغاتی ایرانی میشناسید که باید مسدود شود؟ به اینجا گزارش بدهید [PersianBlocker](https://github.com/MasterKia/PersianBlocker)  
   دامنه ای میشناسید که... خیلی خوب فکر کنم متوجه منظورم شدید!
2. مستقیما در این مخزن مشارکت داشته باشید  
   مشکلات را گزارش کنید، سورس های جدید پیشنهاد بدهید، و یا هر گونه ایده که به بهتر شدن این مخزن کمک میکند را با ما به اشتراک بگذارید.

:raising_hand_man: یک مورد دیگه، اگر این مخزن برای شما مفید واقع شده لطفا یک ستاره در بالای این صفحه از خودتون به جا بگذارین تا به بیشتر دیده شدن این لیست کمک بشه.

# :copyright: لایسنس

این پروژه، به جز منابع مورد استفاده، تحت لایسنس GNU GPLv3 قرار دارد. برای جزئیات بیشتر اینجا را ببینید [لایسنس](LICENSE)

تمامی حقوق برای منابع استفاده شده بر اساس لایسنس های مربوطه شان محفوظ است. لطفا برای اطلاعات بیشتر به قسمت منابع مراجعه کنید.

# :package: منابع

## GeoIP

| Source                 | Maintainer           | Home Page                                                                                 | License                                                                              | Category          |
| ---------------------- | -------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ----------------- |
| GeoLite2               | MaxMind              | [Home Page](https://dev.maxmind.com/geoip/geolite2-free-geolocation-data)                 | [CC BY-SA 4.0](https://dev.maxmind.com/geoip/geolite2-free-geolocation-data#license) | Country IPs       |
| IP2Location LITE       | IP2Location          | [Home Page](https://lite.ip2location.com/ip2location-lite)                                | [CC BY-SA 4.0](https://lite.ip2location.com/terms-of-use)                            | Country IPs       |
| ITO GOV                | ITO GOV              | [Home Page](https://eservices.ito.gov.ir/Page/IPListMessenger)                            | N/A                                                                                  | ir(messenger IPs) |
| V2ray-rules-dat        | Loyalsoldier         | [Home Page](https://github.com/Loyalsoldier/v2ray-rules-dat)                              | [GPL-3.0](https://github.com/Loyalsoldier/v2ray-rules-dat/blob/master/LICENSE)       | cn                |
| Arvan Cloud            | Arvan Cloud          | [Home Page](https://www.arvancloud.ir/en/dev/ips)                                         | All rights reserved                                                                  | arvancloud        |
| Derak Cloud            | Derak Cloud          | [Home Page](https://derak.cloud/لیست-بازه-های-ip)                                         | All rights reserved                                                                  | derakcloud        |
| IranServer             | IranServer           | [Home Page](https://docs.iranserver.com/irserver-cloud/cdn/allow-iranserver-ip-addresses) | All rights reserved                                                                  | iranserver        |
| ParsPack               | ParsPack             | [Home Page](https://parspack.com/cdnips.txt)                                              | All rights reserved                                                                  | parspack          |
| Cloudflare             | Cloudflare           | [Home Page](https://www.cloudflare.com/ips)                                               | All rights reserved                                                                  | cloudflare        |
| Telegram               | Telegram             | [Home Page](https://core.telegram.org/resources/cidr.txt)                                 | All rights reserved                                                                  | Telegram          |
| URLhaus                | abuse.ch             | [Home Page](https://urlhaus.abuse.ch)                                                     | [CC0](https://urlhaus.abuse.ch/api/#tos)                                             | malware           |
| Phishing URL Blocklist | malware-filter Group | [Home Page](https://gitlab.com/malware-filter/phishing-filter)                            | [MIT](https://gitlab.com/malware-filter/phishing-filter/-/blob/main/LICENSE)         | phishing          |
| IPRanges               | lord-alfred          | [Home Page](https://github.com/lord-alfred/ipranges)                                      | [CC0 1.0](https://github.com/lord-alfred/ipranges/blob/main/LICENSE)                 | everything else   |

## GeoSite

| Source                      | Maintainer            | Home Page                                                      | License                                                                         | Category        |
| --------------------------- | --------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------- | --------------- |
| Iran Hosted Domains         | bootmortis            | [Home Page](https://github.com/bootmortis/iran-hosted-domains) | [MIT](https://github.com/bootmortis/iran-hosted-domains/blob/main/LICENSE)      | ir              |
| PersianBlocker              | MasterKia             | [Home Page](https://github.com/MasterKia/PersianBlocker)       | [AGPL-3.0](https://github.com/MasterKia/PersianBlocker/blob/main/LICENSE)       | ads             |
| DNS Blocklists              | Hagezi                | [Home Page](https://github.com/hagezi/dns-blocklists)          | All rights reserved                                                             | ads             |
| Ad and tracking server list | Peter Lowe            | [Home Page](https://pgl.yoyo.org/adservers)                    | [McRae GPL](https://pgl.yoyo.org/license)                                       | ads             |
| GoodbyeAds                  | jerryn70              | [Home Page](https://github.com/jerryn70/GoodbyeAds)            | [MIT](https://github.com/jerryn70/GoodbyeAds/blob/master/LICENSE)               | ads             |
| AdGuard DNS filter          | Adguard Team          | [Home Page](https://github.com/AdguardTeam/AdGuardSDNSFilter)  | [GPL-3.0](https://github.com/AdguardTeam/AdGuardSDNSFilter/blob/master/LICENSE) | ads             |
| URLhaus                     | abuse.ch              | [Home Page](https://urlhaus.abuse.ch)                          | [CC0](https://urlhaus.abuse.ch/api/#tos)                                        | malware         |
| Phishing URL Blocklist      | malware-filter Group  | [Home Page](https://gitlab.com/malware-filter/phishing-filter) | [MIT](https://gitlab.com/malware-filter/phishing-filter/-/blob/main/LICENSE)    | phishing        |
| NoCoin adblock list         | hoshsadiq             | [Home Page](https://github.com/hoshsadiq/adblock-nocoin-list)  | [MIT](https://github.com/hoshsadiq/adblock-nocoin-list/blob/master/LICENSE)     | cryptominers    |
| Unified Hosts               | StevenBlack           | [Home Page](https://github.com/StevenBlack/hosts)              | [MIT](https://github.com/StevenBlack/hosts/blob/master/license.txt)             | social, nsfw    |
| Domain list community       | Domain list community | [Home Page](https://github.com/v2fly/domain-list-community)    | [MIT](https://github.com/v2fly/domain-list-community/blob/master/LICENSE)       | everything else |

# :warning: سلب مسئولیت

این مخزن هیچگونه همکاری، ارتباط، مجوز، و یا به طور کلی به هیچ طریقی هیچ گونه ارتباطی به طور رسمی با هریک از منابع ذکر شده اعم از وبسایت ها، سرویس ها و یا هر چیزی که ممکن است به آن ارتباط داشته باشد، ندارد.  
اطلاعات موجود در این مخزن از منابع در دسترس عموم جمع آوری گردیده و فقط به منظور اطلاع رسانی بدون هیچ ضمانتی مبنی بر دقیق بودن و یا در دسترس بودن عرضه شده است. همچنین ما هیچگونه مسئولیتی در برابر هر گونه خسارت ناشی از استفاده از اطلاعات این مخزن که ممکن است به وجود بیاید، نداریم. لطفا قبل از استفاده از اطلاعات این مخزن، تحقیقات لازم را به عمل بیاورید.

# :pray: تشکر ویژه

- همه maintainer های نامبرده شده در این مخزن
- [Project S](https://github.com/SagerNet)
