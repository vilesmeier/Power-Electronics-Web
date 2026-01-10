# 硬件工程
## 简介
本选项卡主要介绍资料库内的硬件PCB工程部分  
**后续硬件开发主要以Altium Designer 24为主**  

|EDA软件|更新状态|
|:---:|:---:|
|立创EDA-PRO        |停止更新|
|Altium Designer 24 |更新中|

## 文件结构
```
├── PCB                         硬件工程
│   ├── AD_Projects             Altium Designer 24 PCB工程
│   ├── LCEDA_Library           立创EDA库文件夹
│   └── LCEDA_Projects          立创EDA工程文件夹，现用模块工程
```

## /AD_Projects
### /Auxiliary_power_LM5164
非隔离辅助电源，LM5164  
6-100V输入，转±12V-1A/5V-1A  

### /Common_Files
AD通用文件，库文件需要AD设置内导入  
.outjob文件需要每个工程单独引入  
 -- project选项卡，右键，添加已有文件  

### /Control_Card_28P650
F28P650DKXPTP控制卡  

### /Control_Card_280049C
F280049CPTP控制卡  

### /Power_Stage_1PH_Serial_3_Level
单相级联三电平H桥

### /Power_Stage_3PH_Serial_3_Level
三相级联三电平H桥

### /Sample_Board_H_Bridge
单相/三相H桥通用采样小板  

## /LCDEA_Library
立创EDA的自定义器件与封装  
部分常用复用模块原理图与PCB  

## /LCDEA_Projects
立创EDA工程  
