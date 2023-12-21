---
pageClass: home-page
# some data for the components

name: 卢宪廷
profile: /profile.jpg

socials:
  - title: Github
    icon: "/icons/github.svg"
    link: https://github.com/Celthi
  - title: Zhihu
    icon: "/icons/zhihu.svg"
    link: https://www.zhihu.com/people/lan-tian-89
  - title: Linkedin
    icon: "/icons/linkedin.svg"
    link: https://www.linkedin.cn/incareer/in/%E5%AE%AA%E5%BB%B7-%E5%8D%A2-4513a6117
  - title: 脉脉
    icon: "/icons/maimai.png"
    link: https://maimai.cn/profile/detail?dstu=169947964
bio: 程序员，偶尔写文章
email: Evan_L00@qq.com
phone: +86l8667024392
cv: https://raw.githubusercontent.com/Celthi/Celthi.github.io/master/Xianting%20Lu_zh.pdf
---

<ProfileSection :frontmatter="$page.frontmatter" />

## 关于我

专注于大语言模型/GPT应用开发/提示工程，事件驱动异步架构/分布式，C++/Rust/Typescript，企业搜索


译著[Effective Debugging](https://github.com/Celthi/effective-debugging-zh)，编写[Rust 系列：正确编程的思考模型](https://zhuanlan.zhihu.com/p/365845688)，[C++驿站](https://www.zhihu.com/column/c_1385152794127720448)


掌握语言: C++/Rust/Java/, Python/Typescript/Javascript等等.

熟练工具: kubernetes/Lucene/Container/gdb/CoreAnalyzer/OpenSearch消息中间件等等



## 工作经历
- [2023年2月 - 至今] 大语言模型/ChatGPT赋能数据分析、提示工程、GPT模型
  
  - 设计和开发微策略基于OpenAI的AI可视化机器人，从原型开发到产品架构设计、NodeJS微服务设计、 MSTR Chat Agent with Langchain、 Multiple Action工具等等.
  
  - 微策略AI可视化机器人的重大更新和提升，如文本到可视化、SQL到可视化、提示词优化和多Agent多步骤策略等等

  - 公司内部工具：[任务自动创建微服务](https://github.com/Celthi/rally-rs)，快速便捷记录工单和公司Python多语言方便添加工具。
  
- [2021年7月 - 2023年2月] 微策略（杭州）有限公司, 高级软件工程师, C++基础架构，+Rust, +Python等等

  - 设计并实现OCR微服务（一语行测），花销小时记的测试仅仅一个评论就分发到集群里运行，被65+工程师（90%）应用在他们每天的开发中，

  - 主导并实现时区感知数据分析对象模型(序列化和反序列基础架构)，将客户盼望已久的时区感知带入微策略平台。

  - 实现防止服务器崩溃的系统性机制，消除了难以重现的服务器崩溃问题，并申请了专利（三作）。

  - 设计和实现异步微策略数据迁移基础架构，用于微策略报表文件的导入和导出。


- [2019年2月 - 2021年7月] MicroStrategy Corp., 美国，软件工程师，+Nodejs, +kubenetes等等

  - 微策略下一代全域搜索（基于Elatic Search)微服务的主程，设计并实现：搜索查询解析器，自动补全，多语言支持，用户查询，索引更新架构等等功能模块。

  - 容器化和集群化(k8s)微策略传统的集成测试, 独自编写了服务器的生命周期管理微服务CAT，极大提高资源利用率，节省工程时间，启动时间从小时变成了分钟。

  - 设计并实现微策略智能服务器的任务内存限制模块，提供高稳定的服务，并获得专利（一作）。改进微策略的高并行任务基础架构并提供节流服务，避免服务器非正常用户流量的过载。

  - 设计和主导重大客户Indidex的产品升级验证工具，使得客户继续使用并升级到微策略产品；设计的验证工具被集成到产品中，从而服务更多的客户。

- [2017年5月 - 2019年2月] 微策略中国技术中心, 软件工程师，+Java, +Lucene搜索等等

  - 微策略下一代微服务数据管理调研，从关系型切换到MongoDB。
  - 微策略核心的功能元数据管理，，用户权限等等）的维护和开发。

  - 微策略搜索引擎（Lucene为核心）的增强和维护。

  - C++大型服务器core dump分析，如内存损坏（double free, use after free, dangling pointer等等)，多线程bug.

  - C++大型服务器内存泄漏分析，并总结了十个内存泄漏模式，分享给所有公司的工程师学习。


