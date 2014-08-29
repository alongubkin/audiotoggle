## AudioToggle

Cordova plugin for switching between speaker and earpiece when playing audio.

    cordova plugin add https://github.com/alongubkin/audiotoggle.git
    
### Supported Platforms

- Android
- iOS

### Usage

To set the current audio mode, use the `setAudioMode` method:

    AudioToggle.setAudioMode(AudioToggle.SPEAKER);
    // or
    AudioToggle.setAudioMode(AudioToggle.EARPIECE);