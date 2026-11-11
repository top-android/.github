<div align="center">
  <h1>💎 TOP-ANDROID</h1>
  <p><b>Low-Level Android System Engineering · Kernel Compilation · Automated Build Workflows</b></p>
  <p>专注于 Android 底层系统适配、AOSP 跨版本移植、内核调优与容器化构建工程</p>

  <p>
    <img src="https://img.shields.io/badge/Platform-AOSP-38BDF8?style=flat-square&logo=linux&logoColor=white" alt="AOSP" />
    <img src="https://img.shields.io/badge/Kernel-Linux%20%2F%20GKI-2563EB?style=flat-square&logo=linux&logoColor=white" alt="Kernel" />
    <img src="https://img.shields.io/badge/Build-Docker%20CI%2FCD-1D4ED8?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/Language-C%20%2F%20C%2B%2B%20%2F%20Shell-0B0F19?style=flat-square" alt="Languages" />
  </p>
</div>

---

### ⚡ About Us / 关于组织

**top-android** 是一个专注于 Android 底层系统工程与硬件适配的技术组织。我们致力于探索高版本 AOSP 移植、Vendor HAL 升级（HIDL 向 AIDL 演进）、カスタム内核（Kernel）编译以及可复现的 Docker 自动化构建环境。

**top-android** is dedicated to low-level Android system development, device bring-up, custom kernel engineering, and reproducible build infrastructures.

---

### 🛠️ Core Focus / 核心方向

* **🔧 Device Bring-up & Porting**：特定设备（如 MT6853 / `cannon` 等）的设备树（Device Tree）、Vendor 固件提取与跨大版本 AOSP 适配。
* **🐧 Kernel Engineering**：内核源码维护、驱动补丁移植、性能优化与定制化配置。
* **🐳 Reproducible Builds**：基于 Docker 与 Shell 脚本的无人值守内核/ROM/Recovery 编译流水线。
* **🛡️ Recovery & Debugging**：TWRP 适配、早期启动阶段（Init / SELinux / ADB）底层调试与修复方案。

---

### 📦 Featured Repositories / 核心仓库导航

| 仓库名称 (Repository) | 类型 (Type) | 说明 (Description) |
| :--- | :--- | :--- |
| **[android_kernel_xiaomi_cannon](https://github.com/top-android/android_kernel_xiaomi_cannon)** | `C` / `Kernel` | Redmi Note 9 5G (`cannon`) 内核源码树与底层补丁维护 |
| **[Cannon_Docker_Kernel_Build](https://github.com/top-android/Cannon_Docker_Kernel_Build)** | `Shell` / `Docker` | 容器化内核自动编译环境，实现开箱即用的一键构建 |
| **[cannon-build](https://github.com/top-android/cannon-build)** | `Shell` / `Scripts` | 编译构建脚本集合与自动化辅助工具链 |

---

<div align="center">
  <sub>Built with precision by <b>top-android</b>.</sub>
</div>
