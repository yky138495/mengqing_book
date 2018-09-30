# Lua 循环



很多情况下我们需要做一些有规律性的重复操作，因此在程序中就需要重复执行某些语句。

一组被重复执行的语句称之为循环体，能否继续重复，决定循环的终止条件。

循环结构是在一定条件下反复执行某段程序的流程结构，被反复执行的程序被称为循环体。

循环语句是由循环体及循环的终止条件两部分组成的。![](http://www.runoob.com/wp-content/uploads/2015/12/loop.png)

Lua 语言提供了以下几种循环处理方式：

| 循环类型 | 描述 |
| :--- | :--- |
| [while 循环](http://www.runoob.com/lua/lua-while-loop.html) | 在条件为 true 时，让程序重复地执行某些语句。执行语句前会先检查条件是否为 true。 |
| [for 循环](http://www.runoob.com/lua/lua-for-loop.html) | 重复执行指定语句，重复次数可在 for 语句中控制。 |
| [repeat...until](http://www.runoob.com/lua/lua-repeat-until-loop.html) | 重复执行循环，直到 指定的条件为真时为止 |
| [循环嵌套](http://www.runoob.com/lua/lua-nested-loops.html) | 可以在循环内嵌套一个或多个循环语句（while do ... end;for ... do ... end;repeat ... until;） |

### 循环控制语句

循环控制语句用于控制程序的流程， 以实现程序的各种结构方式。

Lua 支持以下循环控制语句：

| 控制语句 | 描述 |
| :--- | :--- |
| [break 语句](http://www.runoob.com/lua/lua-break-statement.html) | 退出当前循环或语句，并开始脚本执行紧接着的语句。 |

### 无限循环

在循环体中如果条件永远为 true 循环语句就会永远执行下去，以下以 while 循环为例：

```text
while( true )
do
   print("循环将永远执行下去")
end
```

