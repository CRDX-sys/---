# ---
项目名称: E-Shop Microservices Platform  技术栈:  语言: Python (FastAPI) 数据库: PostgreSQL (主数据库), Redis (缓存) 消息队列: RabbitMQ 容器化: Docker 部署: Kubernetes (可选) 监控: Prometheus + Grafana 日志: ELK Stack (可选)
# E-Shop Microservices Platform

现代化的电商平台微服务架构，使用Python和FastAPI构建。

## 功能

- 用户管理 (注册、登录、个人资料)
- 商品管理 (CRUD、分类、搜索)
- 订单处理 (创建、状态管理)
- 支付集成 (模拟支付流程)
- API网关 (统一入口、负载均衡)
- 监控和日志

## 技术栈

- **语言**: Python 3.9+
- **框架**: FastAPI
- **数据库**: PostgreSQL, Redis
- **消息队列**: RabbitMQ
- **容器化**: Docker
- **编排**: Kubernetes (可选)
- **监控**: Prometheus + Grafana

## 快速开始

1. 克隆仓库
```bash
git clone https://github.com/yourusername/eshop-microservices.git
cd eshop-microservices
```

2. 复制环境变量文件
```bash
cp .env.example .env
```

3. 启动服务
```bash
docker-compose up --build
```

4. 访问服务
- API网关: http://localhost:8080
- 用户服务: http://localhost:8000
- 商品服务: http://localhost:8001
- RabbitMQ管理: http://localhost:15672

## 开发

安装开发依赖:
```bash
pip install -r requirements-dev.txt
```
