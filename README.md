## Introduction :-
A-IDE is an Android App IDE for Android.  it creates Android Project, Builds Android X and uses latest AndroidX and Material Design Mavens Libraries, The output apk will be run smoothly, it uses D8, ECJ, Apksinger, Manifest Merger And Latest android.jar 31 etc.

## Getting Started :-
These steps will show you How to Create and Run the Project, There is a bug while creating Android Project. So it's can be solved by renaming the layout name in MainActivity.java, Here You can see :-

>>>setContentView(R.layout.activity_main.xml);

So we have to change the layout/activity_main.xml to layout/activity_main

 it will no errors.

## Building :-
When Created the Android Project and do all first proccess and simply click on Merge icon, it will start merging all manifests, then click on run Play icon to build the project, don't forget to remove (.xml) in MainActivity.java (R.layout.*.xml); if it gives error you will see a error dialog.

Note: Manifest Merger Should be Installed on Device otherwise it will not work anymore,

May be in updates it will be removed.

on Build Successful you need to give permission for installing apps for A-IDE

## Features
Now It's spporting External Libraries

Next Update Module Zip for Aab

Stay Tuned :- For More Upcoming Updates


