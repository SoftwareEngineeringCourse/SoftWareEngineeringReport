### 1.类图

![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/1.png)

ATM能从银行数据库获取客户的各种信息，满足客户的各种操作，并提交给银行进行修改

### 2.对象图

![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/2.jpg)

用户对ATM发送存款取款或者开账户的请求，ATM将用户的信息和请求发送给银行数据库，同时定时和银行库进行现金流通

### 3.用例图

![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/3.jpg)

新用户需要开户成为老用户，老用户就能够进行取款，存款转账等操作。

### 4.状态图

![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/4.png)

展示了客户在ATM存取款自动机进行操作时，ATM机系统的状态转移情况

### 5.序列图

![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/5.png)

展示了客户在ATM机发出服务请求到服务完成的过程，其中强调了服务请求的生命线和控制焦点

### 6.协作图

![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/6.png)

同样展示了客户在ATM机发出服务请求到服务完成的过程，但强调了接收和发送消息的对象的结构组织

### 7.活动图

![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/7.jpg)

ATM机读取银行卡，审核输入密码，判断正误，密码错误则判断密码错误次数，超过上限结束，没有超过上限返回审核输入密码；密码正确则读取取款金额，并行执行出款和打印取款凭证，最后结束。

### 8.构件图
![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/8.jpg)

ATM机有读取银行卡操作，用户信息库会匹配用户信息和密码操作，ATM机读取取款单然后进行结算，钱币库存出款并打印凭证。

### 9.部署图
![](https://github.com/SoftwareEngineeringCourse/SoftWareEngineeringReport/blob/main/Week4/9.jpg)

应用服务器向上连接到用户信息数据库服务器，向下连接到客户使用的客户操作界面，银行财务职员的财务管理界面以及技术人员的技术维护界面。