## 教育

- **东南大学** <br/>
2014年9月 - 2017年4月 （保送） 信息与通信工程

- **天津大学** <br/>
2010年9月 - 2014年6月, （top10) 通信工程

- **南开大学** <br/>
2012–2014 双学位, 经济学院，金融专业

## 开源项目

[→ Full list](/projects/)


<ProjectCard hideBorder=true>

  **[Rabot](https://github.com/Celthi/robot)**

  我的智能机器人，帮我处理重复，繁琐和机械化的工作，比如记录工作时间，运行集成测试，生成工单等等。极大提高了我的工作效率，让我不被各种琐屑的事情中断思路。

</ProjectCard>

<ProjectCard hideBorder=true>

  **[Core Analyzer]((https://github.com/yanqi27/core_analyzer))**
  Core maintainer

  一个被证明的调试内存问题的强大的工具。通过解析一个进程core dump或者存活地址空间的内存镜像，core analyzer可以遍历目标的堆数据结构，寻找内存损坏区域，搜索整个地址空间寻找数据对象的引用，或者分析内存模式等等。一个全面，免掉繁琐，并且有洞察性的工具。

</ProjectCard>


<ProjectCard hideBorder=true>

**[Melt Subtitles]((https://github.com/Celthi/meltSubtitles))**

自动翻译字幕中不认识的单词。通过它，看电影电视剧，也可以学习英语。

</ProjectCard>


<ProjectCard hideBorder=true>

**[Github Webhook Gateway]((https://github.com/Celthi/github-webhook-gateway))**

Rust编写的微服务，用于消费转发Github的事件，可以部署在Kubernetes，内存占用仅10~M。

</ProjectCard>

<ProjectCard hideBorder=true>

**[AI应用]((http://141.164.44.169/#/))**

GPT 应用，翻译，润色，AI机器人

</ProjectCard>

## 专利 & 认证

[Systems and methods for job-level memory governing](https://patents.google.com/patent/US20220058057A1/en?inventor=xianting+lu&oq=xianting+lu+) [1st Author]


(Systems and Methods for Server Crash Prevention)[https://patents.google.com/patent/US11789838B2/en?q=(Systems+and+Methods+for+Server+Crash+Prevention)&inventor=xianting+lu]

[Certified Kubernetes Application Developer (CKAD)](https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/daf55d86-dbdf-4dfe-9d10-790aab10cd4e-xianting-lu-ed5ee5ec-6a46-46c1-b067-cbaf09825d82-certificate.pdf)

## 受欢迎的文章
- [高效C/C++调试] 第二作者 ISBN: 9787302649717
- [你还在用GDB调试程序吗？](https://zhuanlan.zhihu.com/p/152274203)
- [Rust 系列：正确编程的思考模型](https://zhuanlan.zhihu.com/p/365845688)
- [什么是move？理解C++ Value categories，move， move in Rust](https://zhuanlan.zhihu.com/p/374392832)
- [玩了分手厨房，我理解了协程是什么](https://mp.weixin.qq.com/s/FjEVCxvmsu9hoMqS2zhvMA)
- [C++驿站](https://www.zhihu.com/column/c_1385152794127720448)
- [如何debug crash 系列](https://zhuanlan.zhihu.com/p/369006512)

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
