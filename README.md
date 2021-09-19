# speechnotes-speech-recognizer
The speech recognition engine behind Speechnotes.

[Speechnotes](https://speechnotes.co) is an online dictation nontepad, and the code operating its core speech to text functionality is run through this code in this repository. The npm package has the same name. 

What this engine does is basically wrap up the Webspeech-API with helper methods for easier integration into any website. 

Currently, the webspeech api is supported only on the following browsers:
- Chrome

It has limited support, as it has to run a speech recognition engine, which is provided for free on Chrome by Google. Not yet provided by other companies (as of 2021-09-17)

