# Java教程（中文笔记）

Java教程是为JDK 8而编写的。本页中介绍的示例和练习未利用后续版本中引入的改进。

Java教程是希望使用Java编程语言创建应用程序的程序员的实用指南。 它们包括数百个完整的工作示例和数十个课程。 相关课程组被组织成“Trails”。

# 入门

Java技术介绍和安装Java开发软件的课程，并用它来创建一个简单的程序。

## Java技术现象

谈论Java技术似乎无处不在，但究竟是什么呢？ 以下各节介绍了Java技术既是一种编程语言又是一种平台，并概述了该技术可为您做些什么。

### 关于Java技术

Java技术既是一种编程语言，也是一个平台。

#### Java编程语言

Java编程语言是一种高级语言，可以用以下所有流行语来表征：

- 简单 
- 面向对象
- 分布式
- 多线程
- 多态
- Architecture neutral
- 可移植性强
- 高性能
- 鲁棒性
- 安全

在Java语言环境中，James Gosling和Henry McGilton编写了一份白皮书，解释了上述每个术语。

在Java编程语言中，所有源代码首先以纯文本文件编写，并以.java扩展名结尾。 这些源文件然后由javac编译器编译到.class文件中。 .class文件不包含处理器本机的代码; 它代之以字节码 -  Java虚拟机（Java VM）的机器语言。 Java启动程序工具然后使用Java虚拟机的实例运行您的应用程序。

由于Java VM在许多不同的操作系统上都可用，因此相同的.class文件可以在Microsoft Windows，Solaris™操作系统（Solaris OS），Linux或Mac OS上运行。 一些虚拟机（例如Java SE HotSpot概览）在运行时执行其他步骤，以提高应用程序的性能。 这包括各种任务，如查找性能瓶颈和重新编译（本地代码）经常使用的代码部分。

#### Java平台

平台是程序运行的硬件或软件环境。 我们已经提到了一些最流行的平台，如Microsoft Windows，Linux，Solaris OS和Mac OS。 大多数平台可以被描述为操作系统和底层硬件的组合。 Java平台不同于大多数其他平台，因为它是一个运行在其他基于硬件的平台之上的纯软件平台。

Java平台有两个组件：

- Java虚拟机
- Java应用程序编程接口（API）

您已经被引入Java虚拟机; 它是Java平台的基础，并被移植到各种基于硬件的平台上。

API是大量现成的软件组件，提供许多有用的功能。 它被分组到相关类和接口的库中; 这些库被称为包。 下一节，Java技术可以做什么？ 强调了API提供的一些功能。

### Java技术可以做什么？

通用的高级Java编程语言是一个功能强大的软件平台。 Java平台的每个完整实现都会为您提供以下功能：

- **开发工具**：开发工具提供编译，运行，监视，调试和记录应用程序所需的一切。 作为一名新开发人员，您将使用的主要工具是javac编译器，java启动程序和javadoc文档工具。
- **应用程序编程接口（API）**：该API提供了Java编程语言的核心功能。 它提供了大量有用的类，可以在您自己的应用程序中使用。 它涵盖了从基本对象到网络和安全，到XML生成和数据库访问等等的所有内容。 核心API非常大; 要了解它包含的内容，请参阅Java Platform Standard Edition 8文档。
- **部署技术**：JDK软件提供标准机制，例如用于将应用程序部署到最终用户的Java Web Start软件和Java Plug-In软件。
- **用户界面工具包**：JavaFX，Swing和Java 2D工具包使创建复杂的图形用户界面（GUI）成为可能。
- **集成库**：Java IDL API，JDBC API，Java命名和目录接口（JNDI）API，Java RMI和基于因特网ORB间协议技术的Java远程方法调用（Java RMI-IIOP技术）等集成库支持数据库访问 和远程对象的操纵。

### Java技术将如何改变我的生活？

如果你学习Java编程语言，我们不能保证你的名声，财富，甚至是工作。 尽管如此，它可能会使您的程序更好，并且比其他语言花费更少的工作量。 我们相信Java技术将帮助您做到以下几点：

- **快速入门**：尽管Java编程语言是一种功能强大的面向对象语言，但它很容易学习，尤其对于已经熟悉C或C ++的程序员而言。
- **编写较少的代码**：程序度量（类别计数，方法计数等）的比较表明，使用Java编程语言编写的程序可能比使用C ++编写的同一程序小四倍。
- **编写更好的代码**：Java编程语言鼓励良好的编码实践，自动垃圾收集可帮助您避免内存泄漏。 它的面向对象，JavaBeans™组件体系结构以及范围广泛且易于扩展的API使您可以重复使用现有的经过测试的代码并引入更少的错误。
- **更快地开发程序**：Java编程语言比C ++更简单，因此，编写它时，开发时间可能会快两倍。 你的程序也需要更少的代码。
- **避免平台依赖性**：通过避免使用用其他语言编写的库，可以保持程序的可移植性。
- **一次编写，随处运行**：由于使用Java编程语言编写的应用程序编译为与机器无关的字节码，因此它们可以在任何Java平台上始终运行。
- **更轻松地分发软件**：使用Java Web Start软件，用户只需单击鼠标即可启动应用程序。 启动时的自动版本检查可确保用户随时了解最新版本的软件。 如果有更新可用，Java Web Start软件将自动更新其安装。

## “Hello World！” 应用

## 仔细看看“Hello World！”

## 常见问题（及其解决方案）

# 学习Java语言

该章节描述了Java编程语言基本概念和功能。

## 面向对象的编程概念

如果你以前从未使用过面向对象的编程语言，那么在你开始编写任何代码之前，你需要学习一些基本概念。 本课将向您介绍对象，类，继承，接口和包。 每个讨论的重点是如何将这些概念与现实世界联系起来，同时介绍Java编程语言的语法。

### 什么是对象？

一个对象是一个相关状态和行为的软件包。 软件对象通常用于模拟您在日常生活中发现的真实世界对象。 本课介绍了状态和行为在对象中的表现方式，介绍了数据封装的概念，并解释了以这种方式设计软件的好处。

对象是理解面向对象技术的关键。 现在环顾四周，你会发现许多真实世界物体的例子：你的狗，你的桌子，你的电视机，你的自行车。

真实世界的物体有两个特点：它们都有状态和行为。 狗有状态（名字，颜色，品种，饥饿）和行为（吠叫，取指，摇尾巴）。 自行车还具有状态（当前档位，当前踏板节奏，当前速度）和行为（变换档位，改变踏板节奏，应用制动器）。 识别真实世界对象的状态和行为是从面向对象编程开始思考的好方法。

现在花一点时间观察您附近区域的真实世界物体。 对于你看到的每个物体，问自己两个问题：“这个物体可能有哪些状态？” 和“这个对象有什么可能的行为？”。 确保写下你的观察结果。 和你一样，你会注意到真实世界的对象在复杂性上有所不同; 您的桌面灯可能只有两种可能的状态（开和关）以及两种可能的行为（打开，关闭），但您的桌面收音机可能会有其他状态（开，关，当前音量，当前电台）和行为（打开 ，关闭，增加音量，减小音量，寻找，扫描和调频）。 您可能还会注意到，某些对象反过来也会包含其他对象。 这些真实世界的观察都转化为面向对象编程的世界。

软件对象在概念上与真实世界的对象相似：它们也包含**状态**和**相关**行为。 对象将其状态存储在**字段**（某些编程语言中的变量）中，并通过**方法**（某些编程语言中的函数）公开其行为。 方法对对象的内部状态进行操作，并作为对象到对象通信的主要机制。 隐藏内部状态并要求通过对象方法执行所有交互被称为**数据封装** - 数据封装是面向对象编程的基本原则。

将代码捆绑到单个软件对象中提供了许多好处，其中包括：

- **模块化**：可以独立于其他对象的源代码编写和维护对象的源代码。 一旦创建，一个对象可以很容易地在系统内传递。
- **信息隐藏**：通过仅与对象的方法交互，其内部实现的细节对外界保持隐藏。
- **代码复用**：如果某个对象已经存在（可能由另一个软件开发人员编写），则可以在程序中使用该对象。 这允许专家实现/测试/调试复杂的，特定任务的对象，然后您可以信任它们在自己的代码中运行。
- **可插拔性和调试简便性**：如果某个特定对象变得有问题，您可以简单地将它从应用程序中删除，并插入其他对象作为替换对象。 这类似于解决现实世界中的机械问题。 如果螺栓损坏，请更换，而不是整台机器。

### 什么是类？

类是创建对象的蓝图或原型。 本节定义了一个模拟真实世界对象的状态和行为的类。 它故意专注于基础知识，展示一个简单的类甚至可以干净地为状态和行为建模。

在现实世界中，你经常会发现很多单独的物体都是同一种物体。 可能有成千上万的其他自行车存在，所有相同的品牌和型号。 每辆自行车都由同一套蓝图构成，因此包含相同的部件。 在面向对象的术语中，我们说你的自行车是一类称为自行车的物体的一个实例。 一个类是创建单个对象的蓝图。

以下自行车类是一种可能的自行车实现方式：

```java

class Bicycle {

    int cadence = 0;
    int speed = 0;
    int gear = 1;

    void changeCadence(int newValue) {
         cadence = newValue;
    }

    void changeGear(int newValue) {
         gear = newValue;
    }

    void speedUp(int increment) {
         speed = speed + increment;   
    }

    void applyBrakes(int decrement) {
         speed = speed - decrement;
    }

    void printStates() {
         System.out.println("cadence:" +
             cadence + " speed:" + 
             speed + " gear:" + gear);
    }
}
```

Java编程语言的语法对你来说看起来很新，但这个类的设计是基于前面对自行车对象的讨论。 类成员踏板节奏，速度和齿轮表示对象的状态，方法（changeCadence，changeGear，speedUp等）定义了它与外部世界的交互。

您可能已经注意到Bicycle类不包含main主方法。 那是因为它不是一个完整的应用程序; 这只是可能用于应用程序的自行车蓝图。 创建和使用新的Bicycle对象的责任属于应用程序中的其他类。

这是一个BicycleDemo类，它创建两个独立的Bicycle对象并调用它们的方法：

```java
class BicycleDemo {
    public static void main(String[] args) {

        // Create two different 
        // Bicycle objects
        Bicycle bike1 = new Bicycle();
        Bicycle bike2 = new Bicycle();

        // Invoke methods on 
        // those objects
        bike1.changeCadence(50);
        bike1.speedUp(10);
        bike1.changeGear(2);
        bike1.printStates();

        bike2.changeCadence(50);
        bike2.speedUp(10);
        bike2.changeGear(2);
        bike2.changeCadence(40);
        bike2.speedUp(10);
        bike2.changeGear(3);
        bike2.printStates();
    }
}
```

该测试的输出结果为打印两辆自行车结束踏板节奏，速度和齿轮：

```java
cadence:50 speed:10 gear:2
cadence:40 speed:20 gear:3
```



### 什么是继承？

继承为组织和构建软件提供了强大而自然的机制。 本节介绍了类如何继承其超类的状态和行为，并解释了如何使用Java编程语言提供的简单语法从另一个类派生另一个类。

不同种类的物体通常具有一定的共同点。 例如，山地自行车，公路自行车和双人自行车都具有自行车的特征（当前速度，当前踏板节奏，当前档位）。 然而每一个也定义了使它们不同的附加特征：双人自行车有两个座位和两组把手; 公路自行车有把手; 一些山地自行车有一个额外的链环，给他们一个较低的传动比。

