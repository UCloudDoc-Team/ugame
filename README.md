<!--一下子提供一种思路，欢迎大家发挥 -->
# 概览


云游戏是一种以云计算技术为基础的在线游戏方式，游戏与画面的渲染将在云端完成，并通过流媒体技术将渲染后的画面传输到玩家终端。云游戏让玩家可以在智能电视、PC、手机、平板电脑等各终端之间无缝切换，随时随地畅玩游戏大作。

#### <center>[了解](#_1了解)   |   [购买及付费](#_2购买及付费)   |   [接入指南](#_3云游戏接入三步曲)  <!-- |   [快速上手](#_4云游戏WEB演示程序快速上手指南) --> </center>   

## 1.了解

UCloud云游戏包含云手游和云端游两个产品，其中云手游是基于工业级ARM服务器和工业级GPU渲染、自研安卓虚拟化、低延迟编码串流、一站式跨地域调度算法等多种技术以满足2B、2C的不同应用场景需求。云端游产品将在后续发布，敬请关注。

### 1.1)功能与优势
#### 即开即玩
无惧终端与场景限制，免下载安装，跨终端游戏进度同步，一个终端所有平台游戏畅玩。
#### 高灵活度
区别于SoC云手机架构，客户可任意的对整台服务器切割成各种规格的云手机，如1C1G或20C80G。
#### 便捷接入
UCloud完善的IaaS资源+合作伙伴PaaS、SaaS能力，集成工业级ARM服务器和工业级GPU渲染等多套技术方案，助力云游戏业务快速成长。
#### 突破算力瓶颈
ARM服务器和GPU渲染，突破传统手机和SoC云手机的硬件瓶颈，客户可基于此设计长期的原生云游戏、元宇宙演进路线。
#### 高灵活度、高利用率
传统SoC（片上系统）架构只能运行2-3个实例，剩余的资源碎片无法使用，而不同帧率和分辨率又无法混跑，进而会产生多种资源池、增大管理复杂度。而ARM服务器架构只需一种规格即可运行所有实例，实例按需使用CPU和GPU资源，多余CPU和GPU算力碎片由内核调度给其他实例使用；而不同分辨率和帧率的实例亦可混跑，实现服务器资源最大利用率，也简化资源管理复杂度。
####  高性能
传统x86 CPU模拟安卓应用的ARM指令会有20-30%开销，还有的采用EmuGL来实现OpenGLES到OpenGL的指令转换，都存在性能损耗大、延迟大、卡顿等体验问题。
UCloud云游戏基于原生ARM CPU、自研安卓虚拟化技术、GPU直通安卓技术、内核调优，高性能运行80-120路游戏。
####  多数据中心
目前已建设14个三通机房（青岛、镇江、廊坊、杭州、武汉、扬州、娄底、重庆、安顺、沈阳、合肥、咸阳、石家庄、洛阳），100+单线机房，核心数据中心全球有31个

### 1.2)应用场景
#### 云手游2C场景
低配玩3A：手游在云端运行，低配手机也能流畅运行大型手游； 不发烫。
客户端：可根据UCloud提供的安卓、iOS、H5等客户端SDK Demo集成到客户的客户端。
调度平台：UCloud提供一站式调度。
#### 云手游2B场景
试玩广告：可将试玩链接嵌入到第三方APP中，将“下载”替换成“试玩”，实现秒级呈现。
微端投放：投放5MB游戏微端下载，也可极大降低下载门槛，进一步引导下载完整客户端，实现游戏获客。
短信推广：短信发送URL，玩家点击URL在微信小程序内可玩游戏，可实现快速传播；也可实现多人同屏。
### [词汇表](/ucgs/_glossary.md)



## 2.购买及付费

	

* [计费模式](/ucgs/price#计费模式)
* [服务器配置](/ucgs/price#AMR服务器配置)
* [退款](/ucgs/price#退款)



## 3.云游戏接入三步曲

传统游戏经过游戏上传、实例创建、SDK开发与上线三步即可轻松接入UCloud云游戏平台，无需对原有的代码做任何的改动即可轻松跨端使用。


  * [云手游2C场景上线流程](/ucgs/user_guide#X86云手游2C场景上线流程)
  * [云手游微端/H5链接推广流程](/ucgs/user_guide#ARM云手游微端/H5链接推广流程)
 
  
<!--
## 4.云游戏WEB演示程序快速上手指南

为了您更好的使用云游戏服务，缩短开发周期，我们也准备了一个Docker镜象来供您对云游戏进行试用和联调测试，同时在您完成了云游戏服务创建后，我们也提供了几款游戏供您进行客户端同步开发和内部测试。

请注意，在未获得游戏版权方授权的情况下，测试游戏不可进行商业运营。 


- [创建云游戏DEMO CUBE](/ucgs/quick_start#创建Servless服务)
- [访问您的云游戏](/ucgs/quick_start#通过WEB访问DEMO页面)
-->
