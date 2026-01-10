# 仿真
## 简介
本文件夹包含Matlab/Multisim/Plesc仿真  

|软件|版本|
|:---:|:---:|
|Matlab|Matlab 2024b|
|Multisim|Multisim 14.3|
|Plece|Plece 4.7|

## 文件结构
```
├── Simulate                    仿真文件    
│   ├── Matlab                  matlab仿真
│   │   ├── Question            赛题仿真
│   │   └── Topology            拓扑/环路仿真
│   ├── Multisim                模拟环路仿真
│   └── Plecs                   Plecs仿真文件
```


## /Matlab
- 控制环路仿真
- **控制环路仿真以Matlab为主**

### /Topology
- 针对于拓扑/控制环路的仿真
- 按类别区分不同文件夹

### /Question
- 针对于历年真题的仿真
- 按**Ans_年份 题目**的格式命名  

### Subsystem.slx
- 常用自定义模块打包
- 包括 调制器/常用算法

## /Multisim
- 模拟环路仿真
- 仿真内容见文件命名

## /Plecs
- 以算法验证为主
