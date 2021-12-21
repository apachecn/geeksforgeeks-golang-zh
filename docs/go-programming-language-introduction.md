# Go 编程语言(简介)

> 原文:[https://www . geesforgeks . org/go-programming-language-introduction/](https://www.geeksforgeeks.org/go-programming-language-introduction/)

**简介**

[**Go**](https://www.geeksforgeeks.org/go-programming-language/) 是一种程序化的编程语言。它是由罗伯特·格里森、罗布·派克和肯·汤普森在谷歌于 2007 年在 T4 开发的，但在 2009 年作为开源编程语言推出。程序通过使用包来组装，以便有效地管理依赖关系。这种语言也支持环境采用与动态语言相似的模式。例如，类型推断(y := 0 是浮点型变量 y 的有效声明)。

**从** [**开始进行编程**](https://www.geeksforgeeks.org/go-programming-language/)

网上有各种各样的 IDEs，如围棋、复盘等。它可以用来运行 Go 程序而无需安装。

要在自己的电脑或笔记本电脑上安装 Go，我们需要以下两个软件:文本编辑器和编译器
**文本编辑器:**文本编辑器为您提供了一个*平台*，您可以在这里编写源代码。以下是文本编辑器列表:

*   Windows 记事本
*   操作系统编辑命令
*   简短的
*   埃普西隆
*   虚拟机或虚拟设备
*   Emacs
*   VS 代码

**寻找 Go 编译器:** Go 发行版以可二进制安装的形式提供给 *FreeBSD* (第 8 版及以上版本) *Linux、Mac OS X(雪豹及以上版本)*以及采用 *32 位(386)* 和 *64 位(amd64) x86* 处理器架构的 Windows 操作系统。
了解更多安装说明。请访问[安装 GO 发行版](https://golang.org/doc/install)

```go
Note: Extension of source code file of go language must be .go
```

**在 Go 写第一个程序:**

## 去

```go
package main 

import "fmt"

func main() {

     // prints geeksforgeeks
     fmt.Println("Hello, geeksforgeeks")
}
```

**输出:**

```go
Hello, geeksforgeeks
```

**Go 程序语法解释:**

*   **第 1 行:**包含节目的*包主*，有节目的整体内容。这是运行程序的起点，所以必须要写。
*   **第 2 行:**它包含*导入“fmt”*，这是一个预处理器命令，告诉编译器包含包中的文件。
*   **第 3 行:** *主功能*，是程序执行的开始。
*   **4 号线:** *fmt。Println()* 是一个标准的库函数，用来在屏幕上打印一些东西作为输出。其中， *fmt* 包传输了 Println 方法，用于显示输出。
*   **注释:**注释用于解释代码，使用方式与 [Java](https://www.geeksforgeeks.org/java/) 或 [C](https://www.geeksforgeeks.org/c-programming-language/) 或 [C++](https://www.geeksforgeeks.org/c-plus-plus/) 相似。编译器忽略注释条目，并且不执行它们。注释可以是单行或多行。

**单行注释:**

**语法:**

```go
// single line comment
```

**多行评论:**

**语法:**

```go
/* multiline comment */
```

**下面是另一个例子:**

## 去

```go
package main
import "fmt"

func main() {
   fmt.Println("1 + 1 =", 1 + 1)
}
```

**输出:**

```go
1 + 1 = 2
```

**以上程序说明:**
在以上这个程序中，相同的包行，相同的导入行，相同的函数声明，使用的 Println 函数和我们在 *1st GO 程序*中使用的一样。这次我们不是打印字符串*“你好，极客们”*而是打印字符串 1 + 1 =后跟表达式 1 + 1 的结果。这个表达式由三部分组成:数值文字 1(类型为 int)、+运算符(表示加法)和另一个数值文字 1。

**为什么会出现这种“围棋语言”？**

因为 Go 语言努力将解释的动态类型语言的编程简单性与静态类型的编译语言的效率和安全性结合起来。它的目标也是现代化，支持网络化和多核计算。

**在围棋中排除其他语言中存在的什么？**

*   Go 试图减少单词两个意思的打字量。在整个设计中，开发人员试图减少混乱和复杂性。
*   没有正向声明，也没有头文件；每件事都只声明一次。
*   通过使用 **:=** 声明和初始化构造进行简单的类型推导，可以减少口吃。
*   没有类型层级:类型只是*是*，它们不需要公布它们的关系。

**硬件限制**

我们观察到，十年来，硬件和处理配置的变化速度非常慢。2004 年，P4 的时钟速度为 3.0 千兆赫，现在 2018 年，Macbook pro 的时钟速度约为(2.3 千兆赫对 2.66 千兆赫)。为了加快速度，我们使用更多的处理器，但是使用更多的处理器，成本也会增加。由于这个原因，我们使用有限的处理器，使用有限的处理器，我们有一个沉重的编程语言，其线程占用更多的内存，降低了我们系统的性能。因此，为了克服这样的问题，Golang 的设计方式是不使用线程，而是使用 Goroutine，这类似于线程，但消耗的内存非常少。
类似线程消耗 1MB，而 goro tine 消耗 2KB 内存，因此同时，我们可以触发数百万个 goro tine。
所以上面讨论的这一点使得 golang 成为一种像 C++和 Java 一样处理并发性的强大语言。

**围棋语言的优缺点**

**优势:**

1.  灵活——简洁、简单、易读。
2.  并发性——它允许多个进程同时有效地运行。
3.  快速结果——它的编译时间非常快。
4.  库-它提供了一个丰富的标准库。
5.  垃圾收集——这是围棋的一个重要特点。Go 擅长对内存分配进行大量控制，并在最新版本的垃圾收集器中显著降低了延迟。
6.  它验证接口和类型嵌入。

**缺点:**

1.  它不支持泛型，即使有很多关于它的讨论。
2.  用这种编程语言分发的包非常有用，但是 Go 并不是传统意义上的面向对象。
3.  缺少一些库，尤其是用户界面工具包。

**一些用 Go 语言开发的热门应用**

*   Docker:一套部署 linux 容器的工具
*   **Openshift:** 红帽推出的云计算平台即服务。
*   **Kubernetes:** 无缝自动化部署流程的未来
*   **Dropbox:** 将他们的一些关键组件从 Python 迁移到 Go。
*   **网飞:**为他们的服务器架构的两个部分。
*   **InfluxDB:** 是由 InfluxData 开发的开源时间序列数据库。
*   **Golang:** 语言本身就是用 Go 写的。

[目前使用 Go 语言的国别公司。](https://github.com/golang/go/wiki/GoUsers)

**围棋语言的特点**

*   **语言设计:**语言的设计者做了一个有意识有目的的保持语言简单易懂。整个细节在几页中，一些有趣的设计决策是通过语言中的*面向对象*支持做出的。对于这一点，语言是固执己见的，推荐一种*惯用的*达成目标的方式。比起继承，它更喜欢合成。在围棋语言中，*“少花钱多办事”*是口头禅。
*   **包管理:** Go 融合了现代开发人员与*开源项目*合作的工作流程，并将其包含在管理外部包的方式中。直接在工具中提供支持，以获取外部包并在一组简单的命令中发布您自己的包。
*   **强大的标准库:** Go 拥有强大的标准库，以包的形式分发。
*   **静态类型化:** Go 是静态类型化语言。因此，在这个编译器中，不仅要成功编译代码，还要确保类型转换和兼容性。由于这个特性，Go 避免了我们在动态类型语言中面临的所有问题。
*   **测试支持:** Go 本身为我们提供了单元测试特性，即一个简单的机制来编写与代码并行的单元测试，因此您可以通过自己的测试来理解代码覆盖率。作为一个例子，这可以很容易地用于生成代码文档。
*   **平台无关:** Go 语言和 Java 语言一样，支持平台无关性。由于其模块化设计和模块化，即代码被编译并转换成尽可能小的二进制形式，因此不需要依赖。它的代码可以在任何平台或你工作的任何服务器和应用程序中编译。