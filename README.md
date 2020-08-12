
## Golang笔记

go中的变量定义以后必须要使用



变量需要声明后才能使用

```go
var name string="zhangsan"
a :=10
var b=10
```



一次定义多个变量

```go
var(
	username="zhangsan"
	age int
	sex string
)
```



全局变量不能用短变量声明

匿名变量不占用命名空间，不会分配内存，所以匿名变量不存在重复声明



常量的值不可改变

```go
const pi=3.14
```



const同时声明多个常量时，如果省略了值则表示和上面一行的值相同

```go
const(
	n1=100
	n2
	n3
	n4
)
```

iota常量计数器

```go
const(
	n1=iota //0
	n2		//1
	n3		//2
	n4		//3
)
```



go中的变量的名字是区分大小写的



基本数据类型：整型，浮点，布尔，字符串

复合数据类型：数组，切片，结构体，函数，map，channel，interface等

![](C:\Users\Joseph\Desktop\新建文件夹\整型.PNG)



两种浮点：float32 and float64

