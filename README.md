# Awesome Steam with stars

> A curated list of [packages](#packages) and [resources](#resources) regarding [Steam](http://store.steampowered.com/) development.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

The purpose of this document is to provide a quick overview over existing packages (libraries, modules etc.) and resources available regarding Steam client automation and WebAPI usage. Whenever you need to start a new project, have a look at the list of packages and see if there is anything useful for your use case. If you need technical details or tutorials, check out the resources section.

## Table of Contents

* [Packages](#packages)
  * [Node.js](#nodejs)
  * [C#](#c)
  * [PHP](#php)
  * [Go](#go)
  * [Python](#python)
  * [C++](#c-1)
  * [Java](#java)
  * [Objective-C](#objective-c)
  * [Ruby](#ruby)
  * [Rust](#rust)

* [Resources](#resources)
  * [General](#general-3)
  * [Tutorials](#tutorials)
  * [Posts](#posts)
  * [Standalone Tools](#standalone-tools)
  * [Discussion Boards](#discussion-boards)
  * [Third-Party Services](#third-party-services)

## Packages

> 💡 Many of these package repositories provide helpful READMEs and wiki pages, which explain the usage and/or provide examples. Do not forget to check them out when using particular package.

### Node.js

#### General

* [steam-user](https://github.com/DoctorMcKay/node-steam-user) ⭐ 1,117 | 🐛 64 | 🌐 JavaScript | 📅 2025-12-04 - Feature-rich easy-to-use Steam client.
* [steam](https://github.com/seishun/node-steam) ⚠️ Archived - Interface directly with Steam servers from Node.js.
* [vapor](https://github.com/scholtzm/vapor) ⭐ 111 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-11 - Lightweight Steam client framework.
* [steamworks-ffi-node](https://github.com/ArtyProf/steamworks-ffi-node) ⭐ 76 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-24 - A Node.js wrapper for Steamworks SDK.
* [steam-client](https://github.com/DoctorMcKay/node-steam-client) ⚠️ Archived - API-compatible fork of node-steam's SteamClient.
* [steam-parentbot](https://github.com/dragonbanshee/node-steam-parentbot) ⚠️ Archived - Simple base class for a Steam bot.

#### WebAPI

* [steamapi](https://github.com/lloti/node-steamapi) ⭐ 198 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-01 - A nice Steam API wrapper.
* [steam-webapi](https://github.com/DoctorMcKay/node-steam-webapi) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2017-08-18 - Complete WebAPI wrapper with support for extra HTTP headers sent by Steam.

#### Trading

* [steam-tradeoffer-manager](https://github.com/DoctorMcKay/node-steam-tradeoffer-manager) ⭐ 606 | 🐛 12 | 🌐 JavaScript | 📅 2026-03-27 - Simple and sane Steam trade offer management.
* [steam-tradeoffers](https://github.com/Alex7Kom/node-steam-tradeoffers) ⚠️ Archived - Steam Trade Offers for Node.js.
* [steam-trade](https://github.com/seishun/node-steam-trade) ⚠️ Archived - Node.js wrapper around Steam live trading.
* [steam-inventory-stream](https://github.com/timvandam/steam-inventory-stream) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2020-04-15 - Fetch inventories as readable streams.
* [steam-inventory-api-ng](https://github.com/itsjfx/node-steam-inventory-api-ng) ⭐ 5 | 🐛 2 | 🌐 JavaScript | 📅 2025-05-28 - A Steam Inventory API wrapper with advanced features such as retries and proxy support.

#### Game Interaction

* [dota2](https://github.com/RJacksonm1/node-dota2) ⚠️ Archived - Interact directly with Dota 2 game coordinator.
* [csgo](https://github.com/joshuaferrara/node-csgo) ⭐ 464 | 🐛 9 | 🌐 JavaScript | 📅 2023-09-27 - Interact directly with CS:GO game coordinator.
* [tf2](https://github.com/DoctorMcKay/node-tf2) ⭐ 63 | 🐛 13 | 🌐 JavaScript | 📅 2024-03-12 - Interact directly with TF2 game coordinator.
* [steam-gameserver](https://github.com/DoctorMcKay/node-steam-gameserver) ⭐ 20 | 🐛 4 | 🌐 JavaScript | 📅 2026-04-17 - Steam client handler for Gameserver and AnonGameserver account types.

#### Community & Store Automation

* [steamcommunity](https://github.com/DoctorMcKay/node-steamcommunity) ⭐ 579 | 🐛 47 | 🌐 JavaScript | 📅 2026-07-13 - Interact with steamcommunity.com. Also allows to confirm trade offers.
* [steamstore](https://github.com/DoctorMcKay/node-steamstore) ⭐ 69 | 🐛 4 | 🌐 JavaScript | 📅 2024-09-03 - Interact with store.steampowered.com.
* [steam-weblogon](https://github.com/Alex7Kom/node-steam-weblogon) ⚠️ Archived - Retrieve SteamCommunity cookies if you are running Steam network client.
* [steam-web-api-key](https://github.com/Alex7Kom/node-steam-web-api-key) ⚠️ Archived - Automatically registers and retrieves Steam API key.
* [steam-parental](https://github.com/Alex7Kom/node-steam-parental) ⚠️ Archived - Disable parental lock.

#### Authentication

* [passport-steam](https://github.com/liamcurry/passport-steam) ⭐ 358 | 🐛 23 | 🌐 JavaScript | 📅 2026-04-02 - Steam (OpenID) authentication strategy for Passport and Node.js.
* [steam-login](https://github.com/cpancake/steam-login) ⭐ 64 | 🐛 6 | 🌐 JavaScript | 📅 2023-06-18 - Simple Connect / Express Steam authentication library.
* [meteor-accounts-steam](https://github.com/scholtzm/meteor-accounts-steam) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2016-10-10 - Steam OpenID integration for Meteor Accounts.

#### Misc

* [steam-totp](https://github.com/DoctorMcKay/node-steam-totp) ⭐ 257 | 🐛 0 | 🌐 JavaScript | 📅 2022-03-15 - Easily generate 2FA codes used by Steam.
* [steam-chat-bot](https://github.com/Steam-Chat-Bot/node-steam-chat-bot) ⚠️ Archived - Simplified interface for a steam chat bot.
* [steamid](https://github.com/DoctorMcKay/node-steamid) ⭐ 75 | 🐛 1 | 🌐 JavaScript | 📅 2024-10-20 - SteamID usage and conversion made easy.
* [steam-resources](https://github.com/seishun/node-steam-resources) ⚠️ Archived - Steam's enums, protobufs and structs.
* [vdf](https://github.com/RJacksonm1/node-vdf) ⚠️ Archived - vdf to object and vice versa.
* [steam-crypto](https://github.com/seishun/node-steam-crypto) ⚠️ Archived - Node.js implementation of Steam crypto.
* [steam-groups](https://github.com/scholtzm/node-steam-groups) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2015-08-05 - Custom node-steam handler which provides group functions.
* [steamapis](https://github.com/itsjfx/node-steamapis) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2021-08-25 - Module to use the API of [steamapis.com](https://steamapis.com).
* [steamrep](https://github.com/scholtzm/node-steamrep) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2016-08-21 - Check user's SteamRep reputation.
* [reptf](https://github.com/scholtzm/node-reptf) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2016-08-21 - Check user's rep.tf reputation.

### C\#

#### General

* [SteamKit2](https://github.com/SteamRE/SteamKit) ⭐ 3,165 | 🐛 37 | 🌐 C# | 📅 2026-08-01 - .NET library designed to interoperate with Valve's Steam network.
* [SteamBot](https://github.com/Jessecar96/SteamBot) ⚠️ Archived - Automated bot software for interacting with steam trade.
* [SteamAuth](https://github.com/geel9/SteamAuth) ⭐ 318 | 🐛 25 | 🌐 C# | 📅 2026-04-25 - A C# library that provides vital Steam Mobile Authenticator functionality.
* [SteamTradeOffersBot](https://github.com/waylaidwanderer/SteamTradeOffersBot) ⭐ 49 | 🐛 4 | 🌐 C# | 📅 2017-08-19 - SteamBot fork which focuses on trade offers.
* [SteamStandardProject](https://github.com/ObsidianMinor/SteamStandardProject) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2018-02-21 - A collection of .NET Standard libraries using common types that provide functionality in one or more parts of Steam.

#### Misc

* [BackpackLogin](https://github.com/igeligel/BackpackLogin) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2017-04-23 - A .NET Standard library for logging into backpack.tf using Steam credentials.
* [TeamFortressOutpostApi](https://github.com/igeligel/TeamFortressOutpostApi) ⭐ 3 | 🐛 1 | 🌐 C# | 📅 2017-04-23 - A .NET Standard class library which allows user to interact with TF2Outpost.

### PHP

* [SteamAuthentication](https://github.com/SmItH197/SteamAuthentication) ⭐ 443 | 🐛 40 | 🌐 PHP | 📅 2024-01-12 - Steam OpenID authentication with PHP.
* [SteamCommunity](https://github.com/waylaidwanderer/PHP-SteamCommunity) ⭐ 80 | 🐛 25 | 🌐 PHP | 📅 2017-10-25 - A PHP library for interacting with the Steam Community website.
* [steam-api](https://github.com/DaMitchell/steam-api-php) ⚠️ Archived - A PHP wrapper for the Steam API.
* [SteamAuthOOP](https://github.com/BlackCetha/SteamAuthOOP) ⭐ 39 | 🐛 1 | 🌐 PHP | 📅 2021-01-08 - An object-oriented alternative to SteamAuthentication.
* [steam-totp](https://github.com/DoctorMcKay/php-steam-totp) ⭐ 22 | 🐛 0 | 🌐 PHP | 📅 2017-10-31 - PHP library to deal with Steam's proprietary TOTP algorithm.
* [steam-auth](https://github.com/vikas5914/steam-auth) ⭐ 19 | 🐛 2 | 🌐 PHP | 📅 2025-02-12 - An alternative Steam authentication library with Composer support.
* [steamid](https://github.com/DoctorMcKay/php-steamid) ⭐ 11 | 🐛 0 | 🌐 PHP | 📅 2021-09-10 - SteamID class for PHP.

### Go

* [go-steam](https://github.com/Philipp15b/go-steam) ⭐ 432 | 🐛 38 | 🌐 Go | 📅 2024-03-13 - Steam's protocol in Go.
* [steam](https://github.com/0xAozora/steam) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2024-12-10 - Simple steam library for trading in Go.
* [steam-mobileauth](https://github.com/YellowOrWhite/go-steam-mobileauth) ⭐ 19 | 🐛 1 | 🌐 Go | 📅 2016-01-07 - Port of SteamAuth in Go.

### Python

#### General

* [steam](https://github.com/ValvePython/steam) ⭐ 1,279 | 🐛 62 | 🌐 Python | 📅 2026-06-23 - Module for various interactions with Steam.
* [steampy](https://github.com/bukson/steampy) ⭐ 667 | 🐛 91 | 🌐 Python | 📅 2024-12-23 - Fully automated Steam trade offers library with SteamGuard support.
* [SteamAPI](https://github.com/smiley/steamapi) ⚠️ Archived - An object-oriented Python 2.7+ library for accessing the Steam Web API.
* [aiosteampy](https://github.com/somespecialone/aiosteampy) ⭐ 106 | 🐛 7 | 🌐 Python | 📅 2026-08-19 - Trade and interact with Steam market, WebAPI, SteamGuard.
* [steamodd](https://github.com/Lagg/steamodd) ⭐ 80 | 🐛 0 | 🌐 Python | 📅 2026-03-06 - Steam tools library.
* [Steam-Trade](https://github.com/Zwork101/steam-trade) ⚠️ Archived - An asynchronous, event-based trade library.

#### Game Interaction

* [dota2](https://github.com/ValvePython/dota2) ⭐ 222 | 🐛 33 | 🌐 Python | 📅 2023-03-02 - Python module for interacting with Dota 2's Game Coordinator.
* [csgo](https://github.com/ValvePython/csgo) ⭐ 131 | 🐛 16 | 🌐 Python | 📅 2021-02-03 - Python module for interacting with CSGO's Game Coordinator.

#### Misc

* [vdf](https://github.com/ValvePython/vdf) ⭐ 213 | 🐛 24 | 🌐 Python | 📅 2024-06-30 - Python module for working with Valve's KeyValue format.
* [vpk](https://github.com/ValvePython/vpk) ⭐ 187 | 🐛 9 | 🌐 Python | 📅 2023-09-20 - Python module for working with Valve's Pack format.

### C++

* [SteamPP](https://github.com/seishun/SteamPP) ⭐ 118 | 🐛 10 | 🌐 C++ | 📅 2017-03-07 - C++ library to interoperate with Steam servers.

### Java

* [JavaSteam](https://github.com/Longi94/JavaSteam) ⭐ 144 | 🐛 4 | 🌐 Kotlin | 📅 2026-07-13 - Java library that provides an interface to directly interact with Valve's Steam servers.
* [SteamKit-Java](https://github.com/Top-Cat/SteamKit-Java) ⭐ 51 | 🐛 4 | 🌐 Java | 📅 2018-07-18 - Java port of SteamKit.

### Objective-C

* [SteamAuth](https://github.com/michaelchum/SteamAuth) ⭐ 6 | 🐛 0 | 🌐 Objective-C | 📅 2015-01-05 - An iOS wrapper around Steam's OpenID login.

### Ruby

* [steam-trade](https://github.com/OmG3r/steam-trade) ⭐ 10 | 🐛 5 | 🌐 Ruby | 📅 2023-06-23 - Ruby gem for sending trade offers.

### Rust

* [steamguard-cli](https://github.com/dyc3/steamguard-cli) ⭐ 1,033 | 🐛 21 | 🌐 Rust | 📅 2026-07-29 - Command-line utility for generating Steam 2FA codes and managing Steam confirmations.

## Resources

### General

* [Steam Internal WebAPI Documentation by Revadike](https://github.com/Revadike/UnofficialSteamWebAPI) ⭐ 641 | 🐛 2 | 🌐 HTML | 📅 2022-03-26
* [Steam WebAPI @ ValveSoftware](https://developer.valvesoftware.com/wiki/Steam_Web_API)
* [Steam WebAPI @ TF2 Wiki](https://wiki.teamfortress.com/wiki/WebAPI)
* [Steam WebAPI Documentation by xPaw](https://lab.xpaw.me/steam_api_documentation.html)
* [Steam as OpenID Provider](http://steamcommunity.com/dev)
* [Steam API Key Registration](http://steamcommunity.com/dev/apikey)
* [Steam Error Codes](https://steamerrors.com/) - List of `EResult` codes with possible explanations.

### Tutorials

* [In-depth Steam Bot Guide with Node.js](https://github.com/andrewda/node-steam-guide) ⭐ 711 | 🐛 29 | 🌐 JavaScript | 📅 2024-08-05
* [Charred's node.js Guide to Steam Bots](https://github.com/charredgrass/nodejs-bot-guide) ⭐ 46 | 🐛 1 | 🌐 JavaScript | 📅 2020-08-08
* [Creating a Steam Trade Bot with Node.js](https://firepowered.org/developer/create-a-steam-trade-bot-with-nodejs-iojs-updated-for-node-steam-v1-0/)
* [Retrieving 2FA Keys from iOS Device](http://forums.backpack.tf/index.php?/topic/45995-guide-how-to-get-your-shared-secret-from-ios-device-steam-mobile/)

### Posts

* [Item IDs Explained](https://dev.doctormckay.com/topic/332-identifying-steam-items/)
* [Everything Related to Escrow](https://www.reddit.com/r/SteamBot/comments/3udhkd/everything_related_to_escrow/)
* [Understanding Avatar Hash](https://www.reddit.com/r/SteamBot/comments/3cv6k7/problem_downloading_an_avatar_using/)

### Standalone Tools

* [SteamDesktopAuthenticator](https://github.com/Jessecar96/SteamDesktopAuthenticator) ⭐ 3,811 | 🐛 317 | 🌐 C# | 📅 2024-10-20 - Desktop implementation of Steam's mobile authenticator app.
* [NetHook2](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHook2) ⭐ 3,165 | 🐛 37 | 🌐 C# | 📅 2026-08-01 - Intercept Steam client's network messages.
* [NetHook2 Analyzer](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHookAnalyzer2) ⭐ 3,165 | 🐛 37 | 🌐 C# | 📅 2026-08-01 - Inspect messages dumped by NetHook2.
* [steam-desktop-authenticator-multiplatform](https://github.com/tre3p/steam-desktop-authenticator-multiplatform) ⭐ 9 | 🐛 7 | 🌐 Kotlin | 📅 2024-07-20 - Steam desktop authenticator.
* [protonenv](https://github.com/rizkiarm/protonenv) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2021-05-07 - Simple Proton version and prefix management.
* [steam-auth-web-util](http://scholtzm.github.io/steam-auth-web-util/) - Generate 2FA codes directly in your web browser.

### Discussion Boards

* [node-steam-forum](https://github.com/steam-forward/node-steam-forum) ⭐ 43 | 🐛 4 | 📅 2017-11-06
* [/r/SteamBot](https://www.reddit.com/r/SteamBot)
* [/r/SteamBot Discord](https://discord.gg/0i5X3oDHJbDUsiGC)
* [/r/nodesteam](https://www.reddit.com/r/nodesteam)
* [DoctorMcKay's Dev Forum](https://dev.doctormckay.com/)

### Third-Party Services

Websites listed below may provide free and/or paid services and are listed alphabetically according to their domain name.

* [backpack.tf](https://backpack.tf/developer) - Provides TF2 prices and Steam market/inventory related services.
* [steamanalyst.com](https://steamanalyst.com/) - Provides CS:GO prices.
* [hexa.one](https://hexa.one/) - Provides prices for several games and Steam market/inventory related services.
* [steamapis.com](https://steamapis.com/) - Provides prices for several games and Steam market/inventory related services.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author and contributors of this text have waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
