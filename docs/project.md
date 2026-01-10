# 代码工程
## 简介
本文件夹内主要包括备赛/25年国赛期间的代码工程  

## 文件结构
```
├── Projects                        软件手册，按主控区分
│   ├── F28P650
│   ├── F28335
│   ├── F28379D
│   └── F280049C
```
## /28335
### /3ph_Inverter
#### /3ph_Current_source_inverter
三相电流源逆变器  

#### /3ph_inverter_offgrid_para
三相电压源逆变器，并机  

#### /3ph_Voltage_source_inverter
三相电压源逆变器，单机  

#### /SVPWM
SVPWM调制，闭环  

### /22A
#### /PQ
PQ控制，实现指定功率因数  

#### /Rectifier_10k
单相PWM整流器  
10KHz桥臂输出，等效20K开关频率  

#### /Rectifier_20k
单相PWM整流器  
20KHz桥臂输出，等效40K开关频率  

#### /SVG
静止无功发生器，PQ控制  

### /23A
#### /Master_new
PR电压环+P电流环（电流前馈）  
支持单机/并机/离网/并网/均功  

### /24B
2024年B题 单项功率分析仪 代码  

### /24Invitation
#### /Solar_sim
24年邀请赛，模拟内阻  

### /25A
2025年电赛A题 能量回馈的变流器负载测试装置  
以最新版V13为准  

### /DCDC
#### /Buck
Buck电路，单电压环  

#### /Boost
Boost电路，单电压环  

#### /Four_Switch_Buck_Boost
四开关升降压电路，单电压环  
支持buck/boost/buck-boost模式  

#### /MPPT
最大功率点跟踪  
支持电导增量法/扰动观测法  

### /Test_Projects
模式测试工程  

### /VSG
虚拟同步机  
**暂时不可用**

