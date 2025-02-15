# Expo Camera Preview Issue on Android

This repository demonstrates a bug where the Expo Camera preview displays incorrectly on certain Android devices. The preview may appear distorted or completely black.  This issue does not reproduce on iOS devices.

## Problem

The problem lies in how the Expo Camera API interacts with specific Android device configurations or camera hardware. While the exact root cause is unclear, the bug is characterized by an inconsistent camera preview, often resulting in a visual distortion or a black screen.

## Solution

The solution involves using specific camera options within the Expo Camera API to mitigate the issue.  These options might involve using a specific camera type, setting aspect ratios, or adjusting other parameters to force compatibility across different devices.

## Reproduction Steps

1. Clone this repository.
2. Run `npm install`.
3. Run the app on an Android device (the bug is not consistent across all devices; you might need to try multiple devices).
4. Observe the Camera preview.  Distortion or a black screen indicate the presence of the bug. 

## Additional Notes

This bug might be related to specific Android versions, device manufacturers, or underlying camera drivers. More investigation is needed to fully identify the exact cause.