# CrushOn V2 静态版本

## 使用方法

### 方式1：直接打开（推荐）
1. 下载 `crushon-v2-static.tar.gz`
2. 解压文件
3. 用浏览器打开 `dist/index.html`

### 方式2：本地服务器
```bash
cd dist
npx serve
# 或
python3 -m http.server 3000
```

## 页面说明

| 页面 | 路径 |
|------|------|
| 登录 | `/login/index.html` |
| 注册 | `/register/index.html` |
| 发现流 | `/explore/index.html` |
| 聊天 | `/chat/char-001/index.html` |
| 创建角色 | `/characters/create/index.html` |

## 功能特性

- ✅ 200+ AI 角色
- ✅ 情感状态追踪（好感度/信任度/亲密度）
- ✅ 流式聊天体验
- ✅ 角色编辑器
- ✅ Mock 数据模式（无需后端）

## 注意事项

- 使用 Mock 数据，所有数据保存在内存中
- 刷新页面后数据会重置
- 支持离线使用
