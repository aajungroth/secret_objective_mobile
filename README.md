# secret_objective_mobile

# ios/secret_objective_mobile.xcodeproj/project.pbxproj 

Quote from Stack Overflow:
This file holds the list of all the files in the project, settings of targets and which files belong to which targets. It's probably the meatiest file in project bundle. You should not ignore this file.

See this post:
https://stackoverflow.com/questions/8026429/should-i-git-ignore-xcodeproject-project-pbxproj-file#:~:text=This%20file%20holds%20the%20list,should%20not%20ignore%20this%20file.

# Testing on a physical iPhone
Currently the easiest way is to test on iPhone is to build to an actual iphone.
A developer account is needed, so an apple ID. 
A iPhone plugged into a Mac with X-Code installed by USB cable will work. 
Change the build target in X-Code to be the connected iPhone.
Run the build. 
Select the developer account if not already added in X-Code. 
Once the build finishes, on iPhone go to settings > general > VPN & Device Management > approve the developer app
The app should be installed and usuable for testing. 
