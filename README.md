## GIT/svn  学习

### 1 .  安装 ，一直next

### 2. ssh 生成密钥

```
ssh-keygen -c rsa  然后一直回车，直到看到下图
```

![](C:\Users\10852\AppData\Roaming\Typora\typora-user-images\image-20200808182922849.png)

- 再github 网站点击个人中心, 点击 settings --> SSH and GPG keys

![image-20200808183050526](C:\Users\10852\AppData\Roaming\Typora\typora-user-images\image-20200808183050526.png)

![image-20200808183308136](C:\Users\10852\AppData\Roaming\Typora\typora-user-images\image-20200808183308136.png)

-  找到ssh 生成的密钥，然后把公钥的内容复制到新增密钥的区域

![image-20200808183437437](C:\Users\10852\AppData\Roaming\Typora\typora-user-images\image-20200808183437437.png)

![image-20200808183631566](C:\Users\10852\AppData\Roaming\Typora\typora-user-images\image-20200808183631566.png)



- 测试

  ```
  ssh -T git@github.com ,回车后，会在 .ssh 文件里生成 
  known_hosts 文件
  
  ```

  