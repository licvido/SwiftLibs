# SwiftLibs

[![Platform](http://img.shields.io/badge/platform-ios-blue.svg?style=flat)](https://developer.apple.com/iphone/index.action)
[![Language](http://img.shields.io/badge/language-swift-brightgreen.svg?style=flat)](https://developer.apple.com/swift)

List of my favorite swift libraries, frameworks, extensions, tools, examples, etc.

## Table of Contents
* [Layout, UI](#layout-ui)
* [Networking](#networking)
* [Images](#images)
* [Dispatches](#dispatches)
* [JSON](#json)
* [Databases](#databases)
* [Games, SceneKit, SpriteKit](#games-scenekit-spritekit)
* [Caching](#caching)
* [Extensions](#extensions)
* [Authentication](#authentication)
* [Playgrounds](#playgrounds)
* [Others](#others)


## Layout, UI

* [Neon](https://github.com/mamaral/Neon) - A powerful Swift programmatic UI layout framework.
* [SnapKit](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & OS X.
* [ActiveLabel.swift](https://github.com/optonaut/ActiveLabel.swift) - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://).
* [ParkedTextField](https://github.com/gmertk/ParkedTextField) - A text field with a constant text/placeholder.
* [LiquidFloatingActionButton](https://github.com/yoavlt/LiquidFloatingActionButton) - Material Design Floating Action Button in liquid state.
* [TKSubmitTransition](https://github.com/entotsu/TKSubmitTransition) - Animated UIButton of Loading Animation and Transition Animation.
* [AMScrollingNavbar](https://github.com/andreamazz/AMScrollingNavbar) - Scrollable UINavigationBar that follows the scrolling of a UIScrollView.
* [BRYXBanner](https://github.com/bryx-inc/BRYXBanner) - A lightweight dropdown notification for iOS 7+, in Swift.
* [PullToBounce](https://github.com/entotsu/PullToBounce) - Animated "Pull To Refresh" Library for UIScrollView.
* [TKAnimatedCheckButton](https://github.com/entotsu/TKAnimatedCheckButton) - Animated Check Button.
* [FillableLoaders](https://github.com/poolqf/FillableLoaders) - Completely customizable progress based loaders drawn using custom CGPaths written in Swift.
* [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) - Collection of nice loading animations.
* [TOCropViewController](https://github.com/TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects.
* [iOS Charts](https://github.com/danielgindi/ios-charts) - An iOS port of the beautiful MPAndroidChart.
* [CVCalendar](https://github.com/Mozharovsky/CVCalendar) - A custom visual calendar for iOS 8 written in Swift.
* [UIStackViewPlayground](https://github.com/dasdom/UIStackViewPlayground) - Playground to play with UIStackViews.
* [CariocaMenu](https://github.com/arn00s/cariocamenu) - CariocaMenu is a simple, elegant, fast, modern, innovative, ..., navigation menu for your iOS app.
* [Cartography](https://github.com/robb/Cartography) - A declarative Auto Layout DSL.
* [FlagKit](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web.
* [CardAnimation](https://github.com/seedante/CardAnimation) - There are two style implement, auto layout and frame-based layout.
* [FrostedSidebar](https://github.com/edekhayser/FrostedSidebar) - Hamburger Menu using Swift and iOS 8 API's
* [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) - A custom animation for the UIRefreshControl.
* [SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by facebook, twitter photo browsers written by swift 2.0.
* [DGElasticPullToRefresh](https://github.com/gontovnik/DGElasticPullToRefresh) - Elastic pull to refresh for iOS developed in Swift.
* [StarWars Animation](https://github.com/Yalantis/StarWars.iOS) - This component implements transition animation to crumble view-controller into tiny pieces.
* [Instructions](https://github.com/ephread/Instructions) - Create walkthroughs and coach mark tours in a simple way.

## Networking

* [Alamofire](https://github.com/Alamofire/Alamofire) - Elegant HTTP Networking in Swift.
* [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web.
* [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures.

## Images

* [ImageLoaderSwift](https://github.com/hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS written in Swift.
* [Toucan](https://github.com/gavinbunney/Toucan) - Fabulous Image Processing in Swift.
* [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web.
* [Nuke](https://github.com/kean/Nuke) - Advanced framework for managing images.
* [TOCropViewController](https://github.com/TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects.

## Dispatches

* [Async](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch.
* [RateLimit](https://github.com/soffes/RateLimit) - Simple utility for only executing code every so often.

## JSON

* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - Simple JSON Object mapping written in Swift.
* [AlamofireObjectMapper](https://github.com/tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper.
* [Unbox](https://github.com/JohnSundell/Unbox) - The easy to use Swift JSON decoder.
* [Argo](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift.
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift.
* [Decodable](https://github.com/Anviking/Decodable) - Swift 2 JSON parsing done (more) right.
* [ModelRocket](https://github.com/ovenbits/ModelRocket) - An iOS framework for creating JSON-based models.
* [JSONWebToken.swift](https://github.com/kylef/JSONWebToken.swift) - Swift implementation of JSON Web Token (JWT).
* [Gloss](https://github.com/hkellaway/Gloss) - A shiny JSON parsing library in Swift.
* [Genome](https://github.com/LoganWright/Genome) - A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 2.0 (Supports Linux)

## Databases

* [Realm](https://github.com/realm/realm-cocoa) - Realm is a mobile database: a replacement for Core Data & SQLite.
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3.

## Games, SceneKit, SpriteKit

* [SceneKitFrogger](https://github.com/devindazzle/SceneKitFrogger) - A 3D Frogger / Crossy Road clone made with Scene Kit and Swift.
* [Swift 2048](https://github.com/austinzheng/swift-2048) - 2048 for Swift.
* [FlappySwift](https://github.com/fullstackio/FlappySwift) - Swift implementation of flappy bird.
* [JigsawPuzzle](https://github.com/nealCeffrey/JigsawPuzzle) - Simple 9x9 jigsaw puzzle game.
* [Breakout](https://github.com/nealCeffrey/Breakout) - Simple breakout game.
* [Simple SpriteKit Game](https://github.com/mihailt/simple-sprite-kit-game) - Simple SpriteKit game with sounds, gestures, dynamic lightning, detect collisions, has splash and shake screen effects.
* [Orbit7](https://github.com/Mav3r1ck/Orbit7) - Open Source iOS Game created in SpriteKit with Swift.

## Caching

* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images.

## Extensions

* [ExSwift](https://github.com/pNre/ExSwift) - A set of Swift extensions for standard types and classes.
* [UIColor+Hex](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string.
* [EVReflection](https://github.com/evermeer/EVReflection) - Swift helper library with reflection functions with support for NSCoding, Printable, Hashable, Equatable and JSON.

## Authentication

* [OAuth2](https://github.com/p2/OAuth2) - OAuth2 framework for OS X and iOS, written in Swift.
* [OAuthSwift](https://github.com/dongri/OAuthSwift) - Swift based OAuth library for iOS.

## Playgrounds

* [UIStackViewPlayground](https://github.com/dasdom/UIStackViewPlayground) - Playground to play with UIStackViews.

## Others

* [PathKit](https://github.com/kylef/PathKit) - Effortless path operations in Swift.
* [Design Patterns In Swift](https://github.com/ochococo/Design-Patterns-In-Swift) - Design Patterns implemented in Swift.
* [Linchi](https://github.com/loiclec/Linchi) - Small web server written in pure Swift, designed for Linux.
* [awesome-swift](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome swift resources. Great source!
* [jazzy](https://github.com/realm/jazzy) - Soulful docs for Swift & Objective-C.
* [Swift Radio](https://github.com/swiftcodex/Swift-Radio-Pro) - Professional Radio Station App.
* [SwiftWeather](https://github.com/JakeLin/SwiftWeather) - SwiftWeather is an iOS weather app developed in Swift 2.
* [LeetCode Solutions in Swift](https://github.com/diwu/LeetCode-Solutions-in-Swift) - Get prepared for your next iOS job interview by studying high quality LeetCode solutions in Swift 2.1.
* [Plum-O-Meter](https://github.com/FlexMonkey/Plum-O-Meter) - 3D Touch Application for Weighing Plums (and other small fruit!)
