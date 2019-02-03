# Notes for Open Source Projects with Go | Go语言开原工程阅读笔记

这个项目是《Go语言日常》的配套文档，目标是记录我感兴趣的开源项目的阅读笔记。

我选择阅读工程的基本原则是为书本服务。如果书中介绍到的功能，标准库没有很好的实现，而有优秀的第三方库实现，我就会找时间阅读与分析它，并把收获的笔记分享在这里。这些笔记会是这本书很好地内容补充，也会长期坚持下去。

同样，它也会是了解这些第三方库的一个很好的介绍。有介绍性的文档，再去阅读代码，应当会少走很多弯路，节省很多时间。

欢迎大家将自己的阅读笔记也添加进来。

## Structure | 结构

每个开源工程的笔记会记录在单独的目录中。每个笔记我打算做如下几种记录：

- 描述性的介绍。
- 总体架构分析与模块介绍。
- 数据结构介绍，包括struct等。
- 分功能介绍。按照每个独立的功能来讲，把该功能涉及到的函数调用流程讲清楚。
- 关键函数的实现细节。
- 优秀代码片段的赏析。
- 其他分析

## Plans | 计划

当前计划阅读的第三方开源库，列举如下：

| 笔记 | 开源工程源地址 | 说明 |
| --- | --- | --- |
| stdlib | Go语言标准库 |  |
| codesearch | [codesearch](https://github.com/google/codesearch)  | 代码搜索工具，by Russ Cox (one of the Go authors)|
| fsnotify | [fsnotify](https://github.com/fsnotify/fsnotify)  | 跨平台的文件消息通知系统|
| etcd | [etcd](https://github.com/etcd-io/etcd)  | 分布式配置系统兼键值库|
| syncthing | [syncthing](https://github.com/syncthing/syncthing)  | 持续文件同步系统|
| go-sync | [go-sync](https://github.com/Redundancy/go-sync)  | 实现了完整的ZSync/rsync功能|
| gut | [gut](https://github.com/tillberg/gut)  | 实时双向文件夹同步|
| studygolang | [studygolang](https://github.com/studygolang/studygolang)  | 开源的社区论坛，包括前后端|
| tail | [tail](https://github.com/hpcloud/tail) |  tail in Go|
| viper | [viper](https://github.com/spf13/viper) |  Configuratio library|
| protobuf | [protobuf](https://github.com/golang/protobuf) |  protobuf support for go|
