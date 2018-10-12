## 一、TCP三次握手
### 1、三次握手过程
![image](https://github.com/ym652324/network/blob/master/image/QQ%E5%9B%BE%E7%89%8720181012165306.png)
<br/>
（1）客户端发送包，其中标志位SYN=1（生成序号seq=x），进入SYN_SENT状态  
（2）服务器端接收到包，识别到SYN=1，发送确认包，ACK=1（ack=x+1），SYN=1（seq=y）  
（3）客户端接收到确认包，发送确认包ACK=1，ack=y+1，seq=x+1  
### 2、标志位及序号
（1）SYN标志位：同步标志，表示建立连接连接。  
（2）ACK标志位：确认标志，确认序号有效  
（3）seq序号：用来标识从TCP源端向目的端发送的字节流  
（4）ack序号：只有ACK标志位为1时，确认序号字段才有效，ack=seq+1，确认seq序号的包成功接收  

### 3、两次握手不行吗？
#### 
## 二、TCP四次挥手
### 1、四次挥手过程
![image](https://github.com/ym652324/network/blob/master/image/20170606084851272.png)
（1）
