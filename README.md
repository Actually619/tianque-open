# 天阙支付 Skill

> 一句话接入天阙支付，支持主扫、被扫、查询、退款

## 简介

天阙支付 Skill 是一个 AI 技能包，帮助开发者快速接入天阙开放平台支付接口。无需翻阅文档，只需告诉 AI 你要做什么，它会自动生成正确的集成代码。


## 安装

### 方式一：从 GitHub 下载

```bash
# 克隆仓库
git clone https://github.com/<你的用户名>/tianque-payment-skill.git

# 复制到 AI skills 目录
cp -r tianque-payment-skill ~/.openclaw/workspace/skills/tianque-payment
```

### 方式二：手动下载

1. 点击 GitHub 页面 **Code** → **Download ZIP**
2. 解压后将文件夹重命名为 `tianque-payment`
3. 放入 `~/.openclaw/workspace/skills/` 目录

### 验证安装

重启 OpenClaw 或发送心跳，然后询问 AI：

```
你有哪些支付相关的技能？
```

如果回复中包含"天阙支付"，说明安装成功 ✅

## 快速开始

向 AI 发送以下任一指令：

```
帮我接入支付
我要接入天阙
帮我生成主扫支付代码
```

AI 会引导你完成：

1. **身份确认** — 商户 or 服务商
2. **环境选择** — 测试 or 生产
3. **配置信息** — 机构号、商户号、私钥
4. **场景选择** — 主扫/被扫/两者都要
5. **代码生成** — 自动生成并测试验证

## 目录结构

```
tianque-payment/
├── SKILL.md                   # 技能主文件
└── references/
    ├── sign-examples.md       # 签名代码示例（6语言）
    ├── api-reference.md       # 接口参数详情
    └── response-codes.md      # 应答码说明
```

### 需要帮助？

联系天阙技术支持
