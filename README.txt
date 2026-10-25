MISSION 35 PLUS — Attendance & Reminders starter app

FEATURES
- Add college subjects
- Log attendance by subject/date: Present, Absent, or On Duty/approved leave
- Automatic per-subject and overall percentages
- Same subject/date updates existing record to prevent duplicates
- Export attendance as CSV
- Daily mission checklist
- Add reminders with date, time, category, and repeat label
- Optional browser notifications while the app/browser is active
- JSON backup and restore
- Data stored locally in the browser; no server sync

ANDROID SETUP
1. Extract the ZIP using your phone's Files app.
2. For best installability, host the folder on an HTTPS static host you control (e.g. GitHub Pages) or use a local web server. A PWA generally cannot be installed with full features by opening index.html directly from the file manager.
3. Open the HTTPS app URL in Chrome on Android.
4. Chrome menu (three dots) > Add to Home screen / Install app.
5. Open the app and add subjects, then log attendance.
6. Download a JSON backup periodically.

IMPORTANT LIMITATIONS
- This is a PWA starter, not a native APK.
- Browser reminders are not guaranteed when Chrome/app is closed or Android suspends it. Use Clock/Calendar for critical alarms.
- Repeating reminders are stored with a repeat label; this starter does not generate every future repeated occurrence automatically.
- Local browser storage may be lost if site data is cleared. Export backups.
- It does not log into SIS or store SIS credentials.
- Attendance percentage counts Present and On Duty as attended; Absent counts against attendance. Confirm your college's official rules for OD/leave.
