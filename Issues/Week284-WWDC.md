> This is a very last-minute effort to get a WWDC special edition of iOS Goodies out on Tuesday evening (CET). Since this is a special edition, different than the others, and a bit in a hurry, there's also almost no structure and no process to creating this issue of our newsletter. Sorry about that, blame it on [me](https://twitter/com/marius_const). If you want to contribute to this, feel free to do it. Some ways to do it are:
> - add links to things you found interesting/useful from WWDC 2019
> - if you know of sales on iOS dev learning resources, please add them here. Not 100% sure if those are going to make it to the final edition of the newsletter yet.
> - organize the existing links into "themes": user-facing feature (like the volume hud, etc), developer stuff (further sub-classifications into swift ui, combine, xcode improvements, security and privacy, other new frameworks, etc), design/ux (SF Symbols, less flat design, etc), others
> - be patient and please tolerate the chaotic approach to this issue :). We'll be back on Thursday with a more normal edition of iOS Goodies


Surprise! Happy Tuesday! The first day of WWDC 2019 was so amazing that made me want to send out a special edition of iOS Goodies to share all the good news. This is a spcial edition of our newsletter, so it's not following closely the usual pattern.

The opening keynote brought huge news to developers. tvOS will gain multi-user support, and watchOS gets some new audio streaming APIs. The Apple Watch will become more independent from the iPhone, also gaining its own App Store. iOS 13 was announced, which will run on iPhone SE, iPhone 6s and above, dropping iPhone 6 and iPhone 5S support. Surprisingly, the iOS that's running on iPads was renamed to iPadOS. iPadOS is based on iOS and it seems that, at least this year, [iPadOS is still iOS](https://twitter.com/_inside/status/1135640410175332356), but the different naming might say something about the different directions Apple wants to take the two devices. iPadOS is comatible with iPad Air 2 and newer devices. 

The new macOS is named Catalina, and will probably get a lot more new apps, since project Catalyst (what everybody knew as Marzipan) will help make an iPad app into a Mac app only by selecting a checkbox. At least, that's what they demoed, so it must be true 🙃. It's not clear yet to me how Universal apps will be affected by the iOS/iPadOS split and if only iPad apps can be made into Mac apps or if an iPhone-only app can also become a Mac app, but we have enoudh time to figure that out until September.

