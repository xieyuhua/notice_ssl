# 介绍
用于监控https证书有效期信息，即将过期了通过 企业微信或钉钉机器人 发送消息提醒，采用系统定时任务计划每天执行一次检测

```

## 配置

安装后需要修改配置文件，请在hscm.yml（没有此文件就新建）中填写webhook地址和需要监控的域名

填写示例：

编辑hscm.yml文件，写入以下内容(需要将webhook和hosts换成实际的)，

```yml
webhook: https://oapi.dingtalk.com/robot/send?access_token=b7xxxf
hosts:
  - web.example.com
  - api.example.com:4433




wget -c https://github.com/go-acme/lego/releases/download/v4.14.2/lego_v4.14.2_linux_amd64.tar.gz
tar -zxvf lego_v4.14.2_linux_amd64.tar.gz
rm lego_v4.14.2_linux_amd64.tar.gz
chmod +x lego

#!/bin/bash
PATH=/bin:/sbin:/usr/bin:/usr/sbin:/usr/local/bin:/usr/local/sbin:~/bin
export PATH
cd  /www/server/panel/vhost/cert/ssl/ &&
ALICLOUD_ACCESS_KEY=LTAIkD3A3iPMyxH \
ALICLOUD_SECRET_KEY=LM7UjnEQEmz \
./lego --email="1510120461@qq.com" \
--dns="alidns" \
--domains="*.zadsadfef.com" \
renew --days=30 \
--renew-hook="sudo  /etc/init.d/nginx restart"
echo "----------------------------------------------------------------------------"
endDate=`date +"%Y-%m-%d %H:%M:%S"`
echo "★[$endDate] Successful"
echo "----------------------------------------------------------------------------"


ALICLOUD_ACCESS_KEY=57575757  ALICLOUD_SECRET_KEY=47575
./lego --email="1510120461@qq.com" --dns="alidns" --domains="*.az4757bk.com" --path=/www/wwwroot/www.578575.com/ssl  run

```

