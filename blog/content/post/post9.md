---
title: "Làm việc với ArrayList trong Java"
date: 2024-12-22
tags: ["Java", "Programming", "ArrayList"]
---

`ArrayList` là một trong những lớp của Java cung cấp một cách tiếp cận động đối với mảng. Nó có thể thay đổi kích thước khi bạn thêm hoặc xóa phần tử.

- **Khởi tạo ArrayList**:

```java
import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>();
        list.add("Java");
        list.add("Python");
        list.add("JavaScript");
        
        System.out.println(list);
    }
}