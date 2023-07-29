# Redundant Page Deleter

之前在研究所的時候，都有類似的問題。因為pdf的簡報不能有動畫功能，所以會有講者把一頁拆成好幾頁，這好幾頁的差異就只是多了或少了一段文字，就成功有動畫效果了。但是對於學生來說，這樣的pdf是很痛苦的，因為會把原本可能十幾頁的文件變成三十幾頁。例如在 [introduction to statistical learning](https://www.statlearning.com/) 的其中一個講義中，被拆成4頁的樣子:

During my time in the research institute, we often encountered a similar issue. Since PDF presentations don't have animation functions, some speakers would divide a single slide into several slides. The difference between these slides would only be the addition or removal of a piece of text, thus achieving an effect similar to animation. However, this type of PDF is quite painful for students, as it can turn a document that might originally be only a dozen pages into over thirty. For instance, in one of the lectures from [Introduction to Statistical Learning](https://www.statlearning.com/), there are 4 pages like following:

![](https://static.coderbridge.com/img/ar851060/0912c9bee8284ace89eae41938ae0de3.gif)

所以我做了一個code，目前存在colab裡面。目前只能解決有頁碼的pdf，之後功能再說啦。
So, I create a function, and save in colab. Now, it just solve the problem for the pdf with page number.
