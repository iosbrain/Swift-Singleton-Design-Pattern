# Swift-Singleton-Design-Pattern
An Xcode 9 project, written in Swift 4, demonstrating how to implement the singleton design pattern.

In this repo and [accompanying tutorial](http://iosbrain.com/blog/2018/07/31/two-creational-design-patterns-in-swift-4-factory-method-and-singleton/), I explain the singleton design pattern, good for protecting shared resources, providing access to some system which contains one and only one instance of an object, supporting one object which performs some type of app-wide coordination, and, as we’ll see here, can be good for providing a value-added wrapper of a built-in iOS singleton.

Here's the app -- resulting from building this project in Xcode -- in action:

![alt text][logo1]

[logo1]: http://iosbrain.com/wp-content/uploads/2018/07/Show_Pwd-1.gif "Singleton"

## Xcode 9 project settings
**To get this project running on the Simulator or a physical device (iPhone, iPad)**, go to the following locations in Xcode and make the suggested changes:

1. Project Navigator -> [Project Name] -> Targets List -> TARGETS -> [Target Name] -> General -> Signing
- [ ] Tick the "Automatically manage signing" box
- [ ] Select a valid name from the "Team" dropdown
  
2. Project Navigator -> [Project Name] -> Targets List -> TARGETS -> [Target Name] -> General -> Identity
- [ ] Change the "com.yourDomainNameHere" portion of the value in the "Bundle Identifier" text field to your real reverse domain name (i.e., "com.yourRealDomainName.Project-Name").

