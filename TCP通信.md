# 一、TCP通信概述

## TCP通信的客户端代码实现：

###      用了客户端类Socket

![image-20220417215659899](E:\笔记\image-20220417215659899.png)

![](E:\笔记\image-20220418130202283.png)

## TCP通信的服务器端代码实现：

###          用了服务器类SeverSocket

![image-20220417223725079](E:\笔记\image-20220417223725079.png)![image-20220418130212964](E:\笔记\image-20220418130212964.png)

![image-20220418130234926](E:\笔记\image-20220418130234926.png)

结果：![image-20220418130301190](E:\笔记\image-20220418130301190.png)

![image-20220418130315153](E:\笔记\image-20220418130315153.png)



# 二、TCP通信文件上传案例

![image-20220418222522850](E:\笔记\image-20220418222522850.png)

## 客户端：

![image-20220419161215784](E:\笔记\image-20220419161215784.png)

![image-20220419161232726](E:\笔记\image-20220419161232726.png)

## 服务器端：

![image-20220419161821219](E:\笔记\image-20220419161821219.png)

![image-20220419215217583](E:\笔记\image-20220419215217583.png)

![image-20220419215229937](E:\笔记\image-20220419215229937.png)

# 三、文件上传案例阻塞问题

### 读文件会读-1，读数组不会读-1

问题：

![](E:\笔记\image-20220423171402712.png)

![image-20220423171334377](E:\笔记\image-20220423171334377.png)

# 四、文件上传案例优化

![image-20220423172024056](E:\笔记\image-20220423172024056.png)

![image-20220423172127955](E:\笔记\image-20220423172127955.png)

![image-20220423172343299](E:\笔记\image-20220423172343299.png)