---
title: "Truyền API trong Java"
date: 2024-12-23
tags: ["Java", "Programming", "Stream API"]
---

Truyền API trong Java là một công cụ mạnh mẽ để xử lý các tập dữ liệu lớn theo cách hàm, hỗ trợ các thao tác như lọc, sắp xếp, và chuyển đổi mà không thay đổi dữ liệu gốc.

- **Khởi tạo Stream từ Collection**:

```java
import java.util.Arrays;
import java.util.List;

public class Main {
    public static void main(String[] args) {
        List<String> languages = Arrays.asList("Java", "Python", "C++", "JavaScript");
        
        languages.stream()
                 .filter(language -> language.startsWith("J"))
                 .forEach(System.out::println);
    }
}