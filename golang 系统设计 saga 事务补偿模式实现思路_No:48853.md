最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.cl318b.asia/arts/713885.Doc

原标题：OOMKilled 容器被杀完整排查
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.cl318b.asia/arts/995256.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.cl318b.asia/arts/609064.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.cl318b.asia/arts/672514.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.cl318b.asia/arts/117621.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.cl318b.asia/arts/181879.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.cl318b.asia/arts/307409.Doc

原标题：golang defer panic 异常处理
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.cl318b.asia/arts/850032.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.cl318b.asia/arts/102413.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.cl318b.asia/arts/484414.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.cl318b.asia/arts/418194.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.cl318b.asia/arts/303614.Doc

原标题：golang 时间时区处理避坑指南
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.cl318b.asia/arts/151326.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.cl318b.asia/arts/918957.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.cl318b.asia/arts/423930.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.cl318b.asia/arts/360261.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.cl318b.asia/arts/083390.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.cl318b.asia/arts/026699.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.cl318b.asia/arts/461814.Doc

原标题：API 大版本不兼容平滑迁移
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.cl318b.asia/arts/131638.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.cl318b.asia/arts/157815.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.cl318b.asia/arts/491322.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.cl318b.asia/arts/151138.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.cl318b.asia/arts/361807.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.cl318b.asia/arts/540772.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.cl318b.asia/arts/621369.Doc

原标题：文件编码统一随机乱码修复
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.cl318b.asia/arts/905748.Doc

原标题：定时任务重复执行分布式锁
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.cl318b.asia/arts/539390.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.cl318b.asia/arts/330953.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.cl318b.asia/arts/544177.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.cl318b.asia/arts/616639.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.cl318b.asia/arts/058284.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.cl318b.asia/arts/724886.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.cl318b.asia/arts/767813.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.cl318b.asia/arts/584858.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.cl318b.asia/arts/129139.Doc

原标题：数据库死锁成因规避方案
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.cl318b.asia/arts/202205.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.cl318b.asia/arts/055762.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.cl318b.asia/arts/228731.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.cl318b.asia/arts/977570.Doc


二、踩坑排错｜Troubleshooting
原标题：开源项目构建失败排查步骤
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.cl318b.asia/arts/614557.Doc

原标题：从零学习基础的接口请求与参数处理
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.cl318b.asia/arts/479027.Doc

原标题：代码模块化组件化拆分思路
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.cl318b.asia/arts/114174.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.cl318b.asia/arts/538177.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.cl318b.asia/arts/006480.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.cl318b.asia/arts/998639.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.cl318b.asia/arts/922139.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.cl318b.asia/arts/552400.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.cl318b.asia/arts/781770.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.cl318b.asia/arts/229576.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.cl318b.asia/arts/718900.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.cl318b.asia/arts/522650.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.cl318b.asia/arts/322933.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.cl318b.asia/arts/995149.Doc

原标题：golang mysql 避免 select * 查询
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.cl318b.asia/arts/013135.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.cl318b.asia/arts/186666.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.cl318b.asia/arts/491055.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.cl318b.asia/arts/181123.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.cl318b.asia/arts/085443.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.cl318b.asia/arts/587941.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.cl318b.asia/arts/989196.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.cl318b.asia/arts/965220.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.cl318b.asia/arts/639193.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.cl318b.asia/arts/158143.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.cl318b.asia/arts/792839.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.cl318b.asia/arts/032381.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.cl318b.asia/arts/318389.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.cl318b.asia/arts/207058.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.cl318b.asia/arts/778633.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.cl318b.asia/arts/571930.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.cl318b.asia/arts/821058.Doc

原标题：单元测试用例编写入门实操
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.cl318b.asia/arts/279418.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.cl318b.asia/arts/140731.Doc

原标题：golang etcd 分布式锁实现原理
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.cl318b.asia/arts/455484.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.cl318b.asia/arts/521814.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.cl318b.asia/arts/208833.Doc

