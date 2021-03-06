# museum

 |发布日期 | 2019-12-10 | 
-|-|
项目名称| 博物馆-动静皆宜 | 
项目现状| 进行中| 
项目所有者| 廖俊杰| 
项目设计师| 廖俊杰| 
项目开发者|廖俊杰| 
项目测试者| 廖俊杰| 

### 多版本价值主张写作
***
#### 1句话版本

- 基于用户的最基本需求，该产品能够满足“多动者”宣泄“动”的需求、“不动者”寻求“静”的需求，即给他们提供“趣拍博物馆”的手势拍照服务，同时提供与历史人物进行人脸融合的服务。

#### 1分钟版本

- 博物馆内的参观者众多，难免会有“好动者”（注意力不集中，好动）和“好静者”（只想坐着静静）走进博物馆参观展品。在参观过程中，“好动者”需要一些能够吸引他们的事物，“好静者”则需要一些能够放松自身、休息的事物。比方说，参观者A是个好动者，想要宣泄内心的“动”的心情。参观者B是个好静者，想要有安静又富含趣味的博物馆参观体验。参观者C是好动者的家人/伙伴，想让好动者能够集中注意力。针对以上问题，我们将采用“百度AI——手势识别API”、“百度AI——人脸融合API”来对博物馆进行加值。我们将提供一款“博物馆趣拍”小程序。通过这个小程序，“好动者”摆出不同的手势，可以拍出带有博物馆特色的趣味照片，满足其宣泄“动”的需求。同时，“好静者”在休息的时候也能通过趣味拍照来提升静的趣味性，满足其寻求“静”的需求。

## Part A. 价值主张设计

### （一）背景
***
- 博物馆内参观者难免有些人好动，有些人好静。但博物馆内，似乎只有展品能够吸引好动者，休息区吸引好静者。如果有一个能够满足这两类参观者寻求“动”与“静”需求的博物馆产品（APP/小程序），这也许能让参观者对博物馆的体验有所提升。


### （二）加值宣言
*** 

- 如今，人们的文化需求日益增长。越来越多的人喜欢到博物馆参观，以作消遣、也能拓宽视野。但博物馆内的参观者众多，难免会有“好动者”（注意力不集中，好动）和“好静者”（只想坐着静静）走进博物馆参观展品。在参观过程中，“好动者”需要一些能够吸引他们的事物，“好静者”则需要一些能够放松自身、休息的事物。基于现状，我们将采用“百度AI——手势识别API”、“百度AI——人脸融合API”来对博物馆进行加值。

- 主要：运用了“人脸与人体识别技术”中的“手势识别”技术——识别图片中的手部位置和手势类型，可识别24种常见手势，包括拳头、OK、比心、作揖、作别、祈祷、我爱你、点赞、Diss、Rock、竖中指、数字等。即输入——用户拍照时，含手势的图片，输出——含手势类型相对应特效的趣味照片。

- 次要：运用了“人脸与人体识别技术”中的“人脸融合”技术——对两张人脸进行融合处理，生成的人脸同时具备两张人脸的外貌特征。即输入两张图片（用户自拍图片、博物馆展品相关历史人物图片），输出同时具备拍照用户、历史人物外貌特征的图片。


### （三）核心价值宣言
***
- 基于用户的最基本需求，该产品能够满足“多动者”宣泄“动”的需求、“不动者”寻求“静”的需求，即给他们提供“趣拍博物馆”的手势拍照服务，同时提供与历史人物进行人脸融合的服务。


### （四）目标用户
***
- 博物馆参观者（好动者）
- 博物馆参观者（好静者）


### （五）用户痛点宣言
***
- 场景1：参观者A是个好动者，想要宣泄内心的“动”的心情。
- 场景2：参观者B是个好静者，想要有安静又富含趣味的博物馆参观体验。
- 场景3：参观者C是好动者的家人/伙伴，想让好动者家人/伙伴能够集中注意力。

### （六）用户需求列表
***
用户案例 | 对应标题 |  重要程度
-|-|-
参观者想宣泄内心的“动”需求——通过手势拍照，宣泄内心的“动”| 手势识别 | 重要 |
参观者想寻求有趣的“静”需求——通过手势拍照，寻求有趣的“静”| 手势识别| 重要|
参观者想与博物馆展品产生一定的联系——与历史人物进行人脸融合| 人脸融合 | 次重要 |

#### 具体应用场景
- 周末，好动的小学生鑫鑫和他的爸爸去参观博物馆。鑫鑫在博物馆内四处跑动，用手触摸展品箱。爸爸感到十分苦恼，于是点开了博物馆小程序——“趣拍博物馆”，给鑫鑫示范了一遍趣味拍照。看完之后，鑫鑫就沉浸在富含博物馆特色的特效拍照中，摆出了多种不同的手势，得到了不同的含有博物馆特色的趣味照片。即解决了他好动的问题，又能丰富博物馆体验。

