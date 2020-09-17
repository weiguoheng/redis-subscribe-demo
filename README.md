# redis-subscribe-demo
1，composer install
2，php artisan redis:subscribe执行监听任务
3，再打开一个窗口执行php artisan redis:push {message}
4，第一个窗口会接收到第二个脚本发送的message
