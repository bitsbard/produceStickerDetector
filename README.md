# ProduceStickerDetector

Apply Vision algorithms to identify objects in real-time video.

I trained a machine learning model using Create ML to train on a dataset I collected of 20 images of produce sticker labels. I used roboflow.com to annotate the data.

With the [Vision](https://developer.apple.com/documentation/vision) framework, you can recognize objects in live capture.  Starting in iOS 12, macOS 10.14, and tvOS 12, Vision requests made with a Core ML model return results as  [`VNRecognizedObjectObservation`](https://developer.apple.com/documentation/vision/vnrecognizedobjectobservation) objects, which identify objects found in the captured scene.

This app shows you how to set up your camera for live capture and incorporate a Core ML model into Vision and parse results as classified objects.
