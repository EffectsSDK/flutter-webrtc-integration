# Flutter EffectsSDK integration

Tested for **webRTC v0.14.0**

## Instructions

1. Clone [flutter WebRTC](https://github.com/flutter-webrtc/flutter-webrtc) repository
2. Download [patch](webRTC-patch.diff) from this repository and apply it
3. Download effects SDK release for your platform
4. Add Effects SDK as webRTC dependency (to **webRTC_repo_root/android/libs** catalog)
5. Add webRTC as dependency to your project

## EffectsSDK methods

Check platform specifications:
1. [iOS] (not implemented yet)
2. [android](https://github.com/EffectsSDK/android-integration-sample)


## Technical details

Effects SDK included by using custom  CameraVideoCapturer instance for Effects SDK camera pipeline(android).
You can modify our solution as you need or try another way for integration (for example with custom VideoProcessor).
Also you can replace CameraPipeline to lite version of it.

## Additional links

1. Platform documentation (iOS, [android](https://github.com/EffectsSDK/android-integration-sample))
2. Effects SDK [site](https://effectssdk.ai/)
