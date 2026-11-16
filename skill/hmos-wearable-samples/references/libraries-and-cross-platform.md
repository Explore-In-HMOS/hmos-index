# Libraries, cross platform and companion projects

10 projects. Each entry: what it demonstrates, the distinctive HarmonyOS kits or system modules it uses, its GitHub topics, the SDK version and the repository URL. Every entry starts with `### <repo-name>`, so search this file for a keyword, kit or topic instead of reading it top to bottom.

## Contents

- [Sensors and Health](#sensors-and-health-sensors-and-health) (2)
- [Connectivity and Network](#connectivity-and-network-connectivity-and-network) (4)
- [Data and Storage](#data-and-storage-data-and-storage) (1)
- [UI and Interaction](#ui-and-interaction-ui-and-interaction) (3)

## Sensors and Health (`sensors-and-health`)

### library-workoutcore
ArkTS sport tracking library for HarmonyOS watches reporting distance, speed, steps, heading, heart rate, swim strokes and swim style.
Kits: CoreFileKit, LocationKit, SensorServiceKit. Topics: fitness, gps, library, ohpm, sensors, swimming, workout-tracker. URL: https://github.com/Explore-In-HMOS/library-workoutcore

### flutter-healthkit
Flutter client for Huawei Health Kit REST APIs with OAuth2, token refresh, data collectors and health-record I/O using Riverpod and Dio.
Kits: not applicable (cross platform). Topics: dart, dio, flutter, health-kit, oauth2, rest-api, riverpod. URL: https://github.com/Explore-In-HMOS/flutter-healthkit

## Connectivity and Network (`connectivity-and-network`)

### library-phone-number-input
ArkTS phone number input library for HarmonyOS with a searchable country code picker, formatting and validation for 200+ countries.
Kits: LocalizationKit. Topics: input, library, localization, ohpm, phone-number, ui-components. URL: https://github.com/Explore-In-HMOS/library-phone-number-input

### moveo-mobile
Android companion for Moveo using Huawei Wear Engine for discovery, connection monitoring and watch-to-phone health-data exchange.
Phone OS: Android. Pairs with: sportwatch-moveo. Topics: android, health-data, jetpack-compose, kotlin, p2p, wear-engine. URL: https://github.com/Explore-In-HMOS/moveo-mobile

### wear-engine-ios-to-watch-file-message
SwiftUI sample for Huawei Wear Engine on iOS with watch messaging, device discovery and app reachability/version checks.
Phone OS: iOS. Pairs with: none, pair with your own watch app. Topics: ios, messaging, p2p, swift, swiftui, wear-engine. URL: https://github.com/Explore-In-HMOS/wear-engine-ios-to-watch-file-message

### wear-engine-mobile-to-watch
Android Wear Engine sample in Kotlin and Jetpack Compose for Huawei watch messaging, file transfer, device discovery and peer-app reachability checks.
Phone OS: Android. Pairs with: none, pair with your own watch app. Topics: android, file-transfer, jetpack-compose, kotlin, p2p, wear-engine. URL: https://github.com/Explore-In-HMOS/wear-engine-mobile-to-watch

## Data and Storage (`data-and-storage`)

### library-arkorm
Type-safe ArkTS ORM library for HarmonyOS with decorators, a fluent query builder, relations, migrations and transactions.
Kits: ArkData. Topics: arkdata, database, library, ohpm, orm, relational-database. URL: https://github.com/Explore-In-HMOS/library-arkorm

## UI and Interaction (`ui-and-interaction`)

### library-app-lock
ArkTS app lock library for HarmonyOS that wraps app content in a lock screen unlocked with face, fingerprint or PIN authentication.
Kits: CryptoArchitectureKit, UserAuthenticationKit. Topics: app-lock, biometric-authentication, library, ohpm, user-authentication-kit. URL: https://github.com/Explore-In-HMOS/library-app-lock

### library-portable-debug-panel
ArkTS debug library for HarmonyOS apps that captures console and hilog output natively, shows it in a floating overlay and saves it as JSONL.
Kits: CoreFileKit. Topics: debugging, developer-tools, hilog, library, logging, ohpm. URL: https://github.com/Explore-In-HMOS/library-portable-debug-panel

### library-shimmer
ArkTS shimmer loading library for HarmonyOS watches that sweeps a highlight across skeleton placeholders while content loads.
Kits: core ArkUI/Ability kits only. Topics: animation, library, ohpm, shimmer, skeleton-loading, ui-components. URL: https://github.com/Explore-In-HMOS/library-shimmer
