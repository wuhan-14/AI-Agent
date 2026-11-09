# Java 打卡进度表（120 天 · 共 120 项）

> 这张表只记 **Java 线**。Python 线那张在 [`打卡进度表-Python.md`](打卡进度表-Python.md)，两张各自独立打勾。
> 
> 每天只花 30 秒：做完勾一下，写一句「今天真正用上了什么」。写不出来，说明今天只是看完了视频，没动手。

## 一、阶段进度

| 阶段     | 天数          | 主线内容                                                                                                   | 已完成                          |
| ------ | ----------- | ------------------------------------------------------------------------------------------------------ | ---------------------------- |
| P1     | D1–D30      | 语法 → 数组 → 方法 → 类与封装 → 集合 → 继承/接口 → 异常 → IO                                                             | &nbsp;&nbsp;&nbsp; 1/ 30     |
| P2     | D31–D60     | 多线程/反射（了解）→ MySQL → SQL → JDBC → Maven → MyBatis → Servlet → Spring IOC/AOP → SpringMVC → SpringBoot   | &nbsp;&nbsp;&nbsp; / 30      |
| P3     | D61–D90     | Spring AI：ChatClient → Prompt → Memory → 流式 → 结构化 → Embedding → 切分 → VectorStore → Advisor → 混合检索 → 评测 | &nbsp;&nbsp;&nbsp; / 30      |
| P4     | D91–D108    | @Tool → 多工具 → Agent 循环 → MCP Server → trace → Docker/Compose → 压测 → 跨语言联调                              | &nbsp;&nbsp;&nbsp; / 18      |
| P5     | D109–D120   | 架构图 → 指标表 → 简历 → 面试题 → 系统设计 → 模拟面试 → 投递                                                                | &nbsp;&nbsp;&nbsp; / 12      |
| **合计** | **D1–D120** |                                                                                                        | **&nbsp;&nbsp;&nbsp; / 120** |
|        |             |                                                                                                        |                              |

## 二、每日打卡

