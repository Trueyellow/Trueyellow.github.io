# 个人信息

- 黄凯翔/男/   1995/07/15
- 硕士: Rutgers University, the state University of New Jersey -- Computer Engineering **GPA: 4.0 / 4.0**
- 本科: 电子科技大学--电子科学与技术专业 **GPA: 3.4 / 4.0**
- Github: [Trueyellow](https://github.com/Trueyellow)
- 期望职位: 计算机视觉，深度学习工程师
- 手机: +1 (908)-848-9097 (美国) / 18916887495（中国）
- Email: hkx444@live.com
- 微信号: trueyellow
# 项目经历

### 基于cycleGAN的声音情绪引导的面部图片生成网络

**课程项目** ：Pattern Recognition (17年9月--17年12月)

在这个课程项目中，我们小组提出并实现了一个基于演讲人声音的情绪的脸部生成网络，我们提出了一个 Speech Emotion Restricted cycleGAN，并且引入了预训练的CNN网络加强我们的Discriminator。身为课程项目组组长，负责根据老师的项目需求，查找阅读相关文献论文，提出项目并且分工，安排项目时间，并且最后负责项目讲解，展示。在编程方面主要负责Pre-trained 的 emotion-level CNN以及CycleGAN网络的主体搭建与训练。在这个项目中，我第一次接触到并且实现了GAN 网络，在网络的训练方面，提出了使用预训练的脸部情绪CNN来稳定GAN网络容易崩坏的训练过程。

### Attention Network and DQN Based Tuning for Online Activity Recognition

**实验室项目** ：IJCAI-2018

通过attention结构加上RL类型的tuning，实现实时行为识别系统。通过在普通的CNN-LSTM的视频识别网络中加入Attention模块，提升网络对嘈杂环境中的行为识别能力。再通过基于强化学习的Tuning模型，使得模型忽略数据集中被误标的LABEL的影响，达到一个对整体结构Fine-tuning的效果。在这个项目中，我参与模型的搭建，训练，和论文的修改环节，论文已提交：***IJCAI* -18会议**

### Human Conversation Analysis Using Attentive Multimodal Networks with Hierarchical Encoder-Decoder

**实验室项目** ：ACM-Multimedia 2018

通过声音信号，文本信号和计算机视觉信号，构建一个人物对话情绪识别检测网络。整个网络基于word级别的信息对齐，decoder成feature vector 后，再通过一个带modality attention 的fusion 网络将3个branch的信息融合，通过最后的hierarchical的带temporal attention 的encoder-decoder 将信息提取成我们想要的结果。在这个项目中，我负责CV信号的feature extraction，fusion网络以及hierarchical encoder-decoder的编写以及整体模型的训练，论文的修改。论文已提交：***ACM Multi-media* 18会议**

### 肺部CT图像癌症及肺部小结节识别

**个人项目**： Kaggle Data Bowl 2017(17年1月--17年4月)

这是一个我了解机器学习以及深度学习的课余项目，我一直认为参与到真实的项目或竞赛之中可以加强对机器学习模型的理解与应用。这是一个对大批量肺部CT图片分析的项目，所以使用的数据量特别大，涉及到医疗图像预处理，可视化，模型分析搭建的项目。刚接手这个项目时，我在图像预处理过后从2D CNN尝试起，但是发现整体的效果特别差，因为样本数目虽然多，但很多都是一个肺部的不同位置不同角度的扫描图片，所以尝试通过位置信息，将属于同一个肺部的2DCT图片结合生成3D图片，然后使用3D CNN做整个肺部图片的特征分析与识别。由于是课余项目，且由于CT图片较大(平均一个2D图片在60MB左右，整个数据集有7000张左右2D图片)，需要较高成本的硬件支持，所以最后只是做了一些比较简单的CNN模型，结果不是特别理想，测试结果排在了的排行榜前40%左右。

### 基于CNN与Computer Vision 特征的手写识别

**课程项目** ：Capstone Design (17年1月--17年4月)

英文字母的手写识别。首先通过CV的feature定位到手写字符的位置，然后采用不同大小的滑动窗对单词进行切割并送入字母级别的CNN中，获得字母层面的预测。发现经常会有一些连写字符的识别特别差，后又将输出接入一个LSTM网络进行词语级别的纠错。在这个项目中，我主要负责CNN与LSTM网络的搭建与训练，整合与数据预处理。最后我们项目参与了学院的展示，并且与业界人士以及老师们讲解讨论了项目的可以后续改进的地方与不足。

# 企业/实验室经历

### 电通安吉斯（上海）集团公司 Dentsu Aegis Network Ltd

**自动化社交网络分析系统** (17年5月--17年8月 暑期实习)

参与了社交图片分析系统的讨论与构建，我主要负责了真实与虚拟图片，场景识别和食物识别三个部分的子分类器。通过查阅论文文献，使用了效果较好且参数较少Inception Net，搭建的网络作为分析系统的重要部分merge到主系统中。通过这个系统，公司的策划团队可以自动化分析社交平台上用户对某类产品的反馈，针对性的制定相关活动或者给予客户品牌建议，从而提高客户品牌的口碑，制定发展蓝图。



### Multimedia Image Processing Lab, Rutgers University

**基于深度强化学习以及注意力网络的实时行为识别**  (17年9月--至今 助理研究员)

我们实验室主要关注手术室的基于器械传感器，图像信息，景深图片，声音信息的手术行为识别。我在其中主要负责模型编程实现，网络训练以及参与项目讨论，论文修改。在最近的这个项目中，我们 提出了基于注意力网络以及多种类型数据的行为识别，并且采用了深度强化网络以及异步训练模式，优化生成的注意力网络，从而达到加强相关特征的效果。

期间发表论文:

**Attention Network and DQN Based Tuning for Online Activity Recognition**（已提交 ***IJCAI***  18会议）

**Deep Reinforcement Learning for Concurrent Activity Recognition** （已提交**Ubicomp** 18会议）

**Human Conversation Analysis Using Attentive Multimodal Networks with Hierarchical Encoder-Decoder**（已提交**ACMMM** 18会议）

# 技能清单

- 编程语言：C/C++, Python, Java
- 熟练使用机器学习框架：Sklearn, Tensorflow, Keras
- 并行计算架构：ISPC, CUDA, Pthread
- 操作系统：Windows, Linux
