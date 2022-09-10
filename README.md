# What
- packages\Microsoft.NET.StringTools.1.0.0\lib\netstandard2.0


# How To Install

Since version 2021 LTS unity has built-in System.Memory so we will not need to install additional dependencies for System.Collections.Immutable to work.


### For Unity 2021 LTS Or Newer
Add the lines below to `Packages/manifest.json`

for version `1.0.0`
```csharp
"com.system-community.stringtools": "https://github.com/system-community/StringTools.git?path=Assets/_Root#1.0.0",
"com.system-community.systemruntimecompilerservicesunsafe": "https://github.com/system-community/SystemRuntimeCompilerServicesUnsafe.git?path=Assets/_Root#5.0.0",
```


### For Unity 2020 LTS Or Older
Add the lines below to `Packages/manifest.json`

for version `1.0.0`
```csharp
"com.system-community.stringtools": "https://github.com/system-community/StringTools.git?path=Assets/_Root#1.0.0",
"com.system-community.systemmemory": "https://github.com/system-community/SystemMemory.git?path=Assets/_Root#4.5.4",
"com.system-community.systembuffers": "https://github.com/system-community/SystemBuffers.git?path=Assets/_Root#4.4.0",
"com.system-community.systemnumericsvectors": "https://github.com/system-community/SystemNumericsVectors.git?path=Assets/_Root#4.4.0",
"com.system-community.systemruntimecompilerservicesunsafe": "https://github.com/system-community/SystemRuntimeCompilerServicesUnsafe.git?path=Assets/_Root#5.0.0",
```
