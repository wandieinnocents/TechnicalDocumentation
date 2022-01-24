---
description: >-
  We need to install JDK(Java Development Kit) to develop Android app with
  react-native
---

# Install JDK

open Command Prompt(cmd) as Administrator, and Execute Chocolatey command below to install JDK.

If you already have a working version of JDK , You can skip this step

For different versions of JDK ,&#x20;

Recomended :  install JDK 11 from link below

&#x20;[https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)

Visit : [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)

Altenatively :&#x20;

```
choco install -y jdk8
```

After installing, reopen Command Prompt(cmd), and execute the command below to check Java is installed well.

```
java -version
```

If Java is installed well via installing JDK, you can see Java version like below.



```
openjdk version "1.8.0_222"
OpenJDK Runtime Environment (AdoptOpenJDK)(build 1.8.0_222-b10)
OpenJDK 64-Bit Server VM (AdoptOpenJDK)(build 25.222-b10, mixed mode)
```

When JDK is installed, Java compiler is alo installed. Execute the command below to check Java compiler is also installed well.

```
javac -version
```

If Java compiler is installed well via installing JDK, Java compiler version is shown up like below.

```
javac 1.8.0_222
```
