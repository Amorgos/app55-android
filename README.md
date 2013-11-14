App55 Android Example
=====================

This is an example use of the app55-java library on the Android platform. Please see https://www.app55.com/docs for information on specific service endpoints for what you need to do.

Revision History
----------------
* 1.0 Initial release.

Dependencies
------------
* [app55-java](https://github.com/app55/app55-java) v0.8.4 or greater. Included in this example.
* [Jackson](http://wiki.fasterxml.com/JacksonDownload) Core / Mapper 1.9.x. Included in this example.

Running
-------
Running this example requires an Android 4.0 or greater compatible emulator or device.

1. Create an App55 account to get your API Key and Secret.
2. Checkout this project.
3. This is an Eclipse project, so you can just import it into Eclipse as an existing project.
4. Modify `Configuration.java` with your `API_KEY_DEFAULT` and `API_KEY_SECRET`.
5. Compile and deploy the application, and click run to execute the test script.

Notes
-----
* The example requires Android 4.0 or greater. This is due to bugs in java.net.URLConnection on Android versions prior to Honeycomb.
