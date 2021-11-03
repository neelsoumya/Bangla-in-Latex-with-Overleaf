### Introduction

Latex for Bengali and Latex overleaf for Bengali

https://tex.stackexchange.com/questions/99606/how-to-write-bengali-in-latex


All credit goes to the users in the stackexchange link above and user Rajan-sust



### Changing Compiler from Overleaf

* Sometimes for certain languages, classes and packages it may be necessary to use a different compiler like xelatex than the default pdflatex. We have to set XeLatex instead of PdfLatex for using fontspec package.</br>

	* To change the compiler, simply click into the left hand menu </br>
	![First Image](/images/first.png)

	* Click on the Compiler menu under Settings </br>
	![Second Image](/images/second.png)


### Download Any Bengali Font and Upload in Overleaf

Download from [Free Bangla Fonts Download](https://www.omicronlab.com/bangla-fonts.html)
</br>
I'm using Kalpurush font. Without downloading you can take kalpurush.ttf file from this repository. Finally, you have to upload it in overleaf.

### Add the following code snippet

```tex
\usepackage{fontspec}
\setmainfont{Times New Roman}
\newfontface{\bn}{kalpurush.ttf}
```
	
### Bangla Writing



```tex
\bn{অনেক আশা করে লিভারপুল ছেড়ে বার্সেলোনায় যোগ দিয়েছিলেন ব্রাজিল তারকা ফিলিপ কুতিনহো।}
```
