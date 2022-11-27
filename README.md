# ProduceStickerDetector

Applying vision algorithms to identify objects in real-time video.

I trained a machine learning model using Core ML to train on a dataset I collected of 20 annotated images of produce sticker labels. I used roboflow.com to annotate the data.

With the [Vision](https://developer.apple.com/documentation/vision) framework, you can recognize objects in live capture.  Starting in iOS 12, macOS 10.14, and tvOS 12, Vision requests made with a Core ML model return results as  [`VNRecognizedObjectObservation`](https://developer.apple.com/documentation/vision/vnrecognizedobjectobservation) objects, which identify objects found in the captured scene.

This app uses a device camera for live capture and incorporates a Core ML model into vision that parses results as classified objects.
