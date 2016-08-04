# mmx_nginx
nginx一些常用的配置

##判断客户端是否是移动客户端

###配置
```shell
 include user_agent_mobile.conf;
```

###使用

```shell
  if ( $user_agent_mobile = 1) {
    #TODO:do something
  }
```
