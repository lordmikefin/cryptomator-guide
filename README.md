# Guide for encrypt data with Cryptomator
This is guide and test ground for storing any data in encrypted storage which can be shared through any cloud storage.

  https://cryptomator.org

  https://cryptomator.org/downloads/


## Installing in Windows

Quick version:
Download 'Cryptomator-X.X.X-x64.msi' and install it.

  https://cryptomator.org/downloads/

  https://cryptomator.org/downloads/win/thanks/

Here is batch script for downloading and installing Resilio Sync.

```bat
C:

cd "%HOMEDRIVE%%HOMEPATH%\Downloads"

PowerShell -Command "& {$client = new-object System.Net.WebClient; $client.DownloadFile('https://github.com/cryptomator/cryptomator/releases/download/1.6.5/Cryptomator-1.6.5-x64.msi','.\Cryptomator-1.6.5-x64.msi')}"

Cryptomator-1.6.5-x64.msi
```