| 天   | 周   | 今日主题                                  | 知识点自查（能不看资料讲清才打勾）                                                                                              | 完成   | 卡点 / 疑问 |
| --- | --- | ------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ---- | ------- |
| 1   | W1  | JDK 安装、IDEA、第一个 Java 程序               | JDK / JRE / JVM 三者关系、javac 编译与 java 运行两条命令、main 方法各部分的含义、IDEA 新建项目的目录结构                                        | [ √] |         |
| 2   | W1  | 变量、基本类型与类型转换                          | byte/short/int/long/float/double/char/boolean 与取值范围、变量声明、初始化与命名规范、自动类型提升与强制转换、int 与 Integer 的区别（装箱）            | [ ]  |         |
| 3   | W1  | 运算符与表达式                               | 算术、关系、逻辑、位运算符、自增自减与赋值运算符、三元表达式与运算符优先级、整数除法与取模的符号规则                                                             | [ ]  |         |
| 4   | W1  | Scanner 键盘录入与 if/else                 | Scanner 读整数与读整行、nextInt 后接 nextLine 的换行坑、if / else if / else 与嵌套、条件必须是 boolean，不能写 if(1)                       | [ ]  |         |
| 5   | W1  | switch 与循环入门                          | switch 的穿透与 break、Java 14+ 箭头语法与 yield、while 与 do-while 的区别、break / continue 的作用                               | [ ]  |         |
| 6   | W1  | for 循环与嵌套                             | 传统 for 的三段式执行顺序、增强 for 遍历数组与集合、嵌套循环与循环变量作用域、带标签的 break                                                         | [ ]  |         |
| 7   | W1  | Random、循环综合练习                         | Random 生成指定范围随机数、while(true) 与退出条件、循环里的输入校验、累加与计数模式                                                            | [ ]  |         |
| 8   | W2  | 数组基础与遍历                               | 数组的静态初始化与动态初始化、length 属性与下标越界、遍历、求和、求最值、数组作为方法参数与返回值                                                           | [ ]  |         |
| 9   | W2  | 数组排序、二分查找、二维数组                        | 冒泡排序的手写实现、Arrays.sort 与 binarySearch、二维数组的声明与遍历、数组拷贝 System.arraycopy                                          | [ ]  |         |
| 10  | W2  | 方法定义与调用                               | 方法的完整格式：修饰符 返回值 方法名(参数)、形参与实参、返回值、方法重载（同名不同参）、方法的内存执行流程                                                        | [ ]  |         |
| 11  | W2  | 值传递、可变参数                              | Java 只有值传递：基本类型传副本、对象传引用副本、可变参数 String... args、方法内修改对象内容会影响外部、递归的基线条件                                          | [ ]  |         |
| 12  | W2  | 类与对象、属性与方法                            | 类的定义：属性 + 行为、对象的创建与使用、成员变量与局部变量的区别、对象内存图（栈引用指向堆对象）                                                             | [ ]  |         |
| 13  | W2  | 封装与 this                              | private 的作用与封装的意义、this 指向当前对象、getter/setter 与字段校验、构造方法重载                                                       | [ ]  |         |
| 14  | W2  | 构造方法、JavaBean 标准写法                    | 构造方法的作用与重载、this(...) 调用同类构造器、JavaBean 规范：无参构造 + getter/setter、对象数组与遍历                                          | [ ]  |         |
| 15  | W3  | String 常用 API                         | 字符串不可变与常量池、length/charAt/substring/indexOf、equals 与 == 的区别、trim/replace/split/contains                         | [ ]  |         |
| 16  | W3  | StringBuilder、StringJoiner            | 循环拼接为什么慢（每次新建对象）、StringBuilder 的 append/toString、StringBuilder 与 StringBuffer 的区别、StringJoiner 的用法             | [ ]  |         |
| 17  | W3  | ArrayList 与泛型入门                       | ArrayList 的增删改查、泛型 <> 的作用、ArrayList 与数组的取舍、遍历时删除元素的坑                                                           | [ ]  |         |
| 18  | W3  | Set 家族                                | HashSet 的去重原理（hashCode + equals）、LinkedHashSet 保留插入顺序、TreeSet 自动排序、Set 的交并差                                    | [ ]  |         |
| 19  | W3  | HashMap 与 Map 接口                      | put/get/containsKey/remove、遍历 entrySet 与 keySet、computeIfAbsent 的常用场景、HashMap 无序、LinkedHashMap 保序              | [ ]  |         |
| 20  | W3  | 综合：类 + 集合 + 循环 + 输入                   | 用类建模学生、用 ArrayList 存数据、用 switch 做菜单、输入校验与异常处理                                                                  | [ ]  |         |
| 21  | W3  | static 与 final                        | static 成员属于类不属于对象、静态方法与工具类写法、final 修饰变量/方法/类、静态代码块与执行顺序                                                        | [ ]  |         |
| 22  | W4  | 继承与 super                             | extends 与单继承、super 调用父类构造与方法、方法重写与 @Override、构造器的执行顺序                                                          | [ ]  |         |
| 23  | W4  | 多态与类型转换                               | 多态的三个前提：继承、重写、父类引用指向子类、向上转型与向下转型（instanceof）、多态在方法参数中的价值、编译看左边、运行看右边                                           | [ ]  |         |
| 24  | W4  | abstract class 与 interface            | 抽象类可以有实现，接口定义契约、接口的多实现与默认方法、抽象方法必须被实现、面向接口编程的意义                                                                | [ ]  |         |
| 25  | W4  | 内部类与 Lambda                           | 成员内部类与静态内部类、匿名内部类实现接口、函数式接口与 Lambda 表达式、方法引用 :: 的写法                                                            | [ ]  |         |
| 26  | W4  | 枚举、包装类、BigDecimal                     | enum 的定义与带参枚举、枚举在 switch 中的使用、包装类的缓存与 null 拆箱、BigDecimal 做金额计算                                                 | [ ]  |         |
| 27  | W4  | 异常处理                                  | Throwable → Error / Exception 体系、受检异常与运行时异常的区别、try-catch-finally 执行顺序、throws 声明与调用方处理                          | [ ]  |         |
| 28  | W4  | 自定义异常、日志 SLF4J                        | 自定义异常的分类（业务/系统）、异常信息与错误码设计、SLF4J + Logback 基本用法、日志级别与占位符                                                       | [ ]  |         |
| 29  | W5  | File、字节流、字符流                          | File 类的路径与常用方法、字节流 FileInputStream/OutputStream、字符流 FileReader/Writer 与编码、BufferedReader 按行读                   | [ ]  |         |
| 30  | W5  | 综合：OOP + 集合 + IO + 异常                 | 分层：菜单 / 服务 / 存储、用接口抽象存储（内存/文件）、统一异常处理、代码复用与重构                                                                  | [ ]  |         |
| 31  | W5  | Thread、Runnable、线程池                   | 进程与线程的区别、Thread / Runnable / Callable、线程安全问题与 synchronized、线程池 ExecutorService                                 | [ ]  |         |
| 32  | W5  | Socket、TCP/UDP、HTTP 协议                | TCP 三次握手与 Socket 通信流程、HTTP 请求与响应结构、常用方法与状态码、Content-Type 与 JSON body                                           | [ ]  |         |
| 33  | W5  | 反射与注解                                 | Class 对象的三种获取方式、反射创建对象、调用方法、注解的定义与元注解、动态代理的作用（AOP 的基础）                                                         | [ ]  |         |
| 34  | W5  | MySQL 环境与 DDL                         | MySQL 安装与客户端连接、库、表、行、列与数据类型、建表语句与主键自增、常用约束：非空、唯一、默认、外键                                                         | [ ]  |         |
| 35  | W5  | 单表查询                                  | select 的列选择与别名、where 的条件与 like/in/between、order by 多字段排序、limit 分页                                              | [ ]  |         |
| 36  | W6  | count/sum/avg/max/min、group by        | 聚合函数与 NULL 的处理、group by 与 having、执行顺序：where → group by → having → order by、聚合结果别名                              | [ ]  |         |
| 37  | W6  | inner join / left join                | 一对一、一对多、多对多建模、inner join 与 left join 的区别、join 的 on 条件、笛卡尔积的成因                                                  | [ ]  |         |
| 38  | W6  | 事务、索引、explain                         | 事务的 ACID、begin/commit/rollback、隔离级别与脏读/幻读、索引原理与最左前缀                                                            | [ ]  |         |
| 39  | W6  | JDBC 与 JdbcTemplate 前身                | JDBC 六步：加载驱动、连接、Statement、ResultSet、关闭、PreparedStatement 与 SQL 注入、事务控制、连接池的必要性                                 | [ ]  |         |
| 40  | W6  | Maven、Druid/HikariCP                  | Maven 坐标与目录结构、依赖范围与传递依赖、生命周期与常用命令、连接池配置与参数                                                                     | [ ]  |         |
| 41  | W6  | MyBatis 基础                            | MyBatis 的作用与半自动 ORM、Mapper 接口 + XML 映射、resultType 与 resultMap、增删改查的返回值                                         | [ ]  |         |
| 42  | W6  | 动态 SQL、参数、分页                          | if/where/set/foreach 标签、多参数传递（@Param）、一对一/一对多关联映射、PageHelper 分页                                                | [ ]  |         |
| 43  | W7  | 前端三件套（了解）                             | HTML 常用标签与表单、CSS 选择器与盒模型（了解）、JS 变量、函数、事件、fetch 发请求                                                             | [ ]  |         |
| 44  | W7  | Servlet、请求响应、MVC                      | Servlet 的生命周期、request/response 的作用、转发与重定向的区别、MVC 三层各自的职责                                                       | [ ]  |         |
| 45  | W7  | Cookie/Session/JWT                    | Cookie 的存取与生命周期、Session 的原理与超时、JWT 的结构与无状态鉴权、三种方案的取舍                                                           | [ ]  |         |
| 46  | W7  | 异步请求与接口规范                             | 同步请求与异步请求的区别、JSON 交互格式、统一响应结构 code/message/data、接口版本与命名规范                                                      | [ ]  |         |
| 47  | W7  | IOC、DI、Bean                           | IOC 容器的作用、Bean 的声明与扫描、构造器注入 vs 字段注入、Bean 的作用域与生命周期                                                             | [ ]  |         |
| 48  | W7  | AOP、@Transactional                    | AOP 的切面、切点、通知、代理模式与 AOP 实现原理、@Transactional 的传播行为、事务失效的常见原因                                                    | [ ]  |         |
| 49  | W7  | SpringMVC 注解                          | @RestController 与 @RequestMapping、@PathVariable/@RequestParam/@RequestBody、返回值与 ResponseEntity、Jackson 序列化与字段名 | [ ]  |         |
| 50  | W8  | Bean Validation、@RestControllerAdvice | @Valid 与常用约束注解、嵌套对象的级联校验、MethodArgumentNotValidException、统一错误响应                                                | [ ]  |         |
| 51  | W8  | SpringBoot 核心                         | start.spring.io 生成项目、自动配置与 starter 机制、内嵌 Tomcat 与端口、启动类与包扫描范围                                                  | [ ]  |         |
| 52  | W8  | application.yml、Profile               | yml 语法与配置优先级、多环境 Profile、@ConfigurationProperties 绑定、密钥用环境变量注入                                                 | [ ]  |         |
| 53  | W8  | 日志配置、Actuator                         | Logback 配置与日志分级、MDC 加 traceId、Actuator health/metrics、日志脱敏                                                     | [ ]  |         |
| 54  | W8  | 持久层整合                                 | Spring Boot 整合 MyBatis、JPA 的实体与 Repository、分页插件、事务边界放在 Service                                                 | [ ]  |         |
| 55  | W8  | OpenAPI、MockMvc                       | springdoc 生成 Swagger UI、注解补充接口说明、MockMvc 测 Controller、测试数据库用 H2 或 Testcontainers                               | [ ]  |         |
| 56  | W8  | jar 打包、Docker 基础                      | mvn package 与可执行 jar、java -jar 启动与参数、Dockerfile 编写、镜像分层与体积优化                                                   | [ ]  |         |
| 57  | W9  | 项目实战一                                 | 分层：Controller/Service/Mapper、DTO 与实体分离、统一响应与异常、分页与条件查询                                                         | [ ]  |         |
| 58  | W9  | 项目实战二                                 | JWT 登录与拦截器、接口权限控制、MockMvc 覆盖核心流程、异常与日志                                                                         | [ ]  |         |
| 59  | W9  | 项目实战三                                 | Dockerfile 与 compose、健康检查、环境变量与密钥、启动脚本与日志                                                                      | [ ]  |         |
| 60  | W9  | 复盘：SpringBoot vs FastAPI              | 两套技术栈的对应关系、类型系统与校验的差异、生态与适用场景、代码量与开发速度                                                                         | [ ]  |         |
| 61  | W9  | LLM 基本概念                              | token 与计费方式、上下文窗口与截断、temperature/top_p 的作用、幻觉的成因与边界                                                            | [ ]  |         |
| 62  | W9  | OpenAI 兼容接口                           | API Key 与配额管理、base_url 与 model 参数、请求/响应结构、错误码与重试                                                               | [ ]  |         |
| 63  | W9  | Spring AI 接入                          | starter 依赖与自动配置、ChatClient 的构建方式、prompt/call/content 链式调用、多模型配置切换                                              | [ ]  |         |
| 64  | W10 | 提示词模板                                 | PromptTemplate 的占位符、System 与 User 消息的分工、输出格式约束、Few-shot 示例                                                     | [ ]  |         |
| 65  | W10 | ChatMemory                            | 对话历史的结构、MessageWindowChatMemory 限制条数、上下文膨胀与摘要压缩、会话隔离                                                           | [ ]  |         |
| 66  | W10 | 流式响应                                  | SSE 协议格式、Spring 的 Flux 返回流、前端 EventSource 接收、流式下的错误处理                                                          | [ ]  |         |
| 67  | W10 | entity 映射                             | response_format 与 JSON mode、.entity(Class) 映射、字段与提示词对齐、解析失败的重试                                                 | [ ]  |         |
| 68  | W10 | 成本控制                                  | 输入/输出 token 单价、max_tokens 与截断、限流与重试策略、小模型分流                                                                    | [ ]  |         |
| 69  | W10 | EmbeddingModel                        | embedding 的语义含义、维度与归一化、批量 embedding、换模型必须重算                                                                    | [ ]  |         |
| 70  | W10 | 文档读取与清洗                               | PDF 文本提取的局限、Word/HTML 解析、页眉页脚与页码清理、表格与代码块的特殊处理                                                                 | [ ]  |         |
| 71  | W11 | 切分                                    | 按字符/段落/标题切分的差异、chunk size 的取舍、overlap 的作用、元数据随 chunk 一起存                                                       | [ ]  |         |
| 72  | W11 | pgvector 建表与索引                        | CREATE EXTENSION vector、vector(n) 字段与维度、<=> 余弦距离与排序、HNSW 索引与参数                                                 | [ ]  |         |
| 73  | W11 | VectorStore                           | VectorStore 接口、add/delete/similaritySearch、initialize-schema 选项、按 docId 删除重建                                   | [ ]  |         |
| 74  | W11 | similaritySearch                      | topK 与 threshold、相似度分数的含义、检索结果的组装、召回质量的初步判断                                                                    | [ ]  |         |
| 75  | W11 | FilterExpression                      | 元数据字段设计、过滤表达式语法、先过滤再排序的顺序、权限过滤                                                                                 | [ ]  |         |
| 76  | W11 | ETL Pipeline                          | Reader → Splitter → Writer、Pipeline 的配置方式、失败重试与断点、增量更新                                                         | [ ]  |         |
| 77  | W11 | Advisor 与 RAG 调用                      | QuestionAnswerAdvisor 的作用、检索结果如何注入提示词、Advisor 顺序、自定义 Advisor                                                   | [ ]  |         |
| 78  | W12 | 引用与拒答                                 | 引用标号与来源列表、相似度阈值与拒答、拒答话术设计、越权与敏感内容                                                                              | [ ]  |         |
| 79  | W12 | 项目实战一                                 | 完整链路：上传 → 入库 → 问答、多文档与分类、基础前端页面或 Swagger、错误处理                                                                  | [ ]  |         |
| 80  | W12 | 复盘：定位瓶颈                               | 检索问题 vs 生成问题的区分、badcase 记录表、指标基线、下一步优化方向                                                                       | [ ]  |         |
| 81  | W12 | BM25 与混合检索                            | 纯向量检索的盲区（专有名词、型号）、BM25 的原理与实现、两路召回的数量控制、何时该用混合                                                                 | [ ]  |         |
| 82  | W12 | RRF 融合                                | 为什么不能直接加权分数、RRF 公式与 k 值、多路结果的截断、实现与调参                                                                          | [ ]  |         |
| 83  | W12 | rerank 接入                             | 双塔召回与交叉编码器精排、rerank 服务的调用方式、候选数量与延迟的取舍、阈值截断                                                                    | [ ]  |         |
| 84  | W12 | Query 改写                              | 用户口语与文档表述的差距、让模型生成 2-3 个改写、多查询并行与合并、改写不能丢实体                                                                    | [ ]  |         |
| 85  | W13 | 上下文压缩                                 | 塞太多片段的害处、抽取式压缩、按相关性排序后截断、引用编号的维护                                                                               | [ ]  |         |
| 86  | W13 | 评测集构建                                 | 问题类型分布（事实/比较/拒答）、标准答案与正确来源标注、难易分层、评测集的维护                                                                       | [ ]  |         |
| 87  | W13 | 评测指标                                  | Recall@k 的计算、忠实度的判定方法、P95 延迟的统计、单次成本核算                                                                         | [ ]  |         |
| 88  | W13 | 优化实验                                  | badcase 分类方法、单变量实验、实验记录表、回归验证                                                                                  | [ ]  |         |
| 89  | W13 | 项目实战二                                 | 按评测结果优化、引用与拒答完善、性能与成本、文档与演示                                                                                    | [ ]  |         |
| 90  | W13 | 阶段复盘：RAG 从能跑到可信                       | 全链路回顾：解析 → 切分 → 检索 → 生成、用指标定位瓶颈、工程取舍：召回 / 延迟 / 成本、下一步优化清单                                                      | [ ]  |         |
| 91  | W13 | 工具调用原理                                | 工具 = 名称 + 描述 + 参数 Schema、模型输出的是调用意图、执行由应用侧完成、结果以 tool 角色回填                                                     | [ ]  |         |
| 92  | W14 | 工具注册                                  | @Tool 标注与描述、.tools(new MyTools()) 注册、工具类可以是任意 Bean、@ToolParam 描述参数                                             | [ ]  |         |
| 93  | W14 | 工具编排                                  | 工具数量与选择准确率、参数类型与枚举约束、返回值结构化、工具粒度设计                                                                             | [ ]  |         |
| 94  | W14 | agent loop                            | 循环的四步：思考/调用/观察/再思考、消息追加顺序、最大轮次与超时、超步数后的降级                                                                      | [ ]  |         |
| 95  | W14 | 容错设计                                  | 可重试错误与不可重试错误、指数退避、降级返回、token 预算                                                                                | [ ]  |         |
| 96  | W14 | MCP 协议                                | MCP 的三角色：Host/Client/Server、tools/resources/prompts、stdio 与 HTTP 传输、协议解决什么问题                                   | [ ]  |         |
| 97  | W14 | MCP Server 实现                         | Server 的项目结构、工具声明与 inputSchema、鉴权与超时、日志与调试                                                                     | [ ]  |         |
| 98  | W14 | trace 设计                              | trace_id 贯穿全链路、每步记录输入输出与耗时、token 与成本统计、失败原因归类                                                                  | [ ]  |         |
| 99  | W15 | 服务治理                                  | 语义缓存、限流与熔断、按租户计量、降级策略                                                                                          | [ ]  |         |
| 100 | W15 | 复盘                                    | 成功率统计、失败分类、成本与延迟、人工兜底                                                                                          | [ ]  |         |
| 101 | W15 | Dockerfile 与镜像优化                      | Dockerfile 分层与缓存、多阶段构建、镜像体积优化、时区与字体等常见坑                                                                        | [ ]  |         |
| 102 | W15 | Docker Compose                        | services/networks/volumes、depends_on 与 healthcheck、环境变量与 .env、数据持久化                                            | [ ]  |         |
| 103 | W15 | 压测与容量                                 | 压测工具与场景设计、QPS、P95、错误率、瓶颈定位（CPU/IO/模型）、限流与降级验证                                                                  | [ ]  |         |
| 104 | W15 | 跨语言调用                                 | HTTP 调用与超时、请求幂等与重试、错误码约定、服务发现（了解）                                                                              | [ ]  |         |
| 105 | W15 | 链路追踪                                  | trace_id 透传、日志聚合、耗时分解、失败点定位                                                                                    | [ ]  |         |
| 106 | W16 | 部署与运维                                 | 部署方式（单机/容器/云）、启动脚本与守护、回滚方案、基础监控告警                                                                              | [ ]  |         |
| 107 | W16 | 项目实战三                                 | 多工具 + 多步流程、失败兜底、trace 与成本、演示脚本                                                                                 | [ ]  |         |
| 108 | W16 | 架构图与指标表                               | 架构图画法：组件 + 数据流 + 边界、指标表四列：召回 / 忠实 / 延迟 / 成本、取舍说明：为什么不用另一个方案、技术选型理由                                             | [ ]  |         |
| 109 | W16 | 阶段复盘：从项目到作品集                          | 两个项目的定位差异、哪些能讲、哪些不能讲、补齐短板、下一步计划                                                                                | [ ]  |         |
| 110 | W16 | 简历写作                                  | 简历结构与排版、项目描述的 STAR 写法、技术栈的写法、避免的坑                                                                              | [ ]  |         |
| 111 | W16 | Java 高频题                              | == 与 equals、hashCode 契约、集合的底层结构与选型、线程安全与锁、JVM 内存与 GC（了解）                                                       | [ ]  |         |
| 112 | W16 | Spring 高频题                            | IOC/DI 与 Bean 生命周期、AOP 与事务失效场景、自动配置原理、循环依赖                                                                     | [ ]  |         |
| 113 | W17 | Spring AI 高频题                         | ChatClient 与 Advisor 机制、ChatMemory 的实现与限制、结构化输出的可靠性、VectorStore 与 ETL                                          | [ ]  |         |
| 114 | W17 | RAG 高频题                               | chunk size 怎么定、召回不准怎么定位、混合检索与 rerank 的取舍、幻觉怎么控制                                                                | [ ]  |         |
| 115 | W17 | Agent 高频题                             | Function Calling 的原理、工具描述怎么写、死循环怎么防、多工具怎么路由                                                                    | [ ]  |         |
| 116 | W17 | 系统设计                                  | 需求澄清与边界、容量估算、存储与检索选型、权限与多租户                                                                                    | [ ]  |         |
| 117 | W17 | 项目讲述                                  | 3 分钟版本、10 分钟版本、追问应对、数据一致性                                                                                      | [ ]  |         |
| 118 | W17 | 基础与编码                                 | 常见手撕题：反转链表/二分/字符串、SQL 手写、并发场景题、边界处理                                                                            | [ ]  |         |
| 119 | W17 | 投递：渠道、节奏与跟踪                           | 目标公司分层、渠道：BOSS / 拉勾 / 内推 / 官网、投递节奏、跟踪表                                                                         | [ ]  |         |
| 120 | W18 | 总复盘：120 天之后怎么走                        | 能力盘点、作品集检查、求职计划、长期学习                                                                                           | [ ]  |         |

## 三、怎么用这张表

| 时机 | 动作 |
| --- | --- |
| 每天结束 | 勾「完成」；写一句今天真正写过的代码或踩过的坑 |
| 每周日 | 数一遍本周 7 天勾了几个；没勾的当天补，别拖到下周 |
| 每个阶段末（D30 / D60 / D90 / D108） | 回头抽查 3 天，合上资料讲知识点，讲不出就重做那天的练习 |

**完成率**：数本文件里 `[x]` 的个数 ÷ 120。低于 80% 不要进入下一阶段——Java 线的知识是叠加的，跳过的会在后面反复咬你。

**连续 3 天没勾**：不要补进度，直接把当天内容减半（只做「知识点自查」里第一条 + 跑通代码），先把节奏接回来。

---

[Python 线打卡表](打卡进度表-Python.md)　|　[每日计划](../每日计划/第001天.md)　|　[详细学习手册](../详细学习手册/第001天.md)　|　[每周复盘模板](../每周复盘模板.md)
