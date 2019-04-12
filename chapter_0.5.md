# 章節 0: 前言

## 0.5 閱讀本書的先決條件

市面上有很多用 Python 做的非常好的貝葉斯統計模組，像是 [PyMC](https://github.com/pymc-devs/pymc3) 和 [OpenBUGS](http://www.openbugs.net/w/FrontPage)。

我選擇在本書中不使用這些模組，因為你需要不少的背景知識才能開始使用這些模組，並且我想要最少的先決條件。也就是説**你懂 Python 並且也懂一些機率，那麼你就可以開始閱讀本書了**。

第一章是關於機率與貝葉斯定理不需要原始碼。第二章介紹機率質量函數 (Probability Mass Function) ，我用 Python 的 dictionary 來去代表一個 PMF 。接著第三章介紹 Suite ，這是一種 PMF ，它提供了一個貝葉斯更新(Bayesian updates)的框架。

在後面的一些章節中，我用解析分佈，包括高斯分佈（Gaussian distribution）、指數分佈（Exponential distribution）、帕松分佈（Poisson distribution）以及 Beta 分佈。

第十五章中，我會介紹一個不常見的 Dirichlet 分佈，但是我不會講述太多細節。如果你不熟悉上述的分佈，你可以在維基百科上閱讀相關資料。你也可以閱讀我撰寫的另一本關於統計的書籍 [Think Stats](https://greenteapress.com/wp/think-stats-2e/)，或是閱讀其他統計入門的書籍（我擔心這對於實際應用幫助不大，因為大多統計書籍是用數學方法撰寫）。