## skript-playertag
skript插件脚本编写的玩家称号插件

## 安装
1. 先决条件：spigot/paper服务端、PlaceholderAPI插件、聊天格式插件、mysql/maridb
2. 安装skript
3. 安装skript拓展:skript-placeholders、skript-reflect
4. 脚本放入`[yourserver]\ plugins\Skript\scripts\`下
5. 更改自定义数据库值：
```
	set {easy-playertag_db_host} to "jdbc:mysql://127.0.0.1:3306/"
	set {easy-playertag_db_db} to "playertag"
	set {easy-playertag_db_user} to "root"
	set {easy-playertag_db_password} to "passwd"
```
6. 重启服务器或执行`sk reload <对应脚本>`

## 其他
脚本偏向自用，还很多bug
