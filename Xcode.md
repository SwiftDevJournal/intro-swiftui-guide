# Installing Xcode

[Xcode](https://developer.apple.com/xcode/) is Apple's tool for developing apps for iOS, Mac, tvOS, and watchOS. To go through this guide, you should install Xcode.

## System Requirements

To follow this guide you must install Xcode 12 or above. Xcode 12.4 requires a Mac running macOS 10.15 or above. Xcode 12.5 and Xcode 13 require macOS 11 or above.

## Where do I get Xcode?

You can install the latest version of Xcode from the Mac App Store. The latest version of Xcode may require the latest version of macOS.

To get an older version of Xcode, go to Apple's [Downloads and Resources page](https://developer.apple.com/xcode/resources/) . The site [Xcode Releases](https://xcodereleases.com) has direct download links for every version of Xcode Apple has ever released.

## The App Store says I don't have enough space to install Xcode, but I do. How do I fix this?

Free up more disk space on your Mac. You need 4-5 times the size of the Xcode download to install Xcode.

If Apple is telling you that you don't have enough space to install Xcode, you don't have enough space. A mistake many people make is comparing the Xcode download size to the amount of free space on their Mac. But the Xcode file you're downloading is a compressed file. The operating system has to expand the file. While expanding the file, the operating system needs space for both the compressed and expanded files.

### How do I free up space?

The app [DevCleaner for Xcode](http://www.one-minute-games.com/portfolio/dev-cleaner/) can free up space by removing caches and old simulator files that build up over time.

If you still don't have enough free space and have an existing version of Xcode on your Mac, delete it. This will free up space, but it will make an App Store Xcode installation take longer because it will have to download the entire Xcode file instead of performing a delta update, where only the parts that need to be updated are downloaded.

### Can I install Xcode on an external drive?

Xcode must be installed on your Mac’s startup disk. If you make an external drive the startup disk, you can install Xcode on an external drive. Use the System Preferences app (Choose Apple > System Preferences from the menu bar) to set the startup disk.

## I don't have a Mac

If you have an iPad running iOS 15 or later, you can use the [Swift Playgrounds app](https://apps.apple.com/us/app/swift-playgrounds/id908519492) to develop SwiftUI apps.
