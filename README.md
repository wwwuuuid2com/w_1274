# w_1274
【yshop前后端分离商城系统 v3.2】拼团砍价秒杀+新增商品积分兑换模块+新增商城装修模块
<br/></br>
[下载地址](https://www.uuid2.com/1274.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>yshop基于当前流行技术组合的前后端分离商城系统： <p>
<p>SpringBoot2+MybatisPlus+SpringSecurity+jwt+redis+Vue的前后端分离的商城系统， <p>
<p>包含商城、拼团、砍价、商户管理、 秒杀、优惠券、积分、分销、会员、充值、多门店等功能，更适合企业或个人二次开发。<p>
<p>功能：<p>
<p>一、商品模块：商品添加、规格设置，商品上下架等<p>
<p>二、订单模块：下单、购物车、支付，发货、收货、评价、退款等<p>
<p>三、营销模块：积分、优惠券、分销、砍价、拼团、秒杀、多门店等<p>
<p>四、微信模块：自定义菜单、自动回复、微信授权、图文管理、模板消息推送<p>
<p>五、配置模块：各种配置<p>
<p>六、用户模块：登陆、注册、会员卡、充值等<p>
<p>七、其他等<p>
<p>项目结构：<p>
<p>项目采用分模块开发方式<p>
<p>yshop-weixin 微信相关模块<p>
<p>yshop-common 公共模块<p>
<p>yshop-admin 后台模块<p>
<p>yshop-logging 日志模块<p>
<p>yshop-tools 第三方工具模块<p>
<p>yshop-generator 代码生成模块<p>
<p>yshop-shop 商城模块<p>
<p>yshop-mproot mybatisPlus<p>
<p>docker部署：<p>
<p>1、创建一个存储第三方软件服务Docker Compose文件目录：<p>
<p>mkdir -p /yshop/soft<p>
<p>2、然后在该目录下新建一个docker-compose.yml文件：<p>
<p>vim /yshop/soft/docker-compose.yml<p>
<p>3、接着创建上面docker-compose.yml里定义的挂载目录：<p>
<p>mkdir -p /yshop/mysql/data /yshop/redis/data /yshop/redis/conf<p>
<p>4、创建Redis配置文件redis.conf：<p>
<p>touch /yshop/redis/conf/redis.conf<p>
<p>5、docker 部署参考根目录docker文件夹<p>
<p>6、以上创建好之后参考docker下文件，先执行软件安装：<p>
<p>cd /yshop/soft<p>
<p>docker-compose up -d 启动<p>
<p>docker ps -a 查看镜像<p>
<p>7、运行docker/applicatiion目录下 docker-compose,当然之前一定要打包jar包，构建镜像 切换到Dockerfile 文件下：<p>
<p>docker build -t yshop-admin .<p>
<p>    <p>
<p>源码更新日志：<p>
<p>3.2版本已经正式发布啦！<p>
<p>1、新增商城装修模块<p>
<p>2、新增商户订单通知<p>
<p>3、提现接入企业付款接口<p>
<p>4、新增app端后台版本控制<p>
<p>5、新增商家端退款申请通知<p>
<p>6、新增商品积分兑换模块（同步主商品sku）<p>
<p>7、升级wxjava版本4.0.0<p>
<p>8、升级springboot最新版本2.4.2<p>
<p>9、新增docker一键部署方案<p>
<p>10、后台商城首页优化<p>
<p>11、新增快递鸟查询顺丰轨迹<p>
<p>12、关键bug修复：<p>
<p>移除roketmq依赖及相关逻辑<p>
<p>修改退款扣库存<p>
<p>去除素材分组分页，防止素材过多显示不完全<p>
<p>修改订单金额为0时，支付不成功直接报错<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202107/7a6aa2e214.jpg" alt="【yshop前后端分离商城系统 v3.2】拼团砍价秒杀+新增商品积分兑换模块+新增商城装修模块"><img src="https://www.uuid2.com/wp-content/uploads/img/202107/a35e286859.jpg" alt="【yshop前后端分离商城系统 v3.2】拼团砍价秒杀+新增商品积分兑换模块+新增商城装修模块">
