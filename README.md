# The_Notes_of_Spring
加油学习spirng框架。

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
