Coalescing timers sample
========================

This sample shows how to coalesce low priority WM\_TIMER messages. Specifically, this sample covers using the [**SetCoalescableTimer**](http://msdn.microsoft.com/en-us/library/windows/desktop/hh405404) function to identify the WM\_TIMER messages to coalesce.

**Note**  WM\_TIMER messages are lower priority than other Windows messages and receive special treatment within the message queue. It is expected that these timers are handled when applications are almost idle and provide a better opportunity for coalescing than the other high-resolution, fine-accuracy timers. Coalescing can significantly reduce power usage.

**Warning**  This sample requires Microsoft Visual Studio 2013 or a later version (any SKU) and will not compile in Microsoft Visual Studio Express 2013 for Windows.

**Note**  The Windows-classic-samples repo contains a variety of code samples that exercise the various programming models, platforms, features, and components available in Windows and/or Windows Server. This repo provides a Visual Studio solution (SLN) file for each sample, along with the source files, assets, resources, and metadata needed to compile and run the sample. For more info about the programming models, platforms, languages, and APIs demonstrated in these samples, check out the documentation on the [Windows Dev Center](https://dev.windows.com). This sample is provided as-is in order to indicate or demonstrate the functionality of the programming models and feature APIs for Windows and/or Windows Server. This sample was created for Windows 8.1 and/or Windows Server 2012 R2 using Visual Studio 2013, but in many cases it will run unaltered using later versions. This sample was created for Windows 8.1 and/or Windows Server 2012 R2 using Visual Studio 2013, but in many cases it will run unaltered using later versions. Please provide feedback on this sample!

To get a copy of Windows, go to [Downloads and tools](http://go.microsoft.com/fwlink/p/?linkid=301696).

To get a copy of Visual Studio, go to [Visual Studio Downloads](http://go.microsoft.com/fwlink/p/?linkid=301697).

Related topics
--------------

[Windows and Messages](http://msdn.microsoft.com/en-us/library/windows/desktop/ms632586)

Related technologies
--------------------

[Timers](http://msdn.microsoft.com/en-us/library/windows/desktop/ms632592)

Operating system requirements
-----------------------------

Client

Windows 8.1

Server

Windows Server 2012 R2

Build the sample
----------------

To build this sample:

1.  Start Visual Studio and select **File** \> **Open** \> **Project/Solution**.
2.  Go to the directory named for the sample, and double-click the Microsoft Visual Studio Solution (.sln) file.
3.  Press F7 (or F6 for Visual Studio 2013) or use **Build** \> **Build Solution** to build the sample.

Run the sample
--------------

To debug the app and then run it, press F5 or use **Debug** \> **Start Debugging**. To run the app without debugging, press Ctrl+F5 or use **Debug** \> **Start Without Debugging**.

