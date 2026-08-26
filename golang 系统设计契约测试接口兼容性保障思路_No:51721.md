最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.d0lohs.asia/arts/756601.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.d0lohs.asia/arts/441315.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.d0lohs.asia/arts/506012.Doc

原标题：从零搭建简单的健康检查接口示例
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.d0lohs.asia/arts/764717.Doc

原标题：golang context 上下文传参讲解
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.d0lohs.asia/arts/258999.Doc

原标题：nodejs redis 缓存业务实战
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.d0lohs.asia/arts/170593.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.d0lohs.asia/arts/639008.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.d0lohs.asia/arts/838181.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.d0lohs.asia/arts/711581.Doc

原标题：golang prometheus counter gauge 使用
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.d0lohs.asia/arts/032100.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.d0lohs.asia/arts/926043.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.d0lohs.asia/arts/286772.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.d0lohs.asia/arts/801444.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.d0lohs.asia/arts/135931.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.d0lohs.asia/arts/218663.Doc

原标题：golang es 索引生命周期管理思路
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.d0lohs.asia/arts/360055.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.d0lohs.asia/arts/942617.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.d0lohs.asia/arts/227147.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.d0lohs.asia/arts/683656.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.d0lohs.asia/arts/166136.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.d0lohs.asia/arts/275973.Doc

原标题：CI 构建缓存加速编译速度
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.d0lohs.asia/arts/972712.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.d0lohs.asia/arts/347743.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.d0lohs.asia/arts/508180.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.d0lohs.asia/arts/358245.Doc

原标题：golang redis hyperloglog 基数统计
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.d0lohs.asia/arts/644901.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.d0lohs.asia/arts/539959.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.d0lohs.asia/arts/211388.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.d0lohs.asia/arts/984998.Doc

原标题：慢查询分析索引调优数据库实战
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.d0lohs.asia/arts/084174.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.d0lohs.asia/arts/117168.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.d0lohs.asia/arts/688915.Doc

原标题：golang alertmanager 钉钉告警推送
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.d0lohs.asia/arts/915251.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.d0lohs.asia/arts/582419.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.d0lohs.asia/arts/433675.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.d0lohs.asia/arts/276963.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.d0lohs.asia/arts/187875.Doc

原标题：golang prometheus metrics 埋点开发
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.d0lohs.asia/arts/718124.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.d0lohs.asia/arts/101393.Doc

原标题：golang git 提交信息规范校验
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.d0lohs.asia/arts/205249.Doc


二、踩坑排错｜Troubleshooting
原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.d0lohs.asia/arts/659889.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.d0lohs.asia/arts/733314.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.d0lohs.asia/arts/009869.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.d0lohs.asia/arts/022411.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.d0lohs.asia/arts/956843.Doc

原标题：golang 文件上传下载接口开发
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.d0lohs.asia/arts/329783.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.d0lohs.asia/arts/572844.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.d0lohs.asia/arts/776200.Doc

原标题：golang url 参数编码处理方案
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.d0lohs.asia/arts/694712.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.d0lohs.asia/arts/481438.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.d0lohs.asia/arts/513790.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.d0lohs.asia/arts/503674.Doc

原标题：任务执行锁防止并发重复调度
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.d0lohs.asia/arts/585927.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.d0lohs.asia/arts/123893.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.d0lohs.asia/arts/095552.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.d0lohs.asia/arts/193699.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.d0lohs.asia/arts/003389.Doc

原标题：golang kafka 消息丢失重复消费
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.d0lohs.asia/arts/611897.Doc

原标题：golang go test 覆盖率统计实操
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.d0lohs.asia/arts/830657.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.d0lohs.asia/arts/652125.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.d0lohs.asia/arts/503313.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.d0lohs.asia/arts/538556.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.d0lohs.asia/arts/875111.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.d0lohs.asia/arts/411535.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.d0lohs.asia/arts/828903.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.d0lohs.asia/arts/931303.Doc

原标题：golang 大文件 http 下载服务
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.d0lohs.asia/arts/042362.Doc

原标题：golang 优雅停机服务关闭实现
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.d0lohs.asia/arts/842911.Doc

原标题：nodejs 流处理大文件不占内存
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.d0lohs.asia/arts/618963.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.d0lohs.asia/arts/541798.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.d0lohs.asia/arts/325276.Doc

