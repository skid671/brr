# Практична 1 F2 черемуш
# Практична робота № 1

**Дисципліна:** Основи побудови інформаційних систем та мереж

**Тема:** Спостереження за процесом звернення до вебресурсу. Побудова власної моделі рівнів взаємодії

| | |
|---|---|
| **Прізвище, ім'я** |Черемуш Артур |
| **Група** | F2 2.01|
| **Номер варіанта** | 29|
| **Домен варіанта** |nure.ua |
| **Середовище виконання** |  Windows |
| **Версія curl** | *8.21.0 (Windows) libcurl/8.21.0 Schannel zlib/1.3.2 WinIDN WinLDAP* |
| **Дата виконання** |17.09.2026 |

---

## Частина A. Збір експериментальних даних

### A.1. Запит із діагностичним виводом

**Команда:**

```
curl -v https://nure.ua
```

**Вивід:**

```
 * Host nure.ua:443 was resolved.

* IPv6: (none)

* IPv4: 31.202.132.10

*   Trying 31.202.132.10:443...

* schannel: disabled automatic use of client certificate

* ALPN: curl offers http/1.1

* ALPN: server accepted http/1.1

* Established connection to nure.ua (31.202.132.10 port 443) from 192.168.0.101 port 63981

* using HTTP/1.x

> GET / HTTP/1.1

> Host: nure.ua

> User-Agent: curl/8.21.0

> Accept: */*

>

* Request completely sent off

* schannel: remote party requests renegotiation

* schannel: renegotiating SSL/TLS connection

* schannel: SSL/TLS connection renegotiated

* schannel: remote party requests renegotiation

* schannel: renegotiating SSL/TLS connection

* schannel: SSL/TLS connection renegotiated

< HTTP/1.1 200 OK

< Server: nginx

< Date: Thu, 17 Sep 2026 17:32:29 GMT

< Content-Type: text/html; charset=UTF-8

< Transfer-Encoding: chunked

< Connection: keep-alive

< Vary: Accept-Encoding

< set-cookie: lPSgAVatQZ=DR4YZz; expires=Fri, 18 Sep 2026 17:32:28 GMT; Max-Age=86400; path=/; secure

< set-cookie: yGDKICMRwYx=IfxJtaNymA; expires=Fri, 18 Sep 2026 17:32:28 GMT; Max-Age=86400; path=/; secure

< set-cookie: -VCSAMfbOI=xGQ2adBXH; expires=Fri, 18 Sep 2026 17:32:28 GMT; Max-Age=86400; path=/; secure

< link: <https://nure.ua/wp-json/>; rel="https://api.w.org/"

< link: <https://nure.ua/wp-json/wp/v2/pages/167>; rel="alternate"; title="JSON"; type="application/json"

< x-turbo-charged-by: LiteSpeed

< Cache-Control: no-cache

<

<!DOCTYPE html><html dir="ltr" lang="uk-UA" prefix="og: https://ogp.me/ns#" class="no-js"><head>  <script async src="https://www.googletagmanager.com/gtag/js?id=G-H7Z0ZG6WWP"></script> <script>window.dataLayer = window.dataLayer || [];

  function gtag(){dataLayer.push(arguments);}

  gtag('js', new Date());


  gtag('config', 'G-H7Z0ZG6WWP');</script> <meta name="google-site-verification" content="EuIF_cA2kFMZMULNnSda5XZWHsX9IqS8np_wLV4m3j0" /><meta charset="UTF-8"/><meta name="apple-mobile-web-app-capable" content="yes"/><meta name="apple-mobile-web-app-status-bar-style" content="black-translucent"/><meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, minimal-ui"><meta http-equiv="X-UA-Compatible" content="IE=edge"><title>ХНУРЕ | ХНУРЕ - Харківський національний університет радіоелектроніки</title><link rel="apple-touch-icon" sizes="180x180" href="https://nure.ua/wp-content/themes/nure/icons/apple-touch-icon.png"><link rel="icon" type="image/png" sizes="32x32" href="https://nure.ua/wp-content/themes/nure/icons/favicon-32x32.png"><link rel="icon" type="image/png" sizes="16x16" href="https://nure.ua/wp-content/themes/nure/icons/favicon-16x16.png"><link rel="manifest" href="https://nure.ua/wp-content/themes/nure/icons/manifest.json"><link rel="mask-icon" href="https://nure.ua/wp-content/themes/nure/icons/safari-pinned-tab.svg" color="#0450a2"><link rel="shortcut icon" href="https://nure.ua/wp-content/themes/nure/icons/favicon.ico"><meta name="msapplication-config" content="https://nure.ua/wp-content/themes/nure/icons/browserconfig.xml"><meta name="theme-color" content="#0450a2"> <script src="https://www.google.com/recaptcha/api.js" async defer></script> <meta name="description" content="ХНУРЕ | Харківський національний університет радіоелектроніки" /><meta name="robots" content="max-image-preview:large" /><link rel="canonical" href="https://nure.ua" /><meta name="generator" content="All in One SEO (AIOSEO) 5.0.0.1" /><meta property="og:locale" content="uk_UA" /><meta property="og:site_name" content="NURE" /><meta property="og:type" content="article" /><meta property="og:title" content="ХНУРЕ" /><meta property="og:description" content="ХНУРЕ | Харківський національний університет радіоелектроніки" /><meta property="og:url" content="https://nure.ua" /><meta property="og:image" content="https://nure.ua/wp-content/themes/nure/images/logo.png" /><meta property="og:image:secure_url" content="https://nure.ua/wp-content/themes/nure/images/logo.png" /><meta property="article:published_time" content="2018-01-13T12:46:34+00:00" /><meta property="article:modified_time" content="2026-09-14T18:29:46+00:00" /><meta property="article:publisher" content="https://www.facebook.com/profile.php?id=61578407176131" /><meta name="twitter:card" content="summary" /><meta name="twitter:site" content="@PressNURE" /><meta name="twitter:title" content="ХНУРЕ" /><meta name="twitter:description" content="ХНУРЕ | Харківський національний університет радіоелектроніки" /><meta name="twitter:image" content="https://nure.ua/wp-content/themes/nure/images/logo.png" /> <script type="application/ld+json" class="aioseo-schema">{"@context":"https:\/\/schema.org","@graph":[{"@type":"BreadcrumbList","@id":"https:\/\/nure.ua\/#breadcrumblist","itemListElement":[{"@type":"ListItem","@id":"https:\/\/nure.ua#listItem","position":1,"name":"Home"}]},{"@type":"Organization","@id":"https:\/\/nure.ua\/#organization","name":"NURE","description":"\u0425\u0430\u0440\u043a\u0456\u0432\u0441\u044c\u043a\u0438\u0439 \u043d\u0430\u0446\u0456\u043e\u043d\u0430\u043b\u044c\u043d\u0438\u0439 \u0443\u043d\u0456\u0432\u0435\u0440\u0441\u0438\u0442\u0435\u0442 \u0440\u0430\u0434\u0456\u043e\u0435\u043b\u0435\u043a\u0442\u0440\u043e\u043d\u0456\u043a\u0438","url":"https:\/\/nure.ua\/","logo":{"@type":"ImageObject","url":"https:\/\/nure.ua\/wp-content\/uploads\/logo-3.png","@id":"https:\/\/nure.ua\/#organizationLogo","width":52,"height":52},"image":{"@id":"https:\/\/nure.ua\/#organizationLogo"},"sameAs":["https:\/\/www.instagram.com\/khnure_official\/","https:\/\/www.tiktok.com\/@nure.official","https:\/\/www.youtube.com\/@mediaNURE","https:\/\/www.linkedin.com\/school\/15099424"]},{"@type":"WebPage","@id":"https:\/\/nure.ua\/#webpage","url":"https:\/\/nure.ua\/","name":"\u0425\u041d\u0423\u0420\u0415","description":"\u0425\u041d\u0423\u0420\u0415 | \u0425\u0430\u0440\u043a\u0456\u0432\u0441\u044c\u043a\u0438\u0439 \u043d\u0430\u0446\u0456\u043e\u043d\u0430\u043b\u044c\u043d\u0438\u0439 \u0443\u043d\u0456\u0432\u0435\u0440\u0441\u0438\u0442\u0435\u0442 \u0440\u0430\u0434\u0456\u043e\u0435\u043b\u0435\u043a\u0442\u0440\u043e\u043d\u0456\u043a\u0438","inLanguage":"uk-UA","isPartOf":{"@id":"https:\/\/nure.ua\/#website"},"breadcrumb":{"@id":"https:\/\/nure.ua\/#breadcrumblist"},"datePublished":"2018-01-13T15:46:34+03:00","dateModified":"2026-09-14T21:29:46+03:00"},{"@type":"WebSite","@id":"https:\/\/nure.ua\/#website","url":"https:\/\/nure.ua\/","name":"\u0425\u041d\u0423\u0420\u0415","description":"\u0425\u0430\u0440\u043a\u0456\u0432\u0441\u044c\u043a\u0438\u0439 \u043d\u0430\u0446\u0456\u043e\u043d\u0430\u043b\u044c\u043d\u0438\u0439 \u0443\u043d\u0456\u0432\u0435\u0440\u0441\u0438\u0442\u0435\u0442 \u0440\u0430\u0434\u0456\u043e\u0435\u043b\u0435\u043a\u0442\u0440\u043e\u043d\u0456\u043a\u0438","inLanguage":"uk-UA","publisher":{"@id":"https:\/\/nure.ua\/#organization"}}]}</script> <link rel="alternate" href="https://nure.ua/" hreflang="uk" /><link rel="alternate" href="https://nure.ua/en/" hreflang="en" /><link rel="alternate" title="oEmbed (JSON)" type="application/json+oembed" href="https://nure.ua/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fnure.ua%2F&#038;lang=ua" /><link rel="alternate" title="oEmbed (XML)" type="text/xml+oembed" href="https://nure.ua/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fnure.ua%2F&#038;format=xml&#038;lang=ua" /><style id="wp-img-auto-sizes-contain-inline-css">img:is([sizes=auto i],[sizes^="auto," i]){contain-intrinsic-size:3000px 1500px}

/*# sourceURL=wp-img-auto-sizes-contain-inline-css */</style><style id="wp-block-library-inline-css">:root{--wp-block-synced-color:#7a00df;--wp-block-synced-color--rgb:122,0,223;--wp-bound-block-color:var(--wp-block-synced-color);--wp-editor-canvas-background:#ddd;--wp-admin-theme-color:#007cba;--wp-admin-theme-color--rgb:0,124,186;--wp-admin-theme-color-darker-10:#006ba1;--wp-admin-theme-color-darker-10--rgb:0,107,160.5;--wp-admin-theme-color-darker-20:#005a87;--wp-admin-theme-color-darker-20--rgb:0,90,135;--wp-admin-border-width-focus:2px}@media (min-resolution:192dpi){:root{--wp-admin-border-width-focus:1.5px}}.wp-element-button{cursor:pointer}:root .has-very-light-gray-background-color{background-color:#eee}:root .has-very-dark-gray-background-color{background-color:#313131}:root .has-very-light-gray-color{color:#eee}:root .has-very-dark-gray-color{color:#313131}:root .has-vivid-green-cyan-to-vivid-cyan-blue-gradient-background{background:linear-gradient(135deg,#00d084,#0693e3)}:root .has-purple-crush-gradient-background{background:linear-gradient(135deg,#34e2e4,#4721fb 50%,#ab1dfe)}:root .has-hazy-dawn-gradient-background{background:linear-gradient(135deg,#faaca8,#dad0ec)}:root .has-subdued-olive-gradient-background{background:linear-gradient(135deg,#fafae1,#67a671)}:root .has-atomic-cream-gradient-background{background:linear-gradient(135deg,#fdd79a,#004a59)}:root .has-nightshade-gradient-background{background:linear-gradient(135deg,#330968,#31cdcf)}:root .has-midnight-gradient-background{background:linear-gradient(135deg,#020381,#2874fc)}:root{--wp--preset--font-size--normal:16px;--wp--preset--font-size--huge:42px}.has-regular-font-size{font-size:1em}.has-larger-font-size{font-size:2.625em}.has-normal-font-size{font-size:var(--wp--preset--font-size--normal)}.has-huge-font-size{font-size:var(--wp--preset--font-size--huge)}:root .has-text-align-center{text-align:center}:root .has-text-align-left{text-align:left}:root .has-text-align-right{text-align:right}.has-fit-text{white-space:nowrap!important}#end-resizable-editor-section{display:none}.aligncenter{clear:both}.items-justified-left{justify-content:flex-start}.items-justified-center{justify-content:center}.items-justified-right{justify-content:flex-end}.items-justified-space-between{justify-content:space-between}.screen-reader-text{word-wrap:normal!important;border:0;clip-path:inset(50%);height:1px;margin:-1px;overflow:hidden;padding:0;position:absolute;width:1px}.screen-reader-text:focus{background-color:#ddd;clip-path:none;color:#444;display:block;font-size:1em;height:auto;left:5px;line-height:normal;padding:15px 23px 14px;text-decoration:none;top:5px;width:auto;z-index:100000}html :where(.has-border-color){border-style:solid}html :where([style*=border-color]){border-style:solid}html :where([style*=border-top-color]){border-top-style:solid}html :where([style*=border-right-color]){border-right-style:solid}html :where([style*=border-bottom-color]){border-bottom-style:solid}html :where([style*=border-left-color]){border-left-style:solid}html :where([style*=border-width]){border-style:solid}html :where([style*=border-top-width]){border-top-style:solid}html :where([style*=border-right-width]){border-right-style:solid}html :where([style*=border-bottom-width]){border-bottom-style:solid}html :where([style*=border-left-width]){border-left-style:solid}html :where(img[class*=wp-image-]){height:auto;max-width:100%}:where(figure){margin:0 0 1em}html :where(.is-position-sticky){--wp-admin--admin-bar--position-offset:var(--wp-admin--admin-bar--height,0px)}@media screen and (max-width:600px){html :where(.is-position-sticky){--wp-admin--admin-bar--position-offset:0px}}


/*# sourceURL=/wp-includes/css/dist/block-library/common.min.css */</style><style id="classic-theme-styles-inline-css">/*! This file is auto-generated */

.wp-block-button__link{color:#fff;background-color:#32373c;border-radius:9999px;box-shadow:none;text-decoration:none;padding:calc(.667em + 2px) calc(1.333em + 2px);font-size:1.125em}.wp-block-file__button{background:#32373c;color:#fff;text-decoration:none}

/*# sourceURL=/wp-includes/css/classic-themes.min.css */</style><style id="global-styles-inline-css">:root{--wp--preset--aspect-ratio--square: 1;--wp--preset--aspect-ratio--4-3: 4/3;--wp--preset--aspect-ratio--3-4: 3/4;--wp--preset--aspect-ratio--3-2: 3/2;--wp--preset--aspect-ratio--2-3: 2/3;--wp--preset--aspect-ratio--16-9: 16/9;--wp--preset--aspect-ratio--9-16: 9/16;--wp--preset--color--black: #000000;--wp--preset--color--cyan-bluish-gray: #abb8c3;--wp--preset--color--white: #ffffff;--wp--preset--color--pale-pink: #f78da7;--wp--preset--color--vivid-red: #cf2e2e;--wp--preset--color--luminous-vivid-orange: #ff6900;--wp--preset--color--luminous-vivid-amber: #fcb900;--wp--preset--color--light-green-cyan: #7bdcb5;--wp--preset--color--vivid-green-cyan: #00d084;--wp--preset--color--pale-cyan-blue: #8ed1fc;--wp--preset--color--vivid-cyan-blue: #0693e3;--wp--preset--color--vivid-purple: #9b51e0;--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgb(6,147,227) 0%,rgb(155,81,224) 100%);--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgb(252,185,0) 0%,rgb(255,105,0) 100%);--wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgb(255,105,0) 0%,rgb(207,46,46) 100%);--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);--wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);--wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);--wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);--wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);--wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);--wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);--wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);--wp--preset--font-size--small: 13px;--wp--preset--font-size--medium: 20px;--wp--preset--font-size--large: 36px;--wp--preset--font-size--x-large: 42px;--wp--preset--spacing--20: 0.44rem;--wp--preset--spacing--30: 0.67rem;--wp--preset--spacing--40: 1rem;--wp--preset--spacing--50: 1.5rem;--wp--preset--spacing--60: 2.25rem;--wp--preset--spacing--70: 3.38rem;--wp--preset--spacing--80: 5.06rem;--wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);--wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);--wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);--wp--preset--shadow--outlined: 6px 6px 0px -3px rgb(255, 255, 255), 6px 6px rgb(0, 0, 0);--wp--preset--shadow--crisp: 6px 6px 0px rgb(0, 0, 0);}:where(body) { margin: 0; }:where(.is-layout-flex){gap: 0.5em;}:where(.is-layout-grid){gap: 0.5em;}body .is-layout-flex{display: flex;}.is-layout-flex{flex-wrap: wrap;align-items: center;}.is-layout-flex > :is(*, div){margin: 0;}body .is-layout-grid{display: grid;}.is-layout-grid > :is(*, div){margin: 0;}body{padding-top: 0px;padding-right: 0px;padding-bottom: 0px;padding-left: 0px;}:root :where(.wp-element-button, .wp-block-button__link){background-color: #32373c;border-width: 0;color: #fff;font-family: inherit;font-size: inherit;font-style: inherit;font-weight: inherit;letter-spacing: inherit;line-height: inherit;padding-top: calc(0.667em + 2px);padding-right: calc(1.333em + 2px);padding-bottom: calc(0.667em + 2px);padding-left: calc(1.333em + 2px);text-decoration: none;text-transform: inherit;}.has-black-color{color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-color{color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-color{color: var(--wp--preset--color--white) !important;}.has-pale-pink-color{color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-color{color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-color{color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-color{color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-color{color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-color{color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-color{color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-color{color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-color{color: var(--wp--preset--color--vivid-purple) !important;}.has-black-background-color{background-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-background-color{background-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-background-color{background-color: var(--wp--preset--color--white) !important;}.has-pale-pink-background-color{background-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-background-color{background-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-background-color{background-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-background-color{background-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-background-color{background-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-background-color{background-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-background-color{background-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-background-color{background-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-background-color{background-color: var(--wp--preset--color--vivid-purple) !important;}.has-black-border-color{border-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-border-color{border-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-border-color{border-color: var(--wp--preset--color--white) !important;}.has-pale-pink-border-color{border-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-border-color{border-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-border-color{border-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-border-color{border-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-border-color{border-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-border-color{border-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-border-color{border-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-border-color{border-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-border-color{border-color: var(--wp--preset--color--vivid-purple) !important;}.has-vivid-cyan-blue-to-vivid-purple-gradient-background{background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;}.has-light-green-cyan-to-vivid-green-cyan-gradient-background{background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;}.has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;}.has-luminous-vivid-orange-to-vivid-red-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;}.has-very-light-gray-to-cyan-bluish-gray-gradient-background{background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;}.has-cool-to-warm-spectrum-gradient-background{background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;}.has-blush-light-purple-gradient-background{background: var(--wp--preset--gradient--blush-light-purple) !important;}.has-blush-bordeaux-gradient-background{background: var(--wp--preset--gradient--blush-bordeaux) !important;}.has-luminous-dusk-gradient-background{background: var(--wp--preset--gradient--luminous-dusk) !important;}.has-pale-ocean-gradient-background{background: var(--wp--preset--gradient--pale-ocean) !important;}.has-electric-grass-gradient-background{background: var(--wp--preset--gradient--electric-grass) !important;}.has-midnight-gradient-background{background: var(--wp--preset--gradient--midnight) !important;}.has-small-font-size{font-size: var(--wp--preset--font-size--small) !important;}.has-medium-font-size{font-size: var(--wp--preset--font-size--medium) !important;}.has-large-font-size{font-size: var(--wp--preset--font-size--large) !important;}.has-x-large-font-size{font-size: var(--wp--preset--font-size--x-large) !important;}

/*# sourceURL=global-styles-inline-css */</style><link rel='stylesheet' id='simple-spoiler-style-css' href='https://nure.ua/wp-content/plugins/simple-spoiler/css/simple-spoiler.min.css?ver=1.5' media='all' /><link rel='stylesheet' id='bootstrap.min-css' href='https://nure.ua/wp-content/themes/nure/libs/bootstrap/css/bootstrap.min.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='sidr-css' href='https://nure.ua/wp-content/themes/nure/libs/sidr/stylesheets/jquery.sidr.bare.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='font-awesome-css' href='https://nure.ua/wp-content/themes/nure/libs/font-awesome/css/font-awesome.min.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='owl-css' href='https://nure.ua/wp-content/themes/nure/libs/owlcarousel/assets/owl.carousel.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='owl.theme-css' href='https://nure.ua/wp-content/themes/nure/libs/owlcarousel/assets/owl.theme.default.min.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='fancybox-css' href='https://nure.ua/wp-content/themes/nure/libs/fancybox/jquery.fancybox.min.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='scroll-css' href='https://nure.ua/wp-content/themes/nure/libs/jquery.mCustomScrollbar/jquery.mCustomScrollbar.min.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='formstyler-css' href='https://nure.ua/wp-content/themes/nure/libs/jquery.formstyler/jquery.formstyler.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='formstyler.theme-css' href='https://nure.ua/wp-content/themes/nure/libs/jquery.formstyler/jquery.formstyler.theme.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='styles-css' href='https://nure.ua/wp-content/themes/nure/style.css?ver=7.0.4' media='all' /><link rel='stylesheet' id='tablepress-default-css' href='https://nure.ua/wp-content/tablepress-combined.min.css?ver=74' media='all' /> <script id="jquery-core-js" src="https://nure.ua/wp-includes/js/jquery/jquery.min.js?ver=3.7.1"></script> <link rel="https://api.w.org/" href="https://nure.ua/wp-json/" /><link rel="alternate" title="JSON" type="application/json" href="https://nure.ua/wp-json/wp/v2/pages/167" /><style type="text/css">.spoiler-head {

                        background: #f1f1f1;

                        border: 1px solid #dddddd;

                }

                .spoiler-body {

                        background: #fbfbfb;

                        border-width: 0 1px 1px 1px;

                        border-style: solid;

                        border-color: #dddddd;

                }</style></head><body class="home wp-singular page-template page-template-page-home page-template-page-home-php page page-id-167 page-parent wp-theme-nure locale-uk-ua"><div class="wrapper ua"><header class="header anim"><div class="container-fluid"><div class="row"><div class="col-md-3 col-sm-4 col-xs-3"> <a href="https://nure.ua" class="logo-container"> <img src="https://nure.ua/wp-content/themes/nure/images/logo.png?v=2.0" class="logo" alt="ХНУРЕ "><div class="logo-block"><p>ХНУРЕ</p> <span>Харківський національний університет радіоелектроніки</span></div> </a></div><div class="header-menu-cover bg-dark-blue col-md-9 col-sm-8 col-xs-9"><div class="hidden-lg hidden-md"> <a href="#sidr" id="main-menu-open" class="toggleMenu"><i class="fa fa-bars" aria-hidden="true"></i></a></div><div class="row header-top"><ul class="header-address col-md-7"><li>просп. Науки, 14, м. Харків, 61023</li><li><a href="mailto:info@nure.ua">info@nure.ua</a></li><li><a href="tel:+380 (57) 720-9-027">+380 (57) 720-9-027</a></li></ul><div class="header-info col-md-5"><ul class="header-languages"><li><span title="Українська">ua</span></li><li><a href="https://nure.ua/en/" title="English">en</a></li></ul> <a href="https://nure.ua/universytet/kontakti" class="link">Контакти</a><div class="header-search"><form method="get" action="https://nure.ua"> <input type="text" name="s" class="search anim" value="" placeholder="Пошук" tabindex="1" autocomplete="off"> <button type="submit" class="button-search"><i class="fa fa-search" aria-hidden="true"></i></button></form></div></div></div><div id="main-menu" class="header-menu"><ul id="menu-holovne-meniu" class="main-menu"><li id="menu-item-45" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-45"><a href="https://nure.ua/universytet">Університет</a><i class="fa fa-angle-down anim" aria-hidden="true"></i><ul class="sub-menu"><li id="menu-item-31" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-31"><a href="https://nure.ua/universytet/pro-universitet">Про університет</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-34792" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-34792"><a href="https://nure.ua/branch/muzey-istoriyi-hnure/istorija-hnure">Історія ХНУРЕ</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-32" class="menu-item menu-item-type-taxonomy menu-item-object-people menu-item-32"><a href="https://nure.ua/people/kerivnitstvo-universitetu">Керівництво</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-46" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-46"><a href="https://nure.ua/branch/naglyadova-rada">Наглядова рада</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-47" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-47"><a href="https://nure.ua/branch/vchena-rada">Вчена рада</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-51" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-51"><a href="https://nure.ua/universytet/struktura">Структура</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-14153" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-14153"><a href="https://nure.ua/branch/viddil-litsenzuvannya-akreditatsiyi-ta-vnutrishnoyi-sistemi-zabezpechennya-yakosti-osviti">Ліцензування та акредитація</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-49" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-49"><a href="https://nure.ua/universytet/normativno-pravova-baza">Нормативно-правова база</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-40484" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-40484"><a href="https://nure.ua/branch/viddil-benchmarkingu-ta-veb-menedzhmentu/mizhnarodni-rejtingi">Міжнародні рейтинги</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-46485" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-46485"><a href="https://nure.ua/konferencii-ta-workshops/seminar-cili-stalogo-rozvitku-zavdannja-hnure-shhodo-ih-realizacii">Цілі сталого розвитку</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-102299" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-102299"><a href="https://nure.ua/kljuchovi-pokazniki-efektivnosti-kpi-kafedr">KPI кафедр університету</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-721" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-721"><a href="https://nure.ua/branch/vzmt-ta-kt" title="/branch/vzmt-ta-kt">Державні закупівлі</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-52" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-52"><a href="https://nure.ua/universytet/mizhnarodna-diyalnist">Міжнародна діяльність</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-29150" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-29150"><a href="https://nure.ua/universytet/it-prostir-nure">IT-простір NURE</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-29259" class="menu-item menu-item-type-taxonomy menu-item-object-people menu-item-29259"><a href="https://nure.ua/people/pochesni-profesori">Почесні професори ХНУРЕ</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-68" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-68"><a href="https://nure.ua/universytet/vipusknikam">Випускникам</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-149013" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-149013"><a href="https://nure.ua/universytet/blahodijna-dopomoha">Благодійна допомога</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-66" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-66"><a href="https://nure.ua/universytet/kontakti">Контакти</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li></ul></li><li id="menu-item-101" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-101"><a href="https://nure.ua/abituriyentam">Абітурієнтам</a><i class="fa fa-angle-down anim" aria-hidden="true"></i><ul class="sub-menu"><li id="menu-item-114" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-114"><a href="https://nure.ua/branch/pidgotovche-viddilennya">Підготовче відділення &#8220;Відкритий шлях до вищої освіти&#8221;</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-115" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-115"><a href="https://nure.ua/branch/priymalna-komissiya">Приймальна комісія</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-652" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-652"><a href="https://nure.ua/abituriyentam/pravila-prijomu">Правила прийому 2026</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-126109" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-126109"><a href="https://nure.ua/dohovory-publichnoi-oferty">Договори публічної оферти</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-102" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-102"><a href="https://nure.ua/abituriyentam/vstupna-kampanija">Вступна кампанія</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-109" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-109"><a href="https://nure.ua/abituriyentam/spetsialnosti-ta-spetsializatsiyi">Спеціальності (бакалавр, магістр, PhD)</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-108" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-108"><a href="https://nure.ua/abituriyentam/litsenziyni-obsyagi">Вартість, ліцензійні обсяги та держзамовлення</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-54733" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-54733"><a target="_blank" href="https://nure.ua/abituriyentam/rekviziti-oplati-kontraktu">Реквізити для оплати контракту</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-105" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-105"><a href="https://nure.ua/abituriyentam/vstup-inozemnim-gromadjanam">Вступ: Іноземним громадянам</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-54028" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-54028"><a target="_blank" href="https://nure.ua/branch/navchalno-naukoviy-tsentr-zaochnoyi-formi-navchannya">Заочне навчання</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-103" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-103"><a href="https://nure.ua/abituriyentam/druga-vishha-osvita">Друга вища освіта</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-107131" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-107131"><a href="https://nure.ua/abituriyentam/nostryfikatsiia-dokumentiv">Визнання іноземних документів про освіту</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-78180" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-78180"><a target="_blank" href="https://nure.ua/abituriyentam/links">Інфоресурси</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-122633" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-122633"><a href="https://nure.ua/abituriyentam/osvitni-tsentry-donbas-ukraina-ta-krym-ukraina">“Донбас-Україна” та “Крим-Україна”</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li></ul></li><li id="menu-item-113" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-113"><a href="https://nure.ua/studentam">Студентам</a><i class="fa fa-angle-down anim" aria-hidden="true"></i><ul class="sub-menu"><li id="menu-item-123043" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-123043"><a href="https://nure.ua/branch/vijskovo-mobilizatsijnyj-viddil">Інформація з військового обліку</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-128" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-128"><a href="https://nure.ua/studentam/stipendialniy-reyting">Стипендіальний рейтинг</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-117143" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-117143"><a href="https://nure.ua/studentam/stypendialne-zabezpechennia">Стипендіальне забезпечення</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-61525" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-61525"><a href="https://nure.ua/branch/navchalniy-viddil/studentskij-kvitok">Студентський квиток</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-12886" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-12886"><a target="_blank" href="http://cist.nure.ua/ias/app/tt/f?p=778:2">Розклад занять</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-114078" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-114078"><a href="https://nure.ua/osvita/edki">ЄДКІ</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-132" class="menu-item menu-item-type-post_type menu-item-object-public menu-item-132"><a href="https://nure.ua/public/profspilkoviy-komitet-studentiv">Профспілковий комітет студентів</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-133" class="menu-item menu-item-type-post_type menu-item-object-public menu-item-133"><a href="https://nure.ua/public/studentskiy-senat">Студентський сенат</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-131" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-131"><a href="https://nure.ua/branch/studentskiy-klub">Студентський клуб</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-130" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-130"><a href="https://nure.ua/branch/studmistechko">Студмістечко</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-94786" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-94786"><a href="https://nure.ua/medichnij-punkt-hnure">Медичний пункт ХНУРЕ</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-129" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-129"><a href="https://nure.ua/branch/sportivniy-klub-it-lyder">Спортивний клуб «Радіотехнік»</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-127" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-127"><a href="https://nure.ua/studentam/pratsevlashtuvannya">Працевлаштування</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-20566" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-20566"><a href="https://nure.ua/skillsschool">Skills School</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-56949" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-56949"><a target="_blank" href="https://nure.ua/blagodijnij-fond-povir-u-sebe-partner-hnure">БФ &#8220;Повір у себе&#8221;</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li></ul></li><li id="menu-item-110" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-110"><a href="https://nure.ua/nauka">Наука</a><i class="fa fa-angle-down anim" aria-hidden="true"></i><ul class="sub-menu"><li id="menu-item-728" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-728"><a href="https://nure.ua/branch/naukovo-tehnichna-rada">Науково-технічна рада</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-141" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-141"><a href="https://nure.ua/branch/naukovo-doslidna-chastina">Науково-дослідна частина</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-140" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-140"><a href="https://nure.ua/naukovi-shkoli">Наукові школи</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-722" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-722"><a href="https://nure.ua/branch/rada-molodih-vchenih">Рада молодих учених</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-137" class="menu-item menu-item-type-taxonomy menu-item-object-departments menu-item-137"><a href="https://nure.ua/departments/naukovi-vidannya">Наукові видання</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-139" class="menu-item menu-item-type-taxonomy menu-item-object-departments menu-item-139"><a href="https://nure.ua/departments/spetsializovani-radi">Спеціалізовані вчені ради</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-19784" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-19784"><a href="https://nure.ua/branch/viddil-aspiranturi-ta-doktoranturi">Аспірантура та докторантура</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-40631" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-40631"><a target="_blank" href="https://openarchive.nure.ua/?locale=uk">Репозитарій «ElAr KhNURE»</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-98280" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-98280"><a href="https://nure.ua/nauka/vinahidnicka-dijalnist">Винахідницька діяльність</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-81709" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-81709"><a target="_blank" href="https://nure.ua/nauka/sciencelabnure">Проєкт Science Labs NURE</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-21185" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-21185"><a href="https://nure.ua/konferencii-ta-workshops">Конференції / WorkShops</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-32717" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-32717"><a href="https://nure.ua/olimpiadi-konkursi">Олімпіади / конкурси / рейтинги</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-97011" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-97011"><a href="https://nure.ua/nauka/populjarizacija-nauki">Популяризація науки</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li></ul></li><li id="menu-item-111" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-111"><a href="https://nure.ua/osvita">Освіта</a><i class="fa fa-angle-down anim" aria-hidden="true"></i><ul class="sub-menu"><li id="menu-item-148" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-148"><a href="/faculty">Факультети, інститут та кафедри</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-146" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-146"><a href="/branch/naukova-biblioteka">Наукова бібліотека</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-19779" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-19779"><a href="https://nure.ua/branch/navchalno-metodichna-rada">Навчально-методична рада</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-145" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-145"><a target="_blank" href="http://cist.nure.ua/ias/app/tt/f?p=778:2">Розклад занять</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-65728" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-65728"><a target="_blank" href="https://nure.ua/branch/navchalniy-viddil/informacijni-povidomlennja-navchalnogo-viddilu">Графіки освітнього процесу</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-101270" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-101270"><a href="https://nure.ua/zagalnij-katalog-vibirkovih-navchalnih-disciplin">Каталог вибіркових навчальних дисциплін</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-76764" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-76764"><a href="https://nure.ua/branch/akademichna-dobrochesnist-ta-zabezpechennja-jakosti-osviti">Якість освіти та академічна доброчесність</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-147" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-147"><a target="_blank" href="http://catalogue.nure.ua/knmz/">Методичне забезпечення</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-755" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-755"><a href="https://nure.ua/branch/viddil-aspiranturi-ta-doktoranturi" title="/branch/viddil-aspiranturi-ta-doktoranturi">Аспірантура</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-155" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-155"><a href="https://nure.ua/branch/navchalno-naukoviy-tsentr-zaochnoyi-formi-navchannya">Заочна освіта</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-144" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-144"><a href="https://nure.ua/branch/tsentr-pislyadiplomnoyi-osviti">Післядипломна освіта</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-135409" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-135409"><a href="https://nure.ua/dualna-osvita">Дуальна освіта</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-107921" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-107921"><a href="https://nure.ua/universytet/neformalna-informalna-osvita">Неформальна та інформальна освіта</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-104286" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-104286"><a href="https://nure.ua/osvita/vijskova-pidgotovka">Військова підготовка</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-156" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-156"><a href="https://nure.ua/osvita/inozemnim-gromadyanam">Іноземним громадянам</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li></ul></li><li id="menu-item-112" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-112"><a href="https://nure.ua/pres-tsentr">Прес-центр</a><i class="fa fa-angle-down anim" aria-hidden="true"></i><ul class="sub-menu"><li id="menu-item-161" class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-161"><a href="https://nure.ua/branch/pres-sluzhba-mediatsentr">Прес-служба «Медіацентр»</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-164" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-164"><a href="https://nure.ua/novini">Новини та події</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-163" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-163"><a href="https://nure.ua/media-galereja">Медіа галерея</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-78187" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-78187"><a target="_blank" href="https://nure.ua/abituriyentam/links">Інфоресурси для абітурієнтів</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-116998" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-116998"><a href="https://nure.ua/pres-tsentr/kiberpolitsiia-zasterihaie-vid-shakhraiv">Кіберполіція інформує!</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li><li id="menu-item-77822" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-77822"><a href="https://nure.ua/zapobigannja-vijavlennja-i-pripinennja-teroristichnoi-dijalnosti">Запобігання, виявлення і припинення терористичної діяльності</a><i class="fa fa-angle-down anim" aria-hidden="true"></i></li></ul></li></ul></div></div></div></div></header><main><div class="slider-cover bg-white"><div class="container-fluid"><div class="row"><div class="col-sm-4 col-md-3 hidden-xs"></div><div class="main-slider"><div id="sync1" class="owl-carousel owl-theme big-images"> <img src="https://nure.ua/wp-content/uploads/2026/bz-2026-prk.jpg" alt="Додатковий набір"> <img src="https://nure.ua/wp-content/uploads/News_Gallery/stud-2026.jpg" alt="Консультаційний центр ХНУРЕ"> <img src="https://nure.ua/wp-content/uploads/News_Gallery/onl_3.jpg" alt="Онлайн-консультації"> <img src="https://nure.ua/wp-content/uploads/News_Gallery/kd_ua.jpg" alt="Вступникам з Криму та Донбасу"> <img src="https://nure.ua/wp-content/uploads/News_Gallery/v_ua.jpg" alt="Вступ ветеранів та ветеранок"> <img src="https://nure.ua/wp-content/uploads/img_20231017_070803_531.jpg" alt="Запрошуємо на підготовче відділення!"> <img src="https://nure.ua/wp-content/uploads/News_Gallery/onl_4.jpg" alt="Напрями підготовки ХНУРЕ"> <img src="https://nure.ua/wp-content/uploads/News_Gallery/gl_uk.jpg" alt="Гаряча лінія ХНУРЕ"> <img src="https://nure.ua/wp-content/uploads/News_Gallery/ranc_2026-ua.jpg" alt="ХНУРЕ у світових рейтингах"></div><div id="sync2" class="owl-carousel owl-theme thumbs "><div class="text-cover"><div class="bg-grey"> <span class="label">#Вступ-2026</span><p class="headline">Додатковий набір</p><div class="info-cover hidden-xs"><p>ХНУРЕ оголошує додатковий набір вступників на навчання <strong> </strong>на вільні місця ліцензійного обсягу в <strong>МАГІСТРАТУРУ</strong> (за кошти фізичних та/або юридичних осіб, денна/заочна форма)</p><p>&nbsp;</p></div> <a href="https://nure.ua/uvaha-khnure-oholoshuie-dodatkovyj-nabir-vstupnykiv-na-navchannia-na-vilni-mistsia-litsenzijnoho-obsiahu-v-mahistraturu-za-koshty-fizychnykh-ta-abo-iurydychnykh-osib-denna-zaochna-forma" class="btn-bordered anim">Детальніше</a></div></div><div class="text-cover"><div class="bg-grey"> <span class="label">#Вступ-2026</span><p class="headline">Консультаційний центр ХНУРЕ</p><div class="info-cover hidden-xs"><p>Має бажання стати крутим програмістом, створювати інновації в робототехніці, створити власний штучний інтелект?</p><p>Запрошуємо до консультаційного центру ХНУРЕ, ми розповімо про те, де цього можна навчитися в Україні!</p></div> <a href="https://nure.ua/konsultatsijnyj-tsentr-khnure-dopomahaie-vstupnykam-pid-chas-vstupnoi-kampanii-2026-roku" class="btn-bordered anim">Детальніше</a></div></div><div class="text-cover"><div class="bg-grey"> <span class="label">#Вступ-2026</span><p class="headline">Онлайн-консультації</p><div class="info-cover hidden-xs"><p class="isSelectedEnd">Онлайн-консультації для вступників <span style="text-decoration: underline;"><strong>щосереди о 18:00</strong></span>. Надаємо відповіді на всі питання щодо вступу в бакалаврат, магістратуру, аспірантуру та докторантуру.</p><p><strong>Приєднуйся: <a href="https://meet.google.com/ukx-nqpe-ovt">meet.google.com/ukx-nqpe-ovt</a></strong></p></div></div></div><div class="text-cover"><div class="bg-grey"> <span class="label">#UA</span><p class="headline">Вступникам з Криму та Донбасу</p><div class="info-cover hidden-xs"><p>Україна чекає на дітей і молодь з тимчасово окупованих територій і створює умови, щоб цей шлях був реальним, доступним і безпечним.</p><p><strong>Телефон (Viber, WhatsApp): +38 (093) 319-81-90</strong></p></div> <a href="https://nure.ua/abituriyentam/osvitni-tsentry-donbas-ukraina-ta-krym-ukraina" class="btn-bordered anim">Детальніше</a></div></div><div class="text-cover"><div class="bg-grey"> <span class="label">#UA</span><p class="headline">Вступ ветеранів та ветеранок</p><div class="info-cover hidden-xs"><p>Україна <strong>створює</strong> рівні умови для навчання всім.</p><p>ХНУРЕ <strong>реалізує</strong> це у свої політиці підтримок ветеранів та захисників України.</p><p><strong><span style="text-decoration: underline;">Запрошуємо на навчання до ХНУРЕ!</span></strong></p></div> <a href="https://nure.ua/abituriyentam/vstupna-kampanija/pilhovyj-vstup-dlia-veteraniv-i-veteranok" class="btn-bordered anim">Детальніше</a></div></div><div class="text-cover"><div class="bg-grey"> <span class="label">#GO_to_NURE</span><p class="headline">Запрошуємо на підготовче відділення!</p><div class="info-cover hidden-xs"><p>Ти плануєш вступити до ХНУРЕ?</p><p>Тепер ти можеш знайти детальну інформацію про навики, що будеш опановувати, вартість та графік навчання, аби обрати саме те, що <a href="https://drive.google.com/file/d/1L9hxZyzZbvJJUxf1GStYTaKJ1re6Yu66/view?usp=sharing">ідеально підходить тобі</a>!</p><p>Займайся саморозвитком разом з Підготовчим відділенням Першого серед кращих!</p></div> <a href="https://drive.google.com/file/d/1L9hxZyzZbvJJUxf1GStYTaKJ1re6Yu66/view?usp=sharing" class="btn-bordered anim">Детальніше</a></div></div><div class="text-cover"><div class="bg-grey"> <span class="label">#Абітурієнтам</span><p class="headline">Напрями підготовки ХНУРЕ</p><div class="info-cover hidden-xs"><p class="isSelectedEnd">Дізнайся більше про спеціальності, напрями підготовки та можливості для майбутніх студентів.</p><p><strong>Твій шлях до ІТ, інженерії, науки та інновацій починається тут.</strong></p></div> <a href="/abituriyentam/spetsialnosti-ta-spetsializatsiyi" class="btn-bordered anim">Детальніше</a></div></div><div class="text-cover"><div class="bg-grey"> <span class="label">#HOTLINE</span><p class="headline">Гаряча лінія ХНУРЕ</p><div class="info-cover hidden-xs"><p>На час воєнного стану в ХНУРЕ працюють телефони гарячої лінії для оперативного зв’язку з університетом.</p><ul><li>+380 (57) 702-10-13 (внутрішній 268)</li><li>+380 (98) 709-47-56 (внутрішній 268)</li><li>+380 (57) 702-17-36</li><li>+380 (93) 785-02-87</li><li>+380 (66) 097-75-30</li><li>+380 (96) 087-30-09</li><li>+380 (96) 479-85-43</li></ul></div></div></div><div class="text-cover"><div class="bg-grey"> <span class="label">#Rankings</span><p class="headline">ХНУРЕ у світових рейтингах</p><div class="info-cover hidden-xs"><p class="isSelectedEnd"><strong><a href="https://nure.ua/en/nure-in-qs-world-university-rankings-europe-2026-2"><span style="color: #ff6600;">QS Europe 2026</span></a>:</strong> 561-570 в Європі</p><p class="isSelectedEnd"><strong><span style="color: #ff0000;"><a style="color: #ff0000;" href="https://nure.ua/en/nure-in-the-qs-world-university-rankings-by-subject-2026">QS Subject 2026</a></span>:</strong> Computer Science &amp; Information Systems &#8211; 651-700</p><p class="isSelectedEnd"><strong><a href="https://nure.ua/en/nure-in-times-higher-education-world-university-rankings-2026-2">THE Subject Rankings</a>:</strong> No. 1 в Україні по Computer Science</p><p><strong>ХНУРЕ впевнено представлений у провідних світових рейтингах університетів!</strong></p></div></div></div></div></div></div></div></div><div class="news-cover container-fluid"><p class="headline">Новини</p><div class="row"><div class="anim animate-left animate-fade col-md-3 hidden-sm hidden-xs"><div class="sidebar bg-dark-blue"><ul id="menu-bokove-meniu" class=""><li id="menu-item-177" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-177"><a target="_blank" href="https://mon.gov.ua"><div class="icon-cover"><img src="https://nure.ua/wp-content/uploads/Icons/ico4.png" alt="Мiнiстерство освiти i науки України"></div><span class="title">Мiнiстерство освiти i науки України</span></a></li><li id="menu-item-178" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-178"><a target="_blank" href="https://naqa.gov.ua/"><div class="icon-cover"><img src="https://nure.ua/wp-content/uploads/Icons/ico5.png" alt="Національне агентство із забезпечення якості вищої освіти"></div><span class="title">Національне агентство із забезпечення якості вищої освіти</span></a></li><li id="menu-item-174" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-174"><a target="_blank" href="http://lib.nure.ua/"><div class="icon-cover"><img src="https://nure.ua/wp-content/uploads/Icons/ico1.png" alt="Наукова бібліотека"></div><span class="title">Наукова бібліотека</span></a></li><li id="menu-item-175" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-175"><a target="_blank" href="http://cist.nure.ua/ias/app/tt/f?p=778:2"><div class="icon-cover"><img src="https://nure.ua/wp-content/uploads/Icons/ico2.png" alt="Розклад занять"></div><span class="title">Розклад занять</span></a></li><li id="menu-item-176" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-176"><a target="_blank" href="http://ctdl.nure.ua/"><div class="icon-cover"><img src="https://nure.ua/wp-content/uploads/Icons/ico3.png" alt="Дистанційна освіта"></div><span class="title">Дистанційна освіта</span></a></li></ul></div></div><div class="main-article-cover anim animate-right animate-fade col-md-9 col-sm-12 col-xs-12"><div class="main-article bg-white"><div class="label">Новини</div> <img src="https://nure.ua/wp-content/uploads/2026/17e882cc-4871-4853-bd37-80ccfec3460d-360x315.png" class="main-img" alt="Виконання умов до зарахування до магістратури"><div class="text-block"> <a href="https://nure.ua/vykonannia-umov-do-zarakhuvannia" class="title">Виконання умов до зарахування до магістратури</a> <span class="date">24.08.2026</span><p style="text-align: center;"><span style="font-size: 14pt;">Ваш наступний крок до вступу &#8211;</span></p><p style="text-align: center;"><strong><span style="text-decoration: underline;"><span style="font-size: 18pt;"><a href="https://nure.ua/abituriyentam/vstupna-kampanija/poriadok-podannia-dokumentiv-na-vstup-do-mahistratury-denna-zaochna-forma/vykonannia-umov-zarakhuvannia">виконання умов зарахування до магістратури</a></span></span></strong></p></div></div></div></div><div class="row article-list"><div class="sub-article-cover col-md-3 col-sm-6 col-xs-12 anim animate-fade animate-bottom"><div class="sub-article bg-white "><div class="label">Новини</div> <a href="https://nure.ua/studentka-khnure-zdobula-sriblo-na-europe-women-s-programming-contest-2026" class="title">Студентка ХНУРЕ здобула срібло на Europe Women’s Programming Contest 2026</a> <span class="date">17.09.2026</span><p class="PDq2pG_selectionAnchorContainer" dir="auto" data-start="83" data-end="417">Студентка ХНУРЕ <strong data-start="150" data-end="169">Дарина Карпенко</strong> виборола срібну медаль на міжнародному змаганні з алгоритмічного програмування <strong data-start="249" data-end="299">Europe Women’s Programming Contest (EWPC 2026)</strong>.</p><p dir="auto" data-start="83" data-end="417"></p></div></div><div class="sub-article-cover col-md-3 col-sm-6 col-xs-12 anim animate-fade animate-bottom"><div class="sub-article bg-white "><div class="label">Новини</div> <a href="https://nure.ua/rukhaiemosia-razom-u-khnure-vidbuvsia-sportyvnyj-fleshmob" class="title">Рухаємося разом: у ХНУРЕ відбувся спортивний флешмоб!</a> <span class="date">17.09.2026</span><p class="PDq2pG_selectionAnchorContainer" dir="auto" style="text-align: justify;" data-start="63" data-end="408">З 8 по 14 вересня 2026 року у ХНУРЕ проходив спортивний флешмоб, присвячений Дню фізичної культури і спорту України.</p><p dir="auto" style="text-align: justify;" data-start="63" data-end="408"></p></div></div><div class="sub-article-cover col-md-3 col-sm-6 col-xs-12 anim animate-fade animate-bottom"><div class="sub-article bg-white "><div class="label">Новини</div> <a href="https://nure.ua/uvaha-khnure-oholoshuie-dodatkovyj-nabir-vstupnykiv-na-navchannia-na-vilni-mistsia-litsenzijnoho-obsiahu-v-mahistraturu-za-koshty-fizychnykh-ta-abo-iurydychnykh-osib-denna-zaochna-forma" class="title">Увага! ХНУРЕ оголошує додатковий набір вступників на навчання  на вільні місця ліцензійного обсягу в МАГІСТРАТУРУ (за кошти фізичних та/або юридичних осіб, денна/заочна форма)</a> <span class="date">14.09.2026</span></p></div></div><div class="sub-article-cover col-md-3 col-sm-6 col-xs-12 anim animate-fade animate-bottom"><div class="sub-article bg-white "><div class="label">Новини</div> <a href="https://nure.ua/khnure-na-vseukrainskomu-molodizhnomu-forumi-ukraina-2036-arkhitektory-majbutnoho" class="title">ХНУРЕ на Всеукраїнському молодіжному форумі «Україна 2036. Архітектори майбутнього»</a> <span class="date">14.09.2026</span><p class="PDq2pG_selectionAnchorContainer" data-start="88" data-end="328">8 вересня 2026 року представники студентського самоврядування Харківського національного університету радіоелектроніки взяли участь у Всеукраїнському молодіжному форумі <strong data-start="257" data-end="300">«Україна 2036. Архітектори майбутнього»</strong>, що відбувся на Рівненщині.</p><p data-start="88" data-end="328"></p></div></div></div></div><div class="video-container anim animate-fade"> <img src="https://nure.ua/wp-content/themes/nure/images/video-img.jpg" alt=""><div class="video-block"><div class="video-table"><div class="video-row"> <a data-fancybox="" href="https://www.youtube.com/watch?v=EtS-EB7mJak" savefrom_lm_index="2" savefrom_lm="1"><img src="https://nure.ua/wp-content/themes/nure/images/icons/play-ico.png" alt="" class="play-ico"></a><p class="title">ХНУРЕ - перший серед кращих!</p></div></div></div></div><div class="bg-white"><div class="partners-container container bg-white"><p class="headline">Партнери</p><div class="partner-list row"><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://itukraine.org.ua/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/it_ukrane_association.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://ec.europa.eu/programmes/erasmus-plus/" target="_blank"><img src="https://nure.ua/wp-content/uploads/InternationalActivity/erasmuslogo1.png" alt="Erasmus+"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://www.microsoft.com/uk-ua" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/microsoft.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://www.epam.com/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/epam.png" alt="EPAM Systems"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://nixsolutions.com/ " target="_blank"><img src="https://nure.ua/wp-content/uploads/2024/nix.png" alt="Nix Solutions"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://it-kharkiv.com/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/logo_it-cluster.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://globallogic.com/ " target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/globallogic.png" alt="GlobalLogic"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://sigma.software/ " target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/sigma.png" alt="Sigma"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="http://www.gameloft.com/ " target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/gameloft.png" alt="Gameloft"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="http://jabil.com" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/jabil.png" alt="Jabil"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://clarity-project.info/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2026/logo-clarity-project-.jpg" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="/partnerstvo-hnure-ta-turkish-airlines" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/turkishairlines.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://www.andersenlab.com" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/andersen_logo_preview.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://intetics.com" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/intetics_logo.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://program-ace.com" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/program-ace.jpg" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://www.softserveinc.com" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/softserve-logo-rgb.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://distributedlab.com/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/distributed-lab.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://rubika.com.ua" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/rubika.png" alt="Rubika"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://www.zfort.com.ua" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/view_zfort_logo_600x400.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://csltd.com.ua/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/cs.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://lnu.edu.ua/" target="_blank"><img src="https://nure.ua/wp-content/uploads/Main_Docs_NURE/lnu.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://www.cisco.com/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/cisco_logo_no_tm_sky_blue-rgb.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://maxnet.ua" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/maxnet-uk.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="http://www.infotech.com.ua/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/hikvision.jpg" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://dataart.team/" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/dataart.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="http://flex.com" target="_blank"><img src="https://nure.ua/wp-content/uploads/2018/01/flex.jpg" alt="Flex"></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://jobs.g5e.com" target="_blank"><img src="https://nure.ua/wp-content/uploads/Benchmarking/6044_logo-g5-e1570479363358.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://cloudwk.com/" target="_blank"><img src="https://nure.ua/wp-content/uploads/cw.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://www.altexsoft.com/" target="_blank"><img src="https://nure.ua/wp-content/uploads/as.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://promodo.ua/" target="_blank"><img src="https://nure.ua/wp-content/uploads/promodo.png" alt=""></a></div><div class="partner-item col-md-4 col-xs-4 anim animate-fade animate-top"> <a href="https://solid.software" target="_blank"><img src="https://nure.ua/wp-content/uploads/Main_Docs_NURE/solid.png" alt=""></a></div></div></div></div></main><footer class="footer bg-dark-blue anim animate-fade animate-bottom"><div class="container-fluid"><ul id="menu-holovne-meniu-1" class="footer-main-menu anim"><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-45"><a href="https://nure.ua/universytet">Університет</a><ul class="sub-menu"><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-31"><a href="https://nure.ua/universytet/pro-universitet">Про університет</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-34792"><a href="https://nure.ua/branch/muzey-istoriyi-hnure/istorija-hnure">Історія ХНУРЕ</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-people menu-item-32"><a href="https://nure.ua/people/kerivnitstvo-universitetu">Керівництво</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-46"><a href="https://nure.ua/branch/naglyadova-rada">Наглядова рада</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-47"><a href="https://nure.ua/branch/vchena-rada">Вчена рада</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-51"><a href="https://nure.ua/universytet/struktura">Структура</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-14153"><a href="https://nure.ua/branch/viddil-litsenzuvannya-akreditatsiyi-ta-vnutrishnoyi-sistemi-zabezpechennya-yakosti-osviti">Ліцензування та акредитація</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-49"><a href="https://nure.ua/universytet/normativno-pravova-baza">Нормативно-правова база</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-40484"><a href="https://nure.ua/branch/viddil-benchmarkingu-ta-veb-menedzhmentu/mizhnarodni-rejtingi">Міжнародні рейтинги</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-46485"><a href="https://nure.ua/konferencii-ta-workshops/seminar-cili-stalogo-rozvitku-zavdannja-hnure-shhodo-ih-realizacii">Цілі сталого розвитку</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-102299"><a href="https://nure.ua/kljuchovi-pokazniki-efektivnosti-kpi-kafedr">KPI кафедр університету</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-721"><a href="https://nure.ua/branch/vzmt-ta-kt" title="/branch/vzmt-ta-kt">Державні закупівлі</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-52"><a href="https://nure.ua/universytet/mizhnarodna-diyalnist">Міжнародна діяльність</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-29150"><a href="https://nure.ua/universytet/it-prostir-nure">IT-простір NURE</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-people menu-item-29259"><a href="https://nure.ua/people/pochesni-profesori">Почесні професори ХНУРЕ</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-68"><a href="https://nure.ua/universytet/vipusknikam">Випускникам</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-149013"><a href="https://nure.ua/universytet/blahodijna-dopomoha">Благодійна допомога</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-66"><a href="https://nure.ua/universytet/kontakti">Контакти</a></li></ul></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-101"><a href="https://nure.ua/abituriyentam">Абітурієнтам</a><ul class="sub-menu"><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-114"><a href="https://nure.ua/branch/pidgotovche-viddilennya">Підготовче відділення &#8220;Відкритий шлях до вищої освіти&#8221;</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-115"><a href="https://nure.ua/branch/priymalna-komissiya">Приймальна комісія</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-652"><a href="https://nure.ua/abituriyentam/pravila-prijomu">Правила прийому 2026</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-126109"><a href="https://nure.ua/dohovory-publichnoi-oferty">Договори публічної оферти</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-102"><a href="https://nure.ua/abituriyentam/vstupna-kampanija">Вступна кампанія</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-109"><a href="https://nure.ua/abituriyentam/spetsialnosti-ta-spetsializatsiyi">Спеціальності (бакалавр, магістр, PhD)</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-108"><a href="https://nure.ua/abituriyentam/litsenziyni-obsyagi">Вартість, ліцензійні обсяги та держзамовлення</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-54733"><a target="_blank" href="https://nure.ua/abituriyentam/rekviziti-oplati-kontraktu">Реквізити для оплати контракту</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-105"><a href="https://nure.ua/abituriyentam/vstup-inozemnim-gromadjanam">Вступ: Іноземним громадянам</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-54028"><a target="_blank" href="https://nure.ua/branch/navchalno-naukoviy-tsentr-zaochnoyi-formi-navchannya">Заочне навчання</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-103"><a href="https://nure.ua/abituriyentam/druga-vishha-osvita">Друга вища освіта</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-107131"><a href="https://nure.ua/abituriyentam/nostryfikatsiia-dokumentiv">Визнання іноземних документів про освіту</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-78180"><a target="_blank" href="https://nure.ua/abituriyentam/links">Інфоресурси</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-122633"><a href="https://nure.ua/abituriyentam/osvitni-tsentry-donbas-ukraina-ta-krym-ukraina">“Донбас-Україна” та “Крим-Україна”</a></li></ul></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-113"><a href="https://nure.ua/studentam">Студентам</a><ul class="sub-menu"><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-123043"><a href="https://nure.ua/branch/vijskovo-mobilizatsijnyj-viddil">Інформація з військового обліку</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-128"><a href="https://nure.ua/studentam/stipendialniy-reyting">Стипендіальний рейтинг</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-117143"><a href="https://nure.ua/studentam/stypendialne-zabezpechennia">Стипендіальне забезпечення</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-61525"><a href="https://nure.ua/branch/navchalniy-viddil/studentskij-kvitok">Студентський квиток</a></li><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-12886"><a target="_blank" href="http://cist.nure.ua/ias/app/tt/f?p=778:2">Розклад занять</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-114078"><a href="https://nure.ua/osvita/edki">ЄДКІ</a></li><li class="menu-item menu-item-type-post_type menu-item-object-public menu-item-132"><a href="https://nure.ua/public/profspilkoviy-komitet-studentiv">Профспілковий комітет студентів</a></li><li class="menu-item menu-item-type-post_type menu-item-object-public menu-item-133"><a href="https://nure.ua/public/studentskiy-senat">Студентський сенат</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-131"><a href="https://nure.ua/branch/studentskiy-klub">Студентський клуб</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-130"><a href="https://nure.ua/branch/studmistechko">Студмістечко</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-94786"><a href="https://nure.ua/medichnij-punkt-hnure">Медичний пункт ХНУРЕ</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-129"><a href="https://nure.ua/branch/sportivniy-klub-it-lyder">Спортивний клуб «Радіотехнік»</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-127"><a href="https://nure.ua/studentam/pratsevlashtuvannya">Працевлаштування</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-20566"><a href="https://nure.ua/skillsschool">Skills School</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-56949"><a target="_blank" href="https://nure.ua/blagodijnij-fond-povir-u-sebe-partner-hnure">БФ &#8220;Повір у себе&#8221;</a></li></ul></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-110"><a href="https://nure.ua/nauka">Наука</a><ul class="sub-menu"><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-728"><a href="https://nure.ua/branch/naukovo-tehnichna-rada">Науково-технічна рада</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-141"><a href="https://nure.ua/branch/naukovo-doslidna-chastina">Науково-дослідна частина</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-140"><a href="https://nure.ua/naukovi-shkoli">Наукові школи</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-722"><a href="https://nure.ua/branch/rada-molodih-vchenih">Рада молодих учених</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-departments menu-item-137"><a href="https://nure.ua/departments/naukovi-vidannya">Наукові видання</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-departments menu-item-139"><a href="https://nure.ua/departments/spetsializovani-radi">Спеціалізовані вчені ради</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-19784"><a href="https://nure.ua/branch/viddil-aspiranturi-ta-doktoranturi">Аспірантура та докторантура</a></li><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-40631"><a target="_blank" href="https://openarchive.nure.ua/?locale=uk">Репозитарій «ElAr KhNURE»</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-98280"><a href="https://nure.ua/nauka/vinahidnicka-dijalnist">Винахідницька діяльність</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-81709"><a target="_blank" href="https://nure.ua/nauka/sciencelabnure">Проєкт Science Labs NURE</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-21185"><a href="https://nure.ua/konferencii-ta-workshops">Конференції / WorkShops</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-32717"><a href="https://nure.ua/olimpiadi-konkursi">Олімпіади / конкурси / рейтинги</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-97011"><a href="https://nure.ua/nauka/populjarizacija-nauki">Популяризація науки</a></li></ul></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-111"><a href="https://nure.ua/osvita">Освіта</a><ul class="sub-menu"><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-148"><a href="/faculty">Факультети, інститут та кафедри</a></li><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-146"><a href="/branch/naukova-biblioteka">Наукова бібліотека</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-19779"><a href="https://nure.ua/branch/navchalno-metodichna-rada">Навчально-методична рада</a></li><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-145"><a target="_blank" href="http://cist.nure.ua/ias/app/tt/f?p=778:2">Розклад занять</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-65728"><a target="_blank" href="https://nure.ua/branch/navchalniy-viddil/informacijni-povidomlennja-navchalnogo-viddilu">Графіки освітнього процесу</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-101270"><a href="https://nure.ua/zagalnij-katalog-vibirkovih-navchalnih-disciplin">Каталог вибіркових навчальних дисциплін</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-76764"><a href="https://nure.ua/branch/akademichna-dobrochesnist-ta-zabezpechennja-jakosti-osviti">Якість освіти та академічна доброчесність</a></li><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-147"><a target="_blank" href="http://catalogue.nure.ua/knmz/">Методичне забезпечення</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-755"><a href="https://nure.ua/branch/viddil-aspiranturi-ta-doktoranturi" title="/branch/viddil-aspiranturi-ta-doktoranturi">Аспірантура</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-155"><a href="https://nure.ua/branch/navchalno-naukoviy-tsentr-zaochnoyi-formi-navchannya">Заочна освіта</a></li><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-144"><a href="https://nure.ua/branch/tsentr-pislyadiplomnoyi-osviti">Післядипломна освіта</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-135409"><a href="https://nure.ua/dualna-osvita">Дуальна освіта</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-107921"><a href="https://nure.ua/universytet/neformalna-informalna-osvita">Неформальна та інформальна освіта</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-104286"><a href="https://nure.ua/osvita/vijskova-pidgotovka">Військова підготовка</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-156"><a href="https://nure.ua/osvita/inozemnim-gromadyanam">Іноземним громадянам</a></li></ul></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-112"><a href="https://nure.ua/pres-tsentr">Прес-центр</a><ul class="sub-menu"><li class="menu-item menu-item-type-post_type menu-item-object-branch menu-item-161"><a href="https://nure.ua/branch/pres-sluzhba-mediatsentr">Прес-служба «Медіацентр»</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-164"><a href="https://nure.ua/novini">Новини та події</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-163"><a href="https://nure.ua/media-galereja">Медіа галерея</a></li><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-78187"><a target="_blank" href="https://nure.ua/abituriyentam/links">Інфоресурси для абітурієнтів</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-116998"><a href="https://nure.ua/pres-tsentr/kiberpolitsiia-zasterihaie-vid-shakhraiv">Кіберполіція інформує!</a></li><li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-77822"><a href="https://nure.ua/zapobigannja-vijavlennja-i-pripinennja-teroristichnoi-dijalnosti">Запобігання, виявлення і припинення терористичної діяльності</a></li></ul></li></ul><div class="footer-bottom row"><div class="social col-xs-12"><ul id="menu-sotsyalnye-sety" class="social-menu"><li id="menu-item-185" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-185"><a target="_blank" href="https://www.facebook.com/profile.php?id=61578407176131"><i class="fa fa-facebook" aria-hidden="true"></i></a></li><li id="menu-item-186" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-186"><a target="_blank" href="https://www.instagram.com/khnure_official/"><i class="fa fa-instagram" aria-hidden="true"></i></a></li><li id="menu-item-187" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-187"><a target="_blank" href="https://www.youtube.com/@mediaNURE"><i class="fa fa-youtube-play" aria-hidden="true"></i></a></li><li id="menu-item-63163" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-63163"><a target="_blank" href="https://www.linkedin.com/school/kharkiv-national-university-of-radioelectronics/"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li><li id="menu-item-89598" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-89598"><a href="https://twitter.com/PressNURE"><i class="fa fa-twitter" aria-hidden="true"></i></a></li><li id="menu-item-136683" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-136683"><a href="https://www.tiktok.com/@nure.official"><img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/tiktok.svg" alt="TikTok"      style="width: 20px; height: 19px; filter: brightness(0) saturate(100%) invert(53%) sepia(92%) saturate(686%) hue-rotate(157deg) brightness(105%) contrast(102%);"></a></li></ul> <a href="http://mon.gov.ua/" target="_blank" class="logo-mon"><img src="https://nure.ua/wp-content/themes/nure/images/icons/mon.png" alt=""></a><p class="copy">&copy; ХНУРЕ, 2001&mdash;2026, Усі права захищені<br><small>Створення та розробка сайтів - <a href="https://rubika.com.ua" target="_blank">Rubika</a></small></p></div></div></div></footer></div> <script type="speculationrules">{"prefetch":[{"source":"document","where":{"and":[{"href_matches":"/*"},{"not":{"href_matches":["/wp-*.php","/wp-admin/*","/wp-content/uploads/*","/wp-content/*","/wp-content/plugins/*","/wp-content/themes/nure/*","/*\\?(.+)"]}},{"not":{"selector_matches":"a[rel~=\"nofollow\"]"}},{"not":{"selector_matches":".no-prefetch, .no-prefetch a"}}]},"eagerness":"conservative"}]}</script> <script id="simple-spoiler-script-js" src="https://nure.ua/wp-content/plugins/simple-spoiler/js/simple-spoiler.min.js?ver=1.5"></script> <script id="pll_cookie_script-js-after">(function() {

                                var expirationDate = new Date();

                                expirationDate.setTime( expirationDate.getTime() + 31536000 * 1000 );

                                document.cookie = "pll_language=ua; expires=" + expirationDate.toUTCString() + "; path=/; secure; SameSite=Lax";

                        }());


//# sourceURL=pll_cookie_script-js-after</script> <script id="bootstrap-js" src="https://nure.ua/wp-content/themes/nure/libs/bootstrap/js/bootstrap.min.js?ver=7.0.4"></script> <script id="sidr-js" src="https://nure.ua/wp-content/themes/nure/libs/sidr/jquery.sidr.min.js?ver=7.0.4"></script> <script id="owl-js" src="https://nure.ua/wp-content/themes/nure/libs/owlcarousel/owl.carousel.min.js?ver=7.0.4"></script> <script id="fancybox-js" src="https://nure.ua/wp-content/themes/nure/libs/fancybox/jquery.fancybox.min.js?ver=7.0.4"></script> <script id="scroll-js" src="https://nure.ua/wp-content/themes/nure/libs/jquery.mCustomScrollbar/jquery.mCustomScrollbar.concat.min.js?ver=7.0.4"></script> <script id="formstyler-js" src="https://nure.ua/wp-content/themes/nure/libs/jquery.formstyler/jquery.formstyler.min.js?ver=7.0.4"></script> <script id="table.sorter-js" src="https://nure.ua/wp-content/themes/nure/libs/jquery.tablesorter.min.js?ver=7.0.4"></script> <script id="tree-app-js" src="https://nure.ua/wp-content/themes/nure/js/tree/app.js?ver=7.0.4"></script> <script id="hammer-js" src="https://nure.ua/wp-content/themes/nure/js/tree/hammer.min.js?ver=7.0.4"></script> <script id="nure-js-extra">var wp_vars = {"wp_ajaxurl":"https://nure.ua/wp-admin/admin-ajax.php","wp_nonce":"b0e4ccfcad"};

//# sourceURL=nure-js-extra</script> <script id="nure-js" src="https://nure.ua/wp-content/themes/nure/js/nure.js?ver=7.0.4"></script> <script type="text/javascript">jQuery(document).ready(function ($) {


            for (let i = 0; i < document.forms.length; ++i) {

                let form = document.forms[i];

                                if ($(form).attr("method") != "get") { $(form).append('<input type="hidden" name="nxyFgKljL" value="SCVNhDY5s2MgQ]" />'); }

if ($(form).attr("method") != "get") { $(form).append('<input type="hidden" name="lCqPAVmE" value="[qh8xilc@uZ" />'); }

if ($(form).attr("method") != "get") { $(form).append('<input type="hidden" name="tHoYvrckhgXyKQO" value="UNfhy3G" />'); }

if ($(form).attr("method") != "get") { $(form).append('<input type="hidden" name="brsCyM" value="pNzHQCuY" />'); }

            }


            $(document).on('submit', 'form', function () {

                                if ($(this).attr("method") != "get") { $(this).append('<input type="hidden" name="nxyFgKljL" value="SCVNhDY5s2MgQ]" />'); }

if ($(this).attr("method") != "get") { $(this).append('<input type="hidden" name="lCqPAVmE" value="[qh8xilc@uZ" />'); }

if ($(this).attr("method") != "get") { $(this).append('<input type="hidden" name="tHoYvrckhgXyKQO" value="UNfhy3G" />'); }

if ($(this).attr("method") != "get") { $(this).append('<input type="hidden" name="brsCyM" value="pNzHQCuY" />'); }

                return true;

            });


            jQuery.ajaxSetup({

                beforeSend: function (e, data) {


                    if (data.type !== 'POST') return;


                    if (typeof data.data === 'object' && data.data !== null) {

                                                data.data.append("nxyFgKljL", "SCVNhDY5s2MgQ]");

data.data.append("lCqPAVmE", "[qh8xilc@uZ");

data.data.append("tHoYvrckhgXyKQO", "UNfhy3G");

data.data.append("brsCyM", "pNzHQCuY");

                    }

                    else {

                        data.data = data.data + '&nxyFgKljL=SCVNhDY5s2MgQ]&lCqPAVmE=[qh8xilc@uZ&tHoYvrckhgXyKQO=UNfhy3G&brsCyM=pNzHQCuY';

                    }

                }

            });


        });</script> </body></html>* Connection #0 to host nure.ua:443 left intact 
```

