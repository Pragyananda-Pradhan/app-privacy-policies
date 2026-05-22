# Calculator Data Safety Notes

Use this as the starting point for the Google Play Console Data Safety form. It must match the real app behavior.

## Draft assumptions

- App name: Calculator
- Developer: Pragyananda-Pradhan
- Account creation: No
- Ads: No
- Analytics: No
- Crash reporting SDK: No
- Internet/network use: No app-operated network transfer
- Sensitive Android permissions: None
- Data transmitted off device: None
- Local data: calculation inputs/results during use, optional local calculation history, optional local display/theme preferences

## Suggested Data Safety answers for this exact draft

- Does your app collect or share any of the required user data types? No
- Is all user data collected by your app encrypted in transit? Not applicable if no user data is transmitted off device
- Do you provide a way for users to request that their data is deleted? No server-side data is collected; local data can be deleted by clearing app data or uninstalling
- Does the app share user data with third parties? No
- Does the app process data locally only? Yes

## When this draft must change

Update the privacy policy and Data Safety answers if the app uses any of these:

- Firebase Analytics, Crashlytics, Performance Monitoring, or Remote Config
- AdMob or any advertising SDK
- Sign in, user profiles, subscriptions, purchases, or cloud sync
- Internet APIs, backend services, or WebView content controlled by the app
- Location, contacts, camera, microphone, SMS, phone, health, photos, files, calendar, or installed-apps access
- Push notifications or messaging tokens
- Any SDK that transmits app, device, diagnostics, usage, advertising ID, or personal data off device

## Official Google references

- User Data policy: https://support.google.com/googleplay/android-developer/answer/10144311
- Data Safety form: https://support.google.com/googleplay/android-developer/answer/10787469