原标题：golang k8s 节点污点容忍度配置
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.d0lohs.asia/arts/058509.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.d0lohs.asia/arts/136808.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.d0lohs.asia/arts/065669.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.d0lohs.asia/arts/273679.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.d0lohs.asia/arts/284198.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.d0lohs.asia/arts/084339.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.d0lohs.asia/arts/708595.Doc

原标题：golang elasticsearch 索引设计思路
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.d0lohs.asia/arts/828670.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.d0lohs.asia/arts/706990.Doc

三、实战开发｜Practice
原标题：记一次升级操作系统内核引发服务不稳定
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.d0lohs.asia/arts/598189.Doc

原标题：golang etcd 配置中心简单使用
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.d0lohs.asia/arts/307417.Doc

原标题：快速上手简单性能监控指标查看
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.d0lohs.asia/arts/057250.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.d0lohs.asia/arts/983104.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.d0lohs.asia/arts/341620.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.d0lohs.asia/arts/332996.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.d0lohs.asia/arts/064275.Doc

原标题：文件批量导入导出功能实现
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.d0lohs.asia/arts/962261.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.d0lohs.asia/arts/014026.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.d0lohs.asia/arts/704221.Doc

原标题：golang consul 健康检查服务注册
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.d0lohs.asia/arts/618036.Doc

原标题：批量操作分批处理防止 OOM
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.d0lohs.asia/arts/154463.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.d0lohs.asia/arts/941352.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.d0lohs.asia/arts/666469.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.d0lohs.asia/arts/465054.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.d0lohs.asia/arts/058735.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.d0lohs.asia/arts/332592.Doc

原标题：短信服务封装失败自动重试
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.d0lohs.asia/arts/963076.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.d0lohs.asia/arts/659711.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.d0lohs.asia/arts/210983.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.d0lohs.asia/arts/077505.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.d0lohs.asia/arts/783385.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.d0lohs.asia/arts/821760.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.d0lohs.asia/arts/341568.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.d0lohs.asia/arts/533305.Doc

原标题：集成测试业务流程编写示例
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.d0lohs.asia/arts/478990.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.d0lohs.asia/arts/252641.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.d0lohs.asia/arts/082142.Doc

原标题：golang 项目环境变量加载方案
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.d0lohs.asia/arts/617180.Doc

原标题：golang 互斥锁读写锁并发安全
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.d0lohs.asia/arts/892967.Doc

原标题：定时任务重复执行分布式锁
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.d0lohs.asia/arts/887135.Doc

原标题：新手参与开源社区贡献指南
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.d0lohs.asia/arts/905919.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.d0lohs.asia/arts/538553.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.d0lohs.asia/arts/307360.Doc

原标题：golang consul 健康检查服务注册
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.d0lohs.asia/arts/903887.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.d0lohs.asia/arts/373868.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.d0lohs.asia/arts/754886.Doc

原标题：Git 子模块更新代码不全修复
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.d0lohs.asia/arts/522249.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.d0lohs.asia/arts/078527.Doc

原标题：多实例部署 Session 共享方案
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.d0lohs.asia/arts/229057.Doc

四、架构设计｜Architecture
原标题：golang 系统设计布隆过滤器原理与落地
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.d0lohs.asia/arts/481885.Doc

原标题：nodejs 中间件模式原理剖析
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.d0lohs.asia/arts/162304.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.d0lohs.asia/arts/236624.Doc

原标题：golang docker compose 本地开发最佳实践
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.d0lohs.asia/arts/322469.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.d0lohs.asia/arts/498428.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.d0lohs.asia/arts/222836.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.d0lohs.asia/arts/891897.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.d0lohs.asia/arts/209368.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.d0lohs.asia/arts/293158.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.d0lohs.asia/arts/042655.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.d0lohs.asia/arts/315834.Doc

原标题：Cookie Session 会话状态管理
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.d0lohs.asia/arts/184116.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.d0lohs.asia/arts/332406.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.d0lohs.asia/arts/229550.Doc

原标题：设计思考：分布式会话架构选型对比
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.d0lohs.asia/arts/118420.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.d0lohs.asia/arts/716572.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.d0lohs.asia/arts/950580.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.d0lohs.asia/arts/583576.Doc

?
