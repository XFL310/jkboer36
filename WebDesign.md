#### 功能设计

整个外卖订单管理系统的对象分为管理员、骑手、用户三个部分：

##### 管理员

管理员具有修改食品信息的功能，包括增删改查等：

<img src="C:\Users\XFL\AppData\Roaming\Typora\typora-user-images\image-20220502163007205.png" alt="image-20220502163007205" style="zoom:50%;" />

增加信息：添加一种新的食品到系统，包括食品名，价格等信息。

删除商品：从系统中删除商品。

修改信息：管理员可以修改系统中食品的若干属性。

查看食品信息：管理员可以向用户一样浏览查看系统中所有食品的信息。

<img src="C:\Users\XFL\AppData\Roaming\Typora\typora-user-images\image-20220502170627515.png" alt="image-20220502170627515" style="zoom:50%;" />





##### 骑手

骑手的功能包括接单和送单；

<img src="C:\Users\XFL\AppData\Roaming\Typora\typora-user-images\image-20220502163551608.png" alt="image-20220502163551608" style="zoom:50%;" />



##### 用户

用户是整个系统的主要服务对象，包括下单，查看订单状态，退单，支付等功能：

下单功能：用户浏览并且选择一种食品下单，下单后进行支付，在等待订单送达的时间内，用户可以查看订单状态。

退单：在一定时间内，用户因为某种原因可以选择退单。

<img src="C:\Users\XFL\AppData\Roaming\Typora\typora-user-images\image-20220502172858748.png" alt="image-20220502172858748" style="zoom:50%;" />

##### 登录功能

登录功能是所有的用户共同具有的权限，用户、管理员、骑手等使用账号密码的方式登录系统，密码正确则进入系统主页面，否则会提示登录失败。在个人中心页面，可以修改密码，从而重新登录。

<img src="C:\Users\XFL\AppData\Roaming\Typora\typora-user-images\image-20220502175604124.png" alt="image-20220502175604124" style="zoom:50%;" />



#### 系统结构

##### 系统功能结构



###### <img src="C:\Users\XFL\AppData\Roaming\Typora\typora-user-images\image-20220502190129396.png" alt="image-20220502190129396" style="zoom:67%;" />

##### 组织结构

外卖订单系统为层级机构，由登录界面进入系统主页面。然后再主页面，不同角色可以通过头部菜单选择不同的功能，然后进入相应的界面。

#### 页面设计

##### 主页面

![image-20220502191834919](C:\Users\XFL\AppData\Roaming\Typora\typora-user-images\image-20220502191834919.png)

##### 登录页面

<img src="C:\Users\XFL\AppData\Roaming\Typora\typora-user-images\image-20220502192154013.png" alt="image-20220502192154013" style="zoom:67%;" />