
程序结构
------------

- 申明

entity object declaration : var, const, type, func

包一级的声明，在包的所有源文件中都可以访问

- 变量

var 变量名字 类型 = 表达式
如果类型被省略，则自动推倒值
如果表达式被省略，则富裕默认值

简短变量申明 := 方式，申明并赋值, 如果简短变量被申明了
那么这个表达式，将会被赋值

采用var方式，通常是全局，或者稍后将会被赋值

函数返回的局部变量的地址，依然有效



****变量的别名****



数据类型
========================

- **字符串**

字符串的值，是不可更改的
字符串的，长度是内置函数，指字节数目，不是字符数目
字符串的，索引为字节索引
字符串，可以通过 str[tartIndex : endIndex]创建一个
字串，startIndex, endIndex可以忽略，则为(0, len(str))
字符串比较，是同过比较字节数目来进行

使用反引号，可以使字符串变为原生字符串，没有转义发生



- 数组

数组类型定义， var variableName = [constentLen]type {initial value | 
                                                                  | //emtpy values
                                                   index: value}    //index to specialed values otehrs empty
              var variableName1 = [...]type (below)

          






- ***slice 切片***

切片可以看作是数组部分的一个




方法
=======================

- ***方法的申明***

func (f reciever) funcName (arglist ..) (retlist ..) {}

reciever : 接收器，如this, self
funcName : 选择器，如成员函数的名称

可以为内置类型，增加一些方法（指针除外）

如，为切片类型增加一些方法
type path []int
func (p path) distance(x, y int) ret int {}


- ***指针对象的方法***




