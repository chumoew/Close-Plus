<div>

[**中文**](README.md)

</div>

# Close

**Close** is an Android ad blocking tool based on the Xposed framework, dedicated to providing an ad-free app browsing experience, aiming to optimize user experience and reduce interference. Please use it in the LSPosed framework environment.

The core function of Adlose is to prevent the initial loading of the ad SDK in the application and intercept the application ad request to block the ad.

## Main features

Function support (sequence):

- **Precise processing**: Block the initialization of the in-app ad SDK.

- **Ad request interception**: Intercept and block the network ad request of the application.

- **Sensor monitoring removal**: Used to disable sensor-based ad jumps such as shake.

- **Non-root use**: Can be used through LSPatch, NPatch and other non-root Xposed framework applications based on the LSPosed core.

 ## Supported Application Range

Close supports many popular Android applications, including but not limited to:

- Video playback applications
- Reading and news applications
- Business and office applications
- Social and communication applications

## Ad SDK processing

Close can handle multiple SDK types in applications, including the following:

- ADSuyiSdk Ads
- AdScope
- Ali BaiChuan Ads
- Applovin Sdk
- Appic Ads
- Baidu Ads
- BJXingu Ads
- ByteDance (Pangolin) Ads
- ByteDance (Pangolin) GroMore
- FaceBook Ads
- Google Ads
- Google FireBase Crashlytics Sdk
- Huawei Ads
- Inmobi Ads
- Kwai Ads
- MeiShu Ads
- Mintegral Ads
- Mbridge Ads
- Pinduoduo Ads
- Qumeng Ads
- Sigmob Ads
- Tanx Ads
- Tencent Ads
- Tencent SDK
-  TopOn SDK (anythink)
- TradPlus Ads
- Umeng SDK
- Unity3d Ads
- Vungle Sdk
- XiaoChuang Ads (ZuiYou)
- XinwuPaijin Ads
- Xiaomi Ads
- Pangolin advertisement

## User Guide

Before installing Close, please make sure that your device has installed the non-root Xposed framework application based on the LSPosed core.

1. Download and install the Close module, or use the root Xposed framework application built-in.

2. Activate the Close module in the non-root Xposed module manager.

3. Select the application you want to remove ads in the module scope.

4. Start the AdClose module, select and click the application list, and enable the corresponding Hook function.

## How to contribute

If you have suggestions for improvement of Close, or find a bug, please report it through Issues.

## Support us

If Close is helpful to you, please give us Star support! This is the biggest motivation for our continuous improvement.
