# FirstAndroidApp
For Practice Android App Design and Develop

1. Install Android Studio (Include its AVM and some popular API package. e.m. API-19).
2. Create a New Project For Your First App Project.
3. Go to the forlder named "Layout" which location is in "\app\src\main\res\".
  The activity_main.xml was the first View file for your App. You will put your View elements here to bring the best exepirence for your customer.

  All of View files would be build in this folder.
  
  In View file.
  You will need to add a Layout element as base on first step. Then You can put a lot of other elements on it, like TextView , EditView , DropList... etc.

And don't forget setting a primary id for each elements then Control file can easly connectting it.

4. Then go to the folder "java" which would be a child package in a package named as "YourProjectName".
  Here is control file, a control file would connect with a View file and defined lot of eventListener , event , elements connect... etc here. Ofcourse You can building another module and call them in control file.
  
  In Control file.
  You need to check this Control file was connect with correct View file first.
  If you want to get element from View. You need to build a variable for this element and connect it just like JavaScript.
  For Example:
  I want to get EditText Value(most is a string).
  
  EditText editText;
  editText = findViewById(R.id.elementID);
  String getString = editText.getText().toString();
  
  You can create a lot of EventListener here for this View.(Lambda expression would be helpful).
  
5. We got basic View And Control File, also you can build module file for yourself.
  But Most important is a config File named "AndroidManifest.xml".
  
  All your app permission and activity file(control file) needs to wright here for setting.
  
  Without setting permission or activity here, app will be stop when encountering relationed service.
  
  So Please Remember to join your permission or new activity file setting here.
