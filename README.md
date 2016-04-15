# Android_appium

Workflow:
  1. Install Java as a prerequisite
  2. Install Android and set paths
  3. Install other packages, node and script to create appium

# How to build/run ??

Build

First you have to build install_java image
then build install_android and finally android final

Run

docker run -d -e DEVICE_NAME=device1 -e TARGET=7 -e ABI=default/armeabi-v7a sopansagorkar/android_final
