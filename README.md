### 来自laradock仓库 (开箱即用的docker-sync版本)

#### 配置说明 
    * 配置dock目录和应用目录：`laradock`(本项目)和`www`(用于放各个php项目)在同一级目录  
    * 配置相关环境参数--`.env`
    * 配置dockersync,用于加速容器访问宿主机文件慢的问题--`docker-compose.sync.yml`
    * 配置脚本启动项--`sync.sh`

#### Command

```
./sync.sh up
```

> 更多命令直接参考 `sync.sh` 