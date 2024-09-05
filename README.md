# Clang-r522817

## Source
This repository is pulled frome AOSP source.  

from: https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+/refs/heads/main/clang-r522817/  
tree: 53718971d9d1c882e13c2f3b45409d741849ffa5  
at: Wed Sep 05 18:30:51 2024 +0000

## Useage
Add code to <source_code_path>/.repo/local_manifests/roomservice.xml  
```
<?xml version="1.0" encoding="UTF-8"?>
<manifest>

    <!-- Add this if you haven't defined 'github-non-los' remote -->
    <remote name="github-non-los"
           sync-c="true"
           sync-j="4"
           fetch="https://github.com" />

    <project path="prebuilts/clang/host/linux-x86/clang-r522817" name="flyfishxu/clang_host_linux-x86_clang-r522817" remote="github-non-los" />

    <!-- 
        Your other room define here.
    -->

<manifest />
```