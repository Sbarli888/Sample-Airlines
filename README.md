Airlines
===============
<a href="https://platform.telerik.com/#appbuilder/clone/https%3A%2F%2Fgithub.com%2FIcenium%2Fsample-airlines" target="_blank"><img src="http://docs.telerik.com/platform/appbuilder/sample-apps/images/try-in-appbuilder.png" alt="Try in AppBuilder" title="Try in AppBuilder" /></a>  <a href="https://github.com/Icenium/sample-airlines" target="_blank"><img style="padding-left:20px" src="http://docs.telerik.com/platform/appbuilder/sample-apps/images/get-github.png" alt="Get from GitHub" title="Get from GitHub"></a>

<a id="top"></a>
* [Overview](#overview)
* [Showcased APIs](#showcased-apis)
* [Important Directories and Files](#important-directories-and-files)
* [Screenshots](#screenshots)
* [Test the Sample](#test-the-sample)
* [Limitations](#limitations)

# Overview

This sample app is a simple air trip management app. Developed with Apache Cordova and jQuery Mobile, this app lets you log into your account with a fictitious airline company, view your trips, check in for flights and change seat selection.

> *Supported mobile platforms:* iOS, Android, Windows Phone
>
> *Developed with:* Apache Cordova 3.7.0, jQuery Mobile 1.3.1

[Back to Top](#top)

# Showcased APIs

This sample shows how to use the following widgets and features of jQuery Mobile.

* **[MVC][MVC]:** Model-view-controller is a design pattern which helps developers separate the model (the data) from the view (the UI) and the process that accepts input and converts it to commands to the view or the model (the controller).
* **mobile:** The base object of jQuery Mobile.
* **[Page][Page]:** This widget manages a single item in the page-based architecture of jQuery Mobile. In this sample app, each page represents a screen in the application.
* **[Header][Header]:** This widget is a toolbar at the top of the page. Usually contains the page title and some buttons.
* **[Listview][Listview]:** This widget displays simple unordered lists of items.
* **[Button][Button]:** This widget creates a tappable button based on standard HTML anchor and input elements.
* **[Widget data attributes][Widget data attributes]:** The various data attributes let you customize your widgets.

This sample shows how to use the following Apache Cordova core plugin.

* **[Splashscreen][Splashscreen]:** This plugin lets you hide or show the splashscreen programmatically.

[Back to Top](#top)

# Important Directories and Files

* `scripts\airlinedata.js`: Contains the model implementation of the MVC.
* `scripts\main.js`: Contains the controller implementation of the MVC.
* `scripts\seatmapdrawing.js`: Contains the implementation of the SVG-based seat selector.

[Back to Top](#top)

# Screenshots

Platform | Login | User Home | Trips | Trip Details 
---|---|---|---|---
All | ![](https://github.com/Icenium/sample-airlines/blob/master/screenshots/login.jpg) | ![](https://github.com/Icenium/sample-airlines/blob/master/screenshots/user-home.jpg) | ![](https://github.com/Icenium/sample-airlines/blob/master/screenshots/trips.jpg) | ![](https://github.com/Icenium/sample-airlines/blob/master/screenshots/trip-info.jpg)

Platform | Seat Selector | Boarding Pass | &nbsp; | &nbsp; 
---|---|---|---|---
All | ![](https://github.com/Icenium/sample-airlines/blob/master/screenshots/seat-selector.jpg) | ![](https://github.com/Icenium/sample-airlines/blob/master/screenshots/boarding-pass.jpg) | &nbsp; | &nbsp;

[Back to Top](#top)

# Test the Sample

Apart from exploring the sample code base in GitHub, you can also clone and run the sample in your preferred AppBuilder client.

## In-Browser

With the AppBuilder in-browser client, you can develop hybrid and NativeScript cross-platform mobile apps from your browser. You can use the in-browser client at [https://platform.telerik.com](https://platform.telerik.com).

### Clone the sample

1. Click **Try in AppBuilder** above.
1. Provide your login credentials, if prompted.

### Run the sample

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Deploy on device via QR code.][QR code]

[Back to Top](#top)

## Windows

With the AppBuilder Windows client, you can develop hybrid and NativeScript cross-platform mobile apps from your Windows desktop. You can download and install the Windows client from [http://www.telerik.com/appbuilder/windows-client](http://www.telerik.com/appbuilder/windows-client).

### Clone the sample

1. Verify that the AppBuilder Windows client is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. In the dashboard, click **Samples** and select **Hybrid**.
1. From the **Workspace** drop-down menu, select the workspace in which you want to develop your application.
1. Select **Demos**.
1. Select **Airlines**.
1. (Optional) Rename the project.
1. Click **Clone**.

### Run the sample

With the AppBuilder Windows client, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

## Visual Studio

With the AppBuilder extension for Visual Studio, you can develop hybrid and NativeScript cross-platform mobile apps from Microsoft Visual Studio. You can download and install the extension from [http://www.telerik.com/appbuilder/visual-studio-extension](http://www.telerik.com/appbuilder/visual-studio-extension).

### Clone the sample

1. Verify that the AppBuilder extension for Visual Studio is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. Select **AppBuilder** &#8594; **Get Sample**.
1. Select **Hybrid**.
1. Select **Demos**.
1. Select **Airlines**.
1. (Optional) Rename the project.
1. Click **Get**.

The extension for Visual Studio copies the sample files locally. The extension creates a new solution and project and loads them.

### Run the sample

With the AppBuilder extension for Visual Studio, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

## CLI

With the AppBuilder command-line interface, you can develop hybrid and NativeScript cross-platform mobile apps from the command line. You can learn how to add the AppBuilder commands to your command line from [http://www.telerik.com/appbuilder/command-line-interface](http://www.telerik.com/appbuilder/command-line-interface).

### Clone the sample

1. Verify that a command prompt is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. To list the available samples, run the following command.

	```bash
	appbuilder sample
	```
1. Run the clone command for the sample as listed by `appbuilder sample`.
	
	```bash
	appbuilder sample clone airlines
	```

The AppBuilder command-line interface shows the following message: `Successfully initialized project in the folder!`

### Run the sample

With the AppBuilder command-line interface, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

# Limitations

* You cannot use the seat selector on devices running Android versions earlier than Honeycomb.
* [jQuery Mobile 1.3.1][jQuery Mobile 1.3.1] is a legacy release. Many APIs are now deprecated.
* The login is a dummy functionality. The login data is hardcoded and is never verified on login.
* Only the trip management functionality is implemented.

[Back to Top](#top)

[device simulator]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-apps-in-simulator/launch-simulator
[companion]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/run-companion/using-appbuilder-companion-app
[QR code]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/deploy-remote
[USB deploy]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/running-on-connected-devices/deploy-connected
[emulators]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-in-emulators/native-emulators
[jQuery Mobile 1.3.1]: http://api.jquerymobile.com/1.3/
[Page]: http://api.jquerymobile.com/1.3/page/
[Header]: http://api.jquerymobile.com/1.3/header/
[Listview]: http://api.jquerymobile.com/1.3/listview/
[Button]: http://api.jquerymobile.com/1.3/button/
[Widget data attributes]: http://api.jquerymobile.com/1.3/data-attribute/
[MVC]: https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller
[Splashscreen]: https://www.npmjs.com/package/cordova-plugin-splashscreen