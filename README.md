
环境：python 2.7 64bit，win10 64bit，SqlServer 2008

微信公众号文章爬取器

从搜狗微信公众号入口爬取公众号新闻列表

支持爬取新闻标题、Icon、作者、时间等

支持文章内容图片下载替换

支持去掉含有二维码的图片

支持去掉带有超链接的html 标签

支持保存数据到数据库sql server

二维码识别采用zbar，支持用python zbar插件和用zbar的windows exe两种方式解析二维码

微信文章过于频繁，搜狗和微信会提示 输入验证码，自动识别和输入验证码采用 若快打码（收费）

关于scrapy同时运行多个任务的问题，请参照这篇博文http://blog.csdn.net/humanbeng/article/details/77368834