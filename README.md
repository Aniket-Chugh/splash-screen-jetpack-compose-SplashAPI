# Splash Screen in Jetpack Compose
Hi guys , i have made splash screen by usinf just 4 lines of code. How ? Read This Full

## Preview --
https://github.com/Aniket-Chugh/splash-screen-jetpack-compose-SplashAPI/assets/149312276/09dcf6bf-86a0-47f1-bab8-d0c00287ace3


## 4 Lines Code (in themes.xml) --


    <style name="Theme.Myapp" parent="Theme.SplashScreen">
        <item name="windowSplashScreenBackground">@color/purple_700</item>
        <item name="windowSplashScreenAnimatedIcon">@drawable/ic_launcher_foreground</item>
        <item name="windowSplashScreenAnimationDuration">2000</item>
        <item name="postSplashScreenTheme">@style/Theme.SplashScreenAPI</item>
    </style>


## Dependencies --

    implementation("androidx.core:core-splashscreen:1.0.0-alpha02")

    

    ## Call it in the MainActivity.kt --

     installSplashScreen()

    



