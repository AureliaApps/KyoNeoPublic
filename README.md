<!-- Kyo Logo & Title -->
<br/>
<div align="center">
  <a href="https://github.com/AureliaApps/KyoNeoPublic">
    <img src="assets/logowo ;3.png" alt="Logo" width="196" height="196">
  </a>
  <h1 align="center">Kyo - School App</h3>
  <p align="center">
    All-in-one School and Lesson planner
    <br />
    <br />
    <a href="https://docs.google.com/forms/d/1NinLmmbEe3kLaupgTp2eWH6vM7NBExna42tVYwMhJvo">Beta Signup</a>
    ·
    <a href="https://github.com/AureliaApps/KyoNeoPublic/issues/new?assignees=Aeastr&labels=bug&template=bug_report.md&title=">Bug Reports</a>
    ·
    <a href="https://github.com/AureliaApps/KyoNeoPublic/issues/new?assignees=Aeastr&labels=feature&template=feature_request.md&title=">Feature Requests</a>
  </p>
</div>

<!-- Table of contents -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-kyo">About Kyo</a>
      <ul>
        <li><a href="#what-is-kyo-built-with">What is Kyo Built with?</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#using-kyo">Using Kyo</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#current-version">Current Version</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- OLD TITLE
# Kyo - School App
### School Planner and Lesson Planner
-->

## About Kyo
Kyo is an all-in-one comprehensive school and lesson planner for iOS devices. 

Using the Planner tool, you are able to organise and schedule your classes to ensure you arrive on time, all the time. 

Using the Tasks tool, you are able to map out and visualise your tasks and prioritise what's important.

#### What is Kyo Built with?
Kyo is written in fully native Swift and SwiftUI for iOS devices. This ensures the most optimal performance and a stable experience.

## Using Kyo
*This section is still currently in development and will be populated closer to full public release. Go to the Craft link below the Roadmap and Search for "Help (WIP), this will contain some information on how to use Kyo.*

<!---
Add features that are coming soon or already implemented,
maybe even a release date/estimated release? :p
--->
## Roadmap
| Feature | Planned? | Released? | Est Release |
|---------|----------|-----------|-------------|
| Today View | Yes | Coming Soon | - |
| Planner | Yes | Yes | - |
| Tasks | Yes | Coming Soon | - |

### If you have an idea or want to see a feature implemented in Kyo, feel free to fill out a feature request in the Issues section on the repo, or click [here](https://github.com/AureliaApps/KyoNeoPublic/issues/new?assignees=Aeastr&labels=feature&template=feature_request.md&title=).

### All build and feature information, past and present are also available on the Kyo [craft.do](https://www.craft.do/s/JKxsip1wINrS1v).

## Current Version
**Public Beta: 17** \
**Public Release: N/A** \
**For a changelog of older versions check out [CHANGELOG.md](https://github.com/AureliaApps/KyoNeoPublic/blob/main/CHANGELOG.md)**

<!-- When Public Release is out, have a separate ISSUES.md file for known issues past and present in beta, and public builds. -->
### ✨ New Features:
- Settings
    - Added general category
        - Added My Info
        - Added About
    - Look & Feel
        - Increase contrast now adds more contrast to backgrounds
        - Added Tint Pages option
            - Adds a small amount of colour behind main screens
    - 'Delete all my data' has become reset Kyo
        - Reset Kyo now brings up onboarding
    - Added option 'Only countdown current day'
- When resetting onboarding, it will also reset the welcome page
- Changed underlying structure for views
- Custom colours!
- Added debug options to context menus
- Recalculate timestamp
- Added some underlying structure for localisation
- Added some underlying structure for iOS 15
- Added link for (currently unfinished) github page
    - You'll be able notify me of issues here as well as other things

### 🤓 Fixes:
- Onboarding
  - Possible fix for gesture issues in onboarding, please test!
  - Fixed issue where welcome page might not show for new users
  - Fixed buttons not changing state from `edit` -> `done`
  - Fixed swiping still working while in edit mode
- Fixed dark mode not behaving properly in some areas
- Fixed an issue where the timestamp would not be updated when editing an entry, meaning it's position would not update correctly
- All elements that are disabled now show dimmed

### 💔 Known Issues:
- Onboarding might still be buggy
- The quarter sheet popup for creating/editing colours doesn't always animate correctly, and just snaps away
- Sometimes when expanding an entry, some text can behave incorrect and appear incorrectly
*Workaround: Disable `Only countdown current day`*
- Padding can appear incorrectly on some screens

## Contact
For feature requests, open a Feature Request in issues, or [click here](https://github.com/AureliaApps/KyoNeoPublic/issues/new?assignees=Aeastr&labels=feature&template=feature_request.md&title=).

For Bug Reports, open a Bug Report in issues, or [click here](https://github.com/AureliaApps/KyoNeoPublic/issues/new?assignees=Aeastr&labels=bug&template=bug_report.md&title=).

For Security concerns or vulnerabilities, please read [SECURITY.md](https://github.com/AureliaApps/KyoNeoPublic/blob/main/SECURITY.md).

## Acknowledgments
- Skye - [@rainyskye on GitHub](https://github.com/rainyskye)
- Lily - [lilaac.xyz](http://lilaac.xyz)
- Ethan Lipnik - [@EthanLipnik](https://twitter.com/EthanLipnik)
