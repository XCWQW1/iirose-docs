# 注意事项

> 接口中的所有消息都是客户端向蔷薇服务器发送的

> 请将所有消息转换为 String(字符串) 发送到蔷薇ws服务器中 (也就是pyton中的`Str(内容)`或`json.dumps(内容)`

`()` 中扩住的内容代表当前位置的参数是什么，如果第一个括号后带有 `*` 说明该参数不保证准确