最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现接口mock动态返回不同响应
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.z26bb9.asia/arts/012026.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.z26bb9.asia/arts/746795.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.z26bb9.asia/arts/157033.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.z26bb9.asia/arts/054478.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.z26bb9.asia/arts/529584.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.z26bb9.asia/arts/488300.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.z26bb9.asia/arts/277004.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.z26bb9.asia/arts/759584.Doc

原标题：实践：数据库回滚点业务调试实践
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.z26bb9.asia/arts/947736.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.z26bb9.asia/arts/018314.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/235189.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.z26bb9.asia/arts/317688.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.z26bb9.asia/arts/144049.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.z26bb9.asia/arts/567905.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/717886.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.z26bb9.asia/arts/084527.Doc

原标题：看懂报错日志快速定位问题
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.z26bb9.asia/arts/560321.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.z26bb9.asia/arts/623245.Doc

原标题：全量回归测试提升代码质量
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.z26bb9.asia/arts/151452.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.z26bb9.asia/arts/940930.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.z26bb9.asia/arts/647291.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.z26bb9.asia/arts/936884.Doc

原标题：大文件导出内存溢出防护
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.z26bb9.asia/arts/141521.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.z26bb9.asia/arts/963899.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.z26bb9.asia/arts/829829.Doc

原标题：golang mongodb 事务多文档使用
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.z26bb9.asia/arts/771787.Doc

原标题：golang 数据库慢查询监控实现
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/830378.Doc

原标题：golang 内存缓存简单实现方案
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.z26bb9.asia/arts/195229.Doc

原标题：CI 持续集成自动构建流程
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.z26bb9.asia/arts/923359.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.z26bb9.asia/arts/418462.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.z26bb9.asia/arts/055654.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.z26bb9.asia/arts/548218.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.z26bb9.asia/arts/822468.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.z26bb9.asia/arts/272574.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/482826.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.z26bb9.asia/arts/296220.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.z26bb9.asia/arts/770798.Doc

原标题：开源源码阅读拆解学习思路
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.z26bb9.asia/arts/214132.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/841612.Doc

原标题：golang 优雅处理数据库事务
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/264691.Doc


二、踩坑排错｜Troubleshooting
原标题：静态博客部署 GitHub Pages 教程
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/821635.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.z26bb9.asia/arts/595402.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.z26bb9.asia/arts/209783.Doc

原标题：依赖安装失败全方位排错
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.z26bb9.asia/arts/004902.Doc

原标题：OOMKilled 容器被杀完整排查
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.z26bb9.asia/arts/905696.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.z26bb9.asia/arts/070386.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.z26bb9.asia/arts/931601.Doc

原标题：golang k8s devops 流水线简单思路
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.z26bb9.asia/arts/917762.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.z26bb9.asia/arts/230134.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.z26bb9.asia/arts/930793.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/028358.Doc

原标题：文件锁正确使用避免死锁
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.z26bb9.asia/arts/292092.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.z26bb9.asia/arts/615296.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.z26bb9.asia/arts/855544.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/861888.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/839664.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.z26bb9.asia/arts/158141.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.z26bb9.asia/arts/799877.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.z26bb9.asia/arts/533465.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.z26bb9.asia/arts/641417.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.z26bb9.asia/arts/431665.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/506704.Doc

原标题：HTTPS 证书过期更新操作
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.z26bb9.asia/arts/206337.Doc

原标题：重复提交幂等防护再次讲解
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/345444.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.z26bb9.asia/arts/338766.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.z26bb9.asia/arts/515155.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.z26bb9.asia/arts/018555.Doc

原标题：超大数据集分页性能优化方案
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.z26bb9.asia/arts/640760.Doc

原标题：日志驱动异常日志不输出修复
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.z26bb9.asia/arts/685864.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.z26bb9.asia/arts/381799.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/722475.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.z26bb9.asia/arts/848698.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.z26bb9.asia/arts/396295.Doc

原标题：时间精度统一业务判断修复
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.z26bb9.asia/arts/601673.Doc

原标题：正则表达式文本处理实战案例
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/933964.Doc

原标题：从零搭建简单Mock接口服务
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.z26bb9.asia/arts/551337.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.z26bb9.asia/arts/781400.Doc

原标题：提交第一个开源 PR 完整流程
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.z26bb9.asia/arts/506457.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.z26bb9.asia/arts/238076.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.z26bb9.asia/arts/472942.Doc

三、实战开发｜Practice
原标题：golang docker compose 本地开发最佳实践
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.z26bb9.asia/arts/612367.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.z26bb9.asia/arts/233908.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.z26bb9.asia/arts/936606.Doc

原标题：程序预加载加快服务启动速度
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.z26bb9.asia/arts/495543.Doc

原标题：限流窗口绕过漏洞修复方案
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.z26bb9.asia/arts/509366.Doc

原标题：golang redis 缓存雪崩完整处理
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.z26bb9.asia/arts/258870.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.z26bb9.asia/arts/262899.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.z26bb9.asia/arts/717338.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.z26bb9.asia/arts/051032.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.z26bb9.asia/arts/788627.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.z26bb9.asia/arts/010289.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.z26bb9.asia/arts/086544.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.z26bb9.asia/arts/156560.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.z26bb9.asia/arts/939164.Doc

原标题：快速入门异步编程基础模型
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.z26bb9.asia/arts/435776.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.z26bb9.asia/arts/498257.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.z26bb9.asia/arts/362147.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.z26bb9.asia/arts/612049.Doc

原标题：golang github actions 缓存依赖提速
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.z26bb9.asia/arts/085448.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.z26bb9.asia/arts/388371.Doc

原标题：快速入门对象存储基础使用场景
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.z26bb9.asia/arts/198994.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/613583.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.z26bb9.asia/arts/236072.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.z26bb9.asia/arts/098779.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.z26bb9.asia/arts/319265.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.z26bb9.asia/arts/602340.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.z26bb9.asia/arts/210091.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/042992.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.z26bb9.asia/arts/492884.Doc

原标题：golang 系统设计分布式事务几种方案
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.z26bb9.asia/arts/073381.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.z26bb9.asia/arts/373388.Doc

原标题：RPC 接口字段增减兼容处理
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.z26bb9.asia/arts/060360.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.z26bb9.asia/arts/022133.Doc

原标题：echarts 大数据渲染性能调优
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.z26bb9.asia/arts/674726.Doc

原标题：前端骨架屏提升页面体验
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.z26bb9.asia/arts/074867.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.z26bb9.asia/arts/226672.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/075118.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.z26bb9.asia/arts/508241.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.z26bb9.asia/arts/338517.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.z26bb9.asia/arts/862958.Doc

四、架构设计｜Architecture
原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.z26bb9.asia/arts/015562.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.z26bb9.asia/arts/751270.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/555217.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.z26bb9.asia/arts/995668.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.z26bb9.asia/arts/830584.Doc

原标题：golang consul 健康检查服务注册
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.z26bb9.asia/arts/301818.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.z26bb9.asia/arts/491465.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.z26bb9.asia/arts/740714.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.z26bb9.asia/arts/975847.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.z26bb9.asia/arts/165525.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.z26bb9.asia/arts/819485.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.z26bb9.asia/arts/962529.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.z26bb9.asia/arts/122663.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.z26bb9.asia/arts/555995.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.z26bb9.asia/arts/929865.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/129482.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/233524.Doc

原标题：golang consul 服务发现简单示例
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.z26bb9.asia/arts/996961.Doc

?
