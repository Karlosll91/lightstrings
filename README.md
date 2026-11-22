# Lightstrings

A hand-tracked instrument for the browser. Stretch threads of light between your fingertips, pin them as strings, and play the air.

- **Stretch:** raise both hands. Faint threads join your fingertips.
- **Pull taut:** pinch thumb and index on both hands. The length sets the pitch. Release to pin the string.
- **Pluck:** swipe a fingertip across a string.
- **Flick:** flick fast along a string to send sparks down it.
- **Clear:** make a fist and hold it.

**Theremin mode** (switch at the top): your right index finger plays pitch, and moving it closer to the glowing antenna raises the note. Raising your left hand turns the volume up, and pinching it cuts the sound. Pitch can glide freely or snap toward the current scale.

There's also touch and mouse mode for when no camera is available.

Built with [MediaPipe Hand Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) for tracking, Canvas 2D for the visuals, and Web Audio (Karplus-Strong plucked-string synthesis) for the sound. Everything runs on your device. No video is uploaded.
