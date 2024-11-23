# Ams.01


- 启动 Docker 容器：
    
    ```bash
    docker run -it --rm ubuntu:latest bash
    ```
    
- 在容器中运行以下命令下载并执行 `start.sh`：
    
    ```bash
    apt update
    apt install -y curl
    curl -o start.sh https://console.icn.global/downloads/install/start.sh
    bash start.sh -p <key>
```
   end

