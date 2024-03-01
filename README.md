# Awesome RealityKit
<div align="center">
    <img src="Awesome_RealityKit_header.png" alt="header">
</div>

Awesome projects and resources about RealityKit. Feel free to contribute!

The RealityKit framework was built from the ground up specifically for augmented reality with photo-realistic rendering, camera effects, animations, physics, and more. With native Swift APIs, ARKit integration, incredibly realistic physics-based rendering, transform and skeletal animations, spatial audio, and rigid body physics, RealityKit makes AR development faster and easier than ever before.

 * [Projects](#projects)
   + [Community](#community)
       + [Samples](#samples)
       + [Packages](#packages)
       + [VisionOS](#visionos)
   + [Apple](#apple_projects)
 * [Resources](#resources)
    + [Articles](#articles)
    + [Apple](#apple)
    + [WWDC](#wwdc)
        + [2023](#2023)
        + [2022](#2022)
        + [2021](#2021)
        + [2020](#2020)
        + [2019](#2019)
    
## Projects

### Community
#### Samples
- [RealityKit-Sampler](https://github.com/john-rocky/RealityKit-Sampler) - RealityKitSampler is a sample collection of basic functions of RealityKit, Apple's AR framework for iOS
- [RealityKit CardFlip](https://github.com/maxxfrazer/RealityKit-CardFlip) - RealityKit CardFlip game
- [RealityKit 2 DrawableQueue](https://github.com/arthurschiller/realitykit-drawable-queue) - A sample project demonstrating a usecase for the DrawableQueue API in RealityKit 2
- [RealityKitLaunchScreen](https://github.com/aheze/RealityKitLaunchScreen/tree/main) - A launch screen made with SwiftUI and RealityKit
- [Glass-Fit](https://github.com/mounarezgui-mobile/glass-fit) - Glass-Fit is an open-source iOS app demo that showcases the power of RealityKit in making 3D overlays effortless using Reality Composer
- [Capturinator](https://github.com/BertanT/Capturinator) - Powered by RealityKit, Capturinator is a Mac app that turns photos of an object taken at multiple angles into 3D USDZ models.
#### Packages
- [RealityActions](https://github.com/migueldeicaza/RealityActions) - RealityActions brings the popular Cocos2D-style action framework to Entities in RealityKit.
- [FocusEntity](https://github.com/maxxfrazer/FocusEntity) - FocusEntity lets you see exactly where the centre of the view will sit in the AR space
- [RealityUI](https://github.com/maxxfrazer/RealityUI) - RealityUI is a collection of User Interface classes for RealityKit
- [Mirador](https://github.com/HyperARCo/Mirador) - Mirador makes it easy to build impressive point-of-interest AR experiences on top of Apple’s new AR platform, RealityKit
- [RealityKit-Collisions](https://github.com/Reality-Dev/RealityKit-Collisions) - This is a convenience API for setting Collision Filters in RealityKit
- [RealityGeometries](https://github.com/maxxfrazer/RealityGeometries) - Add more geometries to your RealityKit projects
- [BodyTracking](https://github.com/Reality-Dev/BodyTracking) - This package includes classes that enable easy, convenient body tracking in RealityKit
- [Euclid](https://github.com/nicklockwood/Euclid) - Euclid is a Swift library for creating and manipulating 3D geometry using techniques such as extruding or "lathing" 2D paths to create solid 3D shapes, and CSG (Constructive Solid Geometry) to combine or subtract those shapes from one another.
- [reality-dump](https://github.com/elkraneo/reality-dump) - `swift-custom-dump` extension for RealityKit
- [Reality Morpher](https://github.com/Utsira/RealityMorpher) - Adds Morph Target / Shape Key / Blend Shape animations to RealityKit
- [GoncharKit](https://github.com/gonchar/GoncharKit) - RealityKit helper functions for visionOS
- [ShaderGraphCoder](https://github.com/praeclarum/ShaderGraphCoder) - An embedded DSL to write RealityKit shaders in Swift.

#### VisionOS
-  [ImmersiveMoveAndRotate](https://github.com/simonbs/ImmersiveMoveAndRotate) - Example project showing how an immersive scene on visionOS can contain a RealityView that presents a ModelEntity and how that entity can be dragged using DragGesture and rotated using RotateGesture.
- [VisionCraft](https://github.com/Sigil-Wen/VisionCraft) - Minecraft Clone in Apple Vision Pro
- [GenerativeDoodleArt_VisionOS](https://github.com/tracyhenry/GenerativeDoodleArt_VisionOS/tree/54f504eaf7548fc6bb8f910d8e6f379b402812c2) - Explore the transformative capabilities of visionOS by creating augmented reality wall art using Vision Pro
- [VOClimateSpiral](https://github.com/ynagatomo/VOClimateSpiral) - Very simple AR app in visionOS, that shows the climate spiral, which is known as a way to visualize global surface temperature change
- [MacCast](https://github.com/saagarjha/MacCast) - Cast Mac windows to visionOS
- [HandsWidth](https://github.com/FlipByBlink/HandsWidth) - Measure app by hand tracking for Apple Vision Pro
- [BeatmapVisionPro](https://github.com/fabio914/BeatmapVisionPro) - Beat Saber map (a.k.a beatmap) visualizer for the Apple Vision Pro. This project is the successor of BeatmapAR for iOS.
- [ALVR-VisionOS](https://github.com/alvr-org/alvr-visionos) - Experimental visionOS client for ALVR - SteamVR on Apple Vision Pro

### Apple <a name="apple_projects"></a>
- [Building an Immersive Experience with RealityKit](https://developer.apple.com/documentation/realitykit/building_an_immersive_experience_with_realitykit) - Use systems and postprocessing effects to create a realistic underwater scene
- [Controlling Entity Collisions in RealityKit](https://developer.apple.com/documentation/realitykit/controlling_entity_collisions_in_realitykit) - Create collision filters to control which objects collide
- [Creating a game with scene understanding](https://developer.apple.com/documentation/realitykit/creating_a_game_with_scene_understanding) - Create AR games and experiences that interact with real-world objects on LiDAR-equipped iOS devices.
- [Creating a Game with Reality Composer](https://developer.apple.com/documentation/realitykit/creating_a_game_with_reality_composer) - Design your app’s visual look and behaviors in Reality Composer, and complete the gameplay experience by using custom RealityKit code
- [SwiftStrike: Creating a Game with RealityKit](https://developer.apple.com/documentation/realitykit/swiftstrike_creating_a_game_with_realitykit) - Create a multiplayer game with ARKit, RealityKit, and Swift using the SwiftStrike app as a guide
- [Hello World](https://developer.apple.com/documentation/visionos/world) - Use windows, volumes, and immersive spaces to teach people about the Earth
- [Diorama](https://developer.apple.com/documentation/visionos/diorama) - Design scenes for your visionOS app using Reality Composer Pro
- [Swift Splash](https://developer.apple.com/documentation/visionos/swift-splash) - Use RealityKit to create an interactive ride in visionOS

## Resources
### Articles
- [Getting started with RealityKit](https://maxxfrazer.medium.com/getting-started-with-realitykit-3b401d6f6f) - Series of articles about RealityKit
- [RealityKit](https://www.kodeco.com/books/apple-augmented-reality-by-tutorials/v1.0/chapters/9-realitykit) - Part of the book about RealityKit from kodeco
- [Building an AR app with RealityKit](https://www.ralfebert.com/ios/realitykit-dice-tutorial/) - RealityKit dice AR game tutorial
- [Introduction to RealityKit on iOS— Entities, Gestures, and Ray Casting](https://betterprogramming.pub/introduction-to-realitykit-on-ios-entities-gestures-and-ray-casting-8f6633c11877) - Introduction to RealityKit
- [Introduction to RealityKit](https://codingxr.com/?tag=realitykit) - Introduction to RealityKit from codingxr
- [Create your first AR app with RealityKit and SwiftUI](https://medium.com/twinkl-educational-publishers/create-your-first-ar-app-with-realitykit-and-swiftui-7c5d1388b5) - Introduction to RealityKit
- [How to animate AR objects with SwiftUI and RealityKit](https://medium.com/twinkl-educational-publishers/how-to-animate-ar-objects-with-swiftui-and-realitykit-b14730c4fad9)
- [RealityKit on iOS, part 2 — applying collision events](https://betterprogramming.pub/realitykit-on-ios-part-2-applying-collision-events-d64b6e10421f) - Detect and Handle Collision Events in a RealityKit Scene Across Different Entities
- [Evolution of Metal, ARKit, and RealityKit Sheet](https://github.com/ynagatomo/evolution-Metal-ARKit-RealityKit-sheet) - This sheet shows the evolution of Apple frameworks - Metal, ARKit, and RealityKit
- [Awesome visionOS](https://github.com/stevenpaulhoward/awesome-visionos) - Awesome Apple visionOS related content
### Apple
- [RealityKit Overview](https://developer.apple.com/augmented-reality/realitykit/) - Overview
- [RealityKit Documentation](https://developer.apple.com/documentation/realitykit) - Simulate and render 3D content for use in your augmented reality apps
- [Understanding RealityKit’s modular architecture](https://developer.apple.com/documentation/visionos/understanding-the-realitykit-modular-architecture) - Learn how everything fits together in RealityKit
- [Building an Immersive Experience with RealityKit](https://developer.apple.com/documentation/realitykit/building_an_immersive_experience_with_realitykit) - Use systems and postprocessing effects to create a realistic underwater scene
- [Designing RealityKit content with Reality Composer Pro](https://developer.apple.com/documentation/visionos/designing-realitykit-content-with-reality-composer-pro) - Design RealityKit scenes for your visionOS app
- [Loading Entities from a File](https://developer.apple.com/documentation/realitykit/loading-entities-from-a-file) - Retrieve an entity from storage on disk using a synchronous or an asynchronous load operation
- [Implementing systems for entities in a scene](https://developer.apple.com/documentation/realitykit/implementing-systems-for-entities-in-a-scene) - Apply behaviors and physical effects to the objects and characters in a RealityKit scene with the Entity Component System (ECS)
- [Creating 3D Content with Reality Composer](https://developer.apple.com/documentation/realitykit/creating-3d-content-with-reality-composer) - Assemble assets into a dynamic 3D composition that you can add to a scene in your app, or share with AR Quick Look
- [Improving the Accessibility of RealityKit Apps](https://developer.apple.com/documentation/realitykit/improving-the-accessibility-of-realitykit-apps) - Incorporate assistive technologies in your augmented reality app
- [Capturing photographs for RealityKit Object Capture](https://developer.apple.com/documentation/realitykit/capturing-photographs-for-realitykit-object-capture) - Take high-quality images of objects to generate 3D models
- [Modifying RealityKit Rendering Using Custom Materials](https://developer.apple.com/documentation/realitykit/modifying-realitykit-rendering-using-custom-materials) - Write Metal shader functions to implement custom rendering effects
- [Designing Scene Hierarchies for Efficient Physics Simulation](https://developer.apple.com/documentation/realitykit/designing-scene-hierarchies-for-efficient-physics-simulation) - Configure your RealityKit scenes to avoid performance bottlenecks
- [Handling Different-Sized Objects in Physics Simulations](https://developer.apple.com/documentation/realitykit/handling-different-sized-objects-in-physics-simulations) - Set up a scene hierarchy for accurate physics simulations
- [Improving the Performance of a RealityKit App](https://developer.apple.com/documentation/realitykit/improving-the-performance-of-a-realitykit-app) - Measure CPU and GPU utilization to find ways to improve your app’s performance
### WWDC

#### 2023
- [Explore rendering for spatial computing](https://developer.apple.com/videos/play/wwdc2023/10095/) - Find out how you can take control of RealityKit rendering to improve the look and feel of your apps and games on visionOS
- [Meet RealityKit Trace](https://developer.apple.com/videos/play/wwdc2023/10099/) - Discover how you can use RealityKit Trace to improve the performance of your spatial computing apps
- [Enhance your spatial computing app with RealityKit](https://developer.apple.com/videos/play/wwdc2023/10081/) - Go beyond the window and learn how you can bring engaging and immersive 3D content to your apps with RealityKit
- [Evolve your ARKit app for spatial experiences](https://developer.apple.com/videos/play/wwdc2023/10091/) - Learn how ARKit and RealityKit have evolved for spatial computing
- [Explore materials in Reality Composer Pro](https://developer.apple.com/videos/play/wwdc2023/10202/) - Learn how Reality Composer Pro can help you alter the appearance of your 3D objects using RealityKit materials
- [Build great games for spatial computing](https://developer.apple.com/videos/play/wwdc2023/10096/) - Find out how you can develop great gaming experiences for visionOS
- [Develop your first immersive app](https://developer.apple.com/videos/play/wwdc2023/10203/) - Find out how you can build immersive apps for visionOS using Xcode and Reality Composer Pro
- [Build spatial experiences with RealityKit](https://developer.apple.com/videos/play/wwdc2023/10080/) - Discover how RealityKit can bring your apps into a new dimension
- [Advanced Scene Understanding in AR](https://developer.apple.com/videos/play/tech-talks/609/) - ARKit 3.5 and RealityKit provide new capabilities that take full advantage of the LiDAR Scanner on the new iPad Pro
#### 2022
- [Bring your world into augmented reality](https://developer.apple.com/videos/play/wwdc2022/10128/) - Follow along as we demonstrate how you can use Object Capture and RealityKit to bring real-world objects into an augmented reality game
#### 2021
- [Explore advanced rendering with RealityKit 2](https://developer.apple.com/videos/play/wwdc2021/10075/) - Create stunning visuals for your augmented reality experiences with cutting-edge rendering advancements in RealityKit
- [Dive into RealityKit 2](https://developer.apple.com/videos/play/wwdc2021/10074/) - Creating engaging AR experiences has never been easier with RealityKit 2
#### 2020
- [What's new in RealityKit](https://developer.apple.com/videos/play/wwdc2020/10612/) - RealityKit is Apple's rendering, animation, physics, and audio engine built from the ground up for augmented reality
#### 2019
- [Building Collaborative AR Experiences](https://developer.apple.com/videos/play/wwdc2019/610/) - With iOS 13, ARKit and RealityKit enable apps to establish shared AR experiences faster and easier than ever
- [Building Apps with RealityKit](https://developer.apple.com/videos/play/wwdc2019/605/) - Gain a practical understanding of RealityKit capabilities by developing a game using its easy-to-learn API
- [Introducing RealityKit and Reality Composer](https://developer.apple.com/videos/play/wwdc2019/603/) - Architected for AR, RealityKit provides developers access to world-class capabilities for rendering, animation, physics, and spatial audio
