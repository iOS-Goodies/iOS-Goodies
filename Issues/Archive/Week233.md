We're half-way through the WWDC week, and we already know most of what Apple prepared for us. There's so much information that it's hard to cover it all, and I expect it's going to take at least a few weeks to fully understand and get used to all the updates. To celebrate the WWDC week (and to keep it to a readable length), this issue will have a slightly different structure than usual.

**WWDC 18**

As expected, we got the first previews of iOS 12, tvOS 12, macOS Mojave and watchOS 5, as well as the first betas for them (except for watchOS 5 beta 1, which will be available soon). And we got a confirmation of what's been known as the Marzipan project (although Apple didn't use that name - or any name for it): next year it will be possible to build certain iOS apps for macOS. Apple is testing that by porting Voice Memos, Stocks, Apple News and Home, but insist the two platforms won't be merged together. [Michael Tsai](https://twitter.com/mjtsai) gathered [more impressions on this](https://mjtsai.com/blog/2018/06/05/apple-announces-marzipan-for-2019/). And there's already a [MarzipanTool](https://github.com/zhuowei/MarzipanTool/) that helps you run iOSMac apps on macOS 10.14 Beta, made by [@zhuowei](https://twitter.com/zhuowei).

In iOS, we finally got what the Workflow team has been working on at Apple: [Siri Shortcuts](https://developer.apple.com/sirikit/). This is a great feature in my opinion, one that I wasn't expecting, but one which I really think makes Siri a lot more useful. Watch the [WWDC session on those](https://developer.apple.com/videos/play/wwdc2018/211/) for more details.

In other news, iTunes Connect is being replaced by [App Store Connect](https://developer.apple.com/app-store-connect/): the website already redirects to the newer version, and there's a new iOS app. And the best part about this is that soon you'll be able to invite beta testers to your app by sharing a link (no need to colect email addresses). Speaking of the App Store, we can now have free trials in the App Store. But before you get too excited, make sure to read [@danielpunkass](http://twitter.com/danielpunkass/)' article, [Ersatz Free Trials](https://bitsplitting.org/2018/06/06/ersatz-free-trials/), which shows how the free trials really work and what the downside of that is.

Apple also [announced CreateML](https://medium.com/p/wwdc-2018-apple-announces-create-ml-976c30a80192), a tool for creating machine learning models. As well as this, there were updates and advances in ARKit and CoreML, which I'm sure we'll cover in the issues to come. 

As far as Xcode is concerned, beides the beautiful Dark Mode that you can get in macOS Mojave, there are improvements in refactoring and a much better source control integration which allows you to get more upstream code details. We also got a few new Instruments, as well as the possibility to build our own with custom data and vizualizations. A major update is in testing, where you can now run unit and UI tests in parallel. Xcode 10 comes with Swift 4.2 (you can see what's new in [this playground](https://github.com/ole/whats-new-in-swift-4-2)). What I really love about Xcode 10 is that [it finally adds multi-cursor editing](https://twitter.com/olebegemann/status/1003721681301622785).

There were also updates to the [Design Resources](https://developer.apple.com/design/whats-new/), as well as to the [App Review Guidelines](https://gist.github.com/hongrich/260fc8c36aaed3f2a63c0612ba9fc910/revisions).

To keep this issue to a reasonable length, I'll leave you with the [WWDC 18 links](https://mjtsai.com/blog/2018/06/04/wwdc-2018-links/), folowed by a few of the best non-WWDC-related links of this week.

**Articles**

* [Readable and maintainable UITests](https://medium.com/@vermeer.edwin/readable-and-maintainable-uitests-c192a44abde9), by [@evermeer](https://twitter.com/evermeer)
* [Code Injection In Swift](https://medium.com/itch-design-no/code-injection-in-swift-c49be095414c), by [@zenangst](https://twitter.com/zenangst)
* [Why I build my apps using Texture (and why you should too)](https://medium.com/flawless-app-stories/why-i-build-my-apps-using-texture-and-why-you-should-too-99587c73f278), by [@codeOfRobin](https://twitter.com/codeOfRobin)

**Tools/Controls**
* [xcperfect](https://github.com/mkchoi212/xcperfect) - Make your xccov outputs prettier, by [@bananamlkshake2](https://twitter.com/Bananamlkshake2)
* [Vaccine](https://github.com/zenangst/Vaccine) - Vaccine is a framework that aims to make your apps immune to recompile-decease, by [@zenangst](https://twitter.com/zenangst)
* [Crossroad](https://github.com/giginet/Crossroad) - Crossroad is an URL router focused on handling Custom URL Scheme, by [@giginet](https://twitter.com/giginet)

**Credits**

* [zenangst](https://github.com/zenangst), [FranciscoAmado](https://github.com/FranciscoAmado), [mkchoi212](https://github.com/mkchoi212)
