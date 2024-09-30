---
title: 学习日记
tags: [study]
published: true
date: 2024-09-26
updated: 2024-09-26 09:40
categories:
index_img:
archive:
password:
excerpt: 每天学习内容的记录。
sticky: 90
---
# 学习记录

希望能（几乎）每天都保持学习，每天都学到一点东西，或者做一点努力。目标是每天的学习工作，能写下至少一句话。
## 2024-09-30 周一
中午和老板讲了一下前几天学的东西。
## 2024-09-29 周日
又看了那个nagata surface的分解，也是projective bundle. 有一个blow up搞不明白
$$
\mathcal{F}_{n-1,n}^{n} \to \mathcal{F}_n
$$
多学了一些相交数，但是其实$\overline{NE}(X_\Sigma)$还是不清楚，这样的话构造minimal model 有点费劲，除非加个boundary得到trival foliated log canonical divisor。只是这样的话有点丑陋。  
除此之外还差一个lc的singularity条件要验证。
## 2024-09-28 周六
白天骑车，没学习。
把昨天的内容敲了点latex，在overleaf上共享给老板了。希望国庆假期可以搞完并且最终加到论文里。

## 2024-09-27 周五
学了projective bundle的toric描述，主要是$\mathbb(\oplus \mathcal{O}(a_i)) \to \mathbb{P}^s$的情况。这个情况就是之前atiyah flop及其推广的例子，可以做一些具体的计算。大概是清楚各自的fan是什么，以及blow up对应的是什么。  
但是intersection number还没算清楚，能搞出来foliation flop，但是还没搞出来minimal model.  
另外，这些和那个rolled surface或者说$\mathbb{F}_n$的elementary transform似乎有关系，也能推广。如果这样的话，可能可以把这些和toric foliation联系起来。

## 2024-09-26 周四
上午师弟讲foliation，没听。  
吃完饭和老板讲了一下看的例子。toric似乎很有搞头。

## 2024-09-25 周三
继续看flip/flop的例子，查了一些文献，发现其实总够就两个，一个是最原始的（用来证明三维MMP不可行的）例子，一个是Debarre的projective cone over segre embedding of $\mathbb{P}^r\times \mathbb{P}^s$.  
好像更清楚了点，但是不知道怎么用toric写，也就不太能搞出来toric foliation的构造。

## 2024-09-24 周二
上午和老板讨论了toric flop的例子，讲了一点toric foliation. 似乎把atiyah flop强行加boundary就是foliation flop或flip.  
但是还差很多计算。以及要考虑怎么变成projectiv的。下午学了一会儿toric。

## 2024-09-23 周一
今天上午有报告，但是没听。去了，因为Jihao Liu在。

中午讨论了一下，主要是关于foliated Sarkisov Program. Liu的意思是，似乎可以考虑adjoint foliation，即$K=tK_{\mathcal{F}}+(1-t)K_X +B+M_X$，这个太复杂了。  
我的想法是用Hacon McKernan的方法，用divisor的polytope分解。可能要把BCHM的主要定理全部重写，不过应该不怎么用归纳。重点是decomposition的定理，和finiteness of LCM/AM/WLCM/LTM。难点是所有对klt的toggle boundary操作都要放到nef part。这样polytope $\mathcal{E}_A(V)$的定义要修改，要把nef part也放进去。   
有机会，但是也许不大。
