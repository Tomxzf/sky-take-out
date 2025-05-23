# 校园外卖

## 技术栈

SpringBoot+Mysql+Vue3+WebSocket+Redis+ElementUI

## 环境搭建

- **前端**
  - Web文件夹下运行nginx.exe文件
- 小程序
  - 微信开发者工具打开 WeiXinApp 文件夹
- 后端
  - 更改sky-server里面的application-dev.yml文件内容
- 数据库
  - 运行sky_take_out.sql

## 项目截图

- ![image-20240426195901149](./image/image-20240426195901149.png)

- ![image-20240426195929170](./image/image-20240426195929170.png)
- ![image-20240426195959737](./image/image-20240426195959737.png)
- ![image-20240426200014740](./image/image-20240426200014740.png)
- ![image-20240426200102763](./image/image-20240426200102763.png)

## 项目相关知识点

### 数据流向






### 工具类

#### git

git.init -> git add -> git commit -> git push

### nginx

![img.png](img.png)

nginx的优点

1.提高访问速度
2.负载均衡（将大量的请求均衡的平分给服务器群中的服务器）


### md5加密

密码在数据库中明文存储有风险，对密码进行加密

### JWT 令牌


### Thread
用户端发起的每一次请求，都是一个线程

