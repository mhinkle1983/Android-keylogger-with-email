# Android keylogger  with email
Utilises android Accessibility Service to log almost every activity with SMTP support for exporting logs via email. 
__This is made just for fun and to demonstrate how android's accessibility service can be misused, please do not use it malicious purpose__
## features
- Tiny APK Size around ( around 200Kb)
- App icon not Displayed in System Launcher
- Not just keylogging, also logs apps usage and gestures.
## Setup
- gmail SMTP is used by default to change modify `SendMail.java`
- add your gmail details in `Config.java`
- add the mail address where logs must be sent to`testService.java` (just replace 'XXXXX' with maril).
- Build APK, use Android Studio or whatever you like.
- Install app and grant accessibilty access.
