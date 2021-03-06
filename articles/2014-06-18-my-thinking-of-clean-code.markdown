---
layout: post
title: "我對 Clean Code 的想法"
date: 2014-06-18 18:33:20 +0800
comments: true
categories: ["clean code", "think"] 
keywords: clean code, joy of code, well structured
description: "如果對我稍微有認識的工程師，應該會知道我對架構和 clean code 很龜毛（我自己是說有潔癖）。過去以來寫過很多東西、碰過很多雷，因此也對乾淨的架構和程式碼很追求。"
references: [{title: "", link: ""}]
hero: "https://farm4.staticflickr.com/3873/14427724086_5e49214af0_o.png"
---

如果對我稍微有認識的工程師，應該會知道我對架構和 clean code 很龜毛（我自己是說有潔癖）。過去以來寫過很多東西、碰過很多雷（自己過去埋的），因此也對乾淨的架構和程式碼很追求。再加上我覺得這兩個東西做好，其實是在「做功德」，因為不會除了不會造成未來的自己的麻煩，也不會給協同合作的人麻煩。

<!-- more -->

# 什麼是好的架構和乾淨的程式碼？

其實這個部分應該要從物件導向程式語言講起，但是講三天三夜應該也講不完。所以從我實務的經驗的心得講吧！

我過去學程式語言的方式應該算是阿甘式的學習：*如果能自幹就先自幹看看，如果有 opensource library 可以用，我就試著做個一模一樣的輪子出來。*

所以自幹的東西小從一些 helper class，一些 framework 的模組，甚至是輕量的 PHP MVC 架構（這時候才知道，原來寫架構要顧慮這麼多東西）。從這個學習歷程走過來，從模仿中學到很多怎麼包東西、怎麼接參數、不同架構什麼該丟什麼不該丟的寫法等等。因此也沒有知道什麼專有名詞，就是知道大概怎麼做。從此而慢慢學到，怎麼寫乾淨的程式碼，才不會害到未來的自己看到會不想改；或是要引用的時候該丟出來的東西沒有丟出來。

所以我的想法是

> 好的程式碼應該是，好讀好改，不會罵髒話；好的架構是，要用不麻煩，要改不至於翻過來大改

我不想帶一些專有名詞，因為用錯就囧了 XD
