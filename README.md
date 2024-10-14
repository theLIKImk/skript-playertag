## skript-playertag
skript插件脚本编写的Minecraft玩家称号插件

## 安装
1. 先决条件：spigot/paper服务端(只在1.21/1.20.4做了测试)、PlaceholderAPI插件、聊天格式插件、mysql/maridb数据库
2. 安装skript(目前2.9.2+)
3. 安装skript拓展:skript-placeholders、skript-reflect
4. 脚本放入`[yourserver]\ plugins\Skript\scripts\`下(没有文件夹自行创建)
5. 重启服务器

## 使用
1. 更改自定义数据库值：
```
	set {easy-playertag_db_host} to "jdbc:mysql://127.0.0.1:3306/"
	set {easy-playertag_db_db} to "playertag"
	set {easy-playertag_db_user} to "root"
	set {easy-playertag_db_password} to "passwd"
```
2. 使用聊天格式化插件在每条聊天消息前加上PAPI变量`%easy-playertag_player_tag%`
3. 重载即可

## PAPI
玩家当前称号显示 `%easy-playertag_player_tag%`  
玩家当前称号ID `%easy-playertag_player_tag_setid%`  
显示指定称号ID的内容 `%easy-playertag-tagid_<TagID>%`


## 其他
脚本偏向自用，还很多bug
