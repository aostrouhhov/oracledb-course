README
----
1. После выполнения задания 4 должна была остаться схема STUDENT_DB со всеми своими таблицами.

2. Создадим дамп базы. Запуск expdp в терминале в директории "Task 7 (dump)":
```
```

> CREATE DIRECTORY .. AS '...'
> expdp hr FULL=Y DIRECTORY=dpump_dir1 DUMPFILE=student_db.dmp
> impdp hr FULL=Y DIRECTORY=dpump_dir1 DUMPFILE=student_db.dmp
