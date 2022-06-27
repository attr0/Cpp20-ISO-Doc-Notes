# 3 Terms and definitions

1. 为了本文档的用途，在ISO/IEC 2382中的术语和定义，在ISO 80000-2:2009中术语，定义和符号，和下文的内容，均适用：
2. ISO 和 IEC 维护了一个用于标准化文档的术语数据库
    - (2.1) ISO Online browsing platform: available at https://www.iso.org/obp
    - (2.2) IEC Electropedia: available at http://www.electropedia.org/

3. 本文中的”局部“术语会在使用处定义，并且在定义时用斜体标注



## 3.1 access

《execution-time action，执行期动作》读取或修改某个物体的值

[Note, 仅标量类型(scalar type)可以被access。标量的读取在7.3.2节描述，其修改在7.6.19, 7.6.1.6, 7.6.2.3中标识。 尝试读取或修改某个类型的对象一般会触发一个构造函数（11.4.5）或赋值运算（11.4.6）；尽管这样的触发包含对子对象（subobject）的访问，这样的动作并不构成访问]



## 3.2 arbitrary-positional stream

《Library，库》流（stream）可以seek到其长度内，任意整形位置（integral position）

[Note, 每一个arbitrary-positional stream同时也是一个repositional stream（3.42）]



## 3.3 argument

《function call expression，函数调用表达式》被圆括号围住的，用逗号分隔的表达式



## 3.4 argument

《function-like macro，类函数宏》被圆括号围住的，用逗号分隔的，一系列预处理标记



## 3.5 argument

《throw expression，抛异常》throw运算的运算数（operand）



## 3.6 argument

《template instantiation，模板实例化》被尖括号围住的，用逗号分隔的，常量表达式（constant-expression），type-id，或者id-expression，



## 3.7 block

《execution，执行》等待某些条件满足后，进而可以执行剩余代码（而不是执行步骤的实现）



## 3.8 block

《statement，语句》复合语句



## 3.9 character

《library，库》当被连续处理时，可以代表文档（text）的对象

[Note，该术语不仅指代`char`, `char8_t`, `char16_t`, `char32_t`和`wchar_t` 对象（6.8.2），同时指代任何能够满足章21，章28，章29，章30中定义要求的类的值]



## 3.10 character container type

《library，库》用于描述一个character的类或一个类型

[Note，此术语仅用于string，iostream，和正则表达式类型的模板]



## 3.11 component

《library，库》库实体(library entities)直接关联的的成员，参数和返回值的组合

[Note, 例如，模板类型(class templates) `basic_string`和 非成员的且工作在string上的 模板函数(function tempaltes)，一起被引用为string component]



---

page16