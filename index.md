# 个人简历
## <font color="#267CB9"> 教育背景 </font>
* 硕士（2018.9-今）
中科院信息工程研究所国家重点实验室（保送）   计算机体系结构安全   导师：宋威 副研究员
* 学士（2014.9-2018.7）
中国矿业大学 电子信息科学与技术

## <font color="#267CB9"> 项目经历 </font>
**2019.2-至今   基于RISC-V平台的缓存侧信道攻击的研究和检测  中科院信息工程研究所**

> 研究缓存侧信道攻击的访存模式，实时收取数据并分析，以监测缓存侧信道攻击

* **调研**: 分类、总结现有的缓存侧信道攻击及防御方法
* **搭建专用仿真平台**：基于RISC-V指令集模拟器Spike，集成统计友好的缓存模型。移植Linux-5.3，编译Native工具链，配置多核攻击执行环境。（并编写移植linux教程发布至[cnrv](cnrv.io/articles/spike-linux)）
* **移植攻击**：移植攻击到Spike模拟的Linux平台，并且成功复现攻击。 
* **统计**：提取真实攻击在缓存中的行为，分析侧信道攻击存在的共同缓存访问模式。

**2018.3-2019.2   CPU安全测试集内存错误部分设计开发  中科院信息工程研究所**

> 参与设计CPU安全测试集，为研究人员提供一个量化防御策略安全程度的测试工具。其中，我独立设计、开发测试集中测试内存错误的部分

* **调研**: 调研Linux和体系结构中内存错误漏洞。复现典型CVE、各种堆溢出利用；分析已有Benchmark攻击维度和评估方法；总结内存攻击模型，分析已有防御机制。
* **设计**: 根据内存攻击模型，首次提出分层、每层每测试用例单独调用、快速收敛、针对漏洞测试的测试集框架。
* **开发**: 实现测试集，移植测试集至多平台（X86、ARM、RISC-V）。
* **论文**: 作为作者之一撰写论文《CPU Security Benchmark》发表于CCS 2018 Co-Located Workshop，SCI, EI检索。

**2017.7-2017.9   可穿戴设备室内惯性导航系统开发  中国科学院电子学研究所苏州研究院   嵌入式软件工程师（实习）**

* 在STM32平台上，使用九轴惯性传感器统计步数、使用三轴磁力计获取稳定航向角，通过WiFi网络TCP实时传输数据到达上位机。在上位机上对数据进行解算、滤波处理、校准，对航向角误差建模，得到较准确的航向角。最终实现在上位机上实时绘制行走轨迹。

## <font color="#267CB9"> 所获奖项及荣誉 </font>
* 2019年获得中国科学院大学三好学生称号，硕士阶段各科成绩均为良好及以上，本科阶段专业成绩排名4/116；
* 2018年获得中国矿业大学优秀毕业论文；
* 2017年中国机器人大赛（robotcup）三等奖； 
* 2014-2016年连续3年获得校级一等奖学金，同时连续3年被评为校级优秀学生，主持参与多项大创项目；
* 2015-2016：在学生会任职体育部部长,任职期间组织学院运动会、“校园齐三走”活动等等。

## <font color="#267CB9"> 个人技能 </font>
* 指令集及处理器架构：熟悉缓存、计算机体系结构、RISC-V指令集；
* 操作系统：熟悉bootloader，和操作系统初始化启动阶段。熟悉Linux开发环境；
* CPU安全：熟悉缓存侧信道，熟悉软件漏洞：缓冲区溢出漏洞、格式化字符串漏洞、控制流劫持、代码重用等；
* 编程语言：了解且掌握C++、python、汇编等，熟悉C++设计模式和编程调试技巧；
* 工具：掌握git，掌握GDB，掌握常用的脚本使用及编写，例如Makefile、shell等；
* 英语：通过CET6级测试。
