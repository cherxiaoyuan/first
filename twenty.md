#http状态码
1. 301  Moved Permanently               永久重定向——下回不会再找他了
2. 302  Move temporarily                临时重定向——下回依然会请求服务器
3. 304  Not Modified                    未修改——用户可以通过缓存进行访问，实际已经不存在了
4. 404  Not Found                       请求错误——网页或者请求的资源不存在
5. 500  Internal Server Error           服务器内部错误——服务器解析错误
6. 204  No Content                      无内容——服务器处理了请求但是不会返回内容
7. 502  Bad Gateway                     错误网关——访问不到数据一般服务器关掉就会出现这种错误
8. 504  Gateway Time-out                网关超时——长时间访问未能及时获取
9. 503  Service Unavailable             服务不可用是的一种状态（关掉/维护）
10. 414 Request-URI Too Large           URL网址过长，服务器无法处理
11. 410 Gone                            客户端请求的资源已经不存在。以前有但是现在删除了。
12. 408 Request Time-out                服务器等待客户端发送的请求时间过长，超时
13. 406 Not Acceptable                  服务器无法根据客户端请求的内容特性完成请求  
14. 401 Unauthorized                    没有被授权登陆
15. 306 Unused                          已经被废弃的HTTP状态码
16. 305 Use Proxy                       请求的资源必须通过代理访问
17. 307 Temporary Redirect              临时重定向。使用GET请求重定向（和302一样）
18. 403 Forbidden                       服务器理解请求客户端的请求，但是拒绝执行此请求
19. 406 Not Acceptable                  服务器无法根据客户端请求的内容特性完成请求
20. 409 Conflict                        服务器处理请求时发生冲突 
