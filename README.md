# Python Flask 本地服务器

这是一个简单的 Python Flask 服务器，当访问 `http://localhost/hello` 时返回 "hello"。

## 文件说明

- `app.py` - 主要的 Flask 应用文件
- `requirements.txt` - Python 依赖文件

## 安装和运行

1. 安装 Flask：
   ```bash
   sudo apt install python3-flask
   ```

2. 运行服务器：
   ```bash
   sudo python3 app.py
   ```

3. 访问 `http://localhost/hello` 查看结果

## 注意事项

- 服务器运行在端口 80，需要 root 权限
- 服务器配置为监听所有接口 (0.0.0.0)
- 开启了调试模式以便开发
