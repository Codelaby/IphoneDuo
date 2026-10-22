<p align="center">
  <img src="assets/iphoneduoIcon.png" width="128" alt="iPhone Duo by Examples icon">
</p>

# IphoneDuo Examples
SwiftUI examples for the iPhone Duo (foldable iPhone) APIs in iOS 27.1: hinge, reserved regions, ArrangementView, vertical toolbar

<p align="center">
  <img src="https://img.shields.io/badge/iOS-27.1+-blue.svg" alt="iOS 27.1+">
  <img src="https://img.shields.io/badge/Xcode-27.1+-blue.svg" alt="Xcode 27.1+">
  <img src="https://img.shields.io/badge/Swift-6-orange.svg" alt="Swift 6">
  <img src="https://img.shields.io/badge/UI-SwiftUI-purple.svg" alt="SwiftUI">
</p>

## Technology

This project is built with native Apple technologies for iPhone Duo:

- **Swift 6** and **SwiftUI**, using the iOS 27.1 SDK and Xcode 27.1.
- **Swift Charts** for the hinge-angle history example.
- **iPhone Duo SwiftUI APIs** including `onHingeChange`, reserved regions, `ArrangementView`, the vertical bar toolbar APIs, container content margins, and geometry-driven adaptivity.
- **SwiftUI-first architecture** with no UIKit examples, so every sample stays focused on the APIs and layout behavior available to SwiftUI.

## Getting Started

**Requirements:** Xcode 27.1 or later, and the iPhone Duo simulator (iOS 27.1) or an iPhone Duo.

Custom Hinged Layout
## Examples
<table>
<tr>
<td width="50%" valign="top">
<p><a href="https://youtu.be/jzy1F79sUsA"><img width="380" src="assets/cardboardMasonry.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/adaptive-masonry-173093839"><b>Adaptive Masonry Layout</b></a></p>
<p>Responsive masonry grid layout that dynamically adjusts its columns, spacing, and fold-aware gaps.</p>
</td>
<td width="50%" valign="top">
<p><a href="https://youtu.be/xrk41YqegAY"><img width="380" src="assets/ArticleCoverViewIphoneDuo.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/adaptive-article-172973880"><b>Adaptive Article Layout in SwiftUI for Foldable Devices</b></a></p>
<p>A flexible generic layout container accepting three separate content builders—Cover, Primary, and Secondary—with customizable spacing, axis orientation, and split ratios.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><a href="https://youtu.be/pWo1jNaxYLc"><img width="380" src="assets/welcomeScreenDuo.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/dual-screen-in-172435098"><b>Adaptive Welcome Screen</b></a></p>
<p>An adaptive welcome screen that adjusts its layout to the available space and device configuration.</p>
</td>
<td width="50%" valign="top">
<p><a href="https://youtu.be/f_vus4iJGXo"><img width="380" src="assets/EvenColumns.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/event-columns-171868372"><b>Adaptive Column Grid</b></a></p>
<p>A flexible grid that adjusts its column count and spacing across iPhone, iPad, and dual-screen layouts.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><a href="https://www.youtube.com/watch?v=02OHXuOGkSg"><img width="380" src="assets/aspectRatioCard.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/flexible-aspect-171589892"><b>Dynamic Aspect-Ratio Cards</b></a></p>
<p>Explores three approaches to arranging horizontal card collections with flexible aspect ratios.</p>
</td>
<td width="50%" valign="top">
<p><a href="https://youtu.be/VrQ4gnnQta4"><img width="380" src="assets/compatArragement.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/compatarrangemen-171474092"><b>Adaptive Arrangement</b></a></p>
<p>Demonstrates how to adapt content arrangement to changing screen sizes, orientations, and device configurations.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><a href="https://youtu.be/M9QVo5TiOOo"><img width="380" src="assets/customHingedLayout.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/custom-hinged-171198337"><b>Hinge-Aware Layout</b></a></p>
<p>Splits collection content across two display regions using GeometryProxy reserved regions to account for the device hinge.</p>
</td>
<td width="50%" valign="top">
<p><a href="https://youtu.be/hlxhZ9Q9ayU"><img width="380" src="assets/arragementViewSplit.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/about-for-170781766"><b>Exploring ArrangementView</b></a></p>
<p>Explores Apple's ArrangementView API and its role in building layouts that adapt to different display configurations.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><a href="https://youtu.be/ub_35MKoohE"><img width="380" src="assets/reservedRegionsInfo.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/detecting-on-duo-170278132"><b>Inspecting Reserved Regions</b></a></p>
<p>Visualizes device boundaries, cutouts, and reserved display regions using GeometryProxy.</p>
</td>
<td width="50%" valign="top">
<p><a href="https://youtu.be/cHCu9TRDkBE"><img width="380" src="assets/DevicePoseDetector.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/swiftui-device-172521489"><b>Device Pose Detection</b></a></p>
<p>Detects device posture and orientation to help layouts respond to different usage configurations across supported devices.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><a href="https://youtu.be/Y3jZYfE4DWo"><img width="380" src="assets/LargestCornerDetector.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/largest-corner-172876051"><b>Largest Corner Detector</b></a></p>
<p>Analyzes container corner insets and geometry to detect the largest corner region, adapting perimetral layouts for foldable or dual-screen devices.</p>
</td>
<td width="50%" valign="top"></td>
</tr>
</table>



