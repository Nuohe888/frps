# Frps 增强版

![Version](https://img.shields.io/badge/Version-0.62.0-blue.svg)
![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)

## 项目简介

这是一个基于 [frp](https://github.com/fatedier/frp) 的增强版本，在原有功能基础上新增了登录验证和端口验证功能，提供更安全的内网穿透解决方案。

## 主要特性

- ✨ 完全兼容原版 frp 的所有功能
- 🔐 新增用户登录验证系统
- 🚪 端口访问权限验证
- 📊 网络限速
- 🛡️ 流量控制
- 云控下线

### 配置

创建配置文件 `frps.toml`:

```toml
#云控地址
apiUrl = ""

#对接云控密钥
apiKey = ""

#对接云控唯一标识
nodeName = ""
```

### 运行

```bash
./frps-enhanced -c frps.toml
```

## 开发计划

- [ ] 随心开发

## 贡献指南

欢迎提交 Issue 和 Pull Request！

## 许可证

本项目采用 Apache License 2.0 许可证，详情请参见 [LICENSE](LICENSE) 文件。

## 致谢

感谢原版 [frp](https://github.com/fatedier/frp) 项目的开发者们！