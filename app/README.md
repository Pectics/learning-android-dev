# My Application

这是一个使用 Android Studio 创建的空白 Android 应用项目。

This is an empty Android application project created with Android Studio.

## 项目信息 (Project Information)

- **应用名称 (App Name)**: My Application
- **包名 (Package Name)**: com.example.myapplication
- **编程语言 (Programming Language)**: Kotlin
- **最小 SDK (Min SDK)**: API 24 (Android 7.0 Nougat)
- **目标 SDK (Target SDK)**: API 34 (Android 14)
- **编译 SDK (Compile SDK)**: API 34

## 项目结构 (Project Structure)

```
app/
├── src/
│   └── main/
│       ├── java/com/example/myapplication/
│       │   └── MainActivity.kt          # 主活动
│       ├── res/                         # 资源文件
│       │   ├── layout/                  # 布局文件
│       │   ├── values/                  # 值资源（字符串、颜色、主题）
│       │   ├── drawable/                # 图形资源
│       │   ├── mipmap-*/               # 应用图标
│       │   └── xml/                     # XML 配置
│       └── AndroidManifest.xml          # 清单文件
└── build.gradle.kts                     # 应用级构建配置
```

## 如何打开项目 (How to Open the Project)

1. 启动 Android Studio (Launch Android Studio)
2. 选择 "Open" 或 "Open an Existing Project"
3. 导航到此项目目录并选择根文件夹 (Navigate to this project directory and select the root folder)
4. Android Studio 将自动识别并配置项目 (Android Studio will automatically recognize and configure the project)

## 如何运行 (How to Run)

1. 连接 Android 设备或启动模拟器 (Connect an Android device or start an emulator)
2. 点击工具栏的"运行"按钮（绿色三角形）(Click the "Run" button in the toolbar (green triangle))
3. 选择目标设备 (Select the target device)
4. 应用将编译、安装并在设备上启动 (The app will compile, install, and launch on the device)

## 依赖项 (Dependencies)

- AndroidX Core KTX
- AndroidX AppCompat
- Material Design Components
- ConstraintLayout
- JUnit (测试)
- Espresso (UI 测试)

## 许可证 (License)

查看 [LICENSE](../LICENSE) 文件了解详情。
