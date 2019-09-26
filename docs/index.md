---
title: Talk slides template
tags: Templates, Talk
description: View the slide with "Slide Mode".
---

#  <font color="#dd0000">我要介紹JOJO</font>


<!-- Put the link to this slide here so people can follow -->
slide: https://www.google.com/imgres?imgurl=https%3A%2F%2Fi.ytimg.com%2Fvi%2Fu9YriiExAwQ%2Fmaxresdefault.jpg&imgrefurl=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3Du9YriiExAwQ&docid=FDioJLf1FkMcqM&tbnid=S8GrJ2711NpbyM%3A&vet=10ahUKEwja3fuvue7kAhU-yosBHXeHA7AQMwhPKAAwAA..i&w=1280&h=720&bih=693&biw=1340&q=JOJO&ved=0ahUKEwja3fuvue7kAhU-yosBHXeHA7AQMwhPKAAwAA&iact=mrc&uact=8

---

要講JOJO一定要先從幻影血脈講起!
有請......
# **大喬!!!!!**

![](https://img.moegirl.org/common/thumb/7/77/Jonathan_ASB.jpg/200px-Jonathan_ASB.jpg)

---

再來有請我們各種騷包車技的老司機
# 二喬!!!

![](https://img.moegirl.org/common/f/f9/F020e93fcb2bb334650a7328a938cbd0.jpg)

---

再來是我們永遠的龍傲天 有請.....
# 三喬!!!
![](https://gss0.bdstatic.com/-4o3dSag_xI4khGkpoWK1HF6hhy/baike/w%3D268%3Bg%3D0/sign=b083ae4f3efa828bd1239ae5c5242609/54fbb2fb43166d2243f73fde4b2309f79152d2f3.jpg)

---
{%youtube u9YriiExAwQ %}

---



### Usage flow

---


```graphviz
digraph {
  compound=true
  rankdir=RL

  graph [ fontname="Source Sans Pro", fontsize=20 ];
  node [ fontname="Source Sans Pro", fontsize=18];
  edge [ fontname="Source Sans Pro", fontsize=12 ];


  subgraph core {
    c [label="Hackmd-it \ncore"] [shape=box]
  }
  
  c -> sync [ltail=session lhead=session]

  subgraph cluster1 {
     concentrate=true
    a [label="Text source\nGithub, Gitlab, ..."] [shape=box]
    b [label="HackMD Editor"] [shape=box]
    sync [label="sync" shape=plaintext ]
    b -> sync  [dir="both"]
    sync -> a [dir="both"]
    label="An edit session"
  }
}
```



### Thank you! :sheep: 

You can find me on

- GitHub
- Twitter
- or email me
