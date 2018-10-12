## 一、TCP三次握手
### 1、三次握手过程
![image](https://github.com/ym652324/network/blob/master/image/QQ%E5%9B%BE%E7%89%8720181012165306.png)
#### （1）客户端发送SYN包（syn=i），进入SYN_SENT状态（SYN：同步序列编号）
#### （2）服务器端接收到SYN包，发送确认ack包（ack=i+1），以及SYN包（SYN=j），进入SNY_RECV状态
#### （3）客户端接收SNY包和ack包，并且返回确认ack包（ack=j+1），客户端和服务器端连接成功。
### 2、两次握手不行吗？
#### 
## 二、TCP四次挥手
