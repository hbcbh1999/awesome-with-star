# Info come from [JStumpp/awesome-android](https://github.com/JStumpp/awesome-android)
# Awesome Android [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# [<img src="https://raw.githubusercontent.com/jstumpp/awesome-android/master/awesome-android.png">](https://github.com/jstumpp/awesome-android)

A curated list of awesome Android [libraries](#libraries) and [resources](#resources). For general Java libraries have a look at [awesome-java](https://github.com/akullpp/awesome-java).

- [Emulators](#emulators)
- [Libraries](#libraries)
    - [Charts](#charts)
    - [Cloud Services](#cloud-services)
    - [Dependency Injection](#dependency-injection)
    - [Android Services](#android-services)
    - [Game Development](#game-development)
	- [Security](#security)
    - [GUI](#gui)
        - [ActionBar](#actionbar)
        - [Navigation](#navigation)
        - [Animations](#animations)
        - [Images](#images)
        - [Inputs](#inputs)
        - [Loading images](#loading-images)
        - [Video](#video)
        - [Camera](#camera)
        - [Field Validation](#field-validation)
    - [JSON](#json)
    - [Crash monitoring](#crash-monitoring)
    - [Networking](#networking)
    - [Logger](#logger)
    - [Notifications](#notifications)
    - [Database](#database)
        - [ORM](#orm)
    - [REST](#rest)
    - [Testing](#testing)
    - [Tracking](#tracking)
    - [Maps](#maps)
    - [Utility](#utility)
    - [Debugging tools](#debugging-tools)
    - [Wireless](#wireless)
    - [Chat and Messaging](#chat--messaging)
    - [Custom Dialog](#custom-dialog)
    - [Version Checking](#version-checking)
    - [Date & Time](#date--time)
    - [Runtime Permissions](#runtime-permissions)
    - [Other](#other)
- [Resources](#resources)
    - [More lists of libraries](#more-lists-of-libraries)
- [Development Alternatives](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#lua)
    - [Scala](#scala)
    - [Groovy](#groovy)
    - [Kotlin](#kotlin)
- [Performance](#performance)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Emulators
- [AMIDuOS](https://www.amiduos.com)
- [AndY](https://andyroid.net)
- [ARChon](https://archon-runtime.github.io)
- [BlueStacks](https://www.bluestacks.com)
- [Genymotion](https://www.genymotion.com)
- [nox](https://www.bignox.com)
- [Xamarin](https://www.xamarin.com)
- [Remix OS Player](http://www.jide.com/remixos-player)

## Libraries

### Charts

- [AChartEngine](https://github.com/ddanny/achartengine) - Charting Engine. :star:492
- [EazeGraph](https://github.com/blackfizz/EazeGraph) - Chart and graph library. :star:1311
- [WilliamChart](https://github.com/diogobernardino/WilliamChart) - Chart library with good motion capabilities. :star:3542
- [HelloCharts](https://github.com/lecho/hellocharts-android) - Chart and graph library with support for scaling, scrolling and animations. :star:5233
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - An Android chart and graph library supporting scaling and dragging by gesture. :star:19475

### Cloud Services

- [CloudRail](https://cloudrail.com) - Unified API Library for: Cloud Storage, Social Profiles, Payment, Email, SMS & POIs.

### Data binding

- [Anvil](https://github.com/zserge/anvil) - A small library to create reactive UI components, inspired by React. Provides data binding and event listener binding, fits well for MVVM. :star:1136
- [RoboBinding](https://github.com/RoboBinding/RoboBinding) - A data-binding Presentation Model (MVVM) framework for the Android platform. :star:1326
- [Data Binding Library](https://developer.android.com/topic/libraries/data-binding/index.html) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

- [RoboGuice](https://github.com/roboguice/roboguice) - Dependency injection framework for Android. :star:3871
- [Dagger](https://github.com/square/Dagger) - Dependency injection framework for Java and Android. :star:6564
- [Dagger 2](https://github.com/google/dagger) - A fast dependency injector for Android and Java. :star:9183
- [Butter Knife](http://jakewharton.github.io/butterknife/) - View "injection" library for Android.
- [ActivityStarter](https://github.com/MarcinMoskala/ActivityStarter) - Android Library that provide simpler way to start the Activities with multiple arguments. :star:252
- [AndroidAnnotations](https://github.com/androidannotations/androidannotations) - Java annotations with dependency injection at compile time. :star:9922
- [Toothpick](https://github.com/stephanenicolas/toothpick) - A scope tree based Dependency Injection (DI) library for Java. :star:583

### Android Services
- [Remoter](https://github.com/josesamuel/remoter) - An alternative to Android AIDL for Android Remote IPC services using plain java interfaces. :star:5
- [Service Connector](https://github.com/josesamuel/serviceconnector) - Bind Android services and callbacks to fields and methods. :star:2

### Game Development

- [AndEngine](http://www.andengine.org/) - Free, Fun and Fast Android 2D OpenGL Game Engine.
- [Libgdx](https://libgdx.badlogicgames.com/) - Cross-platform game engine and SDK. [Open Source](https://github.com/libGDX/libGDX) :star:13016
- [Vuforia](https://www.vuforia.com/) - Augmented Reality library.
- [Unity](https://unity3d.com/unity/features/multiplatform) - Cross-platform game creation system.
- [Rajawali](https://github.com/Rajawali/Rajawali) - Android OpenGL ES 2.0/3.0 Engine :star:1593
- [Cocos2d-x](http://www.cocos2d-x.org) - Cross-platform 2d game framework.
- [JustWeEngine](https://github.com/lfkdsk/JustWeEngine) - An easy open source Android Native Game FrameWork. :star:695

### Security

- [libsignal-protocol-java](https://github.com/whispersystems/libsignal-protocol-java) - A ratcheting forward secrecy protocol that works in synchronous and asynchronous messaging environments. :star:570

### GUI

- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html) - A swipe refresh layout is available in the v4 support library.
- [Cardslib](https://github.com/gabrielemariotti/cardslib) - Android Library to build a UI Card. :star:4745
- [AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) - Grid view which supports multiple columns with rows of varying sizes. :star:4626
- [AndroidQuery](https://github.com/androidquery/androidquery) - Android-Query (AQuery) is a light-weight library for doing asynchronous tasks and manipulating UI elements in Android. :star:2030
- [Flow](https://github.com/square/flow) - Library that helps with describing an app as a collection of moderately independent screens. :star:2500
- [Crouton](https://github.com/keyboardsurfer/Crouton) - Context sensitive notifications for Android :star:3034
- [DragSortListView](https://github.com/bauerca/drag-sort-listview) - Extension of the Android ListView that enables drag-and-drop reordering (No longer maintained). :star:3168
- [SortableTableView](https://github.com/ISchwarz23/SortableTableView) - An Android library containing a simple TableView and an advanced SortableTableView providing a lot of customisation possibilities to fit all needs. :star:836
- [MaterialProgressBar](https://github.com/DreaminginCodeZH/MaterialProgressBar) - Material design ProgressBar with consistent appearance. :star:1417
- [AndroidFillableLoaders](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders) - Fillable progress view working with SVG paths. Nice option too for creating interesting app logos. :star:1700
- [NexusDialog](https://github.com/dkharrat/NexusDialog) - Allows you to easily and quickly create forms in Android with little code. :star:161
- [Snap RecyclerView Utils](https://github.com/prashantsolanki3/Snap-RecyclerView-Utils) - Populate Single or multiple Layout RecyclerView without creating an Adapter. :star:74
- [MultiSnapRecyclerView](https://github.com/TakuSemba/MultiSnapRecyclerView) - Android library for multiple snapping of RecyclerView :star:1275
- [SwipeableCard](https://github.com/michelelacorte/SwipeableCard) - Implementation of swipe card like StreetView!! :star:664
- [ElasticProgressBar](https://github.com/michelelacorte/ElasticProgressBar) - Beautiful loading bar. :star:283
- [EntryScreenManager](https://github.com/kunall17/EntryScreenManager) - Intro/Entry/Walkthrough/Starting Screens. :star:30
- [EasyIntro](https://github.com/meNESS/EasyIntro) - The flexible, easy to use, all in one app intro library for your Android project. :star:72
- [Material-Calendar-View](https://github.com/BlackBoxVision/material-calendar-view) - Material Design Calendar compatible with API 8+ :star:305
- [SectionedRecyclerViewAdapter](https://github.com/luizgrp/SectionedRecyclerViewAdapter) - An Adapter that allows a RecyclerView to be split into Sections with headers and/or footers. :star:749
- [DragListView](https://github.com/woxblom/DragListView) - Drag and drop to reorder items in a list, grid or board. :star:328
- [Animated Expanding ListView](https://github.com/LeonardoCardoso/Animated-Expanding-ListView) - Animated Expanding ListView provides a fancy animation on expanding or collapsing the content of a listview item. :star:122
- [TastyToast](https://github.com/yadav-rahul/TastyToast) - Toasts with icons and color. :star:1653
- [DotLoader](https://github.com/bhargavms/DotLoader) - A customizable loading animation with Dots. :star:99
- [PodSlider](https://github.com/bhargavms/PodSLider) - A customizable slider widget adhering to material design specs. :star:103
- [TapTargetView](https://github.com/KeepSafe/TapTargetView) - An implementation of tap targets from the Material Design guidelines for feature discovery. :star:3215
- [MaterialIntroScreen](https://github.com/TangoAgency/material-intro-screen) - Material Intro Screen implementation with easily extensible API. :star:2148
- [FloatingView](https://github.com/UFreedom/FloatingView) - FloatingView can make the target view floating above the anchor view with cool animation. :star:1443
- [Timecon](https://github.com/alxrm/animated-clock-icon) - Easy-to-use animated clock icon :star:157
- [Audiogram](https://github.com/alxrm/audiowave-progressbar) - Lightweight audiowave progressbar :star:132
- [Bubbles for Android](https://github.com/txusballesteros/bubbles-for-android) - Facebook like chat bubble library :star:1239
- [Litho (By Facebook)](https://github.com/facebook/litho) - A declarative framework for building efficient UIs on Android. :star:4262
- [MultiViewAdapter](https://github.com/DevAhamed/MultiViewAdapter) - Recyclerview Adapter library to create composable view holders. :star:324
- [LGSnackbar](https://github.com/loregr/LGSnackbar) - An easy to use and customisable wrapper of the native Android Snackbar which stays visible across multiple activities. :star:31
- [ShimmerLayout](https://github.com/team-supercharge/ShimmerLayout) - Memory efficient shimmering effect for Android applications. :star:1110
- [CircleProgressBar](https://github.com/emre1512/CircleProgressBar) - A simple library for creating circular progressbars for Android. :star:11

#### Paginate
- [NoPaginate](https://github.com/NoNews/NoPaginate) - Simple Android pagination library :star:67

#### ActionBar
- [ActionBarSherlock](http://actionbarsherlock.com) - ActionBar for older Android versions.
- [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) - Fading action bar effect that can be seen in the new Play Music app. :star:2896

#### Navigation
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - Library to create applications with slide-in menus. :star:10804
- [SlidingTutorial](https://github.com/Cleveroad/slidingtutorial-android) - Simple library that helps to create awesome sliding android app tutorials. :star:2164
- [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) - An interactive indicator to navigate between the different pages of a ViewPager. :star:6361
- [Page View indicator](https://github.com/JakeWharton/ViewPagerIndicator) - Support for horizontally scrolling ViewPager. :star:9499
- [RecyclerTabLayout](https://github.com/nshmura/RecyclerTabLayout) - An efficient TabLayout library implemented with RecyclerView. :star:987
- [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) - Simple take on a material design navigation drawer. :star:8591
- [Debug-Artist](https://github.com/baristaventures/debug-artist) - Debug menu to enable leakcanary, scalpel and others easy. :star:38
- [Floating-Navigation-View](https://github.com/andremion/Floating-Navigation-View) - A simple Floating Action Button that shows an anchored Navigation View. :star:890

#### Animations
- [NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids) - Library for using the Honeycomb animation API on all versions of the platform back to 1.0. :star:4305
- [Rebound](https://github.com/facebook/rebound) - Rebound is a Java library that models spring dynamics. :star:4860
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - Cute view animation collection. :star:8685
- [Android-Transition](https://github.com/kaichunlin/android-transition) - Allows the easy creation of view transitions that react to user inputs. :star:565
- [Android-View-Actions](https://github.com/dtx12/AndroidAnimationsActions) - Makes creating complex animations for views easy. :star:130
- [Swipper](https://github.com/sdsmdg/Swipper) - Android library for swipeable gestures to control volume , brightness and seek . :star:66
- [Spotlight](https://github.com/TakuSemba/Spotlight) - Android Library that lights items for tutorials or walk-throughs etc... :star:1170

#### Images

- [Crescento](https://github.com/developer-shivam/crescento) - Explore new style in material design by adding curve below image view. :star:1032
- [android-crop](https://github.com/jdamcd/android-crop) - Library project for cropping images. :star:3896
- [CircularImageView](https://github.com/Pkmmte/CircularImageView) - Custom view for circular images while maintaining the best draw performance. :star:1153
- [Android-Image-Filter](https://github.com/ragnraok/android-image-filter) - Library project for applying image filters easily. :star:542
- [Compressor](https://github.com/zetbaitsu/Compressor) - Compressor is a lightweight and powerful android image compression library. :star:2916

#### Inputs

- [FloatingLabel](https://github.com/hardik-trivedi/FloatingLabel) - FloatingLabel Allows you to create a blow kind of EditText. *Doesn't have Gradle or Maven Support.* :star:240
- [MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - Supporting Floating Labels, Single Line Ellipsis, Max/Min Characters, Helper Text and Error Text with Custom Colors. :star:4812
- [Emojicon](https://github.com/rockerhieu/emojicon) - Adds emoticons to your app :star:3048
- [MaterialSearchBar](https://github.com/mancj/MaterialSearchBar) - Material Design Search Bar for Android :star:1206
- [InputMask](https://github.com/RedMadRobot/input-mask-android) - Pattern-based user input formatter, parser and validator. :star:481

#### Loading Images

- [Picasso](https://github.com/square/picasso) - A powerful image downloading and caching library for Android. :star:14644
- [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - Asynchronous, out of the box loading and caching of images. :star:15843
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling, Recommended by Google. :star:19165
- [Fresco](https://github.com/facebook/fresco) - An Android library for managing images and the memory they use. :star:13823
- [Glide Bitmap Pool](https://github.com/amitshekhariitbhu/GlideBitmapPool) - Glide Bitmap Pool is a memory management library for reusing the bitmap memory. :star:357
- [MediaPicker](https://github.com/alhazmy13/MediaPicker) - Android Library that lets you to select multiple images, video or voice for Android :star:100

#### Video

- [ijkplayer](https://github.com/Bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.2, with MediaCodec, VideoToolbox support. :star:16666
- [Exoplayer](https://github.com/google/ExoPlayer) - ExoPlayer is an application level media player for Android, allow  playing audio and video both locally and over the Internet. :star:8514
   Supports features like Dynamic adaptive streaming over HTTP (DASH), SmoothStreaming and Common Encryption
- [Easy-Video-Player](https://github.com/afollestad/easy-video-player) - Easy Video Player is very simple and easy to use in our app.  :star:1052
- [VideoPlayView](https://github.com/MarcinMoskala/VideoPlayView) - Custom Android view with video player, play/stop, loader and placeholder image. :star:50

#### Camera

- [MagicalCamera](https://github.com/fabian7593/MagicalCamera) - Simple way to take or select photos of your gallery, with other features for manage pictures. :star:246

#### Field Validation
- [Convalida](https://github.com/WellingtonCosta/convalida) - A simple and annotation-based way to validate your input fields. :star:32

### JSON

- [Gson](https://github.com/google/gson) - Gson is a Java library used for serializing and deserializing Java objects from and into JSON. :star:11026
- [Jackson JSON Processor](https://github.com/FasterXML/jackson) - High-performance JSON processor. :star:3448
- [Moshi](https://github.com/square/moshi) - A modern JSON library for Android and Java. :star:3360
### Crash monitoring

- [Fabric Crashlytics](https://get.fabric.io/) - Easy crash reporting solution.
- [HockeyApp](https://www.hockeyapp.net/) - Distribution, Crash Reports, Feedback and Analytics
- [Splunk MINT](https://mint.splunk.com/) - Monitoring, Crash Reports, Real time data, Statistic.
- [Bugsnag](https://www.bugsnag.com/) - Cross platform error monitoring. Free tier. Support for SDK & NDK. Error reports include data on device, release, user, and allows arbitrary data.
- [Catcho](https://github.com/alhazmy13/Catcho) - No Force Close any more. :star:21
- [Apteligent](https://www.apteligent.com/) - Cross platform crash reporting/analytics solution. Supports NDK log.
- [Instabug](https://instabug.com/) - Bug reporting, Crash Reporting, In-app Feedback.

### Networking

- [Ion](https://github.com/koush/ion) - Good networking library for android. :star:5516
- [OkHttp](https://github.com/square/okhttp) - An HTTP+SPDY client for Android and Java applications. :star:23935
- [Asynchronous Http Client](https://github.com/loopj/android-async-http) - An Asynchronous HTTP Library. :star:10085
- [RoboSpice](https://github.com/stephanenicolas/robospice) - Library that makes writing asynchronous network requests easy. :star:3043
- [IceNet](https://github.com/anton46/IceNet) - Fast, Simple and Easy Networking for Android :star:66
- [Android Volley](https://developer.android.com/training/volley/index.html) - Official Android HTTP library that makes networking for easier and faster.
- [IceSoap](https://github.com/AlexGilleran/IceSoap) - Easy, asynchronous, annotation-based SOAP for Android. :star:74
- [node-android](https://github.com/InstantWebP2P/node-android) - Run Node.js on Android. :star:470
- [HappyDns](https://github.com/qiniu/happy-dns-android) - A Dns library, user can use custom dns server, dnspod httpdns. Only support A record. :star:138
- [RESTMock](https://github.com/andrzejchm/RESTMock) - HTTP Web server for mocking API responses in Android Instrumentation tests. :star:443
- [Packetzoom](https://packetzoom.com/blog/introducing-http-optimizer-and-analytics-service.html) - SDK for optimizing HTTP requests and free analytics service for networking.
- [Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) - A Complete Fast Android Networking Library that also support HTTP/2. :star:2645

### Logger
- [logger](https://github.com/orhanobut/logger) - Simple, pretty and powerful logger for android :star:8070
- [timber](https://github.com/JakeWharton/timber) - A logger with a small, extensible API which provides utility on top of Android's normal Log class. :star:5037
- [LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor) - An OkHttp interceptor which pretty logs request and response data. :star:718
- [Bugfender](https://github.com/bugfender/BugfenderSDK-android-sample) - Upload your logs and check them online, specially made for mobile :star:15
- [EzyLogger](https://github.com/afiqiqmal/EzyLogger) - Simple Lightweight logger :star:3

### Notifications
- [android-remote-notifications](https://github.com/kaiwinter/android-remote-notifications) - Pulls notifications from a remote JSON file and shows them in your app. :star:73
- [Android HeartBeat Fixer](https://github.com/joaopedronardari/AndroidHeartBeatFixer) - Way to set heartbeat interval and users receive PushNotifications from GCM. :star:41

### Database
- [Cupboard](https://bitbucket.org/littlerobots/cupboard) - Access the sqlite easily via direct database access or through the ContentProvider framework.
- [DbInspector](https://github.com/infinum/android_dbinspector) - Provides a simple way to view the contents of the in-app database for debugging purposes. :star:768
- [SQLite Asset Helper](https://github.com/jgilfelt/android-sqlite-asset-helper) - manage database creation and version management using an application's raw asset files. :star:1875
- [Realm](https://github.com/realm/realm-java) - The alternative to SQLite and ORMs: Simple, modern and fast! Object oriented API and multi platform support. :star:8858
- [Realm Asset Helper](https://github.com/eggheadgames/android-realm-asset-helper) - Copies a realm database from the apk assets folder. Efficiently handles versioning of read-only realm databases. :star:22
- [RestorableSQLiteDatabase](https://github.com/yaa110/RestorableSQLiteDatabase) - A wrapper to replicate android's SQLiteDatabase with restoring capability. :star:17
- [Nitrite Database](https://github.com/dizitart/nitrite-database) - A NoSQL embedded document store for Android with MongoDb like API. :star:106

#### ORM

- [requery](https://github.com/requery/requery) - Compile time ORM and SQL query library for Java & Android. :star:2272
- [GreenDAO](http://greenrobot.org/greendao/) - Light & fast ORM solution.
- [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - Lightweight ORM Java package for JDBC and Android.
- [ActiveAndroid](http://www.activeandroid.com) - Active record style ORM.
- [Sugar ORM](http://satyan.github.io/sugar/) - Insanely easy way to work with Android Databases.
- [DBFlow](https://github.com/Raizlabs/DBFlow) - Fast and powerful ORM with compile-time annotation processing. :star:3891
- [NexusData](https://github.com/dkharrat/NexusData) - Object graph and persistence framework for Android. :star:70
- [SimpleNoSQL](https://github.com/Jearil/SimpleNoSQL) - A simple NoSQL client for Android. Meant as a document store using key/value pairs and some rudimentary querying. Useful for avoiding the hassle of SQL code. :star:394
- [RxSimpleNoSQL](https://github.com/xmartlabs/RxSimpleNoSQL) - Reactive extensions for SimpleNoSQL. Manipulate entities using Observables. :star:36

### REST

- [Retrofit](http://square.github.io/retrofit/) - Retrofit turns your REST API into a Java interface.
- [Spring for Android - Rest Template](https://github.com/spring-projects/spring-android) - A Rest Client for Android. :star:658

### Testing

- [Robotium](https://github.com/robotiumtech/robotium) - Test automation framework for black-box UI tests. :star:2291
- [Roboletric](http://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- [AssertJ Android](https://github.com/square/assertj-android) - AssertJ assertions geared towards Android. :star:1520
- [Green Coffee](https://github.com/mauriciotogneri/green-coffee) - Run your Cucumber tests in your Android instrumentation tests. :star:164

### Tracking

- [MobileAppTracking](https://www.tune.com/) - Tracking your marketing campaigns across multiple ad networks.
- [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users.
- [Countly](https://count.ly) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
- [CleverTap](https://clevertap.com) - Analytics platform and user-engagement platform with 1 million free events

### Maps

- [Google-Directions-Android](https://github.com/jd-alexander/Google-Directions-Android) - Allows you to calculate the direction between two locations and display the route on a Google Map using the Google Directions API. :star:726
- [Android Maps Extensions](https://github.com/mg6maciej/android-maps-extensions) - Extending capabilities of Google Maps Android API v2, adding marker clustering among other things :star:365
- [Clusterkraf](https://github.com/twotoasters/clusterkraf) - Clustering library for the Google Maps Android API v2 :star:265
- [MapScaleView](https://github.com/pengrad/MapScaleView) - Scale bar for Google Maps Android API :star:50

### Utility

- [Conceal SharedPreferences](https://github.com/afiqiqmal/ConcealSharedPreference-Android) - Secured Preferences using Facebook Secure Encryption called Conceal. :star:33
- [EventBus](http://greenrobot.github.io/EventBus/) - EventBus is a library that simplifies communication between different parts of your application.
- [Otto](https://github.com/square/otto) - Event Bus for Android. :star:4965
- [Weak handler](https://github.com/badoo/android-weak-handler) - Memory safer implementation of android.os.Handler. :star:1168
- [Byte Buddy](http://bytebuddy.net) - Runtime code generation library with support for Android.
- [Secure Preference Manager](https://github.com/prashantsolanki3/Secure-Pref-Manager) - Secure Preference Manager for android. It uses various Encryption to protect your application's Shared Preferences. :star:66
- [LeakCanary](https://github.com/square/leakcanary) - Catch memory leaks as they occur. :star:17753
- [Drekkar](https://github.com/coshx/drekkar) - An Android event bus for WebView and JS. :star:17
- [Androl4b](https://github.com/sh4hin/Androl4b) - A vm for assessing android applications. :star:514
- [DroidMVP](https://github.com/andrzejchm/DroidMVP) - Android library to help you incorporate MVP along with Passive View and Presentation Model patterns into your app. :star:217
- [Gota](https://github.com/alhazmy13/Gota) - Simplifying Android Permissions. :star:50
- [EasyDeviceInfo](https://github.com/nisrulz/easydeviceinfo) - Get device information in a super easy way. :star:1324
- [Ask-Permission](https://github.com/Kishanjvaghela/Ask-Permission) - Simple RunTime permission manager. :star:44
- [Shutter-Android](https://github.com/levibostian/Shutter-Android) - Capture photos/videos from device camera or get photos/video from gallery app with no runtime permissions needed. :star:11
- [Validator](https://github.com/anderscheow/Validator) - An utilities class to validate text inside TextInputLayout. :star:18

### Debugging Tools

- [Linx](https://github.com/pedrovgs/Lynx) - Show logcat inside the device for debug builds :star:582
- [Scalpel](https://github.com/JakeWharton/scalpel) - View the entire hierarchy in 3d in the phone. :star:2408
- [Stetho](https://github.com/facebook/stetho) - Debug hierarchy and network from chrome. :star:8910
- [Android Debug Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) - Android Debug Database is a powerful library for debugging databases and shared preferences in Android applications. :star:3382
- [Android Debug Bridge - ADB](https://github.com/mzlogin/awesome-adb/blob/master/README.en.md) - a command-line tool to assist in debugging Android-powered devices

### Wireless

- [SmartGattLib](https://github.com/movisens/SmartGattLib) - Simplifies the work with Bluetooth SMART devices (a.k.a. Bluetooth Low Energy in Bluetooth 4.0). :star:219

### Chat & Messaging

- [Applozic Android Chat SDK](https://github.com/AppLozic/Applozic-Android-SDK) - Android Chat and Messaging SDK for adding real time chat and in-app messaging into your android application. :star:432
- [Qiscus SDK](https://github.com/qiscus/qiscus-sdk-android) - Qiscus SDK is a lightweight and powerful android chat library. Qiscus SDK will allow you to easily integrating Qiscus engine with your apps to make cool chatting application. :star:118

#### Custom Dialog

- [MediaRecorderDialog](https://github.com/alhazmy13/MediaRecorderDialog) - Custom Dialog to record audio, store it and play it in your phone. :star:45
- [HijriDatePicker](https://github.com/alhazmy13/HijriDatePicker) - offers a hijri (Islamic Calendar) Date Picker designed on Google's Material Design Principals For Pickers. :star:56
- [Noty](https://github.com/emre1512/Noty) - A simple library for creating animated alerts/dialogs/warnings. :star:25

### Version Checking

 - [AppUpdater](https://github.com/javiersantos/AppUpdater) - comprehensive and feature rich library, including support for checks at Amazon and FDroid. :star:892
 - [Gandalf](https://github.com/btkelly/gandalf) - comprehensive features and a "companion" iOS solution. :star:287
 - [Siren](https://github.com/eggheadgames/Siren) - focused feature set that mimicks the popular iOS library of the same name. Supports Play and Amazon. :star:69
 - [Fit](https://github.com/KeithYokoma/Fit) - version checking callback framework with no UI. :star:55

### Date & Time

- [ThreeTen Android Backport](https://github.com/JakeWharton/ThreeTenABP) - An adaptation of the JSR-310 backport for Android. :star:1820
- [Joda-Time Android](https://github.com/dlew/joda-time-android) - Joda-Time library with Android specialization. :star:2079
- [True Time](https://github.com/instacart/truetime-android) - Android NTP time library. Get the true current time impervious to device clock time changes. :star:550

### Runtime Permissions

- [Permission Dispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher) - Simple annotation-based API to handle runtime permissions. :star:6255
- [RxPermissions](https://github.com/tbruyelle/RxPermissions) - Android runtime permissions powered by RxJava. :star:5124
- [NoPermission](https://github.com/NoNews/NoPermission) - Simple Android library for permissions request. Consists of only one class. :star:68

### Other

- [Android Support library](https://developer.android.com/topic/libraries/support-library/index.html) - The Android Support Library package is a set of code libraries that provide backward-compatible versions of Android framework API.
- [Google Play Services](https://developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- [Tape](https://github.com/square/tape) - A lightning fast, transactional, file-based FIFO for Android and Java. :star:1965
- [Guava: Google Core Libraries for Java](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth. :star:20772
- [Android Scripting](https://github.com/damonkohler/sl4a) - Allows to run scripting languages on Android. :star:1472
- [Android Priority Job Queue](https://github.com/path/android-priority-jobqueue) - Implementation of a Job Queue to easily schedule jobs (tasks) that run in the background, improving UX and application stability. :star:2412
- [RateMeMaybe](https://github.com/nspo/RateMeMaybe) - Asks the user if (s)he wants to open the Play Store to rate your application. :star:96
- [Easy Rating Dialog](https://github.com/fernandodev/easy-rating-dialog) - Lib provides a simple way to display an alert dialog for rating app. :star:100
- [ZXing Android-Integration](https://github.com/zxing/zxing) - Integration with Barcode Scanner via Intent. :star:16605
- [Gradle Retrolambda Plugin](https://github.com/evant/gradle-retrolambda) - Java 8 Lambdas on Android! :star:5161
- [RxJava](https://github.com/ReactiveX/RxJava)- RxJava – Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
- [RxBinding](https://github.com/JakeWharton/RxBinding)- RxBinding – RxJava binding APIs for Android UI widgets from the platform and support libraries.
- [Caffeine](https://github.com/percolate/caffeine) - A collection of utility classes that help make Android development faster. :star:422
- [AboutLibraries](https://github.com/mikepenz/AboutLibraries) - Automatically generates an About this app section, with a list of used libraries. :star:1959
- [AudioPlayerView](https://github.com/HugoMatilla/AudioPlayerView) - A view that loads audio from an url and have basic playback tools. :star:79
- [andle](https://github.com/Jintin/andle) - command line tool help you sync dependencies, sdk or build tool version. :star:46
- [Typography](https://github.com/workarounds/typography) - An Android library that makes it easy to use custom fonts in views. :star:39
- [Calligraphy](https://github.com/chrisjenx/Calligraphy) - Custom fonts in Android an OK way. :star:7188
- [transai](https://github.com/Jintin/transai) - command line tool help you manage localization string files. :star:49
- [Android-Link-Preview](https://github.com/LeonardoCardoso/Android-Link-Preview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images. :star:281
- [Sensey](https://github.com/nisrulz/sensey) - Detecting gestures in a snap. :star:2127
- [UserAwareVideoView](https://github.com/kevalpatel2106/UserAwareVideoView) - A customized video view that will automatically pause video is user is not looking at device screen! :star:46
- [Flexbox Layout](https://github.com/google/flexbox-layout) - FlexboxLayout is a library which brings the similar capabilities of CSS Flexible Box Layout Module to Android.  :star:10064
- [Agile Boiler Plate](https://github.com/xresco/Android-Agile-Boiler-Plate) - The boiler plate is based on MVP architecture and it is fully based on Dependency Injection design pattern using Dagger2. :star:43

## Resources

- [Vogella Tutorials](http://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- [Android Design in Action Video series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) The video series by Android Design Team of Google.
- [Android Design in Action slides](https://play.google.com/store/apps/details?id=com.astuetz.android.adia&feature=md)- The application that gives you access to the slides of the video series.
- [Android DevBytes Video Series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - It is the technical counterpart of Android Design in Action series.
- [Developing for Android](https://medium.com/google-developers/developing-for-android-introduction-5345b451567c) - A series of articles from Googler Chet Hasae and others, answering most commonly asked question: "What are some of the important rules to keep in mind when developing Android applications?".
- [Android Hive Tutorials](https://www.androidhive.info) - Very good tutorials for beginners.
- [Android Weekly](http://androidweekly.net) - Newsletter with weekly information about android.
- [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/).
- [Device Art Generator](https://developer.android.com/distribute/marketing-tools/device-art-generator.html) - Wraps app screenshots in real device artwork.
- [Android UI design resources](https://androiduiux.com/free-design-resources/) - Gives you wide variety of design resources form a Google Developer Expert in UI/UX.
- [Pencil Project](http://pencil.evolus.vn/) - An open source prototyping software.
- [Google Wear App](https://github.com/mbcrump/FirstGoogleWearableApp) - This is an open source Google Wear App that uses speech recognition to calculate a tip. :star:10
- [How to Make Android Apps](https://www.youtube.com/playlist?list=PLGLfVvz_LVvSPjWpLPFEfOCbezi6vATIh) - Video tutorials by Derek Banas.
- [android-blogs](https://github.com/vbauer/android-blogs) - List with blogs about Android. :star:417
- [Future Studio](https://futurestud.io/tutorials/tag/android) - Extensive Android tutorials on Retrofit, Picasso, Glide & Gson.
- [Android Tips & Tricks](https://github.com/nisrulz/android-tips-tricks) - Cheatsheet about tips and tricks for Android Development. :star:2530
- [Droid Talks](http://www.droidtalks.pro/) -  Awesome Android talks and learning resources, categorised by topic.
- [Associate Android Developer Certification Materials](https://github.com/Amejia481/Associate-Android-Developer-Certification) - A collection of materials for getting ready for the test. :star:450
- [Google Developers Training](https://developers.google.com/training/android/) -  Google Developers Official Training page has list of various useful learning resources for beginner as well seasoned developer.

### Podcast
- [Fragmented](http://fragmentedpodcast.com/)  is the Android developer podcast where Donn Felker and Kaushik Gopal talk about building good software and becoming better Android developers.
- [Android Developers Backstage](http://androidbackstage.blogspot.com/) is a podcast by and for Android developers. Hosted by developers from the Android engineering team, this show covers topics of interest to Android programmers, with in-depth discussions and interviews with engineers on the Android team at Google.
- [Android Dialogs](https://www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed) is a video based podcast, where they have bite-sized conversations with people from the Android community.
- [Android Intelligence](https://plus.google.com/collection/ATg6b) features in-depth interviews with interesting people from the Android world.
- [The Context](https://github.com/artem-zinnatullin/TheContext-Podcast) a podcast about Android Development with Hannes Dorfmann, Artem Zinnatullin and wonderful guests!


### More lists of libraries
- [The Android Arsenal](https://android-arsenal.com/) - Large list of android libraries
- [Square libraries](http://square.github.io/#android) - Multiple high quality libraries by square.
- [Awesome Android @LibHunt](https://android.libhunt.com) - Your go-to Android Toolbox.

## Development Alternatives

My personal recommendation is (for now) to use the android api to build a native app. Scala can help to build this native apps with cleaner code but it adds to many methods (Multidex required). Kotlin is a modern language with 100% interoperatibility with java projects **without multidex**. But there are also use cases where alternatives like cross-platform development can be useful.

### C&#35;

- [Xamarin](https://www.xamarin.com/) - Framework to create native iOS, Android, Mac and Windows apps in C#.

### HTML, CSS and Javascript

- [PhoneGap](https://phonegap.com) - Open source framework by Adobe to create cross platform mobile apps using HTML, CSS, and JavaScript.
- [Titanium](http://www.appcelerator.com/mobile-app-development-products/) - Open-source framework to create 'native' cross platform apps using JavaScript.
- [NativeScript](https://www.nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- [React Native](https://github.com/facebook/react-native) - A framework for building native apps with React by Facebook. :star:56999
- [Ionic Framework](http://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- [Apache Cordova](https://github.com/apache/cordova-android) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript. :star:2115

### Lua
- [Corona SDK](https://coronalabs.com/product/) - Framework to create native iOS and Android Apps (especially Games).

### Scala
- [Scaloid](https://github.com/pocorall/scaloid) - Library for less painful Android development with Scala. :star:2097
- [Macroid](https://github.com/47deg/macroid) - A modular functional UI language for Android. :star:529

### Groovy
- [Groovy on Android](http://melix.github.io/blog/2014/06/grooid.html) - Introduction to Groovy on Android.
- [Groovy Language Support for Android](https://github.com/groovy/groovy-android-gradle-plugin) - Gradle Plugin for Compiling Groovy for Android. :star:732
- [SwissKnife](https://github.com/Arasthel/SwissKnife) - A multi-purpose Groovy library containing view injection and threading for Android using annotations. :star:260

### Kotlin
- [Anko](https://github.com/Kotlin/anko) - DSL for Android written in Kotlin by JetBrains. :star:9048
- [Kotterknife](https://github.com/JakeWharton/kotterknife) - Android view injection written in Kotlin based on ButterKnife :star:1770
- [Android Kotlin Samples](https://github.com/irontec/android-kotlin-samples) - Some basic Android code samples written in Kotlin. :star:210
- [KAndroid](https://github.com/pawegio/KAndroid) - Lightweight library providing useful extensions to eliminate boilerplate code in Android SDK. :star:662
- [RxKotlin/Pocket](https://github.com/RxKotlin/Pocket) - This app help user to save links easily, and can export to Evernote as weekly. :star:18

# Performance
- [awesome-android-performance](https://github.com/Juude/awesome-android-performance) - A list of awesome Android tutorials, videos and tools for performance optimization. :star:2251

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
