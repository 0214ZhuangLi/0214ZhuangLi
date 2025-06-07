# 👋 你好，我是 李庄

<!-- 添加一个简洁的个人介绍横幅 -->
![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Welcome%20to%20my%20GitHub&fontSize=40&fontAlignY=35&desc=苏州大学研究生%20|%20寻找实习机会&descAlignY=55&descAlign=50)

## 🚀 关于我

我是**苏州大学**未来科学与工程学院的研究生一年级学生，对软件开发充满热情。我热爱编程，善于学习新技术，希望通过实习将理论知识转化为实践经验，为公司创造价值的同时提升自己的技术能力。

- 🎓 **学校专业**：苏州大学计算机研究生一年级
- 🔭 **当前状态**：积极寻找**日常实习**机会
- 💼 **实习意向**：后端开发/全栈开发 实习生
- 💬 **技术兴趣**：Java、MySQL、Redis、JUC、分布式系统
- 📫 **联系方式**：570606551@qq.com
- ⚡ **个人特点**：快速学习者，具备良好的团队协作能力

## 🔗 在线主页

[![CSDN博客](https://img.shields.io/badge/CSDN-博客主页-FC5531?style=for-the-badge&logo=csdn&logoColor=white)](https://blog.csdn.net/你的CSDN用户名)
[![LeetCode](https://img.shields.io/badge/LeetCode-算法练习-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black)](https://leetcode.cn/u/你的力扣用户名/)
[![GitHub](https://img.shields.io/badge/GitHub-代码仓库-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/你的GitHub用户名)

## 🛠️ 技术栈

### 编程语言
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)


### 后端技术
![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)


### 前端技术
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### 数据库
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### 工具与平台
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

## 💼 实习经历

### 🏢 [公司名称] - [职位名称]
![实习时间](https://img.shields.io/badge/Time-2025.XX-2025.XX-green)
![工作地点](https://img.shields.io/badge/Location-城市名-blue)
![技术栈](https://img.shields.io/badge/Tech-Java%2FSpring%2FMySQL-orange)

**实习简介：** [在这里描述你的实习公司背景和你的主要职责]

**主要工作：**
- **[工作内容1]**：[具体描述你做了什么，使用了什么技术，解决了什么问题]
- **[工作内容2]**：[具体描述你的贡献和成果]
- **[工作内容3]**：[量化你的工作成果，比如性能提升、bug修复数量等]

**技术收获：**
- [学到的新技术或技能]
- [解决的技术难题]
- [对某个技术领域的深入理解]

**个人成长：**
[描述在实习过程中的个人成长，比如团队协作能力、沟通能力、项目管理能力等方面的提升]

---

## 🎯 项目经历

### 本地宝（仿大众点评）
![项目语言](https://img.shields.io/badge/Language-Java-yellow)
![项目类型](https://img.shields.io/badge/Type-分布式应用-blue)
![完成时间](https://img.shields.io/badge/Time-2025.05-green)


**项目简介：** 基于 Spring Boot + Redis 的高并发点评系统，实现商户查询、优惠券秒杀、社交功能等核
心模块，采用前后端分离架构。

**核心功能：**
- **分布式Session管理**：使用Redis管理分布式Session，设计双层拦截器机制实现用户登录校验与权限控制，支持多实例环境下的统一认证
- **缓存优化策略**：针对缓存穿透、缓存击穿与缓存雪崩问题，分别采用缓存空对象、逻辑过期结合后台异步重建、以及随机TTL策略进行综合治理，提升系统稳定性与缓存命中率
- **高并发秒杀系统**：通过Redis分布式锁控制库存一致性，引入消息队列实现异步削峰和订单异步处理
- **多数据结构应用**：深入应用Redis多种数据结构，使用ZSet实现点赞和关注排序，BitMap支持用户签到统计，HyperLogLog进行UV去重统计
- **地理位置服务**：使用GeoHash提供基于地理位置的附近服务查询功能


**收获体会：**  通过这个项目，我深入理解了Redis在分布式系统中的核心作用，掌握了从理论到实践的完整应用链路。在解决缓存三大经典问题的过程中，不仅提升了我的系统设计思维，更让我明白了在高并发场景下如何权衡性能与一致性。特别是在实现秒杀系统时，我学会了如何运用分布式锁、消息队列等技术栈协同工作，解决复杂的并发控制问题。同时，通过灵活运用Redis的多种数据结构解决实际业务需求，让我对NoSQL数据库的应用场景有了更深刻的认识。这个项目极大地锻炼了我的问题分析能力和技术选型能力，为我今后从事后端开发工作奠定了坚实的基础。

---

### [Gitlet（轻量 Git 实现）](https://github.com/0214ZhuangLi/Gitlet.git)
![项目语言](https://img.shields.io/badge/Language-Java-green)
![项目类型](https://img.shields.io/badge/Type-系统工具-orange)
![完成时间](https://img.shields.io/badge/Time-2025.04-green)


**项目简介：** 基于 Java 实现的轻量级版本控制系统，模仿 Git 核心机制，支持分支管理、版本回滚、合
并冲突处理等功能。

**核心功能：**
- **SHA-1哈希去重存储**：通过SHA-1哈希值实现文件内容的去重存储，确保相同内容只存储一份，提高存储效率
- **分目录对象管理**：将所有Git对象（Blob文件内容和Commit提交记录）按哈希值前缀分目录存储在objects文件夹中，确保数据完整性和高效检索
- **核心数据结构设计**：设计三个核心数据结构——Blob类封装文件内容，Commit类管理提交历史和文件映射关系，StagingArea类处理暂存区状态
- **对象序列化机制**：通过序列化机制实现对象持久化，保证数据在程序重启后的一致性
- **完整版本控制工作流**：支持完整的版本控制工作流，实现add、rm、commit、merge等13个核心命令，覆盖Git的主要功能


**项目状态：** 通过这个项目，我深入理解了Git底层的存储原理和版本控制机制，掌握了如何从零开始设计一个分布式版本控制系统。在实现SHA-1哈希存储的过程中，我学会了如何平衡存储效率与数据完整性，理解了内容寻址存储的核心思想。通过设计Blob、Commit、StagingArea三个核心数据结构，我提升了面向对象设计能力和系统架构思维。特别是在实现merge等复杂命令时，我深刻体会到了算法设计的重要性，学会了如何处理复杂的数据依赖关系。序列化机制的实现让我对数据持久化有了更深的认识，而13个核心命令的完整实现过程极大地锻炼了我的编程能力和项目管理能力。这个项目不仅让我对Git工具有了全新的理解，更重要的是培养了我从用户需求出发进行系统设计的工程思维。

---

## 📊 研究项目

### 知识图谱补全模型改进研究
![项目语言](https://img.shields.io/badge/Language-Python-blue)
![项目类型](https://img.shields.io/badge/Type-学术研究-purple)
![完成时间](https://img.shields.io/badge/Time-2025.XX-green)

**研究背景：** [在这里描述知识图谱补全的研究背景和意义，以及现有方法的不足]

**研究内容：**
- **[改进点1]**：[描述你对现有模型的第一个改进，比如网络结构、损失函数、训练策略等]
- **[改进点2]**：[描述第二个创新点，解决了什么具体问题]
- **[实验设计]**：[描述你的实验设置，使用的数据集，评估指标等]
- **[技术实现]**：[描述使用的深度学习框架，模型架构，核心算法实现等]

**主要贡献：**
- [量化的实验结果，比如在某个数据集上性能提升了多少]
- [理论贡献或新的见解]
- [开源代码或可复现的实验]

**技术栈：**
- **深度学习框架**：PyTorch/TensorFlow
- **数据处理**：NumPy, Pandas, NetworkX
- **可视化**：Matplotlib, Seaborn
- **其他工具**：[根据实际使用的工具填写]

**研究收获：**
[描述通过这个研究项目学到的知识，比如对图神经网络、知识表示学习、深度学习等领域的深入理解，以及科研方法和论文写作能力的提升]

---

## 🏆 教育背景 & 技能

### 📚 教育经历
- 🎓 **苏州大学** -  人工智能 硕士研究生（2024.09 - 2027.06）
- 🎓 **南京工程学院** - 软件工程 学士（2020.09 - 2024.06）
- 📊 **主要课程**：数据结构与算法、计算机网络、操作系统、计算机组成原理、数据库系统、软件设计模式、Java程序设计、软件需求工程、Linux内核

### 💪 个人技能
- **编程能力**：具备扎实的编程基础，能够快速学习新技术
- **学习能力**：善于从文档、教程、开源项目中学习
- **问题解决**：具备良好的逻辑思维和问题分析能力
- **团队协作**：有良好的团队合作经验和沟通能力
- **英语水平**：CET-6 （517分），能够阅读英文技术文档

### 🏅 获奖经历
- 🏆 **研究生学业二等奖学金**：2024.09
- 🏆 **国家励志奖学金**：2023.11
- 🏆 **校一等奖学金**：2023.10
- 🏆 **校三好学生**：2023.10
- 🏆 **校一等奖学金**：2023.05
- 🏆 **国家励志奖学金**：2022.11
- 🏆 **校优秀学生干部**：2022.10
- 🏆 **校二等奖学金**：2022.10
- 🏆 **校优秀共青团员**：2022.05
- 🏆 **校二等奖学金**：2022.05
- 🏆 **暑期社会实践优秀个人**：2021.11

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=[你的GitHub用户名]&style=flat-square&color=blue" alt="Profile views" />
  
  **感谢访问我的GitHub主页！** 🎉
  
  *"代码改变世界，创新驱动未来"*
</div>

## 💼 实习求职信息

### 🎯 求职意向
- **职位类型**：后端开发/全栈开发 实习生
- **实习时间**：
  - 💻 **暑期实习**：2025年6月 - 2025年9月（可全职）
  - 🔄 **日常实习**：每周4-5天，持续3-6个月
- **工作地点**：苏州、上海、杭州、北京、深圳等（可接受远程）
- **期望薪资**：面议

### ✨ 实习优势
- **学习能力强**：研究生阶段培养的快速学习和适应能力
- **时间充裕**：可以投入充足时间完成实习任务
- **基础扎实**：具备良好的计算机基础知识和编程能力
- **积极主动**：主动承担责任，善于沟通和团队协作
- **长期稳定**：寻找长期合作机会，可持续实习

### 📋 技能清单
**熟练掌握**：Java、HTML、CSS、MySQL
**了解使用**：Spring、Python、Redis、Nexus
**正在学习**：GO、Docker
