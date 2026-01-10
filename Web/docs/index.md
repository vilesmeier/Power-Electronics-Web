# NUEDC电力电子方向备赛资料库  
## 仓库简介
山东大学全国大学生电子设计竞赛**电力电子**方向备赛资料库  

[GitHub Pages](https://vilesmeier.github.io/NUEDC)  
[GitHub Repository](https://github.com/vilesmeier/NUEDC)  
[GitHub License](https://github.com/vilesmeier/NUEDC/blob/main/LICENSE.md)  

## 快速开始
[快速开始与工具链教程](https://github.com/vilesmeier/NUEDC/blob/main/TUTORIAL.md)  

## 基础功能
 - 软件
     - 控制层/驱动层间代码解耦，函数/结构体接口
     - 控制器、数字滤波器等环路常用的控制层  
     - 面向**TI C2000系列DSP**的驱动层代码,支持*Doxygen*生成  
     - 支持*Doxygen*生成的API文档  
     - 对部分TI官方库的整合、打包
     - 部分赛题的完整题解、拓扑控制环路  
 - 硬件
     - 常用拓扑的单板集成化功率级  
     - 部分DSP的插卡式Control Card
 - 仿真
     - Matlab 2024b 数字环路仿真
     - Multisim 模拟环路仿真

## 平台支持
### 软件支持
**环路代码提供对C2000系列的汇编优化，对STM32系列仅提供C版本代码**  

- TMS320F28335
    - 寄存器开发（Bit-field）
    - CCS12.4  
    - C2000Ware_5_00_00_00  
    - C2000Ware_DigitalPower_SDK_5_02_00_00  
    - C2000Ware_MotorControl_SDK_5_02_00_00  

- TMS320F28379D/TMS320F280049C/TMS320F28P650
    - 库函数开发+图形化配置(Driver Lib + System Config)   
    - CCS20.20  
    - C2000Ware_5_05_00_00  
    - C2000Ware_DigitalPower_SDK_5_05_00_00  
    - C2000Ware_MotorControl_SDK_5_04_00_00 

### 硬件支持
- 立创EDA-PRO        
- Altium Designer 2024 

### 仿真支持
- Matlab 2024b
- Multisim 14.3
- Plece 4.7

## 文件结构
```
NUEDC
├── Code
│   ├── Control_Driver              控制环路库
│   └── Peripheral_Driver           底层驱动库
├── DataSheet                       数据手册
│   ├── DSP                         主控相关手册，按主控区分
│   │   ├── F28P650
│   │   ├── F28335
│   │   ├── F28379D
│   │   └── F280049C
│   ├── 仪器                        仪器说明书
│   └── 芯片                        芯片数据手册
├── PCB                             硬件工程
│   ├── AD_Projects                 Altium Designer 24 PCB工程
│   ├── LCEDA_Library               立创EDA库文件夹
│   └── LCEDA_Projects              立创EDA工程文件夹，现用模块工程
├── Projects                        软件手册，按主控区分
│   ├── F28P650
│   ├── F28335
│   ├── F28379D
│   └── F280049C
├── Question                         赛题集合
│   ├── 国赛                         历年国赛、省赛赛题
│   ├── 邀请赛                       历年邀请赛赛题
│   └── 综合测评                     历年综合测评题
├── Reference                       参考资料
│   ├── Related Articles            相关论文
│   ├── 参考指南                     自行编写的参考手册
│   ├── 设计工具                     官方设计工具
│   ├── 设计手册                     官方设计手册
│   └── 综合测评资料                 综合测评用资料
├── Simulate                        仿真文件    
│   ├── Matlab                      matlab仿真
│   │   ├── Question                赛题仿真
│   │   └── Topology                拓扑/环路仿真
│   ├── Multisim                    模拟环路仿真
│   └── Plecs                       Plecs仿真文件
└── Web                             Github Pages 静态网站文件
```

## 问题反馈
 - Github提交Issue
 - 电子设计协会论坛内，[2025年A题讲解贴](http://222.206.29.236:1003/forum.php?mod=viewthread&tid=42) **需要校园网**
 - 山东大学学生电子设计协会官方QQ号 **1345623115**  

## 贡献规则
[代码规范与贡献指南](https://github.com/vilesmeier/NUEDC/blob/main/CONTRIBUTING.md)  

## Acknowledgements
**Contributors**  
[@沙发上的大懒猫](https://github.com/vilesmeier).  

特别鸣谢：  
***山东大学电气工程学院 电力电子化能源系统实验室（MPEES）***  
***山东大学电工电子创新教育平台***  
**除此之外，还有许多学长/学姐在我们备赛期间给予了很多指导与帮助，在此一并表示感谢**  
