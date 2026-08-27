最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存一致性方案对比
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.soxckf.asia/blog/3101940.sHtMl

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.soxckf.asia/blog/9827833.sHtMl

原标题：golang redis 锁超时业务处理
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.soxckf.asia/blog/1997437.sHtMl

原标题：golang redis 缓存击穿防护实现
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.soxckf.asia/blog/4528981.sHtMl

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.soxckf.asia/blog/2807910.sHtMl

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.soxckf.asia/blog/6352526.sHtMl

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.soxckf.asia/blog/5356274.sHtMl

原标题：Architecture：静态配置与动态配置架构分离
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.soxckf.asia/blog/4410015.sHtMl

原标题：golang docker 容器资源限制设置
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.soxckf.asia/blog/4335703.sHtMl

原标题：golang 系统设计内存复用 sync.pool 使用
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.soxckf.asia/blog/5921769.sHtMl

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.soxckf.asia/blog/5981051.sHtMl

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.soxckf.asia/blog/7583615.sHtMl

原标题：golang 系统设计限流算法原理代码实现
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.soxckf.asia/blog/8536433.sHtMl

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.soxckf.asia/blog/8913201.sHtMl

原标题：大文件导出内存溢出防护
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.soxckf.asia/blog/1277320.sHtMl

原标题：Shell 脚本自动化命令编写
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.soxckf.asia/blog/6658240.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.soxckf.asia/blog/3116398.sHtMl

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.soxckf.asia/blog/3701333.sHtMl

原标题：Git 子模块更新代码不全修复
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.soxckf.asia/blog/6417581.sHtMl

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.soxckf.asia/blog/9052901.sHtMl

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.soxckf.asia/blog/0651652.sHtMl

原标题：DNS 解析异常第三方调用故障
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.soxckf.asia/blog/3833573.sHtMl

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.soxckf.asia/blog/3533912.sHtMl

原标题：golang k8s 命名空间资源隔离方案
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.soxckf.asia/blog/2688946.sHtMl

原标题：实战项目：前端资源打包体积优化完整实操
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.soxckf.asia/blog/0541977.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.soxckf.asia/blog/9064026.sHtMl

原标题：golang gin 框架接口开发实战
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.soxckf.asia/blog/5354934.sHtMl

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.soxckf.asia/blog/2594515.sHtMl

原标题：golang gorm 批量插入性能调优
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.soxckf.asia/blog/5320453.sHtMl

原标题：golang 系统设计线程协程泄露定位方法
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.soxckf.asia/blog/5701844.sHtMl

原标题：开发复盘：统一错误码体系设计落地实践
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.soxckf.asia/blog/7313987.sHtMl

原标题：时间精度统一业务判断修复
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.soxckf.asia/blog/0409729.sHtMl

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.soxckf.asia/blog/5038196.sHtMl

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.soxckf.asia/blog/2699725.sHtMl

原标题：golang 系统设计 rest 状态码合理使用指南
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.soxckf.asia/blog/6173465.sHtMl

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.soxckf.asia/blog/2215331.sHtMl

原标题：golang rate‑limiter 限流组件
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.soxckf.asia/blog/4656085.sHtMl

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.soxckf.asia/blog/9315085.sHtMl

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.soxckf.asia/blog/1902456.sHtMl

原标题：golang 系统设计开源项目 release 发布流程
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.soxckf.asia/blog/0835841.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Hands‑on：模板渲染引擎最小原型实现
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.soxckf.asia/blog/2394322.sHtMl

原标题：git rebase 整理提交历史实操
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.soxckf.asia/blog/8956798.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.soxckf.asia/blog/8756572.sHtMl

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.soxckf.asia/blog/7135933.sHtMl

原标题：golang yaml 解析配置加载实操
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.soxckf.asia/blog/9214273.sHtMl

原标题：开发复盘：海量日志轮转清理脚本实践
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.soxckf.asia/blog/0067393.sHtMl

原标题：容器内存扩容 OOM 被杀死修复
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.soxckf.asia/blog/1136469.sHtMl

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.soxckf.asia/blog/2860754.sHtMl