---

### A.2. Запит без захисту з'єднання

**Команда:**

```
curl -v http://neverssl.com
```

**Вивід:**

```
* Host neverssl.com:80 was resolved.
* IPv6: (none)
* IPv4: 34.223.124.45
*   Trying 34.223.124.45:80...
* Established connection to neverssl.com (34.223.124.45 port 80) from 192.168.0.101 port 54212
* using HTTP/1.x
> GET / HTTP/1.1
> Host: neverssl.com
> User-Agent: curl/8.21.0
> Accept: */*
>
* Request completely sent off
< HTTP/1.1 200 OK
< Date: Thu, 17 Sep 2026 17:40:58 GMT
< Server: Apache/2.4.68 ()
< Upgrade: h2,h2c
< Connection: Upgrade
< Last-Modified: Wed, 29 Jun 2022 00:23:33 GMT
< ETag: "f79-5e28b29d38e93"
< Accept-Ranges: bytes
< Content-Length: 3961
< Vary: Accept-Encoding
< Content-Type: text/html; charset=UTF-8
<
<html>
        <head>
                <title>NeverSSL - Connecting ... </title>
                <style>
                body {
                        font-family: Montserrat, helvetica, arial, sans-serif;
                        font-size: 16x;
                        color: #444444;
                        margin: 0;
                }
                h2 {
                        font-weight: 700;
                        font-size: 1.6em;
                        margin-top: 30px;
                }
                p {
                        line-height: 1.6em;
                }
                .container {
                        max-width: 650px;
                        margin: 20px auto 20px auto;
                        padding-left: 15px;
                        padding-right: 15px
                }
                .header {
                        background-color: #42C0FD;
                        color: #FFFFFF;
                        padding: 10px 0 10px 0;
                        font-size: 2.2em;
                }
                .notice {
                        background-color: red;
                        color: white;
                        padding: 10px 0 10px 0;
                        font-size: 1.25em;
                        animation: flash 4s infinite;
                }
                @keyframes flash {
                0% {
                        background-color: red;
                }
                50% {
                        background-color: #AA0000;
                }
                0% {
                        background-color: red;
                }
                }
                <!-- CSS from Mark Webster https://gist.github.com/markcwebster/9bdf30655cdd5279bad13993ac87c85d -->
                </style>

                <script>
                        var adjectives = [ 'cool' , 'calm' , 'relaxed', 'soothing', 'serene', 'slow',
                                                        'beautiful', 'wonderful', 'wonderous', 'fun', 'good',
                                                        'glowing', 'inner', 'grand', 'majestic', 'astounding',
                                                        'fine', 'splendid', 'transcendent', 'sublime', 'whole',
                                                        'unique', 'old', 'young', 'fresh', 'clear', 'shiny',
                                                        'shining', 'lush', 'quiet', 'bright', 'silver' ];

                        var nouns =       [ 'day', 'dawn', 'peace', 'smile', 'love', 'zen', 'laugh',
                                                        'yawn', 'poem', 'song', 'joke', 'verse', 'kiss', 'sunrise',
                                                        'sunset', 'eclipse', 'moon', 'rainbow', 'rain', 'plan',
                                                        'play', 'chart', 'birds', 'stars', 'pathway', 'secret',
                                                        'treasure', 'melody', 'magic', 'spell', 'light', 'morning'];

                        var prefix =
                                        // Choose 3 zen adjectives
                                        adjectives.sort(function(){return 0.5-Math.random()}).slice(-3).join('')
                                        +
                                        // Coupled with a zen noun
                                        nouns.sort(function(){return 0.5-Math.random()}).slice(-1).join('');
                        window.location.href = 'http://' + prefix + '.neverssl.com/online';
                </script>
        </head>
        <body>
        <noscript>
                <div class="notice">
                        <div class="container">
                                ⚠️ JavaScript appears to be disabled. NeverSSL's cache-busting works better if you enable JavaScript for <code>neverssl.com</code>.
                        </div>
                </div>
        </noscript>
        <div class="header">
                <div class="container">
                <h1>NeverSSL</h1>
                </div>
        </div>
        <div class="content">
        <div class="container">

        <h1 id="status"></h1>
        <script>document.querySelector("#status").textContent = "Connecting ...";</script>
        <noscript>

                <h2>What?</h2>
                <p>This website is for when you try to open Facebook, Google, Amazon, etc
                on a wifi network, and nothing happens. Type "http://neverssl.com"
                into your browser's url bar, and you'll be able to log on.</p>

                <h2>How?</h2>
                <p>neverssl.com will never use SSL (also known as TLS). No
                encryption, no strong authentication, no <a
                href="https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security">HSTS</a>,
                no HTTP/2.0, just plain old unencrypted HTTP and forever stuck in the dark
                ages of internet security.</p>

                <h2>Why?</h2>
                <p>Normally, that's a bad idea. You should always use SSL and secure
                encryption when possible. In fact, it's such a bad idea that most websites
                are now using https by default.</p>

                <p>And that's great, but it also means that if you're relying on
                poorly-behaved wifi networks, it can be hard to get online.  Secure
                browsers and websites using https make it impossible for those wifi
                networks to send you to a login or payment page. Basically, those networks
                can't tap into your connection just like attackers can't. Modern browsers
                are so good that they can remember when a website supports encryption and
                even if you type in the website name, they'll use https.</p>

                <p>And if the network never redirects you to this page, well as you can
                see, you're not missing much.</p>

        <a href="https://twitter.com/neverssl">Follow @neverssl</a>

        </noscript>

        </div>
        </div>

        </body>
</html>
* Connection #0 to host neverssl.com:80 left intact
```

