# Starry 设计文档

> Starry意指布满星星的，寓意本OS的开发学习借鉴了许多前辈的思路，并将其汇总归一为这个内核。

## 成员

陈嘉钰、郑友捷、王昱栋

## 说明

* 一个内核
* 以riscv64指令集运行
* 支持在qemu、sifive开发板等平台上运行
* 支持gcc、redis等Linux应用
* 支持编译时选择启动架构为Unikernel或者宏内核
