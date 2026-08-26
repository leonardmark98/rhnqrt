最新前沿技术资讯

一、入门教程｜Getting Started
原标题：OpenSource：如何高效阅读大型开源项目源码
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.kecwyj.asia/arts/151259.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.kecwyj.asia/arts/539381.Doc

原标题：golang github actions 缓存依赖提速
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.kecwyj.asia/arts/836287.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.kecwyj.asia/arts/482455.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.kecwyj.asia/arts/121516.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.kecwyj.asia/arts/571701.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.kecwyj.asia/arts/979801.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.kecwyj.asia/arts/644392.Doc

原标题：系统时间同步定时任务偏移
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.kecwyj.asia/arts/489703.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.kecwyj.asia/arts/384968.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.kecwyj.asia/arts/246522.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.kecwyj.asia/arts/453873.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.kecwyj.asia/arts/070718.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.kecwyj.asia/arts/102440.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.kecwyj.asia/arts/945188.Doc

原标题：golang docker compose 环境变量
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.kecwyj.asia/arts/120922.Doc

原标题：golang k8s configmap secret 配置
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.kecwyj.asia/arts/530040.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.kecwyj.asia/arts/669700.Doc

原标题：HTTPS 证书过期更新操作
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.kecwyj.asia/arts/479538.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.kecwyj.asia/arts/472966.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.kecwyj.asia/arts/939688.Doc

原标题：项目语义化版本号规范管理
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.kecwyj.asia/arts/785284.Doc

原标题：rebase 操作防止代码丢失
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.kecwyj.asia/arts/970014.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.kecwyj.asia/arts/422494.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.kecwyj.asia/arts/087463.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.kecwyj.asia/arts/280137.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.kecwyj.asia/arts/757816.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.kecwyj.asia/arts/942182.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.kecwyj.asia/arts/509134.Doc

原标题：超大数据集分页性能优化方案
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.kecwyj.asia/arts/195976.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.kecwyj.asia/arts/458349.Doc

原标题：golang base64 编码解码实操
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.kecwyj.asia/arts/116554.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.kecwyj.asia/arts/954924.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.kecwyj.asia/arts/053123.Doc

原标题：golang kafka 生产者参数调优
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.kecwyj.asia/arts/907120.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.kecwyj.asia/arts/429567.Doc

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.kecwyj.asia/arts/424366.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.kecwyj.asia/arts/867431.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.kecwyj.asia/arts/642446.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.kecwyj.asia/arts/967946.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.kecwyj.asia/arts/229732.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.kecwyj.asia/arts/829448.Doc

原标题：日志切割配置防止日志丢失
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.kecwyj.asia/arts/277961.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.kecwyj.asia/arts/537357.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.kecwyj.asia/arts/526229.Doc

原标题：react 状态管理方案选型对比
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.kecwyj.asia/arts/744045.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.kecwyj.asia/arts/153927.Doc

原标题：跨平台换行符统一异常修复
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.kecwyj.asia/arts/615361.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.kecwyj.asia/arts/596821.Doc

原标题：golang docker compose 部署 minio
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.kecwyj.asia/arts/815738.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.kecwyj.asia/arts/157045.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.kecwyj.asia/arts/605312.Doc

原标题：数据库读写分离性能优化
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.kecwyj.asia/arts/120364.Doc

原标题：前后端会话登录状态持久化
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.kecwyj.asia/arts/678020.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.kecwyj.asia/arts/164696.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.kecwyj.asia/arts/044676.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.kecwyj.asia/arts/456183.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.kecwyj.asia/arts/758950.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.kecwyj.asia/arts/356516.Doc

原标题：golang redis lua 脚本开发调试
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.kecwyj.asia/arts/208260.Doc

原标题：golang 大文件 http 下载服务
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.kecwyj.asia/arts/536438.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.kecwyj.asia/arts/074471.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.kecwyj.asia/arts/166901.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.kecwyj.asia/arts/186398.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.kecwyj.asia/arts/659879.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.kecwyj.asia/arts/576905.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.kecwyj.asia/arts/049276.Doc

