1.使用2018-12-26  pip install的zinnia无法直接运行bootstrap,发现django版本为2.1，zinnia 0.20
具体报错信息为：
OSErrorat /weblog/tags/
[Errno 22] Invalid argument: 'C:\\python3\\Anaconda3\\lib\\site-packages\\django\\contrib\\admin\\templates\\zinnia:zinnia\\tag_list.html'
报错语句：
{% extends "zinnia:zinnia/tag_list.html" %}

修改报错语句：
edit 'zinnia:zinnia' to 'zinnia' may soluve it,but every html file must do this.

有没有更好的解决办法？


