Nader Chaser Weather Alerts — Privacy Policy
Effective date: 2025-08-18

This Privacy Policy explains what information the Nader Chaser Weather Alerts browser extension (the “Extension,” “we,” “our”) collects, how it is used, and your choices. This policy applies to the Extension’s pop-up, Options page, and the Live Weather Coverage page included with the Extension. It does not apply to third‑party sites or services you open from the Extension.

Summary at a glance
We do not sell or rent your data.
We do not run analytics or tracking.
Your settings and alert notification history are stored locally in your browser.
Location is optional. If you enable GPS, the browser asks for permission and coordinates are stored locally.
Weather data is fetched over HTTPS from the National Weather Service (NWS).
Notifications are created locally; we track alerted IDs to avoid duplicates and remove them when alerts expire.
Information we collect and store
The Extension does not create user accounts and does not ask for your name, email, or payment information. It stores only what is necessary to function, using the browser’s local extension storage (chrome.storage.local):

Settings (key: "userSettings")

locationMode: "manual" or "gps"
latitude and longitude: only if you provide them or opt into GPS
notificationsEnabled and soundEnabled
intervalMinutes: how often to check for alerts
filters: your selections for message types, severity, urgency, certainty, and alert type codes (NWS 3-letter codes)
Notified alerts (key: "notifiedAlerts")

A map of NWS alert IDs that have already triggered a notification, each with an expiry timestamp. This prevents repeated notifications for the same alert and is automatically pruned as alerts expire.
System/runtime information

The browser may log standard extension/runtime events locally (e.g., an alarm waking the service worker). We do not collect analytics and do not transmit telemetry to any server.
Location data (optional)

If you enable GPS mode, the browser may prompt for location permission. When granted, your coordinates are saved locally as part of your settings. You can switch to manual entry or reset settings at any time.
How we use the information
Provide weather alerts and related features based on your location and filters by querying the NWS API.
Show a badge on the extension icon with the count of currently active alerts (after applying your filters).
Display desktop notifications for new alerts when enabled, while tracking alert IDs to avoid duplicate notifications until the alert expires.
Persist your preferences (e.g., filters, polling interval, coordinates) so the Extension behaves as you configured it.
Storage and retention
Storage location: Data listed above is stored only in your browser via chrome.storage.local.
Retention:
Settings persist until changed or reset by you.
Notified alert IDs are removed automatically when alerts expire and are cleared on install, on browser startup, and when you change settings.
We do not operate a backend service and do not keep server-side copies of your data.
What we do not do
We do not sell, rent, or trade personal information.
We do not include ad networks, analytics trackers, or third-party SDKs that collect your data.
We do not process payments inside the Extension. The donation link opens an external payment page (Square) that is separate from us and governed by Square’s policies.
Third-party services and links
National Weather Service (NWS) API (https://api.weather.gov): We request public weather data (e.g., points, alerts, forecasts) over HTTPS. Requests may include your coordinates if required to look up alerts for your area. We do not add identifying information.
YouTube: The Live Weather Coverage page embeds a YouTube video in an iframe. YouTube may collect viewer/device information under its own policies. You can avoid this page if you prefer.
NWS and forecast links: The popup can open your NWS office page (weather.gov/{cwa}) and point forecast pages (forecast.weather.gov). These sites are governed by their own policies.
Square donation link: The “BUY THE DEVELOPER A DRINK” link opens Square (https://square.link/…), where any payment information is handled by Square, not this Extension.
Permissions we request and why
storage: Save your settings and the list of alert IDs already notified.
geolocation: Optional; used only if you select GPS mode to get alerts for your current position. You can use manual coordinates instead.
alarms: Schedule periodic background checks for new/updated alerts.
notifications: Show desktop notifications for new alerts when enabled.
host_permissions (https://api.weather.gov/*): Fetch public weather data for your chosen area.
Content Security Policy: Allows iframes from YouTube on the Live page. No content scripts inject into third-party sites.
Your choices and controls
Location: Choose manual coordinates or enable GPS; switch back anytime.
Notifications: Turn on/off desktop notifications in Options; you can also control notifications at the browser/OS level.
Filters: Select which alert types, severities, urgencies, and certainties you want to see and be notified about.
Reset: Use “Reset to Defaults” in Options to clear and restore default settings. The Extension also clears notified alert tracking on install, on startup, and when settings change.
Security
All network requests use HTTPS.
The Extension validates response shapes defensively and stores only the minimal data needed.
Data remains in your browser’s local extension storage unless you choose to share it (the Extension does not provide export/sharing by default).
Children’s privacy
The Extension is a general-audience utility and does not target children. We do not knowingly collect personal information from children. If you have concerns about saved location settings, you can switch to manual mode and reset settings in the Options page.

International users
The NWS API is U.S.-focused. The Extension does not transmit your personal data to our servers. If you enable GPS, your browser may process/store location data locally in line with this policy and your browser/OS privacy controls.

Changes to this policy
We may update this policy as the Extension evolves (for example, if we later add an optional alert sound via an offscreen document). We will update the “Effective date” and, where required, provide additional notice in the store listing or within the Extension.

Contact
If you have questions or requests related to this policy, please contact the developer:

Email: replace-with-your-contact@example.com
Project: Nader Chaser Weather Alerts
If you publish this policy on a website or store listing, replace the email above with your actual contact address so users (and NWS, per API etiquette) can reach you.