---

### A.3. Запит до служби доменних імен

*Windows: `Resolve-DnsName ВАШ_ДОМЕН`*

**Команда (перше виконання):**

```
dig nbuv.gov.ua
```

**Вивід:**

```
Got answer:
    HEADER:
        opcode = QUERY, id = 1, rcode = SERVFAIL
        header flags:  response, want recursion, recursion avail.
        questions = 1,  answers = 0,  authority records = 0,  additional = 0

    QUESTIONS:
        1.0.168.192.in-addr.arpa, type = PTR, class = IN

------------
Server:  UnKnown
Address:  192.168.0.1

------------
Got answer:
    HEADER:
        opcode = QUERY, id = 2, rcode = NOERROR
        header flags:  response, want recursion, recursion avail.
        questions = 1,  answers = 1,  authority records = 0,  additional = 0

    QUESTIONS:
        nbuv.gov.ua, type = A, class = IN
    ANSWERS:
    ->  nbuv.gov.ua
        internet address = 194.44.11.136
        ttl = 94 (1 min 34 secs)

------------
Non-authoritative answer:
------------
Got answer:
    HEADER:
        opcode = QUERY, id = 3, rcode = NOERROR
        header flags:  response, want recursion, recursion avail.
        questions = 1,  answers = 0,  authority records = 1,  additional = 0

    QUESTIONS:
        nbuv.gov.ua, type = AAAA, class = IN
    AUTHORITY RECORDS:
    ->  nbuv.gov.ua
        ttl = 1594 (26 mins 34 secs)
        primary name server = robin.ns.cloudflare.com
        responsible mail addr = dns.cloudflare.com
        serial  = 2414793018
        refresh = 10000 (2 hours 46 mins 40 secs)
        retry   = 2400 (40 mins)
        expire  = 604800 (7 days)
        default TTL = 1800 (30 mins)

------------
Name:    nbuv.gov.ua
Address:  194.44.11.136
```

