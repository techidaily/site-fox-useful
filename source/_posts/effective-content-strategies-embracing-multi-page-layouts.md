---
title: "Effective Content Strategies: Embracing Multi-Page Layouts"
date: 2024-09-24T00:54:29.640Z
updated: 2024-09-30T02:18:47.587Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Effective Content Strategies: Embracing Multi-Page Layouts"
thumbnail: https://thmb.techidaily.com/91f7f58741561326931ca324590beadc475f32b45bcc3a270b10ca0d40e00353.jpg
---

## Effective Content Strategies: Embracing Multi-Page Layouts

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Product Details](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Digital Signature](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Updater](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Upgrades](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Licensing Page](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [CD/DVD Autorun](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Multiple Instances Page](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Instance Properties Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Instance Components Tab](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Multiple Instances Page

This page allows you to install multiple instances of your product on the target computer. The existence of multiple instances is verified by the [EXE setup file](https://tools.techidaily.com/advancedinstaller/products/). This is why the corresponding option must be checked in the [Configuration Tab](https://tools.techidaily.com/advancedinstaller/products/) page.

![Multiple instances](https://cdn.advancedinstaller.com/img/ui/multiple-instances.png "Multiple instances")  

Windows Installer permits only one instance of the ProductCode to be installed per machine and one instance to be installed per user. Starting with Windows Installer 3.x or later multiple instances can be installed by applying ProductCode transforms (called instance transforms) to the base MSI package.

Advanced Installer creates a transform for each defined instance with the same name as in the “Instance IDs” pane and streams it into the MSI database. When the package runs the Multiple Instances selection dialog displayed by the EXE allows the user to install new instance or maintain an already installed one.

The instances are uniquely distinguished by a new**ProductCode** and additionally by the **InstanceId** property. Other properties can be created in the [Instance Properties](https://tools.techidaily.com/advancedinstaller/products/) page. When the first instance is created the InstanceId property, it is added to the project with "#0" as value for the selected build. You can change it in the [Install Parameters](https://tools.techidaily.com/advancedinstaller/products/) page.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The "#0" value is reserved for the base package.

 Advanced Installer uses the name of an instance from “Instance IDs” pane as the InstanceId property value for the corresponding instance. The InstanceId property **will not** be resolved outside the Multiple Instances page.

### Creating a new instance

 Use the “New Instance” command from the context menu or press the Insert key while the “Instance IDs” panel is selected, in order to create a new instance.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Renaming an instance

 Use the “Rename” command from the context menu or press the F2 key while an element is selected, to rename an instance.

### Removing an instance

 Use the “Delete” command from the context menu, or press the Delete key while an element is selected, to remove an instance.

### Specifying the instances' installation order

Use the “Move Up” / “Move Down” context menu item or press the Shift+Up /Shift+Down keys while an instance is selected.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134227/18498" target="_top" id="2134227">
  <img src="//a.impactradius-go.com/display-ad/18498-2134227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134227/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Generate instances at install time

This option enables generating custom name instances at install time for the selected build. It implies loosing all previously created instances.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Build major upgrades for multiple instances

The package is built with major upgrades support. This option has effect only after changing the [Product Version](https://tools.techidaily.com/advancedinstaller/products/). 

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)You cannot author major upgrades and generate instances at install time. The two options above are not compatible.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934258/19272" target="_top" id="1934258">
  <img src="//a.impactradius-go.com/display-ad/19272-1934258" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934258/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Topics

* [Instance Properties Tab](https://tools.techidaily.com/advancedinstaller/products/)  
In this tab you can set/overwrite properties for an instance.
* [Instance Components Tab](https://tools.techidaily.com/advancedinstaller/products/)  
In this page you can overwrite components for an instance.

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-first-edition-top-notch-user-centric-game-edit-apps/"><u>[New] In 2024, First Edition Top-Notch, User-Centric Game Edit Apps</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-stepwise-guide-to-travel-back-in-time-with-facebooks-archive-laptop-and-mobile-for-2024/"><u>[New] Stepwise Guide to Travel Back in Time with Facebook's Archive (Laptop & Mobile) for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-art-and-craft-of-documentary-writing/"><u>[Updated] The Art and Craft of Documentary Writing</u></a></li>
<li><a href="https://facebook.techidaily.com/can-llife-reemerge-and-thrive-amidst-the-new-age-of-metaversal-exploration/"><u>Can LLife Reemerge and Thrive Amidst The New Age of Metaversal Exploration?</u></a></li>
<li><a href="https://buynow-info.techidaily.com/explore-cinemas-treasure-trove-a-guide-to-the-best-online-hubs-for-trailers/"><u>Explore Cinema's Treasure Trove: A Guide to the Best Online Hubs for Trailers</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-poco-f5-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Poco F5 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://fox-useful.techidaily.com/how-to-easily-add-interactive-page-turning-books-on-wordpress-through-flipbuilder-technology/"><u>How to Easily Add Interactive Page-Turning Books on WordPress Through FlipBuilder Technology</u></a></li>
<li><a href="https://fox-useful.techidaily.com/how-to-modify-the-resolution-and-dimensions-of-pdf-files-in-flippdf-pro-comprehensive-guide/"><u>How to Modify the Resolution & Dimensions of PDF Files in FlipPDF Pro - Comprehensive Guide</u></a></li>
<li><a href="https://fox-useful.techidaily.com/how-to-pre-organize-your-photos-for-optimal-flipbook-creation-on-flipbuilder/"><u>How to Pre-Organize Your Photos for Optimal FlipBook Creation on FlipBuilder</u></a></li>
<li><a href="https://fox-useful.techidaily.com/how-to-quickly-print-singlemultiple-pages-from-a-digital-flipbook-on-flipbuilder/"><u>How to Quickly Print Single/Multiple Pages From a Digital Flipbook on FlipBuilder</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-navigating-google-voice-call-logging-with-ease/"><u>In 2024, Navigating Google Voice Call Logging with Ease</u></a></li>
<li><a href="https://screen-recording.techidaily.com/tackling-inaudible-speech-in-obs-captures/"><u>Tackling Inaudible Speech in OBS Captures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-overwatch-voice-communication-problems-fast/"><u>Troubleshoot and Resolve Overwatch Voice Communication Problems Fast</u></a></li>
</ul></div>