原标题：golang 优雅处理系统信号 SIGINT
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.soxckf.asia/blog/3894483.sHtMl

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.soxckf.asia/blog/4388681.sHtMl

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.soxckf.asia/blog/2661354.sHtMl

原标题：golang grpc protobuf 开发实操
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.soxckf.asia/blog/9458427.sHtMl

原标题：请求重试组件退避策略实现
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.soxckf.asia/blog/4869122.sHtMl

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.soxckf.asia/blog/4579580.sHtMl

原标题：消息队列生产消费模型入门
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.soxckf.asia/blog/2036874.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.soxckf.asia/blog/8720539.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.soxckf.asia/blog/2493952.sHtMl

原标题：golang rsa 非对称加密签名验签
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.soxckf.asia/blog/8365687.sHtMl

原标题：nestjs 拦截器过滤器管道实战
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.soxckf.asia/blog/4462654.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.soxckf.asia/blog/5228206.sHtMl

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.soxckf.asia/blog/3839427.sHtMl

原标题：golang minio 分片上传断点续传
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://book.soxckf.asia/blog/7835268.sHtMl

原标题：nodejs 集群模式多核利用实现
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.soxckf.asia/blog/9831787.sHtMl

原标题：WebSocket 聊天室实时通讯开发
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.soxckf.asia/blog/2475653.sHtMl

原标题：golang 系统设计故障演练简单思路
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.soxckf.asia/blog/4761345.sHtMl

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.soxckf.asia/blog/1732689.sHtMl

原标题：golang 系统设计 protobuf json 性能对比
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.soxckf.asia/blog/2609198.sHtMl

原标题：快速入门消息队列基础概念模型
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.soxckf.asia/blog/2074657.sHtMl

原标题：golang 系统设计分布式任务调度
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.soxckf.asia/blog/6782277.sHtMl

原标题：用户敏感数据脱敏代码实现
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.soxckf.asia/blog/3880640.sHtMl

原标题：golang 系统设计技术文档编写最佳实践
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.soxckf.asia/blog/1248287.sHtMl

原标题：golang md5 sha 加密工具实现
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.soxckf.asia/blog/0814162.sHtMl

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.soxckf.asia/blog/7450796.sHtMl

原标题：文件分片上传断点续传功能
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.soxckf.asia/blog/7481537.sHtMl

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.soxckf.asia/blog/6110415.sHtMl

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.soxckf.asia/blog/8961980.sHtMl

原标题：TCP 长连接参数优化 TIME_WAIT
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.soxckf.asia/blog/2804776.sHtMl

原标题：golang docker compose 依赖启动顺序
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.soxckf.asia/blog/2921913.sHtMl

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.soxckf.asia/blog/2247648.sHtMl

原标题：golang mysql json 字段查询使用
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.soxckf.asia/blog/9163455.sHtMl

三、实战开发｜Practice
原标题：零基础理解依赖管理与包管理器
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.soxckf.asia/blog/3769879.sHtMl

原标题：ORM 隐式慢查询问题规避
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.soxckf.asia/blog/9225077.sHtMl

原标题：golang 雪花 id 重复问题排查
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.soxckf.asia/blog/0862800.sHtMl

原标题：新手教程：如何给开源项目提交第一个PR
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.soxckf.asia/blog/9051224.sHtMl

原标题：OpenSource：开源项目贡献者协作流程规范
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.soxckf.asia/blog/7610162.sHtMl

原标题：golang 系统设计防爬虫简单策略
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.soxckf.asia/blog/6627209.sHtMl

原标题：golang 系统设计高可用服务架构梳理
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.soxckf.asia/blog/1381722.sHtMl

原标题：golang 分页查询封装通用工具
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.soxckf.asia/blog/0137789.sHtMl

原标题：语义化版本依赖管理防错乱
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.soxckf.asia/blog/5829943.sHtMl

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.soxckf.asia/blog/6989342.sHtMl

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.soxckf.asia/blog/4537751.sHtMl

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.soxckf.asia/blog/7533652.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.soxckf.asia/blog/8997514.sHtMl

