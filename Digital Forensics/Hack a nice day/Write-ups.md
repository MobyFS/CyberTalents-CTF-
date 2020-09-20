## Задача: 

    can you get the flag out to hack a nice day. Note: Flag format flag{XXXXXXX}

## Ответ:
    flag{Stegn0_1s_n!ce}

## Автор: 
    CyberTalents

## Разбор:
    1. exiftool info.jpg
    2. Видим интересный коммент: badisbad 
    3. Пробуем применить steghide extract -sf info.jpg 
    4. Вводим пароль и получаем файлик с флагом flag{Stegn0_1s_n!ce}

