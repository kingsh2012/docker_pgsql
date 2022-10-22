# docker_pgsql
## 时区修改
* 第一次启动以后生成pgdata目录
```
vi pgdata/postgresql.conf
#将
timezone = 'Etc/UTC'
log_timezone = 'Etc/UTC'
#替换为
timezone = 'Asia/Shanghai'
log_timezone = 'Asia/Shanghai'
```
