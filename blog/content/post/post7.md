---
title: "Xử lý ngoại lệ trong Java"
date: 2024-12-24
tags: ["Java", "Programming", "Exceptions"]
---

Xử lý ngoại lệ là một phần quan trọng trong lập trình Java. Nó giúp chương trình của bạn tiếp tục chạy mặc dù có lỗi xảy ra.

- **try-catch**: Cấu trúc cơ bản để xử lý ngoại lệ.

```java
try {
    int result = 10 / 0;  // gây ra lỗi chia cho 0
} catch (ArithmeticException e) {
    System.out.println("Lỗi: " + e.getMessage());
}