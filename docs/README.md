---
pageClass: home-page
# some data for the components

name: Xianting Lu
profile: /profile.jpeg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/Celthi
  - title: Zhihu
    icon: "/icons/zhihu.svg"
    link: https://www.zhihu.com/people/lan-tian-89

bio: Programmer/Blogger
email: Evan_L00@qq.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me
Problems solver, focusing on full text search, high performance server development with C++.

Programming Languages: C++/Rust/Java/Rust, Python/Typescript/Javascript/, etc.

Tools: Kubernetes/Docker/CoreAnalyzer/Bash/...



## Experiences

- [2021 July - Now] MicroStrategy China Technology Center, Senior Engineer

  - Lead and implement the Time zone aware data analysis object models.
  - Co-authorized the OCR (One comment running integration test) which is adopted by all the engineers in their daily development.
  - Implement and patent the Systems and Methods for Server Crash Prevention [3rd Author, in-process].


- [2019 Feb - 2021 July] MicroStrategy Head Quarter, Washington DC, Engineer

  - Next generation global search with Elastic Search.
  - Containerized legacy integration test with K8S, Author the CAT (Containerized ABA Test Manager) with NodeJS.


- [2017 May - 2019 Feb] MicroStrategy China Technology Center, Engineer

  - MicroStrategy Metadata management and several key components maintenances like Drilling Data, Metadata Server.
  - MicroStrategy Search Engine (Lucene as core) enhancements and maintenances.



## Education

- **Southeast University** <br/>
Sept 2014 - 2017, Information and Communication Engineering

- **Tianjin University** <br/>
Sept 2010 - 2014, Communication Engineering

- **Nankai University** <br/>
2012–2014 Minor, School of Economics

## Projects

[→ Full list](/projects/)


<ProjectCard hideBorder=true>

  **[Rabot](https://github.com/Celthi/robot)**

  A intelligence robot handle all the duplicates, tedious works for me, like record time sheet, triggering integration test, etc.

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

## Patents & Certificates

[Systems and methods for job-level memory governing](https://patents.google.com/patent/US20220058057A1/en?inventor=xianting+lu&oq=xianting+lu+) [1st Author]


Systems and Methods for Server Crash Prevention [3rd Author, in-process]

[Certified Kubernetes Application Developer (CKAD)](https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/daf55d86-dbdf-4dfe-9d10-790aab10cd4e-xianting-lu-ed5ee5ec-6a46-46c1-b067-cbaf09825d82-certificate.pdf)

## My Top Tech Blogs

- [你还在用GDB调试程序吗？](https://zhuanlan.zhihu.com/p/152274203)
- [什么是move？理解C++ Value categories，move， move in Rust](https://zhuanlan.zhihu.com/p/374392832)
- [两大绝招debug core dump?](https://zhuanlan.zhihu.com/p/444389626)
- [Rust那些难理解的点](https://zhuanlan.zhihu.com/p/360342782)
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
