

# Composable Sweet Toast 
[![](https://jitpack.io/v/TalhaFaki/ComposableSweetToast.svg)](https://jitpack.io/#TalhaFaki/ComposableSweetToast)

A library that you can use in 4 different types(Success, Error, Warning, Info) written with Jetpack Compose. You can use this toast easy.

## Tech Stack:
* Kotlin 
* Jetpack Compose
* Material Design
* Solid Principles
* Custom View from Toast

## How to install ? 
You can add the library to your project using jitpack.io.

Add the code below to your project's settings.gradle file.

```
 allprojects {
        repositories {
            jcenter()
            maven { url "https://jitpack.io" }
        }
   }
```


Add the code below to your app's gradle file.
```
implementation 'com.github.TalhaFaki:ComposableSweetToast:1.0.0'
```
## Usage

For Sweet Success with Short Duration : 
```
SweetSuccess(message = "Success Text!", duration = Toast.LENGTH_SHORT)
```
![](https://github.com/TalhaFaki/ComposableSweetToast/blob/master/success.gif)

For Sweet Error :
```
SweetError(message = "Error Text!")
```
![](https://github.com/TalhaFaki/ComposableSweetToast/blob/master/error.gif)

For Sweet Warning : 
```
SweetWarning(message = "Warning Text!")
```
![](https://github.com/TalhaFaki/ComposableSweetToast/blob/master/warning.gif)

For Sweet Info : 
```
SweetInfo(message = "Info Text!")
```
![](https://github.com/TalhaFaki/ComposableSweetToast/blob/master/info.gif)

## Sample App: 
[Click here for MainScreen](https://github.com/TalhaFaki/ComposableSweetToast/blob/master/app/src/main/java/com/android/composablesweettoast/MainScreen.kt)
