最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计消息大小限制业务处理方案
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.3d36u4.asia/blog/263989.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.3d36u4.asia/blog/667030.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.3d36u4.asia/blog/967195.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.3d36u4.asia/blog/203373.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.3d36u4.asia/blog/415185.Doc

原标题：nestjs 全局返回格式统一处理
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.3d36u4.asia/blog/071099.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.3d36u4.asia/blog/534740.Doc

原标题：golang 分页查询封装通用工具
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.3d36u4.asia/blog/827685.Doc

原标题：golang docker compose 本地开发最佳实践
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.3d36u4.asia/blog/536877.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.3d36u4.asia/blog/783928.Doc

原标题：系统字符集统一乱码修复
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.3d36u4.asia/blog/277295.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.3d36u4.asia/blog/388470.Doc

原标题：golang mysql 批量导入数据实操
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.3d36u4.asia/blog/720840.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.3d36u4.asia/blog/812466.Doc

原标题：分布式 ID 全局唯一生成方案
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.3d36u4.asia/blog/550362.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.3d36u4.asia/blog/415398.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.3d36u4.asia/blog/996981.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.3d36u4.asia/blog/714843.Doc

原标题：Cookie Session 会话状态管理
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.3d36u4.asia/blog/619244.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.3d36u4.asia/blog/178192.Doc

原标题：热更新开发环境配置教程
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.3d36u4.asia/blog/606292.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.3d36u4.asia/blog/561885.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.3d36u4.asia/blog/741696.Doc

原标题：Shell 脚本自动化命令编写
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.3d36u4.asia/blog/426694.Doc

原标题：golang mysql 长连接短连接对比
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.3d36u4.asia/blog/297073.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.3d36u4.asia/blog/496953.Doc

原标题：开源源码阅读拆解学习思路
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.3d36u4.asia/blog/944234.Doc

原标题：灰度发布策略服务平滑升级
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.3d36u4.asia/blog/961185.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.3d36u4.asia/blog/619103.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.3d36u4.asia/blog/801060.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.3d36u4.asia/blog/231707.Doc

原标题：DNS 解析异常第三方调用故障
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.3d36u4.asia/blog/797570.Doc

原标题：时间同步修复令牌提前过期
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.3d36u4.asia/blog/459510.Doc

原标题：项目构建脚本编译打包解析
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.3d36u4.asia/blog/274769.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.3d36u4.asia/blog/853600.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.3d36u4.asia/blog/978655.Doc

原标题：golang mysql json 字段查询使用
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.3d36u4.asia/blog/688987.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.3d36u4.asia/blog/292148.Doc

原标题：golang redis 主从复制哨兵原理
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.3d36u4.asia/blog/168815.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.3d36u4.asia/blog/490690.Doc


二、踩坑排错｜Troubleshooting
原标题：布隆过滤器误判问题修正
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.3d36u4.asia/blog/482759.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.3d36u4.asia/blog/966894.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.3d36u4.asia/blog/167958.Doc

原标题：从零搭建本地开发环境完整教程
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.3d36u4.asia/blog/193003.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.3d36u4.asia/blog/499215.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.3d36u4.asia/blog/343996.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.3d36u4.asia/blog/082628.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.3d36u4.asia/blog/993621.Doc

原标题：内存泄漏定位分析完整流程
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.3d36u4.asia/blog/174183.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.3d36u4.asia/blog/618982.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.3d36u4.asia/blog/605447.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.3d36u4.asia/blog/396318.Doc

原标题：快速上手简单性能监控指标查看
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.3d36u4.asia/blog/319519.Doc

原标题：热更新开发环境配置教程
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.3d36u4.asia/blog/195270.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.3d36u4.asia/blog/311468.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.3d36u4.asia/blog/448519.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.3d36u4.asia/blog/464426.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.3d36u4.asia/blog/140408.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.3d36u4.asia/blog/198340.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.3d36u4.asia/blog/839927.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.3d36u4.asia/blog/642794.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.3d36u4.asia/blog/987268.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.3d36u4.asia/blog/893668.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.3d36u4.asia/blog/719015.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.3d36u4.asia/blog/979246.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.3d36u4.asia/blog/663028.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.3d36u4.asia/blog/155850.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.3d36u4.asia/blog/989502.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.3d36u4.asia/blog/801003.Doc

