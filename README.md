# HCSL
支持LoongArch架构，GNU/Linux，MAC，Windows的《都市：天际线2》开源第三方启动器。

本启动器计划基于2023年8月23日发布的Mono 6.13-ea4 LoongArch64及更高版本，同时与Unity进行适配。

# 研制背景
2023年10月25日，《都市：天际线2》发布，2023年11月28日，龙芯3A6000在北京发布，主频2.5GHZ，单核及多核浮点性能接近Intel i3 10100；华硕发布携带龙芯3A6000的主板XC-LS3A6M。

HMCL启动器于2022年完成龙芯原生LoongArch架构适配，使得龙芯能原生运行《我的世界》；龙芯中科的.NET编译器团队与Unity中国合作，完成LoongArch架构下Mono适配。

《都市：天际线2》基于Unity开发，使用C#语言编写并在Mono虚拟机中运行，具有移植至龙芯平台的可能性。基于以上背景，决定启动适配龙芯LoongArch架构的《都市：天际线2》开源第三方启动器项目。

# 项目目标
让《都市：天际线2》C#字节码能原生运行于龙芯3A6000及以上平台，并满足以下最低配置及推荐配置：

## 最低配置
系统要求:需要 64 位处理器和操作系统

操作系统:loongnix，UOS V20桌面专业版LoongArch64

龙架构(LoongArch):LA664

处理器:龙芯(loongson)3A6000

内存:8GB RAM

主板:-

显卡:龙芯(loongson)7A2000桥片(2GB)

声卡:适配LoongArch架构的任意声卡

网络:宽带互联网连接
## 推荐配置
系统要求:需要 64 位处理器和操作系统

操作系统:UOS V20桌面专业版LoongArch64 1060

龙架构(LoongArch):LA664及以上架构

处理器:龙芯(loongson)3A6000及更高版本处理器

内存:16GB RAM

主板:华硕(ASUS) XC-LS3A6M

显卡:摩尔线程MTT S80(16GB)

声卡:适配LoongArch架构的任意声卡

网络:宽带互联网连接

# 与Paradox Launcher，Steam平台关系
本启动器并非与Paradox Launcher及Steam平台制造对立，亦未有破坏《都市：天际线2》开发商Colossal Order与发行商Paradox Interactive官方跨平台之意图，而是提供直接启动《都市：天际线2》C#字节码或在龙芯3A6000及更高版本龙芯CPU启动《都市：天际线2》Linux版的途径。

# 本启动器是否适合在龙芯3A5000启动《都市：天际线2》
虽龙芯3A5000亦为LoongArch架构，然龙芯3A5000性能较弱，不建议使用此启动器运行《都市：天际线2》。

# HCSL(English)
"Hello Cities:Skylines 2 Launcher" that support LoongArch, Linux, mac, windows.

This launcher is planned to be based on Mono 6.13-ea4 LoongArch64 and higher released on August 23, 2023, and will be compatible with Unity.

# Development background

On October 25, 2023, "Cities:Skylines 2" was released. On November 28, 2023, Loongson 3A6000 was released in Beijing, with a main frequency of 2.5GHz and single core and multi-core floating-point performance close to Intel i3 10100; ASUS releases the XC-LS3A6M motherboard carrying the Loongson 3A6000.

The HMCL launcher completed the native LoongArch architecture adaptation of Loongson in 2022, enabling Loongson to run Minecraft natively; Longxin Zhongke .NET team collaborated with Unity China to complete Mono adaptation under the LoongArch architecture.

"Cities:Skylines 2" is developed based on Unity, written in C# language and running in Mono virtual machine, with the possibility of being ported to the Loongson platform. Based on the above background, it is decided to launch the open-source third-party launcher project for "Cities:Skylines 2" that is adapted to the LoongArch architecture of Loongson.

# Project purpose

Enable the C# bytecode of "Cities:Skylines 2" to run natively on Loongson 3A6000 and above platforms, and meet the following minimum and recommended configurations:

## Minimum configuration

System requirements: 64 bit processor and operating system required

Operating System: Loongnix, UOS V20 Desktop Professional Edition LoongArch64

LoongArch: LA664

Processor: Loongson 3A6000

Memory: 8GB RAM

Motherboard:-

Graphics card: Loongson 7A2000 GPU (2GB)

Sound Card: Any sound card that is compatible with the LoongArch architecture

Network: Broadband Internet Connection

## Recommended configuration

System requirements: 64 bit processor and operating system required

