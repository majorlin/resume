# 个人简历

本项目为林明杰的个人简历 Latex 源码存放，同时包含效果图呈现，简历入口为 resume-zh_CN.tex， 修改自项目 [resume](https://github.com/billryan/resume/)，若不想本地手动编译可以将该源码打包至 zip 直接上传至 ShareLatex 进行在线编译与预览。

## 个人简介

**林明杰** - 系统软件总监 | MCU/SoC 系统软件架构 | 芯片验证 FPGA 原型 | 10+ 年半导体经验

(+86) 185-5008-6576 | linmingjie@foxmail.com

具备 10 年以上 MCU/SoC 芯片研发与系统软件经验，技术背景覆盖 FPGA 原型验证、芯片硅前/硅后验证、系统软件架构与自动化测试。

曾任职于恩智浦半导体，负责多款 MCU 芯片验证与原型开发；现任江苏云途半导体系统软件总监，主导 MCU 系统软件架构设计与团队建设，深度参与芯片产品定义、设计与验证。

兼具技术深度与管理经验，能够从芯片架构、软件系统、验证流程多个层面推动产品成功交付。

## 工作经历

### 江苏云途半导体有限公司 - 系统软件总监 (2020.7-至今)
- 负责公司嵌入式系统软件整体架构设计与研发管理，深度参与 MCU 产品定义、架构设计及功能验证
- 建立并持续优化系统软件开发流程，覆盖需求管理、设计评审、代码开发、集成验证及发布全流程
- 组建并管理系统软件团队，开展技术指导与评审，推动团队技术能力与工程效率持续提升
- 负责芯片 FPGA 验证及硅后（Post-Silicon）验证工作，支撑芯片功能、性能及稳定性验证
- 支持芯片及软件功能安全开发流程，配合功能安全需求分析、设计实现与验证活动
- 推动软件开发流程规范化与标准化，建立缺陷/问题追踪与闭环管理机制，提升软件质量与项目可控性

### 恩智浦半导体（NXP）| 飞思卡尔半导体 - 芯片测试工程师|芯片原型验证工程师 (2014.6-2020.7)
- 负责 MCU/SoC 芯片硅后（Post-Silicon）功能验证，覆盖数字 IP 与模拟 IP，搭建并维护芯片验证与测试环境
- 担任多个芯片项目验证负责人，负责验证任务分解、资源协调、进度管理及验证结果汇总与问题跟踪
- 参与芯片硅前（Pre-Silicon）验证工作，基于 FPGA 平台开展芯片原型验证及 IP 前期功能测试
- 负责芯片硅后模拟 IP 参数测试与特性验证，包括 ADC、DAC、CMP 及电源管理模块等
- 参与芯片前端验证与系统级功能验证，协助 SDK 与 ROM 软件开发及验证，熟悉完整芯片研发流程

## 项目经历

### 芯片产品定义和设计开发 (2020.7-至今)
- 结合市场需求，应用需求，技术趋势，竞争产品等多方面因素，制定芯片产品规划和路线图
- 参与芯片需求分析，芯片架构设计，芯片模块设计和验证
  - 对ARM内核有较深入的理解，能够调试和分析 ARM内核相关问题
  - 熟悉常用外设模块的设计和验证，如UART, SPI, I2C, GPIO, ADC, DAC, PWM等
  - 熟练使用EDA工具进行芯片设计和验证，如xrun, vcs, verdi, simvision, vivado, synplify等

### 芯片设计开发验证系统搭建 (2020.7-2021.12)
- 制定芯片设计开发验证流程，基于Python脚本实现芯片验证平台环境搭建和回归测试系统
- 开发芯片IP代码管理系统，实现芯片IP代码的版本管理和变更跟踪
- 了解芯片开发和设计全流程，协助芯片设计团队进行芯片架构设计和模块设计

### 芯片设计开发与验证 (2020.7-至今)
- 参与芯片RoadMap制定，芯片需求分析，芯片架构设计，芯片模块设计和验证
- 负责芯片FPGA验证及硅后验证工作，确保芯片功能和性能符合设计要求
  - 负责项目包含YTM321B1Lx, YTM32B1Mx, YTM32B1Hx等MCU芯片的设计开发和验证工作
  - 为芯片规格参数提供数据支持，对测试结果进行分析和问题定位。
  - 对芯片应用、芯片设计、芯片测试等有深入了解，能够从多个角度对芯片开发过程提出改善建议

### 基于FPGA的ASIC原型系统验证 (2016.11-2020.7)
- 该项目主要是将MCU的ASIC设计移植到 FPGA 上实现，可以在流片前期实现对数字IP和系统集成的验证，提供软件和ROM的早期开发平台，缩短ASIC的研发周期。
  - 优化FPGA时钟资源，对ASIC时钟树进行必要的修改
  - FPGA和ASIC仿真环境做相应的修改，开发流程标准化制定
- FPGA实现之后的板级调试，定位FPGA原型设计中的问题，结合功能仿真和后仿真实现对FPGA原型设计中的问题定位，修复FPGA中的时序问题。
- 开发FPGA配套的升级脚本，提高ROM验证效率

### 基于Python和LabVIEW的自动化测试系统开发 (2014.11-2020.7)
- 该项目主要是为了提高MCU测试效率而开发的一套自动测试系统, 系统分为自动测试和结果收集展示两大部分，其中自动测试部分可以依据测试代码产生各种测试激励，并控制常见的实验室仪器(如示波器，信号发生器，电源等等)对结果进行测量，并根据测试日志判断测试结果;结果收集部分可以将测试日志保存到数据库，并对测试结果进行分析汇总和网页展示。
  - 基于Python和串口的命令交互系统，可以实现测试流程控制，命令延时分发，命令结果汇总
  - 基于串口命令的仪器控制，可以实现MCU对电源，示波器，万用表，信号发生器的控制
  - 测试结果汇总，数据库存储，基于浏览器网页的测试结果展示和统计
- 支持测试过程回溯，可以从网页下载测试过程的关键数据
- 支持自动测试，可以有效的提高芯片测试效率

### 芯片模拟参数验证 (2014.11-2020.7)
- 负责实现芯片模拟参数验证，为芯片数据手册提供数据支持，基于LabVIEW和NI的测试仪器对芯片的功耗，ADC的静态参数和动态参数，DAC的参数，ACMP的模拟参数进行测试。对芯片进行高低温参数测试
  - 芯片功耗测试包含芯片运行模式和低功耗模式下（高低温）的电压电流功耗测试
  - 芯片的高低温测试主要包含芯片稳定性和芯片功能缺陷复现

## 教育经历

### 中国科学院大学
光学工程, 硕士研究生 (2011.9 - 2014.7)

### 武汉理工大学
通信工程, 工学学士 (2007.9 - 2011.7)

## 技术能力

- MCU / SoC 系统软件架构设计，熟悉 ARM Cortex-M 内核与调试
- 外设与驱动：FlexCAN / LIN / ENET / SENT / SAI / UART / SPI / I2C / GPIO / ADC / PWM
- FPGA 原型验证与芯片硅前 / 硅后验证流程
- 自动化测试与工具链：Python / LabVIEW / CI / 回归测试
- EDA 工具：Vivado / Synopsys VCS / Verdi / SimVision / Xrun
- 软件流程与质量体系：版本管理、缺陷管理、代码评审
- AUTOSAR / MCAL 开发与验证经验
- 技术团队管理与跨部门协作

## 项目说明

一个优雅的 \LaTeX\ 简历模板, 使用 \XeLaTeX\ 编译, 因为受不了古老的`res`和不太适合作为一页纸简历的`moderncv`, 遂自己动手写了这个模板， 受以下项目启发：

- [zachscrivena/simple-resume-cv](https://github.com/zachscrivena/simple-resume-cv)
- [res](https://www.ctan.org/pkg/res)
- [JianXu's CV](http://www.jianxu.net/en/files/JianXu_CV.pdf)
- [paciorek's CV/Resume template](http://www.stat.berkeley.edu/~paciorek/computingTips/Latex_template_creating_CV_.html)
- [How to write a LaTeX class file and design your own CV (Part 1) - ShareLaTeX](https://www.sharelatex.com/blog/2011/03/27/how-to-write-a-latex-class-file-and-design-your-own-cv.html)

*注：由于使用到 `fontspec` 包，编译器需选择 XeLaTeX。*

## 特性

- 极其容易定制和扩展 (`res`模板中枪倒地...)
- 完善的 Unicode 字体支持, 因为用的是 \XeLaTeX\ 嘛
- 完美的中文支持，使用 Adobefonts
- 支持 FontAwesome 4.3.0 (目前还不支持使用别名)

### 效果输出

![resume-zh_CN.png](./resume.preview.png)

## 使用方法

1. OverLeaf 在线编译
2. 使用较新的 \LaTeX\ 发行版在本地计算机编译

如果确定只需要中文简历的话单独克隆 `master` 分支即可, 需要注意的是该分支包含 Adobe 的宋楷黑仿四套中文字体，压缩包约为37MB。[下载地址](https://github.com/hijiangtao/resume/releases)

```
git clone https://github.com/hijiangtao/resume.git --branch master --depth 1 --single-branch <folder>
```

如果系统已确定安装有 Adobe 的四套中文字型，在文档的开始处使用包`zh_CN-Adobefonts_internal`, 如果没有安装则使用包`zh_CN-Adobefonts_external`, 在 ShareLaTeX 上编译需要使用包`zh_CN-Adobefonts_external`.

其他具体使用可参考给出的范例，都是极其简单易懂的宏，建议先看看 [How to write a LaTeX class file and design your own CV (Part 1) - ShareLaTeX](https://www.sharelatex.com/blog/2011/03/27/how-to-write-a-latex-class-file-and-design-your-own-cv.html) 和 [How to write a LaTeX class file and design your own CV (Part 2) - ShareLaTeX](https://www.sharelatex.com/blog/2013/06/28/how-to-write-a-latex-class-file-and-design-your-own-cv.html) 了解下该模板的简单背景，下面就一些新定义的宏做简要介绍。

### 宏

- `\name`: 姓名
- `\contactInfo`: 联系信息, 需要三项信息，分别是{邮箱}{手机号}{个人主页}
- `\basicContactInfo`: 简要的联系信息, 需要 项信息, 分别是{邮箱}{手机号}, 没有个人主页的用这个
- `\section`: 用于分节, 如教育背景, 实习/项目经历等
- `\subsection`: 用于小节标题, 无日期选项
- `\datedsubsection`: 用于小节标题, 简历中使用最广，第二项为时间区间，自动右对齐
- `\itemize`: 清单列表，简历中应用最广
- `\enumerate`: 枚举列表，数字标号

### FontAwesome

首先在 [Font Awesome Icons](http://fortawesome.github.io/Font-Awesome/icons/) 上选中自己想使用的图标(暂不支持 alias)，然后在 [fontawesome.sty](https://github.com/billryan/resume/blob/zh_CN/fontawesome.sty) 中找到相应的宏, 将其作为普通文本一样使用。

其他的可以自行参考相应 cls 和 tex 文件。

## License

[The MIT License (MIT)](http://opensource.org/licenses/MIT)

Copyrighted fonts are not subjected to this License.