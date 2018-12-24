# PHP-linux-aemon
PHP守护进程shell脚本


工作中常常会遇到处理消息队列的消费者进程, 这样的进程是一个守护进程, 即一个服务。
服务通常写个shell脚本来管理, 查询服务的status, 启动start 关闭stop  重启reload。


利用 ./demo.sh  status|start|stop|reload 来管理
