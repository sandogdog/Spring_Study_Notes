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
