<p align="center"><img src="http://i.imgur.com/fnVhC6S.png" alt="BetterFirefox Mascott" /></p>

Project on hold!
![Icon](https://raw.github.com/Fody/Obsolete/master/Icons/package_icon.png)


# BetterFirefox

The goal of this project is to create a community based wish list (which can also be used as a communication platform) to get Mozilla Firefox again on the right course. Mozilla can use this to ***improve their own product***; it is up to them to work with us or not.

[![Build Status](https://travis-ci.org/CHEF-KOCH/BetterFireFox.svg?branch=master)](https://travis-ci.org/BetterFireFox)
[![Gitter](https://badges.gitter.im/CHEF-KOCH/BetterFireFox.svg)](https://gitter.im/CHEF-KOCH/BetterFireFox?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)


## Contents

- Overview, contributions, license and goal (this page)
    - [Gh-GitHub page and project overview](https://chef-koch.github.io/BetterFirefox)
- [Why you should use Firefox?](Why Firefox.md)
    - Short explanation for beginners on why you should give Firefox a try


## What is wrong with Firefox?

* Why use Firefox over Chrome, we not want another fork of it! Mozilla would probably argue that Firefox is unique because it’s made by a non-profit company dedicated to making the web better, rather than big for-profit corporations with their own agendas. It also uses Gecko, a different rendering engine, which hopefully helps preserve web standards through a variety of implementations. But is that really enough?
* ~~Multi-Process + Sandboxed Firefox still unfinished and buggy (previously promised to be included in FF 46, but not done because of 'bugs' -- how many years more do we need to wait?).~~ **since Firefox 49**
* Firefox needs a distinct identity.
* Don't kill the engine or the theming ability.
* WebExtensions will replace Firefox’s powerful extension framework; why not add a workaround for both?
* The default search-engine is horrible and (if Google) is actually based on a competitor, also a web browser maker [ [that actually pays for its inclusion](https://duckduckgo.com/?q=mozilla+search+engine+money) ] (Why not DuckDuckGo?)
* [Give us back the control](https://www.eff.org/deeplinks/2016/04/save-firefox) over the browser and keep it clean and slim as much as possible (also less RAM usage then).
* Give us a setup which allow us to opt-in only the stuff we want and not pre-install anything (like the 'Hello' and 'Pockets' clients).
* Bloat like Pocket has been added. To our knowledge, this is a third-party extension that has been added and uses non-Mozilla servers to store data. Things like this should be left as extensions.
* ~~Exclude any DRM (Codecs, Encrypted Media Extensions, etc.), or make it integrated opt-in for people which really need it; ESR is the wrong way, make ONE Browser for all.~~ **since Firefox 47**
* Google's 'safe-browsing' mechanism is by default enabled, let the user decide to use it or not, each visited page otherwise will be sent back to Google, [some user not want to support this](https://en.wikipedia.org/wiki/Firefox#Criticism). 
* Google's 'safe-browsing' mechanism creates cookies on everyone's system.  Mozilla claims these cookies are separate, but the UI makes no indication of this.
* No ability to sync all about:config tweaks (you need extra opt-in for that).
* Ability to reset about:config related changes on per-app/extension basis.
* [Increase the security](https://it.slashdot.org/story/16/02/12/034206/pwn2own-2016-wont-attack-firefox-because-its-too-easy) and adapt faster changes, especially to known reported issue like certificate frauds.
* Fix [known vulnerabilities](https://www.mozilla.org/en-US/security/known-vulnerabilities/) much faster (asap [if possible]). Or have [sponsorship programs](https://blog.mozilla.org/blog/2016/06/09/help-make-open-source-secure/) so that others find/fix them.
* Let [Flash](https://blog.mozilla.org/futurereleases/2016/07/20/reducing-adobe-flash-usage-in-firefox/)/Silverlight/Java go away once and for all... no need to add workarounds... it's waste of time to think that you can 'by-design' harden these things.
* NoScript / uMatrix or uBlock's function could be adopted (or ask/work directly with the developers) to implement it directly since all of the extensions are today 'a must'. Tor Browser showed how it could look, with security sliders and options for 'advanced users'.
* Firefox now stores site data in a `storage` folder in the profile, yet has no way for the user to delete this data.  Never store data across sessions without having functionality for the user to delete this data.
* Unlike competing browsers, the [64-bit version of Firefox uses *massively* more RAM than the 32-bit version](http://www.ghacks.net/2016/01/03/32-bit-vs-64-bit-browsers-which-version-has-the-edge/).  Fix this.
* Full support for DirectX 11/12/Vulkan on Windows to take advantage of graphics acceleration.
* Full support for HTTP/2.
* Support for MSE/DASH video streaming and more advanced handling of media files.
* Bring back XUL/XBL as our main UI and interface language and find a workaround so that extensions with binary (XPCOM) components can co-exist with WebExtensions.
* 'Full sync' not only partial. Some addons/configs create own entries and they not getting synced as long you not explictiy opt-in + FF should get an option to backup/restore the default prefs based on browser version. 


## What is currently good?

* Security tests such as [seperated and isolated online identities](http://www.techtimes.com/articles/165830/20160618/mozilla-tests-firefox-containers-for-separate-online-identities.htm).
* That we [not need Google anymore](http://www.cnet.com/news/firefox-maker-mozilla-we-dont-need-googles-money-anymore/)
* The theming/customization ability 
* Entire tweaking stuff (aka about:config) 
* The [current extensions interface](http://www.ghacks.net/2016/06/09/why-firefox-will-continue-to-lose-market-share/)
* The Tab-System is pretty good, especially for beginners easy to use
* Generally fast web page downloads (compared to other Browsers)
* Private browsing allows user to surf the internet without recording history or cookies (partial)
* Security, several mechanism are added (but still not as good as it could be)
* It's a developer friendly platform (Jetpack/SDK extensions) around the Browser, Extensions and eMail-program
* Integrated 'Reader Mode' for .pdf files
* Password management and the ability to sync (you also can set-up your own sync sever)
* Mostly all standards are supported, such as JavaScript, HTML (HTML5), MathML, PNG, SVG, XHTML, and XML,...
* Still Supports Microsoft Windows XP and theoretically even older systems (backward compatibility) while Chrome not supports it
* [An official roadmap](https://wiki.mozilla.org/Firefox/Roadmap) is avaible, whish shows upcoming changes. 


## Contributions

If you have anything to fix or details to add, first [file an issue](https://github.com/CHEF-KOCH/BetterFireFox/issues) on GitHub to see if it is likely to be accepted, then file a pull request with your change (one Pull Request per issue).

This is not intended to be an open wiki (more overview page), 'we' (the community) want to keep it concise and minimal, but will accept fixes and suitable additions.

See our [contributing policy](CONTRIBUTING.md).


## License

Unless otherwise specified, everything in this repository is covered by the following license:

[![Creative Commons Attribution-ShareAlike 4.0 International](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This project not is an official Mozilla page nor does it have relationship with it.  It is designed for and by the community.
