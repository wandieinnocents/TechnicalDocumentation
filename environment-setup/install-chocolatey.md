---
description: >-
  Chocolatey Chocolatey is a package manager on Windows to install and manage
  packages. We can install packages simply on Windows via Chocolatey.
  Chocolatey: https://chocolatey.org/
---

# Install Chocolatey

For installing Chocolatey, open Command Prompt(cmd) as Administrator, and execute the command below.

{% hint style="success" %}
****

```
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```
{% endhint %}

After installing, reopen Command Prompt(cmd), and execute the command below to check Chocolatey is installed well.

>
>
> ```
> choco –version
> ```

> If Chocolatey is installed well, you can see Chocolatey version on the screen.
>
> ```
> 0.10.15
> ```
