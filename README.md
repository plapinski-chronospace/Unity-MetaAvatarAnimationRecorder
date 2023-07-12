# Unity-MetaAvatarAnimationRecorder

![Meta Avatar Animation Recorder Gif 16x9](https://github.com/adammak23/Unity-MetaAvatarAnimationRecorder/assets/10499951/647bd812-2602-4ead-9519-55f6d62bec30)

## Setup

1. Firstly, you need to ensure that you have the Oculus Integration (51.0+) and Meta Avatars SDK (20.0+) dependencies installed. You can find the necessary packages on the Oculus Developer website (links provided in the "Dependencies" section).
2. Set up your project with the [Oculus Integration](https://developer.oculus.com/downloads/package/unity-integration) and [Meta Avatars SDK](https://developer.oculus.com/downloads/package/meta-avatars-sdk/).
3. Utilize the [Oculus Project Setup Tool](https://developer.oculus.com/documentation/unity/unity-quickstart-project_setup-tool/), available in Oculus > Tools > Project Setup Tool, for convenient project configuration.

![OculusProjectSetupTool](https://github.com/adammak23/Unity-MetaAvatarAnimationRecorder/assets/10499951/9c06d243-ae60-4afc-b960-907b7e532176)

## How To

1. Launch the AvatarRecorderScene.
2. Press the "Play" button to start the scene.
3. Toggle the recording feature on and off by pressing the "X" or "A" button.
4. Toggle the playback feature on and off by pressing the "Y" or "B" button.
5. Recorded data will be appended to the RecordedAvatarData scriptable object for future playback.

![AvatarRecorder](https://github.com/adammak23/Unity-MetaAvatarAnimationRecorder/assets/10499951/c6898965-7ae4-4a8e-867a-d4569cee587f)

## Settings

Adjust the following settings according to your preferences and project requirements:

**Record LOD**: Choose between Full/High/Medium/Low to select the animation resolution. Full records all three LODs.
**MAX_PACKETS_PER_FRAME**: Increasing this value enables more precise animation, although the default settings should be perfect for smooth playback.
**IntervalToSendData**: Increasing this value reduces the amount of stored information but may result in less fluid animation if motion smoothing is not enabled.
**PlaybackTimeDelay**: Increase this value to slow down the animation playback.

## Conclusion

By implementing our tool and following the provided instructions, you can overcome the freezing animation problem experienced with Meta Avatars in Unity. With the ability to record and play animations smoothly, you can enhance the realism and interactivity of your projects. We hope this tutorial has provided you with valuable insights and practical guidance for resolving this issue in your software development endeavors. Happy coding!


_This solution has been developed and tested on Unity version 2022.2.14, Oculus Integration 52 and 54.1, and Meta Avatars SDK 20.3. We recommend using these or newer versions for optimal compatibility and performance._
