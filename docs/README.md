---
pageClass: home-page
# some data for the components

name: Xianting Lu
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
bio: Programmer, write blog sometimes
email: Evan_L00@qq.com
phone: +86l8667024392
cv: https://raw.githubusercontent.com/Celthi/Celthi.github.io/master/Xianting%20Lu.pdf
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me
Focusing on LLM/GPT applications with data analysis, high stable/parallel/distributed server development, event-driven asynchronous architecture with C++/Rust, enterprise search.

Maintained 4M+ line of C++ code, according to enterprise Github, I have contributed 150k+ LOC (C++/NodeJs/Python/Rust) and fixed 500+ defects.

Book **Effective C/C++ Debugging** and two series: [Rust 系列：正确编程的思考模型](https://zhuanlan.zhihu.com/p/365845688), [C++驿站](https://www.zhihu.com/column/c_1385152794127720448)

Programming Languages: C++/Rust/Java/, Python/Typescript/Javascript, etc.

Tools: kubernetes/Lucene/Container/gdb/CoreAnalyzer/Message Queue/Bash, etc.



## Experiences

- [2023 Mar - Now] Large language models empowering data analysis, ChatGPT prompting, GPT models.
  
  - Designed and Implemented the MicroStrategy Auto Answer. 
  
  - Iterated MicroStrategy Auto Answer with major improvement.
  
  - AI Chatbot Integration:
  
    - Seamlessly integrated Langchain with the MSTR dossier model, marking the creation of our inaugural chatbot demo.
    - Skillfully navigated through numerous challenges such as the CodeAI tool, memory loss issues, fragile prompts, and handling multiple responses to single inquiries.
    - Pioneered the setup for the World demo environment.
  
  - AI API Key Provider:
    - Conceptualized and executed the AI API key provider object model, privilege, and feature flag for FFSQL+AI(F38939) in Q2 2023.
    - Indispensable to the release of MSTR's maiden AI feature.
  
  - AI Assistant Development:
     - Championed the design and rollout of various AI assistant components, like the output parser, MSTR chat agent, and Multiple Action tools.
    - Played a key role in the team's rapid understanding and use of the codebase and Langchain for AI assistant creation.
  
  - Machine Learning Package:
  
    - Spearheaded the development of the MSTR machine learning package titled "mstrai", focusing on crafting and packaging the Keydriver Python algorithm for F39080.
    - Identified and rectified a significant performance bottleneck, slashing response times from 40 seconds to a mere second by optimizing package loading.
  - 
  - AI Service Design and Transformation:
  
    - Ingeniously transformed the AI service from a model supporting single-user, single-request engagements to a robust asynchronous framework.
    - This change now supports multiple users interacting with the AI Assistant concurrently.
    - Achieved a commendable shift from Python to JS for the Q3 development milestone
  
- [2021 July - 2023 Mar] MicroStrategy China Technology Center, Senior Engineer, C++ infrastructure, +Rust, +Python, etc.

  - Design and implement the OCR Service(One comment running integration test) which dispatches tests into machine cluster by one comment, and is adopted by more than 65 engineers in their daily development and saving thousands of engineering hours.

  - Lead the Time zone aware data analysis object models (serialize/deserialize infrastructure) to bring the capacity customers requested for a long time into the MicroStrategy platform and  ,.

  - Implement and patent the Systems and Methods for Server Crash Prevention [3rd Author, in-process] to eliminate the hard-to-reproduce server crashes.
  
  - Design and implement the async infrastructure for MicroStrategy package manipulations.


- [2019 Feb - 2021 July] MicroStrategy Head Quarter, Virginia Tysons, Engineer, +NodeJs, +Kubernetes, etc.

  - Core engineer of the next generation global search microservice with Elastic Search, research Kafka/Rabbit for indexing, design and implement the modules: query parser, search autocompletion, i18n support, user mention, etc.

  - Containerized MicroStrategy legacy integration tests with K8S, and build the server CAT (Containerized ABA Test Manager) with NodeJS to provide consistent testing results, quick deployment (minutes vs hours), high utilization rate, resource saving, etc.
  
  - Lead and implement the memory governing component for high stable services(Patented, 1st author) and refine the high parallel Job infrastructure to provide job memory governing and throttling protection functionalities to prevent server crashing from malicious or high-volumes loads.

  - Lead and implement the tool to help the elite customer Inditex to upgrade to MicroStrategy latest products. The tool is integreated into products to serve more customers.


- [2017 May - 2019 Feb] MicroStrategy China Technology Center, Engineer, Data model serialize infrastructure, Java Lucene, etc

  - MicroStrategy next generation repository service with MongoDB research from relation store to document store.

  - MicroStrategy Metadata management and several key components maintenances like Drilling Data, Security.

  - MicroStrategy Search Engine (Lucene as core) enhancements and maintenances.

  - Server crashes analysis  like multithread issues, memory corruption(double free, use after free, etc.).

  - C++ memory detections and summarized 10 memory patterns and educated the whole company engineers.


## Education

- **Southeast University** <br/>
Sept 2014 - 2017, Information and Communication Engineering

- **Tianjin University** <br/>
Sept 2010 - 2014, Communication Engineering

- **Nankai University** <br/>
2012–2014 Minor, School of Economics

## Open Source Projects

[→ Full list](/projects/)


<ProjectCard hideBorder=true>

  **[Rabot](https://github.com/Celthi/robot)**

  A intelligence robot handle all the duplicates, tedious works for me, like record time sheet, triggering integration test, etc. With it, I can focus my work and free from unnecessary interruptions.

</ProjectCard>

<ProjectCard hideBorder=true>

  **[Core Analyzer]((https://github.com/yanqi27/core_analyzer))**
  Core maintainer

  A proved powerful tool to debug memory issues. By parsing the memory image of a process's core dump file or its live address space, core analyzer is able to scan the target's heap data for memory corruption, search the whole address space for data object's references, or analyze memory pattern. It is thorough, labor-free, and insightful. 

</ProjectCard>


<ProjectCard hideBorder=true>

**[Melt Subtitles]((https://github.com/Celthi/meltSubtitles))**

Translating unknown words in video subtitles. With it, you can learn English while watching movies/TV series.

</ProjectCard>

<ProjectCard hideBorder=true>

**[Github Webhook Gateway]((https://github.com/Celthi/github-webhook-gateway))**

A micro service written in Rust to consume the Github Webhook events. Deployable inside Kubenetes and memory footprint 10~M.

</ProjectCard>

## Patents & Certificates

[Systems and methods for job-level memory governing](https://patents.google.com/patent/US20220058057A1/en?inventor=xianting+lu&oq=xianting+lu+) [1st Author]


(Systems and Methods for Server Crash Prevention)[https://patents.google.com/patent/US11789838B2/en?q=(Systems+and+Methods+for+Server+Crash+Prevention)&inventor=xianting+lu]

[Certified Kubernetes Application Developer (CKAD)](https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/daf55d86-dbdf-4dfe-9d10-790aab10cd4e-xianting-lu-ed5ee5ec-6a46-46c1-b067-cbaf09825d82-certificate.pdf)

## My Top Tech Blogs
- [Effective C/C++ Debugging] 2nd Author ISBN: 9787302649717
- [你还在用GDB调试程序吗？](https://zhuanlan.zhihu.com/p/152274203)
- [Rust 系列：正确编程的思考模型](https://zhuanlan.zhihu.com/p/365845688)
- [什么是move？理解C++ Value categories，move， move in Rust](https://zhuanlan.zhihu.com/p/374392832)
- [玩了分手厨房，我理解了协程是什么](https://mp.weixin.qq.com/s/FjEVCxvmsu9hoMqS2zhvMA)
- [两大绝招debug core dump?](https://zhuanlan.zhihu.com/p/444389626)
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
