# WCH CH32 微控制器应用笔记

<p align="center">
  <img src="Images/GitHub-Assets/MES-Hero-Banner.svg" width="100%" alt="MEMAR ELECTRONIC SANAT — MES">
</p>

[🇮🇷 فارسی](README.md) | [🇬🇧 English](README_EN.md) | [🇨🇳 中文](README_zh.md)

## 项目简介

本仓库收集 **WCH CH32 系列微控制器**的应用笔记（Application Notes，简称 AN），内容涵盖 MCU 功能应用、硬件设计、外设配置、固件实现、调试排查以及实际项目中的性能优化。

应用笔记用于补充芯片数据手册（Datasheet）和参考手册（Reference Manual），围绕具体功能或工程问题提供实现步骤、设计注意事项、示例流程及实际应用限制。

## 语言版本与目录结构

| 语言 | 目录 / 文件 | 说明 |
| :---: | :--- | :--- |
| 波斯语 | [fa/](fa/) | 波斯语文档指南及逐步发布的翻译文件 |
| 中文 | [zh/](zh/) | 中文原始应用笔记，包含现有的 Markdown 和 PDF 文件 |
| 英文 | [README_EN.md](README_EN.md) | 英文项目介绍及文档索引 |
| 中文 | [README_zh.md](README_zh.md) | 中文项目介绍及文档索引 |

**波斯语翻译状态：** `fa` 目录目前为下表中的 49 个文档编号分别提供了独立的 README 指南。但各文档的翻译文件并不完全相同：部分目录已包含波斯语 HTML 或 PDF，其他目录目前可能只有指南和相关媒体文件。请打开对应的波斯语 README，确认实际提供的文件。存在目录指南并不代表整篇文档已经完成翻译。

## 文档查找与使用方法

1. 根据文档编号或主题，在下表中查找所需应用笔记。
2. 打开波斯语指南，查看翻译状态及当前可用的波斯语文件。
3. 通过中文原文链接访问原始文档及其配套资料。
4. 设计前请根据具体 MCU 型号的数据手册核对引脚功能、电气参数、封装选项和工作条件。
5. 示例代码应结合 MCU 型号、库版本、开发环境和目标硬件进行适配，并在实际硬件上完成验证后再用于产品设计。

## 应用笔记目录

