<!--
 * @Author: charlottexiao123
 * @Date: 2021-03-07 12:18:51
 * @Description: The Author is a clever man.
-->
# DailyHealth
南信大健康日报Web自动化填写脚本
## 功能:
- 填报的微信推送
- 自动化填报南信大的健康日报
## 运行准备:
- Chrome浏览器
- python3
- selenium包(通过pip install selenuim安装)
- ChromeDriver.exe(需要查看自己的浏览器版本再下载)链接为:http://npm.taobao.org/mirrors/chromedriver/
## 运行:
- 申请Server酱Key,将ServerKey和账号密码填到DailyHealth.py对应位置(Server酱微信推送也可以不使用,可以自行考虑)
- 将下载的ChromeDriver.exe放到DailyHealth.py同目录下,然后运行即可
## 更多
- 可以在windows server或者linux服务器上设置定时启动任务,每日定时填报,不用手动运行;
- 除了web填报的方式,也有用request请求实现的方式
