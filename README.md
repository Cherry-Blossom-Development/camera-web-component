# camera-web-component

A self contained Web Component for video and photos

Having run into multiple issues with most of features listed below, I've developed this self contained, drop in web component. It is cross browser, cross device, cross framework compatible

* Noise reduction using RNNoise WASM
* Normalization to MP4 in all browsers, because Apple, using FFMPEG WASM
* Pause and resume video recording (hello all other recorders I could find that do not have this)
* Captioning (with recording audio at same time, if needed)