| 编号 | 主题 | 波斯语指南 | 中文原文 |
| :---: | :--- | :---: | :---: |
| AN01000 | 低功耗应用笔记 | [波斯语指南](fa/AN01000/README.md) | [中文原文](zh/AN01000/AN01000.md) |
| AN01001 | VDD12 外部供电方案 | [波斯语指南](fa/AN01001/README.md) | [中文原文](zh/AN01001/AN01001.md) |
| AN01002 | CH32L103 低功耗实现策略 | [波斯语指南](fa/AN01002/README.md) | [中文原文](zh/AN01002/AN01002.md) |
| AN01003 | 芯片复位原因分析 | [波斯语指南](fa/AN01003/README.md) | [中文原文](zh/AN01003/AN01003.md) |
| AN03000 | CH32H417 ICache 使用说明 | [波斯语指南](fa/AN03000/README.md) | [中文原文](zh/AN03000/AN03000.md) |
| AN03001 | 双核芯片的中断分配与唤醒 | [波斯语指南](fa/AN03001/README.md) | [中文原文](zh/AN03001/AN03001.md) |
| AN03002 | CoreMark 介绍与跑分配置 | [波斯语指南](fa/AN03002/README.md) | [中文原文](zh/AN03002/AN03002.md) |
| AN03003 | QingKe RISC-V 内核特色指令 | [波斯语指南](fa/AN03003/README.md) | [中文原文](zh/AN03003/AN03003.md) |
| AN03004 | 不同存储介质下运行速度对比 | [波斯语指南](fa/AN03004/README.md) | [中文原文](zh/AN03004/AN03004.md) |
| AN03005 | CH32H417 内核特殊功能介绍 | [波斯语指南](fa/AN03005/README.md) | [中文原文](zh/AN03005/AN03005.md) |
| AN08000 | CH32H417/415/416 系列 DMA 使用注意事项 | [波斯语指南](fa/AN08000/README.md) | [中文原文](zh/AN08000/AN08000.md) |
| AN09000 | 通用 MCU 系列 ADC 使用及注意事项 | [波斯语指南](fa/AN09000/README.md) | [中文原文](zh/AN09000/AN09000.md) |
| AN09001 | CH32X315 ADC 外设使用说明 | [波斯语指南](fa/AN09001/README.md) | [中文原文](zh/AN09001/AN09001.md) |
| AN10000 | WCH 触摸按键应用指南 | [波斯语指南](fa/AN10000/README.md) | [中文原文](zh/AN10000/AN10000.md) |
| AN11000 | RTC/Systick/TIM/LPTIM 对比与应用 | [波斯语指南](fa/AN11000/README.md) | [中文原文](zh/AN11000/AN11000.md) |
| AN11001 | 精简定时器的功能与应用 | [波斯语指南](fa/AN11001/README.md) | [中文原文](zh/AN11001/AN11001.md) |
| AN11002 | 电机应用相关 TIM 使用技巧 | [波斯语指南](fa/AN11002/README.md) | [中文原文](zh/AN11002/AN11002.md) |
| AN14000 | SerDes 使用基础教程 | [波斯语指南](fa/AN14000/README.md) | [中文原文](zh/AN14000/AN14000.md) |
| AN16001 | I2C 与 I3C 对比及 I3C 使用说明 | [波斯语指南](fa/AN16001/README.md) | [中文原文](zh/AN16001/AN16001.md) |
| AN17000 | 通用 MCU 系列 SPI 主机模式 NSS 使用教程 | [波斯语指南](fa/AN17000/README.md) | [中文原文](zh/AN17000/AN17000.md) |
| AN21000 | SDIO 从模式使用说明 | [波斯语指南](fa/AN21000/README.md) | [中文原文](zh/AN21000/AN21000.md) |
| AN22000 | SDMMC 多媒体卡和从模式通信 | [波斯语指南](fa/AN22000/README.md) | [中文原文](zh/AN22000/AN22000.md) |
| AN23000 | PIOC 功能与使用介绍 | [波斯语指南](fa/AN23000/README.md) | [中文原文](zh/AN23000/AN23000.md) |
| AN24000 | CH32 通用系列 OPA 外设使用指南 | [波斯语指南](fa/AN24000/README.md) | [中文原文](zh/AN24000/AN24000.md) |
| AN24001 | CH32 通用系列 CMP 使用指南 | [波斯语指南](fa/AN24001/README.md) | [中文原文](zh/AN24001/AN24001.md) |
| AN25001 | SAI 与 I2S 对比及 SAI 使用说明 | [波斯语指南](fa/AN25001/README.md) | [中文原文](zh/AN25001/AN25001.md) |
| AN26001 | SPI 与 QSPI 对比及 QSPI 使用说明 | [波斯语指南](fa/AN26001/README.md) | [中文原文](zh/AN26001/AN26001.md) |
| AN29000 | FMC 驱动 SDRAM 基础教程 | [波斯语指南](fa/AN29000/README.md) | [中文原文](zh/AN29000/AN29000.md) |
| AN31001 | CH32H417 数字滤波器使用说明 | [波斯语指南](fa/AN31001/README.md) | [中文原文](zh/AN31001/AN31001.md) |
| AN35000 | ARGB 优势对比及基础教程 | [波斯语指南](fa/AN35000/README.md) | [中文原文](zh/AN35000/AN35000.md) |
| AN36000 | PSRAM 使用方法 | [波斯语指南](fa/AN36000/README.md) | [中文原文](zh/AN36000/AN36000.md) |
| AN36001 | PSRAM 跑代码 | [波斯语指南](fa/AN36001/README.md) | [中文原文](zh/AN36001/AN36001.md) |
| AN36002 | V467 移植 LVGL 与使用 PSRAM 驱屏技巧 | [波斯语指南](fa/AN36002/README.md) | [中文原文](zh/AN36002/AN36002.md) |
| AN37000 | USB PD 使用及不同芯片对比 | [波斯语指南](fa/AN37000/README.md) | [中文原文](zh/AN37000/AN37000.md) |
| AN90000 | CH32H417QEU-R1-1v1 开发板使用说明 | [波斯语指南](fa/AN90000/README.md) | [中文原文](zh/AN90000/AN90000.md) |
| AN90001 | 轻量级 WCHGUI 开发实践：控制盒示例 | [波斯语指南](fa/AN90001/README.md) | [中文原文](zh/AN90001/AN90001.md) |
| AN90002 | 用户字区域作为 DataFlash | [波斯语指南](fa/AN90002/README.md) | [中文原文](zh/AN90002/AN90002.md) |
| AN90003 | FatFS 文件系统移植到 MRS | [波斯语指南](fa/AN90003/README.md) | [中文原文](zh/AN90003/AN90003.md) |
| AN91000 | 双核芯片调试配置及注意事项 | [波斯语指南](fa/AN91000/README.md) | [中文原文](zh/AN91000/AN91000.md) |
| AN91001 | 脱机烧录器使用说明 | [波斯语指南](fa/AN91001/README.md) | [中文原文](zh/AN91001/AN91001.md) |
| AN91002 | LD 和 Startup 文件常用工程配置 | [波斯语指南](fa/AN91002/README.md) | [中文原文](zh/AN91002/AN91002.md) |
| AN91003 | 片外 FLASH 的 LINK 下载流程 | [波斯语指南](fa/AN91003/README.md) | [中文原文](zh/AN91003/AN91003.md) |
| AN91004 | LINK 及 MRS 使用技巧 | [波斯语指南](fa/AN91004/README.md) | [中文原文](zh/AN91004/AN91004.md) |
| AN91005 | 通过命令行调试 | [波斯语指南](fa/AN91005/README.md) | [中文原文](zh/AN91005/AN91005.md) |
| AN91006 | 调试过程中芯片问题的排查方法 | [波斯语指南](fa/AN91006/README.md) | [中文原文](zh/AN91006/AN91006.md) |
| AN93000 | 屏幕驱动接口对比 | [波斯语指南](fa/AN93000/README.md) | [中文原文](zh/AN93000/AN93000.md) |
| AN94000 | M030 电源与电机应用功能介绍 | [波斯语指南](fa/AN94000/README.md) | [中文原文](zh/AN94000/AN94000.md) |
| AN94001 | EMI 相关注意事项 | [波斯语指南](fa/AN94001/README.md) | [中文原文](zh/AN94001/AN94001.md) |
| AN97000 | CH32 USB DFU 固件升级 | [波斯语指南](fa/AN97000/README.md) | [中文原文](zh/AN97000/AN97000.md) |

