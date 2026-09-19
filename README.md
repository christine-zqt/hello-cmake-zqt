# hello_cmake

## 项目简介

这是 RoboMaster 算法组新生培训的 Hello CMake 项目。

该项目使用 C++ 编写，通过 CMake 完成构建，并使用 Git 进行版本管理。

## 环境

- Ubuntu 22.04 LTS
- GCC
- CMake
- Git

## 目录结构
```test
hello_cmake/
├── CMakeLists.txt
├── README.md
├── .gitignore
├── images/
│ └── success.png
└── src/
  └── main.cpp
```
## 构建步骤

进入项目根目录：
```bash
cd hello_cmake
```

生成构建文件：
```bash
cmake -S . -B build
```

编译：
```bash
cmake --build build
```

## 运行结果

运行：
```bash
./build/hello
```

输出：
```test
Hello, RoboMaster!
```

## 作者与日期
```test
姓名：张绮婷
学号：2264423010
完成日期：9月19日
```