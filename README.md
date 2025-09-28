# 3D三体问题演示器 / 3D Three-Body Problem Demonstrator

[English](#english) | [中文](#中文)

---

## 中文

### 📖 项目简介

这是一个基于Web的3D三体问题演示器，使用Three.js构建的交互式物理模拟系统。该项目展示了经典的三体问题——三个天体在万有引力作用下的复杂运动轨迹。

### ✨ 主要特性

- **🎮 实时3D可视化**：使用Three.js渲染的流畅3D动画
- **🎛️ 交互式控制面板**：完整的参数调节界面
- **🌟 多种预设配置**：包含6种经典三体系统配置
- **🎨 自定义配置**：支持用户自定义天体参数
- **📊 轨迹可视化**：
  - 三种轨迹粗细（细线、中等、粗线）
  - 轨迹显示/隐藏控制
  - 可调节轨迹长度和透明度
- **⚙️ 物理参数调节**：
  - 万有引力常数
  - 时间步长
  - 时间速度
  - 天体质量
- **💾 配置管理**：导入/导出配置文件
- **📱 响应式设计**：适配不同屏幕尺寸

### 🚀 快速开始

1. **克隆项目**
   ```bash
   git clone [repository-url]
   cd 三体问题
   ```

2. **启动本地服务器**
   ```bash
   # 使用Python
   python -m http.server 8000
   
   # 或使用Node.js
   npx serve .
   ```

3. **打开浏览器**
   访问 `http://localhost:8000/three-body problem1.1.html`

### 🎯 使用说明

#### 基本操作
- **鼠标左键拖拽**：旋转视角
- **鼠标滚轮**：缩放视图
- **鼠标右键拖拽**：平移视图

#### 控制面板功能
1. **物理参数**
   - 调节万有引力常数
   - 设置时间步长和速度
   
2. **轨迹设置**
   - 选择轨迹粗细（细线/中等/粗线）
   - 控制轨迹显示/隐藏
   - 调节轨迹长度和透明度

3. **天体配置**
   - 修改天体质量
   - 选择预设配置
   - 自定义天体参数

4. **配置管理**
   - 导出当前配置
   - 导入保存的配置

### 🔧 技术栈

- **前端框架**：原生HTML5 + CSS3 + JavaScript
- **3D渲染**：Three.js
- **物理模拟**：自定义物理引擎
- **UI设计**：现代化响应式界面

### 📁 项目结构

```
三体问题/
├── three-body problem1.1.html    # 中文版主文件
├── three-body problem-en.html    # 英文版主文件
└── README.md                      # 项目文档
```

### 🎨 预设配置

1. **经典三体**：等质量三体系统
2. **太阳-地球-月球**：真实天体系统模拟
3. **双星系统**：双星绕行配置
4. **混沌轨道**：展示混沌行为
5. **稳定三角**：拉格朗日点配置
6. **8字轨道**：特殊周期轨道

### 🤝 贡献指南

欢迎提交Issue和Pull Request来改进项目！

### 📄 许可证

本项目采用MIT许可证。

---

## English

### 📖 Project Description

This is a web-based 3D Three-Body Problem Demonstrator built with Three.js, featuring an interactive physics simulation system. The project showcases the classic three-body problem - the complex motion trajectories of three celestial bodies under gravitational forces.

### ✨ Key Features

- **🎮 Real-time 3D Visualization**: Smooth 3D animations rendered with Three.js
- **🎛️ Interactive Control Panel**: Complete parameter adjustment interface
- **🌟 Multiple Preset Configurations**: Includes 6 classic three-body system configurations
- **🎨 Custom Configuration**: Support for user-defined celestial body parameters
- **📊 Trail Visualization**:
  - Three trail thickness options (thin, medium, thick)
  - Trail show/hide control
  - Adjustable trail length and opacity
- **⚙️ Physics Parameter Control**:
  - Gravitational constant
  - Time step
  - Time speed
  - Celestial body mass
- **💾 Configuration Management**: Import/export configuration files
- **📱 Responsive Design**: Adapts to different screen sizes

### 🚀 Quick Start

1. **Clone the Project**
   ```bash
   git clone [repository-url]
   cd 三体问题
   ```

2. **Start Local Server**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Or using Node.js
   npx serve .
   ```

3. **Open Browser**
   Visit `http://localhost:8000/three-body problem-en.html`

### 🎯 Usage Instructions

#### Basic Operations
- **Left Mouse Drag**: Rotate view
- **Mouse Wheel**: Zoom view
- **Right Mouse Drag**: Pan view

#### Control Panel Functions
1. **Physics Parameters**
   - Adjust gravitational constant
   - Set time step and speed
   
2. **Trail Settings**
   - Select trail thickness (thin/medium/thick)
   - Control trail visibility
   - Adjust trail length and opacity

3. **Celestial Body Configuration**
   - Modify celestial body mass
   - Select preset configurations
   - Custom celestial body parameters

4. **Configuration Management**
   - Export current configuration
   - Import saved configurations

### 🔧 Tech Stack

- **Frontend Framework**: Native HTML5 + CSS3 + JavaScript
- **3D Rendering**: Three.js
- **Physics Simulation**: Custom physics engine
- **UI Design**: Modern responsive interface

### 📁 Project Structure

```
三体问题/
├── three-body problem1.1.html    # Chinese version main file
├── three-body problem-en.html    # English version main file
└── README.md                      # Project documentation
```

### 🎨 Preset Configurations

1. **Classic Three-Body**: Equal mass three-body system
2. **Sun-Earth-Moon**: Real celestial system simulation
3. **Binary System**: Binary star configuration
4. **Chaotic Orbit**: Demonstrates chaotic behavior
5. **Stable Triangle**: Lagrange point configuration
6. **Figure-8 Orbit**: Special periodic orbit

### 🤝 Contributing

Issues and Pull Requests are welcome to improve the project!

### 📄 License

This project is licensed under the MIT License.