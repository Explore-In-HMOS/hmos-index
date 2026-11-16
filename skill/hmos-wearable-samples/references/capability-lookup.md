# Capability lookup

Read this first to answer "is there a sample for X". Three indexes, each listing every matching project with how-to projects before sample applications:

1. [Smart Wearable kits](#smart-wearable-kits): `@kit.*` imports detected in each project's ArkTS source. The core kits every project uses (AbilityKit, ArkTS, ArkUI, BasicServicesKit, PerformanceAnalysisKit, TestKit) are left out because they do not narrow anything down.
2. [Lite Wearable modules](#lite-wearable-modules): `@system.*` and `@ohos.*` imports in each `sportwatch-` project's JavaScript source.
3. [Topics](#topics): the GitHub topics on each repository, for capabilities that are not a kit, such as `digital-crown`, `heart-rate` or `pull-to-refresh`. Only topics shared by at least 2 projects are listed; every project's own topics are also in its reference entry.

Search this file for the kit, module or topic name rather than reading it whole.

# Smart Wearable kits

## @kit.ArkData (91 projects)
How-to: how-to-build-auto-clear-storage-manager, how-to-build-background-task-scheduler, how-to-build-crash-recovery-guard, how-to-build-data-ability-operations, how-to-build-data-serializer, how-to-build-gesture-drill-board, how-to-build-js-stepper-toolbar, how-to-build-live-widget-factory, how-to-build-local-database, how-to-build-network-firewall-tester, how-to-build-network-usage-dashboard, how-to-build-platform-integration-test, how-to-build-trakinggo-on-harmonyos, how-to-create-card-widgets, how-to-handle-multimodal-gestures, how-to-handle-rapid-input, how-to-implement-self-refreshing-widget, how-to-implement-standalone-network-requests-background-tasks, how-to-implement-theme-aware-swipe-indicators, how-to-make-localization-manager, how-to-use-drag-and-drop, how-to-use-hce, how-to-use-kv-store, how-to-use-qr-health-login-standalone, how-to-use-timer-functionality
Apps: allergy-care, baby-day-tracker, backgammon, barista-recipes, be-fit, bilingual-phrasebook, bmi-calculator, calorie-quest, calorie-tracker, chess, city-taxi, color-switch, daily-food-chose-assistant, daily-horoscope, drive-sense, e-commerce, event-snap, expense-splitter, fall-detector, flash-cards, focus-timer, garden-helper, geo-pulse, goal-pulse, grow-your-pet, habit-timer, habit-tracker, harmony-bird, home-check-app, kokology-game, library-arkorm, local-network-video-player, mail-client, media-player, meet-by-near-link, mini-browser, mood-logger, mr-bulb, near-my-contacts, news-sample, park-pin, personal-finance-vault, picture-guesser-master, quiz-game, reafy, recipe-food-app, rolling-game, sliding-puzzle, smart-home, smart-reminder, smart-scale, smart-word, stack-game-with-unity-tuanjie, swim-statistics, tiny-notes, trip-split, water-tracker, wearable-social-media, weather-app, weather-guess, word-flip, workout-center, world-clock-mini, wrist-auth, wrist-vault, zone-target

## @kit.SensorServiceKit (82 projects)
How-to: how-to-build-3d-watch-face-development, how-to-build-concurrent-lru-cache, how-to-build-gesture-engine, how-to-build-urpc-health-reporter, how-to-create-card-widgets, how-to-get-heart-rate-with-sensorkit, how-to-handle-multimodal-gestures, how-to-implement-adaptive-haptics, how-to-implement-realtime-inclinometer, how-to-implement-sun-exposure-risk, how-to-make-compass-app, how-to-make-smart-lux, how-to-make-sweet-match, how-to-make-wrist-fishing, how-to-show-heart-rate-with-body-sensor, how-to-use-magnetometer, how-to-use-sensorkit-in-wearable, how-to-use-wear-detection-for-workout
Apps: allergy-care, audio-player, backgammon, barista-recipes, be-fit, bmi-calculator, car-game-sample-app, carbon-footprint-step-tracker, city-taxi, context-aware-with-multiple-sensors, daily-dose, daily-food-chose-assistant, daily-horoscope, diabetes-tracker, drive-sense, e-commerce, early-learning, event-snap, fall-detector, fitness-health-kit, flash-cards, golf-helper, grow-your-pet, habit-tracker, harmony-bird, healio, heart-bridge, hi-cycle, innerwave, interval-clock, kitchen-clock-app, kokology-game, library-workoutcore, life-line, mail-client, mind-maze, morse-guard-app, mr-bulb, news-sample, p2p-voice-call, pace-pulse, password-authenticator, peek-and-guess, perfume-collection, pong-game, posture-fixer, qibla-finder, quick-reminder, recipe-food-app, shoot-the-monster, sleep-tracker, sliding-puzzle, smart-reminder, speed-test-app, stock-tracker, sun-exposure-tracker, take-attendance-app, tap-rhythm, tiny-notes, weather-guess, word-game, workout-app, workout-center, zone-target

## @kit.CryptoArchitectureKit (51 projects)
How-to: how-to-build-crown-gesture-navigator, how-to-build-heat-map-explorer, how-to-build-jwt-with-crypto-kit, how-to-build-map-geofence-runner, how-to-build-media-creation-studio, how-to-build-photo-thumbnail-engine, how-to-build-queue-scrollboard, how-to-build-smart-push-dispatcher, how-to-build-swipe-to-refresh, how-to-build-touch-event-handler, how-to-decrypt-with-publickey, how-to-generate-symmetric-keys, how-to-implement-self-refreshing-widget, how-to-implement-swipe-to-refresh-in-arkts-wearable-apps, how-to-make-light-bulb-game, how-to-make-sound-wave, how-to-make-sweet-match, how-to-use-authentication-kit, how-to-use-wear-detection-for-workout
Apps: block-game, brain-game, cacti-hop, car-game-sample-app, coin-and-dice, color-switch, crypto-notes, e-commerce, fasting-app, flash-cards, food-ticket-card, golf-gps-range-finder, guess-the-language, hiking-app, library-app-lock, memory-trainer, mind-maze, morse-guard-app, move-beat, perfume-collection, puzzle-game, reafy, secure-dice-roller, sudoku, tiny-notes, trading-app, transportation, we-authenticator, weather-voice, word-game, wrist-auth, wrist-vault

## @kit.BackgroundTasksKit (48 projects)
How-to: how-to-build-ability-trigger-skills, how-to-build-animatable-transform, how-to-build-background-task-scheduler, how-to-build-web-download-manager, how-to-download-file, how-to-implement-standalone-network-requests-background-tasks, how-to-make-bluetooth-connectivity-monitor, how-to-make-following-app, how-to-make-smart-lux, how-to-send-timed-notification, how-to-use-background-task, how-to-use-background-tasks-kit, how-to-use-timer-functionality
Apps: allergy-care, be-fit, calm-tune, calorie-quest, crown-music, daily-dose, daily-food-chose-assistant, daily-horoscope, diabetes-tracker, drive-sense, early-learning, flowear, goal-pulse, grow-your-pet, kitchen-clock-app, local-network-video-player, mood-logger, move-beat, mr-bulb, music-player, music-player-based-gesture, news-sample, quick-reminder, recipe-food-app, smart-ad-beacon, smart-home, smart-reminder, song-player, sound-map, stock-tracker, tiny-notes, water-tracker, womens-health, workout-app, workout-center

## @kit.NotificationKit (46 projects)
How-to: how-to-build-ability-trigger-skills, how-to-build-network-usage-dashboard, how-to-build-rich-notification-center, how-to-build-smart-push-dispatcher, how-to-download-file, how-to-make-bluetooth-connectivity-monitor, how-to-send-timed-notification, how-to-use-notifications, how-to-use-timer-functionality
Apps: allergy-care, be-fit, calorie-quest, city-taxi, context-aware-with-multiple-sensors, daily-dose, daily-food-chose-assistant, daily-horoscope, diabetes-tracker, early-learning, flowear, food-ticket-card, geo-pulse, goal-pulse, grow-your-pet, kitchen-clock-app, mood-logger, move-tracker, mr-bulb, nearby-eats, news-sample, noise-decibel-meter, parking-timer, quick-reminder, safe-circle, smart-ad-beacon, smart-home, smart-reminder, smart-word, soccer-score, stock-tracker, transportation, water-tracker, way-find, womens-health, workout-app, workout-center

## @kit.AudioKit (39 projects)
How-to: how-to-build-crown-gesture-navigator, how-to-build-haptic-coach, how-to-build-media-creation-studio, how-to-build-podcast-player, how-to-build-volume-control-center, how-to-build-watch-media-player-with-playback-control, how-to-handle-resource-cleanup-in-media-operations, how-to-implement-fft, how-to-implement-peak-hold, how-to-record-audio-over-audio, how-to-record-voice, how-to-use-opuscodec
Apps: audio-player, audio-recorder, calm-tune, crown-music, e-commerce, harmony-bird, innerwave, kitchen-clock-app, local-network-video-player, lynk-puzzle, move-beat, music-player, music-player-based-gesture, noise-decibel-meter, online-fm-radio, p2p-voice-call, podcast-watch-app, quiz-master, serenity-kit, song-player, sound-map, transportation, wear-call, weather-voice, word-game, wv-notes, zone-target

## @kit.MapKit (37 projects)
How-to: how-to-build-advanced-map-overlays, how-to-build-coordinate-toolkit, how-to-build-custom-tile-layers, how-to-build-heat-map-explorer, how-to-build-map-animation-studio, how-to-build-map-camera-zoom, how-to-build-map-geofence-runner, how-to-build-map-overlay-config, how-to-build-poi-cluster-map, how-to-build-route-tracker, how-to-build-trakinggo-on-harmonyos, how-to-convert-address-and-cluster, how-to-create-mapcircle-depends-with-current-location, how-to-display-place-details-on-map, how-to-display-route-with-markers, how-to-implement-routing, how-to-integrate-map-kit, how-to-make-custom-marker-on-map, how-to-make-following-app, how-to-properly-initialize-and-configure-map-kit
Apps: city-taxi, daily-food-chose-assistant, event-snap, geo-pulse, golf-helper, guess-where, hi-cycle, hiking-app, map-explorer, meet-point, offline-map, park-pin, parking-mate, safe-circle, sound-map, track-way, transportation

## @kit.ImageKit (34 projects)
How-to: how-to-build-2d-path-engine, how-to-build-animatable-transform, how-to-build-map-animation-studio, how-to-build-media-creation-studio, how-to-build-micro-poster-renderer, how-to-build-photo-thumbnail-engine, how-to-build-podcast-player, how-to-build-screen-snapshot-tool, how-to-build-smart-push-dispatcher, how-to-build-visual-effects, how-to-build-watch-media-player-with-playback-control, how-to-capture-offscreen-screenshot, how-to-convert-mediakit-units, how-to-generate-qr-code, how-to-integrate-map-kit, how-to-use-call-service-kit, how-to-use-image-effect, how-to-use-qr-health-login-standalone
Apps: calm-tune, calm-yoga, crown-music, demo-auth-scan, event-countdown, event-snap, flashlight, kitchen-clock-app, move-beat, music-player, music-player-based-gesture, smart-dialer, smart-home, song-player, sound-map, track-way

## @kit.LocationKit (31 projects)
How-to: how-to-build-heat-map-explorer, how-to-build-map-geofence-runner, how-to-build-route-tracker, how-to-build-trakinggo-on-harmonyos, how-to-create-mapcircle-depends-with-current-location, how-to-implement-routing, how-to-make-following-app, how-to-show-user-location
Apps: daily-food-chose-assistant, event-snap, geo-pulse, geo-schedule, golf-gps-range-finder, golf-helper, guess-where, hi-cycle, hiking-app, library-workoutcore, location-based-secure-vault, map-explorer, meet-point, move-tracker, nearby-eats, park-pin, parking-mate, qibla-finder, safe-circle, take-attendance-app, track-way, transportation, way-find

## @kit.MediaKit (30 projects)
How-to: how-to-build-media-creation-studio, how-to-build-native-media-player, how-to-build-podcast-player, how-to-build-watch-media-player-with-playback-control, how-to-convert-mediakit-units, how-to-handle-resource-cleanup-in-media-operations, how-to-record-voice, how-to-share-resourcemanager-between-ability-and-components, how-to-use-opuscodec
Apps: audio-player, audio-recorder, calm-tune, crown-music, harmony-bird, kitchen-clock-app, local-network-video-player, lynk-puzzle, move-beat, music-player, music-player-based-gesture, online-fm-radio, pet-training, podcast-watch-app, quiz-master, song-player, sound-map, transportation, word-game, wv-notes, zone-target

## @kit.CoreFileKit (28 projects)
How-to: how-to-build-animatable-transform, how-to-build-cloud-file-sync, how-to-build-media-creation-studio, how-to-build-photo-thumbnail-engine, how-to-build-platform-integration-test, how-to-build-screen-snapshot-tool, how-to-build-web-file-keyboard, how-to-capture-offscreen-screenshot, how-to-handle-resource-cleanup-in-media-operations, how-to-implement-local-file-storage, how-to-monitor-device-storage, how-to-record-audio-over-audio, how-to-record-voice, how-to-show-storage-statistics, how-to-store-and-retrieve-media-files, how-to-track-http-request-progress, how-to-use-opuscodec
Apps: airlines, audio-recorder, clear-watch, guess-the-num, library-portable-debug-panel, library-workoutcore, secure-file-vault, tap-rhythm, wear-engine-hmos-next-wearable-to-phone, weather-voice, wv-notes

## @kit.NetworkKit (28 projects)
How-to: how-to-build-background-task-scheduler, how-to-build-jwt-with-crypto-kit, how-to-build-network-usage-dashboard, how-to-build-podcast-player, how-to-build-smart-push-dispatcher, how-to-check-network-connection, how-to-create-tcp-server, how-to-implement-countly-analytics, how-to-implement-standalone-network-requests-background-tasks, how-to-implement-tcp-connection, how-to-make-rest-api-calls-with-network-kit-in-arkts, how-to-track-http-request-progress, how-to-use-network-kit, how-to-use-qr-health-login-standalone, how-to-use-web-socket
Apps: early-learning, fitness-health-kit, flowear, heart-bridge, near-my-contacts, news-sample, p2p-voice-call, speed-test-app, tic-tac-toe-lan, transportation, wear-call, weather-app, web-browser

## @kit.LocalizationKit (25 projects)
How-to: how-to-build-location-utility-toolkit, how-to-build-media-creation-studio, how-to-build-multilingual-watch, how-to-build-photo-thumbnail-engine, how-to-build-platform-integration-test, how-to-build-podcast-player, how-to-build-smart-push-dispatcher, how-to-convert-mediakit-units, how-to-implement-huks-attestation, how-to-make-transportation-app, how-to-share-resourcemanager-between-ability-and-components, how-to-use-sensorkit-in-wearable
Apps: bilingual-phrasebook, calm-tune, crown-music, e-commerce, event-snap, kitchen-clock-app, library-phone-number-input, move-beat, music-player, music-player-based-gesture, song-player, sound-map, tap-rhythm

## @kit.ArkGraphics2D (17 projects)
How-to: how-to-build-2d-path-engine, how-to-build-3d-material-lighting, how-to-build-micro-poster-renderer, how-to-build-mission-task-switcher, how-to-build-modifier-toolkit, how-to-build-quick-reply-input-deck, how-to-build-typography-showcase, how-to-build-visual-effects, how-to-build-visual-effects-pipeline, how-to-build-watch-face-painter, how-to-handle-multimodal-gestures, how-to-use-image-effect
Apps: calm-tune, calm-yoga, currency-converter, lynk-puzzle, wearable-social-media

## @kit.ConnectivityKit (17 projects)
How-to: how-to-build-bluetooth-device-dashboard, how-to-build-bt-message-phonebook-bridge, how-to-build-nfc-access-badge, how-to-check-network-connection, how-to-control-with-bluetooth, how-to-make-bluetooth-connectivity-monitor, how-to-make-p2p-wifi-connection, how-to-scan-ble, how-to-use-hce, how-to-use-nfc-tag
Apps: beacon-based-attendance, food-ticket-card, p2p-voice-call, safe-zone, smart-ad-beacon, smart-scale, transportation

## @kit.ArkWeb (14 projects)
How-to: how-to-build-arkweb-native-bridge, how-to-build-native-media-player, how-to-build-plugin-routing-framework, how-to-build-web-download-manager, how-to-build-web-file-keyboard, how-to-build-web-permission-console, how-to-build-web-proxy-prefetcher, how-to-build-web-status-handler
Apps: fitness-health-kit, flowear, heart-bridge, mini-browser, web-browser, web-cookie-playground

## @kit.AVSessionKit (13 projects)
How-to: how-to-build-watch-media-player-with-playback-control, how-to-use-call-service-kit, how-to-use-opuscodec
Apps: calm-tune, crown-music, kitchen-clock-app, local-network-video-player, move-beat, music-player, music-player-based-gesture, serenity-kit, song-player, sound-map

## @kit.RemoteCommunicationKit (11 projects)
How-to: how-to-build-urpc-health-reporter, how-to-make-booklist, how-to-make-pagination
Apps: book-store, currency-converter, fitness-health-kit, goal-pulse, near-my-contacts, story-time, tic-tac-toe-lan, wearable-social-media

## @kit.ArkGraphics3D (9 projects)
How-to: how-to-build-3d-material-lighting, how-to-build-3d-model-viewer, how-to-build-3d-post-processing, how-to-build-3d-scene-config, how-to-build-3d-watch-face-development, how-to-control3d-models-with-arkgraphics3d
Apps: e-commerce, n-body-simulation, weather-guess

## @kit.FormKit (9 projects)
How-to: how-to-build-live-widget-factory, how-to-create-card-widgets, how-to-implement-self-refreshing-widget, how-to-use-battery-kit
Apps: e-commerce, event-countdown, mr-bulb, tiny-notes, water-tracker

## @kit.CalendarKit (8 projects)
How-to: how-to-create-calender-picker-in-wearable
Apps: calm-yoga, event-calendar, event-countdown, flowear, geo-schedule, track-way, womens-health

## @kit.WearEngine (7 projects)
How-to: how-to-get-heart-rate-with-sensorkit
Apps: airlines, heart-bridge, innerwave, presentation-remote, wear-engine-hmos-next-wearable-to-phone, zone-target

## @kit.AccountKit (6 projects)
How-to: how-to-build-platform-integration-test
Apps: demo-auth-scan, event-snap, flowear, track-way, transportation

## @kit.TelephonyKit (6 projects)
How-to: how-to-check-network-connection, how-to-initiate-phone-calls-with-telephony-kit, how-to-use-call-service-kit
Apps: city-taxi, smart-dialer, web-browser

## @kit.IAPKit (5 projects)
How-to: how-to-create-purchase-with-iap
Apps: early-learning, health-storage, iap-purchase-subscription-app, transportation

## @kit.ScanKit (5 projects)
How-to: how-to-generate-qr-code, how-to-use-qr-health-login-standalone
Apps: demo-auth-scan, event-snap, track-way

## @kit.AssetStoreKit (4 projects)
How-to: how-to-implement-secure-storage-with-asset-store-kit
Apps: location-based-secure-vault, secure-password-manager, secure-token-locker

## @kit.InputKit (4 projects)
How-to: how-to-build-dynamic-sync-cursor, how-to-build-gesture-engine, how-to-build-screen-snapshot-tool
Apps: daily-food-chose-assistant

## @kit.CallServiceKit (3 projects)
How-to: how-to-use-call-service-kit
Apps: life-line, smart-dialer

## @kit.ContactsKit (3 projects)
How-to: how-to-use-contact-kit-to-create-contact-group
Apps: life-line, smart-dialer

## @kit.IMEKit (3 projects)
How-to: how-to-build-keyboard-switcher, how-to-build-platform-integration-test, how-to-build-web-file-keyboard

## @kit.PushKit (3 projects)
How-to: how-to-build-platform-integration-test, how-to-build-smart-push-dispatcher
Apps: event-snap

## @kit.UserAuthenticationKit (3 projects)
How-to: how-to-use-authentication-kit
Apps: library-app-lock, secure-password-manager

## @kit.AccessibilityKit (2 projects)
How-to: how-to-audit-accessibility-state, how-to-build-platform-integration-test

## @kit.DeviceCertificateKit (2 projects)
How-to: how-to-build-platform-integration-test, how-to-implement-huks-attestation

## @kit.HealthServiceKit (2 projects)
Apps: flowear, healio

## @kit.IPCKit (2 projects)
How-to: how-to-create-card-widgets
Apps: mr-bulb

## @kit.MediaLibraryKit (2 projects)
How-to: how-to-access-system-gallery-on-kids-watch
Apps: wearable-social-media

## @kit.NearLinkKit (2 projects)
How-to: how-to-scan-nearby-devices-by-nearlink-kit
Apps: meet-by-near-link

## @kit.CameraKit (1 project)
How-to: how-to-implement-camera-kit-on-kids-watch

## @kit.CloudFoundationKit (1 project)
Apps: secure-token-locker

## @kit.CoreSpeechKit (1 project)
Apps: e-commerce

## @kit.DeviceSecurityKit (1 project)
How-to: how-to-use-device-security-kit

## @kit.MultimodalAwarenessKit (1 project)
How-to: how-to-build-platform-integration-test

## @kit.NetworkBoostKit (1 project)
Apps: city-taxi

## @kit.ScenarioFusionKit (1 project)
Apps: demo-auth-scan

## @kit.UIDesignKit (1 project)
How-to: how-to-use-HdsListItemCard

## @kit.UniversalKeystoreKit (1 project)
How-to: how-to-implement-huks-attestation

# Lite Wearable modules

## @ohos.router (25 projects)
How-to: sportwatch-how-to-calculate-distance, sportwatch-how-to-implement-file-based-db, sportwatch-how-to-use-hce
Apps: sportwatch-airlines, sportwatch-cacti-hop, sportwatch-city-taxi, sportwatch-coffee-tracker, sportwatch-counttimer-lite, sportwatch-e-commerce, sportwatch-exit-app, sportwatch-fasting-app, sportwatch-food-ticket-card, sportwatch-gmaps-calculate, sportwatch-goal-pulse, sportwatch-golf-gps-range-finder, sportwatch-innerwave, sportwatch-istanbul-travel, sportwatch-morse-guard, sportwatch-moveo, sportwatch-music-controller, sportwatch-pace-pulse-lite, sportwatch-piece-it, sportwatch-quiz-game, sportwatch-throw-the-lines, sportwatch-word-game

## @system.file (19 projects)
How-to: sportwatch-how-to-do-file-operations, sportwatch-how-to-implement-a-custom-navigator, sportwatch-how-to-implement-file-based-db, sportwatch-how-to-read-large-text-files, sportwatch-how-to-use-hce
Apps: sportwatch-airlines, sportwatch-be-fit, sportwatch-city-taxi, sportwatch-encrypted-decrypt-filestore, sportwatch-food-ticket-card, sportwatch-gmaps-calculate, sportwatch-goal-pulse, sportwatch-innerwave, sportwatch-istanbul-travel, sportwatch-lynk-puzzle, sportwatch-moveo, sportwatch-music-controller, sportwatch-tile-guess, sportwatch-zone-target

## @system.app (16 projects)
How-to: sportwatch-how-to-create-dynamic-screen-changes, sportwatch-how-to-create-image-animator, sportwatch-how-to-create-spin, sportwatch-how-to-do-file-operations, sportwatch-how-to-implement-adaptive-layout, sportwatch-how-to-use-app
Apps: sportwatch-encrypted-decrypt-filestore, sportwatch-exit-app, sportwatch-gmaps-calculate, sportwatch-innerwave, sportwatch-moveo, sportwatch-music-controller, sportwatch-piece-it, sportwatch-rolling-game, sportwatch-wear-engine-lite-wearable-to-mobile, sportwatch-weather-now

## @system.vibrator (14 projects)
How-to: sportwatch-how-to-create-dynamic-screen-changes, sportwatch-how-to-derive-linear-acceleration-from-accelerometer-and-gyroscope, sportwatch-how-to-use-vibrator
Apps: sportwatch-be-fit, sportwatch-city-taxi, sportwatch-counttimer-lite, sportwatch-food-ticket-card, sportwatch-innerwave, sportwatch-lynk-puzzle, sportwatch-morse-guard, sportwatch-pace-pulse-lite, sportwatch-parked-here, sportwatch-productivity-timer, sportwatch-zone-target

## @system.router (13 projects)
How-to: sportwatch-how-to-implement-a-custom-navigator, sportwatch-how-to-use-router
Apps: sportwatch-be-fit, sportwatch-goal-pulse, sportwatch-golf-gps-range-finder, sportwatch-music-controller, sportwatch-pace-pulse-lite, sportwatch-productivity-timer, sportwatch-rolling-game, sportwatch-sudoku, sportwatch-wear-engine-lite-wearable-to-mobile, sportwatch-weather-now, sportwatch-zone-target

## @system.sensor (12 projects)
How-to: sportwatch-how-to-build-inclinometer, sportwatch-how-to-derive-linear-acceleration-from-accelerometer-and-gyroscope, sportwatch-how-to-gyro-light, sportwatch-how-to-make-compass-app, sportwatch-how-to-show-heart-rate-and-steps, sportwatch-how-to-use-sensor
Apps: sportwatch-be-fit, sportwatch-innerwave, sportwatch-moveo, sportwatch-pace-pulse-lite, sportwatch-tile-guess, sportwatch-zone-target

## @system.storage (12 projects)
How-to: how-to-build-js-stepper-toolbar, sportwatch-how-to-calculate-distance, sportwatch-how-to-monitor-periods, sportwatch-how-to-use-hce, sportwatch-how-to-use-storage
Apps: sportwatch-be-fit, sportwatch-coffee-tracker, sportwatch-food-ticket-card, sportwatch-lynk-puzzle, sportwatch-parked-here, sportwatch-quiz-game, sportwatch-zone-target

## @system.wearengine (10 projects)
Apps: sportwatch-airlines, sportwatch-city-taxi, sportwatch-food-ticket-card, sportwatch-goal-pulse, sportwatch-innerwave, sportwatch-moveo, sportwatch-music-controller, sportwatch-remote-presentation, sportwatch-wear-engine-lite-wearable-to-mobile, sportwatch-zone-target

## @system.brightness (8 projects)
How-to: sportwatch-how-to-blink-flash, sportwatch-how-to-use-brightness
Apps: sportwatch-city-taxi, sportwatch-food-ticket-card, sportwatch-innerwave, sportwatch-remote-presentation, sportwatch-wear-engine-lite-wearable-to-mobile, sportwatch-zone-target

## @system.device (5 projects)
How-to: sportwatch-how-to-build-scrollable-dynamic-text, sportwatch-how-to-use-device-information
Apps: sportwatch-innerwave, sportwatch-istanbul-travel, sportwatch-lynk-puzzle

## @system.geolocation (5 projects)
How-to: sportwatch-how-to-calculate-distance, sportwatch-how-to-use-geolocation
Apps: sportwatch-gmaps-calculate, sportwatch-parked-here, sportwatch-weather-now

## @ohos.security.huks (3 projects)
How-to: sportwatch-how-to-use-3des, sportwatch-how-to-use-secure-aes-decryption
Apps: sportwatch-encrypted-decrypt-filestore

## @system.battery (3 projects)
How-to: sportwatch-how-to-blink-flash, sportwatch-how-to-implement-battery-indicator, sportwatch-how-to-use-battery

## @ohos.geolocation (2 projects)
How-to: sportwatch-how-to-show-user-location
Apps: sportwatch-golf-gps-range-finder

## @ohos.nfc.cardEmulation (2 projects)
How-to: sportwatch-how-to-use-hce
Apps: sportwatch-food-ticket-card

## @ohos.security.cryptoFramework (1 project)
How-to: sportwatch-how-to-use-crypto-framework

## @system.prompt (1 project)
How-to: how-to-build-js-form-controls

# Topics

## topic: 3d-graphics (6 projects)
How-to: how-to-build-3d-material-lighting, how-to-build-3d-post-processing, how-to-build-3d-scene-config, how-to-build-3d-watch-face-development, how-to-control3d-models-with-arkgraphics3d
Apps: n-body-simulation

## topic: 3des (2 projects)
How-to: how-to-generate-symmetric-keys, sportwatch-how-to-use-3des

## topic: accelerometer (15 projects)
How-to: how-to-build-gesture-engine, how-to-handle-multimodal-gestures, how-to-implement-realtime-inclinometer, sportwatch-how-to-build-inclinometer, sportwatch-how-to-derive-linear-acceleration-from-accelerometer-and-gyroscope, sportwatch-how-to-gyro-light
Apps: car-game-sample-app, drive-sense, fall-detector, harmony-bird, reflex-challenge, shoot-the-monster, sportwatch-tile-guess, swim-statistics, workout-center

## topic: accessibility (3 projects)
How-to: how-to-audit-accessibility-state, how-to-build-focus-accessibility
Apps: weather-voice

## topic: account-kit (3 projects)
How-to: how-to-use-qr-health-login-standalone
Apps: demo-auth-scan, event-snap

## topic: aes (2 projects)
How-to: sportwatch-how-to-use-secure-aes-decryption
Apps: crypto-notes

## topic: ambient-sound (2 projects)
Apps: calm-tune, serenity-kit

## topic: android (7 projects)
How-to: how-to-control-smart-lights-with-harmonyos-and-mqtt
Apps: moveo-mobile, sportwatch-goal-pulse, sportwatch-moveo, sportwatch-wear-engine-lite-wearable-to-mobile, wear-engine-hmos-next-wearable-to-phone, wear-engine-mobile-to-watch

## topic: animation (19 projects)
How-to: how-to-build-animatable-transform, how-to-build-animated-icon-factory, how-to-build-animation-toolkit, how-to-build-dynamic-sync-cursor, how-to-build-map-animation-studio, how-to-build-micro-poster-renderer, how-to-build-watch-face-painter, how-to-control3d-models-with-arkgraphics3d, how-to-make-pulse-animation-console, how-to-make-pulse-ring, how-to-make-sound-wave, how-to-make-sweet-match, how-to-use-animation, sportwatch-how-to-create-marquee, sportwatch-how-to-create-spin
Apps: coin-and-dice, hydration-wave, library-shimmer, sportwatch-exit-app

## topic: app-startup (2 projects)
How-to: how-to-build-autofill-startup, how-to-build-startup-recovery-board

## topic: arc-list (3 projects)
How-to: how-to-use-watch-ui-components, how-to-use-weather-kit
Apps: match-results-tracker

## topic: arc-swiper (3 projects)
How-to: how-to-use-arc-swiper, how-to-use-watch-ui-components
Apps: tiny-notes

## topic: arcade-game (4 projects)
Apps: snake-game, sportwatch-throw-the-lines, stack-game-with-unity-tuanjie, throw-the-lines

## topic: arkdata (32 projects)
How-to: how-to-build-auto-clear-storage-manager, how-to-build-background-task-scheduler, how-to-build-local-database, how-to-build-network-firewall-tester, how-to-implement-self-refreshing-widget, how-to-implement-theme-aware-swipe-indicators, how-to-make-localization-manager, how-to-use-hce, how-to-use-kv-store, how-to-use-timer-functionality
Apps: allergy-care, baby-day-tracker, be-fit, bmi-calculator, coffee-tracker, daily-quotes, expense-splitter, focus-timer, garden-helper, habit-timer, habit-tracker, home-check-app, library-arkorm, mail-client, near-my-contacts, news-sample, park-pin, quiz-game, recipe-food-app, sliding-puzzle, trip-split, wrist-vault

## topic: arkgraphics2d (6 projects)
How-to: how-to-build-2d-path-engine, how-to-build-micro-poster-renderer, how-to-build-mission-task-switcher, how-to-build-typography-showcase, how-to-build-visual-effects-pipeline, how-to-build-watch-face-painter

## topic: arkgraphics3d (8 projects)
How-to: how-to-build-3d-material-lighting, how-to-build-3d-model-viewer, how-to-build-3d-post-processing, how-to-build-3d-scene-config, how-to-build-3d-watch-face-development, how-to-control3d-models-with-arkgraphics3d
Apps: n-body-simulation, weather-guess

## topic: arkweb (10 projects)
How-to: how-to-build-arkweb-native-bridge, how-to-build-native-media-player, how-to-build-web-download-manager, how-to-build-web-file-keyboard, how-to-build-web-permission-console, how-to-build-web-proxy-prefetcher, how-to-build-web-status-handler
Apps: mini-browser, web-browser, web-cookie-playground

## topic: asset-store-kit (3 projects)
How-to: how-to-implement-secure-storage-with-asset-store-kit
Apps: location-based-secure-vault, secure-password-manager

## topic: atomic-services (3 projects)
How-to: how-to-build-atomic-service-launcher, how-to-build-multinav
Apps: parking-mate

## topic: attendance (2 projects)
Apps: beacon-based-attendance, take-attendance-app

## topic: audio-kit (10 projects)
How-to: how-to-build-haptic-coach, how-to-build-volume-control-center, how-to-implement-fft, how-to-implement-peak-hold, how-to-record-audio-over-audio, how-to-use-opuscodec
Apps: audio-player, audio-recorder, p2p-voice-call, wear-call

## topic: audio-player (17 projects)
How-to: how-to-build-media-creation-studio, how-to-build-podcast-player, how-to-build-voice-memo-recorder, how-to-build-watch-media-player-with-playback-control, how-to-record-audio-over-audio
Apps: audio-player, calm-tune, crown-music, move-beat, music-player, music-player-based-gesture, online-fm-radio, pet-training, podcast-watch-app, serenity-kit, song-player, sound-map

## topic: audio-processing (2 projects)
Apps: guitar-tuner, noise-decibel-meter

## topic: audio-recording (6 projects)
How-to: how-to-build-media-creation-studio, how-to-build-voice-memo-recorder, how-to-record-audio-over-audio, how-to-record-voice
Apps: audio-recorder, wv-notes

## topic: authentication (5 projects)
How-to: how-to-build-biometric-auth-button, how-to-use-authentication-kit
Apps: demo-auth-scan, secure-password-manager, wrist-auth

## topic: avplayer (2 projects)
How-to: how-to-handle-resource-cleanup-in-media-operations, how-to-share-resourcemanager-between-ability-and-components

## topic: backgammon (2 projects)
Apps: backgammon, sportwatch-backgammon-game

## topic: background-tasks (21 projects)
How-to: how-to-build-ability-trigger-skills, how-to-build-background-task-scheduler, how-to-build-fault-log-extension, how-to-build-trakinggo-on-harmonyos, how-to-download-file, how-to-make-bluetooth-connectivity-monitor, how-to-make-following-app, how-to-make-smart-lux, how-to-use-background-task, how-to-use-background-tasks-kit
Apps: beacon-based-attendance, calm-tune, crown-music, move-beat, move-tracker, podcast-watch-app, serenity-kit, smart-music-scheduler, smart-reminder, sound-map, swim-statistics

## topic: battery (5 projects)
How-to: how-to-monitor-system-informations, how-to-use-battery-kit, sportwatch-how-to-implement-battery-indicator, sportwatch-how-to-use-battery
Apps: smart-reminder

## topic: beacon (2 projects)
Apps: beacon-based-attendance, smart-ad-beacon

## topic: bill-splitting (3 projects)
Apps: expense-splitter, quick-bill-split, trip-split

## topic: binary-data (3 projects)
How-to: how-to-build-data-serializer, how-to-build-typed-int-arrays, sportwatch-how-to-do-file-operations

## topic: bluetooth (3 projects)
How-to: how-to-build-bluetooth-device-dashboard, how-to-build-bt-message-phonebook-bridge, how-to-make-bluetooth-connectivity-monitor

## topic: bluetooth-low-energy (6 projects)
How-to: how-to-control-with-bluetooth, how-to-scan-ble
Apps: beacon-based-attendance, safe-zone, smart-ad-beacon, smart-scale

## topic: bmi-calculator (2 projects)
How-to: how-to-use-stack
Apps: bmi-calculator

## topic: board-game (4 projects)
Apps: backgammon, chess, sportwatch-backgammon-game, sportwatch-chess

## topic: boarding-pass (2 projects)
Apps: airlines, sportwatch-airlines

## topic: bookmarks (3 projects)
Apps: news-app, news-sample, recipe-food-app

## topic: books (2 projects)
Apps: book-store, story-time

## topic: breathing-exercises (4 projects)
How-to: how-to-make-pulse-ring, how-to-use-particle-for-breath-exercises
Apps: breathing-exercise, sleep-and-relaxation

## topic: brightness (3 projects)
How-to: how-to-use-display, sportwatch-how-to-blink-flash, sportwatch-how-to-use-brightness

## topic: caching (3 projects)
How-to: how-to-build-system-monitor, how-to-build-web-proxy-prefetcher
Apps: weather-app

## topic: caffeine-tracker (2 projects)
Apps: coffee-tracker, sportwatch-coffee-tracker

## topic: calculator (2 projects)
Apps: quick-bill-split, unit-calculator

## topic: calendar (4 projects)
How-to: how-to-create-calender-picker-in-wearable
Apps: event-calendar, event-countdown, geo-schedule

## topic: calendar-kit (5 projects)
Apps: calm-yoga, event-calendar, geo-schedule, smart-music-scheduler, womens-health

## topic: call-service-kit (3 projects)
How-to: how-to-use-call-service-kit
Apps: life-line, smart-dialer

## topic: canvas (14 projects)
How-to: how-to-build-micro-poster-renderer, how-to-build-watch-face-painter, how-to-create-curved-text, how-to-make-sound-wave, how-to-make-wrist-fishing, how-to-use-rich-text-editor, sportwatch-how-to-build-inclinometer
Apps: cacti-hop, car-game-sample-app, pong-game, sportwatch-cacti-hop, sportwatch-parked-here, sportwatch-tower-defense-game, sportwatch-word-game

## topic: card-emulation (2 projects)
How-to: how-to-use-hce, sportwatch-how-to-use-hce

## topic: carousel (2 projects)
How-to: how-to-use-arc-swiper, sportwatch-how-to-create-swiper

## topic: charts (4 projects)
How-to: how-to-use-vchart, sportwatch-how-to-lite-chart
Apps: clear-watch, stock-tracker

## topic: chess (2 projects)
Apps: chess, sportwatch-chess

## topic: clipboard (2 projects)
How-to: how-to-build-round-form-navigator-and-paste-button, how-to-build-security-buttons

## topic: coffee (3 projects)
Apps: barista-recipes, coffee-tracker, sportwatch-coffee-tracker

## topic: collections (2 projects)
How-to: how-to-build-buffered-stream-bench, how-to-build-typed-collections

## topic: compass (6 projects)
How-to: how-to-make-compass-app, sportwatch-how-to-make-compass-app
Apps: golf-helper, qibla-finder, sportwatch-parked-here, way-find

## topic: concurrency (3 projects)
How-to: how-to-build-ability-lifecycle-context, how-to-build-concurrent-lru-cache, how-to-build-typed-collections

## topic: connectivity (2 projects)
How-to: how-to-check-network-connection, how-to-make-bluetooth-connectivity-monitor

## topic: connectivity-kit (6 projects)
How-to: how-to-build-bluetooth-device-dashboard, how-to-build-nfc-access-badge, how-to-use-hce, how-to-use-nfc-tag
Apps: food-ticket-card, safe-zone

## topic: contacts (6 projects)
How-to: how-to-build-bt-message-phonebook-bridge, how-to-build-scroll-filter-list, how-to-use-contact-kit-to-create-contact-group
Apps: meet-by-near-link, near-my-contacts, smart-dialer

## topic: core-file-kit (6 projects)
How-to: how-to-handle-resource-cleanup-in-media-operations, how-to-implement-local-file-storage, how-to-monitor-device-storage, how-to-show-storage-statistics, how-to-store-and-retrieve-media-files
Apps: secure-file-vault

## topic: countdown (5 projects)
How-to: how-to-use-ring-scalering
Apps: event-countdown, kitchen-clock-app, quick-reminder, sportwatch-counttimer-lite

## topic: cpp (5 projects)
How-to: how-to-create-arctext, how-to-implement-logging-in-c, how-to-use-opuscodec
Apps: ndk-opengl, wearable-ndk

## topic: cross-device (2 projects)
How-to: how-to-build-atomic-service-launcher, how-to-build-cross-device-continuation

## topic: crossword (2 projects)
Apps: sportwatch-word-game, word-game

## topic: crud (4 projects)
How-to: how-to-use-contact-kit-to-create-contact-group, sportwatch-how-to-implement-file-based-db, sportwatch-how-to-use-storage
Apps: secure-token-locker

## topic: cryptography (6 projects)
How-to: how-to-decrypt-with-publickey, how-to-generate-symmetric-keys, sportwatch-how-to-use-crypto-framework, sportwatch-how-to-use-secure-aes-decryption
Apps: secure-dice-roller, we-authenticator

## topic: csharp (3 projects)
Apps: chess, rolling-game, stack-game-with-unity-tuanjie

## topic: curved-text (2 projects)
How-to: how-to-create-arctext, how-to-create-curved-text

## topic: custom-rendering (4 projects)
How-to: how-to-build-custom-node-renderer, how-to-build-micro-poster-renderer, how-to-build-render-graphics-pipeline, how-to-build-visibility-render-control

## topic: dark-mode (5 projects)
How-to: how-to-build-dialog-system-config, how-to-build-theme-dark-mode, how-to-implement-theme-aware-swipe-indicators, how-to-use-theme
Apps: quiz-game

## topic: data-structures (3 projects)
How-to: how-to-build-buffered-stream-bench, how-to-build-typed-collections, how-to-build-typed-int-arrays

## topic: data-visualization (4 projects)
How-to: how-to-build-heat-map-explorer, how-to-measure-swipe-speed, how-to-use-vchart, sportwatch-how-to-lite-chart

## topic: database (2 projects)
How-to: sportwatch-how-to-implement-file-based-db
Apps: library-arkorm

## topic: date-picker (2 projects)
How-to: how-to-build-picker-dialogs, how-to-create-calender-picker-in-wearable

## topic: debugging (10 projects)
How-to: how-to-build-app-state-observer, how-to-build-component-event-tracker, how-to-build-crash-recovery-guard, how-to-build-layout-sizing-position, how-to-build-lifecycle-monitor, how-to-build-trace-inspector, how-to-build-web-permission-console, how-to-install-debug-hap-files
Apps: library-portable-debug-panel, web-cookie-playground

## topic: device-capabilities (2 projects)
How-to: how-to-use-nfc-tag, how-to-use-sensorkit-in-wearable

## topic: device-discovery (5 projects)
How-to: how-to-build-bluetooth-device-dashboard, how-to-make-p2p-wifi-connection, how-to-scan-ble, how-to-scan-nearby-devices-by-nearlink-kit
Apps: meet-by-near-link

## topic: device-info (2 projects)
How-to: how-to-monitor-system-informations, sportwatch-how-to-use-device-information

## topic: diagnostics (4 projects)
How-to: how-to-build-network-usage-dashboard, how-to-build-platform-integration-test, how-to-build-system-callback, how-to-build-system-monitor

## topic: dialogs (4 projects)
How-to: how-to-build-dialog-patterns, how-to-build-dialog-system-config, how-to-build-loading-confirm-dialog, how-to-build-picker-dialogs

## topic: dice (2 projects)
Apps: coin-and-dice, secure-dice-roller

## topic: digital-crown (21 projects)
How-to: how-to-build-crown-gesture-navigator, how-to-build-custom-tile-layers, how-to-build-focus-accessibility, how-to-build-map-camera-zoom, how-to-build-reverse-list, how-to-handle-multimodal-gestures, how-to-handle-rapid-input, how-to-make-counter-crown, how-to-monitor-device-storage, how-to-use-digital-crown, sportwatch-how-to-use-crown
Apps: calm-yoga, crown-music, harmony-bird, kokology-game, local-network-video-player, move-beat, perfume-collection, sound-map, stock-tracker, sudoku

## topic: display (2 projects)
How-to: how-to-use-display, sportwatch-how-to-use-brightness

## topic: distance-calculation (2 projects)
How-to: sportwatch-how-to-calculate-distance
Apps: sportwatch-gmaps-calculate

## topic: drag-and-drop (3 projects)
How-to: how-to-build-grid-sort-list, how-to-make-draggable-masonry-grid, how-to-use-drag-and-drop

## topic: ecommerce (3 projects)
Apps: e-commerce, shopping-app, sportwatch-e-commerce

## topic: education (2 projects)
Apps: early-learning, fast-reading-exercises

## topic: educational-game (2 projects)
Apps: morse-guard-app, sportwatch-morse-guard

## topic: encryption (4 projects)
How-to: sportwatch-how-to-use-3des
Apps: crypto-notes, location-based-secure-vault, sportwatch-encrypted-decrypt-filestore

## topic: endless-runner (2 projects)
Apps: cacti-hop, sportwatch-cacti-hop

## topic: error-handling (3 projects)
How-to: how-to-build-crash-recovery-guard, how-to-build-web-status-handler, how-to-handle-resource-cleanup-in-media-operations

## topic: event-driven (3 projects)
How-to: how-to-build-app-lifecycle-hub, how-to-build-podcast-player, how-to-build-system-event-monitor

## topic: event-handling (2 projects)
How-to: how-to-build-component-event-tracker, how-to-build-custom-event-gesture

## topic: event-management (2 projects)
Apps: event-calendar, geo-schedule

## topic: expense-tracker (4 projects)
Apps: expense-splitter, parking-timer, personal-finance-vault, trip-split

## topic: fall-detection (2 projects)
How-to: sportwatch-how-to-derive-linear-acceleration-from-accelerometer-and-gyroscope
Apps: fall-detector

## topic: fasting (2 projects)
Apps: fasting-app, sportwatch-fasting-app

## topic: favorites (4 projects)
Apps: daily-quotes, nearby-eats, perfume-collection, weather-app

## topic: file-io (7 projects)
How-to: how-to-read-raw-file, how-to-store-and-retrieve-media-files, sportwatch-how-to-do-file-operations, sportwatch-how-to-implement-file-based-db, sportwatch-how-to-read-large-text-files
Apps: secure-file-vault, sportwatch-encrypted-decrypt-filestore

## topic: file-transfer (3 projects)
Apps: sportwatch-wear-engine-lite-wearable-to-mobile, wear-engine-hmos-next-wearable-to-phone, wear-engine-mobile-to-watch

## topic: finance (4 projects)
Apps: currency-converter, quick-bill-split, stock-tracker, trading-app

## topic: fitness (16 projects)
How-to: how-to-make-fitness-tracker, how-to-use-wear-detection-for-workout
Apps: be-fit, calm-yoga, calorie-quest, hiking-app, innerwave, interval-clock, library-workoutcore, pace-pulse, sportwatch-be-fit, sportwatch-innerwave, sportwatch-zone-target, workout-app, workout-center, zone-target

## topic: flashcards (2 projects)
Apps: flash-cards, word-flip

## topic: flashlight (2 projects)
How-to: sportwatch-how-to-blink-flash
Apps: flashlight

## topic: flight-status (2 projects)
Apps: airlines, sportwatch-airlines

## topic: football (3 projects)
Apps: goal-pulse, soccer-score, sportwatch-goal-pulse

## topic: form-kit (4 projects)
How-to: how-to-build-live-widget-factory, how-to-create-card-widgets, how-to-implement-self-refreshing-widget
Apps: tiny-notes

## topic: forms (3 projects)
How-to: how-to-build-js-form-controls, how-to-create-pin-input, how-to-make-button-popup

## topic: game (28 projects)
How-to: how-to-make-light-bulb-game, how-to-make-sweet-match, how-to-make-wrist-fishing
Apps: cacti-hop, car-game-sample-app, cocos-game, grow-your-pet, harmony-bird, lynk-puzzle, mind-maze, ndk-opengl, pong-game, puzzle-game, rolling-game, shoot-the-monster, snake-game, sportwatch-cacti-hop, sportwatch-guess-the-num, sportwatch-piece-it, sportwatch-pong-game, sportwatch-quiz-game, sportwatch-rolling-game, sportwatch-tap-the-dot-game, sportwatch-throw-the-lines, sportwatch-tower-defense-game, tap-rhythm, tap-the-dot-game, throw-the-lines

## topic: game-ai (7 projects)
Apps: backgammon, chess, pong-game, sportwatch-backgammon-game, sportwatch-chess, sportwatch-pong-game, xox-game

## topic: gamification (3 projects)
Apps: calorie-quest, early-learning, hydration-wave

## topic: geofencing (5 projects)
How-to: how-to-build-map-geofence-runner
Apps: geo-pulse, location-based-secure-vault, safe-circle, take-attendance-app

## topic: geolocation (10 projects)
How-to: how-to-build-heat-map-explorer, how-to-create-mapcircle-depends-with-current-location, how-to-show-user-location, sportwatch-how-to-calculate-distance, sportwatch-how-to-show-user-location, sportwatch-how-to-use-geolocation
Apps: sportwatch-gmaps-calculate, sportwatch-golf-gps-range-finder, sportwatch-parked-here, sportwatch-weather-now

## topic: gesture-recognition (8 projects)
How-to: how-to-build-crown-gesture-navigator, how-to-build-custom-event-gesture, how-to-build-gesture-drill-board, how-to-build-gesture-engine, how-to-build-touch-gesture-lab, how-to-measure-swipe-speed, sportwatch-how-to-swipe-to-delete
Apps: music-player-based-gesture

## topic: gestures (2 projects)
How-to: how-to-handle-multimodal-gestures, how-to-make-sweet-match

## topic: gltf (4 projects)
How-to: how-to-build-3d-model-viewer, how-to-build-3d-post-processing, how-to-build-3d-scene-config, how-to-control3d-models-with-arkgraphics3d

## topic: golf (3 projects)
Apps: golf-gps-range-finder, golf-helper, sportwatch-golf-gps-range-finder

## topic: gps (9 projects)
How-to: how-to-show-user-location, sportwatch-how-to-calculate-distance, sportwatch-how-to-show-user-location, sportwatch-how-to-use-geolocation
Apps: golf-gps-range-finder, library-workoutcore, sportwatch-gmaps-calculate, sportwatch-golf-gps-range-finder, way-find

## topic: grid-layout (3 projects)
How-to: how-to-build-grid-sort-list, how-to-build-queue-scrollboard, how-to-make-draggable-masonry-grid

## topic: gyroscope (6 projects)
How-to: how-to-implement-realtime-inclinometer, sportwatch-how-to-derive-linear-acceleration-from-accelerometer-and-gyroscope
Apps: drive-sense, fall-detector, mr-bulb, shoot-the-monster

## topic: habit-tracker (3 projects)
How-to: how-to-use-timer-functionality
Apps: habit-timer, habit-tracker

## topic: haptics (31 projects)
How-to: how-to-build-haptic-coach, how-to-implement-adaptive-haptics, how-to-make-following-app, how-to-make-wrist-fishing, how-to-use-sensorkit-in-wearable, sportwatch-how-to-create-dynamic-screen-changes, sportwatch-how-to-use-crown, sportwatch-how-to-use-vibrator
Apps: calm-yoga, color-switch, daily-dose, habit-tracker, kitchen-clock-app, mind-maze, morse-guard-app, news-sample, peek-and-guess, podcast-watch-app, posture-fixer, reflex-challenge, safe-circle, sleep-tracker, sliding-puzzle, speed-test-app, sportwatch-counttimer-lite, sportwatch-lynk-puzzle, sportwatch-morse-guard, sportwatch-pace-pulse-lite, sun-exposure-tracker, take-attendance-app, xox-game

## topic: hce (4 projects)
How-to: how-to-use-hce, sportwatch-how-to-use-hce
Apps: nfc-emulation-app, sportwatch-food-ticket-card

## topic: health-data (6 projects)
How-to: how-to-build-data-ability-operations, how-to-build-urpc-health-reporter
Apps: fitness-health-kit, moveo-mobile, sleep-tracker, sportwatch-moveo

## topic: health-kit (4 projects)
How-to: how-to-use-qr-health-login-standalone
Apps: fitness-health-kit, flutter-healthkit, heart-bridge

## topic: health-tracking (8 projects)
Apps: allergy-care, bmi-calculator, diabetes-tracker, healio, health-storage, sportwatch-innerwave, water-tracker, womens-health

## topic: heart-rate (17 projects)
How-to: how-to-build-urpc-health-reporter, how-to-get-heart-rate-with-sensorkit, how-to-show-heart-rate-with-body-sensor, how-to-use-wear-detection-for-workout, sportwatch-how-to-show-heart-rate-and-steps, sportwatch-how-to-use-sensor
Apps: be-fit, context-aware-with-multiple-sensors, health-storage, heart-bridge, hi-cycle, life-line, pace-pulse, sportwatch-be-fit, sportwatch-pace-pulse-lite, sportwatch-zone-target, zone-target

## topic: hiking (2 projects)
How-to: how-to-build-map-overlay-config
Apps: hiking-app

## topic: hilog (2 projects)
How-to: how-to-implement-logging-in-c
Apps: library-portable-debug-panel

## topic: hmac (2 projects)
How-to: how-to-generate-symmetric-keys
Apps: crypto-notes

## topic: http (3 projects)
How-to: how-to-implement-standalone-network-requests-background-tasks, how-to-make-rest-api-calls-with-network-kit-in-arkts, how-to-track-http-request-progress

## topic: http-client (3 projects)
How-to: how-to-make-booklist, how-to-send-graphql-requests, how-to-use-network-kit

## topic: huks (4 projects)
How-to: how-to-implement-huks-attestation, sportwatch-how-to-use-3des, sportwatch-how-to-use-secure-aes-decryption
Apps: sportwatch-encrypted-decrypt-filestore

## topic: hydration (5 projects)
Apps: calorie-quest, fasting-app, hydration-wave, sportwatch-fasting-app, water-tracker

## topic: iap-kit (2 projects)
How-to: how-to-create-purchase-with-iap
Apps: iap-purchase-subscription-app

## topic: image-kit (5 projects)
How-to: how-to-build-photo-thumbnail-engine, how-to-build-screen-snapshot-tool, how-to-capture-offscreen-screenshot, how-to-integrate-map-kit, how-to-use-image-effect

## topic: image-processing (4 projects)
How-to: how-to-build-photo-thumbnail-engine, how-to-build-visual-effects, how-to-build-visual-effects-pipeline, how-to-use-image-effect

## topic: in-app-purchase (4 projects)
How-to: how-to-create-purchase-with-iap
Apps: health-storage, iap-purchase-subscription-app, transportation

## topic: inclinometer (2 projects)
How-to: how-to-implement-realtime-inclinometer, sportwatch-how-to-build-inclinometer

## topic: input-events (3 projects)
How-to: how-to-make-counter-crown, how-to-use-digital-crown, sportwatch-how-to-use-crown

## topic: input-handling (2 projects)
How-to: how-to-handle-multimodal-gestures, how-to-handle-rapid-input

## topic: insight-intent (2 projects)
How-to: how-to-build-insight-intent, how-to-build-intent-driven-actions

## topic: integration-testing (2 projects)
How-to: how-to-build-platform-integration-test, how-to-build-ui-test-suite

## topic: intents (3 projects)
How-to: how-to-build-ability-trigger-skills, how-to-build-insight-intent, how-to-build-intent-driven-actions

## topic: internationalization (5 projects)
How-to: how-to-build-location-utility-toolkit, how-to-build-multilingual-watch, sportwatch-how-to-use-localization-manager
Apps: bilingual-phrasebook, world-clock-mini

## topic: interval-training (2 projects)
How-to: how-to-make-fitness-tracker
Apps: interval-clock

## topic: iot (5 projects)
How-to: how-to-control-smart-lights-with-harmonyos-and-mqtt, how-to-control-with-bluetooth, how-to-scan-nearby-devices-by-nearlink-kit
Apps: mr-bulb, smart-home

## topic: istanbul (2 projects)
Apps: istanbul-travel-wearable, sportwatch-istanbul-travel

## topic: jetpack-compose (2 projects)
Apps: moveo-mobile, wear-engine-mobile-to-watch

## topic: json (3 projects)
How-to: how-to-read-raw-file, how-to-use-resources-and-json, sportwatch-how-to-read-large-text-files

## topic: jwt (2 projects)
How-to: how-to-build-jwt-with-crypto-kit, how-to-build-smart-push-dispatcher

## topic: key-value-store (5 projects)
How-to: how-to-make-localization-manager, how-to-use-kv-store, sportwatch-how-to-use-storage
Apps: sportwatch-coffee-tracker, sportwatch-quiz-game

## topic: keyboard (2 projects)
How-to: how-to-build-keyboard-switcher, how-to-build-web-file-keyboard

## topic: keyframes (2 projects)
How-to: how-to-build-animation-toolkit
Apps: sportwatch-exit-app

## topic: kids-watch (2 projects)
How-to: how-to-access-system-gallery-on-kids-watch, how-to-implement-camera-kit-on-kids-watch

## topic: kotlin (2 projects)
Apps: moveo-mobile, wear-engine-mobile-to-watch

## topic: language-learning (5 projects)
Apps: bilingual-phrasebook, flash-cards, guess-the-language, smart-word, word-flip

## topic: lazy-loading (2 projects)
How-to: how-to-build-data-prefetch-pipeline, how-to-build-grid-sort-list

## topic: library (6 projects)
Apps: library-app-lock, library-arkorm, library-phone-number-input, library-portable-debug-panel, library-shimmer, library-workoutcore

## topic: lifecycle (12 projects)
How-to: how-to-build-ability-lifecycle-context, how-to-build-app-lifecycle-hub, how-to-build-app-state-observer, how-to-build-component-lifecycle-toolkit, how-to-build-lifecycle-monitor, how-to-build-live-widget-factory, how-to-manage-global-data-during-navigation, how-to-properly-initialize-and-configure-map-kit, how-to-share-resourcemanager-between-ability-and-components, how-to-use-uiability-lifecycle, sportwatch-how-to-use-app
Apps: guess-the-num

## topic: light-sensor (2 projects)
How-to: how-to-make-smart-lux
Apps: sun-exposure-tracker

## topic: lists (9 projects)
How-to: how-to-build-queue-scrollboard, how-to-build-reverse-list, how-to-build-scroll-filter-list, how-to-build-swipe-to-refresh, how-to-implement-swipe-to-refresh-in-arkts-wearable-apps, how-to-make-booklist, how-to-make-pagination, sportwatch-how-to-implement-expandable-list-item, sportwatch-how-to-swipe-to-delete

## topic: local-multiplayer (2 projects)
Apps: backgammon, xox-game

## topic: localization (9 projects)
How-to: how-to-build-location-utility-toolkit, how-to-build-multilingual-watch, how-to-make-localization-manager, how-to-make-transportation-app, how-to-use-resources-and-json, sportwatch-how-to-use-localization-manager
Apps: bilingual-phrasebook, library-phone-number-input, pet-training

## topic: location (12 projects)
How-to: how-to-make-following-app
Apps: city-taxi, daily-food-chose-assistant, event-snap, geo-pulse, golf-helper, meet-point, move-tracker, nearby-eats, parking-timer, qibla-finder, safe-circle

## topic: location-kit (13 projects)
How-to: how-to-build-map-geofence-runner, how-to-build-route-tracker, how-to-build-trakinggo-on-harmonyos, how-to-create-mapcircle-depends-with-current-location, how-to-show-user-location
Apps: geo-schedule, golf-gps-range-finder, hiking-app, location-based-secure-vault, park-pin, parking-mate, take-attendance-app, way-find

## topic: logging (5 projects)
How-to: how-to-build-fault-log-extension, how-to-build-lifecycle-monitor, how-to-implement-logging-in-c, how-to-use-uiability-lifecycle
Apps: library-portable-debug-panel

## topic: lottie (4 projects)
Apps: block-game, coin-and-dice, song-player, workout-app

## topic: map-kit (32 projects)
How-to: how-to-build-advanced-map-overlays, how-to-build-coordinate-toolkit, how-to-build-custom-tile-layers, how-to-build-heat-map-explorer, how-to-build-map-animation-studio, how-to-build-map-camera-zoom, how-to-build-map-geofence-runner, how-to-build-map-overlay-config, how-to-build-poi-cluster-map, how-to-build-route-tracker, how-to-build-trakinggo-on-harmonyos, how-to-convert-address-and-cluster, how-to-create-mapcircle-depends-with-current-location, how-to-display-place-details-on-map, how-to-display-route-with-markers, how-to-implement-routing, how-to-integrate-map-kit, how-to-make-custom-marker-on-map, how-to-properly-initialize-and-configure-map-kit
Apps: city-taxi, daily-food-chose-assistant, event-snap, geo-pulse, golf-helper, guess-where, hiking-app, map-explorer, offline-map, park-pin, parking-mate, sound-map, transportation

## topic: map-markers (5 projects)
How-to: how-to-build-map-animation-studio, how-to-display-place-details-on-map, how-to-display-route-with-markers, how-to-implement-routing, how-to-make-custom-marker-on-map

## topic: map-overlays (5 projects)
How-to: how-to-build-advanced-map-overlays, how-to-build-custom-tile-layers, how-to-build-map-overlay-config, how-to-create-mapcircle-depends-with-current-location, how-to-implement-routing

## topic: map-tiles (2 projects)
How-to: how-to-build-custom-tile-layers
Apps: offline-map

## topic: maps (13 projects)
How-to: how-to-build-advanced-map-overlays, how-to-build-map-camera-zoom, how-to-build-poi-cluster-map, how-to-build-route-tracker, how-to-convert-address-and-cluster, how-to-display-place-details-on-map, how-to-integrate-map-kit, how-to-make-custom-marker-on-map, how-to-parse-gpx-file-for-third-party-map-api, how-to-properly-initialize-and-configure-map-kit
Apps: map-explorer, meet-point, track-way

## topic: marker-clustering (2 projects)
How-to: how-to-build-poi-cluster-map, how-to-convert-address-and-cluster

## topic: media-controls (5 projects)
How-to: how-to-build-crown-gesture-navigator, how-to-build-dynamic-sync-cursor, how-to-build-watch-media-player-with-playback-control
Apps: music-player-based-gesture, sportwatch-music-controller

## topic: media-kit (16 projects)
How-to: how-to-build-media-creation-studio, how-to-build-native-media-player, how-to-build-podcast-player, how-to-build-watch-media-player-with-playback-control, how-to-convert-mediakit-units, how-to-handle-resource-cleanup-in-media-operations
Apps: audio-player, audio-recorder, crown-music, guess-the-language, local-network-video-player, move-beat, music-player, quiz-master, song-player, wv-notes

## topic: media-queries (2 projects)
How-to: sportwatch-how-to-implement-adaptive-layout, sportwatch-how-to-use-media-query

## topic: memory-game (4 projects)
How-to: how-to-make-light-bulb-game
Apps: brain-game, memory-trainer, mind-maze

## topic: messaging (2 projects)
How-to: how-to-build-bt-message-phonebook-bridge
Apps: wear-engine-ios-to-watch-file-message

## topic: microphone (2 projects)
How-to: how-to-implement-peak-hold
Apps: noise-decibel-meter

## topic: mini-games (4 projects)
Apps: brain-game, early-learning, memory-trainer, reafy

## topic: mood-tracking (2 projects)
Apps: flowear, mood-logger

## topic: moon-phase (2 projects)
Apps: daily-horoscope, moon-phases

## topic: morse-code (2 projects)
Apps: morse-guard-app, sportwatch-morse-guard

## topic: multitouch (2 projects)
How-to: how-to-build-touch-gesture-lab, how-to-build-touch-pointer-handler

## topic: mvvm (15 projects)
How-to: how-to-build-border-shape-style, how-to-build-chip-segment-selector, how-to-build-context-menu-editor, how-to-build-js-form-controls, how-to-build-plugin-routing-framework, how-to-implement-local-file-storage, how-to-implement-swipe-to-refresh-in-arkts-wearable-apps, how-to-integrate-map-kit, how-to-make-rest-api-calls-with-network-kit-in-arkts, how-to-properly-implement-scroll-components, how-to-properly-initialize-and-configure-map-kit
Apps: coffee-tracker, golf-gps-range-finder, iap-purchase-subscription-app, kokology-game

## topic: napi (2 projects)
How-to: how-to-implement-logging-in-c
Apps: wearable-ndk

## topic: navigation (10 projects)
How-to: how-to-build-ability-start, how-to-build-multinav, how-to-build-plugin-routing-framework, how-to-build-round-form-navigator-and-paste-button, how-to-create-radial-menu, how-to-manage-global-data-during-navigation, sportwatch-how-to-create-dynamic-screen-changes, sportwatch-how-to-create-radial-menu, sportwatch-how-to-implement-a-custom-navigator, sportwatch-how-to-use-router

## topic: ndk (3 projects)
How-to: how-to-implement-logging-in-c, how-to-use-opuscodec
Apps: ndk-opengl

## topic: nearlink (2 projects)
How-to: how-to-scan-nearby-devices-by-nearlink-kit
Apps: meet-by-near-link

## topic: network-kit (6 projects)
How-to: how-to-build-jwt-with-crypto-kit, how-to-implement-standalone-network-requests-background-tasks, how-to-make-rest-api-calls-with-network-kit-in-arkts, how-to-track-http-request-progress, how-to-use-network-kit
Apps: wear-call

## topic: networking (9 projects)
How-to: how-to-build-network-usage-dashboard, how-to-check-network-connection, how-to-create-tcp-server, how-to-implement-tcp-connection, how-to-make-p2p-wifi-connection, how-to-make-rest-api-calls-with-network-kit-in-arkts, how-to-use-web-socket
Apps: speed-test-app, tic-tac-toe-lan

## topic: news-reader (2 projects)
Apps: news-app, news-sample

## topic: nfc (8 projects)
How-to: how-to-build-nfc-access-badge, how-to-use-hce, how-to-use-nfc-tag, sportwatch-how-to-use-hce
Apps: food-ticket-card, nfc-emulation-app, sportwatch-food-ticket-card, transportation

## topic: notes (5 projects)
How-to: how-to-use-rich-text-editor, sportwatch-how-to-use-localization-manager
Apps: crypto-notes, location-based-secure-vault, tiny-notes

## topic: notification-kit (6 projects)
How-to: how-to-build-rich-notification-center, how-to-build-smart-push-dispatcher, how-to-download-file, how-to-send-timed-notification, how-to-use-notifications
Apps: soccer-score

## topic: notifications (25 projects)
How-to: how-to-build-rich-notification-center, how-to-download-file, how-to-make-bluetooth-connectivity-monitor, how-to-send-timed-notification, how-to-use-notifications
Apps: allergy-care, context-aware-with-multiple-sensors, daily-dose, daily-horoscope, diabetes-tracker, fasting-app, food-ticket-card, geo-pulse, goal-pulse, grow-your-pet, kitchen-clock-app, mood-logger, quick-reminder, safe-circle, smart-ad-beacon, smart-music-scheduler, smart-reminder, smart-word, soccer-score, womens-health

## topic: number-game (2 projects)
Apps: guess-the-num, sportwatch-guess-the-num

## topic: nutrition (2 projects)
Apps: calorie-quest, calorie-tracker

## topic: oauth2 (3 projects)
How-to: how-to-build-jwt-with-crypto-kit, how-to-use-qr-health-login-standalone
Apps: flutter-healthkit

## topic: offline-first (7 projects)
How-to: how-to-build-cloud-file-sync
Apps: garden-helper, moon-phases, pet-training, unit-calculator, wrist-auth, wv-notes

## topic: ohpm (6 projects)
Apps: library-app-lock, library-arkorm, library-phone-number-input, library-portable-debug-panel, library-shimmer, library-workoutcore

## topic: one-time-password (3 projects)
How-to: how-to-make-timed-random-number
Apps: food-ticket-card, password-authenticator

## topic: opengl-es (2 projects)
Apps: ndk-opengl, wearable-ndk

## topic: openharmony (2 projects)
Apps: rolling-game, stack-game-with-unity-tuanjie

## topic: p2p (9 projects)
How-to: how-to-make-p2p-wifi-connection
Apps: moveo-mobile, p2p-voice-call, sportwatch-goal-pulse, sportwatch-wear-engine-lite-wearable-to-mobile, tic-tac-toe-lan, wear-engine-hmos-next-wearable-to-phone, wear-engine-ios-to-watch-file-message, wear-engine-mobile-to-watch

## topic: pagination (2 projects)
How-to: how-to-make-pagination, sportwatch-how-to-implement-file-based-db

## topic: parking (4 projects)
Apps: park-pin, parking-mate, parking-timer, sportwatch-parked-here

## topic: password-manager (2 projects)
Apps: secure-password-manager, wrist-vault

## topic: path-drawing (2 projects)
Apps: lynk-puzzle, sportwatch-lynk-puzzle

## topic: payments (2 projects)
How-to: how-to-create-purchase-with-iap
Apps: food-ticket-card

## topic: pedometer (7 projects)
How-to: sportwatch-how-to-show-heart-rate-and-steps, sportwatch-how-to-use-sensor
Apps: carbon-footprint-step-tracker, habit-tracker, innerwave, pace-pulse, sportwatch-pace-pulse-lite

## topic: performance (2 projects)
How-to: how-to-build-startup-recovery-board, how-to-build-visibility-render-control

## topic: performance-analysis (2 projects)
How-to: how-to-build-trace-inspector, how-to-use-performance-analysis-kit

## topic: performance-monitoring (2 projects)
How-to: how-to-make-pulse-animation-console
Apps: clear-watch

## topic: period-tracker (3 projects)
How-to: sportwatch-how-to-monitor-periods
Apps: flowear, womens-health

## topic: permissions (3 projects)
How-to: how-to-build-security-buttons, how-to-build-web-permission-console, how-to-show-heart-rate-with-body-sensor

## topic: picture-game (2 projects)
Apps: peek-and-guess, picture-guesser-master

## topic: pin-input (2 projects)
How-to: how-to-create-pin-input, sportwatch-how-to-pin-qr

## topic: playlist (2 projects)
Apps: move-beat, music-player

## topic: podcast (2 projects)
How-to: how-to-build-podcast-player
Apps: podcast-watch-app

## topic: points-of-interest (3 projects)
How-to: how-to-build-poi-cluster-map
Apps: map-explorer, touristic-places

## topic: pomodoro (2 projects)
Apps: calm-tune, focus-timer

## topic: pong (2 projects)
Apps: pong-game, sportwatch-pong-game

## topic: popup (3 projects)
How-to: how-to-build-dialog-patterns, how-to-build-popup-tooltip, how-to-make-button-popup

## topic: power-management (3 projects)
How-to: how-to-monitor-system-informations, sportwatch-how-to-use-battery, sportwatch-how-to-use-brightness

## topic: prefetching (2 projects)
How-to: how-to-build-data-prefetch-pipeline, how-to-build-web-proxy-prefetcher

## topic: presentation-remote (2 projects)
Apps: presentation-remote, sportwatch-remote-presentation

## topic: productivity (4 projects)
Apps: focus-timer, habit-timer, home-check-app, sportwatch-productivity-timer

## topic: profiling (2 projects)
How-to: how-to-build-trace-inspector, how-to-use-performance-analysis-kit

## topic: progress-ring (2 projects)
How-to: how-to-build-arc-progress-dashboard, how-to-use-ring-scalering

## topic: proximity (2 projects)
Apps: safe-zone, smart-ad-beacon

## topic: pull-to-refresh (2 projects)
How-to: how-to-build-swipe-to-refresh, how-to-implement-swipe-to-refresh-in-arkts-wearable-apps

## topic: puzzle-game (14 projects)
How-to: how-to-make-sweet-match
Apps: block-game, lynk-puzzle, peek-and-guess, picture-guesser-master, puzzle-game, rolling-game, sliding-puzzle, sportwatch-lynk-puzzle, sportwatch-piece-it, sportwatch-rolling-game, sportwatch-sudoku, sportwatch-tile-guess, sudoku

## topic: qr-code (9 projects)
How-to: how-to-generate-qr-code, how-to-use-qr-health-login-standalone, sportwatch-how-to-implement-and-customize-qr-code, sportwatch-how-to-pin-qr
Apps: demo-auth-scan, istanbul-travel-wearable, sportwatch-food-ticket-card, track-way, we-authenticator

## topic: quiz (8 projects)
Apps: early-learning, guess-the-language, guess-where, kokology-game, quiz-game, quiz-master, sportwatch-quiz-game, weather-guess

## topic: radial-menu (2 projects)
How-to: how-to-create-radial-menu, sportwatch-how-to-create-radial-menu

## topic: random-number-generator (5 projects)
How-to: how-to-make-timed-random-number, sportwatch-how-to-use-crypto-framework
Apps: coin-and-dice, secure-dice-roller, we-authenticator

## topic: reaction-game (5 projects)
Apps: color-switch, reafy, reflex-challenge, sportwatch-tap-the-dot-game, tap-the-dot-game

## topic: recipes (2 projects)
Apps: barista-recipes, recipe-food-app

## topic: relational-database (16 projects)
How-to: how-to-build-auto-clear-storage-manager, how-to-build-data-ability-operations, how-to-build-local-database, how-to-build-network-firewall-tester, how-to-use-timer-functionality
Apps: baby-day-tracker, diabetes-tracker, expense-splitter, health-storage, home-check-app, library-arkorm, near-my-contacts, recipe-food-app, smart-reminder, smart-scale, swim-statistics

## topic: reminders (4 projects)
How-to: how-to-build-ability-trigger-skills, how-to-send-timed-notification
Apps: posture-fixer, quick-reminder

## topic: remote-communication-kit (6 projects)
How-to: how-to-build-urpc-health-reporter, how-to-make-booklist, how-to-make-pagination
Apps: book-store, near-my-contacts, story-time

## topic: remote-control (2 projects)
Apps: presentation-remote, sportwatch-remote-presentation

## topic: resource-management (2 projects)
How-to: how-to-read-raw-file, how-to-use-resources-and-json

## topic: responsive-layout (5 projects)
How-to: how-to-build-flex-layout, how-to-build-responsive-round-layout, how-to-build-split-layout-suite, sportwatch-how-to-build-scrollable-dynamic-text, sportwatch-how-to-use-media-query

## topic: rest-api (2 projects)
How-to: how-to-make-rest-api-calls-with-network-kit-in-arkts
Apps: flutter-healthkit

## topic: restaurants (4 projects)
Apps: daily-food-chose-assistant, event-snap, nearby-eats, travel-app

## topic: rhythm (2 projects)
How-to: how-to-build-haptic-coach
Apps: tap-rhythm

## topic: rotation (2 projects)
How-to: how-to-add-rotating-verifier, sportwatch-how-to-create-spin

## topic: route-tracking (2 projects)
How-to: how-to-build-trakinggo-on-harmonyos
Apps: move-tracker

## topic: route-visualization (3 projects)
How-to: how-to-display-route-with-markers, how-to-parse-gpx-file-for-third-party-map-api
Apps: map-explorer

## topic: rsa (2 projects)
How-to: how-to-decrypt-with-publickey
Apps: sportwatch-encrypted-decrypt-filestore

## topic: rssi (3 projects)
How-to: how-to-scan-ble, how-to-scan-nearby-devices-by-nearlink-kit
Apps: safe-zone

## topic: rtl (2 projects)
How-to: how-to-build-multilingual-watch
Apps: bilingual-phrasebook

## topic: running (3 projects)
How-to: how-to-build-map-geofence-runner
Apps: pace-pulse, sportwatch-pace-pulse-lite

## topic: sandbox (2 projects)
How-to: how-to-implement-local-file-storage, how-to-store-and-retrieve-media-files

## topic: scan-kit (3 projects)
How-to: how-to-generate-qr-code, how-to-use-qr-health-login-standalone
Apps: demo-auth-scan

## topic: screenshots (2 projects)
How-to: how-to-build-screen-snapshot-tool, how-to-build-ui-automation

## topic: scrolling (2 projects)
How-to: how-to-build-queue-scrollboard, sportwatch-how-to-build-scrollable-dynamic-text

## topic: security (4 projects)
How-to: how-to-build-jwt-with-crypto-kit, how-to-implement-huks-attestation, how-to-implement-screenshot-prevention, how-to-implement-secure-storage-with-asset-store-kit

## topic: segmented-control (2 projects)
How-to: how-to-build-shape-segment-button, sportwatch-how-to-create-selection-button

## topic: sensor-fusion (2 projects)
How-to: how-to-implement-realtime-inclinometer, how-to-implement-sun-exposure-risk

## topic: sensor-service-kit (9 projects)
How-to: how-to-handle-multimodal-gestures, how-to-implement-adaptive-haptics, how-to-implement-realtime-inclinometer, how-to-implement-sun-exposure-risk, how-to-make-compass-app, how-to-make-wrist-fishing, how-to-show-heart-rate-with-body-sensor, how-to-use-sensorkit-in-wearable, how-to-use-wear-detection-for-workout

## topic: sensors (29 projects)
How-to: how-to-build-3d-watch-face-development, how-to-build-concurrent-lru-cache, how-to-get-heart-rate-with-sensorkit, how-to-implement-realtime-inclinometer, how-to-make-compass-app, how-to-make-smart-lux, how-to-make-wrist-fishing, how-to-show-heart-rate-with-body-sensor, how-to-use-magnetometer, how-to-use-sensorkit-in-wearable, sportwatch-how-to-build-inclinometer, sportwatch-how-to-derive-linear-acceleration-from-accelerometer-and-gyroscope, sportwatch-how-to-gyro-light, sportwatch-how-to-make-compass-app, sportwatch-how-to-show-heart-rate-and-steps, sportwatch-how-to-use-sensor
Apps: barista-recipes, carbon-footprint-step-tracker, context-aware-with-multiple-sensors, drive-sense, fall-detector, hi-cycle, innerwave, library-workoutcore, life-line, qibla-finder, sportwatch-tile-guess, sun-exposure-tracker, weather-guess

## topic: serialization (2 projects)
How-to: how-to-build-concurrent-lru-cache, how-to-build-data-serializer

## topic: sha256 (2 projects)
Apps: secure-file-vault, wrist-vault

## topic: shaders (2 projects)
How-to: how-to-build-3d-model-viewer, how-to-build-visual-effects-pipeline

## topic: shapes (2 projects)
How-to: how-to-build-shape-segment-button, how-to-draw-graphics

## topic: shopping (3 projects)
Apps: e-commerce, shopping-app, sportwatch-e-commerce

## topic: shopping-cart (2 projects)
Apps: e-commerce, sportwatch-e-commerce

## topic: shortcuts (2 projects)
How-to: how-to-build-autofill-startup, how-to-build-insight-intent

## topic: signal-processing (2 projects)
How-to: how-to-implement-fft, how-to-implement-peak-hold

## topic: simulation (2 projects)
Apps: nfc-emulation-app, wearable-ndk

## topic: sleep-tracking (2 projects)
Apps: sleep-and-relaxation, sleep-tracker

## topic: smart-home (2 projects)
How-to: how-to-control-smart-lights-with-harmonyos-and-mqtt
Apps: smart-home

## topic: smart-lighting (3 projects)
How-to: how-to-control-with-bluetooth
Apps: mr-bulb, smart-home

## topic: sockets (2 projects)
How-to: how-to-create-tcp-server, how-to-implement-tcp-connection

## topic: sports (4 projects)
Apps: goal-pulse, match-results-tracker, soccer-score, sportwatch-goal-pulse

## topic: state-management (7 projects)
How-to: how-to-build-chip-segment-selector, how-to-build-component-lifecycle-toolkit, how-to-build-cross-device-continuation, how-to-build-picker-dialogs, how-to-build-state-persistence, how-to-manage-global-data-during-navigation
Apps: guess-the-num

## topic: state-persistence (2 projects)
How-to: how-to-build-js-stepper-toolbar, how-to-build-state-persistence

## topic: step-counter (3 projects)
How-to: how-to-use-build-variant, how-to-use-qr-health-login-standalone
Apps: fitness-health-kit

## topic: stock-tracker (2 projects)
Apps: stock-tracker, trading-app

## topic: storage (2 projects)
How-to: how-to-monitor-device-storage, how-to-show-storage-statistics

## topic: streaming (4 projects)
How-to: how-to-build-web-download-manager, how-to-play-videos-from-url, sportwatch-how-to-read-large-text-files
Apps: local-network-video-player

## topic: sudoku (2 projects)
Apps: sportwatch-sudoku, sudoku

## topic: swimming (2 projects)
Apps: library-workoutcore, swim-statistics

## topic: swipe (2 projects)
How-to: how-to-measure-swipe-speed, sportwatch-how-to-create-spin

## topic: swipe-to-delete (2 projects)
How-to: sportwatch-how-to-swipe-to-delete
Apps: story-time

## topic: swiper (4 projects)
How-to: how-to-build-dynamic-sync-cursor, how-to-implement-custom-image-based-swiper-indicators, how-to-implement-theme-aware-swipe-indicators, sportwatch-how-to-create-swiper

## topic: system-monitoring (7 projects)
How-to: how-to-build-app-lifecycle-hub, how-to-build-system-callback, how-to-build-system-event-monitor, how-to-build-system-monitor, how-to-use-battery-kit, how-to-use-performance-analysis-kit, sportwatch-how-to-implement-battery-indicator

## topic: task-scheduling (3 projects)
How-to: how-to-build-startup-recovery-board, how-to-use-background-task, how-to-use-background-tasks-kit

## topic: taskpool (2 projects)
How-to: how-to-build-typed-collections, how-to-implement-local-file-storage

## topic: taxi (2 projects)
Apps: city-taxi, sportwatch-city-taxi

## topic: tcp (3 projects)
How-to: how-to-create-tcp-server, how-to-implement-tcp-connection, how-to-use-network-kit

## topic: telephony (3 projects)
How-to: how-to-use-call-service-kit
Apps: city-taxi, smart-dialer

## topic: test-automation (3 projects)
How-to: how-to-build-display-test, how-to-build-platform-integration-test, how-to-build-ui-automation

## topic: test-kit (2 projects)
How-to: how-to-build-display-test, how-to-build-ui-test-suite

## topic: theming (9 projects)
How-to: how-to-build-modifier-toolkit, how-to-build-overlay-dialog, how-to-build-theme-dark-mode, how-to-implement-theme-aware-swipe-indicators, how-to-make-pulse-ring, how-to-make-smart-lux, how-to-use-theme, sportwatch-how-to-implement-battery-indicator
Apps: quiz-game

## topic: tic-tac-toe (2 projects)
Apps: tic-tac-toe-lan, xox-game

## topic: timer (16 projects)
How-to: how-to-make-fitness-tracker, how-to-make-timed-random-number, how-to-use-timer-functionality
Apps: barista-recipes, breathing-exercise, fasting-app, focus-timer, habit-timer, interval-clock, parking-timer, password-authenticator, posture-fixer, quiz-master, sportwatch-counttimer-lite, sportwatch-fasting-app, sportwatch-productivity-timer

## topic: timing-game (2 projects)
Apps: sportwatch-throw-the-lines, throw-the-lines

## topic: touch-events (5 projects)
How-to: how-to-build-custom-event-gesture, how-to-build-gesture-drill-board, how-to-build-touch-event-handler, how-to-build-touch-pointer-handler
Apps: tap-rhythm

## topic: tourism (3 projects)
Apps: sportwatch-istanbul-travel, touristic-places, travel-app

## topic: transitions (3 projects)
How-to: how-to-build-animation-toolkit, how-to-use-animation
Apps: sportwatch-exit-app

## topic: transportation (2 projects)
How-to: how-to-make-transportation-app
Apps: track-way

## topic: travel (9 projects)
Apps: airlines, istanbul-travel-wearable, sportwatch-airlines, sportwatch-istanbul-travel, touristic-places, track-way, travel-app, trip-split, visa-vista

## topic: tuanjie (3 projects)
Apps: chess, rolling-game, stack-game-with-unity-tuanjie

## topic: typography (3 projects)
How-to: how-to-apply-text-typography, how-to-build-mission-task-switcher, how-to-build-typography-showcase

## topic: ui-components (18 projects)
How-to: how-to-build-popup-tooltip, how-to-create-calender-picker-in-wearable, how-to-create-curved-text, how-to-create-pin-input, how-to-implement-custom-image-based-swiper-indicators, how-to-search-item, how-to-show-snackbar, how-to-use-digital-crown, how-to-use-drag-and-drop, how-to-use-HdsListItemCard, how-to-use-progress, how-to-use-watch-ui-components, how-to-use-weather-kit, sportwatch-how-to-create-selection-button, sportwatch-how-to-implement-and-customize-qr-code, sportwatch-how-to-implement-expandable-list-item
Apps: library-phone-number-input, library-shimmer

## topic: ui-testing (3 projects)
How-to: how-to-build-display-test, how-to-build-ui-automation, how-to-build-ui-test-suite

## topic: unity (3 projects)
Apps: chess, rolling-game, stack-game-with-unity-tuanjie

## topic: vchart (2 projects)
How-to: how-to-use-vchart
Apps: clear-watch

## topic: vector-graphics (2 projects)
How-to: how-to-build-2d-path-engine, how-to-draw-graphics

## topic: vibrator (4 projects)
How-to: how-to-implement-adaptive-haptics, how-to-implement-sun-exposure-risk, how-to-make-sweet-match, how-to-use-wear-detection-for-workout

## topic: video-player (3 projects)
How-to: how-to-play-videos-from-url
Apps: local-network-video-player, media-player

## topic: visual-effects (2 projects)
How-to: how-to-build-visual-effects, how-to-build-visual-effects-pipeline

## topic: vocabulary (4 projects)
Apps: flash-cards, smart-word, word-flip, word-game

## topic: voice-recorder (3 projects)
How-to: how-to-build-voice-memo-recorder, how-to-record-voice
Apps: wv-notes

## topic: voip (3 projects)
How-to: how-to-use-call-service-kit
Apps: p2p-voice-call, wear-call

## topic: watch-face (8 projects)
How-to: how-to-build-3d-watch-face-development, how-to-build-animatable-transform, how-to-build-custom-node-renderer, how-to-build-js-stepper-toolbar, how-to-build-multilingual-watch, how-to-build-render-graphics-pipeline, how-to-build-watch-face-painter, sportwatch-how-to-create-image-animator

## topic: water-tracker (2 projects)
Apps: hydration-wave, water-tracker

## topic: wear-engine (15 projects)
How-to: how-to-get-heart-rate-with-sensorkit
Apps: heart-bridge, moveo-mobile, presentation-remote, sportwatch-city-taxi, sportwatch-food-ticket-card, sportwatch-moveo, sportwatch-music-controller, sportwatch-remote-presentation, sportwatch-wear-engine-lite-wearable-to-mobile, sportwatch-zone-target, wear-engine-hmos-next-wearable-to-phone, wear-engine-ios-to-watch-file-message, wear-engine-mobile-to-watch, zone-target

## topic: weather (8 projects)
How-to: how-to-build-background-task-scheduler, how-to-build-live-widget-factory, how-to-use-background-tasks-kit, how-to-use-weather-kit
Apps: sportwatch-weather-now, weather-app, weather-guess, weather-voice

## topic: web-browser (2 projects)
Apps: mini-browser, web-browser

## topic: websocket (3 projects)
How-to: how-to-use-network-kit, how-to-use-web-socket
Apps: wear-call

## topic: webview (8 projects)
How-to: how-to-build-arkweb-native-bridge, how-to-build-native-media-player, how-to-build-web-download-manager, how-to-build-web-file-keyboard, how-to-build-web-permission-console
Apps: mini-browser, web-browser, web-cookie-playground

## topic: wellness (4 projects)
Apps: breathing-exercise, flowear, mood-logger, sleep-and-relaxation

## topic: widgets (8 projects)
How-to: how-to-build-live-widget-factory, how-to-build-shape-segment-button, how-to-create-card-widgets, how-to-implement-self-refreshing-widget, how-to-use-battery-kit
Apps: event-countdown, mr-bulb, tiny-notes

## topic: word-game (2 projects)
Apps: sportwatch-word-game, word-game

## topic: work-scheduler (2 projects)
How-to: how-to-build-background-task-scheduler, how-to-implement-standalone-network-requests-background-tasks

## topic: workout-tracker (11 projects)
How-to: how-to-build-local-database, how-to-use-wear-detection-for-workout
Apps: be-fit, hi-cycle, innerwave, library-workoutcore, sportwatch-be-fit, sportwatch-innerwave, sportwatch-zone-target, swim-statistics, workout-tracker

## topic: xml (2 projects)
How-to: how-to-build-data-serializer, how-to-parse-gpx-file-for-third-party-map-api
