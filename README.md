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
Splach | Login | Home | Movies
--- | --- | --- | --- |
![](https://github.com/b-alramlawi/Movies_app/assets/63581864/352362f6-6ed4-44a5-9abb-db4d5cba86ac) | ![](https://github.com/b-alramlawi/Movies_app/assets/63581864/bb8ba3a2-aa19-4c07-a8da-5dd7aa07c68c) | ![](https://github.com/b-alramlawi/Movies_app/assets/63581864/b2f9d694-9a65-4a9f-9fcc-065b33222c7a) | ![](https://github.com/b-alramlawi/Movies_app/assets/63581864/e5a5be3b-363f-4960-abee-387b2cbe6a96)

| Tv Shows | Details | Profile | Genre
--- | --- | --- | --- |
 ![](https://github.com/b-alramlawi/Movies_app/assets/63581864/44484873-5a97-4277-860b-4a66733b7418) | ![](https://github.com/b-alramlawi/Movies_app/assets/63581864/d09cfa71-aaa0-4174-a889-f84df8e51b56) | ![](https://github.com/b-alramlawi/Movies_app/assets/63581864/fc62317d-82d8-4314-99d7-11e9fb1e28bd) | ![](https://github.com/b-alramlawi/Movies_app/assets/63581864/73616eff-f11f-4bf9-98e7-106d63cfaebe)
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
- [Kotlin Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) - Kotlin Coroutines simplify asynchronous programming in Kotlin, offering a concise and readable way to write non-blocking code.
- [Retrofit](https://github.com/square/retrofit) - A type-safe HTTP client for Android and Kotlin.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
- [Jetpack Navigation](https://developer.android.com/jetpack/compose/navigation) - Navigation refers to the interactions that allow users to navigate across, into, and back out from the different pieces of content within your app
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
<br />
