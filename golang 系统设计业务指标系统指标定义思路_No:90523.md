最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计业务指标系统指标定义思路
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.yxdzuc.asia/arts/537187.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.yxdzuc.asia/arts/808134.Doc

原标题：golang 系统设计接口幂等架构设计
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.yxdzuc.asia/arts/571688.Doc

原标题：网关集成鉴权限流日志一体化
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.yxdzuc.asia/arts/045028.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.yxdzuc.asia/arts/209474.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.yxdzuc.asia/arts/600651.Doc

原标题：内网测试服务搭建团队调试
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.yxdzuc.asia/arts/147690.Doc

原标题：golang k8s ingress 路由域名转发
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.yxdzuc.asia/arts/392094.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.yxdzuc.asia/arts/672799.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.yxdzuc.asia/arts/077700.Doc

原标题：golang 文件上传下载接口开发
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/752656.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.yxdzuc.asia/arts/199062.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.yxdzuc.asia/arts/579832.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.yxdzuc.asia/arts/120533.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.yxdzuc.asia/arts/025206.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.yxdzuc.asia/arts/718404.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.yxdzuc.asia/arts/404470.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.yxdzuc.asia/arts/266133.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.yxdzuc.asia/arts/096322.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.yxdzuc.asia/arts/903709.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.yxdzuc.asia/arts/280287.Doc

原标题：golang 项目 makefile 脚本编写
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.yxdzuc.asia/arts/152551.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.yxdzuc.asia/arts/398603.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.yxdzuc.asia/arts/051294.Doc

原标题：golang 文件上传下载接口开发
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.yxdzuc.asia/arts/541782.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.yxdzuc.asia/arts/460295.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.yxdzuc.asia/arts/981663.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.yxdzuc.asia/arts/715096.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.yxdzuc.asia/arts/268532.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.yxdzuc.asia/arts/182709.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.yxdzuc.asia/arts/344063.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.yxdzuc.asia/arts/284393.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/454798.Doc

原标题：golang gin 框架接口开发实战
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.yxdzuc.asia/arts/576098.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.yxdzuc.asia/arts/398392.Doc

原标题：golang context 上下文传参讲解
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.yxdzuc.asia/arts/864039.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.yxdzuc.asia/arts/719476.Doc

原标题：Git LFS 大文件推送失败解决
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.yxdzuc.asia/arts/291339.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.yxdzuc.asia/arts/844744.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.yxdzuc.asia/arts/026658.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 commit 提交规范约定
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.yxdzuc.asia/arts/638081.Doc

原标题：跨平台 uniapp 多端开发实操
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/190328.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.yxdzuc.asia/arts/780982.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.yxdzuc.asia/arts/274211.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.yxdzuc.asia/arts/266263.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.yxdzuc.asia/arts/076271.Doc

原标题：golang 文件上传下载接口开发
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.yxdzuc.asia/arts/452702.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.yxdzuc.asia/arts/664627.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.yxdzuc.asia/arts/683787.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.yxdzuc.asia/arts/770449.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.yxdzuc.asia/arts/598624.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.yxdzuc.asia/arts/125431.Doc

原标题：golang redis 地理位置 geo 使用
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.yxdzuc.asia/arts/938008.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.yxdzuc.asia/arts/775693.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.yxdzuc.asia/arts/449704.Doc

原标题：线上接口超时故障排查思路
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.yxdzuc.asia/arts/126264.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.yxdzuc.asia/arts/331389.Doc

原标题：golang redis zset 排行榜业务实现
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.yxdzuc.asia/arts/038814.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.yxdzuc.asia/arts/813298.Doc

原标题：nodejs 日志轮转生产环境配置
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.yxdzuc.asia/arts/217704.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.yxdzuc.asia/arts/998140.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.yxdzuc.asia/arts/405659.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.yxdzuc.asia/arts/569325.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.yxdzuc.asia/arts/123343.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/466791.Doc

原标题：GraphQL 接口查询优化实操
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.yxdzuc.asia/arts/018735.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.yxdzuc.asia/arts/504702.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.yxdzuc.asia/arts/203883.Doc

原标题：golang k8s 监控 prometheus 部署
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.yxdzuc.asia/arts/404319.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.yxdzuc.asia/arts/525368.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.yxdzuc.asia/arts/055681.Doc

