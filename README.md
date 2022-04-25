# App Development with Swift
A 90-day training syllabus to learn iOS development for anyone looking to start a career in iOS development.


**Chapters**

1. [Swift Fundamentals](#swift-fundamentals)
2. [Swift Programming Challenges](#swift-programming-challenges)
3. [App Development Bootcamp](#app-development-bootcamp)
4. [Recap Essentials](#recap-essentials)
5. [iOS App Challenge](#ios-app-challenge)

**Duration**

90 Days

---

## Swift Fundamentals

**Description**
To learn the fundamentals of Swift, go through the first 15 days of Hacking with
Swift's "100 Days of Swift" course. This course will teach you how to:
* Understand elements of the Swift standard library
* Learn about Swift’s approach to safety and how to use it to write better apps
* Implement Swift’s functional patterns and utilise extensions to extend “out-of-the-box” functionality
* Learn how Swift manages memory, and contrast this with approaches that other languages take

**Reference**

[The 100 Days of Swift](https://www.hackingwithswift.com/100)

**Challenge**

Submit a playground file containing your own example demonstration of topics covered at the course's ending.

**Duration**

14 days

## Swift Programming Challenges

**Description**

Convert C/C++ programmes to Swift using Playgrounds in order to become acquainted with the Swift programming language and its syntax. You will also get experience working in a playground, Xcode’s prototyping tool.

**Reference**

[C++ Programs - javatpoint](https://www.javatpoint.com/cpp-programs)

**Challenge**

Submit a playground file(s) containing all of the Swift-converted programmes.

**Duration**

7 days

## App Development Bootcamp

**Description**

You will focus on the following main areas of App development in the chapter: • Xcode
* User Interfaces (UIKit)
* Collections(Lists)
* Data persistence 
* Web Services

You will use selected course content from Udemy’s “iOS & Swift - The Complete iOS App Development Bootcamp” course.

**Handpicked Course Content**

* Getting Started with iOS Development and Swift 5
* Xcode Storyboards and Interface Builder
* Xcode Storyboard and Interface Builder Challenge
* Swift Programming Basics - Collections, Constants & Variables 
* Swift Programming Basics Challenge
* Auto Layout and Responsive Uls
* Using and Understanding Apple Documentation
* Intermediate Swift Programming - Control Flow and Optionals 
* iOS App Design Patterns and Code Structuring
* iOS App Design Pattern Challenge
* Advanced Swift Programming - Classes, Inheritance &
* Advanced Optionals
* Advanced Swift Programming Challenge
* Networking, JSON Parsing, APls and Core Location
* Networking and API Challenge
* Firebase Cloud Firestore, TableViews and Cocoapods Dependencies 
* The Command Line and Terminal
* Git, Github and Version Control
* Local Data Persistence - UserDefaults, Core Data and Realm

**Reference**

[iOS & Swift - The Complete iOS App Development Bootcamp](https://www.udemy.com/course/ios-13-app-development-bootcamp)

**Challenge**

Create a Github repository and publish all of the bootcamp course's completed challenges.

**Duration**

21 days

## Recap Essentials

**Description**

Recap the basics of Xcode and UIKit to create native apps for iOS.
Follow the Apple’s iOS App Dev Tutorials and create Today, an app that helps users track their important tasks for the day.

**Contents**

  1. UIKit Essentials
  2. Model-View-Controller 
  3. Navigation 
  4. Table Views and Data Sources 
  5. Editable Cells 
  6. Modality 
  7. Filtering Data 
  8. Design and Animation 
  9. System Frameworks 

**Reference**

[iOS App Dev Training - UIKit](https://developer.apple.com/tutorials/app-dev-training/#uikit-essentials)

> Note: Please ignore SwiftUI Tutorials as they are not part of the syllabus; however, it is a plus to learn them as well ;-)

**Challenge**

1. Introduce an additional enhancement feature to the Today app that makes use of iOS capabilities.
2. Create a Github repository and publish the source code for the Today app. 

**Duration**

14 days

## iOS App Challenge

**Description** 

Complete the randomly assigned iOS app challenge.
1. [Goals](#goals)
2. [Quotes](#quotes)
3. [Bookmarks](bookmarks)

**Duration**

30 days

### Goals

**Description**

Create an app to track goals classified into different categories.

**Features:**

* Allow users to sign in with their Apple ID or Google ID.
* A goal can be tagged with a unique name (examples career, financial, personal etc)
* Goals can be organised into folders by category (examples Life Goals, Daily Goals etc)
* If the user so desires, a goal can be moved to another category
* Deleting a goal category removes all goals associated with it
* Deleting a tag should prompt the user for confirmation before deleting all goals associated with it. The user has the option of deleting only the tag.
* Once created, include the ability to edit a goal, tag, and category.

**Wireframe**
![image](https://user-images.githubusercontent.com/3415400/165108775-bc7c9563-8a35-45b3-b621-8559a6c59cbc.png)

**Notes**

* Using Realm, the app should persist data between app sessions / app relaunches.
* Use RxSwift to implement the MVVM architectural pattern and achieve binding, as well as reactive capabilities where appropriate.
* The code should adhere to the best coding guidelines and practises. 
* App should be universal and compatible with both the iPad and the iPhone. 
* The design is entirely up to you. We want to see how well you can design the UI/UX.

**Challenge**

1. Achieve two-way-sync with the app using Notion API
2. App should re-sync it’s content on “pull to refresh” action. 


### Quotes

**Description**

Create an app to organise favourite quotes into categories.

**Features:**

* Allow users to sign in with their Apple ID or Google ID.
* To add a quote, use Apple's Vision framework to scan the text from an image. After scanning a quote, it can be edited for correctness before being saved.
* A quote can be tagged with author's name
* Quotes can be organised into folders by category (examples Inspirational, Mark Twain, Dark Knight etc)
* If the user so desires, a quote can be moved to another category
* Deleting a quote category removes all quotes associated with it
* Deleting an author should prompt the user for confirmation before deleting all quotes associated with it. The user has the option of deleting only the author.
* Once created, include the ability to edit a quote, author, and category.

**Wireframe**
![image](https://user-images.githubusercontent.com/3415400/165109209-4ec066b7-a507-4ae7-bea2-7abe922763a0.png)

**Notes**

* Using Core Data, the app should persist data between app sessions / app relaunches.
* Use appropriate architectural design pattern.
* The code should adhere to the best coding guidelines and practises. 
* App should be universal and compatible with both the iPad and the iPhone. 
* The design is entirely up to you. We want to see how well you can design the UI/UX.

**Challenge**

1. Achieve two-way-sync with the app using Notion API
2. App should re-sync it’s content on “pull to refresh” action. 


### Bookmarks

**Description**

Create an app that organises web page links into categories.

**Features:**

* * Allow users to sign in with their Apple ID or Google ID.
* To add a link, pre-populate the add link input field with clipboard content only if it’s an URL. Link can be edited for correctness before being saved.
* Use the meta information of the link to display title, description, and image in a list.
* A link can be tagged with unique name (examples tutorial, swift, short read etc)
* Links can be organised into folders by category (examples Good reads, Programming, iOS blogs etc)
* If the user so desires, a link can be moved to another category
* Deleting a link category removes all links associated with it
* Deleting a tag should prompt the user for confirmation before deleting all links associated with it. The user has the option of deleting only the tag.
* Once created, include the ability to edit a link, author, and category.

**Wireframe**
![image](https://user-images.githubusercontent.com/3415400/165109663-eda558cb-d3b3-49ab-83c3-3c3c5d11b20f.png)

**Notes**

* Using Core Data, the app should persist data between app sessions / app relaunches.
* Use appropriate architectural design pattern.
* The code should adhere to the best coding guidelines and practises. 
* App should be universal and compatible with both the iPad and the iPhone. 
* The design is entirely up to you. We want to see how well you can design the UI/UX.

**Challenge**

1. Achieve two-way-sync with the app using Notion API
2. App should re-sync it’s content on “pull to refresh” action. 
