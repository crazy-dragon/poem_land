因为经常看一些理论知识，没有去实际编码，无法建立对某个技术的直观感受，因此决定去建立一个小的项目，
在这里实践自己学习到的一些技术的用法。目的是为了建立对某项新接触技术的直观感受！

# 注意
这个项目的爬虫代码，是项目启动后直接执行一次，类似于初始化工作。它会在项目启动后爬取100首词然后
写入数据库中。所以，如果重复启动的话，需要truncate table poem，不然会导致数据重复。