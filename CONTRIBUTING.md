##  HOW  TO  CONTRIBUTING

## 贡献指南
请您勇敢地去翻译和改进翻译。虽然我们追求卓越，但我们并不要求您做到十全十美，因此请不要担心因为翻译上犯错——在大部分情况下，我们的服务器已经记录所有的翻译，因此您不必担心会因为您的失误遭到无法挽回的破坏。（改编自维基百科）

可能有用的链接：

[英文官网用户手册](https://docs.mongodb.com/manual/)<br/>
[文档翻译认领列表](https://github.com/JinMuInfo/MongoDB-Manual-zh/blob/master/Document-translation-claim-list.md)<br/>
[文档翻译贡献者名单](https://github.com/JinMuInfo/MongoDB-Manual-zh/blob/master/List-of-contributors.md)<br/>
[在线阅读文档 github](https://jinmuinfo.github.io/MongoDB-Manual-zh/)<br/>



### 欢迎任何人参与和完善
你可以做的事  
翻译文档  
校对文档  
润色文档  
格式调整  
链接引用调整  
项目管理等  
包括但不限于以上种种  


### 一 翻译
请将你的文档转为 markdown  格式。  
注意以下事项  

  * 格式

    ​	标题：一级目录

    # 例子：  一级目录

    **必须遵循目录格式书写，否则编译时会产生异常**

    **数字书写**：加粗。 

    例子： **2**

    

    **本页面目录：**

    跳转到本页面去

    

    **页面的“注意” “警告”之类的**：

    格式：

    >注意：
    >
    >............

    

    **方法书写**：\``

    例子：`db.collection.aggregate()`

    

    ​	代码块注解：powershell。  

    例子:

    ```powershell
powershell
    ```
    
  * 超链接的引用

    链接到文件项目本身。

    

  * 图片

    图片链接到文件项目本身

    例子:

    ```powershell
    src="../../img/docs/06-Aggregation/agg-pipeline.mp4"  比如这个路径 最好也是填上绝对路径
    ```

    

  * 已被废弃的版本

书写格式：

```
本项目以最新版本的文档为主，当旧版本的一些内容在新版本被删除时，汉化的新文档不删除该内容只是标记该文档的过期版本。
比如 **MMAPv1 Storage Engine** 已被放弃使用 ，但是我们在文档中仍然保留他的相关资料。
```

  * 新版本新增的功能

    以最新版本为主

# 格式规范

### 警报格式

**用法样式：**
**信息样式**

```kotlin
> **[info] info**
>
> Use this for infomation messages.
```

**警告造型**

```kotlin
> **[warning] warning**
>
> Use this for warning messages.
```

**危险造型**

```kotlin
> **[danger] danger**
>
> Use this for danger messages.
```

**成功造型**

```kotlin
> **[success] success**
>
> Use this for success messages.
```



## 图片问题

**在翻译的问题中涉及到的图片问题**，首先将图片下载下来，然后将图片保存到文档中的`img`文件的`docs`的文件中，`docs`文件夹中有和mongo文档对应的文件夹，请将图片放在对应的文件夹中，然后将图片文件链接更新在文档中。

例子：图片路径格式

```powershell
img/docs/06-Aggregation/distinct.bakedsvg.svg
```



本项目以版本新增及弃用的文档为主，当旧版本的一些内容在新版本被删除时，汉化的新文档不删除该内容只是标记该文档的过期版本。
比如 **MMAPv1 Storage Engine** 已被放弃使用 ，但是我们在文档中仍然保留他的相关资料。



### 二、校对
完善方向
可以完善的方向包括但不限于：

中英文符号（Chinese prior）；
笔误及错误语法；
术语使用；
语言润色；
文档格式；
如果觉得现有翻译的某些部分不好，重新翻译也是可以的。
关于数学公式
尽管用MathJax等工具插入数学公式是一个好的 manner，但是我们目前并不把它列为 high-priority 的提升方向。我们未来会做的！但是针对于这个问题如果你有好的想法并乐意PR，未来我们会针对于这个新特性做一些改进。

如果你发现公式过期或者错误，请务必按照这种格式进行更新："! + [latex 公式] + (图片地址) "，这样可以保证我们的开发比较高效。此外，不要忘记将新的图片放到 img 文件夹中一并 PR。如果你找不到好的latex公式图片下载地址，可以使用这个工具。

管理者校对
管理员应当是组织内活跃的参与者，因此可能会从事很多校对工作。我们建议管理员自己不要 merge 自己对于文档修改或者增加新特性的PR，这样其他管理员可以 review 并 double check，提升文档质量。

### 三、提交
提交的时候不要改动文件名称，即使它跟章节标题不一样也不要改，因为文件名和原文的链接是对应的！！！

fork Github 项目并建立你的分支 branch（我们强烈建议这样做）；  
将译文放在 docs/  文件夹下；  
commit 和 push 你的修改；  
pull request。
如果你还不熟练这个流程，请参阅 [Github 入门指南](https://docs.github.com/cn/github)。  
建议**你在提交的时候 同时修改贡献者名单** 。  
我们非常重视每一个贡献者的付出。  
文末格式  
期待在文末看到你的名字  
```
译者：你的名字
校对：你的名字
本文链接：https://docs.jinmu.info/MongoDB-Manual-zh
原文链接: https://docs.jinmu.info/MongoDB-Manual-zh
最后更新时间：2020-01-01
```

### 四、工具推荐

[**Typora 文本编辑工具**](https://typora.io/)

###  五、 文件名称
文件名称推荐英文命名,空格可以使用中横线`-`  或者 下横线表示`_` 因为生成的 html会被互相引用,空格等会影响字符识别。

###  其他
待补充


