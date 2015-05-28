# GetWeatherInfor
利用java抓取某个城市的天气信息（it's about getting weather information of  city by using java)
该程序从网站上获取实时的天气数据，并将获得的天气数据值写入到后台的数据库websql中。
该程序从数据库(websql)天气信息表(weatherinfor)中搜索到要查询天气的城市名字段，其格式为:城市名:该城市的拼音，例如：厦门:xiamen。
然后从http://flash.weather.com.cn/wmaps/xml/xiamen.xml"提取天气信息。
程序的配置文件为WeatherConf.txt
其内容介绍如下：
IP:127.0.0.1			    //写入数据库所在的IP地址
Port:3306         			//数据库的端口号
DatabaseName:websql     //数据库的名称
User:root        //数据库的用户名
Password:root     //数据库的密码
