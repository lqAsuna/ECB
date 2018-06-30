# Homework 9
## 使用ECB实现 make reservation用例的详细设计（包含用例简介，顺序图，类图）

### 用例简介
该用例完成用户订购酒店的整体过程。  
用户可搜索酒店，得到搜索表单。再根据搜索表单选择满意的酒店和房间类型。  
最后验证预定，完成整个过程。

**用例图：**

![image](https://github.com/lqAsuna/ECB/blob/master/image/result1.png)

**根据用例图，可以得到的BCE类**

- Boudary/UI类：FindHotelPage,OrderPage,RoomPage
- Control类：Control
- Entity类：Reservation，Hotel,Room

### 顺序图

![image](https://github.com/lqAsuna/ECB/blob/master/image/result2.png)

### 类图

![image](https://github.com/lqAsuna/ECB/blob/master/image/result3.png)

### 逻辑设计类图到实际项目框架的映射

![image](https://github.com/lqAsuna/ECB/blob/master/image/result4.png)
