#http协议介绍：
http协议是Hyper Text Transfer Protocol（超文本传输协议）的缩写，主要是进行服务器和浏览器之间进行传送的协议。

http的工作原理主要是客户端（http）通过url像web服务器端发送请求，然后服务器根据请求返回需要的内容，服务器端和客服端他们之间的请求主要是协商着来进行转换的。url客户端会通过网关也就是ip地址进行域名解析然后进行对服务器端的访问。

http中的URL一般格式是：http://xxx.com   URL的网址长度是由一定限制的，根据限制的URL网址服务器端才会查找相应的内容，如果URL长度过长，服务器端无法处理的时候就会返回414状态码。

http的消息主要是从客户端到服务器的请求消息和服务器到客户端的响应时间两部分。URL向web进行访问的时候用的方法一般为get方法和head方法来进行的。

连接：在没有持久连接之前，为获取每一个url指定资源都必须建立一个独立的tcp连接，这样的话就加重了服务器的负担，很容易引起互联网的阻塞。通过较少的tcp连接的话可以减少时间更好的进行控制内存。

http/1.1和http版本最明显的区别也就是连接，http/1.1的持久连接可以通过客户端或者服务器端来进行终止，而通过connection头域可以产生终止连接信号，一旦终止客户端则不可在向服务器端发送任何连接请求。
（问题：这样的话是否有缓存存在呢？）

访问主要通过：get、head、put、delete

get方法的访问目的是减少不必要的网络使用，允许客户端从服务器获取具体的数据。

head方法和head方法一致，除了服务器不能够响应消息外，head方法的访问是有缓存的。

put方法主要是请求服务器把请求的url发送过来。

delet方法主要就是从服务器上进行删除url指定的资源。

状态码.....

http中的缓存主要是方法、头、响应状态码
