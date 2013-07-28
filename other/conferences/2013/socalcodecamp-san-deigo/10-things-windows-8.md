# 10 Things I Learned from Building a Windows 8 App

## 1. MVVM Light

* Dependency Injections via ServiceLocator
* Message Passing
* Marshaling data to UI Thread
* Design Time Data made easy!

## 2. Settings Contract

* The charm bar is a unified location in applications for
  preferences/settings/options.
* If a link to a Privacy Policy is not included in the app, then Microsoft
  won't certify you. The settings menu is a great place to put this.

## 3. Share Direction

* Windows 8 makes sharing easy by abstracting the social media APIs
* Two types of sharing in Windows 8
  * Share source
    * You provide information to Windows 8 to share.
  * Share target
    * Your application is an option to share to in Windows 8.

## 4. Search Contact

1. Search box is scoped to the main app on screen
2. Query suggestions provided by the main app on screen.
  * Autocompletes to terms for which the app has search results
3. List of installed Metro style apps that have implemented the search contact

## 5. Responsive Design

* VisualStateManager
* LayoutAwarePage
* Styles applied based on "states"

## 6. File Picker

* Access to files
* Save location
* Real-time updates


## The Rest

Ran out of time before the rest of the presentation.
