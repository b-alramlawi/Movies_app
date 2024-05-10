<h1 align="center">Movies App</h1>

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>
  <a href="https://android-arsenal.com/api?level=23"><img alt="API" src="https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat"/></a>
  <a href="https://kotlinlang.org"><img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-1.4.xxx-blue"/></a>
  <img alt="MVVM" src="https://img.shields.io/badge/MVVM-Architecture-orange"/>
</p>

![](https://www.microids.com/wp-content/uploads/2020/10/WhoWantsToBeAMillionaire_keyart.jpg)
<br />

## Overview 
Welcome to Movie App, your ultimate movie companion! Dive into a world of cinema with our app, where you can explore, discover, and enjoy movies like never before. From classic films to the latest releases, Movie App has you covered. Get access to a vast library of movies, curated lists, and personalized recommendations based on your preferences. Stay up-to-date with the latest news, trailers, and reviews. Whether you're a casual viewer or a die-hard cinephile, Movie App is your go-to app for all things movies. Start exploring today and let the magic of cinema unfold!
<br />

## App Images 
Splach | Home | Question | Helper
--- | --- | --- | --- |
![](https://i.ibb.co/Rv8TLG4/photo-2022-09-09-14-28-32.jpg) | ![](https://i.ibb.co/kQhHcpQ/photo-2022-09-09-14-28-44.jpg) | ![](https://i.ibb.co/fvcZyLb/photo-2022-09-09-14-28-47.jpg) | ![](https://i.ibb.co/sJnQwCC/photo-2022-09-09-14-29-32.jpg)

| losing | Win | Top result | About
--- | --- | --- | --- |
 ![](https://i.ibb.co/Z65K3vV/photo-2022-09-09-14-30-49.jpg) | ![](https://i.ibb.co/thMfm4B/photo-2022-09-09-14-34-09.jpg) | ![](https://i.ibb.co/ZN91kP7/photo-2022-09-09-14-36-06.jpg) | ![](https://i.ibb.co/k98H6xP/photo-2022-09-09-14-29-40.jpg)
<br />
 
  
## Project Architecture MVVM
![MVVM3](https://user-images.githubusercontent.com/1812129/68319232-446cf900-00be-11ea-92cf-cad817b2af2c.png)
- Yes , liveData is easy , powerful , but you should know how to use.
 - For livedate which will emit data stream , it has to be in your
   data layer , and don't inform those observables any thing else like
   in which thread those will consume , cause it is another
 - For livedata which will emit UI binding events, it has to be in your ViewModel Layer.
 - Observers in UI Consume and react to live data values and bind it.
   responsibility , and according to `Single responsibility principle`
  in `SOLID (object-oriented design)` , so don't break this concept by
   mixing the responsibilities .

  ![mvvm2](https://user-images.githubusercontent.com/1812129/68319008-e9d39d00-00bd-11ea-9245-ebedd2a2c067.png)
<br />
  
  ## Built With 🛠
- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
- [Kotlin Coroutines]([https://github.com/ReactiveX/RxJava](https://kotlinlang.org/docs/coroutines-overview.html)) - Kotlin Coroutines simplify asynchronous programming in Kotlin, offering a concise and readable way to write non-blocking code.
- [Retrofit](https://github.com/square/retrofit) - A type-safe HTTP client for Android and Kotlin.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
- [Jetpack Navigation](https://developer.android.com/jetpack/compose/navigation) - Navigation refers to the interactions that allow users to navigate across, into, and back out from the different pieces of content within your app
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
<br />
