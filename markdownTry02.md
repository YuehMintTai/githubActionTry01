# 使用markdown技巧:貼圖及貼youtube
## 目錄
[[__TOC__]]
[TOC]


## 寫作順序:
- 建立標題
- 建立參考資料
- 安排次標題
- 
## 建立目錄
*  📌手動建立目錄及連結
 
``` markdown
# Table of Contents
    1. [Example](#example)
    2. [Example2](#example2)
    3. [Third Example](#third-example)
    4. [Fourth Example](#fourth-examplehttpwwwfourthexamplecom)
---
## Example
## Example2
## Third Example
## [Fourth Example](http://www.fourthexample.com) 
```


* 📌自動建立目錄

**😒好像有問題跑不出來......**
```
[[_TOC_]]
or  
[TOC]  
```

## 貼上圖片

![貼上圖片](/images/000.png "這是範例圖片")

**注意前面要加一個 !,否則會出不來**
``` markdown
![貼上圖片](/images/000.png "這是範例圖片")
```

## 貼上影片

[![Watch the video](https://raw.githubusercontent.com/YuehMintTai/githubActionTry01/edit/main/assets/000.png)](https://raw.githubusercontent.com/YuehMintTai/githubActionTry01/edit/main/assets/000.mp4)

<video width="320" height="240" controls>
  <source src="/images/000.mp4" type="video/mp4">
</video>

<video width='320' controls>
<soruce src="https://www.youtube.com/shorts/9JsL7wexSgI" type='video/mp4'>
</video>

```
<video width='320' controls>
<soruce src="https://www.youtube.com/shorts/9JsL7wexSgI" type='video/mp4'>
</video>
```


# 參考資料
* [[ Markdown 教學 ] Markdown 是什麼 _｜ 如何用它來寫文件 _ _ 學習軟體工程師的數位筆記方案](https://youtu.be/osPzqfqwmLA)
* [Dellinger.io](https://dillinger.io/)
* [MarkdownLivePreview](https://markdownlivepreview.com/)
* [自動轉換markdown為pdf](https://apitemplate.io/pdf-tools/convert-markdown-to-pdf/)


[版權聲明](https://www.apache.org/licenses/GPL-compatibility.html)
2025/05/05 Sam Tai
