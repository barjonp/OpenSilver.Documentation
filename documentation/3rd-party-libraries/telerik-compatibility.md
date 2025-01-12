# OpenSilver Compatibility TelerikUI

Telerik UI for Silverlight has been migrated successfully to the OpenSilver platform. Both new projects and migrations can reuse Telerik UI now.

The OpenSilver Compatibility TelerikUI package is distributed via MyGet. You will get a link after purchasing a license.

Prerequisites:
* A license for UI from Telerik
* A license for the OpenSilver Compatibility TelerikUI nuget package

There are two types of licenses for the OpenSilver Compatibility TelerikUI Package:
* **Trial**. It is valid for 30 days and can be obtained via [this form](https://opensilver.net/request-Telerik.aspx). You can use all the available components and features of Telerik UI. However, the OpenSilver application will stop working after 30 days from the issue date.
* **Perpetual**. This license is valid forever and, also, it includes free updates for one year since the purchase date. To purchase this license, please follow [this form](https://opensilver.net/request-Telerik.aspx).

### How to start using OpenSilver Compatibility TelerikUI?

1. Create a new OpenSilver application.
2. Add a reference to the OpenSilver Compatibility TelerikUI package into the OpenSilver project.

To do so using Visual Studio, start by right-clicking on the  OpenSilver project in the Solution Explorer, and click "Manage NuGet Packages...":

<img src="/images/3rd-party-libraries/telerik-manage-packages.png" alt="Manage NuGet Packages..." />


Then, click on the "Settings" icon near "Package Sources":

<img src="/images/3rd-party-libraries/telerik-change-package-sources.png" alt="Manage NuGet Packages..." />


Then, add the package source (note: the actual feed URL varies: please use the one that you received by email from Userware):

<img src="/images/3rd-party-libraries/telerik-set-package-source.png" alt="Manage NuGet Packages..." />


Finally, select the newly-added feed and install the package:

<img src="/images/3rd-party-libraries/telerik-install-the-package.png" alt="Manage NuGet Packages..." />

4. Add the license file to your project. The license file is the file named "OpenSilver.Compatibility.TelerikUI.license.json" which had been sent to you by Userware when you obtained the Trial or Perpetual license. This file should be added as an "Embedded Resource" into the OpenSilver project, as show in the screenshot below.

Follow the red borders on the picture to check that everything is done correctly:

<img src="/images/3rd-party-libraries/telerik-license.png" alt="Example of licensing" />

### Where can I find examples of use of Telerik controls in OpenSilver?

You can find examples by cloning the repository of the "OpenSilver Telerik Showcase", which contains samples that demonstrate each supported Telerik control:
* The source code can be found [here on GitHub](https://github.com/OpenSilver/OpenSilver.Samples.TelerikUI)
* A live demo is available [here](https://opensilverdemos.azurewebsites.net/telerikshowcase/release/?20220908)

After cloning the repository, please reference the OpenSilver Compatibility TelerikUI package and add the trial or perpetual license file as an "Embedded Resource" into the UI project, as detailed in the section above.

**Reminder:** you need to own a license from Telerik for 'Telerik UI for Silverlight' in order to have the right to use the controls in an OpenSilver project.
