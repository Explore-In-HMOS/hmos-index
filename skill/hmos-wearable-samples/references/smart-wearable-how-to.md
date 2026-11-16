# Smart Wearable how-to projects (ArkTS)

271 projects. Each entry: what it demonstrates, the distinctive HarmonyOS kits or system modules it uses, its GitHub topics, the SDK version and the repository URL. Every entry starts with `### <repo-name>`, so search this file for a keyword, kit or topic instead of reading it top to bottom.

## Contents

- [Sensors and Health](#sensors-and-health-sensors-and-health) (23)
- [Location and Maps](#location-and-maps-location-and-maps) (29)
- [Media and Audio](#media-and-audio-media-and-audio) (29)
- [Connectivity and Network](#connectivity-and-network-connectivity-and-network) (33)
- [Background and Notifications](#background-and-notifications-background-and-notifications) (16)
- [Data and Storage](#data-and-storage-data-and-storage) (25)
- [UI and Interaction](#ui-and-interaction-ui-and-interaction) (116)

## Sensors and Health (`sensors-and-health`)

### how-to-build-3d-watch-face-development
Procedural 3D watch-face rendering sample for HarmonyOS with animated clock hands and wrist-tilt lighting using ArkGraphics3D and watch sensors.
Kits: ArkGraphics3D, SensorServiceKit. Topics: 3d-graphics, arkgraphics3d, sensors, watch-face. URL: https://github.com/Explore-In-HMOS/how-to-build-3d-watch-face-development

### how-to-build-concurrent-lru-cache
Concurrent sensor cache sample for HarmonyOS watches using SendableLruCache, ArkTS locks, ASON serialization and worker-based data exchange.
Kits: SensorServiceKit. Topics: concurrency, lru-cache, sensors, serialization. URL: https://github.com/Explore-In-HMOS/how-to-build-concurrent-lru-cache

### how-to-build-gesture-engine
Multimodal photo viewer codelab for HarmonyOS watches combining pinch/rotation gestures, swipe navigation, hardware buttons and accelerometer input.
Kits: InputKit, SensorServiceKit. Topics: accelerometer, gesture-recognition, image-viewer. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-gesture-engine

### how-to-build-urpc-health-reporter
URPC health reporting sample for HarmonyOS watches combining live heart-rate and step readings into snapshots for Remote Communication Kit transfer.
Kits: RemoteCommunicationKit, SensorServiceKit. Topics: health-data, heart-rate, remote-communication-kit, urpc. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-build-urpc-health-reporter

### how-to-get-heart-rate-with-sensorkit
Heart-rate sensor codelab for HarmonyOS watches with live Sensor Service Kit readings sent to a paired phone app via Wear Engine.
Kits: SensorServiceKit, WearEngine. Topics: heart-rate, sensors, wear-engine. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-get-heart-rate-with-sensorkit

### how-to-handle-multimodal-gestures
Multimodal input codelab for HarmonyOS watches combining touch pan, digital crown rotation and accelerometer wrist tilt with per-frame updates.
Kits: ArkData, ArkGraphics2D, SensorServiceKit. Topics: accelerometer, digital-crown, display-sync, gestures, input-handling, sensor-service-kit. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-handle-multimodal-gestures

### how-to-implement-adaptive-haptics
Adaptive haptics codelab for HarmonyOS watches that checks preset vibration support and falls back to timed vibrations and composite patterns.
Kits: SensorServiceKit. Topics: haptic-feedback, haptics, sensor-service-kit, vibrator. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-implement-adaptive-haptics

### how-to-implement-realtime-inclinometer
Realtime inclinometer codelab for HarmonyOS watches fusing accelerometer and gyroscope data with a complementary filter for pitch and roll.
Kits: SensorServiceKit. Topics: accelerometer, gyroscope, inclinometer, sensor-fusion, sensor-service-kit, sensors. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-implement-realtime-inclinometer

### how-to-implement-sun-exposure-risk
Sun exposure risk codelab for HarmonyOS watches fusing ambient light and temperature sensors into a tiered score with haptic alerts.
Kits: SensorServiceKit. Topics: ambient-light, health, sensor-fusion, sensor-service-kit, temperature-sensor, vibrator. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-implement-sun-exposure-risk

### how-to-make-compass-app
Compass sample for HarmonyOS watches calculating azimuth from rotation-vector sensor data and rotating the compass display in real time.
Kits: SensorServiceKit. Topics: compass, rotation-vector, sensor-service-kit, sensors. URL: https://github.com/Explore-In-HMOS/how-to-make-compass-app

### how-to-make-fitness-tracker
Interval training timer sample for HarmonyOS with configurable work/rest periods, round indicators and start/pause/reset controls.
Kits: core ArkUI/Ability kits only. Topics: fitness, interval-training, timer. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-make-fitness-tracker

### how-to-make-pulse-animation-console
Pulse-animation console sample for HarmonyOS watches with start/pause interaction, BPM/FPS displays and configurable appearance controls.
Kits: core ArkUI/Ability kits only. Topics: animation, performance-monitoring. SDK: HarmonyOS 6.0.1. URL: https://github.com/Explore-In-HMOS/how-to-make-pulse-animation-console

### how-to-make-pulse-ring
Animator pulse-ring sample for HarmonyOS watches with tap-to-pause control, selectable colors and light/dark themes for breathing or focus sessions.
Kits: core ArkUI/Ability kits only. Topics: animation, breathing-exercises, theming. URL: https://github.com/Explore-In-HMOS/how-to-make-pulse-ring

### how-to-make-smart-lux
Ambient light sensor sample for HarmonyOS with live lux readings, adaptive UI themes and background monitoring using Sensor Service Kit.
Kits: BackgroundTasksKit, SensorServiceKit. Topics: background-tasks, light-sensor, sensors, theming. SDK: HarmonyOS SDK 5.1.0. URL: https://github.com/Explore-In-HMOS/how-to-make-smart-lux

### how-to-make-sweet-match
Match-3 candy game for HarmonyOS watches with swipe and tap swaps, cascading combos, auto reshuffle and a score progress ring.
Kits: CryptoArchitectureKit, SensorServiceKit. Topics: animation, game, gestures, match-3, puzzle-game, vibrator. SDK: HarmonyOS SDK 6.0.2(22). URL: https://github.com/Explore-In-HMOS/how-to-make-sweet-match

### how-to-make-wrist-fishing
Wrist-flick fishing game codelab for HarmonyOS watches detecting upward pulls from accelerometer and gyroscope data with Canvas and haptics.
Kits: SensorServiceKit. Topics: canvas, game, gesture-detection, haptics, sensor-service-kit, sensors. SDK: HarmonyOS SDK 6.0.2(22). URL: https://github.com/Explore-In-HMOS/how-to-make-wrist-fishing

### how-to-show-heart-rate-with-body-sensor
Live heart-rate display sample for HarmonyOS watches using Sensor Service Kit, body-sensor permissions and sensor event subscriptions.
Kits: SensorServiceKit. Topics: heart-rate, permissions, sensor-service-kit, sensors. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-show-heart-rate-with-body-sensor

### how-to-use-build-variant
Product-based build variant sample for HarmonyOS watches using free/paid build profiles to control features in a step-counter app.
Kits: core ArkUI/Ability kits only. Topics: build-variants, hvigor, step-counter. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-build-variant

### how-to-use-magnetometer
Magnetometer sample for HarmonyOS watches displaying magnetic field strength, interference status and figure-eight calibration guidance.
Kits: SensorServiceKit. Topics: magnetic-field, magnetometer, sensors. SDK: HarmonyOS SDK 5.1.1(19). URL: https://github.com/Explore-In-HMOS/how-to-use-magnetometer

### how-to-use-particle-for-breath-exercises
Particle animation sample for HarmonyOS watches visualizing inhale/exhale cycles with expanding and contracting particles for guided breathing.
Kits: core ArkUI/Ability kits only. Topics: breathing-exercises, particle-animation. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-use-particle-for-breath-exercises

### how-to-use-qr-health-login-standalone
Standalone watch app that signs in to Health Kit with a QR code using the OAuth 2.0 Device Code flow and reads step data without a backend.
Kits: ArkData, ImageKit, NetworkKit, ScanKit. Topics: account-kit, device-code-flow, health-kit, oauth2, qr-code, scan-kit, step-counter. URL: https://github.com/Explore-In-HMOS/how-to-use-qr-health-login-standalone

### how-to-use-sensorkit-in-wearable
Sensor and haptics showcase for HarmonyOS watches with capability detection, permission handling, live readings and configurable vibration patterns.
Kits: LocalizationKit, SensorServiceKit. Topics: device-capabilities, haptics, sensor-service-kit, sensors. URL: https://github.com/Explore-In-HMOS/how-to-use-sensorkit-in-wearable

### how-to-use-wear-detection-for-workout
Wear detection codelab for HarmonyOS watches rejecting heart rate samples off the wrist and auto-pausing workouts with the WEAR_DETECTION sensor.
Kits: CryptoArchitectureKit, SensorServiceKit. Topics: fitness, heart-rate, sensor-service-kit, vibrator, wear-detection, workout-tracker. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-use-wear-detection-for-workout

## Location and Maps (`location-and-maps`)

### how-to-build-ability-start
Ability Kit launch and deep-link routing sample for HarmonyOS watches, using mock target abilities to demonstrate launch options and returned results.
Kits: core ArkUI/Ability kits only. Topics: deep-linking, navigation. URL: https://github.com/Explore-In-HMOS/how-to-build-ability-start

### how-to-build-advanced-map-overlays
Advanced Map Kit overlays for HarmonyOS watches with custom arcs, animated route traces, dynamic markers and map interaction events.
Kits: MapKit. Topics: map-kit, map-overlays, maps, route-animation. URL: https://github.com/Explore-In-HMOS/how-to-build-advanced-map-overlays

### how-to-build-coordinate-toolkit
Offline coordinate conversion sample for HarmonyOS watches using synchronous and asynchronous WGS84-to-GCJ02 conversion and distance calculations.
Kits: MapKit. Topics: coordinates, gcj02, map-kit, wgs84. SDK: HarmonyOS SDK 5.1.0(21). URL: https://github.com/Explore-In-HMOS/how-to-build-coordinate-toolkit

### how-to-build-custom-tile-layers
Custom map-layer sample for HarmonyOS watches using Map Kit TileOverlay, geographic overlays and touch/digital crown navigation with MVVM.
Kits: MapKit. Topics: digital-crown, map-kit, map-overlays, map-tiles. URL: https://github.com/Explore-In-HMOS/how-to-build-custom-tile-layers

### how-to-build-heat-map-explorer
Map visuals sample for HarmonyOS watches with heat zones, location-centered overlays, route tracking and point-of-interest markers using Map Kit.
Kits: CryptoArchitectureKit, LocationKit, MapKit. Topics: data-visualization, geolocation, heatmap, map-kit. URL: https://github.com/Explore-In-HMOS/how-to-build-heat-map-explorer

### how-to-build-location-utility-toolkit
Locale formatting preview codelab for HarmonyOS watches using Intl date, currency and plural rules with Localization Kit sendableResourceManager.
Kits: LocalizationKit. Topics: internationalization, locale, localization, localization-kit. URL: https://github.com/Explore-In-HMOS/how-to-build-location-utility-toolkit

### how-to-build-map-animation-studio
Map Kit marker animation studio for HarmonyOS watches with interactive rotation, scaling, movement and combined animations plus playback controls.
Kits: ImageKit, MapKit. Topics: animation, map-kit, map-markers. URL: https://github.com/Explore-In-HMOS/how-to-build-map-animation-studio

### how-to-build-map-camera-zoom
Map camera control codelab for HarmonyOS watches with animated location changes, multi-point framing, zoom and digital crown interaction.
Kits: MapKit. Topics: digital-crown, map-camera, map-kit, maps. URL: https://github.com/Explore-In-HMOS/how-to-build-map-camera-zoom

### how-to-build-map-geofence-runner
Location-aware running codelab for HarmonyOS watches using Map Kit nearby-place search and routing with Location Kit background geofence triggers.
Kits: CryptoArchitectureKit, LocationKit, MapKit. Topics: geofencing, location-kit, map-kit, running. SDK: HarmonyOS NEXT SDK (API 12+). URL: https://github.com/Explore-In-HMOS/how-to-build-map-geofence-runner

### how-to-build-map-overlay-config
Map overlay codelab for HarmonyOS watches using simulated hiking positions, waypoint annotations and polygon proximity checks without GPS access.
Kits: MapKit. Topics: geospatial, hiking, map-kit, map-overlays. URL: https://github.com/Explore-In-HMOS/how-to-build-map-overlay-config

### how-to-build-multinav
Multi-stack navigation codelab for HarmonyOS watches using MultiNavPathStack, MultiNavigation and named routes with independent back-stack histories.
Kits: core ArkUI/Ability kits only. Topics: atomic-services, navigation. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-build-multinav

### how-to-build-plugin-routing-framework
Plugin-based component routing sample for HarmonyOS watches with runtime widget registration, ContentSlot/BuilderNode injection and circular layouts.
Kits: ArkWeb. Topics: mvvm, navigation, plugin-architecture. SDK: HarmonyOS SDK 6.1.1 (API 24). URL: https://github.com/Explore-In-HMOS/how-to-build-plugin-routing-framework

### how-to-build-poi-cluster-map
POI clustering codelab for HarmonyOS watches using Map Kit mass-point and cluster overlays with tap metadata and custom marker info windows.
Kits: MapKit. Topics: map-kit, maps, marker-clustering, points-of-interest. URL: https://github.com/Explore-In-HMOS/how-to-build-poi-cluster-map

### how-to-build-round-form-navigator-and-paste-button
Round-screen task navigation sample for HarmonyOS watches with multi-step workflows, circular progress indicators and clipboard interactions.
Kits: core ArkUI/Ability kits only. Topics: clipboard, navigation. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-build-round-form-navigator-and-paste-button

### how-to-build-route-tracker
Map route codelab for HarmonyOS watches showing current location, a tap-to-set destination marker, route polyline and camera zoom with Map Kit.
Kits: LocationKit, MapKit. Topics: location-kit, map-kit, maps, polyline. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-build-route-tracker

### how-to-build-trakinggo-on-harmonyos
Background route tracking sample for HarmonyOS watches using Map Kit and Location Kit, with start/stop markers, elapsed time and distance measurement.
Kits: ArkData, LocationKit, MapKit. Topics: background-tasks, location-kit, map-kit, route-tracking. URL: https://github.com/Explore-In-HMOS/how-to-build-trakinggo-on-harmonyos

### how-to-convert-address-and-cluster
Map Kit codelab for HarmonyOS watches with reverse geocoding of coordinates into addresses, POIs and AOIs plus marker cluster events.
Kits: MapKit. Topics: map-kit, maps, marker-clustering, reverse-geocoding. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-convert-address-and-cluster

### how-to-create-mapcircle-depends-with-current-location
Location-following map circle sample for HarmonyOS phones and watches, with permission handling, configurable radius and live position updates.
Kits: LocationKit, MapKit. Topics: geolocation, location-kit, map-kit, map-overlays. SDK: HarmonyOS 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-create-mapcircle-depends-with-current-location

### how-to-create-radial-menu
Radial menu codelab for HarmonyOS watches with button-triggered circular navigation and compact quick-access controls using ArkUI.
Kits: core ArkUI/Ability kits only. Topics: navigation, radial-menu. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-create-radial-menu

### how-to-display-place-details-on-map
Map Kit starter sample for HarmonyOS displaying a predefined location and titled marker without live GPS, search or dynamic data fetching.
Kits: MapKit. Topics: map-kit, map-markers, maps. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-display-place-details-on-map

### how-to-display-route-with-markers
Route visualization sample for HarmonyOS watches drawing a route between two predefined map markers without live GPS data.
Kits: MapKit. Topics: map-kit, map-markers, route-visualization. URL: https://github.com/Explore-In-HMOS/how-to-display-route-with-markers

### how-to-implement-routing
Map Kit route-drawing codelab for HarmonyOS with start/end markers, MapArcParams and map controller callbacks.
Kits: LocationKit, MapKit. Topics: map-kit, map-markers, map-overlays. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-implement-routing

### how-to-integrate-map-kit
Map Kit integration codelab for HarmonyOS watches with MVVM, map type switching, animated camera moves, tap coordinates and map screenshots.
Kits: ImageKit, MapKit. Topics: image-kit, map-kit, maps, mvvm. URL: https://github.com/Explore-In-HMOS/how-to-integrate-map-kit

### how-to-make-custom-marker-on-map
Map Kit custom-marker codelab for HarmonyOS watches demonstrating how to place customized markers on a map.
Kits: MapKit. Topics: map-kit, map-markers, maps. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-make-custom-marker-on-map

### how-to-make-following-app
Location-change monitoring demo for HarmonyOS watches with background tracking and vibration alerts when movement exceeds a distance threshold.
Kits: BackgroundTasksKit, LocationKit, MapKit. Topics: background-tasks, haptics, location. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-make-following-app

### how-to-manage-global-data-during-navigation
Navigation data sync codelab for HarmonyOS watches comparing globals, AppStorage, NavPathStack results and a route manager to avoid stale values.
Kits: core ArkUI/Ability kits only. Topics: appstorage, lifecycle, navigation, navpathstack, state-management. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-manage-global-data-during-navigation

### how-to-parse-gpx-file-for-third-party-map-api
GPX parsing codelab for HarmonyOS watches demonstrating route-coordinate extraction and visualization through a third-party map API.
Kits: core ArkUI/Ability kits only. Topics: gpx, maps, route-visualization, xml. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-parse-gpx-file-for-third-party-map-api

### how-to-properly-initialize-and-configure-map-kit
Map Kit setup codelab for HarmonyOS watches covering MapComponent initialization, city camera navigation and show/hide lifecycle handling.
Kits: MapKit. Topics: lifecycle, map-kit, maps, mvvm. URL: https://github.com/Explore-In-HMOS/how-to-properly-initialize-and-configure-map-kit

### how-to-show-user-location
Location Kit sample for HarmonyOS displaying current latitude and longitude with geoLocationManager and speed-priority location requests.
Kits: LocationKit. Topics: geolocation, gps, location-kit. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-show-user-location

## Media and Audio (`media-and-audio`)

### how-to-access-system-gallery-on-kids-watch
System gallery picker codelab for Huawei Kids Watch using Media Library Kit photoAccessHelper to select photos and videos without permissions.
Kits: MediaLibraryKit. Topics: gallery, kids-watch, media-library-kit, photo-picker. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-access-system-gallery-on-kids-watch

### how-to-build-animatable-transform
ArkUI animation playground for HarmonyOS watches with custom animatable properties, transforms, screen transitions and watch-face motion examples.
Kits: BackgroundTasksKit, CoreFileKit, ImageKit. Topics: animation, transforms, watch-face. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-animatable-transform

### how-to-build-crown-gesture-navigator
Gesture navigation codelab for HarmonyOS watches combining digital crown input, two-finger rotation and sequenced gestures for media controls.
Kits: AudioKit, CryptoArchitectureKit. Topics: digital-crown, gesture-recognition, media-controls. SDK: HarmonyOS SDK 6.0.1. URL: https://github.com/Explore-In-HMOS/how-to-build-crown-gesture-navigator

### how-to-build-haptic-coach
Rhythm coaching sample for HarmonyOS watches with synchronized audio/haptic cues, output-device routing and spatial-audio capability checks.
Kits: AudioKit. Topics: audio-kit, haptics, rhythm, spatial-audio. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-haptic-coach

### how-to-build-media-creation-studio
Media Kit codelab for HarmonyOS watches covering M4A voice recording, AVPlayer replay, video-frame extraction and custom-source playback.
Kits: AudioKit, CoreFileKit, CryptoArchitectureKit, ImageKit, LocalizationKit, MediaKit. Topics: audio-player, audio-recording, media-kit, video-processing. SDK: HarmonyOS SDK 6.0.1. URL: https://github.com/Explore-In-HMOS/how-to-build-media-creation-studio

### how-to-build-micro-poster-renderer
ArkGraphics2D rendering sample for HarmonyOS watches with a RenderNode poster pipeline, display-synchronized animation, gradients and shadows.
Kits: ArkGraphics2D, ImageKit. Topics: animation, arkgraphics2d, canvas, custom-rendering. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-build-micro-poster-renderer

### how-to-build-native-media-player
ArkWeb native video sample for HarmonyOS watches, connecting HTML video to AVPlayer through native handlers and XComponent rendering.
Kits: ArkWeb, MediaKit. Topics: arkweb, media-kit, native-video, webview. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-native-media-player

### how-to-build-photo-thumbnail-engine
Image Kit thumbnail sample for HarmonyOS watches covering round crops, rotation, scaling, metadata, packing and picture composition.
Kits: CoreFileKit, CryptoArchitectureKit, ImageKit, LocalizationKit. Topics: image-kit, image-processing, thumbnails. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-build-photo-thumbnail-engine

### how-to-build-podcast-player
Podcast player for HarmonyOS watches with local/URL audio, AVPlayer, metadata extraction, SoundPool feedback and system-event handling.
Kits: AudioKit, ImageKit, LocalizationKit, MediaKit, NetworkKit. Topics: audio-player, event-driven, media-kit, podcast. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-build-podcast-player

### how-to-build-screen-snapshot-tool
Component screenshot sample for HarmonyOS watches using ComponentScreenshot and overlay controls to capture selected UI components.
Kits: CoreFileKit, ImageKit, InputKit. Topics: image-kit, screenshots. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-screen-snapshot-tool

### how-to-build-visual-effects
Visual effects showcase for HarmonyOS watches with foreground blur, motion blur, image filters and composited rendering effects.
Kits: ArkGraphics2D, ImageKit. Topics: blur, image-processing, visual-effects. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-visual-effects

### how-to-build-voice-memo-recorder
Voice memo sample for HarmonyOS watches with on-watch recording, audio playback handling and management of saved recordings.
Kits: core ArkUI/Ability kits only. Topics: audio-player, audio-recording, voice-recorder. URL: https://github.com/Explore-In-HMOS/how-to-build-voice-memo-recorder

### how-to-build-volume-control-center
System volume dashboard for HarmonyOS watches with stream selection, live level controls and optional hardware loopback monitoring.
Kits: AudioKit. Topics: audio-kit, volume-control. URL: https://github.com/Explore-In-HMOS/how-to-build-volume-control-center

### how-to-build-watch-media-player-with-playback-control
Media player for HarmonyOS watches using AVPlayer and AVSession for metadata, playback state and controller-based transport actions.
Kits: AVSessionKit, AudioKit, ImageKit, MediaKit. Topics: audio-player, avsession, media-controls, media-kit. SDK: HarmonyOS SDK (API 20+). URL: https://github.com/Explore-In-HMOS/how-to-build-watch-media-player-with-playback-control

### how-to-capture-offscreen-screenshot
Off-screen snapshot codelab for HarmonyOS watches rendering an @Builder to PixelMap, saving it as JPEG and previewing it in a Scroll.
Kits: CoreFileKit, ImageKit. Topics: component-snapshot, image-kit, pixelmap, screenshot. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-capture-offscreen-screenshot

### how-to-convert-mediakit-units
Media Kit codelab for HarmonyOS watches converting millisecond and microsecond durations to extract video frames with AVImageGenerator.
Kits: ImageKit, LocalizationKit, MediaKit. Topics: frame-extraction, media-kit, video. URL: https://github.com/Explore-In-HMOS/how-to-convert-mediakit-units

### how-to-generate-qr-code
QR code generation sample for HarmonyOS using the built-in QRCode component and Scan Kit, with ArkTS examples for wearable interfaces.
Kits: ImageKit, ScanKit. Topics: qr-code, scan-kit. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-generate-qr-code

### how-to-handle-resource-cleanup-in-media-operations
Media cleanup codelab for HarmonyOS watches releasing AVPlayer, AVRecorder and file descriptors in every error path with try/finally.
Kits: AudioKit, CoreFileKit, MediaKit. Topics: avplayer, avrecorder, core-file-kit, error-handling, media-kit, resource-cleanup. URL: https://github.com/Explore-In-HMOS/how-to-handle-resource-cleanup-in-media-operations

### how-to-implement-camera-kit-on-kids-watch
Camera Kit codelab for Huawei Kids Watch using the cameraPicker system picker to take photos without requesting camera permission.
Kits: CameraKit. Topics: camera, camera-kit, camera-picker, kids-watch. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-implement-camera-kit-on-kids-watch

### how-to-implement-custom-image-based-swiper-indicators
Swiper codelab for HarmonyOS watches replacing default indicators with custom image dots overlaid via Stack and driven by swiper events.
Kits: core ArkUI/Ability kits only. Topics: page-indicator, swiper, ui-components. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-implement-custom-image-based-swiper-indicators

### how-to-implement-fft
Pure ArkTS radix-2 FFT codelab for HarmonyOS watches analysing live microphone audio with windowing, dBFS scaling and peak detection.
Kits: AudioKit. Topics: audio-kit, dsp, fft, signal-processing, spectrum-analyzer. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-implement-fft

### how-to-implement-peak-hold
Sound level meter codelab for HarmonyOS watches measuring microphone RMS in dBFS with EMA smoothing and peak hold on a round gauge.
Kits: AudioKit. Topics: audio-kit, dbfs, microphone, peak-hold, signal-processing, sound-level-meter. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-implement-peak-hold

### how-to-make-sound-wave
Canvas animation codelab for HarmonyOS watches generating simulated linear and circular sound-wave visualizations.
Kits: CryptoArchitectureKit. Topics: animation, audio-visualization, canvas. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-make-sound-wave

### how-to-play-videos-from-url
URL video playback sample for HarmonyOS with user-entered streaming URLs and basic play/pause controls.
Kits: core ArkUI/Ability kits only. Topics: streaming, video-player. URL: https://github.com/Explore-In-HMOS/how-to-play-videos-from-url

### how-to-record-audio-over-audio
Audio recording sample for HarmonyOS watches demonstrating playback and continuation of a previous recording.
Kits: AudioKit, CoreFileKit. Topics: audio-kit, audio-player, audio-recording. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-record-audio-over-audio

### how-to-record-voice
Minimal voice recorder sample for HarmonyOS with quick microphone recording and local voice-clip saving using ArkTS and ArkUI.
Kits: AudioKit, CoreFileKit, MediaKit. Topics: audio-recording, voice-recorder. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-record-voice

### how-to-share-resourcemanager-between-ability-and-components
ResourceManager sharing codelab for HarmonyOS watches passing the ability context to a singleton audio service with init guards and cleanup.
Kits: LocalizationKit, MediaKit. Topics: avplayer, lifecycle, rawfile, resource-manager, uiability. SDK: HarmonyOS SDK 6.0.1(21) compatibility. URL: https://github.com/Explore-In-HMOS/how-to-share-resourcemanager-between-ability-and-components

### how-to-use-image-effect
Image-filter sample for HarmonyOS watches with sepia, grayscale and color adjustments through a compact photo-effects interface.
Kits: ArkGraphics2D, ImageKit. Topics: image-filters, image-kit, image-processing. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-image-effect

### how-to-use-opuscodec
Opus codec codelab for HarmonyOS watches encoding and decoding live microphone audio via AVCodec NDK with AVPlayer and AVSession playback.
Kits: AVSessionKit, AudioKit, CoreFileKit, MediaKit. Topics: audio-codec, audio-kit, avcodec, avsession-kit, cpp, ndk, opus. SDK: HarmonyOS Stage Model, AVCodec NDK. URL: https://github.com/Explore-In-HMOS/how-to-use-opuscodec

## Connectivity and Network (`connectivity-and-network`)

### how-to-build-2d-path-engine
ArkGraphics2D path codelab for HarmonyOS watches with interactive stroke effects, path inspection and geometric transformations on a round screen.
Kits: ArkGraphics2D, ImageKit. Topics: arkgraphics2d, path-rendering, vector-graphics. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-2d-path-engine

### how-to-build-arkweb-native-bridge
ArkWeb bridge sample for HarmonyOS watches with two-way JavaScript/ArkTS messaging, custom URL schemes and simulated health-data tests.
Kits: ArkWeb. Topics: arkweb, interop, javascript-bridge, webview. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-arkweb-native-bridge

### how-to-build-bluetooth-device-dashboard
Bluetooth dashboard codelab for HarmonyOS watches: scan nearby devices, list paired ones and view A2DP, HFP, HID and PAN profile states.
Kits: ConnectivityKit. Topics: a2dp, bluetooth, connectivity-kit, device-discovery, hfp. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-build-bluetooth-device-dashboard

### how-to-build-bt-message-phonebook-bridge
Bluetooth phonebook/message bridge for HarmonyOS watches using SPP/RFCOMM, companion-phone communication and offline demo data.
Kits: ConnectivityKit. Topics: bluetooth, contacts, messaging, rfcomm. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-bt-message-phonebook-bridge

### how-to-build-network-usage-dashboard
Network diagnostics for HarmonyOS watches with metered status, certificate trust checks, mDNS discovery and traffic-counter availability.
Kits: ArkData, NetworkKit, NotificationKit. Topics: certificates, diagnostics, mdns, networking. SDK: HarmonyOS SDK 6.0.1. URL: https://github.com/Explore-In-HMOS/how-to-build-network-usage-dashboard

### how-to-build-nfc-access-badge
NFC reader-mode codelab for HarmonyOS watches with NDEF badge parsing, foreground registration, NFC-A diagnostics and deterministic demo scans.
Kits: ConnectivityKit. Topics: access-control, connectivity-kit, ndef, nfc. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-nfc-access-badge

### how-to-build-smart-push-dispatcher
Push Kit codelab for HarmonyOS watches that gets the push token and AAID, signs a service account JWT and sends notification messages.
Kits: CryptoArchitectureKit, ImageKit, LocalizationKit, NetworkKit, NotificationKit, PushKit. Topics: jwt, notification-kit, push-kit, push-notifications. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-smart-push-dispatcher

### how-to-build-web-download-manager
ArkWeb download manager codelab for HarmonyOS watches with queued web downloads, progress callbacks, item metadata and streamed response handling.
Kits: ArkWeb, BackgroundTasksKit. Topics: arkweb, download-manager, streaming, webview. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-build-web-download-manager

### how-to-build-web-file-keyboard
ArkWeb interaction codelab for HarmonyOS watches covering file selectors, keyboard control, context menus, cookies and form resubmission handling.
Kits: ArkWeb, CoreFileKit, IMEKit. Topics: arkweb, file-picker, keyboard, webview. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-build-web-file-keyboard

### how-to-build-web-permission-console
ArkWeb permissions/debugging sample for HarmonyOS watches covering geolocation, media requests, JavaScript dialogs, console logs and load errors.
Kits: ArkWeb. Topics: arkweb, debugging, permissions, webview. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-web-permission-console

### how-to-build-web-proxy-prefetcher
ArkWeb performance codelab for HarmonyOS watches with proxy configuration, page prefetching and back-forward cache capability checks.
Kits: ArkWeb. Topics: arkweb, caching, prefetching, proxy. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-build-web-proxy-prefetcher

### how-to-build-web-status-handler
ArkWeb status handling sample for HarmonyOS watches covering TLS errors, HTTP authentication, client certificates and web resource failures.
Kits: ArkWeb. Topics: arkweb, error-handling, http-authentication, tls. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-build-web-status-handler

### how-to-check-network-connection
Network connectivity monitoring sample for HarmonyOS watches with connection-status display and disconnection updates.
Kits: ConnectivityKit, NetworkKit, TelephonyKit. Topics: connectivity, network-monitoring, networking. SDK: HarmonyOS SDK 5.0.21(18). URL: https://github.com/Explore-In-HMOS/how-to-check-network-connection

### how-to-control-smart-lights-with-harmonyos-and-mqtt
MQTT smart-device control demo connecting HarmonyOS and Android through a HiveMQ broker, with two-way state sync for simulated lights.
Kits: core ArkUI/Ability kits only. Topics: android, hivemq, iot, mqtt, smart-home. URL: https://github.com/Explore-In-HMOS/how-to-control-smart-lights-with-harmonyos-and-mqtt

### how-to-control-with-bluetooth
Bluetooth LE lighting-control sample for HarmonyOS, showing device scanning, connection and on/off commands through BLE services and characteristics.
Kits: ConnectivityKit. Topics: bluetooth-low-energy, gatt, iot, smart-lighting. URL: https://github.com/Explore-In-HMOS/how-to-control-with-bluetooth

### how-to-create-tcp-server
TCP socket server codelab for HarmonyOS watches implementing a local HTTP echo server with on-screen request logging.
Kits: NetworkKit. Topics: http-server, networking, sockets, tcp. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-create-tcp-server

### how-to-implement-countly-analytics
Countly analytics codelab for HarmonyOS watches integrating the Countly SDK for session and view tracking, custom events and offline mode.
Kits: NetworkKit. Topics: analytics, countly, event-tracking, third-party-sdk. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-implement-countly-analytics

### how-to-implement-standalone-network-requests-background-tasks
Standalone networking codelab for HarmonyOS watches sending HTTP requests over Wi-Fi or cellular without the phone, with background sync.
Kits: ArkData, BackgroundTasksKit, NetworkKit. Topics: background-tasks-kit, continuous-task, http, network-kit, standalone, work-scheduler. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-implement-standalone-network-requests-background-tasks

### how-to-implement-tcp-connection
TCP socket connection codelab for HarmonyOS watches with user-entered peer IP addresses for communication between devices on the same network.
Kits: NetworkKit. Topics: networking, sockets, tcp. SDK: HarmonyOS 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-implement-tcp-connection

### how-to-initiate-phone-calls-with-telephony-kit
Telephony Kit codelab for HarmonyOS watches that opens the built-in dialer with makeCall and checks for a SIM card.
Kits: TelephonyKit. Topics: phone-call, sim, telephony-kit. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-initiate-phone-calls-with-telephony-kit

### how-to-make-booklist
Remote book-list sample for HarmonyOS using HTTP requests, dynamic ArkUI list rendering and interactive swipe actions.
Kits: RemoteCommunicationKit. Topics: http-client, lists, remote-communication-kit. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-make-booklist

### how-to-make-p2p-wifi-connection
Wi-Fi Direct sample for HarmonyOS demonstrating P2P group creation, host/client modes, peer discovery and connection-status feedback.
Kits: ConnectivityKit. Topics: device-discovery, networking, p2p, wifi-direct. SDK: HarmonyOS NEXT. URL: https://github.com/Explore-In-HMOS/how-to-make-p2p-wifi-connection

### how-to-make-pagination
API pagination sample for HarmonyOS watches using ArcList or List with next/previous controls to browse remotely loaded data.
Kits: RemoteCommunicationKit. Topics: lists, pagination, remote-communication-kit. URL: https://github.com/Explore-In-HMOS/how-to-make-pagination

### how-to-make-rest-api-calls-with-network-kit-in-arkts
REST API codelab for HarmonyOS watches sending GET, POST, PUT and DELETE requests with Network Kit, status checks, retries and JSON parsing.
Kits: NetworkKit. Topics: http, mvvm, network-kit, networking, rest-api. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-make-rest-api-calls-with-network-kit-in-arkts

### how-to-scan-ble
BLE scanning and advertising codelab for HarmonyOS watches showing central/peripheral roles, location identifiers and RSSI-based proximity feedback.
Kits: ConnectivityKit. Topics: ble-advertising, bluetooth-low-energy, device-discovery, rssi. SDK: HarmonyOS SDK 5.1.0. URL: https://github.com/Explore-In-HMOS/how-to-scan-ble

### how-to-scan-nearby-devices-by-nearlink-kit
NearLink device discovery sample for HarmonyOS with live scanning, nearby device lists and RSSI signal-strength monitoring.
Kits: NearLinkKit. Topics: device-discovery, iot, nearlink, rssi. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-scan-nearby-devices-by-nearlink-kit

### how-to-send-graphql-requests
GraphQL HTTP request codelab for HarmonyOS with examples using no variables, static variables and dynamically supplied query variables.
Kits: core ArkUI/Ability kits only. Topics: graphql, http-client. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-send-graphql-requests

### how-to-track-http-request-progress
HTTP progress codelab for HarmonyOS watches tracking file download and upload progress with Network Kit request events.
Kits: CoreFileKit, NetworkKit. Topics: download, http, network-kit, progress-tracking, upload. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-track-http-request-progress

### how-to-use-call-service-kit
CallServiceKit codelab for HarmonyOS demonstrating simulated VoIP calls, call-state transitions, mute/speaker controls and error handling.
Kits: AVSessionKit, CallServiceKit, ImageKit, TelephonyKit. Topics: call-service-kit, telephony, voip. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-use-call-service-kit

### how-to-use-hce
Host card emulation (HCE) demo for HarmonyOS watches showing NFC payment-style flows in foreground and background, with cards stored in ArkData RDB.
Kits: ArkData, ConnectivityKit. Topics: arkdata, card-emulation, connectivity-kit, hce, nfc. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-hce

### how-to-use-network-kit
Network Kit playground for HarmonyOS testing HTTP requests, TCP sockets and WebSocket message flows with connection and error handling.
Kits: NetworkKit. Topics: http-client, network-kit, tcp, websocket. SDK: HarmonyOS SDK 5.0.0.25. URL: https://github.com/Explore-In-HMOS/how-to-use-network-kit

### how-to-use-nfc-tag
NFC tag detection demo for HarmonyOS watches with capability checks, foreground reader mode and display of tag UID and supported technologies.
Kits: ConnectivityKit. Topics: connectivity-kit, device-capabilities, nfc, nfc-tags. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-nfc-tag

### how-to-use-web-socket
WebSocket codelab for HarmonyOS demonstrating connection states, bidirectional messages and real-time communication debugging.
Kits: NetworkKit. Topics: networking, realtime, websocket. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-web-socket

## Background and Notifications (`background-and-notifications`)

### how-to-build-ability-trigger-skills
Health reminder codelab for HarmonyOS watches chaining reminderAgentManager alarms, WantAgent skill intents and deferred medication reminders.
Kits: BackgroundTasksKit, NotificationKit. Topics: background-tasks, intents, reminders. SDK: HarmonyOS SDK 6.1.1 (API 12+, stage model). URL: https://github.com/Explore-In-HMOS/how-to-build-ability-trigger-skills

### how-to-build-background-task-scheduler
Background weather synchronization sample for HarmonyOS watches using WorkSchedulerExtensionAbility, periodic work and locally cached preferences.
Kits: ArkData, BackgroundTasksKit, NetworkKit. Topics: arkdata, background-tasks, weather, work-scheduler. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-background-task-scheduler

### how-to-build-fault-log-extension
FaultLogExtensionAbility sample for HarmonyOS watches with background crash/ANR processing, readable summaries and queued telemetry.
Kits: core ArkUI/Ability kits only. Topics: background-tasks, crash-reporting, logging, telemetry. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-fault-log-extension

### how-to-build-live-widget-factory
Form Kit weather widget demo for HarmonyOS watches using mock data, widget lifecycle callbacks, interactive live forms and a city-picker edit flow.
Kits: ArkData, FormKit. Topics: form-kit, lifecycle, weather, widgets. SDK: HarmonyOS SDK (API 20+). URL: https://github.com/Explore-In-HMOS/how-to-build-live-widget-factory

### how-to-build-rich-notification-center
Notification Kit sample for HarmonyOS watches with grouped messages, priority slots, custom layouts and inline reply, dismiss and snooze actions.
Kits: NotificationKit. Topics: notification-kit, notifications, quick-reply. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-rich-notification-center

### how-to-build-shape-segment-button
Wearable workout selector UI sample for HarmonyOS combining ArkUI shape masks, segmented controls, widget previews and form menu actions.
Kits: core ArkUI/Ability kits only. Topics: segmented-control, shapes, widgets. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-shape-segment-button

### how-to-create-calender-picker-in-wearable
Custom calendar picker for HarmonyOS watches with compact month, year and day selection in ArkUI.
Kits: CalendarKit. Topics: calendar, date-picker, ui-components. SDK: HarmonyOS 5.0.39 Beta2 SDK. URL: https://github.com/Explore-In-HMOS/how-to-create-calender-picker-in-wearable

### how-to-create-card-widgets
Watch card-widget sample for HarmonyOS demonstrating a 2x3 widget and bidirectional data updates between the app and its card.
Kits: ArkData, FormKit, IPCKit, SensorServiceKit. Topics: data-binding, form-kit, widgets. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-create-card-widgets

### how-to-download-file
Simulated download workflow for HarmonyOS watches demonstrating pause/resume/cancel controls, background tasks and progress notifications.
Kits: BackgroundTasksKit, NotificationKit. Topics: background-tasks, notification-kit, notifications. SDK: HarmonyOS SDK 5.1.0. URL: https://github.com/Explore-In-HMOS/how-to-download-file

### how-to-implement-self-refreshing-widget
Self-refreshing service widget for HarmonyOS watches with FormExtensionAbility scheduled updates, tap refresh, mock data and Preferences storage.
Kits: ArkData, CryptoArchitectureKit, FormKit. Topics: arkdata, form-kit, widgets. URL: https://github.com/Explore-In-HMOS/how-to-implement-self-refreshing-widget

### how-to-make-bluetooth-connectivity-monitor
Bluetooth state monitoring sample for HarmonyOS watches with ON/OFF updates, notifications and background service controls.
Kits: BackgroundTasksKit, ConnectivityKit, NotificationKit. Topics: background-tasks, bluetooth, connectivity, notifications. URL: https://github.com/Explore-In-HMOS/how-to-make-bluetooth-connectivity-monitor

### how-to-send-timed-notification
Scheduled notification codelab for HarmonyOS using agent-powered reminders to create reminders and deliver notifications.
Kits: BackgroundTasksKit, NotificationKit. Topics: notification-kit, notifications, reminders. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-send-timed-notification

### how-to-use-background-task
Transient background task codelab for HarmonyOS demonstrating timed execution after the app leaves the foreground.
Kits: BackgroundTasksKit. Topics: background-tasks, task-scheduling. SDK: HarmonyOS SDK 5.1.0. URL: https://github.com/Explore-In-HMOS/how-to-use-background-task

### how-to-use-background-tasks-kit
Background weather refresh sample for HarmonyOS watches using deferred tasks to fetch forecast data under suitable system conditions.
Kits: BackgroundTasksKit. Topics: background-tasks, task-scheduling, weather. SDK: HarmonyOS SDK 5.0.2(18). URL: https://github.com/Explore-In-HMOS/how-to-use-background-tasks-kit

### how-to-use-battery-kit
Battery monitoring app and widget for HarmonyOS watches displaying charge level, health, temperature and charging state using Battery Kit.
Kits: FormKit. Topics: battery, battery-kit, system-monitoring, widgets. SDK: HarmonyOS SDK 6.0.0. URL: https://github.com/Explore-In-HMOS/how-to-use-battery-kit

### how-to-use-notifications
Interactive notification codelab for HarmonyOS using WantAgent to launch pages and trigger actions from notification taps and buttons.
Kits: NotificationKit. Topics: notification-kit, notifications, wantagent. URL: https://github.com/Explore-In-HMOS/how-to-use-notifications

## Data and Storage (`data-and-storage`)

### how-to-build-auto-clear-storage-manager
Auto-clear storage codelab for HarmonyOS watches that deletes the oldest relational database rows once a configured storage limit is reached.
Kits: ArkData. Topics: arkdata, relational-database, storage-management. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-build-auto-clear-storage-manager

### how-to-build-cloud-file-sync
Offline-first file sync codelab for HarmonyOS watches, showing queued transfers, retries, conflict handling and file-sharing permissions.
Kits: CoreFileKit. Topics: cloud-storage, file-sharing, file-sync, offline-first. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-cloud-file-sync

### how-to-build-data-ability-operations
Health-data sync sample for HarmonyOS watches showing atomic RDB batches, remote ability readiness checks and resumable watch-to-phone workflows.
Kits: ArkData. Topics: data-sync, health-data, relational-database. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-build-data-ability-operations

### how-to-build-data-serializer
Local data serialization sample for HarmonyOS watches using mock XML/XMI health records, stream chunks, binary buffers and decimal-safe arithmetic.
Kits: ArkData. Topics: arkts-utils, binary-data, serialization, xml. SDK: HarmonyOS SDK 5.0.0(12). URL: https://github.com/Explore-In-HMOS/how-to-build-data-serializer

### how-to-build-js-stepper-toolbar
Watch-face setup wizard for HarmonyOS wearables using a stepper, live preview, responsive layout and persistent dial, complication and color settings.
Kits: ArkData. Topics: state-persistence, stepper, watch-face. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-build-js-stepper-toolbar

### how-to-build-jwt-with-crypto-kit
JWT signing codelab for HarmonyOS watches using Crypto Architecture Kit PS256 RSA-PSS signatures to get a service account access token.
Kits: CryptoArchitectureKit, NetworkKit. Topics: crypto-architecture-kit, jwt, network-kit, oauth2, rsa-pss, security. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-build-jwt-with-crypto-kit

### how-to-build-local-database
ArkData relational database codelab for HarmonyOS watches, using simulated workout records to demonstrate local persistence and history views.
Kits: ArkData. Topics: arkdata, relational-database, workout-tracker. SDK: | HarmonyOS Next |. URL: https://github.com/Explore-In-HMOS/how-to-build-local-database

### how-to-build-network-firewall-tester
ArkData RDB sample for HarmonyOS watches that stores and queries firewall-test records, demonstrating persistence, null handling and asset conversion.
Kits: ArkData. Topics: arkdata, relational-database. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-build-network-firewall-tester

### how-to-build-platform-integration-test
Integration test suite for HarmonyOS watches covering input methods, Huawei ID, push extensions, accessibility, certificates and raw resources.
Kits: AccessibilityKit, AccountKit, ArkData, CoreFileKit, DeviceCertificateKit, IMEKit, LocalizationKit, MultimodalAwarenessKit, PushKit. Topics: diagnostics, integration-testing, test-automation. SDK: HarmonyOS 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-platform-integration-test

### how-to-build-state-persistence
ArkUI state-management codelab for HarmonyOS watches covering PersistenceV2, State/Prop/Link, AppStorage, Environment and reactive change observers.
Kits: core ArkUI/Ability kits only. Topics: state-management, state-persistence. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-state-persistence

### how-to-decrypt-with-publickey
RSA public-key decryption codelab for HarmonyOS watches using Crypto Architecture Kit with RSA/ECB/PKCS1Padding.
Kits: CryptoArchitectureKit. Topics: crypto-framework, cryptography, rsa. SDK: HarmonyOS SDK 5.1.0. URL: https://github.com/Explore-In-HMOS/how-to-decrypt-with-publickey

### how-to-generate-symmetric-keys
Symmetric key generation codelab for HarmonyOS watches creating 3DES and HMAC keys with Crypto Architecture Kit.
Kits: CryptoArchitectureKit. Topics: 3des, cryptography, hmac, key-generation. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-generate-symmetric-keys

### how-to-implement-huks-attestation
Device attestation codelab for HarmonyOS watches using Universal Keystore Kit HUKS key attestation in the TEE and certificate chain checks.
Kits: DeviceCertificateKit, LocalizationKit, UniversalKeystoreKit. Topics: device-certificate-kit, huks, key-attestation, security, universal-keystore-kit. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-implement-huks-attestation

### how-to-implement-local-file-storage
Quick notes codelab for HarmonyOS watches storing files in the app sandbox with Core File Kit atomic writes, taskpool and storage monitoring.
Kits: CoreFileKit. Topics: core-file-kit, file-storage, mvvm, sandbox, state-management-v2, taskpool. SDK: HarmonyOS SDK 5.1.0(18) or later. URL: https://github.com/Explore-In-HMOS/how-to-implement-local-file-storage

### how-to-implement-screenshot-prevention
Screenshot prevention codelab for HarmonyOS watches using setWindowPrivacyMode to black out captures and recordings of sensitive screens.
Kits: core ArkUI/Ability kits only. Topics: screenshot-prevention, security, window-privacy. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-implement-screenshot-prevention

### how-to-implement-secure-storage-with-asset-store-kit
Asset Store Kit codelab for HarmonyOS watches securely adding, updating and deleting sensitive key-value secrets such as tokens and keys.
Kits: AssetStoreKit. Topics: asset-store-kit, secure-storage, security. SDK: HarmonyOS SDK 6.1.0(23). URL: https://github.com/Explore-In-HMOS/how-to-implement-secure-storage-with-asset-store-kit

### how-to-implement-theme-aware-swipe-indicators
Theme-aware Swiper indicator codelab for HarmonyOS watches switching light and dark mode with setColorMode and persisting it in preferences.
Kits: ArkData. Topics: arkdata, dark-mode, swiper, theming. URL: https://github.com/Explore-In-HMOS/how-to-implement-theme-aware-swipe-indicators

### how-to-install-debug-hap-files
Setup guide for Huawei watches: enable developer options, connect DevEco Studio over Wi-Fi and install debug HAP files with HDC commands.
Kits: core ArkUI/Ability kits only. Topics: debugging, deveco-studio, developer-options, hap, hdc. URL: https://github.com/Explore-In-HMOS/how-to-install-debug-hap-files

### how-to-make-localization-manager
Localization and key-value storage sample for HarmonyOS watches with runtime language switching and create/read/delete operations.
Kits: ArkData. Topics: arkdata, key-value-store, localization. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-make-localization-manager

### how-to-monitor-device-storage
Device storage codelab for HarmonyOS watches reading total and free space, app bundle stats and sandbox folder sizes on crown-driven cards.
Kits: CoreFileKit. Topics: core-file-kit, digital-crown, file-system, storage. SDK: HarmonyOS 6.0.1 (API 21). URL: https://github.com/Explore-In-HMOS/how-to-monitor-device-storage

### how-to-read-raw-file
Raw resource file codelab for HarmonyOS demonstrating bundled JSON and MP3 reading and file-length inspection.
Kits: core ArkUI/Ability kits only. Topics: file-io, json, resource-management. URL: https://github.com/Explore-In-HMOS/how-to-read-raw-file

### how-to-show-storage-statistics
Storage statistics codelab for HarmonyOS watches using Core File Kit storageStatistics to show device capacity, free space and app usage.
Kits: CoreFileKit. Topics: core-file-kit, storage, storage-statistics. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-show-storage-statistics

### how-to-store-and-retrieve-media-files
Media file sandbox codelab for HarmonyOS watches storing, retrieving and deleting images, audio and video with Core File Kit fileIo.
Kits: CoreFileKit. Topics: core-file-kit, file-io, media-files, sandbox. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-store-and-retrieve-media-files

### how-to-use-kv-store
Key-value storage codelab for HarmonyOS demonstrating data persistence and listeners for stored-value changes.
Kits: ArkData. Topics: arkdata, key-value-store. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-kv-store

### how-to-use-timer-functionality
Habit timer codelab for HarmonyOS watches with daily time tracking, habit switching, Preferences storage and relational session history.
Kits: ArkData, BackgroundTasksKit, NotificationKit. Topics: arkdata, habit-tracker, relational-database, timer. URL: https://github.com/Explore-In-HMOS/how-to-use-timer-functionality

## UI and Interaction (`ui-and-interaction`)

### how-to-add-rotating-verifier
Rotation-based verification UI sample for HarmonyOS watches, with an interactive dial, success feedback and navigation to the main screen.
Kits: core ArkUI/Ability kits only. Topics: rotation, verification. SDK: HarmonyOS 6.0.0. URL: https://github.com/Explore-In-HMOS/how-to-add-rotating-verifier

### how-to-apply-text-typography
Interactive ArkUI typography codelab for HarmonyOS watches, demonstrating Text component font sizes, weights and styles with live previews.
Kits: core ArkUI/Ability kits only. Topics: text, typography. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-apply-text-typography

### how-to-audit-accessibility-state
Accessibility Kit sample for HarmonyOS watches that inspects touch-guide state, accessibility modes and enabled extensions before a mock transit flow.
Kits: AccessibilityKit. Topics: accessibility, accessibility-kit. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-audit-accessibility-state

### how-to-build-3d-material-lighting
ArkGraphics3D codelab for HarmonyOS watches exploring PBR materials, lighting, texture sampling and HDR capability checks on a procedural watch dial.
Kits: ArkGraphics2D, ArkGraphics3D. Topics: 3d-graphics, arkgraphics3d, lighting, pbr. SDK: HarmonyOS SDK 6.0.1. URL: https://github.com/Explore-In-HMOS/how-to-build-3d-material-lighting

### how-to-build-3d-model-viewer
3D model viewer sample for HarmonyOS watches showing built-in geometry, custom meshes, glTF models and shader/image materials with ArkGraphics3D.
Kits: ArkGraphics3D. Topics: 3d-model-viewer, arkgraphics3d, gltf, shaders. URL: https://github.com/Explore-In-HMOS/how-to-build-3d-model-viewer

### how-to-build-3d-post-processing
3D post-processing codelab for HarmonyOS watches with a GLB viewer, gesture rotation and live controls for bloom, tone mapping and vignette effects.
Kits: ArkGraphics3D. Topics: 3d-graphics, arkgraphics3d, gltf, post-processing. URL: https://github.com/Explore-In-HMOS/how-to-build-3d-post-processing

### how-to-build-3d-scene-config
ArkGraphics3D scene-management sample for HarmonyOS watches: load a glTF chess set, inspect nodes, group objects and configure lights and cameras.
Kits: ArkGraphics3D. Topics: 3d-graphics, arkgraphics3d, gltf, scene-graph. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-3d-scene-config

### how-to-build-ability-lifecycle-context
Ability Kit codelab for HarmonyOS watches visualizing UIAbility lifecycle, Stage-model context hierarchy and thread-safe context transfer to a Worker.
Kits: core ArkUI/Ability kits only. Topics: concurrency, lifecycle, worker. URL: https://github.com/Explore-In-HMOS/how-to-build-ability-lifecycle-context

### how-to-build-animated-icon-factory
Animated icon codelab for HarmonyOS watches using drawable descriptors to compose adaptive layers and preview frame-based animation.
Kits: core ArkUI/Ability kits only. Topics: animation, icons. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-animated-icon-factory

### how-to-build-animation-toolkit
ArkUI animation reference for HarmonyOS watches covering keyframes, motion paths, geometry/shared transitions and drawable playback.
Kits: core ArkUI/Ability kits only. Topics: animation, keyframes, transitions. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-animation-toolkit

### how-to-build-app-lifecycle-hub
App lifecycle dashboard for HarmonyOS watches showing EventHub messaging, ApplicationContext, environment callbacks and process/memory monitoring.
Kits: core ArkUI/Ability kits only. Topics: event-driven, lifecycle, system-monitoring. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-app-lifecycle-hub

### how-to-build-app-state-observer
Application-state observation codelab for HarmonyOS watches with foreground/background callbacks, bundle inspection and process-state API examples.
Kits: core ArkUI/Ability kits only. Topics: debugging, lifecycle, process-monitoring. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-app-state-observer

### how-to-build-arc-progress-dashboard
Arc-style dashboard sample for HarmonyOS watches combining circular metrics, component observation, attribute updates and on-device layout inspection.
Kits: core ArkUI/Ability kits only. Topics: dashboard, progress-ring. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-build-arc-progress-dashboard

### how-to-build-atomic-service-launcher
Atomic service launcher codelab for HarmonyOS watches with on-watch search, full/half-screen launch, AtomicServiceWeb and watch-to-phone migration.
Kits: core ArkUI/Ability kits only. Topics: atomic-services, cross-device. SDK: HarmonyOS 6.0.1. URL: https://github.com/Explore-In-HMOS/how-to-build-atomic-service-launcher

### how-to-build-autofill-startup
Auto-startup status check and shortcut visibility toggle for HarmonyOS watches using autoStartupManager and shortcutManager.
Kits: core ArkUI/Ability kits only. Topics: app-startup, shortcuts. URL: https://github.com/Explore-In-HMOS/how-to-build-autofill-startup

### how-to-build-biometric-auth-button
UserAuthIcon authentication component sample for HarmonyOS wearables, showing system authentication UI and protected views of mock health records.
Kits: core ArkUI/Ability kits only. Topics: authentication, biometrics, user-authentication. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-biometric-auth-button

### how-to-build-border-shape-style
Interactive border styling sample for HarmonyOS watches with profile-card customization, reactive state binding and modular ArkUI components.
Kits: core ArkUI/Ability kits only. Topics: borders, mvvm, ui-styling. SDK: HarmonyOS SDK 6.0.0. URL: https://github.com/Explore-In-HMOS/how-to-build-border-shape-style

### how-to-build-buffered-stream-bench
ArkTS collections codelab for HarmonyOS watches covering Queue, Deque, Stack, ArrayList, HashSet, TreeMap, PlainArray and BitVector operations.
Kits: core ArkUI/Ability kits only. Topics: collections, data-structures. URL: https://github.com/Explore-In-HMOS/how-to-build-buffered-stream-bench

### how-to-build-chip-segment-selector
ArkUI segment and chip filtering sample for HarmonyOS watches with deep state observation, parent-child bindings and a mock fitness dashboard.
Kits: core ArkUI/Ability kits only. Topics: filtering, mvvm, state-management. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-chip-segment-selector

### how-to-build-component-event-tracker
ArkUI component event codelab for HarmonyOS watches with interactive layout, scrolling and accessibility examples plus timestamped event payload logs.
Kits: core ArkUI/Ability kits only. Topics: debugging, event-handling. SDK: HarmonyOS SDK 6.0.1 (API 17 or later). URL: https://github.com/Explore-In-HMOS/how-to-build-component-event-tracker

### how-to-build-component-lifecycle-toolkit
ArkUI component lifecycle codelab for HarmonyOS watches covering page callbacks, component appearance, reuse/recycling and two-way state binding.
Kits: core ArkUI/Ability kits only. Topics: component-reuse, lifecycle, state-management. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-component-lifecycle-toolkit

### how-to-build-context-menu-editor
Context-menu quick-reply editor for HarmonyOS watches, demonstrating ArkUI bindMenu, nested menus, message templates and MVVM state handling.
Kits: core ArkUI/Ability kits only. Topics: context-menu, mvvm, text-editor. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-context-menu-editor

### how-to-build-crash-recovery-guard
Crash recovery codelab for HarmonyOS watches with appRecovery, error and loop observers, UIAbility checkpoints and an incident timeline.
Kits: ArkData. Topics: crash-recovery, debugging, error-handling. URL: https://github.com/Explore-In-HMOS/how-to-build-crash-recovery-guard

### how-to-build-cross-device-continuation
Cross-device continuation codelab for HarmonyOS watches using continueManager quick start, onContinue route-state handoff and migrated state restore.
Kits: core ArkUI/Ability kits only. Topics: continuation, cross-device, state-management. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-cross-device-continuation

### how-to-build-custom-emoji-keyboard
Custom emoji keyboard sample for HarmonyOS watches using ArkUI customKeyboard, Unicode category generation and a compact horizontally scrolling grid.
Kits: core ArkUI/Ability kits only. Topics: custom-keyboard, emoji, unicode. URL: https://github.com/Explore-In-HMOS/how-to-build-custom-emoji-keyboard

### how-to-build-custom-event-gesture
ArkUI event and gesture routing demo for HarmonyOS watches with custom interception, exclusive gesture handling and a round-screen fitness interface.
Kits: core ArkUI/Ability kits only. Topics: event-handling, gesture-recognition, touch-events. SDK: HarmonyOS SDK 6.1.1. URL: https://github.com/Explore-In-HMOS/how-to-build-custom-event-gesture

### how-to-build-custom-node-renderer
Custom node rendering codelab for HarmonyOS watches using BuilderNode, NodeContent and NodeAdapter to compose and update individual watch-face tiles.
Kits: core ArkUI/Ability kits only. Topics: custom-rendering, node-adapter, watch-face. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-custom-node-renderer

### how-to-build-data-prefetch-pipeline
ArkUI list prefetching sample for HarmonyOS watches using BasicPrefetcher and LazyForEach with a local mock news service and simulated latency.
Kits: core ArkUI/Ability kits only. Topics: infinite-scroll, lazy-loading, prefetching. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-data-prefetch-pipeline

### how-to-build-dialog-patterns
Dialog pattern codelab for HarmonyOS watches comparing CustomDialog, DialogV2, sheets, action sheets and popovers in compact round-screen layouts.
Kits: core ArkUI/Ability kits only. Topics: dialogs, popup. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-dialog-patterns

### how-to-build-dialog-system-config
Settings confirmation sample for HarmonyOS watches with data-driven lists, promptAction dialogs, interstitial confirmation and color modes.
Kits: core ArkUI/Ability kits only. Topics: dark-mode, dialogs, settings. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-dialog-system-config

### how-to-build-display-test
UiTest sample for HarmonyOS watches covering window resizing, mouse buttons, match patterns, rotation and documented wearable limitations.
Kits: core ArkUI/Ability kits only. Topics: test-automation, test-kit, ui-testing. URL: https://github.com/Explore-In-HMOS/how-to-build-display-test

### how-to-build-dynamic-sync-cursor
Music remote UI codelab for HarmonyOS watches with frame-synced swiper, marquee and rotation animations, a circular seek ring and playlist editing.
Kits: InputKit. Topics: animation, media-controls, swiper. SDK: HarmonyOS SDK (Latest Wearable API). URL: https://github.com/Explore-In-HMOS/how-to-build-dynamic-sync-cursor

### how-to-build-flex-layout
ArkUI Flex layout codelab for HarmonyOS watches demonstrating growth ratios, shrinking, reversed direction and wrapped content on round screens.
Kits: core ArkUI/Ability kits only. Topics: flexbox, responsive-layout. SDK: HarmonyOS SDK 5.1.0(18)+, API 23 and below. URL: https://github.com/Explore-In-HMOS/how-to-build-flex-layout

### how-to-build-focus-accessibility
Accessible HarmonyOS watch UI codelab with digital crown navigation, programmatic focus, focus properties and accessibility actions using ArcList.
Kits: core ArkUI/Ability kits only. Topics: accessibility, digital-crown, focus-management. SDK: HarmonyOS SDK 6.0.1 (API 20). URL: https://github.com/Explore-In-HMOS/how-to-build-focus-accessibility

### how-to-build-gesture-drill-board
ArkUI gesture drill sample for HarmonyOS watches with pinch and drag stations, touch routing, gesture filtering and dynamic frame-rate controls.
Kits: ArkData. Topics: gesture-recognition, touch-events. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-build-gesture-drill-board

### how-to-build-grid-sort-list
Drag-sortable grid codelab for HarmonyOS watches using Grid editMode, IDataSource, LazyForEach and grouped lists with custom drag previews.
Kits: core ArkUI/Ability kits only. Topics: drag-and-drop, grid-layout, lazy-loading. URL: https://github.com/Explore-In-HMOS/how-to-build-grid-sort-list

### how-to-build-insight-intent
InsightIntent codelab for HarmonyOS watches linking shortcuts to Entry, Function, Link and Page intents for mock heart-rate, workout and call screens.
Kits: core ArkUI/Ability kits only. Topics: insight-intent, intents, shortcuts. URL: https://github.com/Explore-In-HMOS/how-to-build-insight-intent

### how-to-build-intent-driven-actions
Intent-driven action sample for HarmonyOS watches with mock workout/countdown actions, foreground UI launch and structured execution results.
Kits: core ArkUI/Ability kits only. Topics: insight-intent, intents. SDK: HarmonyOS Stage Model, InsightIntent. URL: https://github.com/Explore-In-HMOS/how-to-build-intent-driven-actions

### how-to-build-js-form-controls
Fitness logging form controls for HarmonyOS watches in both ArkTS (MVVM) and JS UI, with time picker, rating, notes, search, select and toggle inputs.
Kits: core ArkUI/Ability kits only. Topics: forms, mvvm. URL: https://github.com/Explore-In-HMOS/how-to-build-js-form-controls

### how-to-build-keyboard-switcher
IME Kit sample for HarmonyOS watches that lists and switches input methods, opens the system keyboard picker and controls keyboard visibility.
Kits: IMEKit. Topics: ime-kit, input-method, keyboard. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-build-keyboard-switcher

### how-to-build-layout-sizing-position
ArkUI layout debugging sample for HarmonyOS watches with bounding-box visuals and interactive sizing, positioning, offsets and safe-area examples.
Kits: core ArkUI/Ability kits only. Topics: debugging, safe-area. SDK: | ArkUI (HarmonyOS UI) |. URL: https://github.com/Explore-In-HMOS/how-to-build-layout-sizing-position

### how-to-build-lifecycle-monitor
UIAbility lifecycle monitor for HarmonyOS watches with real-time diagnostic overlays, AbilityStage observers and structured lifecycle logs.
Kits: core ArkUI/Ability kits only. Topics: debugging, lifecycle, logging. SDK: HarmonyOS Stage Model, Ability lifecycle callbacks, Application state observer. URL: https://github.com/Explore-In-HMOS/how-to-build-lifecycle-monitor

### how-to-build-loading-confirm-dialog
ArkUI dialog comparison codelab for HarmonyOS watches, covering confirmation, loading and tips dialogs alongside their DialogV2 equivalents.
Kits: core ArkUI/Ability kits only. Topics: dialogs. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-loading-confirm-dialog

### how-to-build-mission-task-switcher
Typography and color-space bench for HarmonyOS watches with variable-font axes, glyph outline paths, inline image fallback and sRGB/DCI-P3 switching.
Kits: ArkGraphics2D. Topics: arkgraphics2d, color-management, typography, variable-fonts. SDK: HarmonyOS SDK 6.0.2(22), compatible with 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-build-mission-task-switcher

### how-to-build-modifier-toolkit
Live theme engine for HarmonyOS watches using ArkUI attribute, content, drawing, gesture and symbol modifiers.
Kits: ArkGraphics2D. Topics: modifiers, theming. URL: https://github.com/Explore-In-HMOS/how-to-build-modifier-toolkit

### how-to-build-multilingual-watch
Localized watch-face sample for HarmonyOS with language switching and previews of date, time, number and currency formats, including RTL.
Kits: LocalizationKit. Topics: internationalization, localization, rtl, watch-face. URL: https://github.com/Explore-In-HMOS/how-to-build-multilingual-watch

### how-to-build-overlay-dialog
Static resource overlay codelab for HarmonyOS watches where an HSP overlay module replaces brand colors and strings, toggled with setOverlayEnabled.
Kits: core ArkUI/Ability kits only. Topics: resource-overlays, theming. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-build-overlay-dialog

### how-to-build-picker-dialogs
Picker and dialog codelab for HarmonyOS watches with calendar, time and text selection synchronized through ComponentV2 state management.
Kits: core ArkUI/Ability kits only. Topics: date-picker, dialogs, state-management. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-picker-dialogs

### how-to-build-popup-tooltip
Popup and tooltip pattern library for HarmonyOS watches with anchored bubbles, action buttons, long-press tooltips and a shared visibility controller.
Kits: core ArkUI/Ability kits only. Topics: popup, tooltip, ui-components. SDK: HarmonyOS SDK 5.1.0(21). URL: https://github.com/Explore-In-HMOS/how-to-build-popup-tooltip

### how-to-build-queue-scrollboard
Scrolling queue codelab for HarmonyOS watches using Grid, List and Scroll, with item removal and animated list updates that preserve scroll position.
Kits: CryptoArchitectureKit. Topics: grid-layout, lists, scrolling. URL: https://github.com/Explore-In-HMOS/how-to-build-queue-scrollboard

### how-to-build-quick-reply-input-deck
Quick-reply input UI sample for HarmonyOS watches combining PatternLock, styled text, Canvas drawing and interactive state management.
Kits: ArkGraphics2D. Topics: custom-input, pattern-lock, rich-text. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-build-quick-reply-input-deck

### how-to-build-render-graphics-pipeline
Watch-face rendering pipeline for HarmonyOS with circular viewport fitting, SVG layers, image metadata and Matrix4 transforms.
Kits: core ArkUI/Ability kits only. Topics: custom-rendering, graphics, svg, watch-face. SDK: HarmonyOS SDK 6.1.1.125. URL: https://github.com/Explore-In-HMOS/how-to-build-render-graphics-pipeline

### how-to-build-responsive-round-layout
Responsive layout codelab for HarmonyOS watches using device-shape detection and custom layout lifecycles to adapt round and square screen content.
Kits: core ArkUI/Ability kits only. Topics: adaptive-ui, custom-layout, responsive-layout. URL: https://github.com/Explore-In-HMOS/how-to-build-responsive-round-layout

### how-to-build-reverse-list
Reverse chat-style list codelab for HarmonyOS watches using ArkUI scale inversion, custom crown scrolling and jump-to-latest controls.
Kits: core ArkUI/Ability kits only. Topics: chat-ui, digital-crown, lists. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-reverse-list

### how-to-build-scroll-filter-list
Contact-list UI codelab for HarmonyOS watches with mock contacts, arc alphabet indexing, recent items, multi-selection and display preferences.
Kits: core ArkUI/Ability kits only. Topics: alphabet-indexer, contacts, lists. URL: https://github.com/Explore-In-HMOS/how-to-build-scroll-filter-list

### how-to-build-security-buttons
PasteButton codelab for HarmonyOS watches showing user-triggered temporary clipboard authorization, paste callbacks and security component styling.
Kits: core ArkUI/Ability kits only. Topics: clipboard, permissions, security-components. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-security-buttons

### how-to-build-split-layout-suite
ArkUI split-layout codelab for HarmonyOS watches with ColumnSplit, RowSplit and SideBarContainer examples in separate full-screen demos.
Kits: core ArkUI/Ability kits only. Topics: responsive-layout, sidebar, split-layout. SDK: HarmonyOS SDK 5.1.0(18)+. URL: https://github.com/Explore-In-HMOS/how-to-build-split-layout-suite

### how-to-build-startup-recovery-board
App Startup framework codelab for HarmonyOS watches visualizing task dependencies, independent execution and per-task startup timing.
Kits: core ArkUI/Ability kits only. Topics: app-startup, performance, task-scheduling. SDK: HarmonyOS SDK 6.0.1(21), App Startup framework. URL: https://github.com/Explore-In-HMOS/how-to-build-startup-recovery-board

### how-to-build-swipe-to-refresh
Pull-to-refresh sample for HarmonyOS watches using ArkUI Refresh and List components with mock messages.
Kits: CryptoArchitectureKit. Topics: lists, pull-to-refresh. SDK: HarmonyOS SDK 5.1.0(21). URL: https://github.com/Explore-In-HMOS/how-to-build-swipe-to-refresh

### how-to-build-system-callback
Hardware diagnostics sample for HarmonyOS watches combining CPU, memory and thermal telemetry with serial-port configuration and UART interaction.
Kits: core ArkUI/Ability kits only. Topics: diagnostics, serial-port, system-monitoring, uart. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-system-callback

### how-to-build-system-event-monitor
System event monitor for HarmonyOS watches covering battery, power, screen, timezone and connectivity events with commonEventManager.
Kits: core ArkUI/Ability kits only. Topics: basic-services-kit, event-driven, system-monitoring. SDK: HarmonyOS SDK 6.0.1, BasicServicesKit / `commonEventManager`. URL: https://github.com/Explore-In-HMOS/how-to-build-system-event-monitor

### how-to-build-system-monitor
System health dashboard for HarmonyOS watches using systemLoad levels, cacheDownload cache updates, distributed account status and customConfig.
Kits: core ArkUI/Ability kits only. Topics: caching, diagnostics, system-monitoring. SDK: HarmonyOS SDK 6.1.1(24). URL: https://github.com/Explore-In-HMOS/how-to-build-system-monitor

### how-to-build-theme-dark-mode
Dynamic light/dark theme sample for HarmonyOS watches with a pure-black AMOLED palette, privacy masking and state-aware controls.
Kits: core ArkUI/Ability kits only. Topics: amoled, dark-mode, theming. SDK: HarmonyOS SDK (API 20+). URL: https://github.com/Explore-In-HMOS/how-to-build-theme-dark-mode

### how-to-build-touch-event-handler
Touch interaction lab for HarmonyOS watches covering tap callbacks, touch tracking, hit testing, target expansion and feedback on circular displays.
Kits: CryptoArchitectureKit. Topics: hit-testing, touch-events. SDK: HarmonyOS SDK 6.0.1 (21). URL: https://github.com/Explore-In-HMOS/how-to-build-touch-event-handler

### how-to-build-touch-gesture-lab
Gesture examples for HarmonyOS watches covering tap, long press, pan, pinch, rotation, swipe and sequential or parallel gesture combinations.
Kits: core ArkUI/Ability kits only. Topics: gesture-recognition, multitouch. URL: https://github.com/Explore-In-HMOS/how-to-build-touch-gesture-lab

### how-to-build-touch-pointer-handler
Multi-touch input codelab for HarmonyOS watches using single- and two-finger actions for accidental-touch protection, navigation and media controls.
Kits: core ArkUI/Ability kits only. Topics: multitouch, touch-events. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-touch-pointer-handler

### how-to-build-trace-inspector
Trace inspection codelab for HarmonyOS watches covering performance bottlenecks, debugging and CPU/thread activity analysis.
Kits: core ArkUI/Ability kits only. Topics: debugging, performance-analysis, profiling, tracing. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-trace-inspector

### how-to-build-typed-collections
ArkTS Sendable collections codelab for HarmonyOS watches covering arrays, maps, sets, bit vectors and typed buffers shared across TaskPool workers.
Kits: core ArkUI/Ability kits only. Topics: collections, concurrency, data-structures, taskpool. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-typed-collections

### how-to-build-typed-int-arrays
Typed integer array codelab for HarmonyOS watches with shared binary buffers, signed/unsigned views, DataView endianness and text encoding examples.
Kits: core ArkUI/Ability kits only. Topics: binary-data, data-structures, encoding, typed-arrays. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-build-typed-int-arrays

### how-to-build-typography-showcase
ArkGraphics2D typography sample for HarmonyOS watches using Font, TextBlob, Typeface and paragraph layout APIs.
Kits: ArkGraphics2D. Topics: arkgraphics2d, text-rendering, typography. SDK: HarmonyOS SDK 6.0.1 (API 21). URL: https://github.com/Explore-In-HMOS/how-to-build-typography-showcase

### how-to-build-ui-automation
UI automation codelab for HarmonyOS watches with page navigation assertions, component interactions, screenshot capture and complex gesture tests.
Kits: core ArkUI/Ability kits only. Topics: screenshots, test-automation, ui-testing. SDK: HarmonyOS SDK 6.0.1 (API 21). URL: https://github.com/Explore-In-HMOS/how-to-build-ui-automation

### how-to-build-ui-test-suite
Local and instrumented test suite for HarmonyOS watches using Test Kit Driver, UIEventObserver and UIElementInfo for logic, UI and navigation tests.
Kits: core ArkUI/Ability kits only. Topics: integration-testing, test-kit, ui-testing, unit-testing. URL: https://github.com/Explore-In-HMOS/how-to-build-ui-test-suite

### how-to-build-visibility-render-control
Visibility-aware rendering codelab for HarmonyOS watches with RenderNode drawing, safe-area clipping and selective updates on circular screens.
Kits: core ArkUI/Ability kits only. Topics: clipping, custom-rendering, performance. SDK: HarmonyOS SDK 6.0.1 (API 21). URL: https://github.com/Explore-In-HMOS/how-to-build-visibility-render-control

### how-to-build-visual-effects-pipeline
ArkGraphics2D image-effects codelab for HarmonyOS watches combining shaders, color matrices, image filters, mask glows and text shadows.
Kits: ArkGraphics2D. Topics: arkgraphics2d, image-processing, shaders, visual-effects. URL: https://github.com/Explore-In-HMOS/how-to-build-visual-effects-pipeline

### how-to-build-watch-face-painter
Analog watch-face drawing codelab for HarmonyOS using ArkGraphics2D Canvas, brushes, pens and paths to render dials, bezels and moving hands.
Kits: ArkGraphics2D. Topics: animation, arkgraphics2d, canvas, watch-face. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-build-watch-face-painter

### how-to-control3d-models-with-arkgraphics3d
ArkGraphics3D model control codelab for HarmonyOS demonstrating glTF/GLB scene loading, object rotation, movement and animation control.
Kits: ArkGraphics3D. Topics: 3d-graphics, animation, arkgraphics3d, gltf. URL: https://github.com/Explore-In-HMOS/how-to-control3d-models-with-arkgraphics3d

### how-to-create-arctext
Native C++ arc-text component for HarmonyOS wearables using ArkUI Native Node and native drawing APIs, with size-aware circular text rendering.
Kits: core ArkUI/Ability kits only. Topics: cpp, curved-text, native-development. URL: https://github.com/Explore-In-HMOS/how-to-create-arctext

### how-to-create-curved-text
Reusable curved-text component for HarmonyOS watches using ArkUI Canvas transforms to render labels along circular paths.
Kits: core ArkUI/Ability kits only. Topics: canvas, curved-text, ui-components. URL: https://github.com/Explore-In-HMOS/how-to-create-curved-text

### how-to-create-pin-input
Four-digit PIN input component for HarmonyOS with visual code boxes backed by a single hidden TextInput for continuous keyboard entry.
Kits: core ArkUI/Ability kits only. Topics: forms, pin-input, ui-components. URL: https://github.com/Explore-In-HMOS/how-to-create-pin-input

### how-to-create-purchase-with-iap
IAP Kit purchase-flow codelab for HarmonyOS demonstrating purchase requests, transaction result handling and application state updates.
Kits: IAPKit. Topics: iap-kit, in-app-purchase, payments. SDK: HarmonyOS 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-create-purchase-with-iap

### how-to-draw-graphics
ArkUI graphics codelab for HarmonyOS demonstrating circles, ellipses, lines, paths, polygons and polylines with interactive shape examples.
Kits: core ArkUI/Ability kits only. Topics: shapes, vector-graphics. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-draw-graphics

### how-to-handle-rapid-input
Rapid input codelab for HarmonyOS watches that prevents crashes from repeated taps and crown events with debounce, throttle and re-entrancy guards.
Kits: ArkData. Topics: crash-prevention, debounce, digital-crown, error-manager, input-handling, throttle. SDK: HarmonyOS Stage Model. URL: https://github.com/Explore-In-HMOS/how-to-handle-rapid-input

### how-to-implement-logging-in-c
Native HiLog codelab for HarmonyOS watches logging from C++ with OH_LOG macros, privacy specifiers and Node-API calls from ArkTS.
Kits: core ArkUI/Ability kits only. Topics: cpp, hilog, logging, napi, ndk. URL: https://github.com/Explore-In-HMOS/how-to-implement-logging-in-c

### how-to-implement-swipe-to-refresh-in-arkts-wearable-apps
Pull-to-refresh message list for HarmonyOS watches with a custom refresh header, load-more footer, unread markers and an MVVM mock repository.
Kits: CryptoArchitectureKit. Topics: lists, mvvm, pull-to-refresh. SDK: HarmonyOS SDK 6.1.0(23). URL: https://github.com/Explore-In-HMOS/how-to-implement-swipe-to-refresh-in-arkts-wearable-apps

### how-to-make-button-popup
Button popup codelab for HarmonyOS demonstrating category and amount input followed by a confirmation popup.
Kits: core ArkUI/Ability kits only. Topics: forms, popup. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-make-button-popup

### how-to-make-counter-crown
Digital crown counter sample for HarmonyOS watches demonstrating onDigitalCrown events and reactive increment/decrement controls in ArkUI.
Kits: core ArkUI/Ability kits only. Topics: digital-crown, input-events. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-make-counter-crown

### how-to-make-draggable-masonry-grid
Draggable image grid codelab for HarmonyOS watches with Grid and WaterFlow masonry layouts, long-press reordering and visual drag feedback.
Kits: core ArkUI/Ability kits only. Topics: drag-and-drop, grid-layout, masonry-layout. SDK: HarmonyOS NEXT SDK (Developer Preview). URL: https://github.com/Explore-In-HMOS/how-to-make-draggable-masonry-grid

### how-to-make-light-bulb-game
Light-bulb memory game for HarmonyOS watches with randomized prompts, tap-to-answer interactions, score tracking and toast feedback.
Kits: CryptoArchitectureKit. Topics: game, memory-game. SDK: HarmonyOS SDK. URL: https://github.com/Explore-In-HMOS/how-to-make-light-bulb-game

### how-to-make-timed-random-number
Timed passcode demo for HarmonyOS watches that shows a random one-time code refreshed every 30 seconds on a single ArkUI page.
Kits: core ArkUI/Ability kits only. Topics: one-time-password, random-number-generator, timer. URL: https://github.com/Explore-In-HMOS/how-to-make-timed-random-number

### how-to-make-transportation-app
Localized transportation UI sample for HarmonyOS with driver details, vehicle information, ride endpoints and payment-method views.
Kits: LocalizationKit. Topics: localization, transportation. SDK: HarmonyOS SDK 5.0.0(12). URL: https://github.com/Explore-In-HMOS/how-to-make-transportation-app

### how-to-measure-swipe-speed
Swipe velocity measurement sample for HarmonyOS watches using PanGesture, direction detection, a circular gauge and swipe statistics.
Kits: core ArkUI/Ability kits only. Topics: data-visualization, gesture-recognition, swipe. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-measure-swipe-speed

### how-to-monitor-system-informations
Device information codelab for HarmonyOS watches covering battery status, power APIs, running locks and thermal monitoring.
Kits: core ArkUI/Ability kits only. Topics: battery, device-info, power-management, thermal-monitoring. SDK: HarmonyOS 6.0.0 Beta3. URL: https://github.com/Explore-In-HMOS/how-to-monitor-system-informations

### how-to-properly-implement-scroll-components
Scroll layout codelab for HarmonyOS watches showing correct Scroll height assignment, round-screen safe padding and MVVM dynamic content.
Kits: core ArkUI/Ability kits only. Topics: layout, mvvm, round-screen, scroll. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-properly-implement-scroll-components

### how-to-search-item
Item search codelab for HarmonyOS demonstrating a search box and matching-item results in an ArkTS interface.
Kits: core ArkUI/Ability kits only. Topics: search, ui-components. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-search-item

### how-to-show-snackbar
Snackbar codelab for HarmonyOS watches using PromptAction.showToast and a custom snackbar component with an action button and auto-dismiss.
Kits: core ArkUI/Ability kits only. Topics: snackbar, toast, ui-components. SDK: HarmonyOS SDK 6.0.1(21). URL: https://github.com/Explore-In-HMOS/how-to-show-snackbar

### how-to-use-advanced-typing
Advanced TypeScript typing reference in a HarmonyOS watch project with branded, conditional, mapped and template-literal types for a user domain.
Kits: core ArkUI/Ability kits only. Topics: domain-modeling, type-safety. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-use-advanced-typing

### how-to-use-animation
Introductory ArkUI animation codelab for HarmonyOS demonstrating animation APIs and interactive UI transitions in ArkTS.
Kits: core ArkUI/Ability kits only. Topics: animation, transitions. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-animation

### how-to-use-arc-swiper
ArcSwiper codelab for HarmonyOS watches with circular-screen carousels, swipe animations, gesture control and arc indicators.
Kits: core ArkUI/Ability kits only. Topics: arc-swiper, carousel. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-arc-swiper

### how-to-use-authentication-kit
Authentication Kit sample for HarmonyOS watches demonstrating system PIN verification in an ArkTS application.
Kits: CryptoArchitectureKit, UserAuthenticationKit. Topics: authentication, authentication-kit, pin. URL: https://github.com/Explore-In-HMOS/how-to-use-authentication-kit

### how-to-use-contact-kit-to-create-contact-group
Contact Kit codelab for HarmonyOS demonstrating contact creation, editing and deletion plus contact-group organization.
Kits: ContactsKit. Topics: contact-kit, contacts, crud. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-contact-kit-to-create-contact-group

### how-to-use-device-security-kit
Device Security Kit codelab for HarmonyOS demonstrating local system integrity checks through checkSysIntegrityOnLocal.
Kits: DeviceSecurityKit. Topics: device-security, device-security-kit, system-integrity. URL: https://github.com/Explore-In-HMOS/how-to-use-device-security-kit

### how-to-use-digital-crown
Digital crown input codelab for HarmonyOS watches demonstrating rotation-driven TextPicker and Slider controls for precise UI navigation.
Kits: core ArkUI/Ability kits only. Topics: digital-crown, input-events, ui-components. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-digital-crown

### how-to-use-display
Display API codelab for HarmonyOS watches covering resolution, orientation, refresh rate, brightness and simulated always-on display.
Kits: core ArkUI/Ability kits only. Topics: always-on-display, brightness, display. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-use-display

### how-to-use-drag-and-drop
Drag-and-drop sample for HarmonyOS watches using dragController, a custom drag preview and a compact drop target.
Kits: ArkData. Topics: drag-and-drop, ui-components. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-use-drag-and-drop

### how-to-use-HdsListItemCard
HdsListItemCard usage examples for HarmonyOS watches, demonstrating wearable list-card component configurations in ArkTS.
Kits: UIDesignKit. Topics: hdslistitemcard, ui-components, ui-design-kit. SDK: HarmonyOS SDK 6.0.0(20). URL: https://github.com/Explore-In-HMOS/how-to-use-HdsListItemCard

### how-to-use-performance-analysis-kit
Performance Analysis Kit starter sample for HarmonyOS watches demonstrating device CPU inspection and performance APIs.
Kits: core ArkUI/Ability kits only. Topics: performance-analysis, profiling, system-monitoring. SDK: HarmonyOS 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-performance-analysis-kit

### how-to-use-progress
ArkUI Progress component codelab for HarmonyOS demonstrating configurable progress bars and interactive progress updates.
Kits: core ArkUI/Ability kits only. Topics: progress-bar, ui-components. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-progress

### how-to-use-resources-and-json
Resource management codelab for HarmonyOS reading string/color resources and raw JSON files for localized text, shared colors and data-driven UI.
Kits: core ArkUI/Ability kits only. Topics: json, localization, resource-management. URL: https://github.com/Explore-In-HMOS/how-to-use-resources-and-json

### how-to-use-rich-text-editor
Rich-text note editor sample for HarmonyOS watches with drawing tools, circular controls and safe-area layouts for round screens.
Kits: core ArkUI/Ability kits only. Topics: canvas, notes, rich-text-editor. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-rich-text-editor

### how-to-use-ring-scalering
Countdown timer codelab for HarmonyOS watches comparing RingProgress and ScaleRingProgress visual feedback.
Kits: core ArkUI/Ability kits only. Topics: countdown, progress-ring. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-ring-scalering

### how-to-use-stack
ArkUI Stack codelab for HarmonyOS watches built as a BMI calculator with height/weight input and standard BMI category results.
Kits: core ArkUI/Ability kits only. Topics: bmi-calculator, stack-layout. SDK: HarmonyOS SDK 5.0.0(12). URL: https://github.com/Explore-In-HMOS/how-to-use-stack

### how-to-use-theme
HarmonyOS watch theming sample with light/dark switching, custom color palettes and page-level customization through WithTheme.
Kits: core ArkUI/Ability kits only. Topics: dark-mode, theming. SDK: HarmonyOS SDK "6.0.1(21)". URL: https://github.com/Explore-In-HMOS/how-to-use-theme

### how-to-use-uiability-lifecycle
UIAbility lifecycle codelab for HarmonyOS displaying live creation/destruction and state-transition logs with on-demand refresh.
Kits: core ArkUI/Ability kits only. Topics: lifecycle, logging. SDK: HarmonyOS SDK 5.0.2(14). URL: https://github.com/Explore-In-HMOS/how-to-use-uiability-lifecycle

### how-to-use-vchart
VChart visualization sample for HarmonyOS with examples of multiple chart types using the VisActor Harmony charting package.
Kits: core ArkUI/Ability kits only. Topics: charts, data-visualization, vchart, visactor. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-vchart

### how-to-use-watch-ui-components
ArkUI wearable component showcase for HarmonyOS covering ArcButton, ArcSlider, ArcList, ArcScrollBar, ArcAlphabetIndexer and ArcSwiper.
Kits: core ArkUI/Ability kits only. Topics: arc-list, arc-swiper, ui-components. SDK: HarmonyOS SDK 5.1.0(18). URL: https://github.com/Explore-In-HMOS/how-to-use-watch-ui-components

### how-to-use-weather-kit
Weather UI components for round HarmonyOS watch screens with ArcList layouts, current-condition, forecast and detail cards, and OLED-friendly themes.
Kits: core ArkUI/Ability kits only. Topics: arc-list, ui-components, weather. URL: https://github.com/Explore-In-HMOS/how-to-use-weather-kit
