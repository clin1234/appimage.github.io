---
layout: app

permalink: /Another_Redis_Desktop_Manager/
description: A faster, better and more stable redis desktop manager.
A faster, better and more stable redis desktop manager.
license: MIT

icons:
  - Another_Redis_Desktop_Manager/icons/512x512/another-redis-desktop-manager.png

screenshots:
  - Another_Redis_Desktop_Manager/screenshot.png

authors:
  - name: qishibo
    url: https://github.com/qishibo

links:
  - type: GitHub
    url: qishibo/AnotherRedisDesktopManager
  - type: Download
    url: https://github.com/qishibo/AnotherRedisDesktopManager/releases

desktop:
  Desktop Entry:
    Name: Another Redis Dsektop Manager
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: another-redis-manager
    StartupWMClass: Another Redis Dsektop Manager
    X-AppImage-Version: 1.1.0
    Comment: A faster, better and more stable redis desktop manager.
    Categories: Utility
    X-AppImage-BuildId: 1IcDSJorHRex0mIBUhU82mTHt1F
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  author: Another
  private: true
  main: electron-main.js
  dependencies:
    electron-updater: 4.6.5
    font-list: "^1.4.5"
  repository: github:qishibo/AnotherRedisDesktopManager
---
