# 🚀 快速开始指南

## 5分钟上手德州扑克游戏

### 方法1: 最简单 - 直接打开 ⭐推荐

```bash
# macOS/Linux
open poker.html

# Windows
start poker.html
```

就这么简单！游戏会在浏览器中打开。

### 方法2: 使用本地服务器

```bash
# 安装依赖（仅首次）
npm install

# 启动游戏
npm start
```

浏览器会自动打开 `http://localhost:8000/poker.html`

### 方法3: Python服务器

```bash
# Python 3
python -m http.server 8000

# 然后访问
# http://localhost:8000/poker.html
```

## 🎮 如何游玩

### 开始游戏
1. 点击 "Deal the Cards" 或 "发牌" 按钮
2. 游戏自动开始，你是底部的玩家

### 操作方式

#### 鼠标操作
- 点击按钮进行操作
- Fold (弃牌) - 放弃当前手牌
- Check (过牌) - 不下注继续
- Call (跟注) - 匹配当前注额
- Raise (加注) - 增加注额
- All-In (全下) - 投入所有筹码

#### 键盘快捷键 ⚡
- `F` - 弃牌
- `C` - 跟注/过牌
- `R` - 打开加注菜单
- `A` - 全下
- `Enter` - 确认加注
- `H` - 显示帮助
- `Escape` - 关闭帮助

### 游戏流程
1. **Pre-flop**: 每人2张底牌，第一轮下注
2. **Flop**: 翻开3张公共牌，第二轮下注
3. **Turn**: 翻开第4张公共牌，第三轮下注
4. **River**: 翻开第5张公共牌，最后下注
5. **Showdown**: 比牌，最好的牌型获胜

### 牌型大小（从小到大）
1. 高牌 (High Card)
2. 一对 (One Pair)
3. 两对 (Two Pair)
4. 三条 (Three of a Kind)
5. 顺子 (Straight)
6. 同花 (Flush)
7. 葫芦 (Full House)
8. 四条 (Four of a Kind)
9. 同花顺 (Straight Flush)
10. 皇家同花顺 (Royal Flush)

## 🔧 运行测试

### 快速测试（推荐）
```bash
npm test
```

验证所有核心功能是否正常。

### 完整测试
```bash
npm run test:full
```

运行所有测试用例。

## 🌐 切换语言

点击右上角的语言按钮：
- 中文 ↔️ EN

## 💡 小贴士

### 新手建议
1. 先熟悉牌型大小
2. 观察AI的下注模式
3. 不要每手都玩，学会弃牌
4. 注意你的位置（后位有优势）
5. 管理好你的筹码

### 高级技巧
1. 利用位置优势
2. 观察底池赔率
3. 混合你的玩法
4. 注意对手的下注模式
5. 适时诈唬

## 🐛 遇到问题？

### 游戏无法启动
- 确保使用现代浏览器（Chrome 90+, Firefox 88+, Safari 14+）
- 清除浏览器缓存
- 检查JavaScript是否启用

### 游戏卡住
- 刷新页面（F5）
- 点击"New Game"按钮重新开始

### 按钮无响应
- 确保轮到你操作（你的名字会高亮）
- 检查是否有足够筹码

## 📚 更多信息

- 完整文档: [README.md](README.md)
- 项目分析: [AGENTS.md](AGENTS.md)
- 更新日志: [CHANGELOG.md](CHANGELOG.md)
- 优化报告: [OPTIMIZATION_REPORT.md](OPTIMIZATION_REPORT.md)

## 🎯 快速命令参考

```bash
# 开始游戏
npm start

# 运行测试
npm test

# 查看所有命令
npm run
```

## ⌨️ 键盘快捷键速查

| 按键 | 功能 |
|------|------|
| F | 弃牌 |
| C | 跟注/过牌 |
| R | 加注 |
| A | 全下 |
| Enter | 确认 |
| H | 帮助 |
| Esc | 关闭 |

## 🎰 开始游玩！

现在你已经准备好了！打开 `poker.html` 开始你的德州扑克之旅吧！

**Good Luck! 祝你好运！** 🍀

---

有问题？查看 [README.md](README.md) 获取更多帮助。
