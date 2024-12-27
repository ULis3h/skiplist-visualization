# 算法可视化演示集合 🎯

这个仓库包含了多个经典算法和数据结构的交互式可视化演示。通过动画和交互的方式，帮助理解算法的核心概念和工作原理。每个算法都提供了详细的文档和示例，便于学习和实践。

## 已实现的算法

### 1. [跳表 (Skip List)](skiplist/) ⚡
一种基于概率的数据结构，通过分层索引加速查找。
- **时间复杂度**: O(log n) 平均查找时间
- **特点**: 
  - 多层级快速索引
  - 概率平衡
  - 空间换时间的典型应用
- **可视化功能**:
  - 查找路径追踪
  - 节点层级展示
  - 实时动画演示

### 2. [小世界网络 (Small World)](small-world/) 🌐
展示网络中的"六度分隔"现象和小世界特性。
- **网络特征**:
  - 平均路径长度: O(log n)
  - 聚类系数: 高
- **核心概念**:
  - 规则网络到小世界的转变
  - 随机重连过程
  - 网络特征量化分析
- **交互功能**:
  - 参数动态调节
  - 网络属性计算
  - 节点关系探索

### 3. [HNSW (Hierarchical Navigable Small World)](hnsw/) 🔍
高效的近似最近邻搜索算法，结合了小世界网络和多层级结构。
- **性能特点**:
  - 查询时间: O(log n)
  - 构建时间: O(n log n)
  - 空间复杂度: O(n log n)
- **算法特性**:
  - 多层级导航结构
  - 贪婪路由策略
  - 概率分层机制
- **可视化要素**:
  - 层级结构展示
  - 搜索路径追踪
  - 性能指标监控

### 4. [B+ 树 (B+ Tree)](btree/) 🌳
高效的多路搜索树，广泛应用于数据库索引和文件系统。
- **性能特点**:
  - 查找时间: O(log n)
  - 插入时间: O(log n)
  - 空间利用率高
- **算法特性**:
  - 所有数据存储在叶子节点
  - 叶子节点形成有序链表
  - 非叶节点只存储索引
- **可视化要素**:
  - 树结构动态展示
  - 插入操作演示
  - 查找过程追踪

## 技术实现 🛠️

- **前端技术**:
  - HTML5 Canvas: 绘制和动画
  - 原生 JavaScript: 算法实现
  - CSS3: 界面布局和样式

- **项目特点**:
  - 无依赖设计
  - 高性能渲染
  - 响应式布局
  - 优雅的动画效果

## 本地开发 💻

1. **环境准备**
   ```bash
   # 克隆仓库
   git clone https://github.com/yourusername/algorithm-visualizations.git
   cd algorithm-visualizations
   
   # 启动本地服务器
   python3 -m http.server 8000
   ```

2. **访问演示**
   - 打开浏览器访问 `http://localhost:8000`
   - 选择需要查看的算法演示
   - 根据每个算法的README进行操作

## 开发计划 📝

- [ ] 图算法系列
  - 最短路径算法
  - 最小生成树
  - 图着色问题
- [ ] 高级树结构
  - 红黑树
  - AVL树
  - Trie树
- [ ] 字符串算法
  - KMP算法
  - 后缀数组
  - AC自动机

## 贡献指南 👥

欢迎贡献新的算法实现或改进现有实现！请遵循以下步骤：

1. Fork 本仓库
2. 创建新的分支 `git checkout -b feature/algorithm-name`
3. 提交更改 `git commit -m 'Add new algorithm'`
4. 推送到分支 `git push origin feature/algorithm-name`
5. 提交 Pull Request

## 许可证 📄

MIT License - 详见 [LICENSE](LICENSE) 文件