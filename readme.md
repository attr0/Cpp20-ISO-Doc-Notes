## Cpp20 ISO Document Reading Notes (in Chinese)

Cpp20 ISO/IEC 14882:2020 个人阅读笔记。关键词的中英文对应不准确，还请各位多多包容。



Copyright, Haolin Zhang. Shared under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) License.



### 起源

从C-Style的Macro黑魔法到如今CTE(compile time execution)的魔术表演，C++委员会在过去的20年间吸收各类日月精华开发的“高门槛但高效”的代码文本修正/替换/复制粘贴工具已经深入人心地成为了其他所有语言的笑柄，被我老板喷为“史上最烂的语言”。25年前，Java凭借VM运行时提供标准接口和“优质”代码抽象打烂了所有语言。如今，伴随Cpp20的诞生，这头沉睡的巨龙开始了他的反击。它不仅仅又双叒优化了它的文本替换工具，而且通过STL要求编译器提供统一且广泛的系统接口，向现代语言进发。希望这个古老的语言可以重返青春，也让我这个菜鸟见证一下历史。也许将来的某一天，任何一个软件工程师都可以用Cpp轻松实现硬件和业务接口。



至于说我为什么还要学习Cpp？

> Rust学的越多，我越怀念Cpp给予我的自由；Java/Go学的越多，我越怀念指针的快感



### 目标

- 理解Cpp概念
- 理解Cpp STL



### Milestone

- **2022-06-27** 项目开始