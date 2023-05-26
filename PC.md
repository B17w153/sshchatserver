 # Windows端：
	
  ## 0x00. 使用原始cmd或者powershell 环境
	注意：这种方法连接服务器可能会显示不了Emojis。
Win + R打开 运行 输入cmd 或者powershell
 
 ![image](https://github.com/B17w153/sshchatserver/assets/134407644/0ac8fe1c-0d2d-4494-a263-bf9b06699e9a)

回车打开（这里使用cmd）

![image](https://github.com/B17w153/sshchatserver/assets/134407644/93a63c61-a3e5-46a4-9981-f6360c2ce5e5)

在终端窗口内输入 ssh ，查看自己有没有安装openssh（一般情况下默认是装的）
如下图说明已安装

![image](https://github.com/B17w153/sshchatserver/assets/134407644/f5922343-384a-479e-b57d-958572855691)


现在需要生成ssh密钥
输入 ssh-keygen，回车
 
![image](https://github.com/B17w153/sshchatserver/assets/134407644/eff71f5f-d4fb-4980-aafc-fb23855119df)


输入自己终端内显示的这一段内容（每个人都可能不一样），并且回车。

![image](https://github.com/B17w153/sshchatserver/assets/134407644/224562ad-6218-4a09-8980-a7c989a653ca)


接下来连按两个回车
看到这个画面就可以了
 

![image](https://github.com/B17w153/sshchatserver/assets/134407644/d2815a78-1184-4ab6-8dd3-4ef2d103f165)




现在输入ssh 你使用的用户名@frp-fan.top -p 32106
例如 ssh xiaoming@frp-fan.top -p 32106
就可以在聊天服务器里以xiaoming的身份登录


输入之后，会问你是否继续连接，输入yes回车即可
 

![image](https://github.com/B17w153/sshchatserver/assets/134407644/69dbd294-86a6-48ca-a6f2-0018f4cf40b0)
到这里就登录成功了

![image](https://github.com/B17w153/sshchatserver/assets/134407644/838f3a41-f2c0-4385-8d8c-134c19e43c6c)

## 0x01 第二种方法：使用termius，更快捷方便，可以显示emojis
下载termius
官网地址Termius - SSH platform for Mobile and Desktop
连接可能有点慢，可以挂梯子
 ![image](https://github.com/B17w153/sshchatserver/assets/134407644/2e57c2e4-01ef-465b-92b5-823faaf695af)

安装就行了
可以跳过注册登录，直接选择只在本设备使用就行
点击New Host

![image](https://github.com/B17w153/sshchatserver/assets/134407644/7b67f3de-6722-4c93-adf1-d1dbd37e266b)


填入服务器名称，地址，端口，和用户名，最后点击最下面的箭头指的Set a key
 ![image](https://github.com/B17w153/sshchatserver/assets/134407644/84ff5bf7-d2b9-408e-bd63-834585b72a5f)


点击New key

![image](https://github.com/B17w153/sshchatserver/assets/134407644/68999954-3861-44ff-9a40-342e3d221508)

点击import from my file
 

![image](https://github.com/B17w153/sshchatserver/assets/134407644/60298d35-deb3-4e97-8ce8-35ef0b8e42b0)


现在需要生成ssh密钥
打开cmd

![image](https://github.com/B17w153/sshchatserver/assets/134407644/dc0ab568-3aa4-4958-ad85-df46c050e909)

输入 ssh-keygen，回车
 

输入自己终端内显示的这一段内容（每个人都可能不一样），并且回车。
 
![image](https://github.com/B17w153/sshchatserver/assets/134407644/6c277331-c5e5-4c5a-b297-fc140928c64e)

接下来连按两个回车
看到这个画面就可以了
 
![image](https://github.com/B17w153/sshchatserver/assets/134407644/980fd7fb-6fcf-44ec-9e62-f54901b9da5d)


这时候需要去把上面的内容填进去（![image](https://github.com/B17w153/sshchatserver/assets/134407644/d784f517-e00e-4bfd-88fd-a353915f76fb)
 ）
如下选择id_rsa

![image](https://github.com/B17w153/sshchatserver/assets/134407644/3f1afb2a-2f52-4761-bd95-7e4671f87ab7)

点击save!

![image](https://github.com/B17w153/sshchatserver/assets/134407644/2eac5a04-70a1-4d6f-ba39-047516ccabe4)

 
然后选中刚刚的密钥
 ![image](https://github.com/B17w153/sshchatserver/assets/134407644/31e4bfed-df9c-4847-9485-f3dcefdf6855)

最后双击你创建的host就行
 

 ![image](https://github.com/B17w153/sshchatserver/assets/134407644/da45c690-cdb9-467c-89dd-609af48c0f7f)

![image](https://github.com/B17w153/sshchatserver/assets/134407644/3a67b0f6-8f90-4617-bbc5-726857b639f4)

