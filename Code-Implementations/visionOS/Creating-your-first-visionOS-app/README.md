## Creating your first visionOS app
Tuorial by Apple - Build a new visionOS app using SwiftUI and add platform-specific features.

### Overview
If you’re new to visionOS, start with a new Xcode project to learn about the platform features, and to familiarize yourself with visionOS content and techniques. When you build an app for visionOS, SwiftUI is an excellent choice because it gives you full access to visionOS features. Although you can also use UIKit to build portions of your app, you need to use SwiftUI for many features that are unique to the platform.

<img src="https://docs-assets.developer.apple.com/published/29e2a80ca6ad96afd67faa64fbd11014/multiple-apps-overview-poster.png"/>

In any SwiftUI app, you place content onscreen using scenes. A scene contains the views and controls to display onscreen. Scenes also define the appearance of those views and controls when they appear onscreen. In visionOS, you can include both 2D and 3D views in the same scene, and you can present those views in a window or as part of the person’s surroundings.

<img width="400" src="https://docs-assets.developer.apple.com/published/2128a03dea1096ca3ba51b13db64a4af/2D-window@2x.png" />  <img width="400" src="https://docs-assets.developer.apple.com/published/…6ed7edab76dc30986f976e45f/2D-and-3D-window@2x.png" />

A screenshot that shows a 2D window presented in a room that contains a couch and a lamp. The window shows the Destination Video sample app, showing three featured tiles. Each tile contains a poster photo, a title, and descriptive text.
Scene with a window

A screenshot of the Happy Beam app that shows a 2D window and 3D objects in a room that contains a couch, a lamp, and a plant. The 2D window shows the game’s current score, volume controls, and a pause button. Three 3D cloud objects are positioned at different depths from the player. 
Scene with a window and 3D objects

Start with a new Xcode project and add features to familiarize yourself with visionOS content and techniques. Run your app in Simulator to verify your content looks like you expect, and run it on device to see your 3D content come to life.

Organize your content around one or more scenes, which manage your app’s interface. Each scene contains the views and controls you want to display, and the scene type determines whether your content adopts a 2D or 3D appearance. SwiftUI adds 3D scene types specifically for visionOS, and also adds 3D elements and layout options for all scene types.
