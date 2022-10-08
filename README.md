# C++ Move Semantics
*The Complete Guide*

* 作者：Nicolai M. Josuttis

* 译者：陈晓伟

* 原文发布时间：2020年10月27日

> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

完整的介绍C++ Move语义。

C++11添加的Move语义已经成为现代C++的标志，也使语言变得复杂，即使经验丰富的开发者仍在需要仔细处理Move语义的细节。因为这个原因，一些编程书籍甚至不推荐对非常简单的类使用Move语义。所以，详细的解释C++ Move语义就变得刻不容缓。

本书会从基本原理开始来介绍Move语义，并会解释Move语义的所有细节，使每个开发者都可以正确地使用Move语义。

你将学习到：

* Move语义的起因和术语

* 如何隐式地获益于Move语义

* 如何明确地获益于Move语义

* 会遇到的所有问题，以及如何处理它们

* 所有的结果都取决于你的编程风格

重点在于所描述的特性，需要在实践中进行应用。示例和背景信息，有助于理解和改进简单类，甚至泛型库和框架的代码。



“我以为我理解了Move的语义，但我真的不懂!”我从你的书中学到了很多东西。”

(Jonathan Boccara)

“这是我需要很久的书。”

(Rob Bernstein)

“有时候我觉得我对纠缠和量子隐形传态的理解，要比我对一些奇怪的C++ Move语义的理解要好。套用Feynman的话：如果你认为你理解了C++的Move语义，那你就不理解C++的Move语义。赶快阅读这本书吧。”

(Victor Ciura)

## 作者简介

Nicolai Josuttis (<http://www.josuttis.com>)在编程界很有名，因为他的发言和著作都很有权威，还是世界范围内畅销书的(共同)作者：

* 《The C++ Standard Library》

* 《C++ Templates》

* 《C++ Move Semantics》

* 《C++17》

* 《SOA in Practice》

同时也是一位富有创新精神的演讲者，曾在各种会议和活动中发言。还是独立的讲师，并且在C++标准化方面有20多年的经验。

## 本书相关

* github翻译地址：<https://github.com/xiaoweiChen/CPP-Move-Semantics>