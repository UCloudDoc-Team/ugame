云游戏WEB演示程序快速上手指南
	为了您更好的使用云游戏服务，缩短开发周期，我们也准备了一个Docker镜象来供您对云游戏进行试用和联调测试，同时在您完成了云游戏服务创建后，我们也提供了几款游戏供您进行客户端同步开发和内部测试。需要特别说明的是，您不得将这些测试进行商业运营，除非您正式的获得了这些游戏的版权。使用之前：您已经通过控制台完成了云游戏产品的权限申请，同时在控制台上已经看到了相应的游戏。

### 创建Servless服务
1. 获取帐号和游戏对应的accessKey/accessKeyId/tenantKey/TenantSecret/gameId/bundleId等信息。
2. 申请相应的cube，填入以下信息
	    在镜象里选择 Cube-lab cloudgame-dem
	    高级设置里传入相应的环境变量
	ARM_ACCESS_KEY_ID
	ARM_ACCESS_KEY
	X86_TENANT_SECRET
	X86_TENANT_KEY变量的值
	
	根据自己的需要来勾选外网弹性IP，如果勾选，带宽可以选择最小的1M

3. 由于镜象使用的外网端口为8080，如果需要使用EIP直接 访问镜像，请修改自己的EIP对应的外网防火墙，放通8080端口

4. 静等几秒之后，容器实例的状态变成了running状态，然后就可以通过EIP来使用云游戏演示程序了。

### 通过WEB访问DEMO页面
ARM云游戏使用方式为： http://yourip:port/arm?game=com.xxx.xxx
X86云游戏使用方式为: http://yourip:port/x86?gameId=12345678 
如果你的设置全部正确，您就可以在浏览器上进行云游戏的使用了。
   
