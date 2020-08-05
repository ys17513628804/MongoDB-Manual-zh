# [ ](#)诊断命令

[]()

> **注意**<br />
> 有关特定命令的详细信息，包括语法和示例，请单击特定命令以转到其参考页面。

| 名称                        | 描述                                                         |
| --------------------------- | ------------------------------------------------------------ |
| [`availableQueryOptions`]() | 内部命令，报告当前MongoDB实例的功能。                        |
| [`buildInfo`]()             | 显示有关MongoDB构建的统计信息。                              |
| [`collStats`]()             | 报告指定集合的存储利用率静态信息。                           |
| [`connPoolStats`]()         | 报告从此MongoDB实例到部署中其他MongoDB实例的传出连接的统计信息。 |
| [`connectionStatus`]()      | 报告当前连接的身份验证状态。                                 |
| [`cursorInfo`]()            | 在MongoDB 3.2中已删除。替换为`metrics.cursor`。              |
| [`dataSize`]()              | 返回数据范围的数据大小。供内部使用。                         |
| [`dbHash`]()                | 返回数据库及其集合的哈希值。                                 |
| [`dbStats`]()               | 报告指定数据库的存储利用率统计信息。                         |
| [`diagLogging`]()           | 在MongoDB 3.6中已删除。要捕获，重放和分析发送到您的MongoDB部署的命令，请使用`mongoreplay`。 |
| [`driverOIDTest`]()         | 将ObjectId转换为字符串以支持测试的内部命令。                 |
| [`explain`]()               | 返回有关各种操作执行的信息。                                 |
| [`features`]()              | 报告当前MongoDB实例中可用的功能。                            |
| [`getCmdLineOpts`]()        | 返回带有MongoDB实例及其解析选项的运行时参数的文档。          |
| [`getLog`]()                | 返回最近的日志消息。                                         |
| [`hostInfo`]()              | 返回反映基础主机系统的数据。                                 |
| [isSelf]()                  | 内部命令支持测试。                                           |
| [`listCommands`]()          | 列出当前`mongod`实例提供的所有数据库命令。                   |
| [`lockInfo`]()              | 内部命令，返回有关当前正在保留或挂起的锁的信息。仅适用于 `mongod`实例。 |
| [`netstat`]()               | 报告部署内连接性的内部命令。仅适用于`mongos`实例。           |
| [`ping`]()                  | 测试部署内连接性的内部命令。                                 |
| [`profile`]()               | 数据库事件探查器的接口。                                     |
| [`serverStatus`]()          | 返回有关实例范围的资源利用率和状态的集合指标。               |
| [`shardConnPoolStats`]()    | 报告`mongos`连接池上的统计信息，以供客户端针对分片进行操作。 |
| [`top`]()                   | 返回`mongod`实例中每个数据库的原始使用情况统计信息。         |
| [`validate`]()              | 内部命令，用于扫描集合的数据并为正确性编制索引。             |
| [`whatsmyuri`]()            | 返回有关当前客户端信息的内部命令。                           |