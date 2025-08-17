# Changelog
## [1.1.2] - 2025-07-17

### Added
* Support for APP_UI_EDITOR_ONLY
* QuillSettings with the ability to filter what cameras render

### Fixed
* Physics drawer capsule rotation

## [1.1.1] - 2025-04-26

### Changed
* Updated Anchor support to 1.2.0

### Documentation
* Clarified Circle drawer documentation

## [1.1.0] - 2025-03-29

### Changed
* Updated to Anchor 1.1.1
* Updated to Core 1.4.1 (requires entities 1.4.X)

### Fixed
* Improved a lot of safety in the back end for users
* Compile errors if Unity.Physics is missing
* Modifying in flight GraphicsBuffers
* Shaders broken in URP builds
* Missing conditionals on Text variations
* Release builds

## [1.0.2] - 2025-03-14

### Changed
* If using Anchor, now depends on 1.1.0
* Updated toolbar with new Anchor features
    * Reduced allocations
    * State is now saved between sessions
* Updated shaders to HLSL
* Text shader reworked

### Fixed
* Incorrectly sharing GraphicsBuffer between multiple cameras 

## [1.0.1] - 2025-03-09

### Added
* DrawEditor which provides the Update event for a simple way to draw in editor without having to create your own FrameUtility.

### Fixed
* A cleanup error that could occur when using URP.

### Documentation
* DrawEditor documentation and sample.
* Added Configuration section to read me.

## [1.0.0] - 2025-03-03

### Added
* Initial release.