**Команда (повторне виконання через 5–7 хвилин):**

```
dig ВАШ_ДОМЕН
```

**Вивід:**

```
Got answer:
    HEADER:
        opcode = QUERY, id = 1, rcode = SERVFAIL
        header flags:  response, want recursion, recursion avail.
        questions = 1,  answers = 0,  authority records = 0,  additional = 0

    QUESTIONS:
        1.0.168.192.in-addr.arpa, type = PTR, class = IN

------------
Server:  UnKnown
Address:  192.168.0.1

------------
Got answer:
    HEADER:
        opcode = QUERY, id = 2, rcode = NOERROR
        header flags:  response, want recursion, recursion avail.
        questions = 1,  answers = 1,  authority records = 0,  additional = 0

    QUESTIONS:
        nbuv.gov.ua, type = A, class = IN
    ANSWERS:
    ->  nbuv.gov.ua
        internet address = 194.44.11.136
        ttl = 300 (5 mins)

------------
Non-authoritative answer:
------------
Got answer:
    HEADER:
        opcode = QUERY, id = 3, rcode = NOERROR
        header flags:  response, want recursion, recursion avail.
        questions = 1,  answers = 0,  authority records = 1,  additional = 0

    QUESTIONS:
        nbuv.gov.ua, type = AAAA, class = IN
    AUTHORITY RECORDS:
    ->  nbuv.gov.ua
        ttl = 1294 (21 mins 34 secs)
        primary name server = robin.ns.cloudflare.com
        responsible mail addr = dns.cloudflare.com
        serial  = 2414793018
        refresh = 10000 (2 hours 46 mins 40 secs)
        retry   = 2400 (40 mins)
        expire  = 604800 (7 days)
        default TTL = 1800 (30 mins)

------------
Name:    nbuv.gov.ua
Address:  194.44.11.136
```

