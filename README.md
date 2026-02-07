# Camera_Prep
Big picture – what is this app doing?

This app:

Shows camera preview on the screen

Uses NDK (native C/C++) to:

Start/stop camera

Capture photo

Record video

Kotlin side is only controlling UI + permissions + Surface

Actual camera work happens in native code

📌 Kotlin = controller
📌 Native (C/C++) = camera engine
