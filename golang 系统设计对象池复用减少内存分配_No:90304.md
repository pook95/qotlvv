最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计对象池复用减少内存分配
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.ajyme2.asia/arts/715107.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.ajyme2.asia/arts/306380.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.ajyme2.asia/arts/261604.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.ajyme2.asia/arts/191279.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.ajyme2.asia/arts/235709.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.ajyme2.asia/arts/429451.Doc

原标题：布隆过滤器数据高效去重实现
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.ajyme2.asia/arts/725484.Doc

原标题：golang mysql 慢查询日志开启分析
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.ajyme2.asia/arts/166501.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.ajyme2.asia/arts/427323.Doc

原标题：nodejs 事件循环机制完整讲解
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.ajyme2.asia/arts/457937.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.ajyme2.asia/arts/628085.Doc

原标题：操作系统内核版本适配服务
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.ajyme2.asia/arts/964261.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.ajyme2.asia/arts/947765.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.ajyme2.asia/arts/831632.Doc

原标题：游标分页大数据查询性能提升
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.ajyme2.asia/arts/811048.Doc

原标题：golang 系统设计大文件上传架构
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.ajyme2.asia/arts/034390.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.ajyme2.asia/arts/388170.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.ajyme2.asia/arts/623439.Doc

原标题：golang websocket 服务端开发
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.ajyme2.asia/arts/083875.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.ajyme2.asia/arts/122284.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.ajyme2.asia/arts/427254.Doc

原标题：接口请求重试容错机制实现
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.ajyme2.asia/arts/082458.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.ajyme2.asia/arts/386764.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.ajyme2.asia/arts/207665.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.ajyme2.asia/arts/746820.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.ajyme2.asia/arts/494378.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.ajyme2.asia/arts/089280.Doc

原标题：消息队列消费堆积扩容处理
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.ajyme2.asia/arts/593948.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.ajyme2.asia/arts/923202.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.ajyme2.asia/arts/865126.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.ajyme2.asia/arts/610338.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.ajyme2.asia/arts/560635.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.ajyme2.asia/arts/042971.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.ajyme2.asia/arts/843933.Doc

原标题：业务接口幂等完整落地案例
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.ajyme2.asia/arts/038127.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.ajyme2.asia/arts/420667.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.ajyme2.asia/arts/229138.Doc

原标题：分布式任务调度集群原型开发
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/836889.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.ajyme2.asia/arts/799772.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.ajyme2.asia/arts/502061.Doc


二、踩坑排错｜Troubleshooting
原标题：安全实践：SQL注入产生场景与完整防御手段
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.ajyme2.asia/arts/271772.Doc

原标题：全平台系统环境变量配置
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.ajyme2.asia/arts/788400.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.ajyme2.asia/arts/647842.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.ajyme2.asia/arts/499574.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.ajyme2.asia/arts/882518.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.ajyme2.asia/arts/764748.Doc

原标题：golang 系统设计压测指标确定与分析
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.ajyme2.asia/arts/712865.Doc

原标题：golang etcd 配置中心简单使用
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.ajyme2.asia/arts/560448.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.ajyme2.asia/arts/720484.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.ajyme2.asia/arts/637043.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.ajyme2.asia/arts/307551.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.ajyme2.asia/arts/132784.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.ajyme2.asia/arts/193217.Doc

原标题：nodejs http 服务性能调优实战
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.ajyme2.asia/arts/623637.Doc

原标题：golang k8s devops 流水线简单思路
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/931830.Doc

原标题：Git 子模块更新代码不全修复
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/403812.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.ajyme2.asia/arts/242255.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.ajyme2.asia/arts/427375.Doc

原标题：golang channel 通道并发处理
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.ajyme2.asia/arts/850081.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.ajyme2.asia/arts/729141.Doc

原标题：golang 配置热更新不重启服务
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.ajyme2.asia/arts/452812.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.ajyme2.asia/arts/468733.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.ajyme2.asia/arts/379415.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.ajyme2.asia/arts/019872.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.ajyme2.asia/arts/234234.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.ajyme2.asia/arts/141628.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.ajyme2.asia/arts/255818.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.ajyme2.asia/arts/031728.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.ajyme2.asia/arts/797606.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.ajyme2.asia/arts/874677.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.ajyme2.asia/arts/034788.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.ajyme2.asia/arts/645818.Doc

