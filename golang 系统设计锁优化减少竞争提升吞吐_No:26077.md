最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/237706.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.mljc3b.asia/arts/673957.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.mljc3b.asia/arts/782630.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.mljc3b.asia/arts/308369.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.mljc3b.asia/arts/304777.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/677298.Doc

原标题：echarts 大数据渲染性能调优
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.mljc3b.asia/arts/746455.Doc

原标题：golang yaml 解析配置加载实操
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.mljc3b.asia/arts/245857.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.mljc3b.asia/arts/678175.Doc

原标题：Docker Compose 一键搭建本地栈
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/590256.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.mljc3b.asia/arts/696105.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.mljc3b.asia/arts/604934.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.mljc3b.asia/arts/901209.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.mljc3b.asia/arts/604099.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.mljc3b.asia/arts/180921.Doc

原标题：golang mysql json 字段查询使用
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.mljc3b.asia/arts/441038.Doc

原标题：golang kafka 同步异步消费对比
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.mljc3b.asia/arts/134444.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.mljc3b.asia/arts/996868.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.mljc3b.asia/arts/557714.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.mljc3b.asia/arts/568395.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.mljc3b.asia/arts/363335.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.mljc3b.asia/arts/108510.Doc

原标题：接口请求重试容错机制实现
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/423941.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.mljc3b.asia/arts/003724.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.mljc3b.asia/arts/889507.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.mljc3b.asia/arts/497609.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.mljc3b.asia/arts/607497.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/926668.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.mljc3b.asia/arts/157391.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.mljc3b.asia/arts/741918.Doc

原标题：新手参与开源社区贡献指南
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.mljc3b.asia/arts/156832.Doc

原标题：nodejs http 服务性能调优实战
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.mljc3b.asia/arts/548655.Doc

原标题：包管理器依赖缓存清理
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.mljc3b.asia/arts/058439.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/636238.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.mljc3b.asia/arts/611300.Doc

原标题：Redis 分布式锁高并发安全实现
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/663529.Doc

原标题：数据库排序规则统一结果一致
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.mljc3b.asia/arts/886840.Doc

原标题：css 变量主题切换方案实现
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/451344.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.mljc3b.asia/arts/778666.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/322413.Doc


二、踩坑排错｜Troubleshooting
原标题：Hands‑on：简易事件驱动架构原型开发
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.mljc3b.asia/arts/118981.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/500588.Doc

原标题：零基础理解读写分离基础思想
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.mljc3b.asia/arts/344844.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/034655.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.mljc3b.asia/arts/533308.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.mljc3b.asia/arts/152622.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.mljc3b.asia/arts/123055.Doc

原标题：golang 优雅处理 http 超时设置
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.mljc3b.asia/arts/190971.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.mljc3b.asia/arts/071522.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/822773.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/187886.Doc

原标题：站内邮件消息通知功能开发
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/869704.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/185327.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.mljc3b.asia/arts/868173.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/389139.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.mljc3b.asia/arts/423292.Doc

原标题：golang excel 简单读写操作示例
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.mljc3b.asia/arts/207929.Doc

原标题：golang 链路追踪简易实现方案
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/641162.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.mljc3b.asia/arts/459118.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.mljc3b.asia/arts/438957.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.mljc3b.asia/arts/867766.Doc

原标题：热更新开发环境配置教程
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.mljc3b.asia/arts/456903.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.mljc3b.asia/arts/851369.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/331465.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.mljc3b.asia/arts/553544.Doc

原标题：golang 项目目录分层规范设计
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.mljc3b.asia/arts/008691.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/903847.Doc

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/759541.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.mljc3b.asia/arts/318702.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.mljc3b.asia/arts/615587.Doc

原标题：动态定时任务业务调度实现
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.mljc3b.asia/arts/938441.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/318306.Doc

原标题：开源项目构建失败排查步骤
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.mljc3b.asia/arts/397695.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.mljc3b.asia/arts/675440.Doc

原标题：系统文件描述符上限调大
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/451099.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.mljc3b.asia/arts/299023.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.mljc3b.asia/arts/371695.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.mljc3b.asia/arts/018185.Doc

原标题：消息消费重试次数限制防爆炸
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.mljc3b.asia/arts/633592.Doc

原标题：golang github actions 发布 release 包
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.mljc3b.asia/arts/345404.Doc

三、实战开发｜Practice
原标题：golang redis 主从复制哨兵原理
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/778097.Doc

原标题：端口占用释放资源重启服务
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.mljc3b.asia/arts/390777.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/888188.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.mljc3b.asia/arts/379537.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/318465.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.mljc3b.asia/arts/781548.Doc

原标题：golang md5 sha 加密工具实现
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.mljc3b.asia/arts/316951.Doc

原标题：golang redis 缓存预热实现思路
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.mljc3b.asia/arts/902584.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/900514.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.mljc3b.asia/arts/610230.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.mljc3b.asia/arts/599855.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.mljc3b.asia/arts/413273.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/823177.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.mljc3b.asia/arts/384478.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/518339.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.mljc3b.asia/arts/726277.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.mljc3b.asia/arts/961569.Doc

原标题：golang docker compose 环境变量
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.mljc3b.asia/arts/133279.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.mljc3b.asia/arts/360170.Doc

原标题：语义化版本依赖管理防错乱
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/962280.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/310995.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.mljc3b.asia/arts/783825.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/278771.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.mljc3b.asia/arts/188996.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.mljc3b.asia/arts/534639.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.mljc3b.asia/arts/084377.Doc

原标题：golang 系统设计文件存储选型对比
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.mljc3b.asia/arts/456896.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.mljc3b.asia/arts/100671.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.mljc3b.asia/arts/766417.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.mljc3b.asia/arts/999888.Doc

原标题：前端权限路由动态生成实现
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.mljc3b.asia/arts/482400.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.mljc3b.asia/arts/496875.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/418665.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.mljc3b.asia/arts/679144.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.mljc3b.asia/arts/047295.Doc

原标题：golang 日志 zap 结构化日志实践
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.mljc3b.asia/arts/489558.Doc

原标题：DNS TTL 配置域名切换生效
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.mljc3b.asia/arts/752266.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/566187.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/825411.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.mljc3b.asia/arts/560906.Doc

四、架构设计｜Architecture
原标题：开发复盘：统一错误码体系设计落地实践
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/266221.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/729411.Doc

原标题：热更新开发环境配置教程
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.mljc3b.asia/arts/776172.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/967927.Doc

原标题：gitignore 文件编写过滤规则
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/903852.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.mljc3b.asia/arts/277306.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.mljc3b.asia/arts/755727.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/158922.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.mljc3b.asia/arts/290296.Doc

原标题：golang 系统设计最小权限原则落地实践
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/085914.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/859663.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.mljc3b.asia/arts/749526.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.mljc3b.asia/arts/039747.Doc

原标题：golang 系统设计分布式事务几种方案
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.mljc3b.asia/arts/865892.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/797158.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/822387.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/226668.Doc

原标题：快速入门消息通知简单实现方案
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/369075.Doc

?