- 周末，好静的大学生啊昊独自取参观博物馆，走着走着就累了，想找个安静的地方休息。但在休息区的他发现无事可做，于是他打开了博物馆小程序——“趣拍博物馆”，通过摆出各种不同的手势，拍出了带有博物馆特色的趣味照片，啊昊感觉十分有趣。

- 周末，大学生啊鑫前往博物馆参观。看见一件展品，内心十分感慨，心里想：“如果在过去的那个时候，我大概会是什么样子呢？”。于是他打开了博物馆小程序——“趣拍博物馆”中的“回到过去”拍照功能，自拍了一张，并选择了相应的历史人物，最后，他得到了历史人物融合照片，似乎回到了过去。

### （七）AI概率性考量
***
#### 百度AI-手势识别——产品优势
- 丰富的手势：可识别24种常见手势，可根据业务需求灵活应用，适用于娱乐互动、手势操控各类场景。
- 领先的算法：手势识别算法业界领先，识别准确率90%以上，近景自拍、远景他拍都能精准识别。
- 稳定的保障：可提供企业级稳定、精确的大流量服务，拥有毫秒级识别响应能力及99.9%的可靠性保障
#### 可能发生的问题（环境因素）
- 拍照手机摄像头出现异常、故障；
- 拍照场景过于亮/过于暗，导致拍照画面不清晰；
#### 总结
- 识别准确率高达90%以上，毫秒级的识别响应能力，普遍情况下都可以使用。
- 该产品可能会受环境因素的影响，但发生的概率较小为少数事件，因此对正面影响并不大。

## Part B. 原型

### （八）产品结构图
***
- 若图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum__prototype)中查看。

![产品结构图.png](https://upload-images.jianshu.io/upload_images/9455181-375d598ac83356b6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### （九）产品原型
***
- 若图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum__prototype)中查看。



#### 口头操作说明-微信授权模块

![博物馆-微信授权.png](https://upload-images.jianshu.io/upload_images/9455181-8ad14dcbbc7fe1eb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

***
#### 口头操作说明-手势特效拍摄模块

![手势特效01.png](https://upload-images.jianshu.io/upload_images/9455181-96d55e3e6572e95c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![手势特效02.png](https://upload-images.jianshu.io/upload_images/9455181-14beb268d837c343.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![手势特效03.png](https://upload-images.jianshu.io/upload_images/9455181-ee0f588d7d2dee42.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![手势特效04.png](https://upload-images.jianshu.io/upload_images/9455181-454a4829614b16ad.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

***
#### 口头操作说明-回到过去（人脸融合）模块

![回到过去01.png](https://upload-images.jianshu.io/upload_images/9455181-35611e04f5f031d2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![回到过去02.png](https://upload-images.jianshu.io/upload_images/9455181-7f5ae9d757360a6a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![回到过去03.png](https://upload-images.jianshu.io/upload_images/9455181-f61f083ebed0d38b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![回到过去04.png](https://upload-images.jianshu.io/upload_images/9455181-1a28165fbb8ffa4d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![回到过去05.png](https://upload-images.jianshu.io/upload_images/9455181-f4d767329b343e93.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

***
#### 口头操作说明-我的相册模块

![我的相册01.png](https://upload-images.jianshu.io/upload_images/9455181-8cddce9299cba791.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![我的相册02.png](https://upload-images.jianshu.io/upload_images/9455181-8c4ec6822c3ed8f8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#### AI加值——交互及界面设计

- 在【手势特效拍摄】模块中；
- 【步骤3、4】【用户手势识别——屏幕显示特效】这一核心交互环节使用了人工智能——“手势识别”的加值；即：

![手势特效03.png](https://upload-images.jianshu.io/upload_images/9455181-ee0f588d7d2dee42.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 在【回到过去】模块中；
- 【步骤4】【人脸图片融合】这一核心交互环节使用了人工智能——“人脸融合”的加值；即：

![回到过去04.png](https://upload-images.jianshu.io/upload_images/9455181-1a28165fbb8ffa4d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#### AI加值——信息设计

- 在【手势特效拍摄】模块中；
- 【步骤3、4】【用户手势+屏幕显示的特效】这一核心信息使用了人工智能——“手势识别”的加值，如下所示：

![手势特效03.png](https://upload-images.jianshu.io/upload_images/9455181-ee0f588d7d2dee42.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 在【回到过去】模块中；
- 【步骤4】【融合人物图片+用户人脸图片】这一核心信息使用了人工智能——“人脸融合”的加值，如下所示：

![回到过去04.png](https://upload-images.jianshu.io/upload_images/9455181-1a28165fbb8ffa4d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 原型文档——展示、下载区

- [原型文档——展示](http://nfunm047.gitee.io/museum__prototype)

- [原型文档——下载地址](https://github.com/Liaojunjie2333/Prototype-document-Museum)


## Part C. API

### （十）API的使用水平
***
待完成...

### （十一）API的使用比较分析
***
待完成...

### （十二）API使用后风险报告
***
待完成...

