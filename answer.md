# 第3次作業-作業-HW3
>
>學號：111111109
><br />
>姓名：張雅薰
><br />
>作業撰寫時間：15 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/12/08
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容
先fork老師的倉庫並clone 
```git
git clone
```
根據投影片CSS中垂直對齊之上標super，練習將(AST)改為下標
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    .sub{
        vertical-align: sub;
    }
    </style>
</head>
<body>
    指解析器，它是⼀種程式或⼯具，⽤來解析（分析）結構化的⽂本數據，並將其
    轉換為可供電腦理解的形式。解析器通常⽤於處理語⾔或標記語⾔中的⽂本，例
    如XML、HTML、JSON等。在程式設計中，解析器的常⾒應⽤是解析程式語⾔的
    源代碼。它會讀取原始的程式碼，並將其轉換為⼀個結構化的數據結構，通常是
    ⼀個抽象語法樹<span class="sub">(AST)</span>。這使得程式能夠更容易地被理解、分析和操作。
</body>
</html>
```
推上github
```git
git add 
git commit 
git push
```
## 個人認為完成作業須具備觀念


1.CSS 屬性的運用：了解 vertical-align 的使用方法特別是在文本中進行垂直對齊的情境。學習排版技巧，調整文本中不同元素的垂直位置，例如上標、下標。<br />
2.基本的 Git 操作：包括 fork 別人的倉庫、clone 倉庫到本地、add、commit、push 等基本的 Git 操作，以便管理程式碼版本。