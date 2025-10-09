
# Анализ инцидентов с использованием Splunk и MITRE ATT&CK

## 1. Цель
Обнаружение атаки Brute Force на SSH с помощью SIEM и Sigma.

## 2. Инструменты
- Splunk Free
- Metasploitable (цель)
- Hydra (имитация атаки)
- Sigma (правило детектирования)

## 3. Этапы
1. Установка и настройка Splunk.
2. Подключение логов `/var/log/auth.log`.
3. Написание Sigma-правила для Brute Force.
4. Имитация атаки через Hydra.
5. Обнаружение атаки в Splunk.

## 4. Результат
- Успешно обнаружена атака по IP-адресу.
- Правило соответствует тактике **Credential Access (T1110)** из MITRE ATT&CK.

## 5. Вывод
SIEM + Sigma + MITRE ATT&CK = мощный стек для SOC-аналитика.
