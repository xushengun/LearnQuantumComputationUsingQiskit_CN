# IBM 开源在线教程
## Learn Quantum Computation Using Qiskit 中文版

## 如有任何错误请联系本中文版译者！
## 联系方式如下：
### 中文版译者:徐柳青
### 电话:18616020096(Wechat)
### 电子邮件:45045590@qq.com
### Github:https://github.com/xushengun/
### 日期:20201016

前言
来自 Qiskit 社区团队的问候!本教程是 Qiskit 的大学量子算法/计 算课程的补充:
1. 量子算法背后的数学
2. 当今非容错量子设备的细节
3. 用 Qiskit 编写代码并在 IBM 的云量子 系统上实现量子算法

关于本教程
这是一个免费的数字版教程，在使用 Qiskit SDK 的同时通过本教程教授量子计算的概念。

QisKit Textbook的联系方式
如果您对本教程有任何疑问或建议，或者想将其纳入您的课程表，请联系 Frank Harkins(Francis.Harkins@ibm.com)。本着开放源代码的精神，在本教程的[GitHub](https://github.com/qiskit-community/qiskit-textbook)存储库中欢迎任何章节的贡献。

贡献者
本教程是多人工作的结果。如果在工作中使用本教程，请引用 bib 文件或直接 引用:
Abraham Asfaw, Luciano Bello, Yael Ben-Haim, Sergey Bravyi, Lauren Capelluto, Almudena Carrera Vazquez, Jack Ceroni, Richard Chen, Albert Frisch, Jay Gambetta, Shelly Garion, Leron Gil, Salvador De La Puente Gonzalez, Francis Harkins, Takashi Imamichi, David McKay, Antonio Mezzacapo, Zlatko Minev, Ramis Movassagh, Giacomo Nannicni, Paul Nation, Anna Phan, Marco Pistoia, Arthur Rattew, Joachim Schaefer, Javad Shabani, John Smolin, Kristan Temme, Madeleine Tod, Stephen Wood, James Wootton.

什么是量子?
“量子物理学”是一个被广泛使用但却很少被人理解的术语。它是一种数学模 型，最初用于描述实验室中微小物体的行为，其揭露了先前“经典”物理学理
论的缺陷。量子理论解释了这种行为，并为我们提供了一个更完整的宇宙图
像。人们已经意识到可以利用这种以前无法解释的行为来进行某些之前认为不
可能的计算。人们将其称之为量子计算。
量子计算是您涉足量子物理学的完美方式。量子计算将量子物理学的核心概念 提炼为最简单的形式，同时剥离了物理世界的复杂性。本文将带您去探索和理
解一些奇怪的量子现象，并让您对什么是“量子”有一个初步的了解。

#### 简而言之，量子理论是包含负数的概率论。
