# check_alive

用于检测机器人进行存活

参考配置文件config.json中的配置内容：

```json
{
    "ask": "还活着",
    "ans": "死了"
}
```

第一个字符串`ask`表示检测的询问语句，第二个字符串`ans`表示存活的回复语句

当在**群聊**中出现`ask`语句时，机器人将会回复`ans`语句来表示自己当前处于在线状态