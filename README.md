# Countdown-effect
HTML+CSS+JavaScript实现时间显示、倒计时差、限时抢购三种效果
## Javascript日期操作

时间对象是一个我们经常要用到的对象，无论是做时间输出、时间判断等操作时都与这个对象离不开。   它是一个内置对象——而不是其它对象的属性,允许用户执行各种使用日期和时间的过程。

## Date()返回当前的日期和时间
- getDate() 查看Date对象并返回日期 （1-31）
- getDay() 返回星期几（0-6）
- getHours() 返回小时数 （0-23）
- getMinutes() 返回分钟数 （0-59）
- **getMonth() 返回月份值 (从0开始，＋1）**
- getSeconds() 返回秒数
- getTime()返回毫秒数
- **getYear() 返回年份  获得年最好用    getFullYear()方法来操作（完整格式 如2017**）

## Date对象
- Var myDate = new Date()
- Date对象会自动把当前的日期和时间保存为其初始值

## Math对象方法

Math.ceil(x)方法执行的是向上取整计算，它返回的是大于或等于函数参数，并且与之最接近的整数。

例如:
- Math.ceil(12.2)返回13
- Math.ceil(12.7)返回13
- Math.ceil(12.0)返回12