原标题：开发环境变量配置全平台教程
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.cl318b.asia/arts/380158.Doc

原标题：nodejs 多进程任务分发处理
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.cl318b.asia/arts/380816.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.cl318b.asia/arts/936184.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.cl318b.asia/arts/768180.Doc

三、实战开发｜Practice
原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.cl318b.asia/arts/143474.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.cl318b.asia/arts/897006.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.cl318b.asia/arts/991402.Doc

原标题：空指针异常判空容错处理
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.cl318b.asia/arts/409097.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.cl318b.asia/arts/447998.Doc

原标题：Git 代码冲突正确处理方式
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.cl318b.asia/arts/782394.Doc

原标题：macOS 脚本执行权限开启
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.cl318b.asia/arts/447734.Doc

原标题：文件分片上传断点续传功能
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.cl318b.asia/arts/248679.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.cl318b.asia/arts/591570.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.cl318b.asia/arts/490537.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.cl318b.asia/arts/502299.Doc

原标题：golang etcd 配置中心简单使用
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.cl318b.asia/arts/674336.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.cl318b.asia/arts/000950.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.cl318b.asia/arts/351029.Doc

原标题：正则表达式优化 CPU 占满问题
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.cl318b.asia/arts/028957.Doc

原标题：golang mysql 存储过程简单使用
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.cl318b.asia/arts/004906.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.cl318b.asia/arts/481934.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.cl318b.asia/arts/863250.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.cl318b.asia/arts/451384.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.cl318b.asia/arts/640938.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.cl318b.asia/arts/348593.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.cl318b.asia/arts/681556.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.cl318b.asia/arts/048878.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.cl318b.asia/arts/564030.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.cl318b.asia/arts/264149.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.cl318b.asia/arts/202986.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.cl318b.asia/arts/208186.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.cl318b.asia/arts/325443.Doc

原标题：JWT 令牌过期异常处理
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.cl318b.asia/arts/640004.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.cl318b.asia/arts/094379.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.cl318b.asia/arts/905180.Doc

原标题：golang grpc protobuf 开发实操
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.cl318b.asia/arts/311607.Doc

原标题：golang 系统设计分布式会话方案对比
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.cl318b.asia/arts/236513.Doc

原标题：JSON XML 数据解析处理示例
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.cl318b.asia/arts/895078.Doc

原标题：golang 数据库慢查询监控实现
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.cl318b.asia/arts/360991.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.cl318b.asia/arts/236572.Doc

原标题：golang 系统设计内存高占用排查思路
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.cl318b.asia/arts/829302.Doc

原标题：golang k8s helm chart 简单编写
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.cl318b.asia/arts/642190.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.cl318b.asia/arts/785262.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.cl318b.asia/arts/937330.Doc

四、架构设计｜Architecture
原标题：golang k8s 命名空间资源隔离方案
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.cl318b.asia/arts/616395.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.cl318b.asia/arts/672587.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.cl318b.asia/arts/194503.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.cl318b.asia/arts/636961.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.cl318b.asia/arts/018232.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.cl318b.asia/arts/839769.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.cl318b.asia/arts/895794.Doc

原标题：golang etcd 租约 lease 过期机制
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.cl318b.asia/arts/483778.Doc

原标题：时间同步修复令牌提前过期
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.cl318b.asia/arts/855002.Doc

原标题：golang mongodb 聚合管道实操案例
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.cl318b.asia/arts/505224.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.cl318b.asia/arts/301227.Doc

原标题：线上接口超时故障排查思路
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.cl318b.asia/arts/520084.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.cl318b.asia/arts/992099.Doc

原标题：服务健康检查告警监控体系
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.cl318b.asia/arts/561835.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.cl318b.asia/arts/379216.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.cl318b.asia/arts/452169.Doc

原标题：nodejs 集群模式多核利用实现
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.cl318b.asia/arts/504983.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.cl318b.asia/arts/742609.Doc

?
