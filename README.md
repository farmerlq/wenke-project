# 问客项目

问客项目是一个包含FastAPI后端和Vue.js前端的全栈应用，提供AI对话和智能体管理功能。

## 项目结构

```
├── backend/       # FastAPI后端
├── frontend/      # Vue.js前端
└── .gitignore     # Git忽略文件配置
```

## 后端技术栈
- FastAPI
- SQLAlchemy
- Uvicorn
- Pydantic
- MySQL

## 前端技术栈
- Vue 3
- Element Plus
- TypeScript
- Vite
- Pinia

## 快速开始

### 后端安装

1. 进入backend目录
```bash
cd backend
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 运行服务
```bash
python main.py
```

### 前端安装

1. 进入frontend目录
```bash
cd frontend
```

2. 安装依赖
```bash
pnpm install
```

3. 运行开发服务器
```bash
pnpm dev
```

## 功能特点
- AI对话接口
- 智能体管理
- 用户会话管理
- 商户管理
- 消息记录管理

## 注意事项
- 项目使用Python 3.10+和Node.js 16+
- 后端默认运行在8000端口
- 前端默认运行在5173端口

## License
MIT