## 文档索引

[Index.csv](Index.csv) 提供表格形式的文档索引，可用于检索文档编号和主题。当前文件基于上游资料元数据，部分说明可能为中文。有关波斯语翻译的实际状态，请查看对应的 `fa/ANxxxxx/` 目录中的 README。

## 工程注意事项与免责声明

- 应用笔记不能替代 Datasheet、Reference Manual、Errata 或官方开发工具文档。
- 实施前请核对完整芯片型号、封装、硅版本、工作电压、时钟限制和引脚约束。
- 软件示例可能依赖特定版本的 MounRiver Studio（MRS）、外设库、编译器或固件。
- 对电源、时钟、存储器、USB、RF、EMI 和下载调试等关键部分，应独立验证原理图、PCB 布局和实测结果。
- 如发现问题，请通过仓库 Issues 提交反馈，并附上 AN 编号、MCU 型号、工具版本、复现步骤及预期结果。

## 相关资源

- [MES GitHub 组织](https://github.com/MEMAR-ELECTRONIC-SANAT)
- [WCH 官方论坛](https://www.wch.cn/bbs/forum-106-1.html)
- [中文原始文档](zh/)
- [波斯语指南](fa/)

<p align="center">
  <img src="Images/GitHub-Assets/MES-Divider.svg" width="100%" alt="MES Divider">
</p>

## 图片与示意图

- [MES GitHub 图形资源](Images/GitHub-Assets/)
- [项目横幅](Images/GitHub-Assets/MES-Hero-Banner.svg)
- [章节标题图片](Images/GitHub-Assets/MES-Section-Header.svg)

## 编译与维护

**معمار الکترونیک صنعت**\
**MEMAR ELECTRONIC SANAT (MES)**

همراه شما در مسیر طراحی و ساخت مدارهای مطمئن

电子电路与 PCB 设计、嵌入式系统开发及微控制器配置工具。

- Telegram: [https://t.me/Memar_Electronic](https://t.me/Memar_Electronic)
- Instagram: [https://www.instagram.com/Memar.Electronic](https://www.instagram.com/Memar.Electronic)
- GitHub: [MEMAR-ELECTRONIC-SANAT](https://github.com/MEMAR-ELECTRONIC-SANAT)

<p align="center">
  <img src="Images/GitHub-Assets/MES-Thank-You-Footer.svg" width="100%" alt="Thank you for visiting MES">
</p>
