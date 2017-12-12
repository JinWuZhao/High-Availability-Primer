# 什么是可用性

## 定义
可用性(Availability)就是一个系统处在可工作状态的时间的比例。

## 公式
```
MTBF: Mean time between Failures. 平均故障间隔
MTTR: Mean time to recover. 平均修复时间
Availability = MTBF / (MTBF + MDT)
```

## Service Level Agreement服务水平协议(SLA)
服务提供商与受服务用户之间具体达成了承诺的服务指标——质量、可用性，责任。

## SLA举例
[亚马逊EC2](https://aws.amazon.com/cn/ec2/sla/)  
[阿里云ECS](https://help.aliyun.com/knowledge_detail/40683.html)  
[Azure虚拟机](https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/v1_6/)  

# 影响可用性的因素

## 故障
