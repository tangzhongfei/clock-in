# clock-in

我有个人员名单，每天我都会抓取他们是否打卡,抓出的表格类似附件nba.csv，对于没打卡的我需要邮件通知他们尽快打卡，如果7天内已经通知的，就不重复通知，超过7天的重复通知，这个要怎么用python自动实现自动处理并自动发邮件。

运行方式：python imail.py nba.csv

运行结果：
检测文件格式符合要求
检测到以下人员需要mail通知
Jordan
Kobe
...
James
已发送到
Jordan.test.com
Kobe.test.com
James.test.com
