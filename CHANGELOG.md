# XCTest-Gherkin changelog

### Unreleased
+ Added forms of the step definition method with single and double string match parameters

### 0.5.1
+ Fix for parsing native feature files with comments / whitespace (thanks to @smaljaar)

## 0.5.0
+ Add better debugging for native feature file migration (thanks to @smaljaar)
+ Remove bitcode post install script from podfile and migrate to pod 1.0.x syntax
+ Add xcode-ui example (and tests)
+ Add OSX as a target in the podspec (thanks to @pat2man)
+ Remove foundation from the strings extensions (thanks to @dfrib)

### 0.4.4
+ Make debug use NSLog instead of print - get thread safety

### 0.4.3
+ Make the print step definitions debug method not need an instance of XCTestCase in scope

### 0.4.2
+ Fixed another issue in camelcaseify, added tests

### 0.4.1
+ Fixed bug in camelcaseify function, added tests

## 0.4.0
+ Add shared examples

### 0.3.3
+ Fix crash when steps contain optional matching groups and one of them doesn't match 

### 0.3.2
+ printing the steps is case-insensitive order

### 0.3.1
+ Calling printStepDefinitions now returns the steps even if you haven't run any yet. Previously this would only output the steps after the first step had run

## 0.3
+ Make console color default disabled
+ Allow concurrent tests to work using associated objects instead of global state

## 0.2
+ Add support for native feature files

## 0.1
+ Initial release