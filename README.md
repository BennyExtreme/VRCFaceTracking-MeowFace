# MeowFace Tracking Module

> Let VRCFaceTracking take advantage of **MeowFace**'s tracking directly from your Android device.

## Installing **MeowFace Tracking Module** for **VRCFaceTracking**.

Download the latest `MeowFaceExtTrackingInterface.dll` file from the [GitHub Actions](https://github.com/BennyExtreme/VRCFaceTracking-MeowFace/actions/) page and place it in: `%APPDATA%/VRCFaceTracking/CustomLibs`
  
**VRCFaceTracking is required to use MeowFace Tracking Module.**
  
## Using MeowFace with VRCFaceTracking

1. Download **MeowFace** from [itch.io](https://suvidriel.itch.io/meowface)
3. Launch the app, then enter the IP address of the PC running VRCFaceTracking along with the port number (default: 12345). You can find these details in the console.

## Troubleshooting

> MeowFace is not connecting to VRCFaceTracking.

Make sure that you have **MeowFace**'s *IP* and *port* configured as specified by **VRCFaceTracking** and that you are connected to the same network as the host. Optionally you can send the data to the port to your global IP from any MeowFace connection by port forwarding the specified port.

> MeowFace is not tracking as expected.

MeowFace is not all too perfect at tracking your face... however: some of the tracking may not track as expected when converted for use into VRCFaceTracking's parameter system. Feel free to make an issue if MeowFace doesn't track as expected!
  
## Licenses / Distribution

**All source and release files fall under the [Apache-2.0 License](https://github.com/BennyExtreme/VRCFaceTracking-Modules/blob/master/LICENSE.txt)**.

## Credits
- [Ben](https://github.com/benaclejames/) for VRCFaceTracking!
