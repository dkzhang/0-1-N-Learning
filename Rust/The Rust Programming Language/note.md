[The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html)



# Introduction

Rust语言帮助你编写更快、更可靠的软件。高层级的人类工程学和低层级的控制，在很多编程语言中是冲突的，而Rust则向这种冲突发起了挑战。通过平衡强大的技术能力和出色的开发人员体验，Rust可以让你控制底层的细节（例如内存使用）的同时，避免传统编程语言进行此类控制所带来的麻烦。



**各章概览**

Chapter 1：如何安装Rust，如何编写Hello World，如何使用Cargo，Rust的包管理、构建工具

Chapter 2：介绍Rust语言，基本概念，后续章节则展开细节论述

Chapter 3：介绍Rust跟其他编程语言类似的一些通用特性

Chapter 4：介绍Rust的所有权系统

Chapter 5：struct和methods

Chapter 6：enum，match表达式，if let控制流

Chapter 7：Rust的module模块系统，用于组织管理代码和API接口的隐私规则

Chapter 8：标准库提供的一些collection数据类型，包括vector、string、hash map

Chapter 9：Rust的error-handling哲学和技术

Chapter 10：



# 1. Getting Started



## 1.2 Hello, World!

```rust
// main.rs

fn main() {
    println!("Hello, world!");
}
```



# 2. Programming a Guessing Game



```toml
# Cargo.toml

[package]
name = "hello_cargo"
version = "0.1.0"
edition = "2021"

[dependencies]
```