原标题：站内邮件消息通知功能开发
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.3d36u4.asia/blog/097114.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.3d36u4.asia/blog/427129.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.3d36u4.asia/blog/002181.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.3d36u4.asia/blog/708550.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.3d36u4.asia/blog/329759.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.3d36u4.asia/blog/158952.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.3d36u4.asia/blog/042766.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.3d36u4.asia/blog/358704.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.3d36u4.asia/blog/442743.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.3d36u4.asia/blog/231578.Doc

原标题：单元测试用例编写入门实操
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.3d36u4.asia/blog/523114.Doc

三、实战开发｜Practice
原标题：实战：数据库explain执行计划分析实操演练
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.3d36u4.asia/blog/369531.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.3d36u4.asia/blog/153347.Doc

原标题：golang mysql 长连接短连接对比
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.3d36u4.asia/blog/121557.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.3d36u4.asia/blog/643589.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.3d36u4.asia/blog/646742.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.3d36u4.asia/blog/295161.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.3d36u4.asia/blog/056920.Doc

原标题：端口占用释放资源重启服务
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.3d36u4.asia/blog/261701.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.3d36u4.asia/blog/181402.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.3d36u4.asia/blog/289723.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.3d36u4.asia/blog/785914.Doc

原标题：golang 系统设计分布式任务调度
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.3d36u4.asia/blog/887185.Doc

原标题：包管理器依赖冲突解决方案
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.3d36u4.asia/blog/467990.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.3d36u4.asia/blog/056960.Doc

原标题：多套环境灵活切换配置方案
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.3d36u4.asia/blog/077333.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.3d36u4.asia/blog/991803.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.3d36u4.asia/blog/600444.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.3d36u4.asia/blog/523692.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.3d36u4.asia/blog/367379.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.3d36u4.asia/blog/725755.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.3d36u4.asia/blog/049226.Doc

原标题：golang lru 缓存淘汰算法编写
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.3d36u4.asia/blog/460939.Doc

原标题：DNS 解析异常第三方调用故障
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.3d36u4.asia/blog/674379.Doc

原标题：前后端交互跨域问题完整处理
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.3d36u4.asia/blog/911777.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.3d36u4.asia/blog/142545.Doc

原标题：eslint prettier 代码规范落地
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.3d36u4.asia/blog/863384.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.3d36u4.asia/blog/367029.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.3d36u4.asia/blog/846249.Doc

原标题：MySQL 慢查询索引优化实战
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.3d36u4.asia/blog/715959.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.3d36u4.asia/blog/201344.Doc

原标题：golang redis 网络超时参数调优
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.3d36u4.asia/blog/634543.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.3d36u4.asia/blog/150794.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.3d36u4.asia/blog/169546.Doc

原标题：golang url 参数编码处理方案
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.3d36u4.asia/blog/146282.Doc

原标题：golang 单元测试 table‑driven
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.3d36u4.asia/blog/048133.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.3d36u4.asia/blog/863358.Doc

原标题：golang mock 单元测试编写技巧
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.3d36u4.asia/blog/532519.Doc

原标题：golang 系统信号信号量处理
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.3d36u4.asia/blog/200725.Doc

原标题：热更新开发环境配置教程
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.3d36u4.asia/blog/026936.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.3d36u4.asia/blog/292022.Doc

四、架构设计｜Architecture
原标题：golang 工具函数库封装思路
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.3d36u4.asia/blog/209323.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.3d36u4.asia/blog/536000.Doc

原标题：golang 系统设计容量评估简单方法论
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.3d36u4.asia/blog/131134.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.3d36u4.asia/blog/674799.Doc

原标题：golang mysql 慢查询日志开启分析
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.3d36u4.asia/blog/971130.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.3d36u4.asia/blog/327725.Doc

原标题：golang k8s job 一次性任务执行
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.3d36u4.asia/blog/943466.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.3d36u4.asia/blog/245351.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.3d36u4.asia/blog/080570.Doc

原标题：接口请求重试容错机制实现
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.3d36u4.asia/blog/157418.Doc

原标题：golang 分布式上下文传递方案
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.3d36u4.asia/blog/531107.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.3d36u4.asia/blog/038800.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.3d36u4.asia/blog/311698.Doc

原标题：服务器时钟同步任务错乱修复
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.3d36u4.asia/blog/619763.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.3d36u4.asia/blog/720996.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.3d36u4.asia/blog/171315.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.3d36u4.asia/blog/635442.Doc

原标题：golang 分库分表简单路由实现
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.3d36u4.asia/blog/458676.Doc

?
