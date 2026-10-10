# awesome-nuedc-lanqiao

> 全国大学生电子设计竞赛（NUEDC / 电赛）与蓝桥杯 开源资源精选清单。

这是一个**策展（curated）清单**，汇总 GitHub 上高质量的电赛 / 蓝桥杯相关开源项目，按方向分类，并标注许可证与主要语言，方便备赛的同学快速找到可学习、可二次开发的资源。

> ⚠️ **许可证提示**：清单中标注了各项目的许可证。MIT / Apache-2.0 / BSD / GPL 等项目可依其条款二次开发；标注「无许可证」的项目默认保留所有权利，**仅供学习参考，不可再分发或商用**。二次开发前请务必阅读原项目的 LICENSE 与 README。

---

## 目录

- [赛题 / 真题](#赛题--真题)
- [视觉方案（电赛 E 题等）](#视觉方案电赛-e-题等)
- [控制 / 小车](#控制--小车)
- [信号 / 电源 / 声源](#信号--电源--声源)
- [蓝桥杯 · 嵌入式](#蓝桥杯--嵌入式)
- [蓝桥杯 · 算法 / Python](#蓝桥杯--算法--python)
- [开发板 / PCB](#开发板--pcb)
- [备赛资料 / 工具箱](#备赛资料--工具箱)
- [相关改进项目](#相关改进项目)

---

## 赛题 / 真题

| 项目 | 星标 | 语言 | 许可证 | 说明 |
|---|---|---|---|---|
| [CCBP/NUEDC_Topic](https://github.com/CCBP/NUEDC_Topic) | ⭐995 | — | 无许可证 | 收集整理了 1994–2025 年全国大学生电子设计竞赛历年赛题 |
| [zuoliangyu/NUEDC_TOPIC](https://github.com/zuoliangyu/NUEDC_TOPIC) | ⭐116 | — | 无许可证 | 电赛真题文档，更新到 2026 |
| [chenshuo/nuedc](https://github.com/chenshuo/nuedc) | ⭐65 | HTML | 无许可证 | nuedc.org 站点 |

## 视觉方案（电赛 E 题等）

| 项目 | 星标 | 语言 | 许可证 | 说明 |
|---|---|---|---|---|
| [heyu-233/maixcam-ees-vision-course](https://github.com/heyu-233/maixcam-ees-vision-course) | ⭐113 | Python | 无许可证 | 配套《MaixCAM 电赛视觉教程》的开源代码，摄像头采集 + 图像识别 + AI 检测 + 串口输出 |
| [lvreng/puzzle-vision-simulator](https://github.com/lvreng/puzzle-vision-simulator) | ⭐68 | Python | 无许可证 | 2026 电赛 E 题：拼图视觉识别、矩形还原、位姿矩阵与仿真 |
| [DBinK/2023-NUEDC-E-OpenCV](https://github.com/DBinK/2023-NUEDC-E-OpenCV) | ⭐31 | Python | Apache-2.0 | 2023 电赛 E 题，低成本核桃派 + OpenCV 图像检测方案，面向对象封装 |
| [ziqi-ning/SENTINEL-Vision](https://github.com/ziqi-ning/SENTINEL-Vision) | ⭐29 | Python | MIT | 无人机多维感知库：颜色/形状/特殊标记/雷达融合/串口，工程化完善、带测试 |
| [PancakeCN/nuedc-2019-openmv](https://github.com/PancakeCN/nuedc-2019-openmv) | ⭐29 | Python | 无许可证 | 2019 电赛 OpenMV microPython 代码 |
| [zhouzhou-code/elec_vision_k230](https://github.com/zhouzhou-code/elec_vision_k230) | ⭐23 | Python | 无许可证 | 2023 电赛 E 题 K230 视觉识别代码 |
| [satoshiSchubert/K210_FACEDET](https://github.com/satoshiSchubert/K210_FACEDET) | ⭐21 | Python | GPL-3.0 | 2020 电赛 F 题视觉部分解决方案（K210） |
| [Black-Cyan/NUEDC-2025](https://github.com/Black-Cyan/NUEDC-2025) | ⭐19 | Python | MIT | 2025 电赛 E 题 MaixCAM OpenCV 视觉代码 |
| [CodeCatMeow/CVtools_ForNUEDC](https://github.com/CodeCatMeow/CVtools_ForNUEDC) | ⭐18 | Python | BSD-3-Clause | 面向电赛的视觉处理工具库：巡线、目标识别、ROI、串口等 |
| [0Leeeezy0/25-NUEDC-C](https://github.com/0Leeeezy0/25-NUEDC-C) | ⭐15 | C++ | 无许可证 | 2025 电赛 C 题单目视觉部分开源 |
| [lyletang/ShapeRecognition](https://github.com/lyletang/ShapeRecognition) | ⭐14 | Python | 无许可证 | 2016 校电子设计竞赛，树莓派 + OpenCV 零件形状识别 |
| [xiaoqi371317/k230-25-E](https://github.com/xiaoqi371317/k230-25-E) | ⭐11 | Python | 无许可证 | 2025 电赛 E 题传统视觉算法（非训练模型） |
| [InImpasse/openmv_identify](https://github.com/InImpasse/openmv_identify) | ⭐9 | Python | 无许可证 | 2020 TI 杯 F 题识别部分 |

## 控制 / 小车

| 项目 | 星标 | 语言 | 许可证 | 说明 |
|---|---|---|---|---|
| [yssickjgd/robowalker_train](https://github.com/yssickjgd/robowalker_train) | ⭐843 | C | 无许可证 | RoboMaster 中国科大 RoboWalker 战队电控组培训教学资料 |
| [Thirtynine3939/2025GongChuang_AGV](https://github.com/Thirtynine3939/2025GongChuang_AGV) | ⭐150 | Python | 无许可证 | 2025 工创赛物流搬运 AGV，代码、电路、结构开源 |
| [ptrtonull-workshop/ardupilot](https://github.com/ptrtonull-workshop/ardupilot) | ⭐81 | C | 无许可证 | 电赛项目：STM32 连接 APM、OpenMV、Arduino |
| [abcuer/2024-NUEDC-H-TI_CAR](https://github.com/abcuer/2024-NUEDC-H-TI_CAR) | ⭐32 | C | 无许可证 | 2024 电赛 H 题，TI-MSPM0 惯性导航 + 巡线自动行驶小车 |
| [Pansamic/CarOS](https://github.com/Pansamic/CarOS) | ⭐21 | C | GPL-2.0 | 电赛小车系统：智能车、运动学模型、STM32/MSP432 |

## 信号 / 电源 / 声源

| 项目 | 星标 | 语言 | 许可证 | 说明 |
|---|---|---|---|---|
| [framist/NUEDC2022-E](https://github.com/framist/NUEDC2022-E) | ⭐52 | C | MIT | NUEDC 2022 E 声源定位跟踪系统，省级一等奖作品 |

## 蓝桥杯 · 嵌入式

| 项目 | 星标 | 语言 | 许可证 | 说明 |
|---|---|---|---|---|
| [ReCclay/Blue_Bridge_Embedded_Cup](https://github.com/ReCclay/Blue_Bridge_Embedded_Cup) | ⭐87 | C | 无许可证 | 蓝桥杯嵌入式备赛相关 |
| [nature1995/lanqiao-competition-code](https://github.com/nature1995/lanqiao-competition-code) | ⭐61 | C | MIT | 蓝桥杯嵌入式历年比赛试题与源码（省赛/决赛全部实现） |

## 蓝桥杯 · 算法 / Python

| 项目 | 星标 | 语言 | 许可证 | 说明 |
|---|---|---|---|---|
| [TsingPig/Python-Quick-Course](https://github.com/TsingPig/Python-Quick-Course) | ⭐845 | Python | 无许可证 | Python 算法竞赛速成课件，配套《蓝桥杯 Python 冲刺课》视频 |
| [PlutoaCharon/LanQiaoCode_Python](https://github.com/PlutoaCharon/LanQiaoCode_Python) | ⭐219 | Python | 无许可证 | 蓝桥杯官方练习系统 VIP 题库真题 Python 讲解（持续更新） |
| [TuGengs/Blue_Bridge_Cup](https://github.com/TuGengs/Blue_Bridge_Cup) | ⭐126 | — | 无许可证 | 2018 蓝桥杯 VIP 题 |
| [bat67/challenge-competitive-programming](https://github.com/bat67/challenge-competitive-programming) | ⭐97 | C++ | 无许可证 | 《挑战程序设计竞赛 2》电子书与配套代码 |
| [HEEKDragonOne/ACM](https://github.com/HEEKDragonOne/ACM) | ⭐91 | C++ | 无许可证 | 蓝桥杯 VIP 题库 + 一本通基础/提高 + 测试数据 |
| [libo-sober/LanQiaoCup](https://github.com/libo-sober/LanQiaoCup) | ⭐67 | Python | 无许可证 | 蓝桥杯刷题 |
| [koking0/Algorithm](https://github.com/koking0/Algorithm) | ⭐52 | Python | 无许可证 | 蓝桥杯备战 |
| [shannany0606/2024_LanQiao_Cup_Province](https://github.com/shannany0606/2024_LanQiao_Cup_Province) | ⭐45 | Python | 无许可证 | 2024 第十五届蓝桥杯 Python A 组省赛题目 + 参赛代码 |
| [MAyang38/Blue_Bridge_Cup_Python](https://github.com/MAyang38/Blue_Bridge_Cup_Python) | ⭐28 | Python | 无许可证 | 蓝桥杯 Python 练习系统题库 |
| [lixiangcog/Algorithm_LanQiaobei](https://github.com/lixiangcog/Algorithm_LanQiaobei) | ⭐18 | Python | 无许可证 | 蓝桥杯算法合集 |
| [shannany0606/2023_Lanqiao_Cup](https://github.com/shannany0606/2023_Lanqiao_Cup) | ⭐16 | Python | 无许可证 | 2023 蓝桥杯国赛 Python A 组一等奖（题目 + 考场代码） |
| [Beluga-qwq/python_code](https://github.com/Beluga-qwq/python_code) | ⭐14 | Python | 无许可证 | Python 蓝桥杯题库 |
| [shannany0606/2024_LanQiao_Cup_Nation](https://github.com/shannany0606/2024_LanQiao_Cup_Nation) | ⭐12 | Python | MIT | 2024 蓝桥杯国赛 Python A 组一等奖（题目 + 考场代码） |
| [GuoXianSen/LanQiao_Python](https://github.com/GuoXianSen/LanQiao_Python) | ⭐9 | Python | 无许可证 | 蓝桥杯 Python 解答 |

## 开发板 / PCB

| 项目 | 星标 | 语言 | 许可证 | 说明 |
|---|---|---|---|---|
| [Auroranchen/-PCB](https://github.com/Auroranchen/-PCB) | ⭐62 | — | 无许可证 | 面向蓝桥杯单片机竞赛的 STM32G431RBT6 开发板（嘉立创 EDA，含 DAP-Link、EEPROM、NE555 等外设） |

## 备赛资料 / 工具箱

| 项目 | 星标 | 语言 | 许可证 | 说明 |
|---|---|---|---|---|
| [mc3545dada/mspm0-skill](https://github.com/mc3545dada/mspm0-skill) | ⭐374 | Python | MIT | 面向电赛的 MSPM0 + SysConfig Agent Skill |
| [bitkylin/MapForTour](https://github.com/bitkylin/MapForTour) | ⭐126 | Java | MIT | 研电赛华南赛区二等奖：百度地图多人定位 / 轨迹 / 地理围栏 |
| [TANSUNS/NEDUC_lib](https://github.com/TANSUNS/NEDUC_lib) | ⭐66 | C | 无许可证 | 电子设计竞赛基础算法 & 模块 |
| [CNYuYang/nuedc-prepare-roadmap](https://github.com/CNYuYang/nuedc-prepare-roadmap) | ⭐59 | — | MIT | 电赛备赛图（控制、信号、电源三大方向） |
| [CNLHC/NUEDC-Toolbox](https://github.com/CNLHC/NUEDC-Toolbox) | ⭐34 | C | 无许可证 | 全国大学生电子设计竞赛工具箱 |
| [MDLZCOOL/nwpu-nuedc](https://github.com/MDLZCOOL/nwpu-nuedc) | ⭐28 | C | MIT | 西工大电赛备赛资料 |

## 相关改进项目

- [**SENTINEL-Vision（改进版）**](https://github.com/LXZhui/SENTINEL-Vision) —— 本清单作者**李熙哲**基于 [ziqi-ning/SENTINEL-Vision](https://github.com/ziqi-ning/SENTINEL-Vision)（MIT）改进：修复 import 重构 bug、OpenCV 5.0 / Python 3.12 兼容、可选依赖守卫导入、补全 CI 与测试，88 个测试全部通过。

---

## 贡献

欢迎通过 PR 补充高质量的电赛 / 蓝桥杯开源项目。请遵循以下约定：

1. 项目需与电赛 / 蓝桥杯强相关。
2. 尽量选择有明确许可证、README 完整、维护较活跃的项目。
3. 表格中准确标注许可证（无 LICENSE 文件的项目标注「无许可证」）。

## 免责声明

本清单仅做索引与导航，不托管任何第三方源码。各项目版权归原作者所有，使用前请阅读并遵守对应许可证。

## 作者与许可

© 2026 李熙哲（[LXZhui](https://github.com/LXZhui)）· 本清单采用 [MIT 许可证](LICENSE)。
