# Spring的RestTemplate传多个Cookie
> RestTemplate通过HttpEntity的HttpHeaders发Cookie时，既可以通过多次调用httpHeaders.add("Cookie", "名称=值")来发多个Cookie，也可以直接httpHeaders.add("Cookie", "名称1=值1; 名称2=值2")这种分号分隔的"名称=值"形式的字符串来发送多个Cookie。注意必须是"名称=值"形式的字符串。
## 客户端
![客户端](客户端.png "客户端")
## 服务端
![服务端](服务端.png "服务端")