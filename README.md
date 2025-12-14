# Floating Time Tracker

A privacy-focused, lightweight screen-time tracking solution for Android.

## Overview: 

Floating Time Tracker is a minimal and efficient Android application designed to provide accurate, real-time insight into how long your device is actively in use.

- All processing runs entirely **on-device**.
- Usage is measured only while the **screen is on** (locked or unlocked).
- Statistics are presented through a customisable floating overlay and detailed analytical views (tables and graphs).

This project is developed and maintained by HealthierTime, an independent app developer focused on transparent, privacy-respecting digital tools.

## Key Features
### Floating Overlay

- Real-time tracking via a movable floating bubble that shows today’s usage.
- Customisable size and appearance (scale slider, full opacity or softer background).
- Double-tap gesture on the bubble to return immediately to the main application.
- Optional text colour adapts based on theme and time-limit state.

### App Usage Analysis
- Daily app usage table with horizontal and vertical navigation.
- Vertical sorting by app, with totals per app.
- Predefined date ranges alignment for optimal visibility.
- Technical mode for displaying raw package identifiers.

### Interactive Usage Graph
- Visual representation of app-specific or total usage over time.
- Selectable ranges from 7 days to 6 months.
- Full gesture support: zooming, panning, and list resizing.
- Data points that exceed the configured daily time limit are highlighted in red.

### Time Limits and Warning Bubble
- Separate time-limit settings for Statistics views (table and graph) and the floating bubble.
- When a limit is exceeded: timers switch to a red highlight. An optional warning bubble can appear with contextual phrases.
- Warning bubble options:
  - Display duration (for example: 2, 4, 8, or 12 seconds).
  - Daily frequency cap (once, twice, or unlimited while over the limit).
  - Minimum interval between warnings.
  - Attitude: **Casual**, **Fun**, or **Serious**, each with its own phrase set.

### Data Export
- Export recent usage history as a CSV file for external analysis.
- Fully offline processing with no external transmission.
- Data includes:
  - App identifiers.
  - Day labels.
  - Per-day usage durations in `hh:mm:ss` format.

### Total Usage Overview
- Summarised app usage across the chosen analysis period.
- Automatically sorted by highest accumulated duration.

### Privacy and Security
- No data collection by remote servers and no external analytics SDKs.
- No sign-in, account creation, or network communication.
- All information stored locally on the device.
- Detailed history is automatically pruned based on your selected retention period (for example: 3 or 6 months); older entries are permanently deleted on-device.
- Complete data removal upon app uninstallation.

### Battery Efficiency
- Minimal resource consumption.
- Operates only while the device screen is active.
- Lightweight per-second processing.

## Technology Stack:
- Kotlin.
- Android Jetpack (Room, Activity APIs).
- Foreground Service (specialUse).
- UsageStatsManager.
- System overlay windows (TYPE_APPLICATION_OVERLAY).
- MPAndroidChart.

## Availability
Floating Time Tracker is currently accessible through Google Play testing.

To access the current test build:

- Join the Google Group: https://groups.google.com/g/floating-time-tracker
  The group page provides the official Google Play testing link for the app.
- After joining the group and accepting the testing programme, you can install Floating Time Tracker via the Google Play testing link.

Public availability will be announced upon final review.

## Documentation

Terms of Service
https://healthiertime-dev.github.io/floating-time-tracker/terms-of-service.html

Privacy Policy
https://healthiertime-dev.github.io/floating-time-tracker/privacy-policy.html

Open-Source Licences
https://healthiertime-dev.github.io/floating-time-tracker/open-source-licences.html

## Contributing

Issue reports and feature suggestions are welcome.
Pull requests may be reviewed selectively.

## Contact

For professional enquiries or feedback, please contact: healthiertime.developer@gmail.com

## About HealthierTime

HealthierTime is an independent app developer dedicated to developing privacy-focused, technically robust digital tools.
The project emphasises user autonomy, transparency, and efficient design.
