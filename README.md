# VL.Wekinator

[The Wekinator](http://www.wekinator.org/) is a standalone software that uses machine learning to solve the following problem: given input X, I want to get output Y. Where X can be any input that can be expressed as a series of floats and the output can either be:

- Discrete categories, like "Pose 1", "Pose 2", ...
- Continuous numeric outputs referring to positions between discrete outputs
- Recognition of gestures over time (like drawing a circle with your mouse)

Besides sending input data and receiving outputs data from The Wekinator, this plugin also allows you to easily control the software from your patch : you can trigger the recording of new examples, train your dataset and run with simple nodes.

## Installation

_soon_

## Documentation

Make sure you check the help browser! Besides the traditional introduction help patch, it contains three tutorials that teaches you how to :

- Control a small synthesizer
- Recognize hand poses with your webcam
- Recognize custom hand gestures with a Leap Motion

A few links to the Wekinator documentation are also listed there.

### Dependencies needed for the help patches

- [VL.Audio](https://github.com/vvvv/VL.audio)
- [VL.OpenCV](https://github.com/vvvv/VL.OpenCV)
- [VL.Elementa](https://github.com/vvvv-dottore/VL.Elementa)
- [VL.Devices.LeapOrion](https://github.com/vvvv/VL.Devices.LeapOrion)