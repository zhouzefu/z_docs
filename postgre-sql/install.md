# Ubuntu 系统安装 PostgreSQL

## 更新软件包列表
```bash
sudo apt update
```

## 升级软件包
```bash
sudo apt upgrade -y
```

## 安装 PostgreSQL
```bash
sudo apt install postgresql -y
```

## 查看PostgreSQL 启动状态
```bash
systemctl status postgresql
```

## 启动 PostgreSQL 服务
```bash
sudo systemctl start postgresql
```

## 设置 PostgreSQL 服务开机自启
```bash
sudo systemctl enable postgresql
```

## 检查 PostgreSQL 服务状态
```bash
sudo systemctl status postgresql
``` 

## 重启 PostgreSQL 服务
```bash
sudo systemctl restart postgresql
```

## 修改 PostgreSQL 密码
```bash
sudo -u postgres psql
```

```sql
ALTER USER postgres WITH PASSWORD 'new_password'; 
```
