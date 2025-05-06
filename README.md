# addition-calculation
为了帮助患有整数加法运算障碍的人群，而设计出的最完美的终极解决方案，本项目使用Python编写
## 很正经的项目背景
* 我们注意到，世界上有很多不会进行整数加法计算的人（虽然我并不知道到底有多少XD）
* 与很多用户不会使用搜索引擎进行搜索一样，有大量用户无法正常使用系统自带的计算器功能
* 研表究明，有 我也不知道多少% 以上的电脑用户未曾打开过系统自带的计算器软件
* 本人某日看了某bilibili的某vup视频后，倍感心痛，决定帮助他们
## 环境配置

### 打开电脑

#### 1. 台式电脑
- 按下主机箱上的电源按钮（通常位于前面板，带有⚡或●标志）
- 等待显示器亮起，进入操作系统登录界面

#### 2. 笔记本电脑
- 找到键盘右上角或侧边的电源按钮（通常带有⚡图标）
- 长按1-2秒直到电源指示灯亮起
- 等待屏幕显示操作系统登录界面

#### 3. 首次开机设置（新电脑）
1. 选择语言和地区
2. 连接Wi-Fi网络（可选）
3. 创建用户账户（设置用户名和密码）
4. 等待系统初始化完成

### 进入操作系统

#### Windows系统
- 输入密码（如果有）后按回车（return 或 Enter）
- 等待进入桌面（显示"开始"菜单和任务栏）

#### macOS系统
- 输入密码（如果有）后按回车（return 或 Enter）
- 等待进入桌面（显示Dock栏和顶部菜单栏）

#### Linux系统（如Ubuntu）
- 输入密码（如果有）后按回车（return 或 Enter）
- 等待进入GNOME/KDE等桌面环境

### 打开命令行工具

#### macOS
1. 使用 Spotlight 搜索（快捷键 `Command + Space`）
2. 输入 `terminal` 然后按回车（return 或 Enter）
3. 或者通过 Finder > 应用程序 > 实用工具 > Terminal.app

#### Linux
1. 快捷键 `Ctrl + Alt + T`（适用于大多数发行版）
2. 或者通过应用程序菜单搜索：
   - Ubuntu/Debian：搜索 "Terminal"
   - CentOS/Fedora：搜索 "Konsole" 或 "Terminal"
3. 对于无GUI的服务器：登录后即处于命令行环境

### 配置环境并安装python3

#### macOS
```bash
# 安装 Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 安装 Python 3
brew install python

# 验证是否正确安装
python3 --version
pip3 --version
```

#### Linux (Debian/Ubuntu)
```bash
# Update package list
sudo apt update

# 安装 Python 3 和 pip
sudo apt install python3 python3-pip

# 验证是否正确安装
python3 --version
pip3 --version
```

## 上手指南
* 实在太简单了，所以！
```
one=int(input("请输入第一个数字:"))
two=int(input("请输入第二个数字:"))
print(f"结果：{one+two}")
```

* 自己复制下来去粘贴吧！

###如何运行上述代码

1. 参考环境配置中的教程打开命令行

2. 输入 `python3` + 回车（return 或 Enter）进入 Python 交互模式

3. 直接粘贴以下完整代码块（注意保持缩进）：

```python
one=int(input("请输入第一个数字:"))
two=int(input("请输入第二个数字:"))
print(f"结果：{one+two}")
```
4. 按回车（return 或 Enter）执行（在 macOS/Linux 可能需要多按一次回车）

## 如何使用
* 输入第一个加数，回车，之后输入第二个加数，再次回车即可得到和
## 警告！！！
* 只能使用整数
## 作者
* @STC272
* 您也可以在贡献者名单中参看所有参与该项目的开发者（如果有的话）
## 版权说明
* 该项目采用了MIT 授权许可
## 鸣谢
* 灵感来源于和某位不愿透露姓名的好兄弟的一次玩笑
* 来自@SakuraKoi的建议
* 来自@Ink33的建议
* 来自@风间千景的建议
* 来自我老婆的建议

## 常见问题

1. "python3不是内部或外部命令"
   - 其他系统：尝试`python`代替`python3`

2. 权限被拒绝
   - 在命令前加`sudo`（Linux/macOS）

3. 网络连接问题
   - 检查网络连接
   - 尝试更换软件源（Linux）
