# awesome-xamarin
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/benoitjadinon/awesome-xamarin.svg)](https://travis-ci.org/benoitjadinon/awesome-xamarin)

A hand-picked bookmark collection of subjectively modern/interesting libraries/tools for Xamarin Android/iOS/WP libraries.

Inspired by [awesome-dotnet](https://github.com/quozd/awesome-dotnet)
  
  * [General](#general)
  * [UI Components](#ui-components)
  * [Architecture](#architecture)
  * [Async](#async)
  * [Cloud](#cloud)
  * [Framework](#frameworks)
  * [Fody](#fody)
  * [Game Engine](#game-engine)
  * [Imaging](#imaging)
  * [IO](#io)
  * [IOC](#ioc)
  * [Internationalization](#internationalization)
  * [MVVM](#mvvm)
  * [Network](#network)
  * [Security](#security)
  * [Serialization](#serialization)
  * [Storage](#storage)
  * [Reactive](#reactive)
  * [TDD/BDD](#tdd-bdd)
  * [Tools](#tools)
  * [Wearable](#wearable)
  * [Xamarin.Forms](#xamarin-forms)
  * [More XPlat APIs](#xplat-apis)

## General
* [**AutoMapper ★3,411**](https://github.com/AutoMapper/AutoMapper) - A convention-based object-object mapper in .NET
* [**Humanizer ★1,894**](https://github.com/Humanizr/Humanizer) - Manipulation and displaying of strings, enums, dates, times, timespans, numbers and quantities
* [**Fluent Validation ★1,314**](https://github.com/JeremySkinner/FluentValidation) - Fluent interface and lambda expressions for building validation rules
* [NodaTime](http://nodatime.org/) - Alternative date and time API for .NET
* [**Polly ★1,392**](https://github.com/App-vNext/Polly) - Exception handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker

## UI Components
* [Passcode ★5](https://github.com/kevinskrei/XamarinPasscode) - Xamarin component for locking an app with a passcode

## Architecture
* [Behaviors Toolkit ★19](https://github.com/ThomasLebrun/XamarinBehaviorsToolkit) - A means of adding common and reusable interactivity to your Xamarin applications with minimal code
* [**Stateless ★510**](https://github.com/dotnet-state-machine/stateless) - State Machines

## Async
* [AsyncEx ★402](https://github.com/StephenCleary/AsyncEx) - A helper library for async/await
* [LinqToAwait ★80](https://github.com/paulcbetts/LinqToAwait) - A Task-based LINQ designed to work with async/await

## Cloud
* [Azure](https://developer.xamarin.com/guides/cross-platform/azure/) - Microsoft Azure
* [FireSharp ★159](https://github.com/ziyasal/FireSharp) - Firebase REST API wrapper

## Fody
* [**Fody ★975**](https://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies 
* [ReactiveUI.Fody ★25](https://github.com/kswoll/ReactiveUI.Fody) - Generate RaisePropertyChange notifications for properties and ObservableAsPropertyHelper properties
* [AutoDependencyProperty.Fody](https://bitbucket.org/robertvazan/autodependencyproperty.fody/overview) - Automatically generates DependencyProperty boilerplate from simple C# properties
* [PropertyChanged.Fody](https://github.com/Fody/PropertyChanged/) - Injects INotifyPropertyChanged code into properties at compile time

## Framework
* [SimplyMobile ★77](https://github.com/sami1971/SimplyMobile) - Collection of abstracted mobile functionalities

## Game Engine
* [CocosSharp ★328](https://github.com/mono/CocosSharp) - C# implementation of the Cocos2D and Cocos3D APIs
* [**MonoGame ★3,416**](https://github.com/mono/MonoGame) - Open source implementation of the Microsoft XNA 4.x Framework 
* [**Paradox ★852**](https://github.com/SiliconStudio/xenko) - Paradox3D + Silicon Studio .NET
* [UrhoSharp](https://developer.xamarin.com/guides/cross-platform/urho/) - Cross-platform high-level 3D and 2D engine

## Imaging
* [Fast & Furious Image Loading ★130](https://github.com/molinch/FFImageLoading) - Xamarin library to load images quickly & easily
* [NGraphics ★234](https://github.com/praeclarum/NGraphics) - Cross platform library for rendering vector graphics
* [SkiaSharp](https://developer.xamarin.com/guides/cross-platform/drawing/) - Powerful C# API for doing 2D graphics. It is powered by Google’s Skia library
* [Splat ★402](https://github.com/paulcbetts/splat) - Cross platform image loading, colors and stuff
* [EZ-Compress ★3](https://github.com/VictorGrunn/EZ-Compress-for-Xamarin) - A simple image stream compression plugin for Xamarin

## IO
* [io ★2](https://github.com/aritchie/io) - Access system folders and files using a familiar api
mobile-optimized libs (NSURLSession / OkHttp)
* [PCL Storage ★106](https://github.com/dsplaisted/PCLStorage) - consistent, portable set of local file IO APIs for .NET

## IOC/DI
* [**Autofac ★965**](https://github.com/autofac/Autofac) - An addictive .NET IoC container
* [DryIoc](https://bitbucket.org/dadhi/dryioc) - fast, small, full-featured IoC Container for .NET
* [Funq ★0](https://github.com/thiagoromam/FunqPortable) - High performance DI framework by eliminating all runtime reflection through the use of lambdas and generic functions as factories
* [LightInject ★177](https://github.com/seesharper/LightInject) - Light, simple and stunningly fast IoC container for .NET
* [**Ninject ★1,450**](https://github.com/ninject/Ninject) - The ninja of .net dependency injectors
* [Stiletto](https://github.com/benjamin-bader/stiletto) - .NET port of Dagger, the lightweight Android dependency injector from Square
* [TinyIoC ★422](https://github.com/grumpydev/TinyIoC) - Single-class easy IoC container

## Internationalization
* [Resxible ★5](https://github.com/apcurium/resxible) - tool to generate automatically several platform-dependent resource files from a single RESX file.
* [Vernacular ★158](https://github.com/rdio/vernacular) - Cross Platform Localisation, tools to convert standard strings formats

## MVVM
* Frameworks
  * [**MVVMCross ★1,525**](https://github.com/MvvmCross/MvvmCross) - Cross-platform mvvm mobile development framework
	* [Cheesebaron.MvxPlugins ★65](https://github.com/Cheesebaron/Cheesebaron.MvxPlugins) - A collection of plugins
		* [MvxAms](https://github.com/MobiliTips/MvxPlugins/tree/master/MvxAms) - MVVMCross Azure Mobile Services plugin
		* [MvxForms](https://github.com/MobiliTips/MvxPlugins/tree/master/MvxForms) - MVVMCross plugin for using Xamarin.Forms
	* [acrmvvmcross ★43](https://github.com/aritchie/acrmvvmcross) - Barcode, Device Info, IO, Network, Settings, Signature, User Dialogs
	* [Infinite Scroll Plugin ★14](https://github.com/HBSequence/Sequence.Plugins) - A Plugin which facilitates forward-only incremental scrolling for a paged data source.
  * [**ReactiveUI ★2,249**](https://github.com/reactiveui/ReactiveUI) - Rx MVVM framework
* [Bind ★98](https://github.com/praeclarum/Bind) - Bind gives you easy two-way data binding between properties of objects.
* [Fody/PropertyChanged ★301](https://github.com/Fody/PropertyChanged) - Injects INotifyPropertyChanged code into properties at compile time

## Network
* [Flurl ★206](https://github.com/tmenier/Flurl) - Flurl is a modern, fluent, asynchronous, testable, portable, buzzword-laden URL builder and HTTP client library.
* [Fusillade ★129](https://github.com/paulcbetts/Fusillade) - set of HttpMessageHandlers that make your mobile applications more efficient and responsive
* [Messaging](https://github.com/cjlotz/Xamarin.Plugins/tree/master/Messaging) - make a phone call, send a sms or send an e-mail using the default messaging applications
* [ModernHttpClient ★374](https://github.com/paulcbetts/ModernHttpClient) - Accelerates HTTP requests by using mobile-optimized libs (NSURLSession / OkHttp)
* [Push Notification](https://github.com/rdelrosario/xamarin-plugins/tree/master/PushNotification) - Simple cross platform plugin to handle push notification events such as registering, unregistering and messages arrival on Android and iOS.
* [Reachability ★7](https://github.com/has-taiar/Reachability.Net) - Online/offline connected check
* [**Refit ★802**](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET
* [RestEase ★37](https://github.com/canton7/RestEase) - Refit on steroids, simpler auth, parsing...
* [Sockets ★68](https://github.com/rdavisau/sockets-for-pcl) - An abstraction over the socket helper classes of .NET and WinRT

## Reactive
* [**Akavache ★1,148**](https://github.com/akavache/Akavache) - An Asynchronous Key-Value Store for Native Applications
* [**ReactiveUI ★2,249**](https://github.com/reactiveui/ReactiveUI) - Rx MVVM framework 
* [**Refit ★802**](https://github.com/paulcbetts/refit) - Refit is a library heavily inspired by Square's Retrofit library, and it turns your REST API into a live interface
* [RxFlow ★10](https://github.com/ugaya40/RxFlow) - Simple Flow Control Library with Rx(Reactive Extensions)

## Security
* [BoucyCastle.PCL ★43](https://github.com/onovotny/BouncyCastle-PCL) PCL Version of BouncyCastle (Cryptography) targetting .NET, SL, WP and WinRT
* [Fingerprint Plugin ★18](https://github.com/smstuebe/xamarin-fingerprint) - Xamarin and MvvMCross plugin for accessing the fingerprint sensor
* [PCLCrypto ★86](https://github.com/AArnott/PCLCrypto) - Cryptography for portable class libraries (MD5,...)
* [Permissions](https://github.com/jamesmontemagno/Xamarin.Plugins/tree/master/Permissions) Simple cross platform plugin to check connection status of mobile device, gather connection type, bandwidths, and more

## Serialization
* [**Newtonsoft.Json ★3,000**](https://github.com/JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET

## Storage
* [**Akavache ★1,148**](https://github.com/akavache/Akavache) - An Asynchronous Key-Value Store for Native Applications
* [Lager ★1](https://github.com/ghuntley/Lager) - Cross-platform settings storage that uses Akavache as a storage backend
* [**Massive ★1,530**](https://github.com/FransBouma/Massive) - "wrapper" for your DB tables and uses System.Dynamic extensively
* [Settings ★11](https://github.com/aritchie/settings) - Cross platform settings plugin for Xamarin and Windows
* [SQLite.Net-PCL ★237](https://github.com/oysteinkrog/SQLite.Net-PCL) - SQLite 3 databases support, PCL, async

## TDD/BDD
* [FluentAssertions](http://www.fluentassertions.com/) - TDD/BDD fluent asserts
* [NBehave ★36](https://github.com/nbehave/NBehave) - framework for Behaviour-Driven Development

## Tools
* [GradleBindings ★39](https://github.com/EgorBo/Xamarin.GradleBindings) - Visual Studio extension, for referencing gradle libs in Android projects
* [Material icons generator plugin ★8](https://github.com/interisti/material-icons-generator-plugin) - Xamarin Studio & Visual Studio plugin, for adding material icons to android project
* [**PushSharp ★3,114**](https://github.com/Redth/PushSharp) - A server-side library for sending Push Notifications to iOS (iPhone/iPad APNS), Android (C2DM and GCM - Google Cloud Message), Windows Phone, Windows 8, Amazon, Blackberry, and (soon) FirefoxOS devices!
* [Twin Tools Add-In ★7](https://github.com/twintechs/TwinToolsForXamarin) - Productivity plugin for Xamarin Studio
* [Xamaridea ★17](https://github.com/EgorBo/Xamaridea) - Visual Studio extension, opens *.axml files in Android Studio 

## Wearable
* [WormHoleSharp ★23](https://github.com/Clancey/WormHoleSharp) - Communication between Watch and iDevice

## Xamarin.Forms
* [Acr-xamarin-forms ★190](https://github.com/aritchie/acr-xamarin-forms) - Camera/Gallery, Barcode Scanning, User Dialogs, Geo-Location, Network Utils, Device Info, Settings, E-Mail, Phone, SMS all for Xamarin.Forms
* [AdvancedTimer ★9](https://github.com/ufuf/AdvancedTimer) - Timer object and its methods are implemented for extended support for timers.
* [Android AppCompat ★28](https://github.com/nativecode-dev/oss-xamarin) - Provide Material Design themes now for Xamarin.Forms apps natively without hacks
* [Circle Image Control](https://github.com/jamesmontemagno/Xamarin.Plugins/tree/master/ImageCircle) - Simple but elegant way of display circle images in your Xamarin.Forms projects
* [Compass](https://github.com/JarleySoft/Xamarin.Plugins/tree/master/Compass) - Provides and simple way to access the compass on Windows Phone, iOS and Android from you Xamarin.Forms projects
* [Device Orientation](https://github.com/aliozgur/Xamarin.Plugins/tree/master/DeviceOrientation) - Simple way to get device orientation or be notified of orientation changes in your Xamarin.Forms projects
* [NControl ★87](https://github.com/chrfalch/NControl) - Xamarin.Forms control for NGraphics
* [MvxForms ★7](https://github.com/MobiliTips/MvxPlugins) - MVVMCross plugin for using Xamarin.Forms
* [SolTech Xamarin Forms Toolkit ★18](https://github.com/soltechinc/soltechxf) - set of helpful extensions to the Xamarin Forms framework
* [Store Rating Plugin ★3](https://github.com/voxdev/Xamarin.Plugins) - Rate app popup
* [SVG](https://github.com/paulpatarinski/Xamarin.Forms.Plugins/tree/master/SVG) - SVG file format support
* [Toasts Plugin ★78](https://github.com/EgorBo/Toasts.Forms.Plugin) - A simple way of showing some notifications inside your Xamarin.Forms application
* [TwinTechsFormsLib ★94](https://github.com/twintechs/TwinTechsFormsLib) - FastCell, FastImage, FastGridCell
* [**Xamarin-Forms-Labs ★749**](https://github.com/XLabs/Xamarin-Forms-Labs) - Powerful and cross platform set of controls and helpers
* [xamarin-forms-xna ★5](https://github.com/jvlppm/xamarin-forms-xna) - Monogame wrapper for Xamarin.Forms

## More XPlat APIs
Most of them support Android and iOS, some do Windows Phone 8

* [barcodes ★4](https://github.com/aritchie/barcodes) - A cross platform barcode scanning and creating library built on top of ZXing.Net.Mobile.
* [biometrics ★2](https://github.com/aritchie/biometrics) - (Fingerprint Sensor) For Xamarin (iOS & Android)
* [Calendars ★9](https://github.com/TheAlmightyBob/Calendars) - Calendar API plugin for Xamarin and Windows Phone, Supports basic CRUD operations with calendars and events.
* [Device Motion](https://github.com/rdelrosario/xamarin-plugins/tree/master/DeviceMotion) - Simple cross platform plugin to read motion vectors value for device motion sensors such as: Accelerometer, Gyroscope, Magnetometer, Compass.
* [Estimote ★12](https://github.com/aritchie/estimotes-xplat) - Cross platform implementation of the estimote library for beacons.
* [Fingerprint ★18](https://github.com/smstuebe/xamarin-fingerprint) - Xamarin and MvvMCross plugin for accessing the fingerprint sensor.
* [HybridKit ★6](https://github.com/chkn/HybridKit) - Simple C# – JavaScript bridge for building hybrid iOS and Android apps.
* [Lamp](https://github.com/kphillpotts/Xamarin.Plugins/tree/master/Lamp) - Simple way of controlling the lamp/LED on the back of your phone from Xamarin and Xamarin.Forms projects
* [ManageSleep ★4](https://github.com/molinch/Xam.Plugins.ManageSleep) - Manage auto sleep / auto lock in all platforms. This is useful when dealing with long running processes
* [Messaging ★25](https://github.com/cjlotz/Xamarin.Plugins) - The Messaging plugin makes it possible to make a phone call, send a sms or send an e-mail using the default messaging applications on the different mobile platforms.
* [notifications ★5](https://github.com/aritchie/notifications) - Notifications plugin for Xamarin and Windows
* [Telephony ★8](https://github.com/ghuntley/telephony) - Email, sms, voice and video call functionality
* [userdialogs ★92](https://github.com/aritchie/userdialogs) - Standard user dialogs from a shared/portable library.
* [Version](https://github.com/mtrinder/Xamarin.Plugins/tree/master/Version) - Get app version from bundle
* [Xamarin.Badge ★15](https://github.com/B1naryStudio/Xamarin.Badge) - Simple cross platform plugin to work with application badge
* [Xamarin.LocalNotifications ★23](https://github.com/B1naryStudio/Xamarin.LocalNotifications) - Simple cross platform plugin to work with mobile local notifications
* [Xamarin.Mobile ★181](https://github.com/xamarin/Xamarin.Mobile) - Reading the user's address book and using the camera
* [xamarin-plugins ★12](https://github.com/domaven/xamarin-plugins) - Device Motion, Geofencing, Push Notifications (Beta)
* [Xamarin.Plugins ★468](https://github.com/jamesmontemagno/Xamarin.Plugins) - Battery Status, Connectivity, Contacts, Device Information, Extended Maps, Geolocator, Media, Settings, Text To Speech, Vibrate, Circle Image for Xamarin.Forms
* [Plugins for Xamarin ★231](https://github.com/xamarin/plugins) - Here you will find a listing of cross platform Plugins for Xamarin that support Xamarin.iOS, Xamarin.Android, Xamarin.Forms, and Windows Platform from a single API.


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Benoit Jadinon has waived all copyright and related or neighboring rights to this work.
