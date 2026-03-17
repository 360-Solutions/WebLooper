# WebLooper v1.0

WebLooper is a lightweight, mobile-first audio workstation built entirely for web browsers. It is designed to let musicians practice rhythm and build quick loops on their smartphones without needing an external audio interface, wired headphones, or app store downloads.

## The Mobile-First Approach
Building a looper for a mobile browser presents a massive hurdle: preventing the device microphone from picking up the app's own backing tracks (audio bleed). 

WebLooper solves this using two methods:
1. The Conference Call Trick: The app briefly utilizes a specific audio pipeline during recording to manage microphone access without requiring heavy hardware.
2. The Spotlight Cycle: To keep timing tight and eliminate bleed, the backing track automatically mutes during your recording window. You keep time using an internal metronome, and the virtual band rejoins you perfectly on the next cycle.

## About the Project
This is a free, experimental tool created to solve a personal pain point during day-to-day musical practice. It is optimized for touchscreen interfaces and quick deployments.

Created by Jeremiah Keller (360 Solutions)
