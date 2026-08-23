# Sentinel — Privacy Policy

*Last updated: 23 August 2026*

Sentinel is a dashcam and surveillance camera app. It is designed so that **your recordings never leave your device unless you explicitly configure a destination you control**. The developer operates no server and receives no data from the app.

## Data the app processes

- **Video and audio recordings** — captured with the camera and (optionally) the microphone, stored only on your device or SD card. Old recordings are deleted automatically by the loop-recording storage manager.
- **Location** — used, if you enable the overlay, to burn the current speed and position into your recordings; processed on the device only.
- **Motion and sensor data** — accelerometer and in-frame motion are analysed on the device to detect impacts and events.

## What is never done

- No data is collected, transmitted to, or stored by the developer.
- No analytics, no advertising, no tracking SDKs.
- No account is required.

## Optional features that send data — only where you tell them to

- **Cloud offload** — if you configure it, clips/snapshots are uploaded to a destination you own (your NAS via SMB, a WebDAV server, or a folder of a cloud app you chose). The developer has no access to it.
- **Push notifications (ntfy)** — if you configure them, short event messages (e.g. "impact detected") are sent to the ntfy server and topic you set (public ntfy.sh or self-hosted). No video is sent.
- **Remote access** — if you enable it, the app runs a small server on your device so that *your own* devices can view recordings. Every request requires a secret token; nothing is exposed by the developer.

## Permissions

Camera and microphone are used solely to record your clips. Location feeds the optional speed/GPS overlay. Notifications inform you of recording state and events. Network access exists only for the optional features above.

## Data retention and deletion

All recordings are under your control: they live in the app's own folder on your device/SD card, are pruned automatically by the loop recorder, and are removed when you delete them or uninstall the app.

## Your responsibility

Depending on your country, recording video, audio, or people in public or in vehicles may be regulated. You are responsible for using Sentinel in compliance with the laws that apply to you.

## Children

Sentinel is not directed at children under 13.

## Changes

Any change to this policy will be published at this address with an updated date.

Contact: **albanm.apps@gmail.com**
