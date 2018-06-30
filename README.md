# XYZ Reader project in Udacity's Android Nanodegree.

### Phone
<img src="https://user-images.githubusercontent.com/1282659/40888581-f8ccb11e-671e-11e8-8c36-1622fc6b7e3c.png" width="200"><img src="https://user-images.githubusercontent.com/1282659/40891661-8f4996b8-674f-11e8-96f7-12589e3361b8.png" width="400">

<img src="https://user-images.githubusercontent.com/1282659/40888580-f8b909e8-671e-11e8-9fac-1b543f7e0e87.png" width="200"><img src="https://user-images.githubusercontent.com/1282659/40891662-8f5cd3f4-674f-11e8-9ab4-ab0b8f43c3e0.png" width="400">

### Tablet
<img src="https://user-images.githubusercontent.com/1282659/40891693-08ab9452-6750-11e8-96b0-8e1322b26b1c.png" width="250"><img src="https://user-images.githubusercontent.com/1282659/40891695-0a4b0e64-6750-11e8-918c-80630378d5c3.png" width="450">

<img src="https://user-images.githubusercontent.com/1282659/40891705-2085b29c-6750-11e8-9cb0-1c424060b625.png" width="250"><img src="https://user-images.githubusercontent.com/1282659/40891706-2203bfec-6750-11e8-8a09-396cf8cb8bab.png" width="450">

## Prerequisite
You should have the skills you need to complete this app after completing courses:

1. Developing Android Apps 
2. Advanced Android App Development
3. Material Design for Android Developers

## Abstract

The app is currently functional, and work in most cases for most users.
Your job will be to take the user feedback in the UI Review node, and implement changes that will improve the UI and make it conform to Material Design.

## User feedback(s)

##### Lyla says:
“This app is starting to shape up but it feels a bit off in quite a few places. I can't put finger on it but it feels odd.”

##### Jay says:
“Is the text supposed to be so wonky and unreadable? It is not accessible to those of us without perfect vision."

##### Kagure says:
“The color scheme is really sad and I shouldn't feel sad.”

## Required Tasks
Spend time exploring the current state of the app, looking for ways it could be improved. The app will need multiple improvements. Be sure to look specifically at issues called out in the UI Review.

## Enhancement Details

1. Add Left justified app toolbar.
<img src="https://user-images.githubusercontent.com/1282659/41631629-55845b3a-73fb-11e8-9ef0-a5888fc20ed7.png" width="450">

2. Add background image.
3. Add Collaping app toolbar: reduces height when user swipes book selection.

<img src="https://user-images.githubusercontent.com/1282659/41631630-55a17364-73fb-11e8-809f-3656fe5c7c58.png" width="243"><img src="https://user-images.githubusercontent.com/1282659/41631631-55b6e35c-73fb-11e8-835c-e6ab1b377ec3.png" width="250">

<img src="https://user-images.githubusercontent.com/1282659/42129451-70be2722-7c8a-11e8-8fe0-515b5ba9d9c7.png" width="250"><img src="https://user-images.githubusercontent.com/1282659/42129452-734e27e4-7c8a-11e8-90c1-808492505ae8.png" width="450">

4. Add background gradient overlay for text visibility (regardless of image content).

<img src="https://user-images.githubusercontent.com/1282659/41631849-8e17be32-73fc-11e8-9935-ca39c8fbca58.png" width="120"><img src="https://user-images.githubusercontent.com/1282659/41631850-8e36306a-73fc-11e8-8e2e-4f97f543cb67.png" width="120">
<img src="https://user-images.githubusercontent.com/1282659/41631851-8e4f2f5c-73fc-11e8-9899-1d1d4e9bcd04.png" width="250"><img src="https://user-images.githubusercontent.com/1282659/41631852-8e75c806-73fc-11e8-9f55-fc003c958e41.png" width="250">

5. Add vertical tween (coordinated motion) to RecyclerView (Book list) on main activity.
6. Add curve tween (coordinated motion) to thumbnail for transition between main -> detail activity.
7. Add background gradient overlay on detail page for thumbnail visibility.

<img src="https://user-images.githubusercontent.com/1282659/41814851-4b9d5708-771f-11e8-868f-36e3aa4ee5e4.png" width="200"><img src="https://user-images.githubusercontent.com/1282659/41814853-4d1cb768-771f-11e8-81ed-7bfa87c6e32e.png" width="400">

<img src="https://user-images.githubusercontent.com/1282659/42129450-70afed4c-7c8a-11e8-8b2a-d470ac0f347c.png" width="250"><img src="https://user-images.githubusercontent.com/1282659/42129453-755f16d8-7c8a-11e8-8edd-0f4d165eb005.png" width="450">

## Rubric 
- App uses the Design Support library and its provided widget types 
  (FloatingActionButton, AppBarLayout, SnackBar, etc).
- App uses CoordinatorLayout for the main Activity.
- App theme extends from AppCompat.
- App uses an AppBar and associated Toolbars.
- App provides a Floating Action Button for the most common action(s).
- App properly specifies elevations for app bars, FABs, and other elements specified in the Material Design specification.
- App has a consistent color theme defined in styles.xml. Color theme does not impact usability of the app.
- App provides sufficient space between text and surrounding elements.
- App uses images that are high quality, specific, and full bleed.
- App uses fonts that are either the Android defaults, are complementary, and aren't otherwise distracting.
- App conforms to common standards found in the Android Nanodegree General Project Guidelines.
http://udacity.github.io/android-nanodegree-guidelines/core.html
https://d17h27t6h515a5.cloudfront.net/topher/2016/June/5769c116_1000-files-tutorial/1000-files-tutorial.pdf
- App utilizes stable release versions of all libraries, Gradle, and Android Studio.

## Reference 

#### Starter code
https://github.com/udacity/xyz-reader-starter-code

#### Material design specification
https://material.io/design/introduction/

### JSON data
https://go.udacity.com/xyz-reader-json

### Instructor Nico's recommendations
https://discussions.udacity.com/t/fragment-transition-animation/353502/8
