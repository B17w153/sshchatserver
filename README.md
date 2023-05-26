# BitwiseSSHChatSever
## 0x00 BitwiseSSHChatServer 是一个 AArch64 架构的基于 SSH 的聊天服务器

![QQ图片20230526004758](https://picdl.sunbangyan.cn/2023/05/26/smc3e.png)
## 0x01 服务器地址

```bash
frp-fan.top:32106
```

因为SSH服务几乎无论什么平台都有，所以你可以随时随地甚至可以在家里的路由器上用拖把当键盘加入聊天！
### 有意思的功能:
- 房间功能! 用 cd 来查看所有房间，用 cd #房间名 加入房间（如果没有会自己创建）
- 支持Markdown! 表，头，斜体 还有杂七杂八的东西. 用 \n 换行
- 代码分析高亮. 用Markdown fence发送代码. 发送 eg-code 以查看示例代码示例
- 私信! 用 =user <msg> 发送一条私信，或者用 cd @用户名 保持私聊.
- 时区支持, 用 tz Continent/City 来设置你的时区.
- 内置井字棋游戏和Hangman! 发送 tic 或者 hang <word>开始游戏.
- Emoji 支持! : rocket: => 🚀  (就像discord里一样)
-  <abbr title="Hyper Text Markup Language">安全 、 自由 、 私密</abbr> ：只要不在服务器里辱骂我，就可以<abbr title="World Wide Web Consortium">随便发表言论</abbr>.
- 
  

## 0x02 加入服务器教程
  [手机端](mobile.md)
  
  [电脑端](PC.md)
  
  
[蓝奏云整合(包含电脑端和手机端软件)](https://bitwise.lanzoum.com/b0425ngkb) 提取密码:5l0p
  
  
  
## 0x03 服务器由Bitwise-QQ2216450736, [Github@B17w153](https://GITHUB.COM/B17w153) 运行维护



<img src="https://picdl.sunbangyan.cn/2023/05/26/j3ojx.png" align=center />



 ## 0x04 进阶使用技巧
### 输入`help`查看公告，输入`cmds`查看常用指令。
### 发送图片：以Markdown形式发送

需要先将图片上传至图床

推荐 [SunPics](https://pics.sunbangyan.cn/) 可以直接以Markdown形式复制


`已知bug ： 可能自己有时候会看不到，只需要退出重进就行`


```bash
![图片描述](图片链接地址)
```

例如

```bash
![j3ojx](https://picdl.sunbangyan.cn/2023/05/26/rg09yz.png)
```


<details>
  <summary>会显示</summary>
  
<img src="https://github.com/B17w153/sshchatserver/assets/134407644/5c6a9f0e-b8ea-4800-8707-419a6df5cac8">
</details>
  

### 私聊
发送
```bash
=xiaoming 你好
```
会给` xiaoming` 发送一条 `你好`

### 内置小游戏
输入`tic`可以玩井字棋
'hang' 玩猜词Hangman，不懂是什么的自己去搜

### 测试打字速度
```bash
devmonk
```

 ## 0x05 MIT License

Copyright (c) 2022 Ishan Goel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
 
 
  
 
 
 
 
  
  
  
  
