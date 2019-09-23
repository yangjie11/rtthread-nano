# RT-Thread nano目录结构说明 #

rtthread-nano目录结构如下所示：

| 文件夹名称 | 说明                                               |
| ---------- | -------------------------------------------------- |
| rt-thread  | RT-Thread nano源码                                 |
| docs       | 说明文档，包含 nano 移植文档、FinSH 组件移植文档等 |
| samples    | nano 相关示例代码                                  |

rt-thread 文件夹子目录说明：

| 文件夹名称        | 说明               |
| -------------- | ------------------ |
| libcpu | CPU移植文件，支持ARM、RISC-V架构 |
| src | 内核源码 |
| include    | 内核源码头文件 |
| components/finsh | FinSH组件源码，仅在移植FinSH组件时使用 |

docs文件夹子目录说明：

| 文件夹名称 | 说明                              |
| ---------- | --------------------------------- |
| nano-port  | 将nano移植到主流 IDE 上的说明文档 |
| finsh-port | 基于nano移植FinSH组件的说明文档   |

samples文件夹子目录说明：

| 文件夹名称           | 说明                                      |
| -------------------- | ----------------------------------------- |
| 0-led                | 裸机示例代码                              |
| 1-led-rtthread       | 基于裸机代码移植RT-Thread nano的示例代码  |
| 2-led-rtthread-finsh | 基于RT-Thread nano移植FinSH组件的示例代码 |

