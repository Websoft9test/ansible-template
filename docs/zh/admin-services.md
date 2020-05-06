# 服务启停

使用由Websoft9提供的 RabbitMQ 部署方案，可能需要用到的服务如下：

## RabbitMQ

```shell
sudo systemctl start rabbitmq-server
sudo systemctl stop rabbitmq-server
sudo systemctl restart rabbitmq-server
sudo systemctl status rabbitmq-server

# you can use this debug mode if RabbitMQ service can't run
rabbitmq-server console
```