面向对象编程允许类从其他类继承常用的状态和行为。 在这个例子中，Bicycle现在成为MountainBike，RoadBike和TandemBike的超类。 在Java编程语言中，每个类都允许有一个直接超类，每个超类都有可能有无数个子类：

![](https://raw.githubusercontent.com/shawn520/javaTutorials/master/img/concepts-bikeHierarchy.gif)

创建子类的语法很简单。 在类声明的开始处，使用extends关键字，后跟要继承的类的名称：

```java
class MountainBike extends Bicycle {

    // new fields and methods defining 
    // a mountain bike would go here

}
```

这给了MountainBike所有与Bicycle相同的领域和方法，但允许其代码专注于使其独特的功能。 这使得您的子类的代码易于阅读。 但是，必须注意正确记录每个超类定义的状态和行为，因为该代码不会出现在每个子类的源文件中。

### 什么是接口？

接口是类与外部世界的契约。 当一个类实现一个接口时，它承诺提供该接口发布的行为。 本节定义了一个简单的接口，并解释了实现它的任何类的必要更改。

正如你已经知道的那样，对象通过它们公开的方法来定义它们与外界的交互。 方法形成对象与外界的接口; 例如，电视机前面的按钮就是您和塑料外壳另一侧电线之间的接口。 您按下“电源”按钮打开和关闭电视机。

在其最常见的形式中，接口是一组没有方法体的相关方法。 如果指定为接口，自行车的行为可能如下所示：

```java
interface Bicycle {

    //  wheel revolutions per minute
    void changeCadence(int newValue);

    void changeGear(int newValue);

    void speedUp(int increment);

    void applyBrakes(int decrement);
}
```

为了实现这个接口，你的类的名字会改变（例如，一个特定品牌的自行车，例如ACMEBicycle），你可以在类声明中使用implements关键字：

```java
class ACMEBicycle implements Bicycle {

    int cadence = 0;
    int speed = 0;
    int gear = 1;

   // The compiler will now require that methods
   // changeCadence, changeGear, speedUp, and applyBrakes
   // all be implemented. Compilation will fail if those
   // methods are missing from this class.

    void changeCadence(int newValue) {
         cadence = newValue;
    }

    void changeGear(int newValue) {
         gear = newValue;
    }

    void speedUp(int increment) {
         speed = speed + increment;   
    }

    void applyBrakes(int decrement) {
         speed = speed - decrement;
    }

    void printStates() {
         System.out.println("cadence:" +
             cadence + " speed:" + 
             speed + " gear:" + gear);
    }
}
```

实现一个接口允许一个类对它承诺提供的行为变得更加正式。 接口形成了类和外部世界之间的契约，并且这个契约在编译器的编译时执行。 如果您的类声明实现了一个接口，那么在该类成功编译之前，该接口定义的所有方法都必须出现在其源代码中。

注意：要实际编译ACMEBicycle类，您需要将public关键字添加到实现的接口方法的开头。 稍后您将在类和对象以及接口和继承的课程中了解其原因。

### 什么是包？

包是一种以逻辑方式组织类和接口的名称空间。 将您的代码放入软件包中可以使大型软件项目更易于管理。 本节解释了为什么这很有用，并向您介绍了Java平台提供的应用程序编程接口（API）。

包是一个命名空间，它组织一组相关的类和接口。 从概念上讲，您可以将软件包视为与计算机上的不同文件夹类似。 您可以将HTML页面保存在一个文件夹中，另一个文件中包含图像，另一个文件夹中包含脚本或应用程序。 因为用Java编程语言编写的软件可以由数百或数千个单独的类组成，所以通过将相关的类和接口放入包中来组织事物是很有意义的。

Java平台提供了适用于您自己的应用程序的庞大的类库（一组包）。 该库被称为“应用程序编程接口”，简称“API”。 它的软件包代表了通常与通用编程相关的任务。 例如，一个String对象包含字符串的状态和行为; File对象允许程序员轻松创建，删除，检查，比较或修改文件系统上的文件; 一个Socket对象允许创建和使用网络套接字; 各种GUI对象控制按钮和复选框以及与图形用户界面相关的任何其他内容。 有几千个类可供选择。 这使得程序员可以专注于特定应用程序的设计，而不是专注于使其工作所需的基础架构。

Java平台API规范包含Java SE平台提供的所有包，接口，类，字段和方法的完整列表。 在浏览器中加载页面并为其添加书签。 作为程序员，它将成为您最重要的参考文档。

### 问题和练习

使用本节介绍的问题和练习来测试你对对象，类，继承，接口和包的理解。

#### 问题

​     真实世界的对象包含___和___。
     软件对象的状态存储在___中。
     软件对象的行为通过___公开。
     隐藏来自外部世界的内部数据，并仅通过公开暴露的方法访问它，这就是数据___。
     软件对象的蓝图称为___。
     常见行为可以在___中定义，并使用___关键字继承到___中。
     没有实现的方法集合称为___。
     按功能组织类和接口的名称空间称为___。
     术语API代表___？

#### 练习

## 语言基础

### 变量

正如您在前一课中学到的，对象将其状态存储在字段中。

```java
int cadence = 0;
int speed = 0;
int gear = 1;
```

什么是对象？章节 讨论向你介绍了领域，但你可能还有一些疑问，例如：命名领域的规则和约定是什么？ 除了int之外，还有哪些其他数据类型？ 领域必须在声明时进行初始化？ 如果字段未被显式初始化，字段是否分配了默认值？ 我们将在本课中探讨这些问题的答案，但在此之前，您必须首先意识到一些技术上的区别。 在Java编程语言中，术语“字段”和“变量”都被使用; 这是新开发人员混淆的一个常见原因，因为两者似乎都指向相同的东西。

Java编程语言定义了以下几种变量：

- **实例变量（非静态字段）**从技术上讲，对象将其各个状态存储在“非静态字段”中，即不使用static关键字声明的字段。 非静态字段也称为实例变量，因为它们的值对于类的每个实例（对每个对象都是唯一的），换句话说; 一辆自行车的当前速度与另一辆自行车的速度无关。
- **类变量（静态字段）** 类变量是用静态修饰符static声明的任何字段; 这告诉编译器，这个变量只有一个副本存在，而不管该类实例化了多少次。 定义特定类型自行车的齿轮数量的字段可以被标记为静态的，因为概念上相同数量的齿轮将适用于所有情况。 代码会 `static int numGears = 6;`创建这样一个静态字段。 另外，关键字final可以被添加以指示齿轮的数量永远不会改变。
- **局部变量**  类似于对象如何在字段中存储其状态，方法通常会将其临时状态存储在局部变量中。 声明局部变量的语法类似于声明一个字段（例如，`int count = 0;`）。 没有特殊的关键字将变量指定为本地; 该决定完全来自变量声明的位置 - 这是在方法的开始和结束括号之间。 因此，局部变量只对声明它们的方法可见; 无法从所属类的其他地方得到该局部变量。
- **参数** 您已经在Bicycle类和“Hello World！” 应用的主要方法中看到了参数的示例。 回想一下，main方法的签名是`public static void main（String [] args）`。 这里，args变量是这个方法的参数。 重要的是要记住参数总是被分类为“变量”而不是“字段”。 这也适用于其他参数接受构造（例如构造函数和异常处理程序），您将在本教程后面了解这些构造函数和异常处理程序。

话虽如此，本教程的其余部分在讨论字段和变量时使用以下一般准则。 如果我们在谈论“一般字段”（不包括局部变量和参数），我们可能会简单地说“字段”。 如果讨论适用于“所有上述”，我们可以简单地说“变量”。 如果上下文需要区分，我们将酌情使用特定的术语（静态字段，局部变量等）。 您也可能偶尔会看到使用“成员”一词。 类型的字段，方法和嵌套类型统称为其成员。

##### 命名

每种编程语言都有自己的一套规则和约定，用于允许使用的名称类型，Java编程语言也不例外。 命名变量的规则和约定可以总结如下：

- 变量名称区分大小写。 变量的名称可以是任何合法标识符  一个以字母，美元符号“$”或者下划线"_"开头的无限长的Unicode字母和数字序列。但是，惯例是始终用一个字母开始变量名。此外，按照惯例，美元符号字符根本不会被使用。 您可能会发现某些情况下自动生成的名称将包含美元符号，但您的变量名称应始终避免使用它。 下划线字符存在类似的约定; 尽管用“_”开始变量的名称在技术上是合法的，但这种做法是不鼓励的。 不允许使用空格。
- 后续字符可能是字母，数字，美元符号或下划线字符。惯例（和常识）也适用于此规则。 为变量选择名称时，请使用完整的单词而不是隐含的缩写。 这样做会使您的代码更易于阅读和理解。 在很多情况下，它也会使你的代码自动记录; 例如，名为节奏，速度和齿轮的字段比缩写版本更直观，例如s，c和g。 另外请记住，您选择的名称不能是关键字或保留字。
- 如果您选择的名称只包含一个单词，请以全部小写字母拼出该单词。 如果它包含多个单词，请将每个后续单词的首字母大写。 gearRatio和currentGear这些名称是这个约定的主要例子。 如果你的变量存储了一个常量值，比如static final int NUM_GEARS = 6，那么约定略有变化，大写每个字母并用下划线分隔后续单词。 按照惯例，下划线字符不会在其他地方使用。

#### 基本数据类型

Java编程语言是静态类型的，这意味着所有变量必须先声明才能使用。 这包括声明变量的类型和名称，正如您已经看到的那样：

```java
int gear = 1;
```

这样做会告诉程序存在名为“gear”的字段，保存数字数据并且初始值为“1”。 变量的数据类型决定了它可能包含的值，以及可能对其执行的操作。 除了int，Java编程语言还支持其他七种基本数据类型。 基本数据类型由语言预定义，并由保留关键字命名。 基本数据不与其他基本数据共享状态。 Java编程语言支持的八种基本数据类型是：

- **byte**：字节数据类型是一个8位带符号的二进制补码整数。 它的最小值为-128，最大值为127（包括）。 字节数据类型对于在大型数组中保存内存很有用，其中内存节省实际上很重要。 
- **Short**：Short数据类型是一个16位有符号的二进制补码整数。 它的最小值为-32,768，最大值为32,767（含）。 与字节一样，也适用相同的指导原则：在实际节省内存的情况下，可以使用short来节省大型数组中的内存。
- i**nt**：默认情况下，int数据类型是一个32位有符号的二进制补码整数，其最小值为-2的31次方，最大值为2的31次方-1。 在Java SE 8和更高版本中，可以使用int数据类型来表示无符号的32位整数，其最小值为0，最大值为2的32次方-1。 使用Integer类将int数据类型用作无符号整数。 有关更多信息，请参阅数字类部分。 像compareUnsigned，divideUnsigned等静态方法已被添加到Integer类以支持无符号整数的算术运算。
- **long**：长数据类型是一个64位二进制补码整数。 有符号的长整数的最小值为-2的63次方，最大值为2的63次方-1。 在Java SE 8和更高版本中，可以使用长数据类型来表示无符号的64位长，其最小值为0，最大值为2的64次方-1。 当您需要的值范围比int提供的范围宽时，使用此数据类型。 Long类还包含像compareUnsigned，divideUnsigned等方法来支持无符号long的算术运算。
- **float**：浮点数据类型是一个单精度32位IEEE 754浮点。 它的值范围超出了本讨论的范围，但在Java语言规范的浮点类型，格式和值部分中进行了指定。 与对byte和short的建议一样，如果需要将内存保存在浮点数的大数组中，请使用float（而不是double）。 此数据类型不应用于精确值，例如货币。 为此，您需要改为使用java.math.BigDecimal类。 Numbers和Strings涵盖了Java平台提供的BigDecimal和其他有用的类。
- **double**：双数据类型是一个双精度64位IEEE 754浮点。 它的值范围超出了本讨论的范围，但在Java语言规范的浮点类型，格式和值部分中进行了指定。 对于十进制值，这种数据类型通常是默认选择。 如上所述，此数据类型不应用于精确值，例如货币。
- **布尔值**：布尔数据类型只有两个可能的值：true和false。 将此数据类型用于跟踪真/假条件的简单标志。 这种数据类型代表了一比特信息，但它的“大小”并不是精确定义的。
- **char**：char数据类型是一个单一的16位Unicode字符。 它的最小值为'\ u0000'（或0），最大值为'\ uffff'（或65,535）。

除了上面列出的八种基本数据类型外，Java编程语言还通过java.lang.String类提供了对字符串的特殊支持。 用双引号括起你的字符串会自动创建一个新的String对象; 例如，String s =“这是一个字符串”; 字符串对象是不可变的，这意味着一旦创建，它们的值就不能改变。 String类在技术上不是基本数据类型，但考虑到该语言给予它特殊的支持，您可能倾向于这样认为。 您将在Simple Data Objects中学习更多关于String类的内容

##### 默认值

当声明一个字段时，并不总是需要赋值。 已声明但未初始化的字段将由编译器设置为合理的默认值。 一般来说，根据数据类型的不同，此默认值将为零或空值。 然而，依赖于这种默认值，通常被认为是糟糕的编程风格。

以下图表总结了上述数据类型的默认值。

| 数据类型           | 默认值（对于字段） |
| ------------------ | ------------------ |
| byte               | 0                  |
| short              | 0                  |
| int                | 0                  |
| long               | 0L                 |
| float              | 0.0f               |
| double             | 0.0d               |
| char               | '\u0000'           |
| String(或任意对象) | null               |
| boolean            | false              |

局部变量略有不同; 编译器从不将默认值分配给未初始化的局部变量。 如果你不能初始化声明它的局部变量，确保在你尝试使用它之前给它赋值。 访问未初始化的局部变量将导致编译时错误。

##### Literals

您可能已经注意到，在初始化基本类型的变量时，不会使用new关键字。 基本数据类型是内置于语言中的特殊数据类型; 它们不是从一个类创建的对象。 Literals是固定值的源代码表示; Literals直接在你的代码中表示而不需要计算。 如下所示，可以将一个文字分配给基本类型的变量：

```java
boolean result = true;
char capitalC = 'C';
byte b = 100;
short s = 10000;
int i = 100000;
```

##### 整型数据

如果整数字面量以字母L或l结尾，则其类型为long; 否则它是int类型的。 建议您使用大写字母L，因为小写字母l很难与数字1区分开来。

整数类型byte，short，int和long的值可以通过int文字创建。 long类型超出int范围的值可以由长文字创建。 整数文字可以用这些数字系统表示：

- 十进制：基数10，其数字由数字0到9组成; 这是你每天使用的数字系统
- 十六进制：基数16，其数字由数字0到9以及字母A到F组成
- 二进制：Base 2，其数字由数字0和1组成（您可以在Java SE 7及更高版本中创建二进制文字）

对于通用编程，十进制系统可能是您将要使用的唯一数字系统。 但是，如果您需要使用其他号码系统，则以下示例显示正确的语法。 前缀0x表示十六进制，0b表示二进制：

```java
// The number 26, in decimal
int decVal = 26;
//  The number 26, in hexadecimal
int hexVal = 0x1a;
// The number 26, in binary
int binVal = 0b11010;
```

##### 单精度浮点数据

如果浮点数字以字母F或f结尾，则其类型为float; 否则它的类型是双重的，它可以选择以字母D或d结尾。

浮点类型（float和double）也可以用E或e（用于科学记数法），F或f（32位浮点文字）和D或d（64位双字面量;这是默认值，由 惯例被省略）。

```java
double d1 = 123.4;
// same value as d1, but in scientific notation
double d2 = 1.234e2;
float f1  = 123.4f;
```

##### 字符和字符串

char和String类型的文字可以包含任何Unicode（UTF-16）字符。 如果你的编辑器和文件系统允许，你可以直接在你的代码中使用这些字符。 如果没有，您可以使用“Unicode转义”，例如'\ u0108'（大写字母C with circumflex），或者“S \ Sewer”（SíSeñor用西班牙文）。 对字符文字始终使用“单引号”，对字符串文字使用“双引号”。 Unicode转义序列可以在程序的其他地方使用（例如在字段名称中），而不仅仅是char或String文字。

Java编程语言还支持char和String字面值的一些特殊转义序列：\ b（backspace），\ t（tab），\ n（换行符），\ f（换页），\ r（回车）， \“（双引号），\'（单引号）和\\（反斜线）。

还有一个特殊的空字符，可以用作任何引用类型的值。 null可以被分配给任何变量，除了基本类型的变量。 除了测试它的存在之外，你可以用null值做很少的事情。 因此，程序中通常使用null作为标记来指示某个对象不可用。

最后，还有一种称为类文字的特殊类型文字，通过采用类型名称和附加“.class”形成; 例如，String.class。 这是指表示类型本身的对象（类型为Class）。

##### 在数字文字中使用下划线字符

在Java SE 7和更高版本中，任何数字的下划线字符（_）都可以出现在数字字面上的数字之间的任何位置。 例如，此功能支持您。 以数字文字分隔数字组，这可以提高代码的可读性。

例如，如果您的代码包含具有许多数字的数字，则可以使用下划线字符以三个一组来分隔数字，这与使用逗号或空格等标点符号作为分隔符类似。

以下示例显示了可以在数字文字中使用下划线的其他方法：

```java
long creditCardNumber = 1234_5678_9012_3456L;
long socialSecurityNumber = 999_99_9999L;
float pi =  3.14_15F;
long hexBytes = 0xFF_EC_DE_5E;
long hexWords = 0xCAFE_BABE;
long maxLong = 0x7fff_ffff_ffff_ffffL;
byte nybbles = 0b0010_0101;
long bytes = 0b11010010_01101001_10010100_10010010;
```

您只能在数字之间放置下划线; 你不能在下列地方放置下划线：

- 在数字的开头或结尾
- 与浮点数字中的小数点相邻
- 在F或L后缀之前
- In positions where a string of digits is expected

以下示例演示了数字中的有效和无效下划线布局（突出显示）：

```java
// Invalid: cannot put underscores
// adjacent to a decimal point
float pi1 = 3_.1415F;
// Invalid: cannot put underscores 
// adjacent to a decimal point
float pi2 = 3._1415F;
// Invalid: cannot put underscores 
// prior to an L suffix
long socialSecurityNumber1 = 999_99_9999_L;

// OK (decimal literal)
int x1 = 5_2;
// Invalid: cannot put underscores
// At the end of a literal
int x2 = 52_;
// OK (decimal literal)
int x3 = 5_______2;

// Invalid: cannot put underscores
// in the 0x radix prefix
int x4 = 0_x52;
// Invalid: cannot put underscores
// at the beginning of a number
int x5 = 0x_52;
// OK (hexadecimal literal)
int x6 = 0x5_2; 
// Invalid: cannot put underscores
// at the end of a number
int x7 = 0x52_;
```

#### 数组

数组是一个容器对象，它拥有固定数量的单个类型的值。 创建数组时创建数组的长度。 创建后，其长度是固定的。 您已经在“Hello World！” 应用的主要方法中看到了一个数组的例子。 本节更详细地讨论数组。

![https://raw.githubusercontent.com/shawn520/javaTutorials/master/img/objects-tenElementArray.gif](C:\Users\liush\Documents\workspace\javaTutorials\img\objects-tenElementArray.gif)

数组中的每个项目都称为元素，每个元素都通过其数字索引进行访问。 如上图所示，编号从0开始。例如，第9个元素将在索引8处访问。

以下程序ArrayDemo创建一个整数数组，将一些值放入数组中，并将每个值打印到标准输出。

```java
class ArrayDemo {
    public static void main(String[] args) {
        // declares an array of integers
        int[] anArray;

        // allocates memory for 10 integers
        anArray = new int[10];
           
        // initialize first element
        anArray[0] = 100;
        // initialize second element
        anArray[1] = 200;
        // and so forth
        anArray[2] = 300;
        anArray[3] = 400;
        anArray[4] = 500;
        anArray[5] = 600;
        anArray[6] = 700;
        anArray[7] = 800;
        anArray[8] = 900;
        anArray[9] = 1000;

        System.out.println("Element at index 0: "
                           + anArray[0]);
        System.out.println("Element at index 1: "
                           + anArray[1]);
        System.out.println("Element at index 2: "
                           + anArray[2]);
        System.out.println("Element at index 3: "
                           + anArray[3]);
        System.out.println("Element at index 4: "
                           + anArray[4]);
        System.out.println("Element at index 5: "
                           + anArray[5]);
        System.out.println("Element at index 6: "
                           + anArray[6]);
        System.out.println("Element at index 7: "
                           + anArray[7]);
        System.out.println("Element at index 8: "
                           + anArray[8]);
        System.out.println("Element at index 9: "
                           + anArray[9]);
    }
} 
```

这个程序的输出是：

```java
Element at index 0: 100
Element at index 1: 200
Element at index 2: 300
Element at index 3: 400
Element at index 4: 500
Element at index 5: 600
Element at index 6: 700
Element at index 7: 800
Element at index 8: 900
Element at index 9: 1000
```

在现实世界的编程环境中，您可能会使用支持的循环构造之一来遍历数组的每个元素，而不是像前面的示例中那样单独编写每行。 但是，该示例清楚地说明了数组语法。 您将在“控制流”部分中了解各种循环结构（for, while, and do-while）。

##### 声明一个变量来引用一个数组

上述程序使用以下代码行来声明一个数组（名为anArray）：

```java
// declares an array of integers
int[] anArray;
```

像其他类型变量的声明一样，数组声明包含两个组件：数组的类型和数组的名称。 数组的类型写成类型[]，其中type是所包含元素的数据类型; 括号是特殊的符号，表示这个变量包含一个数组。 数组的大小不是其类型的一部分（这就是括号为空的原因）。 数组的名称可以是任何你想要的，只要它遵循前面在命名部分讨论过的规则和约定。 与其他类型的变量一样，该声明实际上并不创建数组; 它只是告诉编译器该变量将保存指定类型的数组。

同样，你可以声明其他类型的数组：

```java
byte[] anArrayOfBytes;
short[] anArrayOfShorts;
long[] anArrayOfLongs;
float[] anArrayOfFloats;
double[] anArrayOfDoubles;
boolean[] anArrayOfBooleans;
char[] anArrayOfChars;
String[] anArrayOfStrings;
```

您也可以在数组名称后面加上括号：

```java
// this form is discouraged
float anArrayOfFloats[];
```

然而，通常不鼓励这种形式; 括号标识数组类型，并应与类型标识一起出现。

##### 创建，初始化和访问数组

创建数组的一种方法是使用新操作符。 ArrayDemo程序中的下一个语句为10个整数元素分配一个具有足够内存的数组，并将数组赋值给anArray变量。

```java
// create an array of integers
anArray = new int[10];
```

如果缺少这个语句，那么编译器打印出如下所示的错误，编译失败：

```java
ArrayDemo.java:4: Variable anArray may not have been initialized.
```

接下来的几行为数组的每个元素赋值

```java
anArray[0] = 100; // initialize first element
anArray[1] = 200; // initialize second element
anArray[2] = 300; // and so forth
```

每个数组元素都通过其数字索引进行访问：

```java
System.out.println("Element 1 at index 0: " + anArray[0]);
System.out.println("Element 2 at index 1: " + anArray[1]);
System.out.println("Element 3 at index 2: " + anArray[2]);
```

或者，您可以使用更便捷的语法来创建和初始化一个数组：

```java
int[] anArray = { 
    100, 200, 300,
    400, 500, 600, 
    700, 800, 900, 1000
};
```

这里数组的长度由花括号之间提供的值的数量决定，并用逗号分隔。

您还可以使用两组或更多组括号（如String [][]名称）声明一个数组数组（也称为多维数组）。 因此，每个元素必须通过相应数量的索引值进行访问。

在Java编程语言中，多维数组是其组件本身就是数组的数组。 这与C或Fortran中的数组不同。 这样做的结果是允许行的长度变化，如下面的MultiDimArrayDemo程序所示：

```java
class MultiDimArrayDemo {
    public static void main(String[] args) {
        String[][] names = {
            {"Mr. ", "Mrs. ", "Ms. "},
            {"Smith", "Jones"}
        };
        // Mr. Smith
        System.out.println(names[0][0] + names[1][0]);
        // Ms. Jones
        System.out.println(names[0][2] + names[1][1]);
    }
}
```

这个程序的输出是：

```java
Mr. Smith
Ms. Jones
```

最后，您可以使用内置长度属性来确定任何数组的大小。 以下代码将数组的大小打印到标准输出：

```java
System.out.println(anArray.length);
```

##### 复制数组

System类有一个arraycopy方法，可以用来有效地将数据从一个数组复制到另一个数组中：

```java
public static void arraycopy(Object src, int srcPos,
                             Object dest, int destPos, int length)
```

两个Object参数指定要从中复制的阵列和要复制到的阵列。 三个int参数指定源数组中的起始位置，目标数组中的起始位置以及要复制的数组元素的数量。

以下程序ArrayCopyDemo声明一组char元素，拼写单词“decaffeinated.”。 它使用System.arraycopy方法将数组组件的子序列复制到第二个数组中：

```java
class ArrayCopyDemo {
    public static void main(String[] args) {
        char[] copyFrom = { 'd', 'e', 'c', 'a', 'f', 'f', 'e',
			    'i', 'n', 'a', 't', 'e', 'd' };
        char[] copyTo = new char[7];

        System.arraycopy(copyFrom, 2, copyTo, 0, 7);
        System.out.println(new String(copyTo));
    }
}
```

这个程序的输出是：

```
caffein
```

##### 数组操作

数组是编程中使用的一个强大且有用的概念。 Java SE提供了执行与数组相关的一些最常见操作的方法。 例如，ArrayCopyDemo示例使用System类的arraycopy方法，而不是手动迭代源数组的元素，并将每个元素放入目标数组中。 这是在幕后执行的，使开发人员只需使用一行代码即可调用该方法。

为了您的方便，Java SE提供了几种用于在java.util.Arrays类中执行数组操作（常见任务，如复制，排序和搜索数组）的方法。 例如，可以修改前面的示例以使用java.util.Arrays类的copyOfRange方法，如ArrayCopyOfDemo示例中所示。 区别在于使用copyOfRange方法不需要您在调用方法之前创建目标数组，因为目标数组是由方法返回的：

```java
class ArrayCopyOfDemo {
    public static void main(String[] args) {
        
        char[] copyFrom = {'d', 'e', 'c', 'a', 'f', 'f', 'e',
            'i', 'n', 'a', 't', 'e', 'd'};
            
        char[] copyTo = java.util.Arrays.copyOfRange(copyFrom, 2, 9);
        
        System.out.println(new String(copyTo));
    }
}
```

正如你所看到的，这个程序的输出是相同的（caffein），尽管它需要更少的代码。 请注意，copyOfRange方法的第二个参数是要复制的范围的初始索引（包含），而第三个参数是要复制范围的最终索引。 在此示例中，要复制的范围不包括索引为9的数组元素（其中包含字符a）。

java.util.Arrays类中的方法提供的一些其他有用的操作是：

- 在数组中搜索特定值以获取放置它的索引（binarySearch方法）。
- 比较两个数组以确定它们是否相等（equals方法）。
- 填充数组以在每个索引处放置特定值（fill方法）。
- 按升序排列数组。 这可以使用排序方法按顺序完成，也可以使用Java SE 8中引入的parallelSort方法同时完成。多处理器系统上的大型数组的并行排序比顺序数组排序要快。

##### 变量摘要

Java编程语言使用“字段”和“变量”作为其术语的一部分。 实例变量（非静态字段）对于类的每个实例都是唯一的。 类变量（静态字段）是用静态修饰符声明的字段; 无论类实例化了多少次，都只有一个类变量的副本。 局部变量在方法内存储临时状态。 参数是为方法提供额外信息的变量; 局部变量和参数总是被分类为“变量”（而不是“字段”）。 当命名你的字段或变量时，你应该（或必须）遵循规则和约定。

八种基本数据类型是：byte，short，int，long，float，double，boolean和char。 java.lang.String类表示字符串。 编译器将为上述类型的字段分配一个合理的默认值; 对于局部变量，从不分配默认值。 literal 是固定值的源代码表示。 数组是一个容器对象，它拥有固定数量的单个类型的值。 创建数组时创建数组的长度。 创建后，其长度是固定的。

##### 练习

1. 术语“实例变量”是___的另一个名称。
2. 术语“类变量”是___的另一个名称。
3. 局部变量存储临时状态; 它在___中被声明。
4. 在方法签名的开始和结束括号内声明的变量称为____。
5. Java编程语言支持的八种基本数据类型是什么？
6. 字符串由类___表示。
7.  ___是一个容器对象，它拥有固定数量的单个类型的值。

### 运算符

现在你已经学会了如何声明和初始化变量，你可能想知道如何对它们做些什么。 学习Java编程语言的操作符是一个很好的开始。 运算符是对一个，两个或三个操作数执行特定操作的特殊符号，然后返回结果。

在我们探索Java编程语言的运算符时，提前知道哪些运算符具有最高优先级可能会对您有所帮助。 下表中的运算符按优先顺序列出。 操作员出现在靠近表格顶部的位置时，其优先级越高。 具有较高优先级的运算符在优先级相对较低的运算符之前进行运算。 同一生产线上的操作员具有同等优先权。 当相同优先级的运算符出现在同一个表达式中时，必须先规定哪个运算符首先被运算。 除赋值运算符外的所有二元运算符都从左到右进行求值; 赋值运算符从右向左运算。

运算符优先级

|     运算符     | 优先级                                   |
| :------------: | :--------------------------------------- |
|      后缀      | `*expr*++ *expr*--`                      |
|      一元      | `++*expr* --*expr* +*expr* -*expr* ~ !`  |
| multiplicative | `* / %`                                  |
|    additive    | `+ -`                                    |
|      移位      | `<< >> >>>`                              |
|   关系运算符   | `< > <= >= instanceof`                   |
|    equality    | == !=                                    |
|     按位与     | &                                        |
|    按位异或    | ^                                        |
|       或       | \|                                       |
|     逻辑与     | &&                                       |
|     逻辑或     | \|\|                                     |
|      三元      | ?:                                       |
|      分配      | `= += -= *= /= %= &= ^= |= <<= >>= >>>=` |

在通用编程中，某些操作符往往比其他操作符更频繁出现; 例如，赋值运算符“=”远比无符号右移运算符“>>>”更常见。 考虑到这一点，下面的讨论首先关注经常使用的操作符，然后将重点放在那些不常见的操作符上。 每个讨论都伴随着您可以编译和运行的示例代码。 学习它的输出将有助于巩固你刚刚学到的东西。

#### 赋值，算术和一元运算符

##### 简单赋值运算符

您将遇到的最常见的操作符之一是简单赋值运算符“=”。 你在Bicycle类中看到了这个操作符; 它将右边的值赋给左边的操作数：

```java
int cadence = 0;
int speed = 0;
int gear = 1;
```

此操作符也可用于对象以分配对象引用，如创建对象中所述。

##### 算术运算符

Java编程语言为执行加法，减法，乘法和除法的操作符提供了操作。 很有可能你会在基础数学中认识他们。 唯一可能看起来很新的符号是“％”，它将一个操作数除以另一个操作数，并将余数作为结果返回。

| 操作符 | 描述                           |
| :----: | ------------------------------ |
|   +    | 加法运算符（也用于字符串连接） |
|   -    | 减法运算符                     |
|   *    | 乘法运算符                     |
|   /    | 出发运算符                     |
|   %    | 取余运算符                     |

以下程序ArithmeticDemo测试算术运算符。

```java
 public static void main (String[] args) {

        int result = 1 + 2;
        // result is now 3
        System.out.println("1 + 2 = " + result);
        int original_result = result;

        result = result - 1;
        // result is now 2
        System.out.println(original_result + " - 1 = " + result);
        original_result = result;

        result = result * 2;
        // result is now 4
        System.out.println(original_result + " * 2 = " + result);
        original_result = result;

        result = result / 2;
        // result is now 2
        System.out.println(original_result + " / 2 = " + result);
        original_result = result;

        result = result + 8;
        // result is now 10
        System.out.println(original_result + " + 8 = " + result);
        original_result = result;

        result = result % 7;
        // result is now 3
        System.out.println(original_result + " % 7 = " + result);
    }
}
```

该程序打印以下内容：

```java
1 + 2 = 3
3 - 1 = 2
2 * 2 = 4
4 / 2 = 2
2 + 8 = 10
10 % 7 = 3
```

您还可以将算术运算符与简单赋值运算符组合以创建复合赋值。 例如，x + = 1; 和x = x + 1; 都将x的值增加1。

+运算符也可以用于连接（连接）两个字符串，如下面的ConcatDemo程序所示：

```java

class ConcatDemo {
    public static void main(String[] args){
        String firstString = "This is";
        String secondString = " a concatenated string.";
        String thirdString = firstString+secondString;
        System.out.println(thirdString);
    }
}
```

在这个程序结束时，变量thirdString包含“This is a concatenated string.”，它被打印到标准输出。

##### 一元运算符

一元运算符只需要一个操作数; 它们执行各种操作，例如将值递增/递减1，否定表达式或反转布尔值。

| 运算符 | 描述                                           |
| :----: | ---------------------------------------------- |
|   +    | 一元加运算符; 表示正值（但没有这个数字是正数） |
|   -    | 一元减运算符; 否定表达                         |
|   ++   | 自增运算符; 将值增加1                          |
|   --   | 自减运算符; 将值减少1                          |
|   ！   | 逻辑取反运算符                                 |

以下程序UnaryDemo测试一元运算符：

```java
class UnaryDemo {

    public static void main(String[] args) {

        int result = +1;
        // result is now 1
        System.out.println(result);

        result--;
        // result is now 0
        System.out.println(result);

        result++;
        // result is now 1
        System.out.println(result);

        result = -result;
        // result is now -1
        System.out.println(result);

        boolean success = false;
        // false
        System.out.println(success);
        // true
        System.out.println(!success);
    }
}
```

增量/减量运算符可以在操作数之前（前缀）或之后（后缀）应用。 代码result++; 和++result; 两者的结果都会以1递增。 唯一的区别是前缀版本（++result）评估为递增值，而后缀版本（result++）评估为原始值。 如果您只是执行简单的递增/递减操作，则选择哪个版本无关紧要。 但是如果你在更大的表达式中使用这个运算符，那么你选择的运算符可能会有很大的不同。

以下程序PrePostDemo说明了前缀/后缀一元增量运算符：

```java
class PrePostDemo {
    public static void main(String[] args){
        int i = 3;
        i++;
        // prints 4
        System.out.println(i);
        ++i;			   
        // prints 5
        System.out.println(i);
        // prints 6
        System.out.println(++i);
        // prints 6
        System.out.println(i++);
        // prints 7
        System.out.println(i);
    }
}
```

#### 等于，关系和条件运算符

##### 等号和和关系运算符

等号和关系运算符确定一个操作数是否大于，小于，等于或不等于另一个操作数。 大多数这些运算符可能也会看起来很熟悉。 请记住，在测试两个原始值是否相等时，您必须使用“==”，而不是“=”。

| 运算符 | 描述     |
| :----: | -------- |
|   ==   | 等于     |
|   !=   | 不等于   |
|   >    | 大于     |
|   >=   | 大于等于 |
|   <    | 小于     |
|   <=   | 小于等于 |

以下程序ComparisonDemo测试比较运算符：

```java

class ComparisonDemo {

    public static void main(String[] args){
        int value1 = 1;
        int value2 = 2;
        if(value1 == value2)
            System.out.println("value1 == value2");
        if(value1 != value2)
            System.out.println("value1 != value2");
        if(value1 > value2)
            System.out.println("value1 > value2");
        if(value1 < value2)
            System.out.println("value1 < value2");
        if(value1 <= value2)
            System.out.println("value1 <= value2");
    }
}
```

输出：

```java
value1 != value2
value1 <  value2
value1 <= value2
```

##### 条件运算符

&&和|| 运算符对两个布尔表达式执行条件与和操作。 这些运算符表现出“短路”行为，这意味着第二个操作数仅在需要时才被执行。

| 运算符 | 描述   |
| ------ | ------ |
| &&     | 条件与 |
| \|\|   | 条件或 |

以下程序ConditionalDemo1测试这些运算符：

```java
class ConditionalDemo1 {

    public static void main(String[] args){
        int value1 = 1;
        int value2 = 2;
        if((value1 == 1) && (value2 == 2))
            System.out.println("value1 is 1 AND value2 is 2");
        if((value1 == 1) || (value2 == 1))
            System.out.println("value1 is 1 OR value2 is 1");
    }
}
```

另一个条件运算符是？：，它可以被认为是if-then-else语句的简写（在本课的控制流程语句部分讨论过）。 该运算符也称为三元运算符，因为它使用三个操作数。 在下面的示例中，应将此运算符理解为：“如果someCondition为true，则将value1的值分配给result，否则将value2的值分配给result。”

以下程序ConditionalDemo2测试？：运算符：

```java
class ConditionalDemo2 {

    public static void main(String[] args){
        int value1 = 1;
        int value2 = 2;
        int result;
        boolean someCondition = true;
        result = someCondition ? value1 : value2;

        System.out.println(result);
    }
}
```

由于someCondition为真，该程序在屏幕上打印“1”。 如果使代码更具可读性，请使用？：运算符而不是if-then-else语句; 例如，当表达式紧凑且没有副作用（例如分配）时。

##### 类型比较运算符instanceof

instanceof运算符将对象与指定的类型进行比较。 您可以使用它来测试对象是否是类的实例，子类的实例或实现特定接口的类的实例。

下面的程序InstanceofDemo定义了一个父类（名为Parent），一个简单的接口（名为MyInterface）和一个从父类继承并实现该接口的子类（名为Child）。

```java
class InstanceofDemo {
    public static void main(String[] args) {

        Parent obj1 = new Parent();
        Parent obj2 = new Child();

        System.out.println("obj1 instanceof Parent: "
            + (obj1 instanceof Parent));
        System.out.println("obj1 instanceof Child: "
            + (obj1 instanceof Child));
        System.out.println("obj1 instanceof MyInterface: "
            + (obj1 instanceof MyInterface));
        System.out.println("obj2 instanceof Parent: "
            + (obj2 instanceof Parent));
        System.out.println("obj2 instanceof Child: "
            + (obj2 instanceof Child));
        System.out.println("obj2 instanceof MyInterface: "
            + (obj2 instanceof MyInterface));
    }
}

class Parent {}
class Child extends Parent implements MyInterface {}
interface MyInterface {}
```

输出：

```
obj1 instanceof Parent: true
obj1 instanceof Child: false
obj1 instanceof MyInterface: false
obj2 instanceof Parent: true
obj2 instanceof Child: true
obj2 instanceof MyInterface: true
```

在使用instanceof操作符时，请记住，null不是任何事物的实例。

##### 移位运算符

Java编程语言还提供了对整型类型执行按位和位移操作的运算符。 本节讨论的操作符不太常用。 因此，他们的报道很简短; 目的只是让你意识到这些运算符的存在。

一元位运算符“〜”反转位模式; 它可以应用于任何整型，使得每个“0”为“1”，每个“1”为“0”。 例如，一个字节包含8位; 将该运算符应用于位模式为“00000000”的值将其模式更改为“11111111”。（按位取反)

带符号的左移运算符“<<”将位模式向左移位，并且带符号的右移运算符“>>”将位模式向右移位。 位模式由左侧操作数给出，并由右侧操作数移动位置数量。 无符号右移运算符“>>>”将零移动到最左边的位置，而“>>”之后的最左边位置取决于符号扩展。

按位＆运算符执行按位AND运算。

按位^运算符执行按位异或运算。

按位| 运算符执行按位或运算。

以下程序BitDemo使用按位AND运算符将数字“2”打印到标准输出。

```java
class BitDemo {
    public static void main(String[] args) {
        int bitmask = 0x000F;
        int val = 0x2222;
        // prints "2"
        System.out.println(val & bitmask);
    }
}
```



### 表达式，语句和块

现在你已经理解了变量和操作符，现在该学习表达式，语句和块。 运算符可以用于构建计算值的表达式; 表达式是语句的核心组成部分; 语句可以组成块。

#### 表达式

表达式是一个由变量，运算符和方法调用组成的构造，它们是根据语言的语法构建的，其评估为单个值。 您已经看过表达式的例子，如下所示：

```java
int cadence = 0;
anArray[0] = 100;
System.out.println("Element 1 at index 0: " + anArray[0]);

int result = 1 + 2; // result is now 3
if (value1 == value2) 
    System.out.println("value1 == value2");
```

表达式返回的值的数据类型取决于表达式中使用的元素。 表达式cadence = 0返回一个int，因为赋值操作符返回与其左手操作数相同数据类型的值; 在这种情况下，节奏是一个整数。 正如您从其他表达式中看到的，表达式也可以返回其他类型的值，例如布尔值或字符串。

Java编程语言允许您从各种较小的表达式构造复合表达式，只要表达式的一部分所需的数据类型与另一部分的数据类型匹配即可。 下面是一个复合表达式的例子：

```java
1 * 2 * 3
```

在这个特定的例子中，评估表达式的顺序并不重要，因为乘法的结果与顺序无关; 无论按照何种顺序应用乘法，结果总是相同的。 但是，这并非所有表达式都适用。 例如，下面的表达式会给出不同的结果，具体取决于您是先执行加法还是除法操作：

```java
x + y / 100    // ambiguous
```

您可以准确指定如何使用平衡圆括号评估表达式:(和）。 例如，要使前面的表达式明确无误，可以编写以下内容：

```java
(x + y) / 100  // unambiguous, recommended
```

如果您没有明确指出要执行的操作的顺序，则顺序由分配给表达式中使用的操作符的优先级确定。 优先级较高的运算符首先得到评估。 例如，除法运算符的优先级高于加法运算符。 因此，以下两个陈述是等同的：

```java
x + y / 100 


x + (y / 100) // unambiguous, recommended
```

在编写复合表达式时，应明确指出，并用括号表示首先应执行哪些运算符。 这种做法使代码更易于阅读和维护。

#### 语句

语句大致相当于自然语言中的句子。 一条语句构成了一个完整的执行单位。 通过用分号（;）终止表达式，可以将以下类型的表达式变为语句。

- 赋值表达式
- 任何使用++或 - -
- 方法调用
- 对象创建表达式

这些语句被称为表达式语句。 这里有一些表达式语句的例子。

```java
// assignment statement
aValue = 8933.234;
// increment statement
aValue++;
// method invocation statement
System.out.println("Hello World!");
// object creation statement
Bicycle myBike = new Bicycle();
```

除了表达式语句之外，还有两种其他类型的语句：声明语句和控制流语句。 声明语句声明一个变量。 你已经看到很多声明语句的例子：

```java
// declaration statement
double aValue = 8933.234;
```

最后，控制流程语句调节语句执行的顺序。 您将在下一部分“控制流量表”中了解控制流语句

#### 块

块是平衡花括号之间的一组零个或多个语句，可以在允许单个语句的任何位置使用。 以下示例BlockDemo说明了块的用法：

```java
class BlockDemo {
     public static void main(String[] args) {
          boolean condition = true;
          if (condition) { // begin block 1
               System.out.println("Condition is true.");
          } // end block one
          else { // begin block 2
               System.out.println("Condition is false.");
          } // end block 2
     }
}
```



### 控制流语句

源文件中的语句通常按照它们出现的顺序从上到下执行。 但是，控制流程语句通过使用决策制定，循环和分支来分解执行流程，从而使程序有条件地执行特定的代码块。 本节介绍Java支持的决策语句（if-then，if-then-else，switch），循环语句（for，while，do-while）和分支语句（break，continue，return） 编程语言。

#### if-then和if-then-else语句

##### if-then语句

if-then语句是所有控制流程语句中最基本的。 它告诉你的程序只有在特定的测试评估为真时才执行某段代码。 例如，自行车类只有在自行车已经运动时才允许制动器降低自行车的速度。 applyBrakes方法的一种可能的实现方式如下：

```java
void applyBrakes() {
    // the "if" clause: bicycle must be moving
    if (isMoving){ 
        // the "then" clause: decrease current speed
        currentSpeed--;
    }
}
```

如果该测试判断为假（意思是自行车没有运动），则控制跳转到if-then语句的末尾。

另外，“then”子句只包含一个语句，打开和关闭大括号是可选的：

```
void applyBrakes() {
    // same as above, but without braces 
    if (isMoving)
        currentSpeed--;
}
```

决定何时省略大括号是个人品味的问题。 省略它们会使代码变得更脆弱。 如果第二个语句后来被添加到“then”子句中，则常见的错误是忘记添加新需要的大括号。 编译器无法捕捉到这种错误; 你只会得到错误的结果。

##### if-then-else语句

if-then-else语句在“if”子句判断为false时提供执行的辅助路径。 如果在自行车未运动时施加制动，您可以在applyBrakes方法中使用if-then-else语句采取一些行动。 在这种情况下，动作是简单地打印一条错误消息，指出自行车已经停止。

```java
void applyBrakes() {
    if (isMoving) {
        currentSpeed--;
    } else {
        System.err.println("The bicycle has already stopped!");
    } 
}
```

以下程序IfElseDemo根据测试分数的值分配等级：A分数为90％或以上，B分数为80％或以上，等等。

```java
class IfElseDemo {
    public static void main(String[] args) {

        int testscore = 76;
        char grade;

        if (testscore >= 90) {
            grade = 'A';
        } else if (testscore >= 80) {
            grade = 'B';
        } else if (testscore >= 70) {
            grade = 'C';
        } else if (testscore >= 60) {
            grade = 'D';
        } else {
            grade = 'F';
        }
        System.out.println("Grade = " + grade);
    }
}
```

程序的输出是：

```java
Grade = C
```

您可能已经注意到，testscore的值可以满足复合语句中的多个表达式：76> = 70和76> = 60.但是，一旦条件满足，将执行相应的语句（等级='C'; ）并且其余条件不被执行。

#### switch语句

与if-then和if-then-else语句不同，switch语句可以有许多可能的执行路径。 switch语句使用byte，short，char和int基本数据类型。 它也适用于枚举类型（在枚举类型中讨论），String类和几个包装某些基本类型的特殊类：Character，Byte，Short和Integer（在Numbers和Strings中讨论）。

下面的代码示例SwitchDemo声明了一个名为month的int值，其值表示一个月份。 该代码使用switch语句根据月份的值显示月份的名称。

```java
public class SwitchDemo {
    public static void main(String[] args) {

        int month = 8;
        String monthString;
        switch (month) {
            case 1:  monthString = "January";
                     break;
            case 2:  monthString = "February";
                     break;
            case 3:  monthString = "March";
                     break;
            case 4:  monthString = "April";
                     break;
            case 5:  monthString = "May";
                     break;
            case 6:  monthString = "June";
                     break;
            case 7:  monthString = "July";
                     break;
            case 8:  monthString = "August";
                     break;
            case 9:  monthString = "September";
                     break;
            case 10: monthString = "October";
                     break;
            case 11: monthString = "November";
                     break;
            case 12: monthString = "December";
                     break;
            default: monthString = "Invalid month";
                     break;
        }
        System.out.println(monthString);
    }
}
```

在这种情况下，8月将打印到标准输出。

switch语句的主体被称为switch块。 switch块中的语句可以标注一个或多个案例或默认标签。 switch语句评估其表达式，然后执行匹配大小写标签后面的所有语句。

您还可以使用if-then-else语句显示月份的名称：

```java
int month = 8;
if (month == 1) {
    System.out.println("January");
} else if (month == 2) {
    System.out.println("February");
}
...  // and so on
```

决定是否使用if-then-else语句或switch语句基于可读性和语句正在测试的表达式。 if-then-else语句可以基于值或条件的范围来测试表达式，而switch语句仅基于单个整数，枚举值或String对象来测试表达式。

另一个兴趣点是break语句。 每个break语句终止封闭的switch语句。 控制流程继续执行开关块后的第一条语句。 break语句是必需的，因为如果没有它们，switch块中的语句会落空：匹配case标号后面的所有语句按顺序执行，而不管后续case标号的表达式如何，直到遇到break语句为止。 程序SwitchDemoFallThrough在开关块中显示语句。 该程序显示对应于整数月份和下一年的月份：

```java
public class SwitchDemoFallThrough {

    public static void main(String[] args) {
        java.util.ArrayList<String> futureMonths =
            new java.util.ArrayList<String>();

        int month = 8;

        switch (month) {
            case 1:  futureMonths.add("January");
            case 2:  futureMonths.add("February");
            case 3:  futureMonths.add("March");
            case 4:  futureMonths.add("April");
            case 5:  futureMonths.add("May");
            case 6:  futureMonths.add("June");
            case 7:  futureMonths.add("July");
            case 8:  futureMonths.add("August");
            case 9:  futureMonths.add("September");
            case 10: futureMonths.add("October");
            case 11: futureMonths.add("November");
            case 12: futureMonths.add("December");
                     break;
            default: break;
        }

        if (futureMonths.isEmpty()) {
            System.out.println("Invalid month number");
        } else {
            for (String monthName : futureMonths) {
               System.out.println(monthName);
            }
        }
    }
}
```

这是代码的输出：

```java
August
September
October
November
December
```

从技术上讲，最后的break语句不是必需的，因为流程不在switch语句中。 建议使用break语句，以便修改代码更容易，更不容易出错。 缺省部分处理所有未包含在前面case的情况。

以下代码示例SwitchDemo2显示语句如何具有多个案例标签。 代码示例计算特定月份的天数：

```java
class SwitchDemo2 {
    public static void main(String[] args) {

        int month = 2;
        int year = 2000;
        int numDays = 0;

        switch (month) {
            case 1: case 3: case 5:
            case 7: case 8: case 10:
            case 12:
                numDays = 31;
                break;
            case 4: case 6:
            case 9: case 11:
                numDays = 30;
                break;
            case 2:
                if (((year % 4 == 0) && 
                     !(year % 100 == 0))
                     || (year % 400 == 0))
                    numDays = 29;
                else
                    numDays = 28;
                break;
            default:
                System.out.println("Invalid month.");
                break;
        }
        System.out.println("Number of Days = "
                           + numDays);
    }
}
```

这是代码的输出：

```java
Number of Days = 29
```

##### 在switch语句中使用字符串

在Java SE 7和更高版本中，可以在switch语句的表达式中使用String对象。 以下代码示例StringSwitchDemo根据名为month的字符串的值显示月份的编号：

```java

public class StringSwitchDemo {

    public static int getMonthNumber(String month) {

        int monthNumber = 0;

        if (month == null) {
            return monthNumber;
        }

        switch (month.toLowerCase()) {
            case "january":
                monthNumber = 1;
                break;
            case "february":
                monthNumber = 2;
                break;
            case "march":
                monthNumber = 3;
                break;
            case "april":
                monthNumber = 4;
                break;
            case "may":
                monthNumber = 5;
                break;
            case "june":
                monthNumber = 6;
                break;
            case "july":
                monthNumber = 7;
                break;
            case "august":
                monthNumber = 8;
                break;
            case "september":
                monthNumber = 9;
                break;
            case "october":
                monthNumber = 10;
                break;
            case "november":
                monthNumber = 11;
                break;
            case "december":
                monthNumber = 12;
                break;
            default: 
                monthNumber = 0;
                break;
        }

        return monthNumber;
    }

    public static void main(String[] args) {

        String month = "August";

        int returnedMonthNumber =
            StringSwitchDemo.getMonthNumber(month);

        if (returnedMonthNumber == 0) {
            System.out.println("Invalid month");
        } else {
            System.out.println(returnedMonthNumber);
        }
    }
}
```

该代码的输出是8。

switch表达式中的字符串与每个case标签关联的表达式进行比较，就好像正在使用String.equals方法一样。 为了使StringSwitchDemo示例接受任何月份而不考虑大小写，月份将转换为小写（使用toLowerCase方法），并且与案例标签关联的所有字符串均为小写字母。

注意：此示例检查switch语句中的表达式是否为空。 确保任何switch语句中的表达式不为空以防止抛出NullPointerException。

#### while和do-while语句

while语句在特定条件成立时连续执行一组语句。 其语法可以表示为：

```java
while (expression) {
     statement(s)
}
```

while语句评估表达式，它必须返回一个布尔值。 如果表达式的计算结果为true，则while语句将执行while块中的语句。 while语句继续测试表达式并执行其块，直到表达式计算结果为false。 使用while语句打印从1到10的值可以在以下WhileDemo程序中完成：

```java
class WhileDemo {
    public static void main(String[] args){
        int count = 1;
        while (count < 11) {
            System.out.println("Count is: " + count);
            count++;
        }
    }
}
```

您可以使用while语句实现无限循环，如下所示：

```java
while (true){
    // your code goes here
}
```

Java编程语言还提供了do-while语句，可以如下表示：

```java
do {
     statement(s)
} while (expression);
```

do-while和while之间的区别在于do-while在循环底部而不是顶部判断其表达式。 因此，do块中的语句总是至少执行一次，如下面的DoWhileDemo程序所示：

```java
class DoWhileDemo {
    public static void main(String[] args){
        int count = 1;
        do {
            System.out.println("Count is: " + count);
            count++;
        } while (count < 11);
    }
}
```

#### for语句

for语句提供了一种简洁的方式来遍历一系列值。 程序员经常将其称为“for循环”，因为它的重复循环方式直到满足特定的条件。 for语句的一般形式可以表示如下：

```java
for (initialization; termination;
     increment) {
    statement(s)
}
```

在使用for语句的这个版本时，请记住：

- 初始化表达式初始化循环; 它会在循环开始时执行一次。
- 当终止表达式计算结果为false时，循环终止。
- 增量表达式在循环的每次迭代之后被调用; 这个表达式增加或减少一个值是完全可以接受的。

以下程序ForDemo使用for语句的一般形式将数字1到10打印到标准输出：

```java
class ForDemo {
    public static void main(String[] args){
         for(int i=1; i<11; i++){
              System.out.println("Count is: " + i);
         }
    }
}
```

这个程序的输出是：

```java
Count is: 1
Count is: 2
Count is: 3
Count is: 4
Count is: 5
Count is: 6
Count is: 7
Count is: 8
Count is: 9
Count is: 10
```

注意代码如何在初始化表达式中声明一个变量。 该变量的范围从其声明扩展到由for语句控制的块的末尾，因此它也可以用于终止和增量表达式。 如果在循环之外不需要控制for语句的变量，最好在初始化表达式中声明该变量。 名称i，j和k通常用于控制循环; 在初始化表达式中声明它们会限制它们的使用寿命并减少错误。

for循环的三个表达式是可选的; 可以创建一个无限循环如下：

```java
// infinite loop
for ( ; ; ) {
    
    // your code goes here
}
```

for语句还具有另一种用于迭代集合和数组的迭代形式。此表单有时称为增强式for语句，可用于使循环更紧凑且易于阅读。 为了演示，考虑下面的数组，它包含数字1到10：

```java
int[] numbers = {1,2,3,4,5,6,7,8,9,10};
```

以下程序EnhancedForDemo使用增强型for循环访问数组：

```java
class EnhancedForDemo {
    public static void main(String[] args){
         int[] numbers = 
             {1,2,3,4,5,6,7,8,9,10};
         for (int item : numbers) {
             System.out.println("Count is: " + item);
         }
    }
}
```

在这个例子中，变量item保存numbers数组中的当前值。 该程序的输出与以前相同：

```java
Count is: 1
Count is: 2
Count is: 3
Count is: 4
Count is: 5
Count is: 6
Count is: 7
Count is: 8
Count is: 9
Count is: 10
```

我们建议尽可能使用for语句的这种形式，而不是一般形式。

#### 分支语句

##### break语句

break语句有两种形式：带标签和无标签。 您在前面关于switch语句的讨论中看到了无标签的表单。 您还可以使用未标记的中断来终止for，while或do-while循环，如以下BreakDemo程序中所示：

```java
class BreakDemo {
    public static void main(String[] args) {

        int[] arrayOfInts = 
            { 32, 87, 3, 589,
              12, 1076, 2000,
              8, 622, 127 };
        int searchfor = 12;

        int i;
        boolean foundIt = false;

        for (i = 0; i < arrayOfInts.length; i++) {
            if (arrayOfInts[i] == searchfor) {
                foundIt = true;
                break;
            }
        }

        if (foundIt) {
            System.out.println("Found " + searchfor + " at index " + i);
        } else {
            System.out.println(searchfor + " not in the array");
        }
    }
}
```

该程序在数组中搜索数字12。 以粗体显示的break语句在找到该值时终止for循环。 然后控制流程在for循环之后转移到语句。 这个程序的输出是：

```java
Found 12 at index 4
```

未标记的break语句终止最内层的switch，for，while或do-while语句，但带标签的break会终止外部语句。 以下程序BreakWithLabelDemo与前一个程序类似，但使用嵌套for循环搜索二维数组中的值。 当找到该值时，标记的中断会终止循环外部（标记为“搜索”）：

```java
class BreakWithLabelDemo {
    public static void main(String[] args) {

        int[][] arrayOfInts = { 
            { 32, 87, 3, 589 },
            { 12, 1076, 2000, 8 },
            { 622, 127, 77, 955 }
        };
        int searchfor = 12;

        int i;
        int j = 0;
        boolean foundIt = false;

    search:
        for (i = 0; i < arrayOfInts.length; i++) {
            for (j = 0; j < arrayOfInts[i].length;
                 j++) {
                if (arrayOfInts[i][j] == searchfor) {
                    foundIt = true;
                    break search;
                }
            }
        }

        if (foundIt) {
            System.out.println("Found " + searchfor + " at " + i + ", " + j);
        } else {
            System.out.println(searchfor + " not in the array");
        }
    }
}
```

这是该程序的输出:

```java
Found 12 at 1, 0
```

break语句终止带标签的语句; 它不会将控制流转移到标签上。 控制流被转移到紧随标签（已终止）语句之后的语句中。

##### Continue语句

continue语句跳过for，while或do-while循环的当前迭代。 无标签的形式跳到最内层循环体的末尾，并计算控制循环的布尔表达式。 下面的程序，ContinueDemo，遍历字符串，计算字母“p”的出现次数。 如果当前字符不是p，continue语句会跳过循环的其余部分并继续下一个字符。 如果它是“p”，程序会增加字母计数。

```java
class ContinueDemo {
    public static void main(String[] args) {

        String searchMe = "peter piper picked a " + "peck of pickled peppers";
        int max = searchMe.length();
        int numPs = 0;

        for (int i = 0; i < max; i++) {
            // interested only in p's
            if (searchMe.charAt(i) != 'p')
                continue;

            // process p's
            numPs++;
        }
        System.out.println("Found " + numPs + " p's in the string.");
    }
}
```

这是这个程序的输出：

```
Found 9 p's in the string.
```

要更清楚地看到此效果，请尝试删除continue语句并重新编译。 当你再次运行程序时，计数将是错误的，说它发现了35 p而不是9。

带标签的continue语句跳过用给定标签标记的外部循环的当前迭代。 以下示例程序ContinueWithLabelDemo使用嵌套循环搜索另一个字符串中的子字符串。 需要两个嵌套循环：一个迭代子字符串，一个迭代要搜索的字符串。 以下程序ContinueWithLabelDemo使用继续的标记形式跳过外循环中的迭代。

```java
class ContinueWithLabelDemo {
    public static void main(String[] args) {

        String searchMe = "Look for a substring in me";
        String substring = "sub";
        boolean foundIt = false;

        int max = searchMe.length() - 
                  substring.length();

    test:
        for (int i = 0; i <= max; i++) {
            int n = substring.length();
            int j = i;
            int k = 0;
            while (n-- != 0) {
                if (searchMe.charAt(j++) != substring.charAt(k++)) {
                    continue test;
                }
            }
            foundIt = true;
                break test;
        }
        System.out.println(foundIt ? "Found it" : "Didn't find it");
    }
}
```

这是这个程序的输出。

`Found it`

##### return 语句

最后一个分支语句是return语句。 return语句从当前方法退出，并且控制流返回到调用方法的位置。 return语句有两种形式：一种返回值，另一种不返回。 要返回值，只需在return关键字后面放置值（或计算值的表达式）即可。

`return ++count;`

返回值的数据类型必须与方法声明的返回值的类型匹配。 当一个方法被声明为void时，使用不返回值的return形式。

`return;`

类和对象课程将涵盖您需要了解的关于编写方法的一切。

### 控制流语句的总结

if-then语句是所有控制流程语句中最基本的。 它告诉你的程序只有在特定的测试判断为真时才执行某段代码。 if-then-else语句在“if”子句评估为false时提供执行的辅助路径。 与if-then和if-then-else不同，switch语句允许任意数量的可能执行路径。 while和do-while语句在特定条件成立时持续执行一组语句。 do-while和while之间的区别在于do-while在循环底部而不是顶部判断其表达式。 因此，do块中的语句总是至少执行一次。 for语句提供了一种简洁的方式来遍历一系列值。 它有两种形式，其中一种是为循环容器和数组而设计的。

### 问题和练习：控制流语句

Questions

1. Java编程语言支持的最基本的控制流语句是___语句。
2.  ___语句允许任意数量的可能执行路径。
3. ___语句与while语句类似，但在循环的___处评估它的表达式。
4. 你如何使用for语句编写一个无限循环？
5.  如何使用while语句编写无限循环？

## 类和对象

利用您现在掌握的Java编程语言基础知识，您可以学习编写自己的类。 在本课中，您将找到有关定义自己的类的信息，包括声明成员变量，方法和构造函数。

您将学习如何使用您的类创建对象，以及如何使用您创建的对象。

本课还介绍其他类中的嵌套类和枚举

### 类

本节将向您展示一个类的解剖结构，以及如何声明字段，方法和构造函数。

在题为“面向对象编程概念”的课程中，面向对象概念的介绍以自行车课为例，以自行车，山地自行车和串联自行车作为子类。 以下是可能实现Bicycle类的示例代码，为您提供类声明的概述。 本课的后续部分将逐步备份并解释类声明。 目前，不要关注细节。

```java
public class Bicycle {
        
    // the Bicycle class has
    // three fields
    public int cadence;
    public int gear;
    public int speed;
        
    // the Bicycle class has
    // one constructor
    public Bicycle(int startCadence, int startSpeed, int startGear) {
        gear = startGear;
        cadence = startCadence;
        speed = startSpeed;
    }
        
    // the Bicycle class has
    // four methods
    public void setCadence(int newValue) {
        cadence = newValue;
    }
        
    public void setGear(int newValue) {
        gear = newValue;
    }
        
    public void applyBrake(int decrement) {
        speed -= decrement;
    }
        
    public void speedUp(int increment) {
        speed += increment;
    }
        
}
```

作为Bicycle的子类的MountainBike类的类声明可能如下所示：

```java
public class MountainBike extends Bicycle {
        
    // the MountainBike subclass has
    // one field
    public int seatHeight;

    // the MountainBike subclass has
    // one constructor
    public MountainBike(int startHeight, int startCadence,
                        int startSpeed, int startGear) {
        super(startCadence, startSpeed, startGear);
        seatHeight = startHeight;
    }   
        
    // the MountainBike subclass has
    // one method
    public void setHeight(int newValue) {
        seatHeight = newValue;
    }   

}
```

MountainBike继承了Bicycle的所有领域和方法，并添加了现场座椅高度和设置方法（山地自行车的座椅可根据地形要求上下移动）。

#### 声明类

你已经看到以下列方式定义的类：

```java
class MyClass {
    // field, constructor, and 
    // method declarations
}
```

这是一个类声明。 类体（大括号之间的区域）包含所有为从类创建的对象提供生命周期的代码：用于初始化新对象的构造函数，用于提供类及其对象状态的字段的声明以及 方法来实现类和它的对象的行为。

前面的类声明是最小的一个。 它仅包含需要的类声明的组件。 您可以在类声明的开始处提供有关该类的更多信息，例如其超类的名称，是否实现任何接口等等。 例如，

```java
class MyClass extends MySuperClass implements YourInterface {
    // field, constructor, and
    // method declarations
}
```

意味着MyClass是MySuperClass的子类，它实现了YourInterface接口。

您也可以在开始时添加公共或私有等修饰符 - 因此您可以看到类声明的开始行可能变得非常复杂。 确定其他类可以访问MyClass的公共和私有修饰符将在本课稍后部分讨论。 关于接口和继承的教训将解释如何以及为什么要在类声明中使用extends和implements关键字。 目前，您不必担心这些额外的复杂问题。

通常，类声明可以包含这些组件，依次为：

1. 例如public, private, 以及以后会遇到的其他的修饰符。
2. 类名首字母大写。
3. 该类的父类（超类）的名称（如果有）以关键字extends开头。 一个类（子类）只能继承一个父类。
4. 由类实现的以逗号分隔的接口列表（如果有）由关键字implements实现。 一个类可以实现多个接口。
5. 类的身体包含在大括号{}内。

#### 声明成员变量

有几种变量：

- 类中的成员变量 - 这些称为字段。
- 方法或代码块中的变量 - 这些变量称为局部变量。
- 方法声明中的变量 - 这些称为参数。

Bicycle类使用以下代码行来定义其字段：

```java
public int cadence;
public int gear;
public int speed;
```

字段声明由三部分组成，依次为：

1. 零个或多个修饰符，如public或private。
2. 该字段的类型。
3. 该字段的名称。

Bicycle的字段被命名为节奏，齿轮和速度，并且都是数据类型integer（int）。 public关键字将这些字段标识为公共成员，任何可以访问该类的对象都可以访问它们。

##### 访问修饰符

第一个（最左侧）修饰符用于控制其他类可以访问成员字段的其他类。 目前，只考虑public和private。 其他访问修饰符将在稍后讨论。

- public修饰符 - 该字段可从所有类访问。
- private修饰符 - 该字段只能在其自己的类中访问。

本着封装的精神，将字段私有化是很常见的。 这意味着他们只能从Bicycle类直接访问。 但是，我们仍然需要访问这些值。 这可以通过添加获取我们字段值的公共方法间接完成：

```java
public class Bicycle {
        
    private int cadence;
    private int gear;
    private int speed;
        
    public Bicycle(int startCadence, int startSpeed, int startGear) {
        gear = startGear;
        cadence = startCadence;
        speed = startSpeed;
    }
        
    public int getCadence() {
        return cadence;
    }
        
    public void setCadence(int newValue) {
        cadence = newValue;
    }
        
    public int getGear() {
        return gear;
    }
        
    public void setGear(int newValue) {
        gear = newValue;
    }
        
    public int getSpeed() {
        return speed;
    }
        
    public void applyBrake(int decrement) {
        speed -= decrement;
    }
        
    public void speedUp(int increment) {
        speed += increment;
    }
}
```

##### 变量类型

所有变量都必须有一个类型。 您可以使用基本类型，如int，float，boolean等。或者，您可以使用引用类型，例如字符串，数组或对象。

##### 变量名称

所有变量，无论它们是字段，局部变量还是参数，都遵循语言基础课程“变量命名”中涵盖的相同命名规则和约定。

在本课中，请注意，相同的命名规则和约定用于方法和类名称，除此之外

- 类名的第一个字母应该大写
- 方法名中的第一个（或唯一）单词应该是一个动词。

#### 定义方法

这是一个典型的方法声明的例子：

```java
public double calculateAnswer(double wingSpan, int numberOfEngines,
                              double length, double grossTons) {
    //do the calculation here
}
```

方法声明中唯一需要的元素是方法的返回类型，方法名称，一对括号（），以及大括号之间的主体{}。

更一般地说，方法声明有六个组件，依次为：

1. 修饰符 - 例如public，private以及稍后您将学习的其他修饰符。
2. 返回类型 - 方法返回值的数据类型，如果方法没有返回值，则返回void。
3. 方法名称 - 字段名称的规则也适用于方法名称，但约定有点不同。
4. 圆括号中的参数列表 - 逗号分隔的输入参数列表，前面带有括号括起来的数据类型（）。 如果没有参数，则必须使用空括号。
5. 一个exception异常列表 - 稍后讨论。
6. 方法体，包含在大括号之间 - 方法的代码，包括局部变量的声明，都放在这里。

修饰符，返回类型和参数将在本课稍后部分讨论。 异常情况在后面的课程中讨论。

定义：方法声明的两个组件构成方法签名 - 方法名称和参数类型。

上面声明的方法的签名是：

`calculateAnswer(double, int, double, double)`

##### 命名方法

虽然方法名称可以是任何合法的标识符，但代码约定会限制方法名称。 按照惯例，方法名应该是小写的动词，或者是以小写的动词开头的多个词，后面跟着形容词，名词等。在多词的名称中，第二个和后面的每个词的第一个字母 应该大写。 这里有些例子：

```
run
runFast
getBackground
getFinalData
compareTo
setX
isEmpty
```

通常，方法在其类中具有唯一的名称。 但是，由于方法重载，方法可能与其他方法具有相同的名称。

##### 方法重载

Java编程语言支持重载方法，Java可以区分具有不同方法签名的方法。 这意味着如果一个类中的方法具有不同的参数列表，那么类中的方法可以具有相同的名称（这有一些限制，将在标题为“接口和继承”的课程中讨论）。

假设您有一个可以使用书法绘制各种类型的数据（字符串，整数等）并且包含绘制每种数据类型方法的类。 对每种方法使用新名称很麻烦 - 例如，drawString，drawInteger，drawFloat等等。 在Java编程语言中，可以对所有绘图方法使用相同的名称，但将不同的参数列表传递给每个方法。 因此，数据绘图类可能会声明四个名为draw的方法，每个方法都有不同的参数列表。

```java
    ...
    public void draw(String s) {
        ...
    }
    public void draw(int i) {
        ...
    }
    public void draw(double f) {
        ...
    }
    public void draw(int i, double f) {
        ...
    }
}
```

重载的方法通过传递给方法的参数的数量和类型来区分。 在代码示例中，draw（String s）和draw（int i）是不同且唯一的方法，因为它们需要不同的参数类型。

您不能声明多个具有相同名称和相同数量和类型参数的方法，因为编译器无法区分它们。

编译器在区分方法时不考虑返回类型，所以即使它们具有不同的返回类型，也不能声明具有相同签名的两个方法。

注意：应该谨慎使用重载方法，因为它们会使代码更不易读。

#### 为您的类提供构造函数

一个类包含调用来从类蓝图创建对象的构造函数。 构造函数声明看起来像方法声明 - 除了它们使用类的名称并且没有返回类型。 例如，Bicycle有一个构造函数：

```java
public Bicycle(int startCadence, int startSpeed, int startGear) {
    gear = startGear;
    cadence = startCadence;
    speed = startSpeed;
}
```

要创建一个名为myBike的新自行车对象，新运算符将调用构造函数：

```java
Bicycle myBike = new Bicycle(30, 0, 8);
```

`new Bicycle(30, 0, 8)`在内存中为对象创建空间并初始化其字段。

虽然Bicycle只有一个构造函数，但它可以包含其他构造函数，包括无参数的构造函数：

```java
public Bicycle() {
    gear = 1;
    cadence = 10;
    speed = 0;
}
```

`Bicycle yourBike = new Bicycle();`调用无参构造函数来创建一个名为yourBike的新的Bicycle对象。

这两个构造函数都可以在Bicycle中声明，因为它们有不同的参数列表。 与方法一样，Java平台根据列表中参数的数量及其类型区分构造函数。 你不能为同一个类编写两个具有相同编号和类型参数的构造函数，因为平台无法区分它们。 这样做会导致编译时错误。

你不必为你的类提供任何构造函数，但是在做这件事时你必须小心。 编译器自动为任何没有构造函数的类提供一个无参数的默认构造函数。 这个默认构造函数将调用超类的无参构造函数。 在这种情况下，如果超类没有无参数构造函数，编译器会发出提示，因此您必须验证它是否存在。 如果你的类没有显式超类，那么它有一个隐式超类Object，它有一个无参数构造函数。

你可以自己使用一个超类的构造函数。 本课开头的MountainBike课程就是这样做的。 这将在稍后的接口和继承课程中讨论。

您可以在构造函数的声明中使用访问修饰符来控制哪些其他类可以调用构造函数。

注意：如果另一个类不能调用MyClass构造函数，它不能直接创建MyClass对象。

#### 将信息传递给方法或构造函数

方法或构造函数的声明声明了该方法或构造函数的参数的数量和类型。 例如，以下是根据贷款金额，利率，贷款期限（期数）和贷款的未来价值计算住房贷款的每月支付的方法：

```java
public double computePayment(
                  double loanAmt,
                  double rate,
                  double futureValue,
                  int numPeriods) {
    double interest = rate / 100.0;
    double partial1 = Math.pow((1 + interest), 
                    - numPeriods);
    double denominator = (1 - partial1) / interest;
    double answer = (-loanAmt / denominator)
                    - ((futureValue * partial1) / denominator);
    return answer;
}
```

该方法有四个参数：贷款金额，利率，期货价值和期数。 前三个是双精度浮点数，第四个是整数。 这些参数在方法主体中使用，并且在运行时将采用传入的参数的值。

注意：参数指的是方法声明中的变量列表。 参数是调用方法时传入的实际值。 当你调用一个方法时，使用的参数必须与类型和顺序中的声明参数相匹配。

##### 参数类型

您可以将任何数据类型用于方法或构造函数的参数。 这包括原型数据类型，如您在computePayment方法中看到的双精度，浮点数和整数，以及引用数据类型，例如对象和数组。您可以将任何数据类型用于方法或构造函数的参数。 这包括原型数据类型，如您在computePayment方法中看到的双精度，浮点数和整数，以及引用数据类型，例如对象和数组。

下面是一个接受数组作为参数的方法的示例。 在这个例子中，该方法创建一个新的Polygon对象，并从一个Point对象数组中初始化它（假设Point是一个表示x，y坐标的类）：

```java
public Polygon polygonFrom(Point[] corners) {
    // method body goes here
}
```

注意：如果要将方法传递给方法，请使用lambda表达式或方法引用。

##### 任意数量的参数

您可以使用称为varargs的构造将任意数量的值传递给方法。 当您不知道将有多少特定类型的参数传递给该方法时，您可以使用可变参数。 这是手动创建数组的快捷方式（以前的方法可能使用了可变参数而不是数组）。

要使用可变参数，可以通过省略号（三个点，...），空间和参数名称跟随最后一个参数的类型。 然后可以用该参数的任意数量调用该方法，包括无。

```java
public Polygon polygonFrom(Point... corners) {
    int numberOfSides = corners.length;
    double squareOfSide1, lengthOfSide1;
    squareOfSide1 = (corners[1].x - corners[0].x)
                     * (corners[1].x - corners[0].x) 
                     + (corners[1].y - corners[0].y)
                     * (corners[1].y - corners[0].y);
    lengthOfSide1 = Math.sqrt(squareOfSide1);

    // more method body code follows that creates and returns a 
    // polygon connecting the Points
}
```

您可以看到，在该方法内部，拐角被视为一个数组。 该方法可以通过一个数组或一系列参数来调用。 在任何一种情况下，方法体中的代码都会将参数视为数组。

你会最常见的输出方法的可变参数; 例如，这种printf方法：

`public PrintStream printf(String format, Object... args)`

允许您打印任意数量的对象。 它可以这样调用：

```java
System.out.printf("%s: %d, %s%n", name, idnum, address);
```

或者像这样

```java
System.out.printf("%s: %d, %s, %s, %s%n", name, idnum, address, phone, email);
```

或者具有不同数量的参数。

##### 参数名称

向方法或构造函数声明参数时，请为该参数提供一个名称。 该名称在方法体内用于引用传入的参数。

参数的名称在其范围内必须是唯一的。 它不能与同一方法或构造函数的另一个参数的名称相同，也不能是方法或构造函数内的局部变量的名称。

一个参数可以和一个类的字段名称相同。 如果是这种情况，则说该参数影响该字段。 阴影字段可能会使您的代码难以阅读，并且通常仅用于设置特定字段的构造函数和方法中。 例如，考虑下面的Circle类和它的setOrigin方法：

```java
public class Circle {
    private int x, y, radius;
    public void setOrigin(int x, int y) {
        ...
    }
}
```

Circle类有三个字段：x，y和radius。 setOrigin方法有两个参数，每个参数都与其中一个字段具有相同的名称。 每个方法参数都会隐藏共享其名称的字段。 因此，在方法体内使用简单名称x或y是指参数，而不是字段。 要访问该字段，您必须使用合格的名称。 这将在本课后面的“使用此关键字”部分中进行讨论。

##### 传递基本数据类型参数

基本参数（如int或double）通过值传递给方法。 这意味着对参数值的任何更改仅存在于该方法的范围内。 当该方法返回时，参数将消失，对其进行的任何更改都将丢失。 这里是一个例子：

```java
public class PassPrimitiveByValue {

    public static void main(String[] args) {
           
        int x = 3;
           
        // invoke passMethod() with 
        // x as argument
        passMethod(x);
           
        // print x to see if its 
        // value has changed
        System.out.println("After invoking passMethod, x = " + x);
           
    }
        
    // change parameter in passMethod()
    public static void passMethod(int p) {
        p = 10;
    }
}
```

当你运行这个程序时，输出是：

```java
After invoking passMethod, x = 3
```

##### 传递引用数据类型参数

引用数据类型参数（如对象）也按值传递给方法。 这意味着当方法返回时，传入的引用仍然引用与之前相同的对象。 但是，如果对象的字段的值具有适当的访问级别，则可以在该方法中更改该值的值。

例如，考虑移动Circle对象的任意类中的方法：

```java
public void moveCircle(Circle circle, int deltaX, int deltaY) {
    // code to move origin of circle to x+deltaX, y+deltaY
    circle.setX(circle.getX() + deltaX);
    circle.setY(circle.getY() + deltaY);
        
    // code to assign a new reference to circle
    circle = new Circle(0, 0);
}
```

用这些参数调用该方法：

`moveCircle(myCircle, 23, 56)`

在该方法内部，Circle最初指的是myCircle。 该方法分别将圆形引用（即myCircle）的对象的x和y坐标分别改为23和56。 方法返回时，这些更改将持续。 然后，将circle分配给x = y = 0的新Circle对象的引用。但是，此重新分配没有永久性，因为引用是按值传递的，并且不能更改。 在该方法中，circle所指向的对象已经发生了变化，但是当方法返回时，myCircle仍然会像调用方法之前一样引用同一个Circle对象。



### 对象

本节介绍创建和使用对象。 您将学习如何实例化对象，并且在实例化后如何使用点运算符来访问对象的实例变量和方法。

### 更多关于类

本节涵盖依赖于使用对象引用的类的更多方面以及您在上一节中学到的点运算符：从方法，this关键字，类与实例成员以及访问控制返回值。

### 嵌套类

包括静态嵌套类，内部类，匿名内部类，本地类和lambda表达式。 还有关于何时使用哪种方法的讨论。

### 枚举类型

本节讨论枚举，这些专用类允许您定义和使用常量集。

## 注释

## 接口和继承

## 数组和字符串

## 泛型

## 包

# 基本的Java类

关于异常，基本输入输出，并发，正则表达式和平台环境的课程。

# 集合

关于使用和扩展Java集合框架的课程。

# 日期时间API

如何使用java.time页面写入日期和时间代码。

# 部署

如何使用JAR文件打包应用程序和applet，并使用Java Web Start和Java插件进行部署。

## 

