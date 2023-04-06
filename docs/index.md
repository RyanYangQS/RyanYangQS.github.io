---
layout: home
layoutClass: 'm-home-layout'

hero:
  name: 个人博客
  text: 
  tagline: 不爱摄影📷的前端，不是好前端😂
  image:
    # src: /logo.jpg
    alt: 打，打个大西瓜
  actions:
    - text: 前端导航
      link: /nav/
      theme: alt
features:
  - icon: 📖
    title: 前端杂谈
    details: 汇总前端常用知识点<br />
  - icon: 📘
    title: 源码阅读
    details: 站在巨人肩膀上学习
  - icon: 💡
    title: 面试技巧
    details: 汇总经典面试题&担任面试官的经验
  - icon: 🧰
    title: 提效工具
    details: 工欲善其事，必先利其器<br />记录开发和日常使用中所用到的软件、插件
  - icon: 🐞
    title: 踩坑爬坑
    details: 踩过的坑不能掉下去两次
  - icon: 💯
    title: 热爱摄影，热爱生活
    details: '<small class="bottom-small">—— 一个喜欢摄影的前端小菜鸟</small>'
---

<style>
.m-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 59s 1s cubic-bezier(0.3, 0, 0.8, 1);
}

.m-home-layout .details small {
  opacity: 0.8;
}

.m-home-layout .bottom-small {
  display: block;
  margin-top: 2em;
  text-align: right;
}
</style>