**Зафіксовані значення:**

| Параметр | Перше виконання | Повторне виконання |
|---|---|---|
| Час виконання (год:хв) |20:48 |20:55 |
| IP-адреса |194.44.11.136 |194.44.11.136 |
| Значення TTL |94 |300 |

> Якщо друге значення TTL виявилося більшим за перше — це нормально: кеш резолвера встиг оновитися. Зафіксуйте як є.

---

### A.4. Контрольний ресурс

**Команда:**

```
curl -v https://google.com
```

**Вивід:**

```
* Host google.com:443 was resolved.
* IPv6: 2a00:1450:4025:807::65, 2a00:1450:4025:807::8b, 2a00:1450:4025:807::71, 2a00:1450:4025:807::8a
* IPv4: 142.251.98.139, 142.251.98.113, 142.251.98.102, 142.251.98.100, 142.251.98.101, 142.251.98.138
*   Trying [2a00:1450:4025:807::65]:443...
*   Trying 142.251.98.139:443...
* schannel: disabled automatic use of client certificate
* ALPN: curl offers http/1.1
* ALPN: server accepted http/1.1
* Established connection to google.com (142.251.98.139 port 443) from 192.168.0.101 port 61276
* using HTTP/1.x
> GET / HTTP/1.1
> Host: google.com
> User-Agent: curl/8.21.0
> Accept: */*
>
* Request completely sent off
* schannel: remote party requests renegotiation
* schannel: renegotiating SSL/TLS connection
* schannel: SSL/TLS connection renegotiated
< HTTP/1.1 301 Moved Permanently
< Location: https://www.google.com/
< Content-Type: text/html; charset=UTF-8
< Content-Security-Policy-Report-Only: object-src 'none';base-uri 'self';script-src 'nonce-okvN-LbUMiGPGLnSRo1k6w' 'strict-dynamic' 'report-sample' 'unsafe-eval' 'unsafe-inline' https: http:;report-uri https://csp.withgoogle.com/csp/gws/other-hp
< Date: Thu, 17 Sep 2026 17:56:23 GMT
< Expires: Sat, 17 Oct 2026 17:56:23 GMT
< Cache-Control: public, max-age=2592000
< Server: gws
< Content-Length: 220
< X-XSS-Protection: 0
< X-Frame-Options: SAMEORIGIN
< Alt-Svc: h3=":443"; ma=2592000,h3-29=":443"; ma=2592000
<
<HTML><HEAD><meta http-equiv="content-type" content="text/html;charset=utf-8">
<TITLE>301 Moved</TITLE></HEAD><BODY>
<H1>301 Moved</H1>
The document has moved
<A HREF="https://www.google.com/">here</A>.
</BODY></HTML>
* Connection #0 to host google.com:443 left intact
```