原标题：Practice：实现定时任务动态启停管理接口
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.soxckf.asia/blog/8665207.sHtMl

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.soxckf.asia/blog/3388166.sHtMl

原标题：golang redis 网络超时参数调优
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.soxckf.asia/blog/5315050.sHtMl

原标题：新手向：开源项目依赖安装失败排查
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.soxckf.asia/blog/3242705.sHtMl

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.soxckf.asia/blog/5996083.sHtMl

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.soxckf.asia/blog/4135670.sHtMl

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://book.soxckf.asia/blog/8615855.sHtMl

原标题：golang mock 单元测试编写技巧
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.soxckf.asia/blog/7036893.sHtMl

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.soxckf.asia/blog/7482941.sHtMl

原标题：安全实践：请求输入校验防御恶意参数
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.soxckf.asia/blog/7130327.sHtMl

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.soxckf.asia/blog/9479573.sHtMl

原标题：部署实践：服务器时间同步chrony配置
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.soxckf.asia/blog/4164351.sHtMl

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.soxckf.asia/blog/0325508.sHtMl

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.soxckf.asia/blog/6891240.sHtMl

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.soxckf.asia/blog/3180907.sHtMl

原标题：后端大文件分片上传接口开发
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.soxckf.asia/blog/0254240.sHtMl

原标题：golang redis pipeline 原子性说明
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.soxckf.asia/blog/8835711.sHtMl

原标题：golang 系统设计本地缓存更新失效方案实现
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.soxckf.asia/blog/7493494.sHtMl

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.soxckf.asia/blog/4541614.sHtMl

原标题：数据库死锁成因规避方案
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.soxckf.asia/blog/6014780.sHtMl

原标题：golang mysql 联合索引最左匹配
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.soxckf.asia/blog/0347574.sHtMl

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.soxckf.asia/blog/8284261.sHtMl

原标题：跨库查询性能优化处理
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.soxckf.asia/blog/8687568.sHtMl

原标题：程序性能指标 CPU 内存监控
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.soxckf.asia/blog/6453095.sHtMl

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.soxckf.asia/blog/0881320.sHtMl

原标题：golang base64 编码解码实操
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.soxckf.asia/blog/4583575.sHtMl

原标题：golang redis 过期 key 监听业务
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.soxckf.asia/blog/7550676.sHtMl

四、架构设计｜Architecture
原标题：nodejs 多进程任务分发处理
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.soxckf.asia/blog/7143597.sHtMl

原标题：JWT 工具封装令牌刷新过期
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.soxckf.asia/blog/4088206.sHtMl

原标题：多环境配置中心灵活切换方案
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.soxckf.asia/blog/0575202.sHtMl

原标题：Architecture：大文件上传下载系统架构设计
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.soxckf.asia/blog/4176270.sHtMl

原标题：定时任务重复执行分布式锁
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.soxckf.asia/blog/5689713.sHtMl

原标题：golang k8s 日志收集 efk 简单架构
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.soxckf.asia/blog/2974859.sHtMl

原标题：nodejs 全局异常捕获进程防护
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.soxckf.asia/blog/7811088.sHtMl

原标题：golang 系统设计服务优雅停机完整流程
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.soxckf.asia/blog/0083162.sHtMl

原标题：golang 系统设计用户签到统计方案
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.soxckf.asia/blog/5623468.sHtMl

原标题：前端组件库按需加载性能优化
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.soxckf.asia/blog/3265504.sHtMl

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.soxckf.asia/blog/5289257.sHtMl

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.soxckf.asia/blog/7061753.sHtMl

原标题：vite 项目配置与构建提速技巧
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.soxckf.asia/blog/5390870.sHtMl

原标题：部署实践：多实例服务部署无状态改造
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.soxckf.asia/blog/1856658.sHtMl

原标题：golang rate‑limiter 限流组件
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.soxckf.asia/blog/2215717.sHtMl

原标题：Practice：实现多数据源动态切换组件实践
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.soxckf.asia/blog/2689029.sHtMl

原标题：架构思考：单体应用向微服务拆分演进路径
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.soxckf.asia/blog/0407243.sHtMl

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.soxckf.asia/blog/5988727.sHtMl

?
