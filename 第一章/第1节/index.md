## 0.1 课程内容
[00:00:01.866]那这节课
[00:00:02.533]我们继续给大家去讲一下
[00:00:04.133]Python当中的输出函数prunt
[00:00:07.066]实际上啊 
[00:00:07.933]对于Prun的这个函数
[00:00:09.366]大家已经不再陌生了
[00:00:12.000]在之前我们已经使
[00:00:13.766]用咱们的集成开发环境
[00:00:16.000]还有我们的交互式命令行
[00:00:18.133]以及python4代的IDL1都进行过一个输出
[00:00:22.300]那现在
## 0.2 认识函数
[00:00:22.900]咱们就来正式的去认识一下这个函数
[00:00:26.000]在PASS当中有个
[00:00:27.866]函数你可以直接去使用它
[00:00:30.100]那这个函数就叫做Prund
[00:00:32.766]它可以将
[00:00:34.166]咱们想展示的任何东西
[00:00:37.266]在IDL1或者标准的控制台上进行一个
[00:00:40.766]显示你比如说在这的时候
[00:00:43.566]你直接写一个print 520
[00:00:45.966]那实际上是做了一件什么事呢
[00:00:48.400]我们现在来看一下
## 0.3 函数的使用
[00:00:51.733]shift F5 首先呢你当你写上print 520
[00:00:56.600]实际上是计算机发出
[00:00:59.533]一个打印520这样的一个指令
[00:01:03.266]但是呢计算机不认识怎么办呢
[00:01:05.933]所以那这个时候就会到第二步
[00:01:08.300]那把你写的这句代码的话
[00:01:11.300]编译成计算机能够听得懂的机器语言
[00:01:14.766]这个工作是由谁来做的
## 0.4 python解释器
[00:01:16.966]是由咱们那个python解释器
[00:01:19.133]还记不记得
[00:01:19.966]老师让大家去安装我们的python解释器
[00:01:23.600]那python解释器呢
[00:01:25.100]将这句代码翻译成计算机
[00:01:27.300]可以听得懂的语言
[00:01:28.733]计算机一瞅哎你想输出啊
[00:01:31.766]所以呢他就进行一个
[00:01:33.733]在控制台上进行一个输出了
[00:01:37.533]那他是这样的一个直径过程
[00:01:39.966]那然后呢我们现在再来看
[00:01:45.566]我们在进行输出的时候
[00:01:47.733]有的老师打了引号
[00:01:50.866]而像520就没有进行打引号
[00:01:53.800]那是什么关系呢
[00:01:55.366]什么原因呢
## 0.5 输出和输入
[00:01:56.533]我们现在来看一下啊Pro的函
[00:01:59.466]数输出的内容可以是数字
[00:02:01.966]你比如说520就是数字
[00:02:04.366]那加上单引号的hello
[00:02:06.066]word就是咱们的一个字母串
[00:02:08.533]那同时呢咱们的这个普润的函数呢
[00:02:11.366]还可以进行输出
[00:02:13.366]含有预算符的一个表达式
[00:02:17.166]那它不仅可以在咱们的这个
[00:02:19.666]控制台上进行输出
[00:02:21.466]还可以干什么呢
[00:02:22.800]还可以啊去输出到咱们的文件当中
[00:02:27.133]那
[00:02:27.533]而且还有换行以及不换行这样的形式
[00:02:31.133]那现在我们来一个一个的看
[00:02:35.733]首先我在这呢去建一个拍词文件
[00:02:39.366]那这个拍词文件我起名叫做DEMO1
[00:02:42.866]然后在这个过程当中
[00:02:44.566]第一个那这个井号叫什么
[00:02:47.166]井号叫做注
[00:02:48.733]释
[00:02:50.066]那我现在呢在这写上告诉你呢
[00:02:52.133]可以输出什么
[00:02:53.166]可以输出咱们的一个数字
[00:02:56.666]你比如说在这print什么
[00:02:58.966]520是数字吧
[00:03:01.500]print九十八点五
[00:03:04.866]那98.5也是数字啊对吧
[00:03:08.300]所以你看一下
[00:03:09.466]都可以进行一个原样的输出
[00:03:13.166]那第二个
[00:03:14.100]它还可以输出咱们的这个字符串
[00:03:18.200]你比如说我在这的时候pre rent hello word
[00:03:23.600]那这就是输出一个字符串
[00:03:28.666]然后输出
[00:03:29.566]那有没有同学问这样的一个问题
## 0.6 举例
[00:03:32.066]我不加引号行不行呢
[00:03:35.700]对不对
[00:03:36.133]那我们现在来看一下我在这写的什么
[00:03:39.066]hello word没有加引号
[00:03:42.133]他在这就直接报错了
[00:03:44.966]为什么呀
[00:03:45.966]因为我们的字符串是
[00:03:49.166]变化多样的
[00:03:51.733]所以计算机根本就不认识他
[00:03:55.366]那怎么办呀
[00:03:56.333]你加上单引号双引号或者是3引号
[00:04:00.400]他的目的就是告诉计算机
[[00:04:03.100]这个东西不需要你理解
[00:04:06.766]你只需要照着输出就可以了
[00:04:11.600]所以你看我在这的
[00:04:13.566]时候再去给它加上一个双引号
[00:04:16.500]刚才不是单引号吗
[00:04:17.933]现在加上一个双引号
[00:04:20.100]你看它是不是就给你原样输出了
[00:04:23.500]那计算机也明白了
[00:04:24.933]只要看到带单双3引号的
[00:04:28.066]他就不用去理解了
[00:04:29.466]直接输出
[00:04:31.366]那还可以输出什么呢
[00:04:32.800]刚才不是说了吗
[00:04:34.066]还可以输出我们的表达式
[00:04:39.200]含有运算符的表达是什么
[00:04:44.600]叫含有运算符的表达式
[00:04:46.800]你比如说我在这写3+1
[00:04:49.333]那这个3叫什么
[00:04:50.966]三合一叫操作数
[00:04:56.166]加号叫做运算符
[00:04:59.700]那么含有
[00:05:01.733]操作数和预算符的称为表达式
[00:05:05.466]那我们看一下它会输出什么
[00:05:07.800]它会输出3+1还是输出
[00:05:11.100]4呢
[00:05:12.700]结果给咱们输出的什么是
[00:05:15.700]说明我们的Pro的函数当中
## 0.7 表达式
[00:05:18.966]如果是一个表达式的话
[00:05:21.333]它会进行进行运算
[00:05:23.466]然后输出表达式的一个结果
[00:05:30.800]然后现在咱们再看
[00:05:32.200]那这些我们的520呀98.5 hello word呀以及4啊
[00:05:36.966]都是输出在什么地方
[00:05:38.666]都是输出在咱们的这个控制台上
[00:05:43.066]那除了可以输出在这个控制台上
[00:05:46.200]还可以输出到我们的文件当中
[00:05:50.700]那如果要输出在文件当中
[00:05:53.200]我们可以这样去写代码
[00:05:56.533]好了
[00:05:57.000]那我在这写的时候可以将我们的数据
[00:06:01.266]输出到咱们的这个文件当中
[00:06:05.666]如果要输出到文件当中
[00:06:08.166]你应该这样去写
[00:06:10.600]open要打开输出到哪个文件当中呢
[00:06:14.900]我写上d盘p e x t表
[00:06:18.866]那这个是我要把数据所输出到的文件
[00:06:23.766]然后采用的是a加
[00:06:27.733]那a是什么
[00:06:29.866]以读写的方式打开文件
[00:06:33.100]如果文件不存在的话就创建文件存
[00:06:35.933]在的话就在原有内容上进行追加
[00:06:39.533]那现在我的地盘有这样的一个文件吗
[00:06:42.666]先去看一下在我的地盘
[00:06:45.733]有没有一个叫做tight的点TST文件
[00:06:49.566]还真没有
[00:06:50.733]所以这个情况如果我们运行的话
[00:06:53.566]程序会新建这样的一个文件
[00:06:57.166]那然后把它复给一个变量
[00:07:00.266]这个变量叫什么东西
[00:07:02.366]你可能现在还不是很懂
[00:07:04.300]你照着老师的代码敲就可以了
[00:07:08.133]呃后面呢
[00:07:08.933]咱们慢慢的都会去给大家进行讲解
## 0.8 详细说明
[00:07:12.266]你要输出什么内容
[00:07:13.666]我输出hello word
[00:07:16.000]把它输出到什么地方去
[00:07:17.866]输出到我的这个
[00:07:20.000]哎你写一个叫什么呢
[00:07:21.733]FP就输出到这个地方
[00:07:25.566]而这个是不代表的地盘下面的太子
[00:07:27.900]点TST文件啊
[00:07:29.200]最后再写个FP点什么
[00:07:32.300]close关闭的意思
[00:07:35.000]那好了咱们现在去运行一下
[00:07:37.200]前提是大家要有地盘
[00:07:40.733]没有地盘程序汇报错了
[00:07:42.800]你可以写一个其他的位置
[00:07:46.600]那当我们写完之后
[00:07:47.966]咱们看一下咱们的地盘
[00:07:49.466]是不是就多了一个叫做t x
[00:07:51.533]点t x t啊
[00:07:52.733]你把它打开
[00:07:54.566]用记事本打开
[00:07:56.000]然后你发现哎
[00:07:57.500]这块怎么没有内容呢
[00:08:01.666]是不是那我们现在呢
[00:08:03.366]去给大家去解决一下这个问题
[00:08:06.400]因为我们发现咱们执行完毕之后
[00:08:09.266]这一块他没有内容
[00:08:11.300]那我们去来进行一个解决
[00:08:14.766]那咱们的解决方案就是
[00:08:16.566]在这的时候你进行打印输出的时候
[00:08:19.000]它有一个叫
[00:08:21.366]fail
[00:08:23.500]它有这样的一个叫做fail
[00:08:26.133]好了那现在呢我们来继续运行
[00:08:31.300]进行之后
[00:08:32.133]那我们现在再去看一下咱们的地盘
[00:08:36.766]那这回呢
[00:08:38.500]就有这个文件了你把它打开
[00:08:41.100]打开之后你看里面是不是就是hello
[00:08:44.466]word呀所以呢
[00:08:46.200]在这的时候
[00:08:47.266]要想把我们内容输出到文件当中
[00:08:50.933]有两个需要注意的地方
[00:08:53.266]那在这我给你写一下
[00:08:55.566]那么注意点
[00:08:58.166]第一
[00:08:59.966]所指定的盘
[00:09:02.266]符
[00:09:04.700]就是你要给它存到哪个盘当中
[00:09:07.400]要存在第二
[00:09:09.966]就是你要使用什么
[00:09:12.366]使用fail
[00:09:15.466]等于
[00:09:17.200]什么的形式
[00:09:19.000]那我呢在这打开的文件对象叫FP
[00:09:23.500]那你在这就写FP
[00:09:25.133]如果你在这写a
[00:09:27.066]那么你这FL就等于谁a
[00:09:29.566]否则你的数据是写不了的进不去的
[00:09:34.800]这个是需要注意的地方
[00:09:38.166]那除了这个之外还有吗
[00:09:39.900]还有啊那你看一下
[00:09:41.600]咱们这些输出是不是都是换行输出呀
[00:09:45.400]如果我不想换行输出怎么办呢
[00:09:50.400]如果大家不想换行输出
[00:09:52.866]我们可以执行下面这个操作
[00:09:57.333]不进行换行输出
[00:10:00.200]说白了你的输出内容是什么
[00:10:03.500]你的这个叫输出内容是在一行当中
[00:10:08.966]你可以这样去写
[00:10:11.533]叫pre rent
[00:10:13.566]hello逗号word
[00:10:16.733]逗号Python
[00:10:19.966]我写了hello
[00:10:21.366]逗号word逗号Python对吧
[00:10:23.700]我们在运行的时候
[00:10:25.166]你就会看到
[00:10:26.100]他们三个是不是在一行当中
[00:10:28.866]进行了一个输出呀
[00:10:31.900]那我们同时再去看一下
[00:10:34.000]咱们的这个地盘会有几个hello word呢
[00:10:39.366]看是不是两个
[00:10:41.066]为什么因为老师说了在这的时候
[00:10:44.766]在这的a加的意思是什么意思啊
[00:10:47.600]如果文件不存在叫创建
[00:10:52.733]存在就在
[00:10:56.300]后面就文件内容的后面
[00:10:58.700]就在这个文件内容的后面
[00:11:04.000]继选追
[00:11:07.000]加是这样的一个方式
[00:11:10.166]那这个是什么
[00:11:11.333]是a加的含义
[00:11:14.600]那到现在为止呢
[00:11:15.866]咱们的Pro
[00:11:16.666]的函数给大家讲到了这样的内容
[00:11:19.400]第一个内容就是
[00:11:20.966]Pro的函数可以输出数字
[00:11:23.866]普润的函数可以输出字符串
[00:11:26.666]而且普润的函数还可以输出表达式
[00:11:29.666]但是他会计算表达式的结果
[00:11:32.500]他的输出的目的地
[00:11:34.166]前边这些都是输出到咱们的显示器上
[00:11:38.333]而我们下面这种
[00:11:40.066]open的方式是输出到文件当中
[00:11:44.333]还有什么
[00:11:45.200]还有就是如果你直接这样去写的话
[00:11:49.966]直接写prunt
[00:11:51.366]它会在我们的换行输出
[00:11:54.366]但如果你使用逗号进行分隔的话
[00:11:58.000]那他会在一行进行输出
[00:12:02.300]那关于pre的函数的内容
[00:12:04.366]我们就给大家讲到这

```question     
 { 
"category": "radio", 
"title": "以下不是Python3的六个标准数据类型的是?",
 "options": [ 
{ "key": "A", "value": "Number" }, { "key": "B", "value": "List" }, { "key": "C", "value": "try" }  ], "selected": "C" } 
```{{active 00:02:12.001}}  
```experiment 
{ "title": "请打开Shell工具输入ls操作", 
"tool": "shell" }
 ```{{active 00:04:10.001}}
 ```valiate
 { "title": "请打开资源管理器index.js文件，点击运行",
 "tool": "run" }
 ```{{active 00:05:40.001}}
```question
{
  "category": "checkbox",
  "title": "以下是Python3的六个标准数据类型的是?",
  "options": [
    {
      "key": "A",
      "value": "Number"
    },
    {
      "key": "B",
      "value": "List"
    },
    {
      "key": "C",
      "value": "try"
    }
  ],
  "selected": "A,B"
}
```{{active 00:08:06.001}}  