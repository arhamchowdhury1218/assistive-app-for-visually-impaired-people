

This is an example application for [TensorFlow Lite](https://tensorflow.org/lite)
on Android. It uses
[Image classification](+)
to continuously classify whatever it sees from the device's back camera.
Inference is performed using the TensorFlow Lite Java API. The demo app
classifies frames in real-time, displaying the top most probable
classifications. It allows the user to choose between a floating point or
[quantized](https://www.tensorflow.org/lite/performance/post_training_quantization)
model, select the thread count, and decide whether to run on CPU, GPU, or via
[NNAPI](https://developer.android.com/ndk/guides/neuralnetworks).

These instructions walk you through building and
running the demo on an Android device. For an explanation of the source, see
[TensorFlow Lite Android image classification example](https://www.tensorflow.org/lite/models/image_classification/android).

<!-- TODO(b/124116863): Add app screenshot. -->

### Model
MobileNetV1 and SSD 
Do not alter the assets folder
