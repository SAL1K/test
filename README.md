# Тестовое задание

Создал и подключился к виртуальной машине   
![](images/20240826_183739.png)   

### 1. Запустите команду ping для проверки сетевого соединения с сервером.   
![](images/20240826_184915.png)  
Проверил соеденение с серверов ya.ru и google.com
### 2. Используйте команду curl или wget для проверки доступа к веб-серверу по протоколу HTTP/HTTPS.   
Запрос по протоколу http/https с помощью curl:   
![](images/20240826_191051.png)  
Запрос по протоколу http/https с помощью wget:   
![](images/20240826_191223.png)
так же поднял сервер nginx на виртуальной машине, пробросил порты и получил ответ от своего сервера:   
![](images/20240827_140601.png)
![](images/20240827_140853.png)

### 3. Проверьте работу основных служб, таких как SSH, FTP, NFS и других, используя соответствующие команды для каждой службы.
Проверил работу служб SSH FTP NFS:   
![](images/20240826_192508.png)
Отобразил все остальные службы:   
![](images/20240826_192719.png)
### 4. Проверьте логи сервера на наличие ошибок и предупреждений, используя команду tail или grep.
с помощью команды tail мы можем увидеть только некоторое количество строк которое мы укажем в параметрах. В данных логах я не нашел никаких ошибок.   
![](images/20240826_193502.png)
Теперь с помощью команды grep мы можем найти ошибки по всему файлу    
![](images/20240826_194131.png)
Так же командой `tail -f` мы можем просматривать ошибки в реальном времени
### 5. Выполните базовую проверку производительности системы, используя команды top, htop, vmstat, iostat и другие.
программа top отображает запущенные процессы а так же разнообразную информацию о системе (uptime, memory usage, PID и другие:
![](images/20240826_195323.png)  

Программа htop улучшенная версия программы top с интерактивным интерфейсом:
![](images/20240826_195855.png)  

vwstat эта программа показывает основные показатели производительности системы:

![](images/20240826_200210.png)
iostat программа для мониторинга нагрузки на дисковую подсистему:

![](images/20240826_201014.png)
free программа по отображению информации об оперативной памяти:
![](images/20240826_201128.png)
df программа отображает все занятость место в разделах файловой системы linux:
![](images/20240826_201251.png)
sar программа для проверки системы под нагрузкой:
![](images/20240826_201458.png)
