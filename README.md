# libchai-smdc 汉字编码算法・四（三）码定长特化

本项目是一个在 libchai 基础上二次开发的示例，它安装了 libchai 作为依赖，实现了一个自定义的「四码定长编码器」类型和一个自定义的「四码定长目标函数」类型，并利用该自定义的编码器、目标函数和其他 libchai 中的工具实现了一个四码定长类方案优化的命令行程序。

在 Apple M2 Max 电脑上上运行 `cargo bench` 给出的典型四码定长字词和四码定长单字方案计算一次目标函数的用时约为 300 μs 和 50 μs，速度分别是 libchai 的 2 倍和 3 倍。

您可以查看 `examples/` 目录下的米十五笔示例文件以开始使用。