## See Also

Apps and games built for iPhone Duo, where folding the device is the whole point.

<table>
<tr>
<td width="80"><a href="https://github.com/artemnovichkov/Accorduon"><img width="64" src="https://raw.githubusercontent.com/artemnovichkov/Accorduon/main/.github/images/icon.png"></a></td>
<td><a href="https://github.com/artemnovichkov/Accorduon"><b>Accorduon</b></a><br>An accordion where the hinge is the bellows. Fold and unfold to play.</td>
</tr>
<tr>
<td width="80"><a href="https://github.com/artemnovichkov/SandValley"><img width="64" src="https://raw.githubusercontent.com/artemnovichkov/SandValley/main/.github/images/icon.png"></a></td>
<td><a href="https://github.com/artemnovichkov/SandValley"><b>SandValley</b></a><br>Pour sand on the screen and fold the device to make it slide into the valley.</td>
</tr>
<tr>
<td width="80"><a href="https://github.com/artemnovichkov/Duogami"><img width="64" src="https://raw.githubusercontent.com/artemnovichkov/Duogami/main/.github/images/icon.png"></a></td>
<td><a href="https://github.com/artemnovichkov/Duogami"><b>Duogami</b></a><br>An origami workshop. Fold the phone to fold the paper, one crease at a time.</td>
</tr>
<tr>
<td width="80"><a href="https://github.com/artemnovichkov/ClawKit"><img width="64" src="https://raw.githubusercontent.com/artemnovichkov/ClawKit/main/.github/images/icon.png"></a></td>
<td><a href="https://github.com/artemnovichkov/ClawKit"><b>ClawKit</b></a><br>A clay claw machine. The cabinet stands above the fold, the controls sit below it.</td>
</tr>
<tr>
<td width="80"><a href="https://github.com/artemnovichkov/DuoBird"><img width="64" src="https://raw.githubusercontent.com/artemnovichkov/DuoBird/main/.github/images/icon.png"></a></td>
<td><a href="https://github.com/artemnovichkov/DuoBird"><b>DuoBird</b></a><br>Flappy Bird played with the hinge. Snap the device open to flap through the pipes.</td>
</tr>
<tr>
<td width="80"><a href="https://github.com/artemnovichkov/DuoCut"><img width="64" src="https://raw.githubusercontent.com/artemnovichkov/DuoCut/main/.github/images/icon.png"></a></td>
<td><a href="https://github.com/artemnovichkov/DuoCut"><b>DuoCut</b></a><br>The fold is a blade. Slide shapes under it and cut them in half.</td>
</tr>
</table>

## Resources

- [Get Ready for iPhone Duo](https://developer.apple.com/iphone-duo/)
- [Preparing your app for iPhone Duo](https://developer.apple.com/documentation/technologyoverviews/preparing-your-app-for-iphone-duo)
- [Designing for iPhone Duo](https://developer.apple.com/design/human-interface-guidelines/designing-for-iphone-duo) in the Human Interface Guidelines
- Tech Talks:
  - [Prepare your app for iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111461/)
  - [Raise the bar with iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111462/)
  - [Strike a pose with adaptive layouts on iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111463/)
  - [Leverage multiple displays and scenes on iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111464/)
  - [Design for iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111466/)
 
## More info
[Repository based for this iPhoneDuo Adaptative](https://github.com/hoangchungk53qx1/iPhone-Duo-Adaptive/tree/main)
