# BetterFirefox

The goal of this project is to create a community based wish-list (which can also be used as a communication platform) to get Firefox again on the right course. Mozilla could use this to ***improve the product***; it is up to them to work with us or not.

[![Build Status](https://travis-ci.org/CHEF-KOCH/BetterFireFox.svg?branch=master)](https://travis-ci.org/BetterFireFox)
[![Gitter](https://badges.gitter.im/CHEF-KOCH/BetterFireFox.svg)](https://gitter.im/CHEF-KOCH/BetterFireFox?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)


## Contents

- Overview and goal (this page)
    - Gh-Github page and overview
- [Why you should use Firefox?](Why Firefox.md)
    - Short explanation for beginners why you should give Firefox a try
- Wish-list (todo)
    - User based wish-list of how Firefox should improve


## What is wrong with Firefox?

* Firefox is about to become an almost complete copy of Chrome (we not need another fork!)
* Why use Firefox over Chrome? Mozilla would probably argue that Firefox is unique because it’s made by a non-profit company dedicated to making the web better, rather than big for-profit corporations with their own agendas. It also uses Gecko, a different rendering engine, which hopefully helps preserve web standards through a variety of implementations. But is that really enough?
* Multi-Process + Sandboxed Firefox still unfinished and buggy (previously promised to be included in FF 46, but not done because of 'bugs' -- how many years more do we need to wait?)
* Firefox needs a distinct identity
* Don't kill the engine or the theming ability it's fine how it is
* WebExtensions will replace Firefox’s powerful extension framework (why not add a workaround for both?)
* The default search-engine is horrible and (if Google) is actually based on a competitor, also a web browser maker [ [that actually pays for its inclusion](https://duckduckgo.com/?q=mozilla+search+engine+money) ] (Why not DuckDuckGo?)
* Give us back the control over the browser and keep it clean and slim as much as possible (also less RAM usage then)
* Give us a setup which allow us to opt-in only the stuff we want and not pre-install anything (like the 'Hello' and 'Pockets' clients)
* Bloat like Pocket has been added. To our knowledge, this is a third-party extension that has been added and uses non-Mozilla servers to store data. Things like this should be left as extensions.
* Exclude any DRM (Codecs, Encrypted Media Extensions, etc.), or make it integrated opt-in for people which really need it; ESR is the wrong way, make ONE Browser for all
* Google's 'safebrowsing' mechanism is by default enabled, let the user decide to use it or not, each visited page otherwise will be sent back to Google, [some user not want to support this](https://en.wikipedia.org/wiki/Firefox#Criticism). 
* Google's 'safebrowsing' mechanism creates cookies on everyone's system.  Mozilla claims these cookies are separate, but the UI makes no indication of this.
* No ability to sync all about:config tweaks (you need extra opt-in for that)
* Ability to reset about:config related changes on per-app/extension basis 
* Increase the security and adapt faster changes, especially to known reported issue like certificate frauds
* Kill [known insecure](https://www.mozilla.org/en-US/security/known-vulnerabilities/) stuff a lot of faster, let Adobe/Java die once and for all ... no need to add workarounds ... it's waste of time to think that you can 'by-design' harden insecure things.
* NoScript / uMatrix or uBlock's function could be adopted (or ask/work directly with the developers) to implement it directly since all of the extensions are today 'a must'. Tor Browser showed how it could look, with security sliders and options for 'advanced users'.
* Firefox now stores site data in a `storage` folder in the profile, yet has no way for the user to delete this data.  Never store data across sessions without having functionality for the user to delete this data.
* Unlike competing browsers, the [64-bit version of Firefox uses *massively* more RAM than the 32-bit version](http://www.ghacks.net/2016/01/03/32-bit-vs-64-bit-browsers-which-version-has-the-edge/).  Fix this.
* Running multiple instances of plugin apps heavily slows down web page downloading


What is good?

* That we [not need Google anymore](http://www.cnet.com/news/firefox-maker-mozilla-we-dont-need-googles-money-anymore/)
* The theming/customization ability 
* Entire tweak stuff (aka about:config) 
* Extensions interface
* The Tab-System is pretty good, especially for beginners
* Generally fast web page downloads (compared to other Browsers)
* Private browsing allows user to surf the internet without recording history or cookies (partial)
* Security, several mechanism are added (but still not as good as it could be)
* Developer friendly platform
* Integrated 'Reader Mode' for .pdf files
* Password management and the ability to sync (you also can set-up your own sync sever)
* Mostly all standards are supported, such as JavaScript, HTML (HTML5), MathML, PNG, SVG, XHTML, and XML,...



## Contributions

If you have anything to fix or details to add, first [file an issue](https://github.com/CHEF-KOCH/BetterFireFox/issues) on GitHub to see if it is likely to be accepted, then file a pull request with your change (one PR per issue).

This is not intended to be an open wiki (more overview page), 'we' (the community) want to keep it concise and minimal but will accept fixes and suitable additions.

See our [contributing policy](CONTRIBUTING.md).


## License

Unless otherwise specified, everything in this repository is covered by the following license:

[![Creative Commons Attribution-ShareAlike 4.0 International](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This project not is an official Mozilla page nor stand into any relationship of it.  It is designed for and with the community.
