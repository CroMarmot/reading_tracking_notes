---
layout: post
title: "编程之美个人整理"
description: "基于个人已有知识整理"
category: [日志]
tags: [算法]
---

# 总评

整理开始日期:2017-01-23

整理结束日期:2017-06-21

如果你是准备学习算法，那么我非常不建议看这本书,去系统性的多刷刷题吧。

本书适用人群:觉得无聊想了解一下算法有什么用的人，准备参加大公司面试，且技术方面已经准备好的人，学习累了想消遣一下的人。

## 第一章 游戏中碰到的题目

|章节|标题|整理|
|---|---|---|
|1.1|关于cpu的/window的相关|主要用于装逼，和后面的题目毫无相似性|
|1.2|中国象棋将帅的问题|最基础的编解码+C的struct知识|
|1.3|一摞烙饼的排序，对一个数组每次取首部任意个进行翻转求最少次数|深搜枚举剪枝 扩展问题很棒|
|1.4|买书，n(<6)种物品每件物品价格相同，当同时买k种不同的物品各一件时将会有f(k)=((2,3,4,5)=>(5%,10%,20%,25%)的折扣)求最大折扣|动规|
|1.5|快速找出故障机器，找唯一的仅出现一次的数|位表示|
|1.6|饮料供货，每个饮料容量为2的幂，|记忆dp/基于数字特征的贪心|
|1.7|光影切割问题|。。。|
|1.8|小飞的电梯调度算法，一堆整数的整数差值最小|。。。|
|1.9|高效率地安排见面会|图着色问题|
|1.10|双线程高效下载||
|1.11|NIM（1）一排石头的游戏|维持和问题|
|1.12|NIM（2）“拈”游戏分析|反向递推博弈转化 XOR的转换和维持|
|1.13|NIM（3）两堆石头的游戏|反向递推博弈转化 质数筛法！|
|1.14|连连看游戏设计|。。|
|1.15|构造数独|生成再去除|
|1.16|24点游戏|注意分数。。|
|1.17|俄罗斯方块游戏|如何移动旋转 估分(洞 过高)|
|1.18|挖雷游戏|？？？|

## 第2章 数字之魅——数字中的技巧

|章节|标题|整理|
|---|---|---|
|2.3|寻找发帖“水王”|求出现次数超过1/2的数|
|2.7|最大公约数问题|剔除了同偶数共除2和有偶数去2的优化|
|2.8|找符合条件的整数|寻找1、0组成的能整除的被除数 利用数值特性余数进行效率优化|
|2.20|程序理解和时间分析||

## 第3章 结构之法——字符串及链表的探索

|章节|标题|整理|
|---|---|---|
|3.6|编程判断两个链表是否相交|链表成环问题|
|3.11|程序改错||

## 第4章 数学之趣——数学游戏的乐趣

|章节|标题|整理|
|---|---|---|
|4.1|金刚坐飞机问题||
|4.3|买票找零|卡特兰数|
|4.4|点是否在三角形内|计算几何 向量叉乘|
|4.5|磁带文件存放优化|数学。。|
|4.6|桶中取黑白球|奇偶分析6666666 感觉可以加入洗脑密卷豪华套餐|
|4.7|蚂蚁爬杆|等效转化！|
|4.8|三角形测试用例|编码 测试用例应当足量|
|4.9|数独知多少|思路与估值|
|4.11|挖雷游戏的概率||
