---
description: >-
  We need to install Android Studio to develop Android app with react-native.
  Click the link below to go to Android Studio site and download the
  installation file.
---

# Setup Android Studio

Android Studio: [https://developer.android.com/studio](https://developer.android.com/studio)

After downloading, execute the installation file to install Android Studio.

#### Android Studio Configuration <a href="#android-studio-configuration" id="android-studio-configuration"></a>

you can see the screen like below after executing Android Studio installation file.

![Click Next button to go to next screen. When you go to next screen, you can see Choose Components screen like below. Select Android Virtual Device and click Next button to go to next screen.](../.gitbook/assets/stud.jpg)

![When you go to next screen, you can see Android Studio Install Path screen like below. set Install Path or keep default, click Next button to go to next screen.](../.gitbook/assets/comp.jpg)

![When you go to next screen, you can see Start Menu setting screen like below. Just click Install button to install.](../.gitbook/assets/set.jpg)

![After installing, you can see the screen like below. Click Next button to complete Android Studio installation .](../.gitbook/assets/folder.jpg)

After installing, you can see the screen like below. Click Next button to complete Android Studio installation.

![When you click Next button to complete the installation, you can see the screen like below. Check Start Android Studio and click Finish button to finish Android Studio installation.](../.gitbook/assets/success.jpg)

When you click Next button to complete the installation, you can see the screen like below. Check Start Android Studio and click Finish button to finish Android Studio installation.

![When you click Finish button, you can see Android Studio is executed like below. Select Do not import settings, and click OK button to execute Android Studio.](../.gitbook/assets/fin.jpg)

When you click Finish button, you can see Android Studio is executed like below. Select Do not import settings, and click OK button to execute Android Studio.

![When you click OK button to execute Android Studio, you can see Android Studio Setup Wizard like below. Click Next button to go to next screen.](<../.gitbook/assets/dont im.jpg>)

![When you go to next screen, you can see Install Type screen like below. Select Custom and click Next button to go to next screen.](../.gitbook/assets/wizard.jpg)

![When you go to next screen, you can see Select UI Theme screen like below. Select the theme which you like, and click Next button to go to the next screen.](../.gitbook/assets/instaly.jpg)

![When you go to the next screen, you can see SDK Components Setup screen like below. Select Performance (Intel ® HAXM) option and Android Virtual Device option, and clic Next button.](../.gitbook/assets/ui.jpg)

on the next screen, you can see Emulator Settings screen like below. Click Next button without any changing especially.

![the next process is just normal program installation, so I don’t explain the detail. Just click Finish button to continue Android studio installation to complete it. After Android studio installation, you can see Android studio is executed like below.](../.gitbook/assets/emulator.jpg)

![](../.gitbook/assets/android.jpg)

> #### Android Studio SDK Configuration <a href="#android-studio-sdk-configuration" id="android-studio-sdk-configuration"></a>
>
> Click `Configure > SDK Manger` menu on the right botton to go to Android SDK configuration.

![let’s see how to install and configure react-native development environment on Windows. If you want to know how to install react-native on Mac, see the blog post below.](../.gitbook/assets/sdkk.jpg)

1. Android SDK Platform 29
2. Intel x86 Atom System Image
3. Google APIs Intel x86 Atom System Image
4. Google APIs Intel x86 Atom\_64 System Image

If you select all options above, click OK button on the right bottom to install them.

> #### Configure Android Studio Environment Variable <a href="#configure-android-studio-environment-variable" id="configure-android-studio-environment-variable"></a>
>
> Android studio installation and configuration are done. Now, we need to set the environment variables. Right-click This PC and click Properties menu like below.

![When you click Properties menu, you can see System and Security screen. Click Advanced System settings on the left menu list.](../.gitbook/assets/im.jpg)

![When you click Advanced System settings menu, you can see System properties screen like below. Click Advanced tab, and select Environment Varialbes button on the bottom of Advaced tab.](../.gitbook/assets/ad.jpg)

![When you click Environment Variables button, you can see the dialog like below. Click New button on User variables for your name section.](../.gitbook/assets/pro.jpg)

![When you see the dialog like above, insert ANDROID\_HOME to Variable name, and your Android Studio SDK path to Variable value. If you don’t know your Android Studio SDK path, execute ANdroid Studio SDK confiruation screen like below. you can see Android Studio SDK location on the top of the Android Studio SDK configuration screen.](../.gitbook/assets/aaa.jpg)

![When you’ve added ANDROID\_HOME environment variable, you need to set Android Studio platform-tools path. Click Path variable on User variables for your name list to go to the edit dialog.](../.gitbook/assets/ds.jpg)

When you can see the screen like above, insert platform-tools folder paht in Android SDK path like `C:\Users\[user name]\AppData\Local\Android\Sdk\platform-tools` to the bottom of the list and click OK button.

After that, open Command Prompt(cmd) and execute the command below.

```
adb
```

If the environment variables are configured well, you can see the result like below.

>
>
> ```
> Android Debug Bridge version 1.0.41
> Version 29.0.1-5644136
> Installed as /Users/jeonghean_kim/Library/Android/sdk/platform-tools/adb
> ```

### Create & Check react-native Project <a href="#create--check-react-native-project" id="create--check-react-native-project"></a>

Execute React Native CLI command below to create react-native project.

```
npx react-native init WandieDemoApp
```

#### Check on Android <a href="#check-on-android" id="check-on-android"></a>

In Android, execute the command below after connecting the device that the developer mode is activated via USB or executing Android studio emulator.

```
cd SampleApp
# react-native run-android
npm run android
```

If you don’t have any problen, you can see the screen like below.

![](../.gitbook/assets/fg.jpg)

We’ve seen how to install and configure react-native to develop the app on Windows. Also, We’ve created the app by React Native CLI and executed it to check the environment is configured well.

Now, we are ready to develop the app with react-native. Let’s dive to the react-native development world!

CREDITS : [https://dev-yakuza.posstree.com/en/react-native/install-on-windows/](https://dev-yakuza.posstree.com/en/react-native/install-on-windows/)



