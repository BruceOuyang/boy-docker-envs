# boy-docker-envs
docker 定义的一些环境

使用 `docker-compose` 启动项目，需要在项目根目录下执行 `docker-compose up` 命令。

我这里没有使用 docker-compose 的默认配置文件名，在执行的时候需要使用 -f 参数指定配置文件。

例如启动 boy-docker-envs 项目下的 mysql 服务，需要执行以下命令：

```bash
docker-compose -f mysql.yml up
```

 