The biggest news for developer this year was the introduction of [SwiftUI](https://developer.apple.com/xcode/swiftui/): a new declarative framework for building UIs. SwiftUI works only on iOS 13, [no backwards compatibility](https://twitter.com/UINT_MIN/status/1135643392912658432). Apple added some [very nice tutorials](https://developer.apple.com/tutorials/swiftui) for SwiftUI, which is great to see, and a much better way to learn than downloading sample code or reading some documentation. SwiftUI is built from scratch, [it's not a wrapper](https://twitter.com/jckarter/status/1135627146062286848), it [works great with UIKit, AppKit and more](https://twitter.com/nnnnnnnn/status/1135632048478085121), [you can mix and match between SwiftUI and UIKit](https://twitter.com/smileyborg/status/1135947261848875008) and [the animations in SwiftUI are interactive and interruptible by default](https://twitter.com/b3ll/status/1135766725432004609). If you think the SwiftUI sample code looks like Swift, but not too much, you're not alone. Recent swift Evolution proposals, such as Function Builders, Property Delegates and Opaque Results Types [helped make that SwiftUI code possible](https://twitter.com/peres/status/1135707753958129664). Before you get all too excited, remember that this is iOS 13 only, and to be able to test the Editor and Canvas (live previews) shown in the keynote, [you need the Catalina beta](https://twitter.com/karolsmazur/status/1135762901061513216). There are a lot of sessions on SwiftUI this year, make sure to watch some of them when they'll become available in the WWDC app or on the website.


**Stuff to write about** 

- Combine
- custom initializer in view controllers instantiated from IB
- crypto framework
- mandatory apple sign-in
- modal presentation style: card
- SF Symbols
- core haptics framework

**Credits** 
- https://twitter.com/_inside
- https://twitter.com/johnsundell
- https://twitter.com/UINT_MIN
- https://twitter.com/jckarter
- https://twitter.com/peres
- https://twitter.com/karolsmazur
- https://twitter.com/b3ll


User-facing features:
 - New volume UI: - https://twitter.com/_inside/status/1135673068578168832


Developer stuff:

- beta warnings: https://twitter.com/tomhamming/status/1135643886263492609
- beta is buggy https://twitter.com/azamsharp/status/1135965744385220614
- [iOS & iPadOS 13 Beta Release Notes](https://developer.apple.com/documentation/ios_ipados_release_notes/ios_ipados_13_beta_release_notes) - https://twitter.com/steipete/status/1135639581133398016
- Feedback assistant - https://twitter.com/stroughtonsmith/status/1135899464017862657


  Combine
   - Session recommentation: https://twitter.com/kthomas901/status/1135638338314985476
   - Combine previous names / codenames: https://twitter.com/Catfish_Man/status/1135636630155350016
   - [SwiftUI was only the beginning. Introducing the all new Combine framework for Swift!](https://developer.apple.com/documentation/combine) https://twitter.com/alanzeino/status/1135628020180344833

  SPM
   - Yes, you can now officially use SwiftPM to manage dependencies for iOS apps! https://wwdcbysundell.com/2019/xcode-swiftpm-first-look/
   - SPM works with iOS https://twitter.com/phillfarrugia/status/1135675822398853120
   - https://developer.apple.com/documentation/swift_packages, https://twitter.com/NeoNacho/status/1135630111862976512
   - https://twitter.com/jnadeau/status/1135629627534106625

  Xcode improvements
   - MiniMap with breakpoints: https://twitter.com/noahsark769/status/1135673073217155078
   - MiniMap - hold command to see names f classes, funcs, etc https://twitter.com/_eliperkins/status/1135666873591304192
   - MiniMap shows MARK:// - https://twitter.com/twannl/status/1135646946289258496
   - MiniMap: https://twitter.com/twostraws/status/1135641047508213761
   - https://www.hackingwithswift.com/articles/192/what-s-new-in-xcode-11
   - Session recommendation: Xcode previews: - https://twitter.com/twannl/status/1135640043320532993
   - https://developer.apple.com/xcode/whats-new/

  Security and privacy
   - Crypto: https://www.hackingwithswift.com/example-code/cryptokit/how-to-calculate-the-sha-hash-of-a-string-or-data-instance
   - Crypto: https://twitter.com/rustyshelf/status/1135685294345220096
   - Crypto: https://developer.apple.com/documentation/cryptokit
   - MD5 marked as insecure https://twitter.com/vixentael/status/1135680658301444096
   - Location access always: pop-up now and then reminding https://twitter.com/kuba_suder/status/1135678642506338305
   - Apps can't ask for "always" location. Asked when in background https://twitter.com/_inside/status/1135678598336040960
   - App Store Review Guidelines: kids app can't share data with 3rd parties since september 2019 https://twitter.com/preshit/status/1135646822255304704
   - Is Heroku 3rd party? Is aws 3rd party? https://twitter.com/jeiting/status/1135939322270478336

  Other new frameworks
   - Core Haptics https://www.hackingwithswift.com/example-code/core-haptics/how-to-play-custom-vibrations-using-core-haptics
   - UICollectionViewDiffableDataSource https://twitter.com/_ryannystrom/status/1135683786690113536
   - Sample code of diffable collection view data source https://twitter.com/MarvinNazari/status/1135681117384773632
   - Undo / redo gestures work out of the box with NSUndoManager https://twitter.com/steipete/status/1135675328947400704
   - Card-like modal presentation: https://twitter.com/_eliperkins/status/1135674169688055808
   - new mdal style and redesigned UISegmentController: https://twitter.com/hansemannnn/status/1135667513960816642
   - Mandatory Apple Sign In - https://twitter.com/sandofsky/status/1135673287659347968
   - Starting next spring, it will be an App Store requirement for apps to adopt to different screen sizes. https://twitter.com/steipete/status/1135660558261186560
   - Custom initializers on stuff instantiated from IB: https://twitter.com/kharrison/status/1135641442658017281

Design/ux:
- https://developer.apple.com/design/ - https://twitter.com/themikestern/status/1135636351414460416
- SF Symbols - https://twitter.com/twostraws/status/1135639902337478656
- SF Symbols typed: https://twitter.com/simjp/status/1135936933916336128
- Apple design resources: https://developer.apple.com/design/resources/
- HIG updates
- Context menus: https://developer.apple.com/design/human-interface-guidelines/ios/controls/context-menus/


Others:

- macOS Catalina uses ZSH instead of bash, probably because of licensing issues https://twitter.com/nevyn/status/1135814006323712000
- what's new in ios 13: https://www.hackingwithswift.com/articles/193/whats-new-in-ios-13

[Beta downloads](https://developer.apple.com/download/)
