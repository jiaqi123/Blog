---
layout: default
title: 学习md
comments: true
---

#[JS核心] Javascript中的Arguments对象 

Javascript并没有重载函数的功能，但是Javascript核心中却有一个Arguments对象，能够让函数模拟重载。
Javascript在创建函数的同时，会在函数内部创建一个Arguments对象实例：arguments，每个JS们都对这个变量非常熟悉。
arguments是函数参数的数组，将它称为数组其实有些牵强，因为更确切地说它是一个Arguments对象实例，
但是它确实能够像数组一样用"[]"引用它的内部元素.

