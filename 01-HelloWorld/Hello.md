# Go语言

## 介绍

go是有谷歌创建并开源的语言，出生于2009年11月10日，肯-汤普森、罗布-派克、Robert-Griesemer设计并开源该语言，这是一个可以更好的利用多核CPU、简洁高效、风格统一的编程语言。Go语言进能够保证达到静态编译语言的安全和性能，又能够达到动态语言开发维护的高效率。主要的特点有：

1. 从c语言中继承了很多的理念，也保留了c语言一样的编译执行方式以及弱化的指针。

2. 引入了包的概念，每个文件都要归属与某一个包，不能够单独存在。

3. 垃圾回收机制。

4. 天然并发（😭目前还在浅水区，未能体验到）

5. 管道的通信机制

6. 函数可以返回多个值

7. 切片（与python中相似），演示的defer(使用先进后出的栈延时释放资源)  

hello走起：

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello World")
}
/*
输出
Hello World
*/
```
