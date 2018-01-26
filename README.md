# CryptoFlow VR

CryptoFlow VR is a virtual reality cryptocurrency market data analysis sandbox and trading environment built specifically for room-scale VR. Whether you’re a professional trader running a complex set of algorithmic trading strategies, or a day trader looking for the ultimate edge, CryptoFlow gives you a diverse toolset to implement your strategies.

## Requirements
* An HTC Vive or Oculus Touch running SteamVR
* Unity 5.5.5f1 if you'd like to modify the project

## Setup
The Unity project can run without any additional components - just open the cryptoflow scene to get started. 

That being said, the project is missing two third-party components available in the Unity Asset Store:

* [SE Natural Bloom & Dirty Lens](http://u3d.as/7v5) creates the glow and bloom effects seen in the released software
* [Runtime AudioClip Loader](http://u3d.as/hEP) enables MP3 sample loading and improves the performance of all sample loading

To use each of these assets, add the full asset package to the *third_party* folder. If they are not automatically replaced, remove the corresponding placeholder scripts in that same folder.

## Acknowledgement:
This project began as a fork of SoundStage VR, from which the interaction system and look / feel were derived.