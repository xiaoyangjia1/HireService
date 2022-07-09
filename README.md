### 软件发布说明
#### 1.0版本功能
- 客户、自由职业者登录注册功能
- 客户信息管理功能
- 自由职业者信息管理功能
- 客户发布查找合同功能
- 自由职业者发布接受合同功能
- 客户、自由职业者合同签订功能功能
- 管理员统计合同数额功能
- 管理员管理客户、自由职业者、合同、时间表信息功能

#### 运行环境
依赖环境 Redis nodejs java yarn 使用框架为ruoyi
#### 安装方法
- 导入到Eclipse，菜单 File -> Import，然后选择 Maven -> Existing Maven Projects，点击 Next> 按钮，选择工作目录，然后点击 Finish 按钮，即可成功导入。
- Eclipse会自动加载Maven依赖包，初次加载会比较慢（根据自身网络情况而定）
- 创建数据库ry并导入数据脚本ry_2021xxxx.sql，quartz.sql
- 打开项目运行com.ruoyi.RuoYiApplication.java，出现如下图表示启动成功。

	![image](https://img2022.cnblogs.com/blog/2771270/202207/2771270-20220709162226237-487865152.png)

- 打开浏览器，输入：(http://localhost:80 (opens new window)) （默认账户/密码 admin/admin123）
- 若能正确展示登录页面，并能成功登录，菜单及页面展示正常，则表明环境搭建成功