# Android SPL Meter #
This is a simple sound pressure level meter. It grabs 20ms frames of audio and calculates the RMS. It converts this to dB SPL and displays it both as a number and as a colored level bar.

<p align='center'>
<img src='http://android-spl-meter.googlecode.com/files/android-spl-level-meter-small.png' align='center' width='200' />
</p>

It is useful for determining the absolute gain of the audio subsystem which may vary from phone to phone.

This project might be useful as a template for real-time audio processing on Android.

This project includes:
  * A main screen that shows a real time **audio level visualization**.
  * A module that encapsulates the audio and provides real-time audio input.
  * A settings tab for changing parameters.
  * A UI component in the form of a LED VU bar.
  * Persistence (i.e. storing and retrieving) parameters between sessions.

Enjoy!
