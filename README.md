# CraneManipulation3D

CraneManipulation3D is a simple virtual training implementation which includes five stage of equipment operation. You can find the original description of the task in [Annotation vs. Virtual Tutor: Comparative Analysis on the Effectiveness of Visual Instructions in Immersive Virtual Reality](https://www.researchgate.net/publication/336592427_Annotation_vs_Virtual_Tutor_Comparative_Analysis_on_the_Effectiveness_of_Visual_Instructions_in_Immersive_Virtual_Reality) appeared at [ISMAR 2019](https://www.ismar19.org/). This implementation is an open source version which does not include the 'virtual crane' and reimplemented with [Tasc-Unity](https://github.com/JinkiJung/Tasc-Unity).

## Development environment
* Unity 2018 2.0f2
* Windows 10
* Mac OSX 10.14.6

## Platform support
* SteamVR (HTC Vive, Oculus)
* Desktop

## Dependency
- [Tasc-Unity 0.1.0](https://github.com/JinkiJung/Tasc-Unity)
- [Unity Windows Text-To-Speech](https://github.com/VirtualityForSafety/UnityWindowsTTS)
- SteamVR Plugin 2.3.2 (sdk 1.4.18)
- Unity Standard Assets 1.1.5

## How to use it
1. Download or pull this repository.
2. Download and import [Unity Standard Assets](https://assetstore.unity.com/packages/essentials/asset-packs/standard-assets-32351) from AssetStore
3. Download and import [SteamVR Plugin](https://assetstore.unity.com/packages/tools/integration/steamvr-plugin-32647)
4. When you are required to set SteamVRInput up, choose 'GrabGrip' from Actions and press 'Save and Generate'.
5. Hit the run button.

## Acknowledgement
This project has been implemented through a [research collaboration](https://virtualityforsafety.github.io/about/) with KAIST (Hyeopwoo Lee), Xi’an Jiaotong-Liverpool University (Prof. Hai-Ning Liang,
Diego Vilela Monteiro), and Handong Global University (Prof. Daseong Han, Betty Hyejin Kim, Youngnoh Goh).

## Maintainer
- [Jinki Jung](https://jinkijung.github.io/)

## License
 - MIT license

## Future implementation plan
 - Tutor implementation
 - Logging
 
