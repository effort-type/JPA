# JPA
JPA 예시

---
# [개발환경]
+ IDE : IntelliJ IDEA
+ JDK : zulu 11
+ OS : Window
+ DB : H2 (version: 1.4.200)
---
# [Table]
```sql
create table Member (
   id bigint not null,
   name varchar (255),
   primary key (id)
);
```