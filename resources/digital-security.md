# Introductory Topics

Every risk profile includes different tollerances. This guide was originally made as intentionally rigid guidance to those entering sensitive conversations. Many in broad spaces do not follow nearly any of this and are just fine; some have neglected some of these and it has become an issue for those involved. The risk you bear may not entail everything here, but it remains a reference. 

Keep in mind that the safest electronic device is one used offline permanently deep in a cave outside signal range. Strong security is, at all times, a ballancing act with other priorities.

## How to SEC

Check out the official [**50501 OPSEC & INFOSEC**](https://publish.obsidian.md/revolution-starter-pack/PDFs/50501+How+to+INFOSEC+%26+OPSEC+Handbook+v1.6.3-1.pdf) overview with links to more resources. The [Revolution Starter Pack](https://publish.obsidian.md/revolution-starter-pack/Start!) also as a wealth of additional links, resources, and its own privacy guide.

## How to Signal

Key privacy and setup [guidance found here](https://ssd.eff.org/module/how-to-use-signal)!

I've also clarified some important takeaways on [Signal Usage and Digital Hygiene](https://markdownpastebin.com/?id=01b6cde3863a46068fcf00c86ba72603) from recent headline events. Please note that **Signal remains secure and uncompromised** as of 05/07/2026.

## On Surveillance

The ACLU has a [quick breakdown](https://www.acludc.org/en/how-defend-against-police-surveillance-protests), with some oft missed details.

[DeFlock](https://deflock.me/map#map=10/32.274281/-110.942699) is an awesome project tracking ALPR (License Plate Tracking) camera locations. 

Regarding smartphones, I would add that airplane mode or turning off your phone is (probably) not enough (unless you are running GrapheneOS on a Pixel 5 or later). The easy answers are to leave it at home or use a [Faraday bag](https://godarkbags.com/products/godark-faraday-bags-phone-small-bundle) anywhere remotely near a location of concern. The advanced answer is [gently verbose](https://markdownpastebin.com/?id=a4d0f82f1d46453dab0ef0b165d74965).

# Intermediate Topics

## On Cloud

Cloud storage on *both Apple and Android* are insecure and a potential liability for you device security itself. I could [rant](https://markdownpastebin.com/?id=7dbbf8a98baa48259f5c5bb1defd9edb) all day on this, but suffice it to say an offline backup method is ideal, when stored securely.

## On Device Security and Permissions

For *iPhone*, refer to [this permissions guide](https://www.theverge.com/24087604/iphone-app-permissions-how-to) and regularly pruning anything you don’t explicitly need—**especially** access to location, contacts, and motion. 

For *Android*, refer to [this guide](https://www.howtogeek.com/android-permissions-explained-which-ones-you-shouldnt-ignore/) and deny anything that doesn’t make sense. “Draw over other apps” and “Device Administrator” are highly suspect and massive asks from almost any app.

Play Protect does an *alright* job for Android. Most third party "security scanners" and mobile antivirus just collect more of your data with their access, while adding nothing to what’s already built in. As an exception, I might recommend [Hypatia](https://f-droid.org/packages/us.spotco.malwarescanner/). Avoid "cleaners," "boosters," flashlight apps, or anything else duplicating functionality already existing within the OS. 

**Exercise extreme [caution](https://markdownpastebin.com/?id=da3c29af910840e1a03038d91730a2c0)** installing APKs from other sources. Rooting/jailbreaking [is dumb and you shouldn't do it](https://markdownpastebin.com/?id=c251d5c8f7424148970e936c7ab28690).

## On Browsing

[Trackers](https://avoidthehack.com/what-are-trackers) have gotten pretty bad and are [getting worse](https://ico.org.uk/about-the-ico/media-centre/news-and-blogs/2024/12/our-response-to-google-s-policy-change-on-fingerprinting/). Mitigation involves browsers, extensions, and VPN. These industries are rife with exploitation and controversy. 

VPNs [**always** log traffic](https://cyberinsider.com/vpn-logs/) and global scope extensions have access to every site you visit by function. They're an invaluable tool demanding a high level of trust. The VPN I trust most is [Proton](https://protonvpn.com/).

For general use, I'm on [**Firefox**](https://www.mozilla.org/en-US/firefox/), which features extensions on mobile. [**uBlock Origin**](https://addons.mozilla.org/addon/ublock-origin/) blocks malware domains, trackers of various types, intrusive page elements, and more. It does this by downloading rule lists to match on sites locally. [**Decentraleyes**](https://decentraleyes.org/) protects against [content delivery tracking](https://git.synz.io/Synzvato/decentraleyes/-/wikis/Simple-Introduction). [**Privacy Badger**](https://privacybadger.org/) protects against more advanced and emerging tracking techniques.

There are a number of valid reasons one might need a Chromium-based browser (what Google Chrome is based on). For those I use [**Vivaldi**](https://vivaldi.com/). 

[**DuckDuckGo**](https://duckduckgo.com) is simply awesome (as a search engine and a [lite browser](https://duckduckgo.com/app)).  

[**Tor Browser**](https://www.torproject.org/download/) is more than just [TOR](https://cybernews.com/privacy/what-is-tor-and-how-does-it-work/) plus [NoScript](https://noscript.net/): it's been built and rebuilt to mitigate exploitable features common to every other browser. To oversimplify, I use it when I feel like using extra protection or to access [onion](https://community.torproject.org/onion-services/overview/) services. 

I don't, personally, like *Brave Browser*. It's not so much privacy oriented as hijacking the existing ad market with their own crypto direction. It does bundle a crypto wallet and VPN, along with way more than I would prefer... why not just get those as needed with more choice 🤷. Their [pattern of controversy](https://en.wikipedia.org/wiki/Brave_(web_browser) is enough to default me to perfectly reasonable alternatives. 

I don't recommend using any other browsers, unless you know exactly why they fit a particular situation. 

## On OSK

Your smartphone's **O**n-**S**creen **K**eyboard

Last I personally checked, the stock *iPhone* OSK keeps a limited keylog, but this is sandboxed (kept separate from anything else),  ̶[A̶p̶p̶l̶e̶ * ̶d̶o̶e̶s̶*  ̶p̶r̶i̶o̶r̶i̶t̶i̶z̶e priv̶a̶c̶y̶,̶ ̶a̶n̶d̶ ̶i̶t̶'̶s̶ ̶b̶e̶t̶ter th̶an a̶ny̶t̶h̶i̶n̶g̶ ̶e̶l̶s̶e̶ ̶o̶u̶t ther̶e̶,̶ ̶in ̶t̶ha̶t̶ ̶s̶e̶n̶s̶e̶. ](https://proton.me/blog/iphone-privacy)

*Android*-based keyboards, on the other hand, are an outright nightmare, tracking the 💩 out of you and often sidesteping all manner of privacy precautions. I'd recommend [Futo](https://keyboard.futo.org/) and disabling every other thing you can outside it.

## Closing note

I have no time to upkeep this document, but the ultimate solution to device security is to use hardware capable of supporting a hardened system, namely GrapheneOS on a recent Pixel device (Pixel 7a or later). There are many [reasons](https://grapheneos.org/faq) for this and I recommend reading and understanding their [FAQ](https://grapheneos.org/faq), not just for understanding Graphene, but to understand the general landscape. 