最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang k8s liveness readiness 探针
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/598591.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.z26bb9.asia/arts/533253.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.z26bb9.asia/arts/340403.Doc

原标题：本地运行正常线上报错排查
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.z26bb9.asia/arts/899205.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.z26bb9.asia/arts/552184.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.z26bb9.asia/arts/775431.Doc

原标题：golang redis stream 消息队列实践
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.z26bb9.asia/arts/155418.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.z26bb9.asia/arts/056782.Doc

原标题：golang consul 服务发现简单示例
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.z26bb9.asia/arts/784439.Doc

原标题：Security：RPC调用身份认证安全加固
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.z26bb9.asia/arts/404132.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.z26bb9.asia/arts/813221.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.z26bb9.asia/arts/377952.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.z26bb9.asia/arts/389328.Doc

原标题：HTTPS 证书过期更新操作
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.z26bb9.asia/arts/130585.Doc

原标题：golang mongodb 文档结构设计原则
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.z26bb9.asia/arts/730074.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/071258.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.z26bb9.asia/arts/271686.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.z26bb9.asia/arts/994958.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.z26bb9.asia/arts/903599.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.z26bb9.asia/arts/860259.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.z26bb9.asia/arts/634325.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.z26bb9.asia/arts/425030.Doc

原标题：golang 优雅处理 http 超时设置
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.z26bb9.asia/arts/250218.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.z26bb9.asia/arts/744172.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/246367.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.z26bb9.asia/arts/374913.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.z26bb9.asia/arts/489669.Doc

原标题：golang mysql 字符集排序规则设置
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.z26bb9.asia/arts/935866.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/841866.Doc

原标题：项目语义化版本号规范管理
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/295481.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.z26bb9.asia/arts/673594.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.z26bb9.asia/arts/681761.Doc

原标题：批量操作分批处理防止 OOM
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.z26bb9.asia/arts/456174.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.z26bb9.asia/arts/050611.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.z26bb9.asia/arts/930376.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.z26bb9.asia/arts/778443.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.z26bb9.asia/arts/481425.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.z26bb9.asia/arts/723101.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.z26bb9.asia/arts/080682.Doc

原标题：程序信号中断退出处理逻辑
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.z26bb9.asia/arts/140129.Doc


二、踩坑排错｜Troubleshooting
原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.z26bb9.asia/arts/973145.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.z26bb9.asia/arts/185485.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.z26bb9.asia/arts/634768.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.z26bb9.asia/arts/608866.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.z26bb9.asia/arts/971739.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/905294.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.z26bb9.asia/arts/607159.Doc

原标题：从零搭建简单定时任务demo
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/945847.Doc

原标题：集成测试业务流程编写示例
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/029178.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.z26bb9.asia/arts/653243.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.z26bb9.asia/arts/291153.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.z26bb9.asia/arts/098262.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/150736.Doc

原标题：依赖安装失败全方位排错
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/724994.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/261319.Doc

原标题：golang 集成测试启动测试数据库
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.z26bb9.asia/arts/767625.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.z26bb9.asia/arts/113521.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/221729.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.z26bb9.asia/arts/727695.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.z26bb9.asia/arts/036796.Doc

原标题：前端工程化 webpack 打包优化
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/746180.Doc

原标题：浏览器缓存强制刷新方案
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/190269.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.z26bb9.asia/arts/086259.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.z26bb9.asia/arts/864937.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.z26bb9.asia/arts/863291.Doc

原标题：限流窗口绕过漏洞修复方案
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.z26bb9.asia/arts/435655.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.z26bb9.asia/arts/195097.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.z26bb9.asia/arts/738270.Doc

原标题：golang kafka offset 提交策略
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.z26bb9.asia/arts/316078.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.z26bb9.asia/arts/936175.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.z26bb9.asia/arts/044238.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.z26bb9.asia/arts/752750.Doc

原标题：golang 系统设计序列化性能选型对比
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.z26bb9.asia/arts/004395.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.z26bb9.asia/arts/434447.Doc

