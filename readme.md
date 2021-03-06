## IDEA 激活说明
1. 首先去官网下载产品, 想用哪个下哪个, 可以下IDEA
2. 将破解文件放到一个不会改动的文件夹中。
破解文件的地址:  `https://github.com/AmandaYi/idea_Jet_Brains`
比如 `D:/develop/IdeaPoJie/JetbrainsCrack-3.1-release-enc.jar`
打开IDEA的安装目录的bin目录,找`idea.exe.vmoptions`
macOS版去`应用程序/Applications`找`idea.vmoptions`
windows x64平台下面会找到两个以 `.vmoptions`结尾的文件, `idea64.exe.vmoptions`
图示:
![举例idea.exe.vmoptions](./images/1.png)
3. 打开idea.exe.vmoptions, 以及idea64.exe.vmoptions(macOS不需要配置64位的)
在最后加上  -javaagent  以及破解文件的路径,注意window要把路径的斜杠换成左斜杠
`-javaagent:D:/develop/IdeaPoJie/JetbrainsCrack-3.1-release-enc.jar`
图示
![javaagent](./images/2.png)
4. 并且如果你的IDE仅对当前用户安装的话，需要在C:\Users\valenti\产品名\config中编辑.vmoptions文件！64位执行同样操作
5. 复制下面的内容到任意文本编辑器，将`licenseeName`字段的部分改成你自己想要的名字（任意）,PS：没什么意义，启动界面授权名字,比如我的启动界面
![启动界面](./images/3.png)
{"licenseId":"1337",
"licenseeName":"AmandaZhao",
"assigneeName":"",
"assigneeEmail":"",
"licenseRestriction":"Unlimited license till end of the century.",
"checkConcurrentUse":false,
"products":[
{"code":"II","paidUpTo":"2099-12-31"},
{"code":"DM","paidUpTo":"2099-12-31"},
{"code":"AC","paidUpTo":"2099-12-31"},
{"code":"RS0","paidUpTo":"2099-12-31"},
{"code":"WS","paidUpTo":"2099-12-31"},
{"code":"DPN","paidUpTo":"2099-12-31"},
{"code":"RC","paidUpTo":"2099-12-31"},
{"code":"PS","paidUpTo":"2099-12-31"},
{"code":"DC","paidUpTo":"2099-12-31"},
{"code":"RM","paidUpTo":"2099-12-31"},
{"code":"CL","paidUpTo":"2099-12-31"},
{"code":"PC","paidUpTo":"2099-12-31"},
{"code":"DB","paidUpTo":"2099-12-31"},
{"code":"GO","paidUpTo":"2099-12-31"},
{"code":"RD","paidUpTo":"2099-12-31"}
],
"hash":"2911276/0",
"gracePeriodDays":7,
"autoProlongated":false}
6. 启动IDEA，它会弹出授权的提示框，选择Activaction code，复制刚才第5条的一整代码，激活，done！！
![授权的提示框](./images/4.png)
7. 如果你是在试用期,软件不提示授权提示框,这时候需要打开任意项目, 然后点击菜单的Help,找到Register,就会显示第6步的授权提示框
![点击菜单的Help](./images/5.png)
