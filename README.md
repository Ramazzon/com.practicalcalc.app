# PracticalCalc

**Construction & Workshop Calculators for Android**

PracticalCalc is a fast, offline-first Android utility app providing practical calculators for construction, DIY, workshop, mechanical, electrical and geometry tasks.

The app is designed to answer small technical questions quickly, without requiring an account, cloud service or permanent internet connection.

## Features

* 30+ practical calculators
* Construction and DIY calculations
* Workshop and mechanical tools
* Electrical calculators
* Geometry calculators
* Unit conversions
* Metric and imperial units
* Calculation history
* Favorites and recently used calculators
* Fast offline search
* Offline-first calculation engine
* Google AdMob banner and interstitial advertising
* Google UMP consent management

## Calculator Categories

### Construction & DIY

* Area and volume
* Concrete
* Slabs
* Paint
* Tiles and flooring
* Materials
* Waste calculations

### Geometry

* Triangle
* Right triangle
* Circle
* Cylinder
* Pythagorean theorem
* Slope and angles

### Workshop & Mechanical

* Torque
* RPM
* Gear ratios
* Pulley ratios
* Thread calculations
* Pressure
* Force
* Density
* Material weight

### Electrical

* Ohm's law
* Power
* Voltage and current
* Resistance
* Energy consumption
* Voltage drop

### Conversions

* Length
* Area
* Volume
* Mass
* Pressure
* Temperature
* Speed
* Torque
* Power

## Design Principles

PracticalCalc follows a few simple principles:

* **Fast:** calculations should take only a few seconds.
* **Offline-first:** core calculations do not require an internet connection.
* **Simple:** every calculator is designed around input → result.
* **Maintainable:** calculator logic is separated from the UI and implemented through reusable components.
* **Low dependency:** no custom backend or cloud infrastructure is required.

## Technology

* Kotlin
* Jetpack Compose
* Material 3
* AndroidX
* Room
* Kotlin Coroutines
* Google Mobile Ads SDK
* Google User Messaging Platform

## Architecture

The application separates:

```text
UI
│
├── Home
├── Search
├── Calculator
├── History
└── Settings
        │
        ▼
Domain / Calculator Engine
        │
        ├── Calculator definitions
        ├── Formula implementations
        ├── Unit conversions
        └── Validation
        │
        ▼
Local Storage
        │
        └── Room / SharedPreferences
```

Advertising and consent management are isolated from the calculator engine.

The application does not require a developer-operated backend for its core functionality.

## Privacy

PracticalCalc stores calculator history, favorites and local preferences on the user's device.

The application does not operate a cloud backend for calculator data.

Advertising is provided through Google Mobile Ads (AdMob), with consent management handled through Google UMP where applicable.

See the published [Privacy Policy](https://YOUR-DOMAIN/privacy-policy.html).

## Disclaimer

Calculation results are provided for informational and planning purposes.

For construction, electrical, mechanical or other safety-critical applications, users should verify results against applicable regulations, standards, manufacturer requirements and professional guidance.

## Project Status

PracticalCalc is currently being prepared for Google Play distribution.

## License

Add the appropriate license here before making the repository publicly reusable.

For a proprietary commercial application, consider explicitly stating that the source code is not licensed for reuse.
