# BSRadioWaves

![Image](DemoResources/iphone.png)
![Image](DemoResources/watch.png)

## Usage

## To run the project, clone the repo, and run `pod install` from the project directory first.

## API key

1. Register on di.fm
2. Find and install `DI.FM Radio` from the App Store
3. Download and configure `Charles Proxy` for proxing https traffic from iPhone
4. Launch `DI.FM Radio` and find on `Charles Proxy` requests to `api.audioaddict.com`
5. Find your API key in requests

![Image](DemoResources/key.jpg)

6. Insert key into project at line `static let apiKey = ""` and enjoy!

## Requirements
  * iOS 9.0 or higher
  * ARC

## Author

iBlacksus, iblacksus@gmail.com

## License

BSRadioWaves is available under the GNU General Public License v3.0. See the LICENSE file for more info.

# BSRadioWaves is available for personal usage ONLY! Commercial usage is prohibited!