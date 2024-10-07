
This is a direct fork of
https://github.com/Romick2005/react-native-live-audio-stream with one change:
the `data` event has been changed to `RNLiveAudioStream.data`. This is to avoid
conflicts with the
[react-native-tcp-socket](https://github.com/Rapsssito/react-native-tcp-socket)
library, which also has a `data` event.

## License 
MIT
