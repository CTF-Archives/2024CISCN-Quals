# CISCN 2024 初赛

## Misc

### Day1 Power Trajectory Diagram

题目内容：已知某安全设备模块的系统登录过程会产生功耗信息泄漏，采集的功耗轨迹信息已被保存在npz文件中，请根据npz文件中提供的信息破解出登录密码，并提交到相关平台。

注：如破解出的密码是12345678，则提交的flag格式为flag{12345678}。

### Day1 神秘文件

题目内容：我们从云盘中发现了一份可疑的PPT,里面隐含着重要的信息!请帮我们把它提取出来吧!

重要提示1：与flag相关的信息均为一段人类可读的字符串，解密之后将会获得拼接顺序,拼接完毕后为flag{XXX}的形式，大括号内应为标准小写UUID，请验证后提交。

重要提示2：解密的算法、密钥均隐含在PPT中，本题目不涉及猜解与爆破。

重要提示3：解密的算法、密钥均为明文信息，本题目不涉及脑洞联想。

重要提示4：题目中给出的信息足以解密各密文，本题目不涉及密码算法缺陷攻击。

免责声明1：MD5 (attachment.pptm) = d40f90f56c1277a3b8ae60260823cb59

免责声明2：MD5不一致的文件请勿打开，需要联系主办方确认附件是否正确。MD5一致的文件不存在任何恶意代码、木马、后门，请放心打开。

### Day1 Tough_DNS

题目内容：DNS的世界充满了多变的字符，接下来我将直接给你答案：56 16 26 93 66 53 16 56 d2 03 26 93 56

### Day1 火锅链观光打卡

题目内容：快来探索链上火锅游戏的奇妙之旅吧！参与问答挑战，赢取火锅食材图片。（当您集齐7种不同的食材图片时，即可兑换成独一无二的专属NFT！）加入我们，共同体验火锅链带来的乐趣与惊喜吧！

[hotpot.gamectf.com](http://hotpot.gamectf.com:2024)

### Day2 p&p

题目内容：WebAssembly 天下第一！WASM上面会有什么安全问题？

### Day2 通风机

题目内容：通风机坏掉了

### Day2 盗版软件

题目内容：在网上下了一个盗版软件就中毒了，他从内存中提取了文件和浏览器，请帮助分析;（flag为flag{md5(网站域名+c2地址)}，例如flag{md5(baidu.com114.114.114.114)}为flag{ac0997de69c84760c943f59d9c7fc3cf}）

## Crypto

### Day1 what mouth

题目内容：Here is running a key exchange system, but there are someone who has an access to the whole process.

### Day1 hash

题目内容：你能仅仅通过一个Python2.7自带的hash函数的输出，计算出它的原象的sha384哈希值吗？

### Day1 用户信息访问控制

题目内容：完整题目背景及描述请见附件。（请点击“下发赛题”，本题容器下发后的端口是ssh端口，ssh的账号为player，密码为player，ssh登录上去可自行修改密码。登录后请根据题目要求解题）

### Day2 OvO

题目内容：I can only give you my partial e.

### Day2 ezrsa

题目内容：这又是考了一万遍的RSA部分私钥泄露攻击，但这次可不太一样哦。

### Day2 古典密码

题目内容：

AnU7NnR4NassOGp3BDJgAGonMaJayTwrBqZ3ODMoMWxgMnFdNqtdMTM9

### Day2 平台可信认证

题目内容：完整题目背景及描述请见附件。（请点击“下发赛题”，本题容器下发后的端口是ssh端口，ssh的账号为player，密码为player，ssh登录上去可自行修改密码。登录后请根据题目要求解题）

## Reverse

### Day1 asm_re

题目内容：How is your assembly foundation

### Day1 androidso_re

题目内容：Here are only the corresponding So files for the ARM architecture

### Day1 rust_baby

题目内容：Do you know reverse rust

### Day2 gdb_debug

题目内容：动静结合

### Day2 whereThel1b

题目内容：I love Python3

### Day2 GoReverse

题目内容：GoReverse!

## Pwn

### Day1 gostack

题目内容：go stack overflow~

### Day1 orange_cat_diary

题目内容：经典堆

### Day1 ezbuf

题目内容：一个ez的协议

### Day2 magic_vm

题目内容：流水的VM，铁打的Pwn神

### Day2 SuperHeap

### Day2 EzHeap

## Web

### Day1 sanic

题目内容：sanic能有什么问题呢？

### Day1 Simple_php

题目内容：小明在学习CTF的过程中遇到了一道PHP的题目，以他有限的水平做不出来，可以帮帮他吗？

### Day1 easycms

题目内容：

简单的cms，可以扫扫看？

提示1： /flag.php：

```php
if($_SERVER["REMOTE_ADDR"] != "127.0.0.1"){
   echo "Just input 'cmd' From 127.0.0.1";
   return;
}else{
   system($_GET['cmd']);
}
```

提示2：github找一下源码?

### Day2 mossfern

题目内容：小明最近搭建了一个学习 Python 的网站，他上线了一个 Demo。据说提供了很火很安全的在线执行功能，你能帮他测测看吗？

### Day2 ezjava

题目内容：小安的数据源测试站已经开发了一部分，你能帮他找到问题吗？

### Day2 easycms_revenge

题目内容：又是个简单的cms，研发修复了函数存在的漏洞。
