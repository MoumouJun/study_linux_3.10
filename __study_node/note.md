

在Linux 3.10版本的源码中，整体目录结构通常如下所示：

./
|-- arch/                # 架构相关代码
|   |-- arm/             # ARM 架构代码
|   |-- x86/             # x86 架构代码
|   |-- ...
|-- block/               # 块设备子系统代码
|-- crypto/              # 加密子系统代码
|-- Documentation/       # 文档
|-- drivers/             # 驱动程序代码
|-- fs/                  # 文件系统代码
|-- include/             # 头文件
|-- init/                # Linux 内核初始化代码
|-- ipc/                 # 进程间通信代码
|-- kernel/              # 内核核心代码
|-- lib/                 # 通用函数库
|-- mm/                  # 内存管理代码
|-- net/                 # 网络子系统代码
|-- samples/             # 示例代码
|-- scripts/             # 构建和维护脚本
|-- security/            # 安全子系统代码
|-- sound/               # 声音子系统代码
|-- tools/               # 工具
|-- usr/                 # 用户空间代码
|-- virt/                # 虚拟化子系统代码
|-- Makefile             # 内核构建脚本
|-- Kconfig              # 内核配置脚本
|-- README               # 自述文件
|-- COPYING              # 版权信息
`-- ...
这只是一个简单的概览，实际上Linux内核源码非常庞大，包含了许多不同的目录和文件，用于实现各种功能和子系统。每个目录都包含了相应的代码文件，用于实现特定的功能。
注意：Linux内核的源码组织结构可能会因版本、发行版或定制修改而有所不同。上述目录结构是一个通用的参考示例。

arch：包含不同体系结构（如x86、ARM）的特定代码。
block：块设备子系统的代码，包括硬盘和闪存驱动等。
crypto：密码学相关的代码，提供加密算法和哈希函数等。
Documentation：开发者文档和使用手册。
drivers：各种设备驱动程序的代码，例如网络接口卡、声卡和USB设备等。
fs：文件系统实现的代码，包括ext4、FAT等。
include：公共头文件，包含了内核提供的函数和结构的声明。
init：内核初始化和启动代码。
ipc：进程间通信机制的代码，如信号量、消息队列和共享内存等。
kernel：内核的核心代码，包括调度器、内存管理和进程管理等。
lib：一些公用的库函数，供内核和驱动程序使用。
mm：内存管理子系统的代码，包括虚拟内存和物理内存的管理。
net：网络协议栈的代码，包括TCP/IP、UDP和 socket 等。
samples：示例代码，用于演示内核功能的使用方法。
scripts：构建和辅助脚本。
security：安全子系统的代码，包括访问控制和安全模块等。
sound：音频子系统的代码，包括声卡驱动和声音处理函数等。
tools：开发和调试工具。
usr：用户空间工具的代码，如init和shell等。
virt：虚拟化相关的代码。