# gateway-docker-scripts
### 前置条件
docker-compose版本高于1.23

### 说明
本脚本会启动cybex gateway后端, config-server和web2.0前端

### 启动方式
docker-compose up -d

### 自定义配置
- gateway配置项定义文件gateway.yaml
- config-server配置项定义文件为config-server.js
- 因为web2.0为打包好的静态文件，配置文件在[这里](https://github.com/CybexDex/cybex-web-2.0/blob/master/client/lib/config/config.docker.js)， 可以修改后运行[脚本](https://github.com/CybexDex/cybex-web-2.0/blob/master/buildimage-cybex-web.sh)生成新的镜像后重启docker-compose
