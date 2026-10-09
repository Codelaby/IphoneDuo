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
<p><a href="https://youtu.be/f_vus4iJGXo"><img width="380" src="assets/EvenColumns.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/event-columns-171868372"><b>Even Columns Responsive Grid for iphoneDuo, ipad, iphone</b></a></p>
<p>This code creates a flexible screen design (layout) that automatically changes how items are displayed based on your device's screen size or fold state (like on foldable phones).</p>
</td>
<td width="50%" valign="top">
<p><a href="https://www.youtube.com/watch?v=02OHXuOGkSg"><img width="380" src="assets/aspectRatioCard.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/flexible-aspect-171589892"><b>Flexible Aspect Ratio Cards</b></a></p>
<p>Showcase horizontal collections of card components with dynamic aspect ratios across three layout approaches.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><a href="https://youtu.be/VrQ4gnnQta4"><img width="380" src="assets/compatArragement.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/compatarrangemen-171474092"><b>CompatArrangementView</b></a></p>
<p>This code creates a smart, flexible screen layout that automatically rearranges content to fit different screen sizes, orientations, and folding devices (like dual-screen or foldable phones).</p>
</td>
<td width="50%" valign="top">
<p><a href="https://youtu.be/M9QVo5TiOOo"><img width="380" src="assets/customHingedLayout.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/custom-hinged-171198337"><b>Custom Hinged Layout</b></a></p>
<p>The code implements a hinged/dual-screen layout system in SwiftUI designed for foldable devices (such as dual-screen hardware exposing reserved regions via GeometryProxy). It splits collection items dynamically across two display pages (primary and secondary) separated by a hinge/fold division.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><a href="https://youtu.be/hlxhZ9Q9ayU"><img width="380" src="assets/arragementViewSplit.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/about-for-170781766"><b>About ArrangementView</b></a></p>
<p>This file demonstrates the usage of Apple's ArrangementView API</p>
</td>
<td width="50%" valign="top">
<p><a href="https://youtu.be/ub_35MKoohE"><img width="380" src="assets/reservedRegionsInfo.png"></a></p>
<p><a href="https://www.patreon.com/Codelaby/posts/detecting-on-duo-170278132"><b>Detecting Reserved Regions</b></a></p>
<p>This SwiftUI view (ReservedRegionsInfo) uses a GeometryReader to query and render screen cutouts and physical device boundaries:</p>
</td>
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
