# Домашнее задание 8. Systemd
Выполнить следующие задания и подготовить развёртывание результата выполнения с использованием Vagrant и Vagrant shell provisioner (или Ansible, на Ваше усмотрение):

1. Написать service, который будет раз в 30 секунд мониторить лог на предмет наличия ключевого слова (файл лога и ключевое слово должны задаваться в /etc/sysconfig).
2. Из репозитория epel установить spawn-fcgi и переписать init-скрипт на unit-файл (имя service должно называться так же: spawn-fcgi).
3. Дополнить unit-файл httpd (он же apache) возможностью запустить несколько инстансов сервера с разными конфигурационными файлами.
4. *Скачать демо-версию Atlassian Jira и переписать основной скрипт запуска на unit-файл.

# Проверка
Все 4 таски выполнены в одной машине.
Для проверки:
1. Склонировать репозиторий
   `git clone`
2. Запустить vagrant
   vagrant up
