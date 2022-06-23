# RBtreeManim

這個專案使用 Manim 實作 RBtree 的視覺化呈現，主要呈現 RBtree 在經過 insert 和 delete 操作後所發生的結構變化。

視覺化參考對象：
https://www.cs.usfca.edu/~galles/visualization/RedBlack.html

### Manim

Manim 是一個由 Standford 大學的 Grant Sanderson 所開發的動畫渲染引擎，並且 Grant Sanderson 將這套引擎使用在他的 Youtube 數學教學頻道上（https://www.youtube.com/c/3blue1brown），Manim 主要的優點是能夠使用 python 將動畫渲染出來，使得動畫變得可程式化，且因為程式可精確的描述每個動畫物件的位置和各項資訊，所以 Manim 特別適合用作數學教學以及資料結構圖像化等精確性要求比較高的動畫。

目前在網路上有三個常用的 Manim 版本，分別由不同的社群或是由 Grant Sanderson 本人所維護：

* manimCairo

最早 Grant Sanderson 所使用的版本，但該版本已經在 2020/11 停止維護。

* manimGL

目前 Grant Sanderson 所維護的版本，並使用在其 Youtube 數學教學頻道上，以下為 manimGL 的 github 位置： https://github.com/3b1b/manim

* manimCE

是 2020 年由另外一個社群 fork 出來的版本，因為由更多人維護，社群也很活躍，所以穩定性更高，也是本專案主要使用的版本。

github：
https://github.com/ManimCommunity/manim/

documentation:
https://docs.manim.community/en/stable/

discord:
https://discord.com/invite/mMRrZQW

### 參數設定