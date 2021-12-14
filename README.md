# 《On Java 8》中文版

## 书籍简介

* 本书原作者为 [美] Bruce Eckel，即《Java 编程思想》的作者。
* 本书是事实上的 《Java 编程思想》第五版。
* 《Java 编程思想》第四版基于 JAVA **5** 版本；《On Java 8》 基于 JAVA **8** 版本。

- [x] [前言](docs/book/00-Preface.md)
- [x] [简介](docs/book/00-Introduction.md)
- [x] [第一章 对象的概念](docs/book/01-What-is-an-Object.md)
- [x] [第二章 安装Java和本书用例](docs/book/02-Installing-Java-and-the-Book-Examples.md)
- [x] [第三章 万物皆对象](docs/book/03-Objects-Everywhere.md)
- [x] [第四章 运算符](docs/book/04-Operators.md)
- [x] [第五章 控制流](docs/book/05-Control-Flow.md)
- [x] [第六章 初始化和清理](docs/book/06-Housekeeping.md) 
- [x] [第七章 封装](docs/book/07-Implementation-Hiding.md) 
- [x] [第八章 复用](docs/book/08-Reuse.md)
- [x] [第九章 多态](docs/book/09-Polymorphism.md)
- [x] [第十章 接口](docs/book/10-Interfaces.md)
- [x] [第十一章 内部类](docs/book/11-Inner-Classes.md)
- [x] [第十二章 集合](docs/book/12-Collections.md)
- [x] [第十三章 函数式编程](docs/book/13-Functional-Programming.md)
- [x] [第十四章 流式编程](docs/book/14-Streams.md) 
- [x] [第十五章 异常](docs/book/15-Exceptions.md)
- [x] [第十六章 代码校验](docs/book/16-Validating-Your-Code.md)
- [x] [第十七章 文件](docs/book/17-Files.md)
- [x] [第十八章 字符串](docs/book/18-Strings.md)
- [x] [第十九章 类型信息](docs/book/19-Type-Information.md) 
- [x] [第二十章 泛型](docs/book/20-Generics.md)
- [x] [第二十一章 数组](docs/book/21-Arrays.md)
- [x] [第二十二章 枚举](docs/book/22-Enumerations.md)
- [x] [第二十三章 注解](docs/book/23-Annotations.md)
- [x] [第二十四章 并发编程](docs/book/24-Concurrent-Programming.md)
- [ ] [第二十五章 设计模式](docs/book/25-Patterns.md)
- [x] [附录:补充](docs/book/Appendix-Supplements.md)
- [x] [附录:编程指南](docs/book/Appendix-Programming-Guidelines.md)
- [x] [附录:文档注释](docs/book/Appendix-Javadoc.md)
- [ ] [附录:对象传递和返回](docs/book/Appendix-Passing-and-Returning-Objects.md)
- [x] [附录:流式IO](docs/book/Appendix-IO-Streams.md)
- [x] [附录:标准IO](docs/book/Appendix-Standard-IO.md)
- [x] [附录:新IO](docs/book/Appendix-New-IO.md)
- [x] [附录:理解equals和hashCode方法](docs/book/Appendix-Understanding-equals-and-hashCode.md)
- [x] [附录:集合主题](docs/book/Appendix-Collection-Topics.md)  
- [x] [附录:并发底层原理](docs/book/Appendix-Low-Level-Concurrency.md)
- [x] [附录:数据压缩](docs/book/Appendix-Data-Compression.md)
- [x] [附录:对象序列化](docs/book/Appendix-Object-Serialization.md)
- [ ] [附录:静态语言类型检查](docs/book/Appendix-Benefits-and-Costs-of-Static-Type-Checking.md)
- [x] [附录:C++和Java的优良传统](docs/book/Appendix-The-Positive-Legacy-of-C-plus-plus-and-Java.md)
- [ ] [附录:成为一名程序员](docs/book/Appendix-Becoming-a-Programmer.md)

## INSTALL

1. 首先安装[Jupyter Lab](https://jupyter.org/)
2. 安装[Java Kernel](https://github.com/SpencerPark/IJava)

注意： 打开文件后，在工具栏最右边选择`Java`。 Mac下按`CMD + Enter`可以运行Code。

       Java SDK需要1.9及以上。可以用[sdkman](sdkman.io)安装.

3. 代码运行。
   ```java
   public class Hello {
     public static void main(String [] args){
        System.out.println("Hello, world!")
     }

   }

   //调用静态方法main
   Hello.main(new String [0]);
   

  ```


## 一起交流

交流群：721698221 <a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=4cb8bdc26879e544a0e1c2027305afef699029d5c0f314099a239b7c4f309c5f"><img border="0" src="https://raw.githubusercontent.com/LingCoder/OnJava8/master/docs/images/qqgroup.png" alt="OnJava8翻译交流" title="OnJava8翻译交流"></a>( 点击图标即可加入 )<br> 加群时请简单备注下来源或说明

<div align="left">
<img src="https://raw.githubusercontent.com/LingCoder/OnJava8/master/assets/QQGroupQRCode.png"  alt="QQGroupQRCode"/>
 </div>


## 大事记

- 2018-11-20  初始化项目


## 原书资料

<div align="left">
<img src="https://raw.githubusercontent.com/LingCoder/OnJava8/master/cover_small.jpg"  alt="cover_small"/>
 </div>

* 作者: Bruce Eckel 
* ISBN: 9780981872520
* 页数：2038
* 发行：仅电子版


## 示例代码

* [gradle: OnJava8-Examples](https://github.com/BruceEckel/OnJava8-Examples)
* [maven: OnJava8-Examples-Maven](https://github.com/sjsdfg/OnJava8-Examples-Maven



