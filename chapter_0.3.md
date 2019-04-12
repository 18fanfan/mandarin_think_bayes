# 章節 0: 前言

## 0.3 使用原始碼

你可以在此[連結](https://github.com/AllenDowney/ThinkBayes)找到本書中使用的原始碼與聲音樣本。Git 是一個版本控制系統，你可以用它追蹤專案中的文件修改記錄。一份在 Git 版本控制下的文件集合就稱為一個存儲庫（repository）。GitHub 是一個託管服務 (hosting service)，它提供 Git 存儲庫所需要的空間以及易於操作的網頁介面。

這邊提供幾種方式讓你使用我在 GitHub 上儲存庫的原始碼：

- 你可以在 GitHub 上點擊 Fork 按鈕來複製我的儲存庫，但你必須先建立一個 GitHub 帳號。在 Fork 之後，你的 GitHub 上有一份自己的儲存庫，你便可以追蹤你在閱讀本書時所編寫的原始碼。然後你可以 Clone 此儲存庫到你的本機電腦中。
- 你也可以直接 Clone 我的儲存庫。如此你就不需要申請 GitHub 帳號，但你也無法將你對原始碼的更動上傳到 GitHub。
- 如果你根本不想使用 Git ，你可以直接點擊下載按鈕，直接將儲存庫打包成 Zip 並且下載。

本書第一版的原始碼是用 Python 2 所撰寫。如果你是使用 Python 3 ，則可能需要用此[連結](https://github.com/AllenDowney/ThinkBayes2)的程式碼。

我用 Anaconda 撰寫本書中的原始碼，這是一套免費的 Python 發行版，它包含了你執行程式所需要的套件（甚至更多）。Anaconda 很容易安裝。原始設定下，它是 user-level 安裝而不是 system-level 安裝，也就是說你不需要有管理員的權限便能安裝。你可以在[這裡](https://www.anaconda.com/)下載 Anaconda 。

如果你不想使用 Anaconda ，你將需要下列的套件：

- Numpy 基礎數值運算套件，[連結](http://www.numpy.org/)
- SciPy 科學運算套件，[連結](https://www.scipy.org/)
- Matplotlib 數據視覺話套件，[連結](https://matplotlib.org/)

雖然上述是常見的套件，但不包含在所有的 Python 預設安裝內，而且這些套件可能在某些環境下不易安裝。如果你在安裝上述套件遇到問題，我建議你使用 Anaconda 或是其他有包含上述套件的 Python 發行版。

本書中多數的原始碼範例使用到的 class 和 function 是定義在 thinkbayes.py，而有些是在 thinkplot.py 包裹程式（wrapper）中，它包裹了一些在 matplotlib.pyplot 中的函式。
