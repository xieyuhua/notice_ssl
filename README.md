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

```

