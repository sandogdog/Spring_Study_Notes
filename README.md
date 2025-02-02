加油学习spring框架。

---

#### 1.@Transactional 是 Spring 框架中的注解，用于声明式地管理事务。它的作用是自动处理数据库操作的事务逻辑，即确保方法或类中的一系列数据库操作（如增删改）在一个事务中执行，要么全部成功提交（commit），要么全部回滚（rollback），以保证数据的一致性和完整性。

---

#### 2.Lombok 提供了一个方便的注解 @Slf4j，它会自动生成 log 对象，无需手动创建。

---

#### 3.Spring Boot 通常只需要一个配置文件，它会自动加载 application.yml 或 application.properties。选择一个配置文件并在其中完成所有配置，项目会根据这个文件进行配置解析。常见的配置文件有两种：

1)application.properties：常见于简单的项目或更喜欢用属性-值对的配置方式。

2)application.yml：YAML 格式更简洁和层次化，适合更复杂的配置。

<br>

Spring Boot 自动处理加载配置文件的顺序。如果 application.yml 和 application.properties 同时存在并且有重复配置，可能会产生意外行为。所以一般建议选择其中一个进行管理。

---

### 4.Spring中的IoC
![image](https://github.com/user-attachments/assets/cf43e102-a301-461b-ac0d-345618d04157)

![image](https://github.com/user-attachments/assets/e40c1ec8-566e-4485-b462-80e531f08e5f)

![image](https://github.com/user-attachments/assets/03ffb5ea-7b8c-40c8-8174-2c8c0ddfb379)

---

# 5.单例bean是线程安全吗

![image](https://github.com/user-attachments/assets/210caa1e-2fb9-409e-aaa8-e05a98105154)

![image](https://github.com/user-attachments/assets/e8ecc4d6-75d1-4206-a1f8-fb10220b577e)

![image](https://github.com/user-attachments/assets/915e1d3c-a32e-4bde-bd5a-aac9d632ad70)

![image](https://github.com/user-attachments/assets/db6e06ab-560b-42d7-93ee-de3d68a96a4f)

---

# 6.AOP相关面试题

![image](https://github.com/user-attachments/assets/5c328c04-e349-4537-bcaa-f0a267a1b17b)

![image](https://github.com/user-attachments/assets/7be081f2-1c98-4412-8c79-3be7df3ea3d7)

![image](https://github.com/user-attachments/assets/cf0fb2ec-6dba-4f55-919b-5909497e77b8)

![image](https://github.com/user-attachments/assets/d1e025db-8285-4370-be54-a70e4c378e5c)

![image](https://github.com/user-attachments/assets/24076882-92ff-446e-a0c7-6a73654ba886)

---

# 7.事务失效的场景

![image](https://github.com/user-attachments/assets/d34d8628-6368-4322-a548-d07099866006)

![image](https://github.com/user-attachments/assets/70795823-ba6f-4859-af86-3576efde6e5a)

![image](https://github.com/user-attachments/assets/e9f983ea-4706-4352-925c-e0e0ee939dd3)

![image](https://github.com/user-attachments/assets/569100fd-9c58-44f5-a2b8-f7917f8ae9f6)

---

# 8.bean的生命周期

![image](https://github.com/user-attachments/assets/195d251a-ca60-4d55-b308-f627168a7bad)

![image](https://github.com/user-attachments/assets/83ac436f-4a98-4770-9377-aae785e6ee6b)

![image](https://github.com/user-attachments/assets/0a659291-deef-4255-b013-4a894293a362)

---

# 9.bean的循环依赖（循环引用）

![image](https://github.com/user-attachments/assets/ee0dd411-ab45-4769-8195-c166132acb1a)

![image](https://github.com/user-attachments/assets/04311cfc-f014-4f8c-aa2a-fd50c67702c6)

![image](https://github.com/user-attachments/assets/6d0829f6-783f-49cc-ae36-55c568a6c3e5)

![image](https://github.com/user-attachments/assets/150c577b-7b96-411a-9f19-9b1325c7151a)

![image](https://github.com/user-attachments/assets/f20dc1f6-88a4-4dcd-8a64-f62eb12e7097)

![image](https://github.com/user-attachments/assets/69cf2454-823c-41ff-9c6e-1df245fec68d)

![image](https://github.com/user-attachments/assets/4ca206d0-d02d-4b56-b507-f37638c52d14)

![image](https://github.com/user-attachments/assets/69b0bdc1-0588-4517-aa47-524589a8763c)

![image](https://github.com/user-attachments/assets/d13c6770-084f-45d0-8621-81ccbcceaac5)

---

# 10.Springmvc执行流程

![image](https://github.com/user-attachments/assets/354c2e23-420c-475f-bf64-9f701471efbd)

![image](https://github.com/user-attachments/assets/29d9640d-793a-4535-8f14-a4e388a5d063)

![image](https://github.com/user-attachments/assets/5a4a0b21-f203-4f72-8a49-ae96a7fdf3b2)

![image](https://github.com/user-attachments/assets/5dc7c171-4e88-4038-b5a0-861a0e59333c)

---

# 11.SpringBoot自动配置原理

![image](https://github.com/user-attachments/assets/99a87059-686c-4275-98ca-2203f2be1992)

![image](https://github.com/user-attachments/assets/39ec1ad5-815f-4b2c-984b-1e3af378e375)

---

# 12.spring框架常见的注解（spring，springmvc，springboot）

![image](https://github.com/user-attachments/assets/ebb7b2ac-af88-49b4-9f93-01fd8ec74265)

![image](https://github.com/user-attachments/assets/d003660a-58e3-4969-95ee-85d4dbb41037)

![image](https://github.com/user-attachments/assets/0ede741c-985a-43b0-8949-9490c85b7a3d)

---

# 13.@ControllerAdvice 的作用

全局异常处理：统一处理应用程序中的所有控制器的异常。通过定义一个 @ExceptionHandler 方法，捕获指定的异常并进行处理。

全局数据绑定：使用 @ModelAttribute 进行数据绑定，给所有控制器的方法提供公共的模型数据。

全局初始化绑定：通过 @InitBinder 进行表单数据绑定，处理请求数据的预处理。

---

# 14.微服务结构

![image](https://github.com/user-attachments/assets/0fef9d73-dd8e-42b1-ad1b-dfd20c77e280)

---

# 15.server.port=${server.port:51701}

在Spring Boot中，server.port=${server.port:51701}这种写法是不正确的，原因在于它会导致循环引用。让我们来详细分析一下为什么会出现这个问题，以及为什么修改后可以解决。
1. 循环引用问题
server.port=${server.port:51701}的含义是：
尝试从环境变量或配置文件中读取server.port的值。
如果server.port没有被设置，则使用默认值51701。
然而，这里的问题是**server.port的值依赖于它自己**。Spring的占位符解析机制会尝试解析${server.port:51701}，但解析过程中会发现server.port的值尚未确定，因为它还在等待解析。这就形成了一个循环引用，导致Spring无法正确解析该值。

---

# 16.### **@Async 注解详解**

在 Spring 中，`@Async` 注解用于将方法标记为异步执行，使得方法调用不会阻塞主线程，而是提交到线程池中执行。以下是 `@Async` 的详细使用说明和核心要点：

---

**1. 启用异步支持**
在 Spring Boot 中，需通过 `@EnableAsync` 开启异步功能：
```java
@Configuration
@EnableAsync
public class AsyncConfig {
}
```

**2. 基本使用**
- **无返回值方法**：直接使用 `@Async`。
  ```java
  @Service
  public class EmailService {
      @Async
      public void sendEmail(String to) {
          // 模拟耗时操作
      }
  }
  ```
- **有返回值方法**：返回 `Future` 或 `CompletableFuture`。
  ```java
  @Async
  public CompletableFuture<String> fetchData() {
      return CompletableFuture.completedFuture("Data loaded");
  }
  ```

**3. 线程池配置**
Spring 默认使用 `SimpleAsyncTaskExecutor`（非池化，每次新建线程），但推荐自定义线程池。

**方式 1：实现 `AsyncConfigurer` 接口**
```java
@Configuration
@EnableAsync
public class AsyncConfig implements AsyncConfigurer {
    @Override
    public Executor getAsyncExecutor() {
        ThreadPoolTaskExecutor executor = new ThreadPoolTaskExecutor();
        executor.setCorePoolSize(5);     // 核心线程数
        executor.setMaxPoolSize(10);     // 最大线程数
        executor.setQueueCapacity(100);  // 队列容量
        executor.setThreadNamePrefix("Async-");
        executor.initialize();
        return executor;
    }

    @Override
    public AsyncUncaughtExceptionHandler getAsyncUncaughtExceptionHandler() {
        return new CustomAsyncExceptionHandler();
    }
}
```

**方式 2：直接定义 `TaskExecutor` Bean**
```java
@Bean(name = "customExecutor")
public Executor customTaskExecutor() {
    ThreadPoolTaskExecutor executor = new ThreadPoolTaskExecutor();
    executor.setCorePoolSize(3);
    executor.setMaxPoolSize(5);
    return executor;
}

// 使用指定线程池
@Async("customExecutor")
public void processTask() { /* ... */ }
```

---

**4. 注意事项**
- **方法可见性**：`@Async` 方法必须是 `public`，否则异步失效。
- **同类调用**：同一个类内部调用 `@Async` 方法会绕过代理，导致异步失效。
- **异常处理**：
  - 默认异常不传播到调用线程，需通过 `AsyncUncaughtExceptionHandler` 处理。
  ```java
  public class CustomAsyncExceptionHandler implements AsyncUncaughtExceptionHandler {
      @Override
      public void handleUncaughtException(Throwable ex, Method method, Object... params) {
          // 记录异常日志或发送告警
      }
  }
  ```
- **事务管理**：异步方法中的数据库操作默认不在事务上下文中：
  ```java
  @Async
  @Transactional(propagation = Propagation.REQUIRES_NEW)
  public void asyncWithTransaction() { /* ... */ }
  ```

**5. 常见场景**
- **HTTP 请求非阻塞化**：将耗时操作（如文件处理、第三方调用）异步执行，快速释放 Tomcat 线程。
- **批量任务并行处理**：拆分任务并行执行，提升吞吐量。
  ```java
  List<CompletableFuture<Void>> futures = dataList.stream()
      .map(data -> CompletableFuture.runAsync(() -> process(data), executor))
      .collect(Collectors.toList());
  CompletableFuture.allOf(futures.toArray(new CompletableFuture[0])).join();
  ```
- **事件监听异步化**：结合 `@EventListener` 异步响应事件。
  ```java
  @EventListener
  @Async
  public void handleOrderEvent(OrderEvent event) {
      // 异步处理事件
  }
  ```

**6. 性能调优建议**
- **合理设置线程池参数**：
  - 计算密集型任务：核心线程数 ≈ CPU 核心数。
  - IO 密集型任务：核心线程数可适当增大（如 2 × CPU 核心数）。
- **监控线程池状态**：
  - 使用 Spring Boot Actuator 的 `/actuator/metrics` 端点监控线程池活跃线程数、队列大小等。
  - 自定义监控：通过 `ThreadPoolTaskExecutor` 的 `getThreadPoolExecutor()` 获取底层线程池统计信息。

**7. 典型问题排查**
- **异步未生效**：
  - 检查是否添加了 `@EnableAsync`。
  - 确保调用方不是同类中的其他方法。
  - 确认方法是 `public` 的。
- **线程池资源耗尽**：
  - 调整 `maxPoolSize` 和 `queueCapacity`。
  - 设置合理的拒绝策略（如 `ThreadPoolExecutor.CallerRunsPolicy`）。
- **事务不生效**：
  - 在异步方法上显式添加 `@Transactional`。

**总结**
`@Async` 是 Spring 提供的轻量级异步工具，能显著提升应用吞吐量和响应速度，但需注意线程池配置、事务管理及异常处理。合理使用时，建议结合业务场景定制线程池，并配合监控确保系统稳定。