原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.kecwyj.asia/arts/044464.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.kecwyj.asia/arts/818913.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.kecwyj.asia/arts/418067.Doc

原标题：Git 代码冲突正确处理方式
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.kecwyj.asia/arts/048757.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.kecwyj.asia/arts/089739.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.kecwyj.asia/arts/360570.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.kecwyj.asia/arts/759281.Doc

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.kecwyj.asia/arts/741733.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.kecwyj.asia/arts/744592.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.kecwyj.asia/arts/642656.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.kecwyj.asia/arts/720727.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.kecwyj.asia/arts/272638.Doc

原标题：容器资源限制防止宿主机过载
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.kecwyj.asia/arts/183250.Doc

三、实战开发｜Practice
原标题：快速入门简单签名校验实现思路
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.kecwyj.asia/arts/345855.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.kecwyj.asia/arts/384714.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.kecwyj.asia/arts/617733.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.kecwyj.asia/arts/123078.Doc

原标题：跨平台换行符统一异常修复
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.kecwyj.asia/arts/282845.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.kecwyj.asia/arts/744594.Doc

原标题：golang kafka 监控指标简单梳理
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.kecwyj.asia/arts/889816.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.kecwyj.asia/arts/458404.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.kecwyj.asia/arts/351585.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.kecwyj.asia/arts/126020.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.kecwyj.asia/arts/060109.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.kecwyj.asia/arts/463414.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.kecwyj.asia/arts/778954.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.kecwyj.asia/arts/966531.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.kecwyj.asia/arts/668738.Doc

原标题：golang k8s 节点污点容忍度配置
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.kecwyj.asia/arts/496811.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.kecwyj.asia/arts/788228.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.kecwyj.asia/arts/144195.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.kecwyj.asia/arts/389651.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.kecwyj.asia/arts/841958.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.kecwyj.asia/arts/599174.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.kecwyj.asia/arts/296264.Doc

原标题：golang 容器健康检查接口开发
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.kecwyj.asia/arts/066847.Doc

原标题：缓存基础原理与简单代码实现
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.kecwyj.asia/arts/374114.Doc

原标题：API 大版本不兼容平滑迁移
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.kecwyj.asia/arts/677339.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.kecwyj.asia/arts/647266.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.kecwyj.asia/arts/684132.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.kecwyj.asia/arts/458034.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.kecwyj.asia/arts/371156.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.kecwyj.asia/arts/934658.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.kecwyj.asia/arts/260525.Doc

原标题：布隆过滤器数据高效去重实现
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.kecwyj.asia/arts/570930.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.kecwyj.asia/arts/537994.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.kecwyj.asia/arts/108072.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.kecwyj.asia/arts/538799.Doc

原标题：多线程线程安全脏数据规避
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.kecwyj.asia/arts/335748.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.kecwyj.asia/arts/331494.Doc

原标题：golang 单例模式实现几种方式
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.kecwyj.asia/arts/015517.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.kecwyj.asia/arts/313252.Doc

原标题：golang mongodb 事务多文档使用
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.kecwyj.asia/arts/934000.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.kecwyj.asia/arts/090935.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.kecwyj.asia/arts/127893.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.kecwyj.asia/arts/723395.Doc

原标题：项目目录结构规范化最佳实践
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.kecwyj.asia/arts/202967.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.kecwyj.asia/arts/600760.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.kecwyj.asia/arts/617172.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.kecwyj.asia/arts/852231.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.kecwyj.asia/arts/521796.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.kecwyj.asia/arts/634301.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.kecwyj.asia/arts/058824.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.kecwyj.asia/arts/858757.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.kecwyj.asia/arts/241865.Doc

原标题：golang mock 单元测试编写技巧
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.kecwyj.asia/arts/974141.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.kecwyj.asia/arts/269895.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.kecwyj.asia/arts/344436.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.kecwyj.asia/arts/453221.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.kecwyj.asia/arts/426952.Doc

原标题：排错：前端缓存304异常更新不及时
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.kecwyj.asia/arts/056954.Doc

?
