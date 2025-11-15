# Fish-Counting

> 一个基于改进YOLOv8s的海洋牧场鱼类数量检测系统<a href="https://github.com/Coekyun-Dou">
> <img align="right" src="https://github-readme-stats.vercel.app/api?username=Coekyun-Dou&show_icons=true">
> </a>

- 🔭 I’m currently major in **Internet of Things Engineering**

- 🌱 I’m currently learning **Machine Learning and Deep Learning**

- 💬 My hobbies **🏀basketball 📔reading 🎞️watching movie**

- 📫 How to reach me **less_duuuzx@163.com**


<h3 align="left">Languages and Tools:</h3>
<p align="left">  <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://www.qt.io/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Qt_logo_2016.svg" alt="qt" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

------

## 📖 项目简介

在当前全球渔业资源管理与水域生态保护需求日益紧迫的背景下，该水下鱼类计数系统平台作为一套智能化、精准化的生态监测工具，旨在通过融合YOLOv8高精度检测算法与多维度海洋数据整合技术，辅助政府部门及科研机构实时掌握鱼类种群动态分布与数量变化趋势，评估其资源衰减对生态链的影响。基于深度学习模型与时空数据分析能力，平台可动态追踪种群繁殖、迁徙规律，预判过度捕捞及污染冲击下的资源风险，为制定科学捕捞配额、划定海洋保护区提供可靠数据支撑。通过智能化识别、动态预警及可交互式数据可视化功能，平台将助力构建海洋生态精细化监管体系，推动渔业资源可持续利用与水生生态长效保护目标实现。

## 🛠️ 技术栈

### 核心框架
- **深度学习框架**: PyTorch 1.8.1, Ultralytics YOLO
- **GUI框架**: PyQt5 5.15.8
- **图像处理**: OpenCV (opencv-python >= 4.1.2), Pillow
- **数据处理**: NumPy >= 1.18.5, Pandas, SciPy >= 1.4.1

### 辅助工具
- **数据库**: MySQL (pymysql)
- **可视化**: Matplotlib >= 3.2.2, Seaborn >= 0.11.0
- **系统监控**: psutil, mss (屏幕捕获)
- **配置管理**: PyYAML >= 5.3.1
- **其他**: TensorBoard >= 2.4.1, tqdm >= 4.41.0, thop (FLOPs计算)

### 开发环境
- **编程语言**: Python 3.x
- **操作系统**: Windows / Linux
- **IDE**: 支持PyQt5开发的IDE

## ✨ 系统特性

1. **多输入源支持**
   - 支持图片文件（jpg, png, jpeg, bmp）
   - 支持视频文件（mp4, avi, mov）
   - 支持摄像头实时检测
   - 支持RTSP视频流

2. **改进的YOLOv8模型**
   - 基于YOLOv8s架构
   - 集成CBAM注意力机制，提升特征提取能力
   - 支持多种模型变体（n, s, m, l, x）
   - 针对水下环境优化的检测性能

3. **友好的用户界面**
   - 基于PyQt5的现代化GUI设计
   - 实时视频流显示（原始画面与检测结果对比）
   - 参数实时调整（置信度、IoU阈值）
   - 检测结果统计表格展示

4. **智能检测功能**
   - 实时FPS显示
   - 检测进度条
   - 自动保存检测结果
   - 暂停/继续/停止控制
   - 内存监控与资源管理

5. **用户认证系统**
   - MySQL数据库用户管理
   - 登录验证功能

## 📁 项目结构

