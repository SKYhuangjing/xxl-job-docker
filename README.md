# xxl-job-docker

init 目录中会存放 xxl-job 的初始化数据库, 原始路径是 https://github.com/xuxueli/xxl-job/blob/master/doc/db/tables_xxl_job.sql
> 在 `tables_xxl_job.sql` 的第一行请加入 `SET NAMES utf8mb4;`, 避免中文乱码

> docker-compose 中的默认绑定宿主机端口是 28888

启动方式
```bash
docker-compose up -d
```
> 启动后, 会实例化数据库数据, 如果需要重新导入, 请删除 `data` 目录

访问地址: http://localhost:28888/xxl-job-admin
