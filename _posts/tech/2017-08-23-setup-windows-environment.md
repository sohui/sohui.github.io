---
layout: post
title: windows环境配置
category: 技术
tags: windows
keywords: windows
---

## How to fix `filename too long` in Windows Home Edition
1. Start the registry editor (regedit.exe)
2. Navigate to HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem
3. Double click LongPathsEnabled
4. Set to 1 and click OK
5. Reboot

## How to fix `Filename too long` in git for windows
以`管理员`身份执行如下命令：
```
git config --system core.longpaths true
```