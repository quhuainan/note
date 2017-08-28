## 开源库知识记录

#### gson

- 使用@SerializedName注释可以将字段 序列化成自己定义的属性 

  ```java
   @SerializedName("avatar_url")    
   public final String avatarUrl;
  ```

  ​

- 使用@Expose注解可以去除该字段的序列化

  ```java
  @Expose  
  private String name;  
  ```

  ​