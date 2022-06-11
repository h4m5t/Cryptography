# Cryptography

### 原文链接

https://zhuanlan.zhihu.com/p/455104888

### 如何入门密码学

1.首先学习密码学数学基础。**密码学的本质是数学**。

必须要学的内容有：

+ 整除和带余除法
+ 同余的概念和性质
+ 同余类和剩余系
+ 欧几里得算法
+ 扩展欧几里得算法
+ 模运算
+ 素数的性质和判定
+ 费马定理
+ 欧拉定理
+ 中国剩余定理
+ 原根

若时间充足，还建议学的内容有：

+ 贝祖定理
+ 算数基本定理
+ 拉格朗日插值定理
+ Wolstenholme定理
+ 二次剩余
+ 欧拉判别式
+ 高斯引理
+ 二次互反律
+ 原根
+ 位运算和进位制

另外，密码学中最重要的内容还有代数部分。初学者需掌握：

+ 群、环、域的概念和性质
+ 有限域的概念和性质
+ 有限域上的多项式计算
+ 有限域上的一次，二次方程求解。

2.学习密码学基本概念

+ 明文、密文、加密密钥、解密密钥、加密算法、解密算法、密钥生成算法
+ 现代密码学基本原则
+ 香农密码理论
+ 基本密码攻击方法
+ 基本密码分析方法
+ 古典密码：凯撒密码、HILL密码、维吉尼亚密码等

3.学习对称密码

+ 一次一密（One Time Pad加密）
+ 代替、置换
+ Feistal框架
+ SP网络
+ DES
+ AES
+ RC4
+ 流密码（LFSR等）
+ 分组密码的工作模式（ECB、CBC、CFB、OFB、CTR）

4.公钥密码体制

+ 单向陷门函数的概念
+ 数学困难问题（大整数分解、离散对数问题等）
+ RSA
+ Rabin
+ ElGamal
+ ECC
+ Diffie-Hellman

5.哈希函数

+ 哈希函数的定义
+ 哈希函数的单向性、抗弱碰撞性、抗强碰撞性
+ MD5
+ SHA1
+ HMAC
+ 消息认证码

6.数字签名

+ 数字签名的概念和原理
+ RSA数字签名
+ ElGamal数字签名
+ Schnorr数字签名
+ DSA数字签名体制

7.其他部分

+ 密码学相关协议（kerberos PKI SSL IPsec等）
+ 密码学的应用
+ 密钥分配和密钥管理
+ 数字证书（X.509）

### 密码学入门书籍推荐

中文书籍推荐

+ 现代密码学 杨波 清华大学出版社
+ 图解密码技术 第三版
+ 密码编码学与网络安全——原理与实践
+ 网络安全--技术与实践 清华大学出版社

英文书籍推荐

+ A Graduate Course in Applied Cryptography
+ An Introduction to Mathematical Cryptography
+ Crypto101
+ Introduction to Modern Cryptography
+ The Joy of Cryptography
+ Understanding Cryptography by Christof Paar
