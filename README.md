# AI+Rust辅助开发数据收集

## 标注任务
### 针对开发过程的错误收集
收集自己在完成Rust练习题、实际Rust开发时遇到的错误尝试与最终正确解答。详见[develop/README.md](develop/README.md)。

### 针对插件输出的反馈收集
使用CodeGeeX插件完成Rust练习题与进行Rust开发，从多方面评价生成内容，并给出正确实现。详见[feedback/README.md](feedback/README.md)。

### 针对错误类型的数据收集
[Rust Compiler Error Index](https://doc.rust-lang.org/error-index.html)共包含508个Rust编译器会报出的错误，其中部分错误可以无需额外信息，仅根据错误代码内容即修复。需要将这些错误类型筛选出来，并围绕其构造错误代码与正确实现的数据。详见[synthesize/README.md](synthesize/README.md)。

## 提交方式
Fork本仓库，在本地标注数据，标注完成后通过pull request提交到主仓库。