# 苍穹外卖
## 🚀如果这个项目对你有帮助，请给我一个🌟Star 吧！

你的支持对我意义重大，它会帮助我不断改进和优化这个项目。非常感谢！😊

项目包含了 **微信支付（伪支付）**、配置了 **百度地图 API** 以及 **阿里云 OSS 对象存储**。

你只需要替换自己的 API 密钥即可完整运行本项目。

📘 配套文档笔记：[《苍穹外卖》在线阅读](https://yingzya.github.io/posts/44e4c2a4.html)

<p>
  <a href="https://github.com/yingzya/takeout-food/raw/main/document/苍穹外卖.pdf">
    <img src="https://img.shields.io/badge/📄 下载文档（PDF）-blue" alt="PDF文档下载">
  </a>
  <a href="https://github.com/yingzya/takeout-food">
    <img src="https://img.shields.io/badge/🚀 项目地址-green" alt="项目主页">
  </a>
</p>

### 📁 项目结构

- `mp-weixin/`：小程序前端项目(**自己去创建**哦😯，**项目中没有**)
- `sky-take-out/`：后端 SpringBoot 项目
- `nginx-1.20-2/`：Nginx 前端代理（运行时记得启动）
---

### ✅ 快速启动

1. 启动后端 `sky-take-out`
2. 配置并启动前端小程序 `mp-weixin`
3. 启动 Nginx，确保代理正确指向后端接口

---

### 🛠 技术栈

- SpringBoot + MyBatis + Redis + JWT
- 微信小程序开发
- 百度地图 API、OSS 文件上传
- Nginx 前端代理部署

#### 最后，特别感谢 [黑马程序员](https://www.itheima.com/) 提供的优质教程，感谢他们免费的课程！🌸