---

### A.5. Ресурси з некоректною конфігурацією сертифіката

**Випадок 1**

```
curl -v https://expired.badssl.com
```

```
* Host expired.badssl.com:443 was resolved.
* IPv6: (none)
* IPv4: 104.154.89.105
*   Trying 104.154.89.105:443...
* schannel: disabled automatic use of client certificate
* ALPN: curl offers http/1.1
* schannel: next InitializeSecurityContext failed: SEC_E_CERT_EXPIRED (0x80090328) - The received certificate has expired.
* closing connection #0
curl: (35) schannel: next InitializeSecurityContext failed: SEC_E_CERT_EXPIRED (0x80090328) - The received certificate has expired.
```

**Випадок 2**

```
curl -v https://wrong.host.badssl.com
```

```
* Host wrong.host.badssl.com:443 was resolved.
* IPv6: (none)
* IPv4: 104.154.89.105
*   Trying 104.154.89.105:443...
* schannel: disabled automatic use of client certificate
* ALPN: curl offers http/1.1
* schannel: SNI or certificate check failed: SEC_E_WRONG_PRINCIPAL (0x80090322) - The target principal name is incorrect.
* closing connection #0
curl: (60) schannel: SNI or certificate check failed: SEC_E_WRONG_PRINCIPAL (0x80090322) - The target principal name is incorrect.
More details here: https://curl.se/docs/sslcerts.html

curl failed to verify the legitimacy of the server and therefore could not
establish a secure connection to it. To learn more about this situation and
how to fix it, please visit the webpage mentioned above.
```

