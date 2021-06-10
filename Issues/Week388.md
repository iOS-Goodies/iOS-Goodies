Happy Thursday! We're in the WWDC week, and there's so much excitement and so much information everywhere that it can easily be overwhelming. I'll just start by saying that even though some people are already experimenting with the new technology, if you didn't have the chance, that's totally ok. 99% of the iOS developers out there haven't either (me being one of them). 

But let's go briefly through what was annouced this week. The Keynote mostly focused on the user-facing features, and with no big updates (like last year's Widgets and App Clips), I almost dare say it's not even that relevant for developers. Well, most iOS developers are, I guess, also iOS users, so of course you're interested in the Keynote too 😄. But if you want to know how this WWDC will affect your work, [Platforms State of the Union](https://developer.apple.com/wwdc21/102) is the one to watch. 

Xcode 13 got a few updates, better code completion, faster builds, Vim mode, better integration with the git services so pull request comments are visible in directly in Xcode, crash logs are visible in Xcode's organizer right away and not after 24 hours, and a lot of other nice little additions, some of which have been highlighted by Paul Hudson in [this Twitter thread](https://twitter.com/twostraws/status/1402138473415548933).

My wish for the last 3 or 4 WWDCs has finally come true: we've now found out what happened to buddybuild after it was purchased by Apple: we'll have Xcode Cloud, Apple's own CI/CD service. Like everything Apple showcases, it seems magical. For now it's in beta and you need to sign up for access. It seems it will be released next year, so there's still some time until we can use it, but it looks very very promising.

Swift got a lot of updates too, and the biggest one is the new concurrency model. [Holly Borla](https://twitter.com/hollyborla) does an incredible job in the PSotU at explaining complex notions such as the new async/await and actors and make them easy to understand, and there are many other sessions dedicated to concurrency in Swift, which we should all watch. But there's plenty of time for that because, as of now, async/await is iOS 15+, [there's no backwards compatibility](https://forums.swift.org/t/will-swift-concurrency-deploy-back-to-older-oss/49370/4). 

SwiftUI also got some love, and you can read about what's new in Majid's article down below. The Swift Playgrounds app on iPad can now build entire apps. In AR news, there's a new Object Cature API, which allows users to create a 3D model from a series of photographs of an object. There's also a new Screentime API which can be used by parent control apps, there are some additions to UIButton (which now allos multi-lines natively), the Formatters (DateFormatters, NumberFormatter, etc) got an overhaul and are basically not needed anymore, because Dates, Numbers and Lists can now format themselves 😅 (see Filip's post below) and many many other updates that we'll have time to discover over the summer.

One of my personal highlights was the addition of the UIKeyboardLayoutGuide, which makes it a lot easier to stop your content from being hidden behind the keyboard. Also, the UISheetPresentationController. Finally, after so many different attempts from the community to recreate the sheet from Apple Maps, Apple gave us the API for it.

One thing that was easy to miss with all the announcements was the App Store Review Guidelines update. Most of the updates seem harmless, but then there this one: "5.1.1(v): Apps supporting account creation must also offer account deletion.". How many of your apps offer accounr deletion 😳? I don't know when they start enforcing it; as with App Store Review Guidelines, in theory it's starting now, and in practice it will probably depend on the reviewer. But this has the potential to affect a lot of apps, so it's good to be aware of it.

Everything new that was announced this week can be found on [this very nice summary page that Apple made](https://developer.apple.com/documentation/New-Technologies-WWDC-2021). And we have all summer and next years to get familiar with those, so no need to rush 😊.

**WWDC**

* [WWDC Notes](https://wwdcnotes.com/), by the WWDC community
* [Pull to refresh in SwiftUI with refreshable](https://sarunw.com/posts/pull-to-refresh-in-swiftui/), by [@sarunw](https://twitter.com/sarunw)
* [iOS 15: Notable UIKit Additions](https://www.swiftjectivec.com/ios-15-notable-uikit-additions/), by [@jordanmorgan10](https://www.twitter.com/jordanmorgan10)
* [WWDC21 - A first look at Apple's new Augmented Reality features](https://engineering.monstar-lab.com/2021/06/08/WWDC21-A-first-look-at-Apples-new-Augmented-Reality-features), by [@RoxanaJula](https://twitter.com/RoxanaJula)
* [New approach to formatters in iOS 15](https://nemecek.be/blog/106/new-approach-to-formatters-in-ios-15), by [@nemecek_f](https://twitter.com/nemecek_f)
* [Meet the new bottom sheet in iOS 15](https://nemecek.be/blog/108/meet-the-new-bottom-sheet-in-ios-15), by [@nemecek_f](https://twitter.com/nemecek_f)
* [What is new in SwiftUI after WWDC21](https://swiftwithmajid.com/2021/06/08/what-is-new-in-swiftui-after-wwdc21/), by [@mecid](https://twitter.com/mecid)
* [Taking UIKit’s new button configuration API for a spin](https://wwdcbysundell.com/2021/uikits-new-button-configuration-api/), by [@johnsundell](https://twitter.com/johnsundell)
* [Roll your own Shazam with the new ShazamKit framework](https://wwdcbysundell.com/2021/roll-your-own-shazam-with-shazamkit/), by [@_inside](https://twitter.com/_inside)

**Articles**

* [Frames in SwiftUI](https://swiftwithmajid.com/2021/06/02/frames-in-swiftui/), by [@mecid](https://twitter.com/mecid)
* [Getting started with SwiftUI](https://paulstamatiou.com/getting-started-with-swiftui/), by [Paul Stamatiou](https://twitter.com/Stammy)
* [Cracking the Navigation Bar Secrets with SwiftUI](https://kristaps.me/blog/swiftui-navigationview/), by [@fassko](https://twitter.com/fassko)
* [SwiftUI List Bindings - Behind the Scenes](https://peterfriese.dev/swiftui-list-item-bindings-behind-the-scenes/), by [@peterfriese](https://twitter.com/peterfriese)

**Tools/Controls**

* 

**Business/Career**

* 

**UI/UX**

* 

**Videos**

* [Building a Reusable Text Input Field With a Floating Label](https://youtu.be/Sg0rfYL3utI), by [@peterfriese](https://twitter.com/peterfriese)
* [Anatomy of an App Store Scam with Kosta Eleftherious](https://appfigures.com/resources/chats/kosta-eleftheriou-anatomy-app-store-scam), by [@arielmichaeli](https://twitter.com/arielmichaeli)

**Contributors**

* [zntfdr](https://github.com/zntfdr), [mecid](https://github.com/mecid), [LisaDziuba](https://github.com/LisaDziuba), [peterfriese](https://twitter.com/peterfriese), [sarunw](https://github.com/sarunw), [rel](https://github.com/rel), [fassko](https://github.com/fassko)
