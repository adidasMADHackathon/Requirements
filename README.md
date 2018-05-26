# Requirements

- [Machine learning](#machine-learning)
  * [Must have](#must-have)
  * [We recommend you](#we-recommend-you)
  * [Nice to have](#nice-to-have)
    + [Install dependencies](#install-dependencies)
  * [Technical talk](#technical-talk)
- [VR](#vr)
  * [Must have VR](#must-have-vr)
  * [We recommend you](#we-recommend-you-vr)
- [AR](#ar)
  * [ARKit](#ARKit)
    + [Must have ARKit](#must-have-arkit)
  * [ARCore](#ARCore)
    + [Must have ARCore](#must-have-arcore)
    + [We recommend you](#we-recommend-you-arcore)
- [NFC](#nfc)
  * [Must have NFC](#must-have-nfc)
  * [We recommend you NFC](#we-recommend-you-nfc)
  
- [Data/Streaming](#streaming/data)
  * [Must have](#must-have-data)
  * [We recommend you](#we-recommend-you-data)

## Machine learning

You have all the pip requirements in the requirements.txt file.

You have the entire environment in environment.yml file.

If you want you can use one or another. It is located in the [seed project](https://github.com/adidasMADHackathon/seed-keras-models)

### Must have

- [python 3.x](https://www.python.org/downloads/)
- pip3

### We recommend you

- [virtualenvwrapper](http://virtualenvwrapper.readthedocs.io/en/latest/install.html) *If you are using windows powershell it might not work unless you run it with CMD*
- [anaconda](https://anaconda.org/anaconda/python)

** Use anaconda or virtualenvwrapper

** We recommend you to use anaconda, but feel free to use whatever you want

#### Install dependencies

It is up to you to install it or not, or even use another method or technology.

```bash
# with virtualenvwrapper
$ mkvirtualenv -p python3 bot # create virtual environment
$ workon bot # enter VE
(bot) $ pip install -r requirements.txt # install dependencies (make sure you are in the bot VE)
(bot) $ deactivate # exit VE

# with anaconda
$ conda env create -f environment.yml # create virtual environment
$ conda activate bot # enter VE
(bot) $ conda deactivate # exit VE
```

** In the workshop you will be learning to work with Keras (running on top of TensorFlow, CNTK, or Theano). You need TensorFlow to run as backend or CNTK, or Theano.

** Since the 1.7 version of Tensorflow includes Keras, we recommend you to install it

### Nice to have

- [tensorflow 1.7](https://www.tensorflow.org/install/)	
- [cuda 8](https://developer.nvidia.com/cuda-80-ga2-download-archive) *Only if your computer can manage it*
- [cudnn](https://developer.nvidia.com/cudnn) *Only if you managed to install cuda on your system*

### Technical talk

- [ ] Part 1 - Being smarter than AI
- [ ] Part 2 - Train your models in the cloud (AWS)

* The entire talk will be 30 min to 1h

## VR

### Must have VR
- Own laptop
- Compatible device 
### We recommend you <a name="we-recommend-you-vr"></a>
- Bring your own compatible device.
- [Unity 5.6](https://unity3d.com/es/get-unity/download) and make sure that the Android Build Support component is selected during installation.
- [Google VR SDK for Unity](https://github.com/googlevr/gvr-unity-sdk/releases)
- [Android SDK](https://docs.unity3d.com/Manual/android-sdksetup.html)

You can go to the next links in order to get some free 3d models:
- https://www.cgtrader.com/free-3d-models
- https://free3d.com/
- https://www.turbosquid.com/Search/3D-Models/free

## AR

### ARKit

#### Must have ARKit
- iPhone 6s or higher, we provide x2 iPhone.
- [Xcode 9.0](https://developer.apple.com/xcode/)
- iOS 11.0 or higher

### ARCore
#### Must have ARCore
- [A supported Android device](https://developers.google.com/ar/discover/#supported_devices), we provide x3 Android
#### We recommend you <a name="we-recommend-you-arcore"></a>
- [Android SDK version 7.0 (API Level 24) or higher](https://docs.unity3d.com/Manual/android-sdksetup.html)
- [Unity 2017.3.0f2 or higher](https://unity3d.com/es/get-unity/download) with the Android Build Support component
- [ARCore SDK for Unity](https://github.com/google-ar/arcore-unity-sdk/releases/download/v1.1.0/arcore-unity-sdk-v1.1.0.unitypackage)


## NFC

We will provide you as much NFC tags as you need. We recommend you to build an Android or iOS app in order to use this tags.

Technical features:
  - Tag type: NXP MIFARE Ultralight - NTAG213
  - Memory: 180 bytes in 45 pages (4 bytes each)
  - Avaliable memory for user: 137 Bytes
  - More info: https://www.nxp.com/docs/en/data-sheet/NTAG213_215_216.pdf

### Must have NFC

- NFC tags (provided)

### We recommend you NFC
- Own laptop
- Compatible device (Android or iOS smartphone)
- [Android SDK](https://www.python.org/downloads/)
- [Android Studio](https://developer.android.com/studio/?hl=es)

or

- [iOS](https://developer.apple.com/ios/)


## Streaming/Data

Rather than giving you a training on concrete technologies, we are going to provide you a list of posible solutions and you are free to use them or simply ignore them.

### Must have Data

Nothing, or well, at least a computer of your own!

### We recommend you Data

- Docker
- Docker compose v3
- Java v1.8 (or higher)
- Maven v3 (but then also use Gradle, its better, way better and simpler)
- Node JS v8
- NPM

### Technical talk Data

- [ ] Part 1 - About Data and Streaming
- [ ] Part 2 - Quick tips

* The entire talk will be around 30 min