**Випадок 3**

```
curl -v https://self-signed.badssl.com
```

```
* Host self-signed.badssl.com:443 was resolved.
* IPv6: (none)
* IPv4: 104.154.89.105
*   Trying 104.154.89.105:443...
* schannel: disabled automatic use of client certificate
* ALPN: curl offers http/1.1
* schannel: SEC_E_UNTRUSTED_ROOT (0x80090325) - The certificate chain was issued by an authority that is not trusted.
* closing connection #0
curl: (60) schannel: SEC_E_UNTRUSTED_ROOT (0x80090325) - The certificate chain was issued by an authority that is not trusted.
More details here: https://curl.se/docs/sslcerts.html

curl failed to verify the legitimacy of the server and therefore could not
establish a secure connection to it. To learn more about this situation and
how to fix it, please visit the webpage mentioned above.
```

> Якщо використано альтернативний спосіб із параметром `--resolve` — зазначити це та навести фактичну команду.

---

## Частина B. Власна модель рівнів

**Кількість виділених груп:** ___

## Частина B. Власна модель рівнів

**Кількість виділених груп:** 5

| № | Назва групи (власне формулювання) | Рядки виводу, віднесені до групи | Обґрунтування |
|---|---|---|---|
| 1 | Код вебсторінки (HTML) | `<!DOCTYPE html>`, `</html>`, `<title>...</title>` | Це фінальний вміст сторінки, який найближчий до користувача і безпосередньо відображається у вікні браузера. |
| 2 | Відповідь від сервера (Заголовки) | `< HTTP/1.1 200 OK`, `< Content-Type: text/html`, `< Server: nginx` | Службова інформація від сервера, яка повідомляє клієнту про успішність запиту, розмір та тип переданих даних. |
| 3 | Запит від клієнта (HTTP) | `> GET / HTTP/1.1`, `> Host: nbuv.gov.ua`, `> User-Agent: curl/8.21.0` | Команди прикладного рівня, які комп'ютер надсилає на сервер, щоб запросити потрібний ресурс. |
| 4 | Встановлення захищеного каналу (TLS/SSL) | `* ALPN: server accepted http/1.1`, `* schannel: renegotiating SSL/TLS connection` | Етап перевірки сертифікатів та налаштування шифрування (Schannel) для безпечної передачі даних перед самим HTTP-запитом. |
| 5 | Пошук IP-адреси та підключення (DNS/TCP) | `* Host nbuv.gov.ua:443 was resolved.`, `* IPv4: 194.44.11.136`, `* Established connection to nbuv.gov.ua (194.44.11.136 port 443)` | Найближчі до апаратури та мережі процеси: визначення IP-адреси за доменним ім'ям та фізичне встановлення транспортного з'єднання з сервером. |

