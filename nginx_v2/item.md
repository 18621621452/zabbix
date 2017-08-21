Active connections          #活动连接数
Accepted connections\min    #每分钟建立的连接数
Handled connections\min     #每分钟握手的连接数
Requests\min                #每分钟请求数
Reading Connections         #读取客户端的连接数
Writing Connections         #响应数据到客户端的数量
Waiting Connections         #开启keep-alive的情况下,这个值等于active–(reading+writing),意思就是Nginx已经处理完正在等候下一次请求指令的驻留连接
Nginx Proc_Num              #Nginx活动进程数