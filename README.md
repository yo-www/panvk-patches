# panvk-kbase 补丁集镜像

镜像自 `zenithblue-oss/panvk-kbase-android` 的 `patches/` 目录（244 个补丁，6MB），
用于在本机容器内给 Mesa 源码打补丁后编译 glibc 版 PanVK。

- 基线：Mesa commit `5a07217f034b3e50d8c7c7794f97a2df1742613b`（26.3.0-devel，快照日期 2026-09-18）
- 目录：`common/` `kbase-common/` `csf/` `csf-v11/` `jm-v7/` `jm-v9/` `android/` `wsi/` 等
- 设备：MT6991 / Mali-G925-Immortalis MC12（arch 13）→ 需 csf-v11 系列 + kbase-common
