# MONO Fingerprint SDK

[![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)](https://cocoapods.org/)
[![Swift Version](https://img.shields.io/badge/swift-5.0.x-orange.svg)](https://swift.org)
[![Platforms](https://img.shields.io/badge/platform-ios-green.svg)](https://cocoapods.org/)
[![CocoaPods](https://img.shields.io/badge/Pods-Available-brightgreen.svg)](https://cocoapods.org/)
[![Carthage unavailable](https://img.shields.io/badge/Carthage-unavailable-red.svg)](https://github.com/Carthage/Carthage)

## Features
- Generate unique fingerprint.

## Installation
:heavy_exclamation_mark: iOS 10.0+ target deployment

:heavy_exclamation_mark: SSH key needed : Please provide your 'SSH key' pair to Lead of 'IT Team B' for authorized to production repository

Using [CocoaPods](https://cocoapods.org) Simply add the following line to your Podfile:

```swift
pod 'MonoFingerprintSDK', :git => 'ssh://git@code.mthcdn.com:5422/freezeit/fingerprint-ios-framework.git'
```

## Example
```swift
import MonoFingerprintSDK
```

```swift
MonoFingerprintSDK.shared.getFingerprint(onSuccess: { (fingerprint) in
   print(" ✅ Fingerprint = \(fingerprint)")
}) { (errorMessage) in
   print(" ❌ Error = \(errorMessage)")
}
```

## Author
MIS (IT Team B)

## License
MonoFingerprintSDK is available under the MIT license. See the LICENSE file for more info.
