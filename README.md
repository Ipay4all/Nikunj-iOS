# iOS-Developer-Coding-Challenge
As the next step in the interview process, we’d like you to complete a coding challenge.

## The Project

You will be building a beta version of a Virtual Product Management (VPM) APP. There's a postman collection in this repository, Access token is required to get product details based on the country UAE. You will need to take product data and persist it in a backend database. You will then develop a backend API, to be called upon by your frontend, which will display the data. This dashboard should allow registration and login of a user, requiring a password, and the user's credentials should also be persisted in your database.

The result should be a dashboard with two pages (the application can be single-page (SPA), or multiple pages):

* A registration/login page
* A main page that displays products with details well formatted 
* User should be able to add products, update details and delete products 

## Goals

> Keep in mind that **there are no tricks**: each of these expectations are both able to be met, and justifiable development approaches given the challenge. 

In order to set transparent expectations, the following list enumerates the *minimum* concepts that we expect to see demonstrated when evaluating your submission.

- Demonstrated mastery of advanced programming concepts in swift for Apple platforms, including
	- MVC application architecture
		- Most-importantly: fully XCTest-able view controllers & classes (aka independent business logic from the UI / IB interface)
	- Protocol-oriented programming
	- Object-oriented programming
	- Generics
	- UIScene delegation in iOS 13.*
	- Class, object, and attribute privacy and access-control levels
	- The Codable protocol
	- Working with RESTful APIs & raw JSON data
	- URLSession & native networking in Swift
	- Demonstrated experience working with data structures that are relevant to the challenge if any

- Demonstrated experience with Xcode environments / schemes, & application capabilities, including:
	- Shared schemes
	- Elimination of OS activity debugger logs
	- Sourcing environment variables from the Xcode env when running a target as debug
	- Location services capabilities, including entitlement requirements, plist requirements, & user-permission requests / handling.
	- Enabling XCTest code coverage calculations *for the framework target only*.

- Working knowledge & experience with fully cross-platform, cross-technology framework development techniques, including:
	- Full support for both Cocoapods & Swift Package Manager in a single framework repository
	- Full support for **all** Xcode-supported device classes, *including* macOS (aka macCatalyst).
	- Cocoapod framework development with bundled resources
	- Proper referencing of resource bundles that are not part of the main bundle (located within a framework’s bundle and properly sourced from the framework vs main bundle).
	- 0 third party dependencies for custom frameworks
	- Development of an example application that fully implements the project’s cocoapod framework


- Demonstrate experience with advanced Interface-builder concepts, including:
	- Strategies for proper sourcing & instantiation of interface builder .xib & .storyboard files that belong to an encapsulated framework
	- Variable autolayout traits for universal applications (iOS & iPadOS) that support all device classes & device orientations

- Clean-code practices, including
	- Single responsibility principal (SRP)
	- Avoidance of overly complex code and common pitfalls such as cyclomatic dependencies, repeated code, large function signatures, very long lines of code, etc.
	- Standard, quick-help & apple supported documentation of objects, extensions, object attributes, etc.-- especially if parameters or return types are specified in a function signature or initializer.

- Advanced experience using Xcode’s XCTest Suite, including:
	- 100% code coverage in XCTests for the framework target
	- Writing XCTests with expectations to succeed.
	- Writing XCTests with expectations to fail.
	- Expecation / Wait / fulfill for asynchronus testing processes.
	- Recording & running UITests using the framework’s example application.


## Preparing Your Local Development Env

- Make sure you have [enabled signed commits with a GPG key](#signed-commits-with-gpg) on any machine you use during your submission. 
	- 100% signed commits are required for any submission to be evaluated.
- Check your local version of Xcode
	- The very **latest release version** of Xcode is required.
		- Beta versions of Xcode should **not** be used.
- Check your local swift version.
	- **Swift version 5.2 (or higher)** (installed with latest Xcode)
- Check your local swift-tools version.
	- **Swift-Tools version 5.2 (or higher)** is required
	- Install from [Swift.org](https://swift.org) if your local tools are not 5.2 or higher (should be by default when installing Xcode)
- The targeted iOS version for any submission should be **iOS 13.0**
	- In general, make sure to double check your project settings.
	- There is a starter project with some of this configured already, but you’ll need to make sure the final matches the requirements.

All of the goals and requirements for your local ENV and general performance of work enumerated here are the *same* as what you will need to perform the work on a day-to-day basis, so consider this challenge as both a test of your skills, and an orientation to our development workflow for senior engineers. (aka, no lost time if you do end up joining the team).

**Git**
* Maintain code on git (github/gitlab).
* Push code with proper commits.
* Create feature branch for each push (registration, dashboard).
* Create a conflict and resolve.

  
## Additional Information
* Have fun and be as creative as you like!
* Please feel free to reach out to ask any questions (rtahir@ipay4all.com).

## How to submit this challenge (Optional):
1. Fork this repository
2. Work on your solution
3. Deploy the frontend and backend of your application using free services (Netlify, Heroku, etc).
4. Create a pull request as the reviewer.

## Timeframe

We would like the take home challenge to be completed within 1.5 hours. If you need more time, please reach out to us. You will not be judged on how quickly you complete the challenge.
