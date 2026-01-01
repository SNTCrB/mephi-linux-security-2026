# mephi-linux-security-2026

**Уникальный номер:** 374221

| Файл в репозитории | Раздел | Что проверяется |
| `mephi-screenshot.png` | 6 | Визуальное подтверждение (номер 374221) |
| `history.out` | Все | Выполненные команды |
| `stat.out` | 1, 3, 4 | Установка прав на домашнюю директорию и утилиты (`mysu_cat`, `mychown`) |
| `getcap.out` | 4 | Настройка привилегий (`cap_chown=ep`) |
| `passwd.out` | 1 | Управление пользователями (копия `/etc/passwd`) |
| `shadow.out` | 1 | Управление пользователями (копия `/etc/shadow`, хэши скрыты) |
| `group.out` | 1 | Управление группами (копия `/etc/group`) |
| `sudoers.out` | 5 | Настройка sudo |
| `sudoers_user1.out` | 5 | Настройка sudo для user1 (изменение времени) |
| `setuid_files.out` | 2 | Поиск файлов с битом set-UID |
| `suid_processes.out` | 2 | Мониторинг процессов с eUID=0 |
