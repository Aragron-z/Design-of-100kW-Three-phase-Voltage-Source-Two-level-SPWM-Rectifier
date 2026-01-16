# Design-of-100kW-Three-phase-Voltage-Source-Two-level-SPWM-Rectifier
## ⚙项目描述：完成一款100kW/600V输出三相高功率因数整流器的全流程设计与matlab/simulink平台和StarSim NI 半实物仿真平台的仿真验证，拓扑选型、参数包括计算和闭环控制算法实现与调试。

## 🛠技术指标 
1）功率因数：0.95

2）输出功率100KW

3）三相输入电压380V

4）整流直流电压：600V

5）开关频率6kHz

6）直流侧带电阻性负载

7）整流直流纹波小于3%

8）交流侧电流谐波iTHD小于3%
## 🖼️系统原理图
功率电路拓扑图：

<img width="414" height="188" alt="image" src="https://github.com/user-attachments/assets/86f2d33c-ad12-47bd-8ebf-9c46450a4729" />

控制电路结构框图：

<img width="415" height="196" alt="image" src="https://github.com/user-attachments/assets/fcfec094-dea2-4480-a8be-73f3f29e8a1e" />

matlab simulink总体仿真模型图：

<img width="415" height="357" alt="image" src="https://github.com/user-attachments/assets/ae4bbb63-cb9f-48c0-9943-b573182a5592" />


## 📕文件说明
SPWM.slx为matlab simulink仿真文件，使用matlab R2025a以及更高版本的matlab打开运行，通过各示波器即可查看运行结果

100kW三相电压型两电平SPWM整流器设计.docx为整个工程的详细说明文档，涵盖系统设计原理，各参数计算以及仿真的结果分析与总结

## 说明 
本项目为华中科技大学电力电子技术课程设计项目，仅作交流学习使用
