---
title: Understanding Linked Data Packet Dynamics
date: 2024-10-08T04:52:37.587Z
updated: 2024-10-11T03:21:45.225Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Understanding Linked Data Packet Dynamics
thumbnail: https://thmb.techidaily.com/3b4fc9801ceec8439e874198c6f456d3f60986d5a7e58819eb6db488dc36873e.jpg
---

## Understanding Linked Data Packet Dynamics

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Prerequisites](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Predefined Prerequisites](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Installation Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Files Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Conditions Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Chained Package Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Edit PseudoFormatted Type Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Windows Features](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Windows Server Roles](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Specify Builds Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Launch Conditions](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Merge Modules](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Chained Package Behavior

A chained package can either be skipped or run as part of the main setup in the following modes:

* install
* uninstall
* maintenance

The chained package conditions are evaluated for install first, then for uninstall. Both conditions are evaluated in this order when the parent setup runs in install, uninstall and maintenance modes.

When these condition fields are left empty, then the chained package will run in the same mode as its parent setup. 

A chained package's run mode depends on three factors:

* parent setup run mode
* install condition
* uninstall condition

The following tables combine these three factors to clarify how the CP (chained package) will behave:

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)To read the table start from the top left cell then choose a column and a row based on how the conditions you have set in the [Chained Packages](https://tools.techidaily.com/advancedinstaller/products/) get resolved.

| **When the parent package is installed and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| -------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**  | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be installed                |
| **CP uninstall condition resolves to FALSE** | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be installed                |
| **CP uninstall condition field is EMPTY**    | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be installed                |

| **When the parent package is uninstalled and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| ---------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**    | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |
| **CP uninstall condition resolves to FALSE**   | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be skipped                  |
| **CP uninstall condition field is EMPTY**      | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |

| **When the parent package runs in maintenance mode and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| -------------------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**              | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |
| **CP uninstall condition resolves to FALSE**             | \=> CP will be installed                  | \=> CP will run in maintenance mode        | \=> CP will run in maintenance mode     |
| **CP uninstall condition field is EMPTY**                | \=> CP will be installed                  | \=> CP will run in maintenance mode        | \=> CP will run in maintenance mode     |

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
<li><a href="https://facebook-video-footage.techidaily.com/new-unlink-from-youtube-shorts-follow-this-plan/"><u>[New] Unlink From YouTube Shorts - Follow This Plan</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-achieving-stunning-light-conditions-with-an-iphone/"><u>2024 Approved Achieving Stunning Light Conditions with an iPhone</u></a></li>
<li><a href="https://fox-useful.techidaily.com/advanced-malicious-software-scrutiny-kits-expert-choices-for-rapid-attack-counteraction-and-security-reinforcement/"><u>Advanced Malicious Software Scrutiny Kits: Expert Choices for Rapid Attack Counteraction and Security Reinforcement</u></a></li>
<li><a href="https://fox-useful.techidaily.com/get-the-newest-information-breaking-news-and-fresh-insights/"><u>Get the Newest Information: Breaking News and Fresh Insights</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-realme-c33-2023-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Realme C33 2023 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-vivo-y27s-by-fonelab-android-recover-video/"><u>How to recover old videos from your Vivo Y27s</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-xiaomi-redmi-13c-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Xiaomi Redmi 13C to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-ordinary-to-stunning-photo-tile-magic/"><u>In 2024, From Ordinary to Stunning Photo Tile Magic</u></a></li>
<li><a href="https://fox-useful.techidaily.com/in-depth-tutorial-on-how-to-modify-hyperlink-settings-in-the-properties-panel/"><u>In-Depth Tutorial on How to Modify Hyperlink Settings in the Properties Panel</u></a></li>
<li><a href="https://fox-useful.techidaily.com/ini-tuner-pro-simplifying-your-journey-with-advanced-ini-file-editing-tools/"><u>INI Tuner Pro: Simplifying Your Journey with Advanced INI File Editing Tools</u></a></li>
<li><a href="https://fox-useful.techidaily.com/lag-free-hd-recording-solutions-the-ultimate-guide-for-capturing-minecraft-adventures/"><u>Lag-Free HD Recording Solutions: The Ultimate Guide for Capturing Minecraft Adventures</u></a></li>
<li><a href="https://win-able.techidaily.com/rainbow-six-siege-trouble-heres-how-to-get-rid-of-that-annoying-black-screen/"><u>Rainbow Six Siege Trouble? Here's How to Get Rid of That Annoying Black Screen</u></a></li>
<li><a href="https://extra-support.techidaily.com/rhythmic-reels-making-instagram-memories-to-the-beat-for-2024/"><u>Rhythmic Reels Making Instagram Memories to the Beat for 2024</u></a></li>
<li><a href="https://fox-useful.techidaily.com/top-rated-no-cost-video-editor-programs-perfect-for-windows-and-macos-users/"><u>Top Rated No-Cost Video Editor Programs: Perfect for Windows & macOS Users</u></a></li>
<li><a href="https://fox-useful.techidaily.com/top-strategies-for-high-quality-amazon-product-photos-skyrocket-your-online-sales/"><u>Top Strategies for High-Quality Amazon Product Photos: Skyrocket Your Online Sales</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-oppo-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from Oppo</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

