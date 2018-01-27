# MarkDown 语法（二）

## 链接 demo  

### 内嵌式链接  

- 外部链接：[百度](https://www.baidu.com)  
- 内部链接1：链接仓库的其他文件：[demo](demo.md)  
- 内部链接2：链接本文档的其他部分：[代码块 demo](demo2.md#代码块-demo)  

#### 引用式链接  

- 外部链接：[百度]
- 外部链接：[百度][baidu]
- 内部链接1：链接仓库的其他文件：[demo]
- 内部链接2：链接本文档的其他部分：[代码块 demo]

## 图片

-  引用外部图片
![google](https://www.google.com/logos/doodles/2018/wilder-penfields-127th-birthday-6477703409565696.6-law.gif "谷歌")

- 引用仓库内的图片
![引用仓库内的图片](img/me.jpg)


#### 图片的引用式链接  

-  引用外部图片
![google][google_logo]

- 引用仓库内的图片
![引用仓库内的图片][me]


## 引用

>这是一个引文  

                                      ———出自《哈哈》

多次引用
>>>哈哈


## 代码块
块式代码块

```
console.log('hello')
```

行内代码块
就连饭量森 `alert(1)`  

```javascript
<<<<<<< HEAD
<!-- 下面是文档中用到的链接 -->
[百度]: www.baidu.com
[baidu]: www.baidu.com
=======
<!--- 下面是文档中用到的链接 -->
[百度]: https://www.baidu.com
[baidu]: https://www.baidu.com
>>>>>>> 609ce283029a890cb087baf7ac57fcefbffbae34
[demo]: demo.md  
[代码块 demo]: demo2.md#代码块-demo

[google——logo]: https://www.google.com/logos/doodles/2018/wilder-penfields-127th-birthday-6477703409565696.6-law.gif

[me]: img/me.jpg
Creating a new branch is simple AND quick.
