# 地质勘查安全录

> 安全生产培训互动小游戏 · 基于 GitHub Pages 部署

通过互动卡牌游戏，学习地质勘查安全生产知识。涵盖野外作业、钻探、物探、化探、测绘遥感等真实场景，双职业路线，19种结局。

## 🎮 游戏特色

- **双职业路线**：专业技术路线 & 项目管理路线
- **真实场景**：基于地质勘查真实工作场景
- **两难抉择**：安全与进度、合规与效率的博弈
- **知识小课堂**：每个选项附带法规依据
- **10章53张卡牌**：完整的职业成长故事
- **19种结局**：不同选择导向不同人生

## 📁 项目结构

```
geo-safety-game/
├── index.html          # 游戏首页（落地页）
├── game.html           # 游戏主页面
├── .gitignore          # Git忽略文件
└── README.md           # 项目说明
```

## 🚀 部署到 GitHub Pages（5步）

### 第1步：在 GitHub 上新建仓库

1. 登录 [GitHub](https://github.com)
2. 点击右上角 **+** → **New repository**
3. 填写仓库信息：
   - **Repository name**：`geo-safety-game`（或你喜欢的名字）
   - **Description**：地质勘查安全生产培训互动小游戏
   - **Public**：选择公开（GitHub Pages 免费）
   - 不需要勾选 "Add a README file"（我们已经有了）
4. 点击 **Create repository**

### 第2步：克隆仓库到本地

复制仓库地址，然后在命令行执行：

```bash
# 克隆仓库（替换为你的用户名和仓库名）
git clone https://github.com/你的用户名/geo-safety-game.git

# 进入仓库目录
cd geo-safety-game
```

### 第3步：复制游戏文件到仓库

把本项目的所有文件复制到刚克隆的仓库目录中：

```
index.html
game.html
.gitignore
README.md
```

> **注意**：确保 `index.html` 和 `game.html` 在仓库根目录，不要放在子文件夹中。

### 第4步：提交并推送

```bash
# 查看文件状态
git status

# 添加所有文件
git add .

# 提交
git commit -m "初始提交：地质勘查安全录游戏"

# 推送到 GitHub
git push
```

### 第5步：开启 GitHub Pages

1. 在 GitHub 仓库页面，点击 **Settings**（设置）
2. 左侧菜单找到 **Pages**（页面）
3. 在 **Build and deployment** 部分：
   - **Source**：选择 `Deploy from a branch`
   - **Branch**：选择 `main` 分支，文件夹选择 `/ (root)`
4. 点击 **Save**
5. 等待 1-2 分钟，页面顶部会显示：
   > Your site is live at https://你的用户名.github.io/geo-safety-game/

🎉 **完成！** 点击链接即可访问游戏。

---

## 📱 访问地址

部署成功后，游戏访问地址为：

```
https://你的用户名.github.io/仓库名/
```

例如：
- 首页：`https://zhangsan.github.io/geo-safety-game/`
- 游戏页：`https://zhangsan.github.io/geo-safety-game/game.html`

> **注意**：第一次部署可能需要等待 1-2 分钟才能访问。如果访问 404，稍等片刻刷新即可。

---

## 🔄 更新游戏

如果需要更新游戏内容（修改卡牌、结局等）：

1. 替换 `game.html` 文件
2. 提交并推送：
   ```bash
   git add .
   git commit -m "更新游戏内容：xxx"
   git push
   ```
3. GitHub Pages 会自动重新部署，等待 1-2 分钟即可看到更新

---

## 🎯 游戏玩法

1. **阅读场景，做出选择**：每张卡牌描述一个真实的工作场景
2. **查看结果，学习知识**：选择后显示结果和"安全知识小课堂"
3. **管理状态，规避风险**：关注技能、威信、安全、精力四个状态值
4. **选择路线，迎接结局**：第4章结束时选择职业路线，共19种结局

---

## 📊 游戏数据

- **章节**：10章
- **卡牌**：53张
- **选项**：166个
- **结局**：19种
- **知识小课堂**：166个（100%覆盖）
- **法规引用**：64处

---

## 📚 参考法规

- 《中华人民共和国安全生产法》
- 《金属非金属矿山安全规程》GB 16423
- 《地质勘查安全规程》
- 《爆破安全规程》GB 6722
- 《高处作业分级》GB/T 3608
- 《生产安全事故报告和调查处理条例》
- 《中华人民共和国保守国家秘密法》
- 《中华人民共和国网络安全法》
- 《地质勘查资质管理条例》

---

## ⚠️ 注意事项

1. **游戏进度存储**：游戏进度保存在浏览器 localStorage 中，清除浏览器数据会丢失进度
2. **换设备不同步**：不同设备/浏览器之间进度不同步（如需同步，需后端支持）
3. **无痕模式**：无痕/隐私模式下进度无法保存
4. **浏览器兼容性**：建议使用 Chrome、Edge、Firefox 等现代浏览器

---

## 📝 许可证

本游戏仅供安全生产培训教育使用，场景和人物均为虚构。

---

## 🤝 相关链接

- [GitHub Pages 文档](https://docs.github.com/zh/pages)
- [Git 入门教程](https://git-scm.com/book/zh/v2)

---

**如有问题，欢迎提交 Issue。**
