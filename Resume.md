 <center>
     <h1>林浩成</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             18888923312
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             601442991@qq.com
         </span>
         <!-- ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/CyC2018">CyC2018</a>
         </span>
         ·
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="#">My Blog</a>
         </span> -->
     </div>
 </center>

 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息

 - 1994-10
 - 求职意向：C/C++ 后端开发工程师
 - 工作经验：2 年

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 硕士, 浙江大学, 计算机科学与技术专业, CAD&CG Lab, 2017.9 ~ 2020.3
- 学士, 东北大学, 计算机科学与技术专业, 2013.9 ~ 2017.9
- 连续获得校优秀学生奖学金, 绩点 top 10%
- 大学生数学竞赛 2014 全国一等奖
- acm-icpc 2015 shanghai ec-final 铜奖

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

#### <img src="assets/project-diagram-solid.svg" width="30px"> 腾讯，CSIG TRTC，后台开发 工程师，2020.4 - 今

&ensp;&ensp;&ensp;&ensp;&ensp;负责腾讯实时音视频TRTC的后台开发工作<br>
&ensp;&ensp;&ensp;&ensp;&ensp;主要模块是媒体传输模块<br>
&ensp;&ensp;&ensp;&ensp;&ensp;主要工作是负责用户接入、分发网络里的音视频数据, 降低用户的延迟感, 提升通信的流畅性<br>

- **数据缓存服务器与客户端开发**
    - 工作角色: 主要开发者
    - 服务端采用固定大小的线程池, 定时从数据库增量拉取、全量拉取数据; 客户端从服务端定时增量拉取、全量拉取, 写入本地共享内存; 本地业务进程从共享内存获取最新数据
    - 数据存储采用自研的共享内存缓存组件, 存储信息为tlv格式

- **自研 rt-quic 项目开发**
    - 工作角色：参与者
    - 面向实时音视频场景的QUIC传输协议实现
    - 牺牲有序性来提升传输的实时性。（不存在流级别的传输阻塞问题）
    - 采用对丢包不敏感的拥塞控制算法-BBR

 - **网络传输架构重构开发**
    - 工作角色: 参与者
    - 原始的网络架构下, 数据分发的收敛性较弱(数据分发容易产生广播)、容灾能力弱(房间管理容易出现单点故障); 新架构减少了网络分发的包量, 节省带宽费用, 提升了整体架构的可靠性

## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- ★★★ 熟练掌握 Linux 下的开发, 以及网络、负载等问题的排查
- ★★★ 熟练掌握各类数据结构与算法
- ★★★ 熟练掌握 C/C++, python
- ★★☆ 会基本使用 MySQL, Redis, docker
- ★★☆ 了解常见的设计模式
