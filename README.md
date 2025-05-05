# PlantsVsZombiesJS

一个使用HTML5、CSS3和原生JavaScript实现的Plants vs. Zombies游戏克隆版本。这个项目旨在重现经典游戏的核心机制，无需任何外部框架或库。

![游戏截图](screenshot.png)

## 🌱 特性

- 完全使用原生JavaScript实现，无需任何外部依赖
- 响应式设计，适应不同屏幕尺寸
- 包含经典的植物大战僵尸元素：
  - 6种植物角色（向日葵、豌豆射手、坚果墙、寒冰射手、樱桃炸弹、双发射手）
  - 多种僵尸类型（普通僵尸、铁桶僵尸）
  - 阳光资源收集系统
  - 小推车最后防线
  - 铲子功能
  - 植物冷却时间机制
- 使用SVG图形，无需外部图片资源
- 动态难度调整系统

## 🎮 如何游玩

1. 使用鼠标选择植物卡片
2. 点击草坪上的格子放置植物
3. 收集自动掉落的阳光或由向日葵产生的阳光
4. 使用各类植物阻止僵尸到达房子
5. 如需移除已种植的植物，点击铲子图标后再点击目标植物

## 🚀 快速开始

### 在线游玩

访问 [GitHub Pages链接](#) 即可在线体验游戏。

### 本地运行

1. 克隆仓库：
```bash
git clone https://github.com/yourusername/PlantsVsZombiesJS.git
```

2. 打开项目文件夹：
```bash
cd PlantsVsZombiesJS
```

3. 在浏览器中打开`index.html`文件即可开始游戏。

## 💻 技术细节

- **HTML5**: 提供游戏结构和画布
- **CSS3**: 实现游戏样式和动画效果
- **JavaScript**: 处理游戏逻辑、物理和交互

所有图形均使用内联SVG实现，无需加载外部资源，保证离线可玩性。

## 🔧 自定义与扩展

您可以通过修改以下部分来自定义游戏：

- `ROWS`和`COLS`常量：调整游戏网格大小
- `GAME_DURATION`常量：修改游戏时长
- `zombieSpawnRate`变量：调整僵尸生成频率
- 在`plantImages`对象中添加新的SVG图像可以引入新的植物类型

## 📝 待实现功能

- [ ] 更多植物类型（土豆地雷、大嘴花等）
- [ ] 更多僵尸种类（路障僵尸、撑杆僵尸等）
- [ ] 关卡系统
- [ ] 音效系统
- [ ] 本地存档功能
- [ ] 移动设备支持优化

## 📜 许可证

本项目采用MIT许可证 - 详情请查看[LICENSE](LICENSE)文件。

## 🙏 致谢

- 灵感来源于PopCap Games开发的原版《植物大战僵尸》游戏
- 所有SVG图形均为原创设计，旨在致敬原版游戏的经典形象

## 🔗 相关链接

- [原版Plants vs. Zombies官网](https://www.ea.com/games/plants-vs-zombies)
- [MDN Web文档 - 游戏开发](https://developer.mozilla.org/en-US/docs/Games)

---

⭐ 如果您喜欢这个项目，请给它一个star！ ⭐
