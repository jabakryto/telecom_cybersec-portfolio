# Неделя 5: SOC без SIEM


## 1. Анализ логов вручную
- Выполнена атака SSH brute-force на Metasploitable.
- Обнаружено 12 неудачных попыток входа с IP 192.168.0.101.
- Команда: `grep "Failed password" /var/log/auth.log | awk '{print $(NF-3)}' | sort | uniq -c`

## 2. MITRE ATT&CK
- Изучены тактики: Initial Access, Execution, Credential Access.
- Создана таблица с техниками и методами детектирования.

## 3. Sigma-правило
- Написано правило для обнаружения SSH brute-force.
- Готово к интеграции в любую SIEM-систему.

## Вывод
Даже без Splunk/ELK можно развивать навыки SOC-аналитика через анализ логов, MITRE ATT&CK и Sigma.
