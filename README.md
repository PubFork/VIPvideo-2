# VIPvideo

主目录文件结构及说明：

admin  后台管理目录，请改名

save    数据保存目录,注意：权限必须为755以上,不然无法后台更新配置;

cache 文件缓存 目录   注意：权限必须为755以上,不然出错;

include  引用文件 目录 

player   播放器目录

plus     插件存放目录

source      资源目录

templets   模版 目录

video      模块目录 

index.php  首页文件

v.php     vip调用页

api.php     jsonp服务模块

config.php  配置文件

favicon.ico  网站图标

crossdomain.xml   访问权限控制文件  注意：文件直接拷贝到网站根目录下，很重要；

data.php     本地数据库文件

parse.php   模块调用文件

play.html   框架调用文件

so.html   搜索页

404.html  404页


使用前，需登录后台 "/admin" ,默认账号：admin 默认密码：admin888


系统设置-基本设置-网站路径 默认为v3 ，修改为自己上传的目录，如果是根目录，留空即可正常运行；


其他配置请自行摸索，这里不再说明；
