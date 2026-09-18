DAILY TASK MONITOR — enhanced iPhone PWA

New features:
- Daily recurring tasks
- Completed tasks are automatically removed after 24 hours
- Employee name field
- Monthly completed/pending/overdue reports
- Employee completion report
- Monthly calendar with task indicators
- Reminder field and notification support while the app is active; service-worker notifications are supported when invoked
- Colourful redesigned interface
- New app icon and iPhone apple-touch-icon
- Offline caching

Install:
1. Publish this folder over HTTPS (for example GitHub Pages).
2. Open the HTTPS site in Safari.
3. Share > Add to Home Screen.
4. Open the Home Screen app and allow notifications if prompted.

Important: true scheduled background reminders at an arbitrary future time require a Web Push subscription plus a push service/server. The current app provides reminder scheduling while the app is active and uses the service worker for notifications. No server credentials are included.
