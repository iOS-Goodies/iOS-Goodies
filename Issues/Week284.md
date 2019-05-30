Happy Thursday! One of our colleagues told us earlier this week about a weird issue where, after migrating to Swift 5,  `tableView(_:didSelectRowAt:)` was not called anymore in a subclass of another view controller. To make this even harder to catch, it was not happening in a debug build, only in release. It turned out [other people had](https://stackoverflow.com/questions/55592341/xcode-10-2-with-swift-5-0-compiler-protocol-inheritance-issue) [this problem too](https://twitter.com/thesunshinejr/status/1133696540449624064). This seems to be [a known issue ](https://bugs.swift.org/browse/SR-10257) for the Swift team, and apparently it's been resolved. Now we just need new Swift and Xcode releases 😄. Until then, it's good to be aware of this issue, as it's quite hard to catch, since it's only happening in builds in `wholemodule` mode.

**Articles**

* [The power of Delegate design pattern](https://mecid.github.io/2019/05/29/the-power-of-delegate-design-pattern/), by [@mecid](https://twitter.com/mecid)
* [Infinite UIScrollView](https://medium.com/flawless-app-stories/infinite-uiscrollview-b516a5d14caf), by [@AybekCan](https://twitter.com/AybekCan)
* [@autoreleasepool uses in 2019 Swift](https://swiftrocks.com/autoreleasepool-in-2019-swift.html), by [@rockthebruno](https://twitter.com/rockthebruno)
* [Visualizing navigation flow progress](https://osinski.dev/posts/visualizing-navigation-flow-progress/), by [@seb_osinski](https://twitter.com/seb_osinski)
* [ReSwift - Introduction to Redux architecture in Swift](https://benoitpasquier.com/intro-redux-in-swift-with-reswift/), by [@BenoitPasquier_](https://twitter.com/benoitpasquier_)
* [Migrating paid app to free app with In-App Purchase](https://fluffy.es/migrate-paid-app-to-iap/), by [@soulchildpls](https://twitter.com/soulchildpls)
* [Simplifying communication patterns with closure in Swift](https://medium.com/flawless-app-stories/simplifying-communication-patterns-with-closure-in-swift-1938414468b3), by [@onmyway133](https://twitter.com/onmyway133)
* [Migrating to Codable from a third party parsing library](https://medium.com/@elenipapanikolo/migrating-to-codable-from-a-third-party-parsing-library-fd85298ef5a2), by [@elenipapanikolo](https://twitter.com/elenipapanikolo)
* [Preparing a code base for WWDC](https://wwdcbysundell.com/2019/preparing-a-code-base/), by [@swiftbysundell](https://twitter.com/swiftbysundell)
* [How Xcode Indexing Works and How You Can Fix IDE Problems with Your Projects](https://pspdfkit.com/blog/2019/how-xcode-indexing-works-and-how-to-solve-problems), by [@dmartincy](https://twitter.com/dmartincy)
* [How to Save Images and Videos to Core Data Efficiently](http://www.vadimbulavin.com/how-to-save-images-and-videos-to-core-data-efficiently/), by [@V8tr](https://twitter.com/V8tr)
* [Working with Fastlane on iOS in an Enterprise Environment](https://heartbeat.fritz.ai/working-with-fastlane-on-ios-in-an-enterprise-environment-7057a9a8c2d3), by [@mgrebenets](https://twitter.com/mgrebenets)
* [Custom Navigation Transitions, Part III: A Complex Push/Pop Animation](https://devsign.co/notes/navigation-transitions-iii), by [@bryanjclark](https://twitter.com/bryanjclark)
* [Custom Navigation Transitions, Part IV: An Interactive Pop Transition](https://devsign.co/notes/navigation-transitions-iv), by [@bryanjclark](https://twitter.com/bryanjclark)

**Tools/Controls**

* [XCTAssertAutolayout](https://github.com/tarunon/XCTAssertAutolayout) - Provides assert function that check autolayout error in Swift , by [@tarunon](https://twitter.com/tarunon)
* [PVView](https://github.com/toannt/PVView) - A small library that helps you to make an amazing parallax view , by Toan Nguyen

**Business/Career**

* [How my distributed team communicates so no context is left behind](https://circleci.com/blog/how-my-distributed-team-communicates-so-no-context-is-left-behind/), by [@yundt](https://twitter.com/yundt)


**UI/UX**

* [Intentional Subscriptions — Ideas for better subscriptions on iOS](https://david-smith.org/blog/2019/05/28/intentional-subscriptions/), by [@_DavidSmith](http://twitter.com/_DavidSmith)

**Videos**

* 

**Credits**

* [valianka](https://github.com/valianka), [SebastianOsinski](https://github.com/SebastianOsinski), [popei69](https://github.com/popei69), [cupnoodle](https://github.com/cupnoodle), [mecid](https://github.com/mecid), [valianka](https://github.com/valianka)