原标题：nodejs 集成测试业务流程编写
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.ajyme2.asia/arts/597602.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.ajyme2.asia/arts/283852.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/936371.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.ajyme2.asia/arts/795631.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.ajyme2.asia/arts/477070.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.ajyme2.asia/arts/302882.Doc

原标题：文件读写与异常捕获代码示例
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.ajyme2.asia/arts/047023.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.ajyme2.asia/arts/932447.Doc

三、实战开发｜Practice
原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.ajyme2.asia/arts/136684.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.ajyme2.asia/arts/428043.Doc

原标题：快速入门对象存储基础使用场景
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.ajyme2.asia/arts/340226.Doc

原标题：Git 分支切换合并删除完整操作
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.ajyme2.asia/arts/971233.Doc

原标题：后端登录鉴权模块完整开发
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.ajyme2.asia/arts/025602.Doc

原标题：golang kafka 核心概念分区副本
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.ajyme2.asia/arts/497019.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.ajyme2.asia/arts/641592.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.ajyme2.asia/arts/345635.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.ajyme2.asia/arts/259646.Doc

原标题：nodejs 多进程任务分发处理
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.ajyme2.asia/arts/869173.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.ajyme2.asia/arts/245475.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.ajyme2.asia/arts/101635.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.ajyme2.asia/arts/633964.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.ajyme2.asia/arts/259855.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.ajyme2.asia/arts/990091.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.ajyme2.asia/arts/289245.Doc

原标题：零基础理解幂等性基础概念与场景
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.ajyme2.asia/arts/325607.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.ajyme2.asia/arts/070571.Doc

原标题：JWT 令牌过期异常处理
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.ajyme2.asia/arts/708972.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.ajyme2.asia/arts/839936.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.ajyme2.asia/arts/124438.Doc

原标题：golang 配置文件多环境加载
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.ajyme2.asia/arts/150614.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.ajyme2.asia/arts/824449.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.ajyme2.asia/arts/497193.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.ajyme2.asia/arts/346654.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.ajyme2.asia/arts/119216.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.ajyme2.asia/arts/010764.Doc

原标题：接口幂等性防重复请求实现
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.ajyme2.asia/arts/796352.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.ajyme2.asia/arts/282950.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.ajyme2.asia/arts/790285.Doc

原标题：CI 持续集成自动构建流程
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.ajyme2.asia/arts/492510.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.ajyme2.asia/arts/453662.Doc

原标题：文件监控服务自动重启开发
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.ajyme2.asia/arts/303666.Doc

原标题：golang html 模板渲染简单示例
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.ajyme2.asia/arts/297629.Doc

原标题：不必要字符转义关闭业务异常
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.ajyme2.asia/arts/093703.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/349292.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.ajyme2.asia/arts/906718.Doc

原标题：nodejs http 服务性能调优实战
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.ajyme2.asia/arts/544212.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.ajyme2.asia/arts/312680.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.ajyme2.asia/arts/863350.Doc

四、架构设计｜Architecture
原标题：提交第一个开源 PR 完整流程
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/527385.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.ajyme2.asia/arts/514851.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.ajyme2.asia/arts/793820.Doc

原标题：Docker 网络模式容器互通设置
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.ajyme2.asia/arts/575512.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.ajyme2.asia/arts/336730.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.ajyme2.asia/arts/208704.Doc

原标题：全量回归测试提升代码质量
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.ajyme2.asia/arts/191399.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/588546.Doc

原标题：服务启动依赖顺序配置正确
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.ajyme2.asia/arts/082287.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.ajyme2.asia/arts/159149.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.ajyme2.asia/arts/082272.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.ajyme2.asia/arts/811933.Doc

原标题：浏览器缓存强制刷新方案
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.ajyme2.asia/arts/672636.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.ajyme2.asia/arts/641854.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.ajyme2.asia/arts/296779.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.ajyme2.asia/arts/070291.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.ajyme2.asia/arts/539247.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.ajyme2.asia/arts/832903.Doc

?
