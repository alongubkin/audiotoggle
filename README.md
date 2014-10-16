## AudioToggle

Cordova plugin for switching between speaker and earpiece when playing audio.

    cordova plugin add com.dooble.audiotoggle
    
### Supported Platforms

- Android
- iOS

### Usage

To set the current audio mode, use the `setAudioMode` method:

    AudioToggle.setAudioMode(AudioToggle.SPEAKER);
    // or
    AudioToggle.setAudioMode(AudioToggle.EARPIECE);

Android has the following additional options:

    AudioToggle.setAudioMode(AudioToggle.NORMAL);
    // and
    AudioToggle.setAudioMode(AudioToggle.RINGTONE);