# Lab 4 DevOps

Репозиторий с материалами лабораторной работы №4 по системному администрированию Linux.

## Содержимое
- `service.sh` — bash-скрипт запуска HTTP-сервиса
- `lab4-service.service` — unit-файл systemd
- `lab4-healthcheck.sh` — скрипт проверки доступности сервиса
- `inventory.example.ini` — пример Ansible inventory
- `site.yml` — Ansible playbook для развёртывания сервиса

## Проверка сервиса
Сервис отдаёт HTTP-страницу на порту 8000.

## Примечание
Приватные ключи, пароли и рабочий `inventory.ini` в репозиторий не добавляются.
