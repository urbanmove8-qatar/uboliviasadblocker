[![Badge Commits]][Commit Rate]
[![Badge Issues]][Issues]
[![Badge Localization]][Crowdin]
![Badge License]
![Badge NPM]

***

<h1 align="center">
<sub>
<img src="https://urbanmove8.neocities.org/emojis/shield.png" height="38" width="38">
</sub>
Urbanmove Olivia’s Adblocker
</h1>

> **A custom fork of uBlock Origin (uBO), modified for P2PBrowser and Urbanmove projects.  
> This is *not* an official uBlock Origin release.  
> Original project by Raymond Hill (gorhill).**

***

Urbanmove Olivia’s Adblocker is a CPU- and memory-efficient wide-spectrum content blocker based on the original uBlock Origin project.  
It blocks ads, trackers, popups, coin miners, malware sites, and anti-blockers using the same trusted filter lists:

* EasyList
* EasyPrivacy
* Peter Lowe's Blocklist
* Online Malicious URL Blocklist
* uBlock Origin filter lists

You may unselect any lists or add custom Urbanmove-specific filters for P2PBrowser.

This project follows the **GPLv3 license**, identical to the original upstream.

***

* [Documentation](#documentation)
* [Installation](#installation)
* [Release History](#release-history)
* [Translations](#translations)
* [About](#about)

## Documentation

| Basic Mode | Advanced Mode |
| :---: | :---: |
| The <a href="https://github.com/gorhill/uBlock/wiki/Quick-guide:-popup-user-interface">simple popup user interface</a>, optimized for default usage. | The <a href="https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-quick-guide">advanced popup interface</a> with dynamic filtering and a point-and-click firewall. |
| <a href="https://github.com/gorhill/uBlock/wiki/Quick-guide:-popup-user-interface"><img src="https://user-images.githubusercontent.com/585534/232531044-c4ac4dd5-0b60-4c1e-aabb-914be04b846c.png"/></a> | <a href="https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-quick-guide"><img src="https://user-images.githubusercontent.com/585534/232531439-a8f81cc3-6622-45c4-8b32-7348cecf6e98.png"/></a> |

Visit the original uBO documentation on the [Wiki][Wiki].

For support with the original project, see [/r/uBlockOrigin][Reddit].

## Installation

Urbanmove Olivia’s Adblocker is intended primarily for **manual installation** in:

* P2PBrowser
* Chromium-based browsers (development mode)
* Firefox (temporary load)

[Manual Installation][Manual Installation]

## Release History

Releases follow upstream until modified:
* See [uBlock Origin Releases][Releases] for reference
* Local build changes appear under this fork’s Releases page

## Translations

Translation support inherited from uBlock Origin via [Crowdin][Crowdin].

## About

Original project by Raymond Hill (gorhill).
Urbanmove modifications and branding by the Urbanmove development team.

[Manifesto][Manifesto]
[Privacy Policy][Privacy Policy]
[GPLv3 License][License]

Free. Open-source. Licensed under **GPLv3**.

If you wish to contribute, consider supporting the maintainers of the filter lists.

---

[Peter Lowe's Blocklist]: https://pgl.yoyo.org/adservers/
[Malicious Blocklist]: https://gitlab.com/malware-filter/urlhaus-filter#malicious-url-blocklist
[Performance]: https://www.debugbear.com/blog/chrome-extensions-website-performance#the-impact-of-ad-blocking-on-website-performance
[EasyPrivacy]: https://easylist.to/#easyprivacy
[EasyList]: https://easylist.to/#easylist
[Crowdin]: https://crowdin.com/project/ublock
[Reddit]: https://www.reddit.com/r/uBlockOrigin/
[Theft]: https://x.com/LeaVerou/status/518154828166725632

[Manual Installation]: https://github.com/gorhill/uBlock/tree/master/dist#install
[Extended Syntax]: https://github.com/gorhill/uBlock/wiki/Static-filter-syntax#extended-syntax
[Privacy Policy]: https://github.com/gorhill/uBlock/wiki/Privacy-policy
[uBO Filters]: https://github.com/uBlockOrigin/uAssets/tree/master/filters
[Permissions]: https://github.com/gorhill/uBlock/wiki/Permissions
[Commit Rate]: https://github.com/gorhill/uBlock/commits/master
[Deployment]: https://github.com/gorhill/uBlock/wiki/Deploying-uBlock-Origin
[Blocking]: https://github.com/gorhill/uBlock/wiki/Blocking-mode
[Releases]: https://github.com/gorhill/uBlock/releases
[Issues]: https://github.com/uBlockOrigin/uBlock-issues/issues
[Wiki]: https://github.com/gorhill/uBlock/wiki
**[Manifesto]: https://github.com/gorhill/uBlock/wiki/Manifesto-3-vs-uBlock-Origin**

[Badge Localization]: https://d322cqt584bo4o.cloudfront.net/ublock/localized.svg
[Badge Commits]: https://img.shields.io/github/commit-activity/m/gorhill/ublock?label=Commits
[Badge License]: https://img.shields.io/badge/License-GPLv3-blue.svg
[Badge Issues]: https://img.shields.io/github/issues/uBlockOrigin/uBlock-issues
[Badge NPM]: https://img.shields.io/npm/v/@gorhill/ubo-core
**[NPM]: https://www.npmjs.com/package/@gorhill/ubo-core**
