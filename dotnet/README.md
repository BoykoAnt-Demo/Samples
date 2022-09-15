```
dotnet publish -o out --self-contained --arch x64 --os <os>
```

# Windows
## Windows, not version-specific
- win-x64
- win-x86
- win-arm
- win-arm64

## Windows 7 / Windows Server 2008 R2
- win7-x64
- win7-x86

## Windows 8.1 / Windows Server 2012 R2
- win81-x64
- win81-x86
- win81-arm

## Windows 11 / Windows Server 2022 / Windows 10 / Windows Server 2016
- win10-x64
- win10-x86
- win10-arm
- win10-arm64

# Linux
## Linux, not distribution-specific
- linux-x64 (Most desktop distributions like CentOS, Debian, Fedora, Ubuntu, and derivatives)
- linux-musl-x64 (Lightweight distributions using musl like Alpine Linux)
- linux-arm (Linux distributions running on Arm like Raspbian on Raspberry Pi Model 2+)
- linux-arm64 (Linux distributions running on 64-bit Arm like Ubuntu Server 64-bit on Raspberry Pi Model 3+)

## Red Hat Enterprise Linux
- rhel-x64 (Superseded by linux-x64 for RHEL above version 6)
- rhel.6-x64

## Tizen
- tizen
- tizen.4.0.0
- tizen.5.0.0


## macOS
## macOS, not version-specific
- osx-x64 (Minimum OS version is macOS 10.12 Sierra)

## macOS 10.10 Yosemite
- osx.10.10-x64

## macOS 10.11 El Capitan
- osx.10.11-x64

## macOS 10.12 Sierra
- osx.10.12-x64

## macOS 10.13 High Sierra
- osx.10.13-x64

## macOS 10.14 Mojave
- osx.10.14-x64

## macOS 10.15 Catalina
- osx.10.15-x64

## macOS 11.0 Big Sur
- osx.11.0-x64
- osx.11.0-arm64

## macOS 12 Monterey
- osx.12-x64
- osx.12-arm64