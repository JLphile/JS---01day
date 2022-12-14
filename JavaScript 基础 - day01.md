# 一. JavaScript 基础 - 第一天

> 了解变量 数据类型 运算符等基础概念，能够实现数据类型的转换，结合四则运算体会如何编程。

- 体会现实世界中的事务与计算机的关系
- 理解什么是数据并知道数据的分类
- 理解变量存储数据的“容器”
- 掌握常见运算符的使用，了解优先级关系
- 知道JavaScript 数据类型隐式转换的特征

## 1. 介绍

> 掌握Javascript 的引入方式，初步认识JavaScript 的作用

###	1.1. 引入方式

JavaScript 程序不能独立运行，它需要被嵌入HTML中，然后浏览器才能执行JavaScript代码。通过script标签将JavaScript 代码引入到HTML中，有两种方式：

####		1.1.1.内部方式

- 直接写在html文件里，用script标签包住

- 规范：script标签写在</body>上面，也就是<body></body>区域的最下方

- 拓展：alert(‘你好，js’) 页面弹出警告对话框

  - ```html
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Document</title>
      </head>
      <body>
        <!-- 内部js -->
        <script>
          alert('你好,js~')
        </script>
        js~
      </body>
    </html>
    ```

  

#### 		1.1.2.外部方式

- 代码写在以.js结尾的文件里

- 通过script标签，引入到html页面中。

  - ```html
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Document</title>
      </head>
      <body>
        <script src="./js/my.js">
          // 中间不要写内容
        </script>
      </body>
    </html>
    ```

  #### 1.1.3. 内联样式

  - ```html
    <body>
        <button onclick="alert('逗你玩~~~')">点击按钮</button>
    </body>
    ```

    

### 1.2.注释和结束符

#### 1.2.1.单行注释

- 符号：//
- 作用：//右边者一行的代码会被忽略
- 快捷键：ctr + /

#### 1.2.2.块注释

- 符号：/* */
- 作用：在/* 和 */之间的内容都会被注释
- 快捷键：shift +alt +A

### 1.3结束符

- *语句最后的结束符 ; 可以不写*

### 1.4.输入和输出

#### 1.4.1.输出

- 语法1

  - ```html
    document.write('<h1>我是标题</h1>')
    ```

- 语法2

  - ```html
    alert(‘弹出的警示内容’)
    ```

- 语法3

  - ```html
    console.log('控制台打印')
    ```

    

#### 1.4.2.输入

- ```html
   prompt('请输入你的姓名')
  ```

  

### 2.变量

#### 2.1.声明

#### 2.2.赋值

#### 2.3.关键字

#### 2.4.变量名称命名规则

- 不能时关键字和保留字，例如：var for while const
- 由字母、数字 下划线 符号组成，不能以数字开头 let num1$_ = 12

### 3.常量

### 4.数据类型

#### 4.1.数值类型

#### 4.2.字符串类型

#### 4.3.布尔类型

#### 4.4.undefined

### 5.类型转换

#### 5.1.隐式转换

#### 5.2.显示转换

##### 5.2.1.Number4



### 6.软件

diagram designer



### 7.练习题

#### 1. 下列定义的变量名中，不合法的是 (A)

- **A： 2age**
- B： newClass
- C： userName
- D： _age

#### 2.下列有关字符串变量定义正确的是(AB) 【多选题】

- A： let strMsg = "我爱北京天安门"
- B： let strMsg2 = '我爱吃猪蹄'
- C： let strMsg3 = 我爱大肘子
- D： let strMsg4 = '我是'高帅富'程序猿'

#### 3. 下面那些是字面量？(ABCD) 可以多选 【多选题】

- A: 123
- B: '大肘子'
- C: ture
- D: []

#### 4. JavaScript由以下哪几部分组成 ( BCD) 多选 【多选题】

- A: JScript
- B: ECMAScript
- C: DOM
- D: BOM
- E: Object

#### 5.下面不属于JavaScript数据类型的是？ ( D)

- A、number
- B、string
- C、boolean
- D、int
- E、undefined

#### 6.在js代码中，'123'+ 4 的运行结果是（B）

- A:127
- B:'1234' 字符串型
- C:1234 数字型
- D:'123'4

#### 7.请选出下面正确的答案？(B)

- A: console.log(typeof '1') // 返回结果是 number
- B: console.log(typeof '1' + 1) // 返回结果是 string1
- C: console.log( '1'- 1) // 返回结果是 11
- D: console.log('pink' + 1) // 返回结果是 string

#### 8.下列有关javascript变量命名说法错误的是(C)

- A:变量名不能是关键字比如 let 、var、if 等
- B: 变量名是区分大小写的
- C:变量名可以由数字、字母、下划线、$组成，可以以数字开头
- D:变量名建议使用驼峰命名法

#### 9.请问 console.log(typeof +'136') 输出的结果是？(B)

- A： 136
- B： number
- C： NaN
- D： string

#### 10.请问 console.log(NaN + 1) 输出的结果是？(C)

- A: 1
- B： 报错
- C： NaN
- D： undefined

#### 11.今日单词1： 请问页面文档输出的语句是？(C)

- A:prompt()
- B:alert()
- C: document.write()
- D:console.log()

#### 12.今日单词2： 请问控制台打印输出的语句是？(D)

- A:prompt()
- B:alert()
- C:document.write()
- D:console.log()

#### 13.今日单词3： 请问页面弹出警示框语句是？(B)

- A:prompt()
- B: alert()
- C: document.write()
- D:console.log()

#### 14.今日单词4： 请问页面弹出输入框语句是？(A)

- A: prompt()
- B: alert()
- C: document.write()
- D: console.log()

#### 15.今日单词5： 请问数据类型转换中，转换为数字型的语句是？(A)

- A:Number()
- B:number()
- C:String()
- D:Boolean()

#### 16.今日单词6： 请问检测数据类型的语句是？(C)

- A:type
- B:Number()
- C:typeof
- D: script

#### 17.今日单词7： 请问定义常量的关键字是？(C)

- A: let
- B: var
- C:const
- D: function

#### 18.今日单词8： 请问不能转换为数字型的是？(D)

- A: Number()

- B: parseInt()

- C: parseFloat()

- D: Boolean()

- E: +

  

###  8.编程题

- 8.1 获取用户信息
  - 依次询问并获取用户的姓名 年龄 性别 收集数据之后在控制台依次打印出来

- 8.2 增加年龄
  - 询问用户年龄，用户输入年龄后，把用户输入的年龄加5岁
  - 增加5岁后，通过弹出框提示用户“据我估计，五年后，你可能XX岁了”
- 8.3计算银行卡余额案例
  - 用户输入总的银行卡余额，依次输入本月花费的电费，水费，网费
  - 页面打印一个表格，计算出本月银行卡还剩下的余额

