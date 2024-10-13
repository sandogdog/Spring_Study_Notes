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
