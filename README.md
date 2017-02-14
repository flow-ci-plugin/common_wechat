# wechat_message Step
Wechat message sender, should send message to users who bind the wechat user to flow.ci

### INPUTS

* `FLOW_WECHAT_MESSAGE_USER_IDS` - 微信用户ID.
* `FLOW_WECHAT_MESSAGE_DESCRIPTION` - 微信消息.


## EXAMPLE 

```yml
steps:
  - name: wechat_message
    enable: true
    failure: true
    plugin:
      name: wechat_message
      inputs:
        - FLOW_WECHAT_MESSAGE_USER_IDS=$FLOW_WECHAT_MESSAGE_USER_IDS
        - FLOW_WECHAT_MESSAGE_DESCRIPTION=$FLOW_WECHAT_MESSAGE_DESCRIPTION
```