原标题：新手指南：本地多版本环境共存配置
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.yxdzuc.asia/arts/126809.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.yxdzuc.asia/arts/741927.Doc

原标题：golang gorm 批量插入性能调优
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.yxdzuc.asia/arts/107941.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.yxdzuc.asia/arts/337253.Doc

原标题：golang 项目 docker compose 本地调试
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.yxdzuc.asia/arts/710106.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.yxdzuc.asia/arts/263001.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.yxdzuc.asia/arts/344208.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.yxdzuc.asia/arts/165702.Doc

原标题：缓存过期策略优化防业务故障
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/593105.Doc

三、实战开发｜Practice
原标题：git rebase 整理提交历史实操
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.yxdzuc.asia/arts/309953.Doc

原标题：golang mysql 索引失效常见场景
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.yxdzuc.asia/arts/977181.Doc

原标题：golang 静态文件服务搭建教程
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.yxdzuc.asia/arts/600894.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.yxdzuc.asia/arts/044738.Doc

原标题：golang 配置热更新不重启服务
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.yxdzuc.asia/arts/156601.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.yxdzuc.asia/arts/528200.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.yxdzuc.asia/arts/598500.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.yxdzuc.asia/arts/179973.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.yxdzuc.asia/arts/695485.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.yxdzuc.asia/arts/956194.Doc

原标题：CLI 工具进度条交互效果开发
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.yxdzuc.asia/arts/884869.Doc

原标题：golang yaml 解析配置加载实操
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.yxdzuc.asia/arts/304643.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.yxdzuc.asia/arts/011935.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.yxdzuc.asia/arts/227077.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/226906.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/209663.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.yxdzuc.asia/arts/130017.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.yxdzuc.asia/arts/452675.Doc

原标题：布隆过滤器误判问题修正
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.yxdzuc.asia/arts/379266.Doc

原标题：文件读写与异常捕获代码示例
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.yxdzuc.asia/arts/538335.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.yxdzuc.asia/arts/048889.Doc

原标题：Performance：JSON序列化性能优化实践
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.yxdzuc.asia/arts/121501.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.yxdzuc.asia/arts/236693.Doc

原标题：系统字符集统一乱码修复
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.yxdzuc.asia/arts/759816.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.yxdzuc.asia/arts/884124.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.yxdzuc.asia/arts/077007.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.yxdzuc.asia/arts/693316.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.yxdzuc.asia/arts/684600.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.yxdzuc.asia/arts/374193.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.yxdzuc.asia/arts/074836.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/784932.Doc

原标题：浏览器缓存强制刷新方案
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.yxdzuc.asia/arts/999808.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.yxdzuc.asia/arts/718512.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.yxdzuc.asia/arts/086083.Doc

原标题：数据库排序规则统一结果一致
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.yxdzuc.asia/arts/637135.Doc

原标题：多套环境灵活切换配置方案
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.yxdzuc.asia/arts/826767.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.yxdzuc.asia/arts/470033.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/317255.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/428653.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.yxdzuc.asia/arts/460041.Doc

四、架构设计｜Architecture
原标题：golang docker compose 部署 minio
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.yxdzuc.asia/arts/411708.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.yxdzuc.asia/arts/122527.Doc

原标题：消息队列重复消费业务处理
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.yxdzuc.asia/arts/337414.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.yxdzuc.asia/arts/548143.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.yxdzuc.asia/arts/614252.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.yxdzuc.asia/arts/573941.Doc

原标题：golang 分库分表简单路由实现
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.yxdzuc.asia/arts/790288.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.yxdzuc.asia/arts/918108.Doc

原标题：git stash 代码暂存切换分支
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/670449.Doc

原标题：golang redis 缓存击穿防护实现
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.yxdzuc.asia/arts/122574.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.yxdzuc.asia/arts/759926.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.yxdzuc.asia/arts/230313.Doc

原标题：express 请求参数校验处理
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.yxdzuc.asia/arts/241368.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/230622.Doc

原标题：正则表达式文本处理实战案例
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.yxdzuc.asia/arts/598111.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.yxdzuc.asia/arts/941479.Doc

原标题：golang redis 布隆过滤器安装使用
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.yxdzuc.asia/arts/898802.Doc

原标题：golang gorm 批量插入性能调优
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.yxdzuc.asia/arts/115533.Doc

?
