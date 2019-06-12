### Date对象用法 ###
获取当前时间对象 var date = new Date();
获取年 date.getFullYear();
获取月 date.getMonth();
获取日 date.getDate();
获取星期 date.getDay();
获取时 date.getHours();
获取分 date.getMinutes();
获取秒 date.getSeconds();
获取毫秒 date.getMilliseconds();

例：var day = date.getDate();
    console.log(day);

### Math对象用法 ###

向上取整 Math.ceil();
向下取整 Math.floor();
最大值 Math.max();
最小值 Math.min();
伪随机 Math.random();
幂运算 Math.pow(x,y); x的y次方
四舍五入(不严格) Math.round();
      console.log(Math.ceil(5.3)) 向上取整得到6
      Console.log(Math.floor(5.9)) 向下取整得到5
      Console.log(Math.max(2,3,4,5)) 最大值5
      Console.log(Math.min(1,5,8,9)) 最小值1