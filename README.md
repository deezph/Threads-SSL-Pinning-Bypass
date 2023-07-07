Threads SSL Pinning Bypass
Bypass Threads SSL pinning on Android devices.
Supported ABIs: x86, x86_64, armeabi-v7a, arm64-v8a
Latest version: v289-0-0-77-109

Patched APK (No Root)
Download the latest patched APK:



You can use a tool like mitmproxy or Burp Suite to intercept the network.

Install patched APK in the device
Install mitmproxy or Burp Suite
Set up proxy for wifi settings or run: adb shell settings put global http_proxy <proxy>
Now you should be able to see the network traffic.
