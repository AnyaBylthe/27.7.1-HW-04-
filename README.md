# 27.7.1-HW-04

Добавьте в ваш проект чата логгирование сообщений от других участников чата и своих сообщений.

Для этого напишите класс Logger, через который будет проходить вся работа с файлом логов. Сохраняйте сообщения в файл на диске, можете назвать его log.txt. При создании объекта логгера должно производиться открытие файла, а при его разрушении — закрытие файла (концепт RAII).

Реализуйте в классе два метода:

запись строки логов в файл;
чтение одной строки из файла.