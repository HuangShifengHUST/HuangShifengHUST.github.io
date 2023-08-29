```yaml
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:   - /about/  - /about.html
```

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# About Me

Shifeng Huang (黄石峰, E-mail: [shifeng@hust.edu.cn](mailto:shifeng@hust.edu.cn)，Phone: 0086+13476149515) focuses on the research of industrial robots, and aims to bridge the gap between theoretical research and commercial engineering applications. Dr. Huang serves as the Deputy Chief Engineer at the Foshan Institute of Intelligent Equipment Technology and the Director of the Key Technology Laboratory at the same institute. During his doctoral studies, he received a solid engineering education and was mentored by Prof. [Jihong Chen](http://mse.hust.edu.cn/info/1145/1434.htm) (Chairman of Huazhong Numerical Control Co., Ltd.), Prof. [Zhihong Zhu](http://mse.hust.edu.cn/info/1145/1422.htm) (Chief Engineer of Huazhong Numerical Control Co., Ltd.), and Researcher [Huicheng Zhou](http://mse.hust.edu.cn/info/1145/1432.htm) (Chief Expert at the Central Research Institute of Huazhong Numerical Control Co., Ltd.). Dr. Huang is also supervised by Prof. [Jianwei Zhang](https://baike.baidu.com/item/%E5%BC%A0%E5%BB%BA%E4%BC%9F/22043671?fr=ge_ala) (Academician of the National Academy of Engineering Sciences in German).

# 🔥 Research Interests

- **Applications**
  
  - Industrial robots
  
  - Collaborative robots (cobots)

- **Subjects**
  
  - Dynamics modeling and identification
  
  - Calibration & compensation of kinematic errors
  
  - Time-optimal trajectory planning (TOTP) and continuous short line segments real-time interpolation
  
  - physical human–robot interaction (pHRI)
  
  - Servo motion control of trajectory tracking
  
  - Vibration suppression
  
  - Robotic manufacturing

# 🏭 Engineering Practice

**总体介绍：** 所有研究工作都围绕着华数机器人展开，积极践行“学-研-产”行动方针。作为国家数控系统工程技术研究中心机器人课题组的大师兄，自觉形成了机器人课题组的青年带头人。博士期间，以华数机器人为依托，始终围绕“高速”、“高精”和“物理人机交互”等关键技术目标，身体力行并带动课题组研究生，在与华数机器人工程师联合攻关下，开展了多项富有工程实际价值的科研课题，研究成果获得华数机器人工程师一致认可，促进国产工业及协作机器人高水平发展。

**补充说明：**

- 部分研究成果出于商业保密不发表学术论文；

- 学术论文展现的更多是一种研究思想。从理论演算，到实验室级的证实，再到做出市场认可的商用工业产品，有着多方面因素的影响。因此学术论文往往不能简单视为产品的最终技术方案，需要科学对待；

- 部分工程上实现的好效果，其实就是一层窗户纸，捅破了其实就那么回事。产品研发以市场和问题为导向，以“管用”、“好用”、“耐用”为前提，因此“一味”谈脱离市场实际所需的创新略显矫情。

**2017年-2023年** 机器人动力学建模与辨识

- 责任定位：博士研究课题，项目主导，负责所有理论研究和部分工程开发。

- 工程效果：实现了同型号不同本体机器人的动力学参数一致性辨识效果，解决了多机器人模型迁移难题，切实为量产机器人的动力学模型部署提供了成套化解决方案；形成了关节传动部件耦合的动力学建模-辨识体系化解决方案；突破了机器人任意姿态安装的动力学模型辨识难题；建立了经典串联机器人、带局部并联结构（例如，重力平衡系统：平衡缸、平行四边形系统、拉升弹簧等）的串联机器人动力学建模-辨识的规范策略；满足任意姿态安装条件下，狭小作业空间约束的负载辨识，与ABB、iiwa等国际知名品牌机器人的负载辨识功能相比，研究成果不受奇异构型制约，且可实现辨识的最优运动激励，能高精度识别负载的完整惯性参数。

- 学术成果：在IEEE TMECH上发表一篇扩展动力学参数集的研究论文；出于商业保密的问题，仅部分成果允许发表。

**2016年-2017年** 工业机器人末端执行器TCP标定研究

- 责任定位：本人机器人研究生涯的第一项任务，属本人独立研究。

- 工程效果：实现了工具坐标系的最优构型标定。

- 学术成果：在《机械工程学报》期刊发表高水平论文一篇，荣获2019年度中国专利优秀奖。

**2017年-2022年** 连续微小线段插补

- 责任定位：出于实际需求，从原有动力学研究被抽调出来研究攻关小线段插补技术。本人在该课题早起阶段作为独立研究者，而在打通基础版本的小线段插补功能后，于2019年转交给其他工程师开发和深入，并指导了两名硕士研究生，分别开展了连续小线段插补与时间最优轨迹规划课题研究。

- 工程效果：实现了机器人复杂轨迹加工中的动态前瞻多轴联动实时插补，考虑了运动中的几何误差约束、运动学约束、关节电机及减速机的动力学约束。

- 学术成果：部分成果形成指导学生的硕士学位论文。

**2018年-2020年** 协作机器人物理人机交互-拖动示教

- 责任定位：团队中理论研究负责人。

- 工程效果：分别实现了无关节力矩传感器的零力拖动、末端力矩传感器模式下的灵敏拖动、驱动器位置模式下的阻抗柔顺拖动、驱动器电流模式下的阻抗柔顺拖动。

- 学术成果：部分已经是机器人圈内的公开技术，部分商业机密未发表。

**2019年-2021年** 协作机器人物理人机交互-碰撞安全检测

- 责任定位：项目中的理论研究先行者，后来转交华数机器人工程师，并指导一名硕士研究生作为研究生课题。

- 工程效果：当前机器人社区广泛应用的基于广义动量观测器GMO（iiwa、Franka等机器人普遍基于该技术）的碰撞安全检测技术受限于有限带宽，对硬碰撞响应慢，而基于高通滤波器的检测技术无法有效捕捉准静态接触行为。所诉缺陷在自研的BICom碰撞检测技术框架下得以有效解决，其兼具高灵敏性的软/硬碰撞统一化检测能力。此外，设计的窗检测器克服了经典防误报措施引起的两类常见缺陷：检测迟延和检测假阴性。

- 学术成果：在IEEE TMECH上发表一篇BICom技术的研究论文、在国际会议ICIRA上发表一篇碰撞检测与响应的论文。

**2018年-2019年** 工业机器人磨抛加工中的恒力跟踪控制

- 责任定位：指导课题组硕士生开展课题研究。

- 工程效果：实现了打磨头接触工件瞬态时的突变冲击力，达到了高精度磨抛目标接触力跟踪效果。

- 学术成果：在IEEE ICCAR国际会议上发表论文，获得“BEST PRESENTATION”奖。

**2020年-2023年** 高精度伺服控制技术

- 责任定位：作为项目团队高精度伺服控制技术算法研究的带头人、先行者。

- 工程效果：实现了伺服参数的解析化参数整定，对动力学模型的不确定性有大范围鲁棒性，同一套伺服参数能有效适应不同负载质量等级，实现位置跟踪误差的指数收敛。

- 学术成果：商业机密。

**2020年-2022年** 工业机器人运动学参数标定技术

- 责任定位：指导课题组硕士生开展课题研究，在研究初期为团队硕士学生提供标定算法基本框架，并在研究过程中指导和提升标定算法。

- 工程效果：形成了标定构型选优及多工具坐标系快速标定解决方案，开发了机器人运动学参数标定软件一套。

- 学术成果：指导完成硕士学位论文。

**2021年-2023年** 工业机器人振动抑制技术

- 责任定位：指导课题组硕士生开展课题研究，本人在课题中定方向，确定合适技术路线。

- 工程效果：开发了输入整形和迭代学习控制算法，它们分别适用于机器人不同的振动抑制场景。典型地，输入整形需要已知被控振动系统的固有频率，而迭代学习适用于具有重复特征的加工应用。

- 学术成果：指导两名硕士生形成了以输入整形技术，迭代学习技术的学位论文，还有一名在读研究生，形成了具有普适抑振效果的“扭矩微分补偿”研究成果（正在投稿）。

# 🎓 Educations

![sym](images/HUST.png)

- 2016.09 - 2023.09, Doctoral student
  
  Major: Mechanical engineering

National Center of Technology Innovation for Intelligent Design and Numerical Control (NCTI-IDNC), School of Mechanical Science & Engineering

Huazhong University of Science and Technology, Wuhan, China

![sym](images/HUST.png)

- 2015.09-2016.09, Master's student
  
  Major: Mechanical and electronic engineering

National Numerical Control System Engineering Research Center, School of Mechanical Science & Engineering

Huazhong University of Science and Technology, Wuhan, China

![sym](images/CSU.png)

- 2011.09-2015.09, Undergraduate student
  
  Major: Mechanical design, manufacturing, and automation

Advanced Engineering Talent Experimental Class, School of Mechatronics Engineering

Central South University, Changsha, China

# 🎖 Honors

- *2022* Guangdong Provincial Mechanical Industry Science and Technology Award, First Prize (5/15). (2022年荣获广东省机械工业科学技术奖励一等奖，排名第5)

- *2022* Guangdong Provincial Society of Mechanical Engineering Science and Technology Award, First Prize (5/15). (2022年荣获广东省机械工程学会科学技术奖励一等奖，排名第5)

- *2020* "China Patent Excellence Award" from the National Intellectual Property Administration of China (2/5), Award-Winning Patent: A Method for TCP Calibration of Industrial Robots. (2020 年入选中国国家知识产权局“中国专利优秀奖”，获奖专利：一种工业机器人 TCP 标定方法，排名第2)

- *2020* "Best Presentation award" at the IEEE 6th International Conference on Control, Automation and Robotics. Winning Work: Target Force Tracking and Automatic Contour Surface Processing in Industrial Robot Grinding

- *2020* "Special Prize" in the 1st Science and Technology Essay Contest organized by the Foshan Institute of Intelligent Equipment Technology (Theme: Fundamental Research on Factors Influencing Industrial Robot Performance). Winning work: Several Key Issues of Industrial Robot Controller: An Interesting Insight. (2020 年荣获由佛山智能装备技术研究院主办的第1届科技征文大赛特等奖，大赛主题：影响工业机器人性能的基础问题研究，获奖作品：从趣谈控制，到论工业机器人中Controller 的若干问题)

- *2018* “Outstanding Contribution Award” from the Foshan Institute of Intelligent Equipment Technology. (2018 年荣获佛山智能装备技术研究院“突出贡献奖”)

# 📖 Services

- IEEE Transactions on Industrial Electronics (TIE): Reviewer
- IEEE Robotics and Automation Letters (RA-L): Reviewer
- IEEE International Conference on Robotics and Automation (ICRA): Reviewer

# 💬 Invited Talks

- *2023*:   第四届中国机器人学术年会，报告：重力场自适应的机器人扩展动力学参数集与稳健混合建模：机理+学习 [[Poster]](/pdf/2023ZGJQRXSNH.pdf)
- *2022:*  IEEE 14th Workshop on Active Disturbance Rejection Control. Topic: Challenges and Considerings on Motion Control of Industrial Robots: An Engineering Pespective [[Link]](https://mp.weixin.qq.com/s/SvmoTYgqF9-4HmZ_sUn92w)
- *2021:*  The 14th International Conference on Intelligent (ICIRA). Topic: Research on Collision Detection and Collision Reaction of Collaborative Robots [[Poster]](/pdf/2021ICIRAPoster.pdf)
- *2020:*  The 6th International Conference on Control, Automation and Robotics (ICCAR). Topic: Target Force Tracking and Automatic Contour Surface Processing in Industrial Robot Grinding [[Certification]](/pdf/2020-ICCAR-Best-Presentation-Award.pdf)

# 📝 Papers

### 2023

JMS 2023 (TOP)

![sym](images/JMS_2023_FIG1.jpg)

- In-situ fault diagnosis for the harmonic reducer of industrial robots via multi-scale mixed convolutional neural networks

He Yiming, Chen Jihong, Zhou Xing and **Huang Shifeng (通讯作者)**. Journal of Manufacturing Systems, vol. 66, pp. 233-247, 2023. **(Q1, TOP)** | [[PDF]](https://pdf.sciencedirectassets.com/277340/1-s2.0-S0278612522X00058/1-s2.0-S0278612522002205/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFQaCXVzLWVhc3QtMSJIMEYCIQDUdwct7agROyJ6w638FyLu99nts3pWtJ%2Fu6BBbidTaTwIhAP9k2oV0p1gh1DZDxK%2FtTEVShDVAOnnDe1R7V6pOA%2FIKKrIFCB0QBRoMMDU5MDAzNTQ2ODY1IgybRBHecIktq%2B%2BOFzcqjwX8tyXFObqVHpZJBAbCc9IASsREOR6eGZoZArkyIWgZYwaoErYVtpnSmgly5Qg28QZNRj0Ac6xc8dKQUAgE8F%2BoaVCPQC7drszkSAVL3Aw%2FeP7W%2Bq7B8OoDAaHBPd34BLV%2Fwhtv9BJJrAMyoVrfjM94%2FspKt%2Bs1YCc%2B9RO%2BHlnKAjH045N%2B%2BCW0DnAeAF%2FTumxoXDWdsaEOTbrHiPBkKVUT%2Bdg53XQJymReNoPgW8g5vyNusKaEh030xBvfh2auNzVKtZptE6hQ8jsD%2FiUa%2FWPC205ALK2xx5%2Bat2u0jojc9YugwMX4z2ZcCfgmyr2JmlKAhOOipF4Gt3VMEd3YSUmn3s0k3p8rngZWwQgTO82oQEDbslHmSkIMGFdae7SgGE7oWJEjUwE31Ap85290fyg1rO83qq56Qkws%2Bt0eVUttpfNQVRDLyWDNvJuxhepIvdCjN7uSq9t81IDcQeY7Ga9oH0pFY5957WNM5HevO2Xi7a0yjR6IpzCV4Qzt8RR2qRLQW4i%2BJM%2Bs%2BdKKZ3FZTtPpZFE%2F1jCNtdM3KsjgGkYwKJIHOVY5b11MWkXxMBQsC4Q%2Ffvlwmsb5InqRfZ239JD2ExhRBBMPafhY7UohbfAnQ9IaBnxsoPvvootRr7DlvxFCyHjxnOyjV%2By6x0goDFRQNtD7Cnb15Nj0KhMoYtb14AeuEidnO8Pcxi5cguyVwvT9rX8VjlyHoJ1nClxrmUEYOOZ3wxeT%2FYfMMzN8ahlXd5IeJXsCelPisxPuxbv8TSQ6GWY%2Fhzb8U8xdvryvjJqJuiZLwyBPjAE4jBKX88L0N0SCw%2FZG19l9tMkulSaPun1drWc2cxnRCwjAOIjF67t%2BFb40aj8IfP7El7OXEyt9MKi5macGOrABIPd4pMD1zlKwvYO5YnCbKIamMDim8a8bSqCCsnoCcBOBxH87J97rTtSgS9NO4Rp9Zj8chLETeIRyA2WxgHTZgV39isP61NIo4YOzmEzDO74MCPk4zbXjBhKW7YLHuRRktXbbIdmRobrhlyCZATUn15ipQd4OUUqzXrln01n0ieawlRikS%2FzHH86%2FOobxvzGEDN3EKQytnx12jzysg7QRgYRYn3LGrW2pnxpc%2FJ80Bfk%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230823T200737Z&X-Amz-SignedHeaders=host&X-Amz-Expires=299&X-Amz-Credential=ASIAQ3PHCVTYVFCP4AXU%2F20230823%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=22538027af4157d4e7b4e2d89450b7c52d10dfe42a4c1ec742805c004652a277&hash=bb8017543efc9c1b278394d1df1099e38cdaa3b365523c85cb0b012e78db6728&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0278612522002205&tid=spdf-98b220b1-7d65-40f3-82c8-49a6e4afc8ed&sid=e6ae48ca71fd6049fa593f666c4a0dec3053gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=0d0b53030756020256&rr=7fb5fb9bcb15fa1a&cc=cn)

### 2022

TMECH 2022 (TOP)

![sym](images/BICOM_TMECH_FIG1.gif)

- Collision Detection for Cobots: A Back-Input Compensation Approach

**Huang Shifeng**, Gao Meng, Liu Lei, Chen Jihong and Zhang Jianwei. IEEE/ASME Transactions on Mechatronics, vol. 27, no. 6, pp. 4951-4962, 2022. **(Q1, TOP)** | [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9772709)| [[Video]](https://ieeexplore.ieee.org/ielx7/3516/9985401/9772709/supp2-3169084.mp4?arnumber=9772709)

Science China Technological Sciences

![sym](images/Fault_SCTS_2022.png)

- Harmonic reducer in-situ fault diagnosis for industrial robots based on deep learning

Zhou Xing, Zhou Huicheng, He Yiming, **Huang Shifeng**, Zhu Zhihong and Chen Jihong. Science China Technological Sciences, vol. 65, no. 9, pp. 2116-2126, 2022. **(Q2)** | [[PDF]](https://link.springer.com/content/pdf/10.1007/s11431-022-2129-9.pdf?pdf=button%20sticky)

### 2021

TMECH 2021 (TOP)

![sym](images/EDS_TMECH_FIG1.gif)

- Robust Estimation for an Extended Dynamic Parameter Set of Serial Manipulators and Unmodeled Dynamics Compensation

**Huang Shifeng**, Chen Jihong, Zhang Jianwei, Zhu Zhihong, Zhou Huicheng, Li Fan and Zhou Xing. IEEE/ASME Transactions on Mechatronics, vol. 27, no. 2, pp. 962-973, 2021. **(Q1, TOP)** | [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9419753)

ICIRA 2021

![sym](images/Collision_ICIRA_2021.png)

- Research on collision detection and collision reaction of collaborative robots

Zhu Zhihong, Gong Zhihao, Zhang Yuexiang, Chen Simin, Zhao Zhiqiang, Zhou Xing, Gao Meng and **Huang Shifeng (通讯作者)**. Intelligent Robotics and Applications: 14th International Conference, ICIRA, 2021. **(EI, 会议论文)** | [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-030-89098-8_48.pdf?pdf=inline%20link)| [[Video]](https://www.bilibili.com/video/BV1XG411f7fT/?spm_id_from=333.999.0.0)

TOTP 2021

![sym](images/TOTP_XXKZ_2021.png)

- 全动力学约束的机器人高效时间最优轨迹规划

赵志强, 朱志红, 周星, **黄石峰**, 李岩. 信息与控制, 第50卷, 第6期: 701-708, 2021. **(EI)** | [[PDF]](https://xk.sia.cn/CN/10.13976/j.cnki.xk.2021.0546)

### 2020

ICCAR BEST PRESENTATION

![sym](images/Grinding_ICCAR_2020.gif)

- Target Force Tracking and Automatic Contour Surface Processing in Grinding of Industrial Robots

**Huang Shifeng**, Zhu Zhihong, Chen Jihong, Zhou Xing, Yu Jiaxun, Gao Peiyang and Wang Haoqing. IEEE 2020 6th International Conference on Control, Automation and Robotics, ICCAR, 2020. **(EI, 会议论文，BEST PRESENTATION)** | [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9108006)

### 2019

机械工程学报

![sym](images/TCP_JME_2019.png)

- 六关节工业机器人TCP标定模型研究与算法改进

周星, **黄石峰 (通讯作者)**, 朱志红. 机械工程学报, 第55卷, 第11期: 186-196, 2019. **(EI, 机械工程领域高质量科技期刊, 分级: T1)** | [[PDF]](http://qikan.cmes.org/jxgcxb/CN/10.3901/JME.2019.11.186)

# 💻 Patents

- **黄石峰**, 张卓奇, 龚智浩, 王渴建, 招子安, 周星, 朱志红. 机器人末端工具残余振动抑制方法 [中国], 发明专利, 专利号: ZL 2022 1 1091380.5, 授权下证

- 周星, **黄石峰**, 王群, 杨海滨, 李帆. 一种工业机器人 TCP 标定方法 [中国], 发明专利, 专利号: ZL 2016 1 0849202.2, 授权下证

- 张岳翔, **黄石峰**, 高萌, 陈思敏, 周星. 一种基于二阶广义动量观测器的机器人碰撞检测方法 [中国], 发明专利, 专利号: ZL 2021 1 0699021.7, 授权下证

- 张岳翔, **黄石峰**, 高萌, 陈思敏, 周星. 一种机器人碰撞响应方法 [中国], 发明专利, 专利号: ZL 2021 1 0700560.8, 授权下证

- 肖启伟, 周星, **黄石峰**, 张建华, 黄键. 一种工业机器人工具坐标系及零点自标定方法 [中国], 发明专利, 专利号: ZL 2021 1 0699023.6, 授权下证

- 罗健, 朱志红, **黄石峰**. 一种工业机器人编程轨迹诊断及速度优化的方法 [中国], 发明专利, 专利号: ZL 2018 1 0382999.9, 授权下证

# 👨‍💻 Projects

- 2020年度广东省基础与应用基础研究基金佛山市联合基金（粤佛联合基金）项目-重点项目“工业机器人健康监测诊断及控制优化理论与方法”，主要成员 （2020年10月-2023年09月）

---

*[注释]: 🏭🔎 新栏目图标

```yaml
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:   - /about/  - /about.html
```

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# About Me

Shifeng Huang (黄石峰, E-mail: [shifeng@hust.edu.cn](mailto:shifeng@hust.edu.cn)，Phone: 0086+13476149515) focuses on the research of industrial robots, and aims to bridge the gap between theoretical research and commercial engineering applications. Dr. Huang serves as the Deputy Chief Engineer at the Foshan Institute of Intelligent Equipment Technology and the Director of the Key Technology Laboratory at the same institute. During his doctoral studies, he received a solid engineering education and was mentored by Prof. [Jihong Chen](http://mse.hust.edu.cn/info/1145/1434.htm) (Chairman of Huazhong Numerical Control Co., Ltd.), Prof. [Zhihong Zhu](http://mse.hust.edu.cn/info/1145/1422.htm) (Chief Engineer of Huazhong Numerical Control Co., Ltd.), and Researcher [Huicheng Zhou](http://mse.hust.edu.cn/info/1145/1432.htm) (Chief Expert at the Central Research Institute of Huazhong Numerical Control Co., Ltd.). Dr. Huang is also supervised by Prof. [Jianwei Zhang](https://baike.baidu.com/item/%E5%BC%A0%E5%BB%BA%E4%BC%9F/22043671?fr=ge_ala) (Academician of the National Academy of Engineering Sciences in German).

# 🔥 Research Interests

- **Applications**
  
  - Industrial robots
  
  - Collaborative robots (cobots)

- **Subjects**
  
  - Dynamics modeling and identification
  
  - Calibration & compensation of kinematic errors
  
  - Time-optimal trajectory planning (TOTP) and continuous short line segments real-time interpolation
  
  - physical human–robot interaction (pHRI)
  
  - Servo motion control of trajectory tracking
  
  - Vibration suppression
  
  - Robotic manufacturing

# 🏭 Engineering Practice

**总体介绍：** 所有研究工作都围绕着华数机器人展开，积极践行“学-研-产”行动方针。作为国家数控系统工程技术研究中心机器人课题组的大师兄，自觉形成了机器人课题组的青年带头人。博士期间，以华数机器人为依托，始终围绕“高速”、“高精”和“物理人机交互”等关键技术目标，身体力行并带动课题组研究生，在与华数机器人工程师联合攻关下，开展了多项富有工程实际价值的科研课题，研究成果获得华数机器人工程师一致认可，促进国产工业及协作机器人高水平发展。

**补充说明：**

- 部分研究成果出于商业保密不发表学术论文；

- 学术论文展现的更多是一种研究思想。从理论演算，到实验室级的证实，再到做出市场认可的商用工业产品，有着多方面因素的影响。因此学术论文往往不能简单视为产品的最终技术方案，需要科学对待；

- 部分工程上实现的好效果，其实就是一层窗户纸，捅破了其实就那么回事。产品研发以市场和问题为导向，以“管用”、“好用”、“耐用”为前提，因此“一味”谈脱离市场实际所需的创新略显矫情。

**2017年-2023年** 机器人动力学建模与辨识

- 责任定位：博士研究课题，项目主导，负责所有理论研究和部分工程开发。

- 工程效果：实现了同型号不同本体机器人的动力学参数一致性辨识效果，解决了多机器人模型迁移难题，切实为量产机器人的动力学模型部署提供了成套化解决方案；形成了关节传动部件耦合的动力学建模-辨识体系化解决方案；突破了机器人任意姿态安装的动力学模型辨识难题；建立了经典串联机器人、带局部并联结构（例如，重力平衡系统：平衡缸、平行四边形系统、拉升弹簧等）的串联机器人动力学建模-辨识的规范策略；满足任意姿态安装条件下，狭小作业空间约束的负载辨识，与ABB、iiwa等国际知名品牌机器人的负载辨识功能相比，研究成果不受奇异构型制约，且可实现辨识的最优运动激励，能高精度识别负载的完整惯性参数。

- 学术成果：在IEEE TMECH上发表一篇扩展动力学参数集的研究论文；出于商业保密的问题，仅部分成果允许发表。

**2016年-2017年** 工业机器人末端执行器TCP标定研究

- 责任定位：本人机器人研究生涯的第一项任务，属本人独立研究。

- 工程效果：实现了工具坐标系的最优构型标定。

- 学术成果：在《机械工程学报》期刊发表高水平论文一篇，荣获2019年度中国专利优秀奖。

**2017年-2022年** 连续微小线段插补

- 责任定位：出于实际需求，从原有动力学研究被抽调出来研究攻关小线段插补技术。本人在该课题早起阶段作为独立研究者，而在打通基础版本的小线段插补功能后，于2019年转交给其他工程师开发和深入，并指导了两名硕士研究生，分别开展了连续小线段插补与时间最优轨迹规划课题研究。

- 工程效果：实现了机器人复杂轨迹加工中的动态前瞻多轴联动实时插补，考虑了运动中的几何误差约束、运动学约束、关节电机及减速机的动力学约束。

- 学术成果：部分成果形成指导学生的硕士学位论文。

**2018年-2020年** 协作机器人物理人机交互-拖动示教

- 责任定位：团队中理论研究负责人。

- 工程效果：分别实现了无关节力矩传感器的零力拖动、末端力矩传感器模式下的灵敏拖动、驱动器位置模式下的阻抗柔顺拖动、驱动器电流模式下的阻抗柔顺拖动。

- 学术成果：部分已经是机器人圈内的公开技术，部分商业机密未发表。

**2019年-2021年** 协作机器人物理人机交互-碰撞安全检测

- 责任定位：项目中的理论研究先行者，后来转交华数机器人工程师，并指导一名硕士研究生作为研究生课题。

- 工程效果：当前机器人社区广泛应用的基于广义动量观测器GMO（iiwa、Franka等机器人普遍基于该技术）的碰撞安全检测技术受限于有限带宽，对硬碰撞响应慢，而基于高通滤波器的检测技术无法有效捕捉准静态接触行为。所诉缺陷在自研的BICom碰撞检测技术框架下得以有效解决，其兼具高灵敏性的软/硬碰撞统一化检测能力。此外，设计的窗检测器克服了经典防误报措施引起的两类常见缺陷：检测迟延和检测假阴性。

- 学术成果：在IEEE TMECH上发表一篇BICom技术的研究论文、在国际会议ICIRA上发表一篇碰撞检测与响应的论文。

**2018年-2019年** 工业机器人磨抛加工中的恒力跟踪控制

- 责任定位：指导课题组硕士生开展课题研究。

- 工程效果：实现了打磨头接触工件瞬态时的突变冲击力，达到了高精度磨抛目标接触力跟踪效果。

- 学术成果：在IEEE ICCAR国际会议上发表论文，获得“BEST PRESENTATION”奖。

**2020年-2023年** 高精度伺服控制技术

- 责任定位：作为项目团队高精度伺服控制技术算法研究的带头人、先行者。

- 工程效果：实现了伺服参数的解析化参数整定，对动力学模型的不确定性有大范围鲁棒性，同一套伺服参数能有效适应不同负载质量等级，实现位置跟踪误差的指数收敛。

- 学术成果：商业机密。

**2020年-2022年** 工业机器人运动学参数标定技术

- 责任定位：指导课题组硕士生开展课题研究，在研究初期为团队硕士学生提供标定算法基本框架，并在研究过程中指导和提升标定算法。

- 工程效果：形成了标定构型选优及多工具坐标系快速标定解决方案，开发了机器人运动学参数标定软件一套。

- 学术成果：指导完成硕士学位论文。

**2021年-2023年** 工业机器人振动抑制技术

- 责任定位：指导课题组硕士生开展课题研究，本人在课题中定方向，确定合适技术路线。

- 工程效果：开发了输入整形和迭代学习控制算法，它们分别适用于机器人不同的振动抑制场景。典型地，输入整形需要已知被控振动系统的固有频率，而迭代学习适用于具有重复特征的加工应用。

- 学术成果：指导两名硕士生形成了以输入整形技术，迭代学习技术的学位论文，还有一名在读研究生，形成了具有普适抑振效果的“扭矩微分补偿”研究成果（正在投稿）。

# 🎓 Educations

![sym](images/HUST.png)

- 2016.09 - 2023.09, Doctoral student
  
  Major: Mechanical engineering

National Center of Technology Innovation for Intelligent Design and Numerical Control (NCTI-IDNC), School of Mechanical Science & Engineering

Huazhong University of Science and Technology, Wuhan, China

![sym](images/HUST.png)

- 2015.09-2016.09, Master's student
  
  Major: Mechanical and electronic engineering

National Numerical Control System Engineering Research Center, School of Mechanical Science & Engineering

Huazhong University of Science and Technology, Wuhan, China

![sym](images/CSU.png)

- 2011.09-2015.09, Undergraduate student
  
  Major: Mechanical design, manufacturing, and automation

Advanced Engineering Talent Experimental Class, School of Mechatronics Engineering

Central South University, Changsha, China

# 🎖 Honors

- *2022* Guangdong Provincial Mechanical Industry Science and Technology Award, First Prize (5/15). (2022年荣获广东省机械工业科学技术奖励一等奖，排名第5)

- *2022* Guangdong Provincial Society of Mechanical Engineering Science and Technology Award, First Prize (5/15). (2022年荣获广东省机械工程学会科学技术奖励一等奖，排名第5)

- *2020* "China Patent Excellence Award" from the National Intellectual Property Administration of China (2/5), Award-Winning Patent: A Method for TCP Calibration of Industrial Robots. (2020 年入选中国国家知识产权局“中国专利优秀奖”，获奖专利：一种工业机器人 TCP 标定方法，排名第2)

- *2020* "Best Presentation award" at the IEEE 6th International Conference on Control, Automation and Robotics. Winning Work: Target Force Tracking and Automatic Contour Surface Processing in Industrial Robot Grinding

- *2020* "Special Prize" in the 1st Science and Technology Essay Contest organized by the Foshan Institute of Intelligent Equipment Technology (Theme: Fundamental Research on Factors Influencing Industrial Robot Performance). Winning work: Several Key Issues of Industrial Robot Controller: An Interesting Insight. (2020 年荣获由佛山智能装备技术研究院主办的第1届科技征文大赛特等奖，大赛主题：影响工业机器人性能的基础问题研究，获奖作品：从趣谈控制，到论工业机器人中Controller 的若干问题)

- *2018* “Outstanding Contribution Award” from the Foshan Institute of Intelligent Equipment Technology. (2018 年荣获佛山智能装备技术研究院“突出贡献奖”)

# 📖 Services

- IEEE Transactions on Industrial Electronics (TIE): Reviewer
- IEEE Robotics and Automation Letters (RA-L): Reviewer
- IEEE International Conference on Robotics and Automation (ICRA): Reviewer

# 💬 Invited Talks

- *2023*:   第四届中国机器人学术年会，报告：重力场自适应的机器人扩展动力学参数集与稳健混合建模：机理+学习 [[Poster]](/pdf/2023ZGJQRXSNH.pdf)
- *2022:*  IEEE 14th Workshop on Active Disturbance Rejection Control. Topic: Challenges and Considerings on Motion Control of Industrial Robots: An Engineering Pespective [[Link]](https://mp.weixin.qq.com/s/SvmoTYgqF9-4HmZ_sUn92w)
- *2021:*  The 14th International Conference on Intelligent (ICIRA). Topic: Research on Collision Detection and Collision Reaction of Collaborative Robots [[Poster]](/pdf/2021ICIRAPoster.pdf)
- *2020:*  The 6th International Conference on Control, Automation and Robotics (ICCAR). Topic: Target Force Tracking and Automatic Contour Surface Processing in Industrial Robot Grinding [[Certification]](/pdf/2020-ICCAR-Best-Presentation-Award.pdf)

# 📝 Papers

### 2023

JMS 2023 (TOP)

![sym](images/JMS_2023_FIG1.jpg)

- In-situ fault diagnosis for the harmonic reducer of industrial robots via multi-scale mixed convolutional neural networks

He Yiming, Chen Jihong, Zhou Xing and **Huang Shifeng (通讯作者)**. Journal of Manufacturing Systems, vol. 66, pp. 233-247, 2023. **(Q1, TOP)** | [[PDF]](https://pdf.sciencedirectassets.com/277340/1-s2.0-S0278612522X00058/1-s2.0-S0278612522002205/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFQaCXVzLWVhc3QtMSJIMEYCIQDUdwct7agROyJ6w638FyLu99nts3pWtJ%2Fu6BBbidTaTwIhAP9k2oV0p1gh1DZDxK%2FtTEVShDVAOnnDe1R7V6pOA%2FIKKrIFCB0QBRoMMDU5MDAzNTQ2ODY1IgybRBHecIktq%2B%2BOFzcqjwX8tyXFObqVHpZJBAbCc9IASsREOR6eGZoZArkyIWgZYwaoErYVtpnSmgly5Qg28QZNRj0Ac6xc8dKQUAgE8F%2BoaVCPQC7drszkSAVL3Aw%2FeP7W%2Bq7B8OoDAaHBPd34BLV%2Fwhtv9BJJrAMyoVrfjM94%2FspKt%2Bs1YCc%2B9RO%2BHlnKAjH045N%2B%2BCW0DnAeAF%2FTumxoXDWdsaEOTbrHiPBkKVUT%2Bdg53XQJymReNoPgW8g5vyNusKaEh030xBvfh2auNzVKtZptE6hQ8jsD%2FiUa%2FWPC205ALK2xx5%2Bat2u0jojc9YugwMX4z2ZcCfgmyr2JmlKAhOOipF4Gt3VMEd3YSUmn3s0k3p8rngZWwQgTO82oQEDbslHmSkIMGFdae7SgGE7oWJEjUwE31Ap85290fyg1rO83qq56Qkws%2Bt0eVUttpfNQVRDLyWDNvJuxhepIvdCjN7uSq9t81IDcQeY7Ga9oH0pFY5957WNM5HevO2Xi7a0yjR6IpzCV4Qzt8RR2qRLQW4i%2BJM%2Bs%2BdKKZ3FZTtPpZFE%2F1jCNtdM3KsjgGkYwKJIHOVY5b11MWkXxMBQsC4Q%2Ffvlwmsb5InqRfZ239JD2ExhRBBMPafhY7UohbfAnQ9IaBnxsoPvvootRr7DlvxFCyHjxnOyjV%2By6x0goDFRQNtD7Cnb15Nj0KhMoYtb14AeuEidnO8Pcxi5cguyVwvT9rX8VjlyHoJ1nClxrmUEYOOZ3wxeT%2FYfMMzN8ahlXd5IeJXsCelPisxPuxbv8TSQ6GWY%2Fhzb8U8xdvryvjJqJuiZLwyBPjAE4jBKX88L0N0SCw%2FZG19l9tMkulSaPun1drWc2cxnRCwjAOIjF67t%2BFb40aj8IfP7El7OXEyt9MKi5macGOrABIPd4pMD1zlKwvYO5YnCbKIamMDim8a8bSqCCsnoCcBOBxH87J97rTtSgS9NO4Rp9Zj8chLETeIRyA2WxgHTZgV39isP61NIo4YOzmEzDO74MCPk4zbXjBhKW7YLHuRRktXbbIdmRobrhlyCZATUn15ipQd4OUUqzXrln01n0ieawlRikS%2FzHH86%2FOobxvzGEDN3EKQytnx12jzysg7QRgYRYn3LGrW2pnxpc%2FJ80Bfk%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230823T200737Z&X-Amz-SignedHeaders=host&X-Amz-Expires=299&X-Amz-Credential=ASIAQ3PHCVTYVFCP4AXU%2F20230823%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=22538027af4157d4e7b4e2d89450b7c52d10dfe42a4c1ec742805c004652a277&hash=bb8017543efc9c1b278394d1df1099e38cdaa3b365523c85cb0b012e78db6728&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0278612522002205&tid=spdf-98b220b1-7d65-40f3-82c8-49a6e4afc8ed&sid=e6ae48ca71fd6049fa593f666c4a0dec3053gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=0d0b53030756020256&rr=7fb5fb9bcb15fa1a&cc=cn)

### 2022

TMECH 2022 (TOP)

![sym](images/BICOM_TMECH_FIG1.gif)

- Collision Detection for Cobots: A Back-Input Compensation Approach

**Huang Shifeng**, Gao Meng, Liu Lei, Chen Jihong and Zhang Jianwei. IEEE/ASME Transactions on Mechatronics, vol. 27, no. 6, pp. 4951-4962, 2022. **(Q1, TOP)** | [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9772709)| [[Video]](https://ieeexplore.ieee.org/ielx7/3516/9985401/9772709/supp2-3169084.mp4?arnumber=9772709)

Science China Technological Sciences

![sym](images/Fault_SCTS_2022.png)

- Harmonic reducer in-situ fault diagnosis for industrial robots based on deep learning

Zhou Xing, Zhou Huicheng, He Yiming, **Huang Shifeng**, Zhu Zhihong and Chen Jihong. Science China Technological Sciences, vol. 65, no. 9, pp. 2116-2126, 2022. **(Q2)** | [[PDF]](https://link.springer.com/content/pdf/10.1007/s11431-022-2129-9.pdf?pdf=button%20sticky)

### 2021

TMECH 2021 (TOP)

![sym](images/EDS_TMECH_FIG1.gif)

- Robust Estimation for an Extended Dynamic Parameter Set of Serial Manipulators and Unmodeled Dynamics Compensation

**Huang Shifeng**, Chen Jihong, Zhang Jianwei, Zhu Zhihong, Zhou Huicheng, Li Fan and Zhou Xing. IEEE/ASME Transactions on Mechatronics, vol. 27, no. 2, pp. 962-973, 2021. **(Q1, TOP)** | [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9419753)

ICIRA 2021

![sym](images/Collision_ICIRA_2021.png)

- Research on collision detection and collision reaction of collaborative robots

Zhu Zhihong, Gong Zhihao, Zhang Yuexiang, Chen Simin, Zhao Zhiqiang, Zhou Xing, Gao Meng and **Huang Shifeng (通讯作者)**. Intelligent Robotics and Applications: 14th International Conference, ICIRA, 2021. **(EI, 会议论文)** | [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-030-89098-8_48.pdf?pdf=inline%20link)| [[Video]](https://www.bilibili.com/video/BV1XG411f7fT/?spm_id_from=333.999.0.0)

TOTP 2021

![sym](images/TOTP_XXKZ_2021.png)

- 全动力学约束的机器人高效时间最优轨迹规划

赵志强, 朱志红, 周星, **黄石峰**, 李岩. 信息与控制, 第50卷, 第6期: 701-708, 2021. **(EI)** | [[PDF]](https://xk.sia.cn/CN/10.13976/j.cnki.xk.2021.0546)

### 2020

ICCAR BEST PRESENTATION

![sym](images/Grinding_ICCAR_2020.gif)

- Target Force Tracking and Automatic Contour Surface Processing in Grinding of Industrial Robots

**Huang Shifeng**, Zhu Zhihong, Chen Jihong, Zhou Xing, Yu Jiaxun, Gao Peiyang and Wang Haoqing. IEEE 2020 6th International Conference on Control, Automation and Robotics, ICCAR, 2020. **(EI, 会议论文，BEST PRESENTATION)** | [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9108006)

### 2019

机械工程学报

![sym](images/TCP_JME_2019.png)

- 六关节工业机器人TCP标定模型研究与算法改进

周星, **黄石峰 (通讯作者)**, 朱志红. 机械工程学报, 第55卷, 第11期: 186-196, 2019. **(EI, 机械工程领域高质量科技期刊, 分级: T1)** | [[PDF]](http://qikan.cmes.org/jxgcxb/CN/10.3901/JME.2019.11.186)

# 💻 Patents

- **黄石峰**, 张卓奇, 龚智浩, 王渴建, 招子安, 周星, 朱志红. 机器人末端工具残余振动抑制方法 [中国], 发明专利, 专利号: ZL 2022 1 1091380.5, 授权下证

- 周星, **黄石峰**, 王群, 杨海滨, 李帆. 一种工业机器人 TCP 标定方法 [中国], 发明专利, 专利号: ZL 2016 1 0849202.2, 授权下证

- 张岳翔, **黄石峰**, 高萌, 陈思敏, 周星. 一种基于二阶广义动量观测器的机器人碰撞检测方法 [中国], 发明专利, 专利号: ZL 2021 1 0699021.7, 授权下证

- 张岳翔, **黄石峰**, 高萌, 陈思敏, 周星. 一种机器人碰撞响应方法 [中国], 发明专利, 专利号: ZL 2021 1 0700560.8, 授权下证

- 肖启伟, 周星, **黄石峰**, 张建华, 黄键. 一种工业机器人工具坐标系及零点自标定方法 [中国], 发明专利, 专利号: ZL 2021 1 0699023.6, 授权下证

- 罗健, 朱志红, **黄石峰**. 一种工业机器人编程轨迹诊断及速度优化的方法 [中国], 发明专利, 专利号: ZL 2018 1 0382999.9, 授权下证

# 👨‍💻 Projects

- 2020年度广东省基础与应用基础研究基金佛山市联合基金（粤佛联合基金）项目-重点项目“工业机器人健康监测诊断及控制优化理论与方法”，主要成员 （2020年10月-2023年09月）

---

*[注释]: 🏭🔎 新栏目图标
