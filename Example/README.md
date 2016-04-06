# Qwasi Example

The Qwasi `ios-library` provides a convenient method for accessing the Qwasi JSON-RPC API. This example project outlines the proper way to utilize the library, as well as various build settings.

##Requirements:

- Latest version of [XCode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12)
- Latest version of [Cocoapods](https://cocoapods.org)

## Usage
#####There few steps to getting the example project up and running: 

To run the example project: 

1. Clone the [ios-library](https://github.com/qwasi/ios-library.git) repo and navigate to the Example directory.
2. run `pod update` from the Example directory
3. Use *Qwasi.xcworkspace* to open the project
4. Configure the Project with your data:
    - Modify the Qwasi.plist with the apiUrl, apiKey, and appId provided by your account representative.
    - In 'AppDelegate.m' change your USERTOKEN to whatever is desired

Questions?: See the [FAQ](https://github.com/qwasi/ios-library/blob/master/Example/FAQ.md) or read through the [Getting Started Guide](https://github.com/qwasi/ios-library/wiki/getting-started) from the [Wiki](https://github.com/qwasi/ios-library/wiki)
