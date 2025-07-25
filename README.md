# Lerobodog 项目总览

Lerobodog是一款低成本开源复合机器人，兼容主流的lerobot开源生态与商用陪伴机器人底座蔚蓝babyalpha。大家可以通过该设备进行模仿学习，训练物体遥操能力；通过isaac sim大规模强化学习训练，支持从机器人地形自适应行走到动物行为模仿等全套内容；另外将提供小智AI助手的大模型接入和支持。
本项目包含 Lerobodog 相关的硬件、固件、软件、模型和文档资源，旨在为机器人开发者和爱好者提供完整的技术支持和参考。

## 项目结构

```
├── 1.Hardware/         # 硬件相关资料
│   ├── Alphababy/     # Alphababy 机器人硬件
│   ├── Lerobot/       # Lerobot 机器人硬件
│   ├── Power Adaper/  # 电源适配器相关
│   └── RDK x5/        # RDK x5 硬件资料
├── 2.Firmware/         # 固件源码与说明
│   ├── Alphababy/     # Alphababy 固件
│   ├── Lerobot/       # Lerobot 固件
│   └── RDK x5/        # RDK x5 固件
├── 3.Software/         # 软件源码与工具
│   ├── AlphaBaby/     # Alphababy 软件
│   ├── Lerobot/       # Lerobot 软件
│   └── RDK x5/        # RDK x5 软件
├── 4.Model/            # 机械结构与仿真模型
│   ├── Alphababy/     # Alphababy 机械模型
│   ├── Fitting/       # 机械配件
│   │   ├── Arm/       # 机械臂配件
│   │   └── RDK x5/    # RDK x5 配件
│   └── Lerobot/       # Lerobot 机械模型
├── 5.Docs/             # 项目文档
│   └── Bom.xlsx       # 物料清单
├── CONTRIBUTING.md     # 贡献指南
├── LICENSE             # 许可证
├── README.md           # 项目说明
└── Lerobodog技术路线图.pdf # 技术路线图
```

## 快速开始

1. 阅读 `Lerobodog技术路线图.pdf` 了解整体规划。
2. 参考 `CONTRIBUTING.md` 参与项目贡献。
3. 按需查阅各目录下的硬件、固件、软件和模型资源。
4. 物料清单见 `5.Docs/Bom.xlsx`。

## 贡献方式

欢迎提交 issue、pull request 或参与文档完善。请遵循 `CONTRIBUTING.md` 中的规范。

## 许可证

本项目采用 `LICENSE` 文件中所述的开源协议。

## 联系与支持

如有疑问或建议，请通过 issue 反馈或联系项目维护者。

---

> Lerobodog 致力于打造开放、可扩展的机器人平台，欢迎更多开发者加入！