**Рядки, які не вдалося віднести до жодної групи:**

| Рядок виводу | Причина утруднення |
|---|---|
| `* Connection #0 to host nbuv.gov.ua:443 left intact` | Це службове повідомлення самої утиліти curl про те, що вона не закриває з'єднання відразу. Воно відбувається після всіх обмінів і не належить до моделі взаємодії. |
| `* schannel: disabled automatic use of client certificate` | Специфічне налаштування криптографічної бібліотеки Windows на моїй машині, що не є частиною мережевого обміну з сервером. |


---

## Контрольні питання

**1. Скільки рядків діагностичного виводу передує отриманню даних сторінки (завдання A.1)?**

> 36 рядків (це всі рядки, що починаються символами `*`, `>`, `<` до початку HTML-коду сторінки).

**2. Які рядки наявні у виводі A.1 і відсутні у виводі A.2? Чим це зумовлено?**

> У виводі А.1 наявні рядки узгодження безпеки та шифрування (наприклад, `* ALPN: server accepted http/1.1`, `* schannel: renegotiating SSL/TLS connection`). У виводі А.2 вони відсутні, оскільки запит до `neverssl.com` здійснювався за незахищеним протоколом HTTP (порт 80), тоді як у завданні А.1 використовувався захищений HTTPS.

**3. Звідки у виводі з'явилося значення `443`, якщо його не було вказано в адресі?**

> Значення 443 — це стандартний мережевий порт за замовчуванням для протоколу HTTPS. Оскільки в завданні А.1 в адресі було вказано схему `https://`, утиліта curl автоматично ініціювала з'єднання саме через порт 443.

**4. Як змінилося значення TTL між двома запитами (A.3)? Що означає це число?**

> Значення TTL збільшилося з 94 до 300. Це число (Time to Live) означає час у секундах, протягом якого DNS-запис зберігається в кеші резолвера. Збільшення значення означає, що між моїми двома запитами кеш резолвера встиг оновитися, і він отримав нове значення часу життя запису від авторитетного сервера.

**5. Чим відрізняються між собою три причини помилок із завдання A.5? Сформулювати кожну однією фразою.**

| Випадок | Причина недовіри |
|---|---|
| `expired` | Термін дії сертифіката сервера вже вичерпано (він застарів). |
| `wrong.host` | Сертифікат є дійсним, але виданий для іншого доменного імені, а не для того, до якого здійснюється звернення. |
| `self-signed` | Сертифікат підписаний самим собою, а не офіційним довіреним центром сертифікації (CA), який розпізнає система. |

**6. Три рядки з власних виводів, про які не йшлося на лекції 1:**

| № | Рядок виводу | Джерело (номер завдання) |
|---|---|---|
| 1 | `* ALPN: server accepted http/1.1` | A.1 |
| 2 | `* schannel: renegotiating SSL/TLS connection` | A.1 |
| 3 | `> User-Agent: curl/8.21.0` | A.1 |

*Пояснення до цих рядків не потрібне.*

---

## Висновки

*150–300 слів. Спиратися на власні спостереження, а не на матеріал лекції.*

**D.1. Що виявилося неочевидним або несподіваним**

*Назвати конкретно, з посиланням на рядок виводу.*

> Несподіваним виявилося те, скільки прихованих процесів відбувається до отримання самої сторінки. Я думав, що підключення — це миттєва дія, але рядки `* schannel: renegotiating SSL/TLS connection` та `* ALPN: server accepted http/1.1` показують, що клієнт і сервер спочатку довго «домовляються» про шифрування. Також здивувало, що TTL у кеші DNS — це реальний таймер, який постійно оновлюється (у мене значення змінилося з 94 на 300 під час повторного запиту `nslookup`).

**D.2. Чому саме така кількість груп у частині B**

*На якій підставі ухвалено рішення. Що змусило б його змінити.*

> Я виділив 5 груп, бо вирішив розбити процес на максимально зрозумілі кроки за хронологією. Прикладну взаємодію я розділив на мій запит (рядки `>`), відповідь сервера (заголовки `<`) і сам HTML-код. Інші дві групи — це підготовка: пошук IP-адреси та налаштування безпечного з'єднання. Я б зменшив кількість груп, якби стояла задача узагальнити їх до класичної теоретичної моделі (об'єднавши всі кроки роботи з контентом в один загальний «Прикладний рівень»).

**D.3. Питання, яке залишилося без відповіді**

> Не вдалося зробити А3 через "dig", чому саме я не зрозумiв

---

## Використання штучного інтелекту

*Розділ обов'язковий. Заповнюється незалежно від того, чи використовувався ШІ. Детальні вимоги — у документі «Політика використання технологій штучного інтелекту».*

**Факт використання:** використано / не використано *(потрібне залишити)*

**Установлений рівень для цієї роботи:** Р3 — ШІ як співвиконавець

**Фактичний рівень використання:** Р___

### Використані системи

| Система | Версія або модель | Період використання |
|---|---|---|
|claude cod |Opus 5 |17.09 |

### Промпти

*Наводити дослівно, у тому вигляді, у якому запит було надано системі. Переказ не приймається.*

| № | Розділ роботи | Текст промпта |
|---|---|---|
| 1 |Частина А3 |чета я не понял дружбан, когда пишу в цмд dig nbuv.gov.ua вылетает "'dig' is not recognized as an internal or external command, operable program or batch file." |
| 2 | Частина B|что это вообще? |

### Дії з отриманим результатом

| № промпта | Що перевірено | Що змінено | Що відхилено і чому |
|---|---|---|---|
| 1 |Перевірено роботу утиліти dig у середовищі Windows. | Замінено команду dig на альтернативну nslookup -debug згідно з інструкцією до практичної. |  |
| 2 |Пояснено суть розбиття процесу на рівні в Частині В. | Адаптовано структуру та кількість груп (5 рівнів) відповідно до власних виводів утиліти curl та структури Schannel. | Відхилено копіювання чужої моделі рівнів, щоб зберегти автентичність власних даних. |


### Підтвердження

Підтверджую, що всі наведені в цьому звіті виводи команд отримано мною особисто внаслідок фактичного виконання відповідних дій, а відомості цього розділу є повними та достовірними.

> Виводи `curl`, `dig` та інші артефакти не можуть бути згенеровані. Це стосується будь-якого рівня використання ШІ.

---

## Примітки виконавця

*(необов'язковий розділ: що не спрацювало, які команди довелося змінити, які виникли труднощі)*

> Навiть в claude так i не зрозумiв у чому була помилка в А3 з dig ¯\_(ツ)_/¯
