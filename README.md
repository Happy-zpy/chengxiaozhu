# 课表查询系统

一个基于HTML/CSS/JavaScript的课表查询网站，支持周次切换、课程搜索和详情查看。

## 功能特性

- 📅 课表网格视图 - 展示周一至周日的课程安排
- ⏱️ 周次选择器 - 支持灵活切换不同周次
- 🔍 课程搜索 - 支持按课程名称、地点搜索
- 📋 实践课程模块 - 独立展示实践类课程
- 📱 响应式设计 - 适配桌面端和移动端

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)

## 快速开始

```bash
# 克隆仓库
git clone <repository-url>

# 进入目录
cd chengxiaozhu

# 启动本地服务器（推荐）
python -m http.server 3000
# 或使用其他静态服务器

# 打开浏览器访问
http://localhost:3000
```

## 文件结构

```
chengxiaozhu/
├── index.html    # 主页面
├── data.json     # 课表数据
├── .gitignore    # Git忽略配置
└── README.md     # 项目说明
```

## 数据格式

课程数据格式：
```json
{
  "kchId": "课程ID",
  "name": "课程名称",
  "teacher": "授课教师",
  "time": "节次（如1-2）",
  "place": "上课地点",
  "week": 周次,
  "day": "星期几"
}
```

## 开发

使用任何文本编辑器修改代码，无需构建工具。

## 许可证

MIT License
