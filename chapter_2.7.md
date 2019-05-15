## 章節 2：計算統計學 (Computational Statistics)

### 2.7 討論

這章介紹 Suite 類別，用來封裝貝葉斯更新的框架。

Suite 是一個**抽象型別（abstract type）**，這表示 Suite 定義一個介面；一些應該要有方法但不一定會全部都有實作。例如 Suite 介面包含 Update 和 Likelihood 方法，但是 Suite 只有提供 Update 方法的實作，但是 Likelihood 方法則無。

**具體型別（concrete type）**是一個繼承自抽象母型別的類別，並且實作母型別中沒有實作的方法。例如 Monty 類別繼承 Suite 類別，所以Monty 類別也擁有 Update 方法跟 Likelihood 方法。

如果你熟悉設計模式（design patterns），你可能知道這是一個**樣板方法模式（template method pattern）**。

接下來章節中，大部分的範例都是遵循此模式；對於每個問題，我們定義一個新個類別繼承 Suite 類別，利用其 Update 方法，並且實作 Likelihood 方法。只有在少數的範例中，我們會覆寫（override）Update 方法，通常是因為要改進效率。