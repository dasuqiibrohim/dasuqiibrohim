![Phone and Tablet Mockup](https://user-images.githubusercontent.com/73922909/113810539-b30f2400-9794-11eb-83e8-9078bf158463.jpg)


# BraWeather - iOS13
A BraWeather-iOS13 project created in Swift using Application Programming Interfaces (APIs) to grab live data from the internet. BraWeather-iOS13 will have made a beautiful, dark-mode enabled weather app. You'll be able to check the weather for the current location based on the GPS data from the iPhone as well as by searching for a city manually.

```
if you love this BraWeather-iOS13, give us a star, you will be an encouragement in our lives.
```

# Requirements
* Xcode 11.
* Swift 5.
* iOS 13 or higher.

# How to Use
### Step 1:

Download or clone this repo by using the link below:

```
https://github.com/dasuqiibrohim/BraWeather-iOS13.git
```

### Step 2:
Open and Create Account [OpenWeather](https://openweathermap.org).

Goto [API keys](https://home.openweathermap.org/api_keys) OpenWeather and copy key. 

And Paste the keys in code below appid.

```
let weatherURL = "https://api.openweathermap.org/data/2.5/weather?appid=07178fe4cc4f075c5c56746321dd7164&units=metric"
```

# BraWeather-iOS 13 Features
* Light and Dark mode.
* Use vector images as image assets.
* Use the UISearchBar to get user input and the delegate pattern.
* Swift protocols and extensions.
* Swift guard keyword.
* Swift computed properties.
* Swift closures and completion handlers.
* Use URLSession to network and make HTTP requests.
* Parse JSON with the native Encodable and Decodable protocols.
* Use Grand Central Dispatch to fetch the main thread.
* Use Core Location to get the current location from the phone GPS.

# Condition Codes
Weather condition from [OpenWeather](https://openweathermap.org/weather-conditions), you can check weather condition from this link.

```
var conditionName: String {
  switch conditionId {
  case 200...232:
    return "cloud.bolt"
   case 300...321:
    return "cloud.drizzle"
   case 500...531:
    return "cloud.rain"
   case 600...622:
    return "cloud.snow"
   case 701...781:
    return "cloud.fog"
   case 800:
    return "sun.max"
   case 801...804:
    return "cloud"
   default:
    return "cloud"
   }
}
```

# Folder Structure
Here is the core folder structure which flutter provides.
```
BraWeather/
|- BraWeather
  |- AppDelegate.swift
  |- SceneDelegate.swift
  |- Model
    |- WeatherManager.swift
    |- WeatherData.swift
    |- WeatherModel.swift
  |- View
    |- Main.storyboard
  |- Controller
    |- ViewController.swift
  |- Assets.xcassets
  |- LaunchScreen.storyboard
  |- Info.plist
|- Products
```

# About Us
I am [Ibrohim Dasuqi](https://github.com/dasuqiibrohim) from indonesia is a Software Developer focused on mobile iOS Developers. If you are interested in working with me, you can contact me via [Linkedin](https://www.linkedin.com/in/dasuqiibrohim/).

# Conclusion
This is a BraWeather-iOS13 our version, if you liked my work don't forget to give a ⭐ star the repo to show your support. if you want to lend a hand with the BraWeather-iOS13 then please feel free to submit an issue and/or pull request. :)
