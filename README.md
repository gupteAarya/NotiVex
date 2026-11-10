# NotiVex
<p align="start">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=androidstudio,kotlin,figma,firebase" />
  </a>
</p>
<img width="1024" height="500" alt="NotiVex - Your phone, your rules" src="https://github.com/user-attachments/assets/146af0e0-623f-486b-8c27-854263ebd883" />

<a href="https://play.google.com/store/apps/details?id=com.ag.notivex&hl=en_IN">
  <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" width="200">
</a>

**Your ultimate app for notification control & privacy.**

NotiVex silences notification chaos automatically. Mute your phone based on **WiFi networks**, **locations**, or **custom settings**, so your phone is quiet when it needs to be, in classrooms, meetings, at work, at home, or while travelling.

**Our goal: YOUR phone, YOUR rules.**

[Get it on Google Play](https://play.google.com/store/apps/details?id=com.ag.notivex&hl=en_IN) · Completely free to use.

## The Problem

You're in a quiet classroom, focused on studying, and your phone rings. Or you're in a critical office meeting and everyone turns to look because you forgot to silence it. On top of that come endless spam notifications: property, credit card, investment, and promotional apps.

Manually toggling silent mode is easy to forget, and constant interruptions fragment attention and break focus.


## The Solution

Instead of relying on memory, NotiVex ties silence to **context**. If you're connected to a trusted WiFi network or you're at a specific place, your phone mutes itself. No reminders, no manual steps.

<img width="1024" height="500" alt="notivex-banner" src="https://github.com/user-attachments/assets/1c85fe8d-9c53-445e-b6b1-48ce9c608d49" />


Silence should be automatic, predictable, and fully under your control.

## The Implementation

NotiVex is built for students, professionals, and busy commuters who need focus. It evaluates the following triggers:

* **WiFi networks**: silence on trusted/selected networks
* **Locations**: silence at places you choose
* **Time**: silence at the time you choose
* **Bluetooth**: silence when you connect to your bluetooth devices
* **Battery Level**: silence when your battery drops low.

When a trigger matches, NotiVex automatically applies silence/DND. When you leave, normal behavior is restored.


## Features

### Location-Based Muting

<table>
<tr>
<td width="65%">

Mute your phone at **specific places**: classroom, office, library, home. You choose the locations and radius, and you stay in control.


</td>
<td width="35%" align="center">
<img alt="Location Muting" src="https://github.com/user-attachments/assets/41e17184-34e3-4b58-859b-440a99487b4b">

<br>
<em>Location Muting</em>
</td>
</tr>
</table>

### Smart WiFi Triggers
Silence notifications **instantly** when connected to **trusted networks** such as your college, office, or home WiFi.


### Time Based Triggers

<table>
<tr>
<td width="65%">

Turn on **Do Not Disturb** whenever you want it

</td>
<td width="35%" align="center">
<img alt="DND Control" src="https://github.com/user-attachments/assets/a6d87665-5ca0-4e40-a06e-ccab68cb258e">
<br>
<em>DND Control</em>
</td>
</tr>
</table>

### Bluetooth Based Triggers
Connected to your car? NotiVex turns on Do Not Disturb so that you don't get distracted by your notifications.


### Privacy

<table>
<tr>
<td width="65%">

**Zero personal data is collected or shared.** Locations, WiFi networks, and settings stay on your phone.

</td>
<td width="35%" align="center">
<img alt="Privacy" src="https://github.com/user-attachments/assets/f5cb1ed5-e14b-4d1a-9b60-ab3db0367bcc">
<br>
<em>Privacy</em>
</td>
</tr>
</table>

## Technical Stack

### Mobile App
- Kotlin
- Jetpack Compose
- Android Studio
- Android SDK

### Services
- Location / Geofencing APIs

### Version Control
- GitHub

## Architecture

This app is not vibe-coded.

Source code is private. Public documentation focuses on functionality rather than implementation details.

## Privacy

NotiVex collects **no personal data**. Locations, WiFi networks, and settings are processed and stored **locally on the device**, and nothing is shared with third parties except the requests of the location text completion API.

[Read Privacy Policy](https://notivex.lovable.app/#privacy)

## Roadmap

NotiVex is under active development, with more improvements and features planned. Details will be shared as they become available.

## Technical Learnings

### Geofencing
### WiFi State Detection
### Notification Listener Service
### Do Not Disturb Policy Access
### Background Execution Limits
### Permission Handling
### Boot Receivers

## Status

**Currently Live On The Play Store**