原标题：百万数据 Excel 导出内存优化
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.z26bb9.asia/arts/372922.Doc

原标题：前端错误监控上报系统搭建
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.z26bb9.asia/arts/166399.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.z26bb9.asia/arts/845319.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.z26bb9.asia/arts/678181.Doc

原标题：golang 系统设计分库分表中间件思路
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.z26bb9.asia/arts/041916.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.z26bb9.asia/arts/908068.Doc

三、实战开发｜Practice
原标题：后端分页查询逻辑代码实现
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.z26bb9.asia/arts/286389.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.z26bb9.asia/arts/310080.Doc

原标题：golang docker 运行 etcd 本地测试
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/901003.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/913328.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.z26bb9.asia/arts/623657.Doc

原标题：golang zap 日志按日期切割方案
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.z26bb9.asia/arts/788760.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.z26bb9.asia/arts/033004.Doc

原标题：死信队列处理消息阻塞业务
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.z26bb9.asia/arts/615814.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/377480.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.z26bb9.asia/arts/942514.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.z26bb9.asia/arts/879848.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.z26bb9.asia/arts/836653.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/506193.Doc

原标题：golang grpc protobuf 开发实操
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/505165.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.z26bb9.asia/arts/931178.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.z26bb9.asia/arts/805147.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.z26bb9.asia/arts/671111.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.z26bb9.asia/arts/204661.Doc

原标题：日志输出规范防止磁盘爆满
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.z26bb9.asia/arts/299677.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.z26bb9.asia/arts/534103.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.z26bb9.asia/arts/615767.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.z26bb9.asia/arts/411355.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.z26bb9.asia/arts/598268.Doc

原标题：数据库分表存储大表优化方案
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.z26bb9.asia/arts/420874.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.z26bb9.asia/arts/426559.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.z26bb9.asia/arts/019493.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.z26bb9.asia/arts/890322.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.z26bb9.asia/arts/078895.Doc

原标题：消息队列重复消费业务处理
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.z26bb9.asia/arts/655949.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.z26bb9.asia/arts/416395.Doc

原标题：接口幂等性防重复请求实现
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.z26bb9.asia/arts/042175.Doc

原标题：本地运行正常线上报错排查
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/959696.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.z26bb9.asia/arts/275915.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.z26bb9.asia/arts/886614.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.z26bb9.asia/arts/150722.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.z26bb9.asia/arts/648686.Doc

原标题：入门实践：本地简单代理服务搭建
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.z26bb9.asia/arts/223682.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.z26bb9.asia/arts/070473.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.z26bb9.asia/arts/578859.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.z26bb9.asia/arts/366544.Doc

四、架构设计｜Architecture
原标题：macOS 脚本执行权限开启
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.z26bb9.asia/arts/018637.Doc

原标题：入门实践：实现简单文件读写功能
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.z26bb9.asia/arts/016595.Doc

原标题：开发代理服务网络限制解决
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.z26bb9.asia/arts/566177.Doc

原标题：golang redis 发布订阅简单示例
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.z26bb9.asia/arts/027475.Doc

原标题：静态资源 404 路径打包修复
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/064685.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.z26bb9.asia/arts/273697.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.z26bb9.asia/arts/905184.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.z26bb9.asia/arts/684151.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.z26bb9.asia/arts/191594.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/159637.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.z26bb9.asia/arts/428198.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.z26bb9.asia/arts/313624.Doc

原标题：golang makefile 自动化构建脚本
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.z26bb9.asia/arts/263551.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.z26bb9.asia/arts/419994.Doc

原标题：服务熔断防止故障级联传播
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.z26bb9.asia/arts/337255.Doc

原标题：缓存过期策略优化防业务故障
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.z26bb9.asia/arts/823815.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.z26bb9.asia/arts/123280.Doc

原标题：编译打包产物依赖分析解读
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.z26bb9.asia/arts/687267.Doc

?
