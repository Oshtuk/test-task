Чем отличается apt update от apt upgrade? 
apt update — обновляет список пакетов из репозиториев
apt upgrade — обновляет установленные пакеты до актуальных версий, используя список, полученный через apt update
Как проверить, слушает ли сервис нужный порт?
ss -tuln | grep <порт>, netstat -tuln | grep <порт>, lsof -i :<порт>
Какие команды используются для диагностики сетевых проблем?
ping <ip/host> , traceroute <host>, curl <url>, telnet <host> <port> / nc -zv <host> <port>
