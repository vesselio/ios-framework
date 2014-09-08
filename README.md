Vessel iOS-framework (Studio Beta)
=============


<strong>Step I: Download</strong>

1.Login to Vessel Command Center
2.Add your application
3.Get Vessel Secret Key

<strong>Step II: Unzip and Install</strong>

1.Make sure you are using the latest version of Xcode (v4.6+) and targeting iOS 4.3 or higher.
2.Download https://github.com/vesselio/ABTesting/archive/Studio.zip
2.Unzip the file and drag the Vessel.framework folder into your Xcode project folder target.


<strong>Step III: Link libraries</strong>

1.Select you project in Xcode<br>
2.Click your app name under Targets<br>
3.Select the Build Phases tab<br>
4.Expand the Link Binary With Libraries<br>


<strong> Step IV: Add the following frameworks:</strong>

1.SystemConfiguration.framework<br>
2.Security.framework<br>
3.CFNetwork.framework<br>
4.libsqlite3.dylib<br>
5.libicucore.dylib<br>

<strong> Step V: Import, Buld & Run</strong>

1. Open your AppDelegate.m file. Import Vessel header
2. Build your application. 

<strong>Run!</strong>

