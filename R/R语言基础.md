# R语言基础

## 1. R语言基础中的基础

1. 查看数据的数据类型可以使用class()函数

## 2. Vector 向量

1. 向量的创建方法：使用`c()`函数来进行聚合，函数中的每一项中间都用逗号分隔

   ```R
   numeric_vector <- c(1, 2, 3)
   character_vector <- c("a", "b", "c")
   ```

2. 通过`names()`为向量的每一个元素起名

   ```R
   some_vector <- c("John Doe", "poker player")
   names(some_vector) <- c("Name", "Profession")
   ```

3. 计算vector中的数值类型元素之和

   ```R
   # 用c()函数创建一个向量数据类型
   poker_vector <- c(140, -50, 20, -120, 240)
   total_poker <- sum(poker_vector)
   ```