```
fish-counting/
├── main/                    # 主程序模块
│   ├── innerface.py        # 主界面逻辑
│   ├── login.py            # 登录界面
│   ├── innerfaceUi.ui      # UI设计文件
│   └── icons/              # 图标资源
├── models/                  # 模型相关
│   ├── common.py           # 通用模型组件（包含CBAM）
│   ├── conv.py             # 卷积模块
│   ├── v8/                 # YOLOv8模型配置
│   │   ├── yolov8s.yaml    # YOLOv8s配置
│   │   ├── yolov8n.yaml    # YOLOv8n配置
│   │   └── ...
│   ├── yolov8_demo.py      # YOLOv8演示代码
│   └── 模型调用/           # 模型训练/验证/测试脚本
├── utils/                   # 工具函数
│   ├── general.py          # 通用工具函数
│   ├── datasets.py         # 数据集加载
│   ├── plots.py            # 可视化工具
│   ├── augmentations.py    # 数据增强
│   └── ...
├── config/                  # 配置文件
│   ├── setting.json        # 系统设置
│   ├── ip.json             # IP配置
│   └── fold.json           # 文件夹配置
├── dialog/                  # 对话框模块
│   └── rtsp_win.py         # RTSP流对话框
├── test/                    # 测试模块
├── pt/                      # 模型权重文件目录
├── result/                  # 检测结果保存目录
├── testdata/                # 测试数据
├── start.py                 # 程序入口
├── requirements.txt         # 依赖包列表
└── README.md               # 项目说明文档
```

## 🔧 环境配置

### 1. 安装Python依赖

```bash
pip install -r requirements.txt
```

### 2. 配置数据库（可选）

如需使用登录功能，需要配置MySQL数据库：

```python
# 在 main/login.py 中配置数据库连接
host='192.168.10.3'
user='root'
passwd='123456'
port=3306
db='hsfdSystem'
```

### 3. 准备模型文件

将训练好的YOLOv8模型权重文件（.pt格式）放置在 `pt/` 目录下，默认使用 `pt/best.pt`。

## 🚀 快速开始

### 1. 启动程序

```bash
python start.py
```

### 2. 登录系统

- 输入用户名和密码
- 点击登录按钮进入主界面

### 3. 开始检测

1. **选择输入源**
   - 点击"打开"按钮选择图片或视频文件
   - 或点击"摄像头"按钮使用摄像头
   - 或点击"RTSP"按钮输入RTSP流地址

2. **调整参数**
   - **置信度阈值 (conf)**: 控制检测的严格程度（0-1）
   - **IoU阈值**: 控制非极大值抑制的严格程度（0-1）
   - **延迟设置**: 控制检测帧率

3. **运行检测**
   - 点击"运行"按钮开始检测
   - 实时查看检测结果
   - 查看统计表格中的计数结果

## 📝 功能说明

### 主界面功能

- **左侧控制面板**
  - 模型选择下拉框
  - 输入源选择（文件/摄像头/RTSP）
  - 参数调整滑块
  - 自动保存选项

- **中间显示区域**
  - 左侧：原始视频流
  - 右侧：检测结果视频流
  - 底部：控制按钮（运行/暂停/停止）

- **右侧统计面板**
  - 实时检测结果统计表格
  - 显示各类别检测数量

### 检测流程

1. **图像预处理**: 自动调整图像尺寸，保持宽高比
2. **模型推理**: 使用YOLOv8模型进行目标检测
3. **后处理**: 非极大值抑制（NMS）过滤重复检测
4. **结果绘制**: 在图像上绘制边界框和标签
5. **统计更新**: 更新检测计数统计
6. **结果保存**: 自动保存检测结果（可选）

## 🖼️ 平台展示

#### 1）登录页面
![image](https://github.com/user-attachments/assets/23eb9103-4d8e-4e04-9314-b09b73c91e9e)

#### 2）系统参数调制页面
![image](https://github.com/user-attachments/assets/5fe287d5-e8b5-4a5c-acec-143749d52be7)

#### 3）水下鱼类计数测量展示页面
![image](https://github.com/user-attachments/assets/7e3c0ac5-4549-49c3-9d96-f71bb8742068)

## 📧 联系方式

- **邮箱**: less_duuuzx@163.com
- **GitHub**: [Coekyun-Dou](https://github.com/Coekyun-Dou)
