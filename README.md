# ParseStarterProjectUpdated 2016-08-22
An updated Parse starter project for Rob Percival's iOS9 course projects Instagram, Tinder, etc for deployment on Heroku. Updates & fixes as follows:

Original starter project dated Feb 2016 = http://www.robpercival.co.uk/wp-content/uploads/2016/02/ParseServerStarterProject.zip

Updated & fixed to swift 2 xcode 7.3 = https://github.com/plaudev/ParseStarterProjectUpdated
  This code also has Parse & Bolts framework updated to the latest version v1.14.2 as of July 2016

You need to update heroku keys to your own values Lecture #112 @6:45
  ParseMutableClientConfiguration.applicationId = "myAppId"
  ParseMutableClientConfiguration.clientKey = "myMasterKey"
  ParseMutableClientConfiguration.server = "https://anotherdarntest.herokuapp.com/parse"

Removed both unassigned launch images by right-clicking on them & selecting “remove” in Xcode->Tinder PL->Resources->Images.xcassets->LaunchImage

Removed black bands at top & bottom of screen by changing value to “Main.storyboard” in this field Xcode->Tinder PL->Targets->General->App Icons and Launch Images->Launch Screen File
  Geir’s full instructions here https://www.udemy.com/the-complete-ios-9-developer-course/learn/v4/questions/1460332

To rename the project file structure to what you want (instead of “Tinder PL”) follow instructions here https://developer.apple.com/library/ios/recipes/xcode_help-project_editor/RenamingaProject/RenamingaProject.html
  This changes all the filenames except one which is the folder that contains the .xcodeproj file. To change that one:
  Close the project in xcode
  Change the name of that folder in finder
  The from Xcode->File->Open find & open your .xcodeproj file

