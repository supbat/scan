2020-10-13
# scan
# 自己公司互联网服务开放监控，目前500+IP全天重点端口监控，如有新增服务则自动微信推送告警
scanIP.txt为扫描IP范围，每行一个（可自行调整为范围，然后调整NMAP扫描参数）
whitelist.txt为白名单，建议直接扫描一个输出文件然后内容复制至此
output/日期.txt 扫描端口输出文件
notice.txt 对比扫描结果和白名单生成文件，后续告警通知调用此文件
output/logs.log 通知执行情况日志，新增服务，无新增服务均记录

注意：微信告警通知为 server酱，需要自行获取key然后替换scan.sh内的key值，如通知多人添加""""即可;server酱使用指南百度即可；
如适用邮件通知自行百度添加邮箱告警模块即可。

非运维非开发，菜鸟一枚，大佬勿喷！

