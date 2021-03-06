## MyTasks UIAutomation Demo Project

A simple task list application used to demo the use of UIAutomation for automated functional testing of iOS apps.  

This application accompanies the blog post entitiled 'iOS Functional Testing with UIAutomation' available [here](http://mattmccomb.com/blog/2013/06/02/ios-functional-testing-with-uiautomation/).

![ScreenShot](https://raw.github.com/MattMcComb/MyTasks-UIAutomation-Demo/master/Readme%20Images/mytasks_app_screenshot.png)

## Project Structure

- __/MyTasks__ contains the app source code.
- __/Functional Tests__ contains the UIAutomation test suite.
- __/Functional Tests/TaskList tests.js__ - the UIAutomation test suite containing the functiontal tests for the app.
 
## Executing the Tests

- Clone the repository to your local machine.
- Open the MyTasks sample project in XCode
- Run the app with profiling enabled by selecting Product –> Profile from the menu bar
- In the new Instruments window pick the Automation tool
- Load the test script by selecting Add –> Import… from the left hand pane (Scripts section). In the new finder window navigate to the project directory, open the Functional Tests folder and select the TaskList Tests.js script.
- Switch the active pane from Trace Log to Script and hit the play button to begin execution of the tests.

## Useful Resources
- [Tuneup JS](https://github.com/alexvollmer/tuneup_js)
- [Apple UIAutomation Reference Guide](http://developer.apple.com/library/ios/#documentation/DeveloperTools/Reference/UIAutomationRef/_index.html)
- [Apple Introduction to Accessibility Programming](https://developer.apple.com/library/mac/#documentation/Cocoa/Conceptual/Accessibility/)
