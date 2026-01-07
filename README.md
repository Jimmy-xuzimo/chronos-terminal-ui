# Chronos Terminal UI

> 一个科幻风格的时间显示网页，灵感来源于终端界面、工业控制面板与未来主义设计。

---

## 🎨 设计理念

Chronos 旨在将传统的时间显示与科幻终端美学结合，提供两种视觉模式：

- **Hacker Mode（深色主题）**：暗黑背景 + 霓虹蓝 + 警示橙，模拟黑客终端与代码矩阵。
- **Engineer Mode（浅色主题）**：工业灰蓝背景 + 机械橙，灵感来自工程控制台与极简主义设计。

两种模式均采用**橙色-灰色**工业风配色，强调功能性与视觉层次。

---

## 🖥️ UI 设计亮点

### 1. 终端风格面板
- 双层边框与角落装饰，增强立体感与机械感
- 状态指示灯（脉冲动画）模拟系统运行状态
- 顶部标题栏模拟命令行提示符

### 2. 动态背景
- **代码雨效果**：使用 Canvas 实现 Matrix 风格的字符下落动画
- 字符集包含拉丁文、数字与符号，增强科技感

### 3. CRT 复古效果
- 扫描线 + 轻微 RGB 色散
- 闪烁动画模拟老式显示器视觉残留

### 4. 启动序列
- 模拟系统启动日志，逐行打字机效果
- 渐进式显示主界面，增强沉浸感

### 5. 响应式布局
- 适配桌面与移动端
- 字体大小与布局自动调整

---

## ⚙️ 功能特性

- ✅ 实时显示时间（时:分:秒）
- ✅ 完整日期信息（年/月/日/星期）
- ✅ 深色/浅色模式切换（自动记忆）
- ✅ 模拟系统状态信息（CPU、内存、网络等）
- ✅ 启动动画与平滑过渡
- ✅ 键盘友好（无依赖，纯前端实现）

---

## 🧠 技术实现

- **纯 HTML/CSS/JavaScript**，无外部依赖
- Canvas 2D 绘制动态背景
- CSS 变量实现主题切换
- `requestAnimationFrame` 实现流畅动画
- 本地存储（localStorage）记忆主题偏好

---

## 🚀 如何使用

1. 克隆仓库：
```bash
git clone https://github.com/your-username/chronos-terminal-ui.git
```

2. 直接打开 `index.html` 或在本地服务器中运行。

3. 点击右上角 `[SWITCH_MODE]` 切换主题。

---

## 📁 项目结构

```
chronos-terminal-ui/
├── index.html          # 主页面
├── README.md           # 项目说明
```

---

## 🎯 设计细节

### 颜色系统：
- **深色主题**：`#0a0a12` + `#00f3ff` + `#ff9100`
- **浅色主题**：`#e0e5ec` + `#2b3a42` + `#ff4500`
- 所有颜色通过 CSS 变量管理，便于扩展

### 字体：
- `VT323`：像素风格字体，用于时间与日志
- `Share Tech Mono`：等宽字体，增强终端感

### 动画：
- 光标闪烁
- 状态灯脉冲
- CRT 闪烁
- 代码雨流畅下落

---

## 📸 效果预览

<img width="4400" height="2722" alt="image" src="https://github.com/user-attachments/assets/1c73674f-c557-4094-adfc-2528ede26336" />
<img width="4400" height="2722" alt="image" src="https://github.com/user-attachments/assets/95d72986-1708-411f-aee5-d54209f7e067" />

---

## 📄 开源协议

MIT License  
欢迎 Fork、Star、Issue 与 PR！

---

## 🌐 作者与链接

- 作者：Jimmy-xuzimo
- 项目链接：[GitHub - chronos-terminal-ui](https://github.com/your-username/chronos-terminal-ui)
- 设计灵感：科幻电影、终端界面、工业控制台

---

> “Time is the most valuable currency. Watch it like a system.” — Chronos UI
