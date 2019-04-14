# 章節 0: 前言

## 0.1 作者的理論

跟其他 Think X (例如 Think Java, Think Stats 作者出版的其他書籍) 系列的書籍一樣，我認為如果你懂得撰寫程式，那你也可以利用此技能去學習其他的主題。

大多數講述貝葉斯統計的書籍利用數學符號來表達其想法，例如微積分等等數學概念。本書用 Python 程式碼代替數學表示，用離散近似(discrete approximations) 取代連續的函數表示。因此，大部分的積分 (integral) 操作將變成加法操作，而且機率分佈的操作都是由簡單的迴圈構成。

對於會撰寫程式的人來說，我認為本書是相對容易理解的。這也更為通用，因為在模型選擇時，我們可以利用撰寫程式找到更適合的模型，而不需要用傳統的模型分析方法。

```
It is also more general, because when we make modeling decisions, we can choose the most appropriate model without worrying too much about whether the model lends itself to conventional analysis.
```

此外，本書由淺入深的介紹簡單的例子到實際世界的問題。例如第三章節，一開始從一個基礎機率常用的骰子範例開始。接著，從骰子問題慢慢演變到 locomotive 問題（這個問題我借用自 Mosteller’s Fifty Challenging Problems in Probability）；再從 locomotive 問題演進到一個貝葉斯方法應用在第二次世界大戰的範例，德國坦克問題。

