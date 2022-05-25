---
layout: default_2
category: Research
title: Research
nav_order: 2
---

# Research

## On the Classification of Networks Using Graph Scattering

## On the Inversion-Free Newton Algorithm

## On the Existence of Induced H-Saturated Graphs

## Network Reliability Using Graph Coloring

## Counting Triangles Using Combinaotrics
Given $$n$$ lines within an arrangement $$\mathcal{A}$$ projected on $$\mathbb{R}^2$$, how many triangles are formed as a result? For example, how many triangles, $$\Delta$$, exist within the following arrangement?:

<p align="center">
<img src="assets\img\triangles1.jpg" alt="drawing" width="300"/>
</p>

Observe that the following two conditions hold in $$\mathcal{A}$$:

1. There exist no intersection point with more than two lines
2. and there exist no pairwise set of parallel lines

In <a href="https://www.nytimes.com/2019/08/21/science/math-equation-triangles-pemdas.html?unlocked_article_code=AAAAAAAAAAAAAAAACEIPuomT1JKd6J17Vw1cRCfTTMQmqxCdw_PIxftm3iava3DFDmwbiP8eAoWG8EqKYKN_Z54-ximSWN5GNvozXv17yOBbMlcoUwStrpKf3pQZJiF_4aSCYlQL5bOfF7Yp7W2tKWCjNOZ0wLD44kLaOzbrXKHAgnZyJhJi8pRgaQmv3nQXkavGR7Z-2td82_cjFYk6EWlbHFSCufLjDxx1PtuUPFqLukRtBbYvCXyElsWc6rkAbAxUFVnNKXt46m8749lZU8gFaOe9d1VzPZqj3shCTzBgP4yrBJYuRoTLlLUMsbLFqBCEysTe1OyTEozl8_G1Db-lHaE7BIVZ&smid=em-share">this New York Times article</a>, Po Shen Loh, the national coach of the IMO team, found the following solution for such an arrangement $$\mathcal{A}$$ under the aforementioned conditions

$$\Delta = C(n,3) = {n \choose 3}.$$

In our paper, we found the following solution, counting the number of triangles with **no** assumptions

$$\Delta = C(n,3) - \sum_{i=3}^nk_iC(i,3) - \left(\sum_{i\neq j}C(|P_i\cup P_j|,3) - (t-2)\sum_{i=1}^tC(|P_i|,3)\right)$$

where we define $$k_i$$ as the number of intersetion points with $$i$$ intersecting lines. Additionally, we partition the set of lines in the arrangement $$\mathcal{A}$$ into sets $$P_1$$, $$P_2$$, . . . , $$P_t$$, where lines $$\ell$$ and $$\ell'$$ are both in the same partition set $$P_i$$ if and only if $$\ell$$ and $$\ell'$$ are parallel.

This means we can find $$\Delta$$ if we know the following information about $$\mathcal{A}$$:
  1. the total number of lines $$n$$
  2. all $$k_i$$'s s.t. $$i > 2$$
  3. all partition sets (more specifically their cardinality)

This allows us to find $$\Delta$$ for the followin complex arrangement

<p align="center">
<img src="assets\img\Figure7.jpg" alt="drawing" width="300"/>
</p>

## Metareasoning in Autonomous Systems


[back](./)
