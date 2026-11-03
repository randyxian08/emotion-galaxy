<div align="center">

<h1>Emotion Galaxy</h1>

<p><b>A journey through four planets, each one a small practice for your mental health.</b></p>

<p>
<img alt="Swift Student Challenge 2025 Distinguished Winner" src="https://img.shields.io/badge/Swift_Student_Challenge_2025-Distinguished_Winner-F05138?style=flat-square&logo=apple&logoColor=white">
<img alt="iPadOS 18" src="https://img.shields.io/badge/iPadOS-18-111111?style=flat-square">
<img alt="Swift 6" src="https://img.shields.io/badge/Swift-6-F05138?style=flat-square&logo=swift&logoColor=white">
</p>

<p>
<a href="https://apps.apple.com/app/emotiongalaxy/id6744534726"><b>App Store</b></a>
&nbsp;·&nbsp;
<a href="https://www.youtube.com/watch?v=_qZ94zRjrqs"><b>Demo video</b></a>
&nbsp;·&nbsp;
<a href="https://randyxian.com/blog/emotion-galaxy"><b>Write-up</b></a>
</p>

<img src="docs/menu-complete.jpg" alt="Emotion Galaxy journey menu with all four planets completed" width="860">

</div>

<br>

Feelings are hard to talk about because they have no shape. Planets have one.

Emotion Galaxy turns four practices that therapists use into four planets you visit in order. Each planet runs on
the Apple framework that makes its practice possible, and finishing one unlocks the next, so the whole thing plays
like a short game with an ending.

## Planets

<table>
<tr>
<td width="50%" valign="top"><img src="docs/venus-guide.jpg" alt="Venus guide screen"><br><br><b>Venus</b>: smile and hold it for two seconds.<br><sub>Vision · AVFoundation</sub></td>
<td width="50%" valign="top"><img src="docs/artistic-planet.jpg" alt="A planet textured with the user's drawings"><br><br><b>Artistic</b>: four drawings become the surface of your own planet.<br><sub>PencilKit · Create ML · SceneKit</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="docs/demo-oceanus.jpg" alt="Neptune placed on a real floor in AR"><br><br><b>Oceanus</b>: Neptune lands in your room. Breathe in 3, hold 5, out 6.<br><sub>ARKit · RealityKit</sub></td>
<td width="50%" valign="top"><img src="docs/andromeda-chat.jpg" alt="Andromeda conversation"><br><br><b>Andromeda</b>: say how you feel; an on-device model reads the emotion.<br><sub>Create ML · Core ML</sub></td>
</tr>
</table>

## Built with AI

Built in three weeks, February 2025, with no prior ARKit, RealityKit or Create ML experience.

**100% of the code was written by Claude 3.5 Sonnet in Cursor.** The idea, the design of each planet, the
training data for both Core ML models and the testing on a real iPad were mine. The commit history is kept as it
was during the challenge.

## Run it

Open `EmotionGalaxy.swiftpm` in Xcode 16+ or Swift Playgrounds on iPad, then run on iPadOS 18.
The camera, sketch classifier and AR need a real device.

<br>

<div align="center"><sub><a href="https://randyxian.com">Randy Xian</a></sub></div>
