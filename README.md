Brightcove Player SDK Freewheel Sample
====================

### How to Run
This project depends on the Brightcove-Player-SDK and Brightcove-Player-SDK-Freewheel Cocoapods.  Brightcove-Player-SDK-Freewheel Cocoapod is available from the [BCOVSpecs](https://github.com/brightcove/BCOVSpecs) Cocoapods repository.

To install the BCOVSpecs resository, simply call `pod repo add BCOVSpecs https://github.com/brightcove/BCOVSpecs.git` from the commandline.

To run the app, run `pod install` from the root directory. This will install all the required Cocoapods for the project. When finished, open `BCOVSampleFW.xcworkspace` using Xcode 5.1 or above.  

From your Freewheel account, retrieve the Freewheel AdsManager.framework and add it to the project manually. Brightcove is not authorized to distribute this framework, so it is not included in this sample.

