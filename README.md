# CS_360_Android_Mobile_Programming

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The purpose of the proposed inventory app is to track and update items stored in a warehouse by authorized users to know how much of warehoused items are available and get notified for items running out of stock. To achieve its purpose the app uses a database with two collections/tables, one for item details and another for user details. The app autheniticates existing user or registers new ones before permitting them to use the app, and allow users to turn on or off permission for SMS notifications.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app uses four screens: login/register, Items list, Edit/Add Item, and SMS Notification. The login screen presents a form using a plain-text element to receive username input, a password element to receive password input, and a button element to submit the form. The iventory list screen is be made up of a recycler view to dynamically render all the items in a scrollable vertical list; this screen allows users to add a new item, logout, or manage SMS notification permission form. Each item on the list will use view elements to display item details and an overflow button to allow user edit the item or delete it.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
I used the MVC architecture as a framework for my development. The Inventory database model holds one or more item models created from an SQLite database of inventory items. The four screens have their own views and controllers.

## How did you test to ensure your code was functional? Why is this process important and what did it reveal?
The functionality of the app was tested using the Android screen emulator which allows the app to be used as expected on a real android device. This helps to get a real sense of the user experience produced by the app and to make adjustments as necessary.

## Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
Considering the full process, Implementing the recycler view and the SMS permission preference required some level of innovation.

## In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
Implementing the inventory list view, its controller and the iventory database model using SQLite demonstated my growing knowledge in mobile app development especially in Android.
