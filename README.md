# 无限暖暖音符播放器 (由deepseek生成)

这是一个为《无限暖暖》游戏开发的音符自动播放工具。通过这个工具，您可以轻松地播放预先编写好的音符序列。

## 功能特点

- 自动检测游戏窗口
- 支持自定义音符文件
- 实时显示播放状态
- 可随时暂停/停止播放

## 使用说明

### 运行要求
- Windows 操作系统
- Python 3.6 或更高版本
- 需要管理员权限运行

### 音符文件格式
音符文件为文本格式（.txt），每行包含一个音符和持续时间，格式如下：


### 音符对应关系
- 1-7：对应键盘按键 A S D F G H J
- h1-h7：对应键盘按键 Q W E R T Y U

### 操作步骤
1. 运行程序（需要管理员权限）
2. 点击"选择音符文件"加载音符文件
3. 确保游戏窗口已被检测到（如未检测到，点击"重新检测窗口"）
4. 点击"开始播放"开始自动播放
5. 需要停止时点击"停止播放"

## 注意事项
- 请确保游戏窗口处于活动状态
- 播放过程中请勿切换窗口
- 建议在游戏音符界面再开始播放
- 程序需要管理员权限才能正常运行

## 常见问题
Q: 为什么需要管理员权限？
A: 为了能够向游戏窗口发送按键消息，程序需要管理员权限。

Q: 找不到游戏窗口怎么办？
A: 请确保游戏已经启动，然后点击"重新检测窗口"按钮。

## 更新日志
v2.0
- 新增自定义音符持续时间功能
- 优化界面布局
- 改进游戏窗口检测机制

## 许可证
本项目仅供学习交流使用，请勿用于商业用途。