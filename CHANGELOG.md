# Changelog

All notable changes to TCOC (True Camera-Oriented Controls) are documented here.

## [1.1.0]
- Added optional gamepad sprint steering: the camera now follows V as you steer left or right while sprinting. Enabled by default, with an adjustable steering speed in the CET overlay.

## [1.0.10]
- Added a configurable radial deadzone for gamepad movement in the CET window.
- Changed default radial deadzone value to 0.50.

## [1.0.9]
- Improved slow-walking animations when using a controller, with footsteps now better matching V's actual movement speed.
- Improved controller movement responsiveness near the center of the analog stick.
- Fixed V shifting sideways while turning, resulting in smoother and more natural direction changes.
- Special thanks to meanero, who shared controller-focused improvements and tuning work that helped make this update possible.

## [1.0.8]
- Fixed NPC dialogue/voice reactions no longer playing in third person.

## [1.0.7]
- Fixed TPP-to-FPP transitions being interrupted by TCOC's spatial-audio handling (introduced in 1.0.6). ITP now retains full control over FPP camera restoration while camera-oriented 3D audio remains enabled in TPP.

## [1.0.6]
- Spatial audio now follows the active camera in third person.

## [1.0.5]
- Fixed V performing a full 360° turn when resuming movement after orbiting the camera while idle.
- Body realignment and TCOC visual rotation are now coordinated in world space.
- V can continue moving in the previous world direction without unnecessary rotation, regardless of the retained idle orientation.

## [1.0.4]
- TCOC head and eye tracking now respects Immersive Third Person's "Head follows camera" setting.

## [1.0.3]
- Head and eye camera tracking now works while idling in every TCOC orientation.
- Made camera tracking smooth and responsive with natural follow lag.
- Fixed head snapping in the opposite direction when the camera leaves the tracking range.
- Fixed V turning toward the camera when descending ladders.

## [1.0.2]
- Improved character rotation responsiveness when using a controller.
- Added adaptive rotation blending: small stick movements remain immediate, while sharp direction changes use a short smooth transition.

## [1.0.1]
- Updated for ITP 1.2.0, including V's new relaxed shoulder posture.
- Fully reworked dash animation orientation: forward dashes now correctly follow the direction of travel; backward cartwheel dashes now correctly face away from the direction of travel.

## [1.0.0]
- Initial release.
