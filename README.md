# Acoustic PodSpecs

CocoaPods spec repository for the Acoustic mobile SDKs. It replaces CocoaPods
trunk, which becomes permanently read-only on 2 December 2026.

## Usage

Add the source to your `Podfile`, then depend on the pods as before:

```ruby
source 'https://github.com/go-acoustic/PodSpecs.git'
source 'https://cdn.cocoapods.org/'

pod 'AcousticConnect'
```

Swift Package Manager is the recommended integration path. See
https://github.com/go-acoustic/Connect-SP.

## Pods published here

| Pod | Product |
|---|---|
| AcousticConnect, AcousticConnectDebug | Acoustic Connect iOS SDK |
| AcousticMobilePush, AcousticMobilePushNotification, AcousticMobilePushWatch and their Debug variants | Acoustic Campaign mobile push SDK |

Specs are written by CI only. Do not edit by hand.

Copyright (C) 2026 Acoustic, L.P. All rights reserved.
