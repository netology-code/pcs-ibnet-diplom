# Курсовая работа по итогам модуля IBNET "Сети передачи данных и безопасность"

Курсовая работа необходима для проверки практических навыков, полученных в ходе прохождения курса **"Сети передачи данных и безопасность"**.

Мы создадим и настроим виртуальное рабочее место. Позже вы сможете использовать эту систему для выполнения домашних заданий по курсу.

## Задание

1. Создайте виртуальную машину Linux (лучше брать Ubuntu 20.04 desktop).
2. Установите службу FTP (например, vftp).
3. Установите службу HTTP (например, nginx).
4. Установите СОВ Suricata.
5. Настройте СОВ Suricata для анализа событий локальной сети.
6. Установите СОВ fail2ban.
7. Настройте СОВ fail2ban для блокировки подбора паролей по протоколам SSH, FTP, HTTP и HTTPS.
8. Заблокируйте все порты при помощи межсетевого экрана, кроме тех, которые необходимы для работы служб SSH, FTP, HTTP и HTTPS.
9. Проверьте правильность работы сервера (воспользуйтесь сканером **nmap** и средством для подбора паролей **hydra**):

- Службы SSH, FTP, HTTP и HTTPS должны быть доступны;
- Suricatа должна определять сетевые атаки;
- fail2ban должен блокировать перебор паролей для указанных служб.


## Итог

Итогом дипломной работы должны быть снимки экрана:

- работающих служб SSH, FTP, HTTP;
- определение атак с помощью СОВ Suricatа;
- блокировки подбора паролей с помощью СОВ fail2ban .
