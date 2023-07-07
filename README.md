# Threads SSL Pinning Bypass

Bypass Threads SSL pinning on Android devices.  
Supported ABIs: `x86`, `x86_64`, `armeabi-v7a`, `arm64-v8a`  
Latest version: `289.0.0.77.109`

## Patched APK (No Root)

Download the latest patched APK: 
+ [Threads.289.0.0.77.109.x86.apk](https://github.com/deezph/Threads-SSL-Pinning-Bypass/releases/download/v289.0.0.77.109/Threads.289.0.0.77.109.x86.apk)

## Intercept network traffic

You can use a tool like mitmproxy or Burp Suite to intercept the network.

1. Install patched APK in the device
2. Install [mitmproxy](https://mitmproxy.org/) or [Burp Suite](https://portswigger.net/burp)
3. Set up proxy for wifi settings or run: `adb shell settings put global http_proxy <proxy>`

Now you should be able to see the network traffic.
