---
layout: post
title: 拥抱异常，拥抱变化
---

最近，在知乎上看到一个话题，关于异常处理的，讨论很激烈，话题本身跟我今天想表达的没什么关系，就不说了。不过这个话题倒是引发了我的一些思考。我这几年一直在做软件系统开发，从原型设计到接手完全陌生的系统进行运维和定制，遇到了很多挑战。不过也正是这些实战，让我有机会对原来零散学习的计算机专业知识进行系统的整理和反思。异常就是我觉得最困难也是最有意思的。一个复杂软件的设计和实现中最关键的要素其实应该就是它，但是它并不能显性的体现一个软件的价值，这导致了它常常被忽视，然后软件就越来越难于驾驭以致僵化。

现有的软件工程通常只是对需求进行了重点描述，在实践过程中我们常常将某些异常当作需求，并在此基础上对系统进行设计和开发。然而这时我们仍然缺乏对异常的系统认识和建模，导致我们设计的系统缺乏鲁棒性，我们的系统就像有着一颗玻璃心，脆弱易碎。我们必须在开放封闭原则的基础上对异常进行系统的设计和实现，这样我们的系统才可能是稳定的，并且适应不断的变化的。
