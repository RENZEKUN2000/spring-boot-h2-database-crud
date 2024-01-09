# 使用官方的 Node.js 14 镜像作为基础镜像
FROM node:14

# 设置环境变量，指定应用程序的端口
ENV VUE_APP_PORT=8081

# 创建一个工作目录
WORKDIR /app

# 复制 Vue.js 应用程序的文件到容器内的工作目录
COPY . .

# 安装依赖并构建 Vue.js 应用程序
RUN npm install
RUN npm run build

# 启动 Vue.js 应用程序
CMD ["npm", "run", "start"]

