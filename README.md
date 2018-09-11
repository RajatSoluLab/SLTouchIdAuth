# SLTouchIdAuth

[![CI Status](https://img.shields.io/travis/ankitkargathra/SLTouchIdAuth.svg?style=flat)](https://travis-ci.org/ankitkargathra/SLTouchIdAuth)
[![Version](https://img.shields.io/cocoapods/v/SLTouchIdAuth.svg?style=flat)](https://cocoapods.org/pods/SLTouchIdAuth)
[![License](https://img.shields.io/cocoapods/l/SLTouchIdAuth.svg?style=flat)](https://cocoapods.org/pods/SLTouchIdAuth)
[![Platform](https://img.shields.io/cocoapods/p/SLTouchIdAuth.svg?style=flat)](https://cocoapods.org/pods/SLTouchIdAuth)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.
To run the example project, clone the repo, and run `pod install` from the Example directory first.
- Got to project -> target -> Linked framework and library
- Add SLTouchAuth.framework
- import SLTouchAuth in ViewController.swift file
- Put the code.

```ruby
SLTouchIDAuth.shared.openTouchIDAlert { (success, error) in
if error == nil {
// success
} else{
// fail
}
}
```

## Requirements

## Installation

SLTouchIdAuth is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'SLTouchIdAuth'
```

## Author

ankitkargathra, ankit.kargathra@gmail.com

## License

SLTouchIdAuth is available under the MIT license. See the LICENSE file for more info.
