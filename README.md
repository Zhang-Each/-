更新：修改了一下代码，现在的爬虫代码获得的结果里options不包含题干了，其实就改动了一下下标

另外爬虫直接获得的json文件里，所有东西都写在一行里面，比较乱，可以用vscode之类的一键格式化排版成人类可以阅读的json文件

-------------------------------------------------------------

本项目包含浙江大学计算机学院的课程

- 软件工程(CS/信安 大三下)
- 软件工程基础(SE 大二下)

的客观题题库(考试的客观题据说都是这里面来的)



通过python 网络爬虫获取了全部题目和答案，并保存在了json文件中

另外写了个简单的刷题小程序，支持

- 按章节刷题
- 随机生成若干个题目刷题

其中json文件中稍微有一点小问题就是选项里把题目也写进去了，不过无伤大雅，依然可以正常使用

时间有限，就不改了

本来使用pyinstaller打包生成了一个可执行文件，不过由于pyinstaller只能生成本机操作系统支持的类型，所以只能生成exe文件，如果你发现了这个项目，可以clone原码来运行刷题程序，也可以用pyinstaller在自己电脑上打包，生成可执行文件



不过客观题库需要放在生成的可执行文件同个目录下，不然要出事

