# better-cromite

My recommendations for the ultimate configuration of the [Cromite](https://github.com/uazo/cromite) Browser :)

**NOTE:** This project can be found on both [Codeberg](https://codeberg.org/Magnesium1062/better-cromite), which will act as the main & preferred way to contribute, and [GitHub](https://github.com/Retold3202/better-cromite).

# Search engine

Edit search engines -> **Search engines** -> Remove any search engines here you don't use (i.e. Google & Bing)

Edit search engines -> Site search -> **History** -> 3 dots -> `Deactivate`

**Search engine** -> `DuckDuckGo` ✅

# Password Manager

**Enable native Android autofill** -> ❌

**Enable native Android autofill in incognito** -> ❌

**Save passwords** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

**Auto Sign-in** -> ❌

# Payment methods

**Save and fill payment methods** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

**Manually verify every time you pay using autofill** -> ✅

# Addresses and more

**Save and fill addresses** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

# Privacy and security

Privacy -> Delete browsing data -> **At Startup**:

* `Browsing history` -> ✅

* `Cached images and files` -> ✅

* `Saved passwords` -> ✅ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

* `Autofill form data` -> ✅ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

<br>

Privacy -> **Third-party cookies** -> `Block third-party cookies` ✅

Privacy -> **Global Privacy Control "Sec-GPC"** -> `On` ✅

Security -> **Always use secure connections** -> ✅

Security -> **Use secure DNS** -> ✅

Security -> Use secure DNS -> Choose another provider -> **Custom** -> Pick a private, secure, & reputable DNS provider of your choice, I would recommend setting up your own [NextDNS](https://nextdns.io) configuration if you are able to (See my recommendations for NextDNS [here](https://codeberg.org/Magnesium1062/nextdns-settings), otherwise I would recommend [Quad9](https://quad9.net/): `https://dns.quad9.net/dns-query` *(Even if you have a private/secure DNS provider set on your OS/network level, make sure to still set it here too like this, so that you can take advantage of [Encrypted Client Hello](https://blog.cloudflare.com/announcing-encrypted-client-hello))*

Security -> Always incognito mode -> **Enable history** -> ❌

Security -> **Close all open tabs on exit** -> ❌

Security -> **HTTP Referer header policy** -> `Disable if cross-origin and user begins navigation` ✅

Other services -> **Improve search suggestions** -> ❌

Other services -> **Expire history days threshold** -> `No history`

Other services -> **Access payment methods** -> ❌

# Adblock Plus settings

**Enable Adblock Plus** -> ✅

Filter lists:

* `EasyList` -> ✅

* `Fanboy's Notifications Blocking List` -> ✅

* `EasyPrivacy` -> ✅

* `Fanboy's Social Blocking List` -> ✅

<br>

**Enable anti-circumvention and snippets** -> ✅

Don't forget to select **Check for updates now** when you're done here.

# Legacy Adblock Settings

**Ad Blocking** -> `Autoupdate disabled` ❌

Ad Blocking -> **Filters URL** -> Make sure the box is blank, then select `Save`

# Notifications

General -> **All "General Notifications** -> ✅

General -> **Browser** -> ❌

General -> **Completed downloads** -> ✅

General -> **Active downloads** -> ✅

General -> **Incognito** -> ✅

General -> **Playing media** -> ✅

# Homepage

**Show NTP at startup** -> ❌

# User Agent

**Mobile User Agent** -> `Use standard user agent`

**Desktop Mode User Agent** -> `Use standard user agent`

Desktop Mode User Agent -> **Enable processing of the viewport meta tag also for desktop mode** -> ❌

# User Scripts

**Activate User Scripts** -> ❌ *(User scripts are highly fingerprintable, avoid using them unless absolutely necessary)*

# Toolbar shortcut

**Toolbar shortcut** -> `New tab` ✅

# Accessibility and UI

**Enable Accessibility Service** -> ❌ *(Unless needed)*

**Force enable zoom** -> ✅

**Simplified view for web pages** -> ✅

# Site settings

Permissions -> **Location** -> `Blocked` ❌ 

Permissions -> **Camera** -> `Blocked` ❌ *(Obviously don't set if you use sites that need camera access, but you can still set exceptions for sites if needed*)

Permissions -> **Microphone** -> `Blocked` ❌ *(Obviously don't set if you use sites that need microphone access, but you can still set exceptions for sites if needed*)

Permissions -> **Notifications** -> `Blocked` ❌

Permissions -> **Embedded content** -> `Blocked` ❌

Permissions -> **Motion sensors** -> `Blocked` ❌

Permissions -> **NFC devices** -> `Blocked` ❌

Permissions -> **USB** -> `Blocked` ❌

Permissions -> **Clipboard** -> `Blocked from reading clipboard` ❌

Permissions -> **Virtual reality** -> `Blocked` ❌

Permissions -> **Augmented reality** -> `Blocked` ❌

Permissions -> **Your device use** -> `Blocked` ❌

Content -> **JavaScript** -> `Blocked` ❌ *(This **will** cause breakage, but it heavily improves privacy & security, so I'd recommend blocking it if possible and if you're willing to re-enable JavaScript on sites that need it)*

Content -> **Pop-ups and redirects** -> `Block all popups` ✅

Content -> **Intrusive ads** -> `Blocked on some sites` ❌

Content -> **Protected content** -> `Blocked` ❌ - https://www.eff.org/deeplinks/2017/10/drms-dead-canary-how-we-just-lost-web-what-we-learned-it-and-what-we-need-do-next

Content -> **Dark theme for sites** -> `On` ✅ *(See `chrome://flags` below)*

Content -> **Background sync** -> `Blocked` ❌

Content -> **Autoplay** -> `Autoplay disabled` ❌

Content -> **Access to Private Network** -> `Block access to private network` ❌

Content -> **JavaScript JIT** -> `Block JIT and WebAssembly` ❌ *(May cause breakage with certain advanced web games or anything else that requires advanced graphics, but allows easily re-enabling per-site when needed)*

Content -> **Timezone override** -> `Random (for each page)` ✅ *(Helps against fingerprinting, if this isn't usable for you, you can set this to `System timezone`)*

Content -> **Viewport Size Protection** -> `Enabled` ✅

Content -> **Webgl** -> `Disabled` ❌ *(May cause breakage with certain advanced web games or anything else that requires advanced graphics, but allows easily re-enabling per-site when needed)*

Content -> **WebRTC** -> `Disabled` ❌ *(Will cause breakage with calling through services like Discord & Zoom, but allows easily re-enabling per-site when needed)*

# Downloads

**Ask where to save files** -> ✅

**Automatically open PDFs** -> ❌

# About Cromite

**Allow checking for updates** -> ✅ *(Should be default)*

# chrome://flags

Available:

* `#android-open-pdf-inline` -> `Enabled`

* `#max-connections-per-host` -> `15`

<br>

Cromite:

* `#cleartext-permitted` -> `Disabled`

* `#enable-show-ntp-at-startup` -> `Disabled`

* `#share-intent-ui` -> `Disabled`

* `#viewport-protection` -> `Enabled`

# Additional recommendations

* Use a (reputable) VPN. I would recommend either [Mullvad](https://mullvad.net/) or [ProtonVPN](https://protonvpn.com/).

* Use a (reputable) anti-virus if possible, such as [Hypatia](https://f-droid.org/packages/us.spotco.malwarescanner/). **NOTE:** You should install Hypatia through the [DivestOS Official Repo](https://divestos.org/fdroid/official/?fingerprint=E4BE8D6ABFA4D9D4FEEF03CDDA7FF62A73FD64B75566F6DD4E5E577550BE8467) instead of F-Droid's main repo, as it will allow you to receive quicker updates directly from the developer. It's also recommended to use [F-Droid Basic](https://f-droid.org/en/packages/org.fdroid.basic/) as your F-Droid client of choice.