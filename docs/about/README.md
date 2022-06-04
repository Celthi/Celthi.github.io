---
pageClass: about-page
description: 'The biography and information about me.'
avatar: /profile.jpg
head: 'Xianting Lu'
info: 'Programmer/Blogger'
interests: 'Programming and Movies'
socials:
- title: github
  link: https://github.com/Celthi
- title: linkedin
  link: https://www.linkedin.cn/incareer/in/%E5%AE%AA%E5%BB%B7-%E5%8D%A2-4513a6117
- title: email
  link: 'mailto:evan_l00[at]qq.com'
actions:
- text: Projects
  link: /projects/
- text: Blog
  link: https://www.zhihu.com/people/lan-tian-89

footer: Made with ♥ Xianting Lu. Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >


</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)
  
  .last-updated
    display none

</style>
