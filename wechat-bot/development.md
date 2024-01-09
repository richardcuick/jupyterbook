# 微信聊天机器人开发

![](wechat-logo.jpg)

发布说明：

- 版本0.1 - **完成**
    - 通过Wechaty创建聊天机器人
    - 获取消息发送给OpenAI并将内容作为微信消息返回
    - 控制台应用展示二维码
    - 部署到Azure云服务器
- 版本0.2 - 未开始
    - 使用TypeScript重写代码
    - 直接使用OpenAI类库
    - 使用GPT-4模型
- 版本0.3 - 未开始
    - 存储会话内容到数据库
- 版本0.4 - 未开始
    - 保持会话内容合理裁剪发送给API

错误调查，原因应该是网络连接问题出现重试时出错：

- 第一次运行：21:48 - 10:11
    - uncaughtException GError: connect ETIMEDOUT 116.128.169.42:443
    - uncaughtException GError: 状态同步超过197.872s未响应，5s后尝试重启
- 第二次运行：10:56 - 11:04
    - uncaughtException GError: not supported friend request message raw payload
    - uncaughtException GError [AxiosError]: timeout of 60000ms exceeded
    - uncaughtException GError: 状态同步超过201.874s未响应，5s后尝试重启
- 第三次运行：11:12 - (运行2.4小时后出错)
    - uncaughtException GError: 状态同步超过8637.27s未响应，5s后尝试重启
    - uncaughtException GError [AxiosError]: timeout of 60000ms exceeded