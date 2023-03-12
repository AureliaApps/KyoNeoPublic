## Kyo Changelog
### This Section will only be updated for Build 17+, the backlog may be eventually ported, but isn't a priority at this time.

## Build 17

### ✨ New Features

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

### 🤓 Fixes
- Onboarding
    - Possible fix for gesture issues in onboarding, please test!
    - Fixed issue where welcome page might not show for new users
    - Fixed buttons not changing state from 'edit' → 'done'
    - Fixed swiping still working while in edit mode
- Fixed dark mode not behaving properly in some areas
- Fixed an issue where the timestamp would not be updated when editing an entry, meaning it's position would not update correctly 
- All elements that are disabled now show dimmed 

### 💔 Known Issues
- Onboarding might still be buggy
- The quarter sheet popup for creating/editing colours doesn't always animate correctly, and just snaps away
- Sometimes when expanding an entry, some text can behave incorrect and appear incorrectly
- Workaround: Disable 'Only countdown current day'
- Padding can appear incorrectly on some screens