# MarkDown语法

## 标题

    # 一级标题
    ## 二级标题
    ### 三级标题
以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

## 列表
### 无序列表
在文字开头添加(*, +, and -)实现无序列表。但是要注意在(*, +, and -)和文字之间需要添加空格。（建议：一个文档中只是用一种无序列表的表示方式）

    * 项目1
    * 项目1
    * 项目1

    + 项目2
    + 项目2
    + 项目2

    - 项目3
    - 项目3
    - 项目3

* 项目1
* 项目1
* 项目1

+ 项目2
+ 项目2
+ 项目2

- 项目3
- 项目3
- 项目3

### 有序列表
使用数字后面跟上句号.（还要有空格）,数字不一定要按照顺序

    1. 项目1
    1. 项目1
    5. 项目1


1. 项目1
1. 项目1
5. 项目1


## 引用

只需要在文本前加入 > 这种尖括号（大于号）即可

`>引用的内容`

>引用的内容

## 图片与链接


### 链接
Markdown中有两种方式，实现链接，分别为内联方式和引用方式。

#### 内联方式
内联方式：`This is an [example link](http://example.com/).`
This is an [example link](http://example.com/).
#### 引用方式
    I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][c].  
    
    [1]: http://google.com/        "Google" 
    [2]: http://search.yahoo.com/  "Yahoo Search" 
    [c]: http://search.msn.com/    "MSN Search"
I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][3].  

[1]: http://google.com/        "Google" 
[2]: http://search.yahoo.com/  "Yahoo Search" 
[3]: http://search.msn.com/    "MSN Search"

### 图片 
插入链接与插入图片的语法很像，区别在一个 !号

#### 内联方式
内联方式：`![alt text](1.png "Title")`
内联方式：![alt text](1.png "Title")
#### 引用方式
    ![alt text][id] 
    
    [id]: 1.png "Title"

![alt text][id] 

[id]: 1.png "Title"
## 粗体与斜体

### 粗体
用两个 `*` 或 `_` 包含一段文本就是粗体的语法

    **这里是粗体**
    __这里是粗体__

**这里是粗体**
__这里是粗体__

### 斜体

用一个 `*` 或 `_` 包含一段文本就是斜体的语法

    *这里是斜体*
    _这里是斜体_

*这里是斜体*
_这里是斜体_

## 表格
    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## 代码框
### 行内或单行代码
用两个 ` 把中间的代码包裹起来

    `echo 'hello world!';`

`echo 'hello world!';`

### 代码块
在代码块前添加TAB则是连在一起的代码块

    function index(){
        echo "hello world!";
    }

## 分割线

分割线的语法只需要三个 `*` 或 `_` 号，例如：

`***`

***

`---`

---