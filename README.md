
# 健康提醒app
### 久坐提醒 - 实时计时，达到设定时间后弹出通知
### 喝水提醒 - 定时推送喝水通知
### 弹出通知 - 使用expo-notifications，支持锁屏显示
### 统计功能 - 记录每日站立次数和喝水杯数
### 自定义设置 - 可调整提醒间隔、喝水目标、提醒时间范围
### 数据持久化 - 设置和统计数据保存在本地

### 项目结构
## plaintext
HealthReminder/
├── App.tsx                    # 主入口，导航配置
├── src/
│   ├── screens/
│   │   ├── HomeScreen.tsx     # 主页：计时器、喝水记录、统计
│   │   └── SettingsScreen.tsx # 设置页：自定义各项参数
│   ├── services/
│   │   └── NotificationService.ts  # 通知服务
│   ├── store/
│   │   └── useAppStore.ts     # Zustand状态管理+数据持久化
│   └── types/
│       └── index.ts           # TypeScript类型定义
已实现功能
## 项目截图
 ### ![Uploading 10913baee3b07b3fd554ed52c22f7e9f.jpg…]()
