# PocketPal AI - 移动端小型语言模型

## 开发环境搭建

### 前置要求
- Node.js (18.0 或更高版本)
- Yarn 包管理器
- React Native CLI
- Xcode (iOS开发)
- Android Studio (Android开发)

### 开始开发
1. 克隆仓库
```bash
git clone https://github.com/a-ghorbani/pocketpal-ai
cd pocketpal-ai
```

2. 安装依赖
```bash
yarn install
```

3. iOS 额外步骤
```bash
cd ios
pod install
cd ..
```

### 运行应用

运行 iOS 模拟器:
```bash
yarn ios
```

运行 Android 模拟器:
```bash
yarn android
```

### 常用命令
```bash
# 启动 Metro 打包器
yarn start

# 清理构建产物
yarn clean

# 代码检查和类型检查
yarn lint
yarn typecheck

# 运行测试
yarn test
```