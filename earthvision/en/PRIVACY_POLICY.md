---
title: EarthVision — Privacy Policy
permalink: /earthvision/en/PRIVACY_POLICY.html
---

[Français](../PRIVACY_POLICY.html) · **English** · [Español](../es/PRIVACY_POLICY.html)

# Privacy Policy — EarthVision

_Last updated: October 1, 2026_

This policy explains how the **EarthVision** app ("the App", "we") collects, uses and protects information when you use it on Android or iOS.

EarthVision shows **public live webcams** owned by third parties (YouTube channels, transport agencies, tourist boards…) on a globe. We do not film, record or rebroadcast anything: the App displays the stream provided by each camera's owner.

---

## 1. Publisher

The App is published by **EarthVision**, reachable at **simondouz81150@gmail.com**.

## 2. Data we process

EarthVision is designed to collect as little as possible. This is the complete list.

### 2.1 Anonymous ID
- **What:** a random technical identifier created on first launch (anonymous sign-in). No name, email or phone number.
- **Why:** to link your favorites to your device and sync them.
- **Where:** Supabase (hosted in the European Union, Ireland).
- **How long:** until you delete your data (see section 6).

### 2.2 Favorites
- **What:** the list of cameras you added to your favorites.
- **Why:** to show them to you, and to compute the anonymous "People's favorites" ranking (number of favorites per camera, never who saved what).
- **Where:** on your device and with Supabase.

### 2.3 Ratings and reports
- **Ratings:** if you rate the app inside the App, the rating (1 to 5 stars) is stored with your anonymous ID to help us improve it.
- **Reports:** if you report a camera, we store the camera's ID and the date.

### 2.4 Location
- **When:** **only** when you ask for it ("Locate me", the "Near here" tab, ISS pass alerts) and grant the permission. Never in the background without your consent, never continuous tracking.
- **Why:** to center the globe on you, sort cameras by distance and, if you turn on ISS pass or aurora alerts (EarthVision+), work out what will be visible above you.
- **Where:** **only on your device.** For alerts, a position **rounded to about 10 km** is kept there and refreshed when you open the App. **It is never sent to our servers.**

### 2.5 Notifications and alerts
- **Discovery notifications:** at most **two per week** (a sunset, a place to discover).
- **EarthVision+ alerts (if you turn them on):** sunset on one of your favorites (at most one per day), visible ISS passes, aurora nights.
- **100% local:** scheduled by the App on your device, with no server. For auroras, the App checks NOAA's public Kp index forecast about once an hour (see section 3): no data about you is sent, apart from the IP address inherent to any connection.
- **Turning them off:** in the App (Profile, Favorites) or in your phone settings.

### 2.6 Home screen widget
- The widget shows the latest image from the camera you choose. Your choice and the image are kept **on your device**; the image is downloaded directly from the camera's provider.

### 2.7 Preferences
- Language, camera types shown, alert settings: kept **on your device** only.

### 2.8 EarthVision+ subscription
- Payment is handled by **Google Play** or the **App Store**: we never receive your payment details, name or email.
- Your subscription status is managed by **RevenueCat**, which receives the purchase receipt (product, date, renewal) from the store, linked to an anonymous user ID created by the App.

### 2.9 What we do NOT collect
Name, email, address, date of birth, contacts, photos, browsing history, advertising ID. **No ad tracking.** No usage analytics or crash reports at this time.

## 3. Third-party services

| Service | Role | Data involved |
|---|---|---|
| **Supabase** (Supabase Inc., servers in Ireland) | Database, anonymous sign-in, camera list | Anonymous ID, favorites, ratings, reports, IP address (technical logs) |
| **RevenueCat** (RevenueCat Inc., United States) | EarthVision+ subscription management | Anonymous purchase ID, purchase receipts sent by the store, IP address ([RevenueCat policy](https://www.revenuecat.com/privacy)) |
| **Mapbox** (Mapbox Inc., United States) | Map and globe | IP address, technical data and anonymous SDK telemetry ([Mapbox policy](https://www.mapbox.com/legal/privacy)) |
| **YouTube** (Google) | Playing YouTube live streams | Data collected by the YouTube player when you watch a video ([Google privacy policy](https://policies.google.com/privacy)) |
| **Windy** and other **camera providers** (TfL, Fintraffic, departments of transportation…) | Sending images and video | IP address, as for any web page you visit |
| **MET Norway** (Norwegian Meteorological Institute) | Weather shown on a camera's page | Coordinates **of the camera** (not yours), IP address |
| **Wikipedia** (Wikimedia Foundation) | "About this place" card | Coordinates **of the camera**, IP address |
| **NOAA** (US agency, space weather forecasts) | Aurora forecast | IP address only |
| **Google Play / App Store** | Downloads, ratings, purchases | According to their own policies |

Some data may be processed outside the European Union (RevenueCat, Mapbox, Google) under appropriate safeguards (EU-US Data Privacy Framework or standard contractual clauses).

## 4. Legal basis

- **Performance of the service:** anonymous ID, favorites, subscription, location on request.
- **Legitimate interest:** ratings, reports, technical logs (security, improving the app).
- **Consent:** location and notifications (system permissions, which you can withdraw at any time).

## 5. Background task

For aurora alerts and the widget, the App runs a short background task about once an hour (scheduled by Android, only with an Internet connection): it checks NOAA's forecast and reloads the widget's image. It sends no personal data.

## 6. Your rights (GDPR / CCPA)

You can access, correct or delete your data, object to its processing or ask for its portability.

- **Instant deletion:** in the App, **Profile → Delete my data**. Your anonymous ID, favorites and ratings are erased from our servers and from your device.
- **By email:** **simondouz81150@gmail.com**. Answer within **30 days at most**. See also the [data deletion page](./DATA_DELETION.html).
- You can lodge a complaint with your data protection authority (in France, the **CNIL**, cnil.fr).

## 7. Retention

- Anonymous ID, favorites, ratings: until you delete your data.
- Reports: kept without any link to you after you delete your data.
- Subscription data at RevenueCat: as long as needed to manage the subscription and meet legal obligations.
- Data on the device (preferences, rounded position, widget): erased when you uninstall the App.
- Technical logs: a few days, according to each host's policy.

## 8. Security

All communication with our servers is encrypted (**HTTPS / TLS**). Database access is protected by row-level security rules: each user can only read and change their own favorites.

## 9. Children

Webcams show public places live, without prior moderation. The App is intended for users **13 and over**. We do not knowingly collect data from children under 13.

## 10. People on camera

Cameras film public places and belong to their operators. If you believe a camera invades your privacy, use "Report a problem" in the player or email us: we remove it from the App within **7 days**.

## 11. Changes

This policy may change (for example when ads are introduced). The date at the top shows the latest version; major changes will be announced in the App.

## 12. Governing law and contact

This policy is governed by **French** law. For any question: **simondouz81150@gmail.com**.
