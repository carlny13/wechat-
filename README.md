# wechat-
从sogou微信上搜索与终端相关的文章主题，并爬取url、文章主题、公众号名、发布日期。

#从document.write(cutLength("中国移动终端服务基地", 16)）字符中提取关键中文文字，可以使用：.find的方式查找出来，或者正则。
代码示例如下：
title = title.script.get_text()
title = title[title.find('("') + 1: title.find('", ')]
