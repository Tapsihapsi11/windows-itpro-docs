---
title: Policy CSP - SmartScreen
description: Policy CSP - SmartScreen
ms.author: maricia
ms.topic: article
ms.prod: w10
ms.technology: windows
author: nickbrower
ms.date: 01/29/2018
---

# Policy CSP - SmartScreen



<hr/>

<!--StartPolicies-->
## SmartScreen policies  

<dl>
  <dd>
    <a href="#smartscreen-enableappinstallcontrol">SmartScreen/EnableAppInstallControl</a>
  </dd>
  <dd>
    <a href="#smartscreen-enablesmartscreeninshell">SmartScreen/EnableSmartScreenInShell</a>
  </dd>
  <dd>
    <a href="#smartscreen-preventoverrideforfilesinshell">SmartScreen/PreventOverrideForFilesInShell</a>
  </dd>
</dl>


<hr/>

<!--StartPolicy-->
<a href="" id="smartscreen-enableappinstallcontrol"></a>**SmartScreen/EnableAppInstallControl**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Added in Windows 10, version 1703. Allows IT Admins to control whether users are allowed to install apps from places other than the Store.

<!--/Description-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 – Turns off Application Installation Control, allowing users to download and install files from anywhere on the web.
-   1 – Turns on Application Installation Control, allowing users to only install apps from the Store.

<!--/SupportedValues-->
<!--EndPolicy-->

<hr/>

<!--StartPolicy-->
<a href="" id="smartscreen-enablesmartscreeninshell"></a>**SmartScreen/EnableSmartScreenInShell**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Added in Windows 10, version 1703. Allows IT Admins to configure SmartScreen for Windows.

<!--/Description-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 – Turns off SmartScreen in Windows.
-   1 – Turns on SmartScreen in Windows.

<!--/SupportedValues-->
<!--EndPolicy-->

<hr/>

<!--StartPolicy-->
<a href="" id="smartscreen-preventoverrideforfilesinshell"></a>**SmartScreen/PreventOverrideForFilesInShell**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Added in Windows 10, version 1703. Allows IT Admins to control whether users can can ignore SmartScreen warnings and run malicious files.

<!--/Description-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 – Employees can ignore SmartScreen warnings and run malicious files.
-   1 – Employees cannot ignore SmartScreen warnings and run malicious files.

<!--/SupportedValues-->
<!--EndPolicy-->
<hr/>

Footnote:

-   1 - Added in Windows 10, version 1607.
-   2 - Added in Windows 10, version 1703.
-   3 - Added in Windows 10, version 1709.

<!--EndPolicies-->

