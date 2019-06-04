> This is a very last-minute effort to get a WWDC special edition of iOS Goodies out on Tuesday evening (CET). Since this is a special edition, different than the others, and a bit in a hurry, there's also almost no structure and no process to creating this issue of our newsletter. Sorry about that, blame it on [me](https://twitter/com/marius_const). If you want to contribute to this, feel free to do it. Some ways to do it are:
> - add links to things you found interesting/useful from WWDC 2019
> - if you know of sales on iOS dev learning resources, please add them here. Not 100% sure if those are going to make it to the final edition of the newsletter yet.
> - organize the existing links into "themes": user-facing feature (like the volume hud, etc), developer stuff (further sub-classifications into swift ui, combine, xcode improvements, security and privacy, other new frameworks, etc), design/ux (SF Symbols, less flat design, etc), others
> - be patient and please tolerate the chaotic approach to this issue :). We'll be back on Thursday with a more normal edition of iOS Goodies

**Stuff to write about** 

- iOS 13 compatible devices
- iPad OS
- SwiftUI ios 13 onwards
- Combine
- custom initializer in view controllers instantiated from IB
- crypto framework
- mandatory apple sign-in
- modal presentation style: card
- SF Symbols
- core haptics framework

**Credits** 
- People who tweeted stuff I saw

**Sales**
- https://www.hackingwithswift.com/offers/wwdc19-50



- "future of apple" https://twitter.com/stroughtonsmith/status/1135647926439632899


User-facing features:
 - New volume UI: - https://twitter.com/_inside/status/1135673068578168832


Developer stuff:

- beta warnings: https://twitter.com/tomhamming/status/1135643886263492609
- beta is buggy https://twitter.com/azamsharp/status/1135965744385220614
- [iOS & iPadOS 13 Beta Release Notes](https://developer.apple.com/documentation/ios_ipados_release_notes/ios_ipados_13_beta_release_notes) - https://twitter.com/steipete/status/1135639581133398016
- Feedback assistant - https://twitter.com/stroughtonsmith/status/1135899464017862657

  Swift UI
   - Editor and Canvas (previews) needs Catalina https://twitter.com/karolsmazur/status/1135762901061513216
   - under the hood: https://twitter.com/peres/status/1135707753958129664
   - Swift UI is not a wrapper, it's all new https://twitter.com/kuba_suder/status/1135693450190426112
   - Swift UI is not a wrapper, maybe a bridge: - https://twitter.com/jckarter/status/1135627146062286848
   - Swift UI built from scratch https://twitter.com/Lascorbe/status/1135677628789080064
   - Swift UI built from scratch: UIView or NSView - implementation detail https://twitter.com/jckarter/status/1135676286079135744
   - Swift UI only on iOS 13 +: https://twitter.com/UINT_MIN/status/1135643392912658432
   - https://developer.apple.com/xcode/swiftui/
   - Session recommendation: https://twitter.com/luka_bernardi/status/1135638382028021761
   - Swift UI tutorials: Swift UI in view controllers - https://twitter.com/nnnnnnnn/status/1135632048478085121
   - no more storyboards - https://twitter.com/cocoawithlove/status/1135630886680973312
   - https://www.hackingwithswift.com/articles/191/swiftui-lets-us-build-declarative-user-interfaces-in-swift
   - Swift UI in View controllers and views: https://twitter.com/jnadeau/status/1135626293301501952
   - Swift UI interop: https://twitter.com/smileyborg/status/1135947261848875008
   - https://www.hackingwithswift.com/articles/194/get-started-with-swiftui


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

Credits:
*  

[Beta downloads](https://developer.apple.com/download/)
