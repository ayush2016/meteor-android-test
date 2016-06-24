#meteor-android-test

ANGULAR + METEOR

You can use this repo to check if on your Ubuntu (14.04) system, step "Running on an Android device" works fine.

a.Install Java JDK:

sudo add-apt-repository ppa:webupd8team/java

sudo apt-get update

sudo apt-get install oracle-java8-installer

b.Android SDK:

sudo add-apt-repository ppa:ubuntu-desktop/ubuntu-make

sudo apt update

sudo apt install ubuntu-make

umake android

c.Download 'SDK Platform' for android-23, Android SDK Platform-tools (latest), Android SDK Build-tools" (latest).

d.Set the ANDROID_HOME environment variable:

UBUNTU -> File Explorer -> Ctrl + H -> Edit .bashrc

export ANDROID_HOME=/home/username/Android/Sdk

export PATH=$PATH:/home/username/Android/Sdk/tools

export PATH=$PATH:/home/username/Android/Sdk/platform-tools

e.Enable USB debugging in your Android device.

Done!

