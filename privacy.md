---
title: TaskPilot Privacy Policy
permalink: /privacy/
---

# TaskPilot Privacy Policy

**Effective date:** November 7, 2026
**Developer:** Prashanth555 ("we", "us")
**Contact:** samch2347@gmail.com

TaskPilot is a task list and day planner. We built it to collect as little as possible. There are no accounts,
no ads, no analytics SDKs and no tracking.

## What stays on your device

- **Your tasks** (titles, notes, due dates, priorities) are stored only on your device, in the app's local database.
- **Voice recordings** are never saved. Audio is turned into text while you record. When your device supports it,
  this happens entirely on the device. Otherwise Apple's speech recognition service processes the audio under
  [Apple's privacy policy](https://www.apple.com/legal/privacy/). We never receive audio.
- **Settings** (sync, notification and sound preferences, your daily free-request count) are stored on your device.
- **Reminders and notifications** (task alerts and the morning summary) are scheduled by iOS on your device. Task
  titles and due times are used only to build these local notifications. Nothing is sent to us or to any push
  service, and no AI requests are made for them.

## What is sent to our server, and why

AI features only send data when you use them:

| Feature | What's sent | Why |
|---|---|---|
| **Find Tasks** | The text of your note, plus the current date and time zone | To extract tasks and resolve dates such as "tomorrow" |
| **Chat** | Your recent chat messages; titles, due dates, priorities and estimates of relevant open tasks (never notes); titles and times of today's calendar events, if you turned on "Use Calendar When Planning" | To suggest a plan |
| **Every AI request** | A random identifier created when you install the app (not linked to your identity), your IP address (seen by any server), and, if you subscribe, a signed proof of your subscription from Apple | To enforce fair-use daily limits and recognize subscribers |

This data goes to our server (hosted on Cloudflare Workers) and is forwarded to **Anthropic**, the provider of the
Claude AI models, to generate the response. **We do not store the content of your requests.** Our server logs only
technical metadata (time, which feature, success or failure, and a shortened one-way hash of the install
identifier), which we keep for up to 30 days to operate and secure the service. Anthropic processes API data
under its own terms and privacy policy (<https://www.anthropic.com/legal/privacy>) and, per its commercial terms,
does not train its models on API inputs.

Daily-limit counters (install identifier and IP address, with a count per day) are kept for up to 2 days.

## Calendar and Reminders

If you turn on Calendar or Reminders sync, TaskPilot reads and writes events and reminders **on your device** through
Apple's EventKit framework. It creates events for tasks with a due time, and a "TaskPilot" Reminders list. If "Use
Calendar When Planning" is on, the titles and times of today's events are included in Chat requests as described
above. Nothing else from your calendars is sent anywhere. You can turn these off at any time in TaskPilot's settings
or in iOS Settings.

## Purchases

Subscriptions are processed by Apple. We never see your payment details. The app receives a signed record of your
subscription from Apple and sends it to our server only to apply the subscriber limit.

## What we don't do

- No accounts, no names, email addresses or contacts.
- No advertising, no data sale, no sharing with data brokers.
- No tracking across apps or websites, and no third-party analytics or crash-reporting SDKs.

## Children

TaskPilot is not directed at children under 13 (or the minimum age in your country), and we don't knowingly collect
their information.

## Your choices and rights

- Use TaskPilot without the AI features; recording, editing, reminders and sync work without sending anything to us.
- Turn reminders off at any time in TaskPilot's settings or in iOS Settings → Notifications.
- Delete the app to remove all locally stored data. Calendar events and reminders it created remain in those apps
  until you delete them.
- Because we don't store request content and can't link the install identifier to you, there is usually no personal
  data for us to access or delete. Contact us at samch2347@gmail.com with any request; we'll respond within the
  time required by applicable law (for example GDPR or CCPA).

## Changes

If this policy changes, we'll update the effective date above and, for material changes, notify you in the app.

## Contact

Prashanth555
samch2347@gmail.com