Operating System: UOS V20 Desktop Professional Edition Loongarch64 1060

LoongArch: LA664 and higher architecture

Processor: Loongson 3A6000 and higher processors

Memory: 16GB RAM

Motherboard: ASUS XC-LS3A6M

Graphics card: Moore thread MTT S80 (16GB)

Sound Card: Any sound card that is compatible with the LoongArch architecture

Network: Broadband Internet Connection

# Relationship with Paradox Launcher and Steam Platform

This launcher is not intended to create a conflict with Paradox Launcher and Steam platforms, nor is it intended to disrupt the official cross platform intentions of Colossal Order, the developer of "Cities:Skylines 2", and Paradox Interactive, the publisher. Instead, it provides a way to directly launch the C# bytecode of "Cities:Skylines 2" or to launch the Linux version of "Cities:Skylines 2" on Loongson 3A6000 and higher Loongson CPUs.

# Is this starter suitable for starting "Cities:Skylines 2" on Loongson 3A5000

Although the LoongArch architecture is also used for the Loongson 3A5000, its performance is weak and it is not recommended to use this launcher to run "Cities:Skylines 2".

# HCSL(日本語)
竜アーキ(LoongArch)、GNU/Linux、MAC、Windowsの「都市：天際線2」(シティーズ:スカイライン2)オープンソース第三者ランチャーをサポートする。

本ランチャーは、2023年8月23日にリリースされるMono 6.13-ea4 LoongArch64およびそれ以上のバージョンに基づいて、Unityとの適合を同時に行う予定です。

# 開発背景

2023年10月25日、「都市：天際線2」が発表され、2023年11月28日、龍芯3A6000が北京で発表された。主周波数は2.5 GHZで、単核及び多核浮動小数点性能はIntel i3 10100に近い。ASUSTeKは、龍芯3A6000を搭載したマザーボードXC-LS3A6Mを発表した。

HMCLスタータは2022年に龍芯原生LoongArchアーキテクチャの適合を完成し、龍芯が原生的に「Minecraft」を運行できるようにした、龍芯中科の.NETコンパイラチームはUnity中国と協力し、LoongArchアーキテクチャ下でMono適合を完成した。

「都市：天際線2」はUnity開発に基づいて、C#言語を用いて作成し、Mono仮想マシンで実行し、龍芯プラットフォームに移植する可能性がある。以上の背景に基づいて、龍芯LoongArchアーキテクチャに適した「都市：天際線2」のオープンソース第三者イニシエータプロジェクトを開始することを決定した。

# プロジェクト目標

「都市：天際線2」C#バイトコードを龍芯3A6000以上のプラットフォームで原生的に動作させ、以下の最低配置と推奨配置を満たす：

## 最低配置

システム要件：64ビットCPUとオペレーティングシステムが必要

オペレーティングシステム：loongnix、UOS V20専業エディションLoongArch64

LoongArch：LA664

CPU：龍芯（loongson）3A6000

メモリ：8GB RAM

マザーボード:-

グラフィックスカード：龍芯（loongson）7A2000 GPU（2GB）

サウンドカード：LoongArchに適した任意のサウンドカード

ネットワーク：ブロードバンドインターネット接続

## 推奨配置

システム要件：64ビットCPUとオペレーティングシステムが必要

オペレーティングシステム：UOS V20UOS V20専業エディションLoongArch64 1060

LoongArch：LA664以降

CPU：龍芯（loongson）3A6000以降

メモリ：16GB RAM

マザーボード：ASUS XC-LS3A6M

グラフィックス：摩爾線程MTT S80（16GB）

サウンドカード：LoongArchに適した任意のサウンドカード

ネットワーク：ブロードバンドインターネット接続

# Paradox Launcher，Steamプラットフォームとの関係

本イニシエータはParadox LauncherおよびSteamプラットフォームの製造と対立しているわけではなく、「都市：天際線2」開発者のColossal Orderと発行元のParadox Interactive公式クロスプラットフォームを破壊する意図もなく、「都市：天際線2」C#バイトコードを直接起動するか、龍芯3A6000およびそれ以上のバージョンの龍芯CPUで「都市：天際線2」Linux版を起動する方法を提供している。

# 本イニシエータは龍芯3A5000で「都市：天際線2」を起動するのに適しているか

龍芯3A5000もLoongArchアーキテクチャであるが、龍芯3A5000は性能が弱く、このイニシエータを使用して「都市：天際線2」を実行することは推奨されていない。
