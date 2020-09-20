## Задача: 

    Ann scanned a QR code of an item, she tried to open the image but it seems it was corrupted, can you identify what is Ann lost item?

## Ответ:
    Flag{Aw3s0m3-Y0u-G0t-th1s}

## Автор: 
    CyberTalents

## Разбор:
    1. Непонятный файл -> для начала нужно определить нам тип файла, пробуем file help_ann_please
    2. К сожалению нам это ничего не дало,лезем в hex и замечаем,что это PNG файл и кажется кто-то поломал наш заголовок 
    3. Чиним его просто заменяя 00 на 89 
    4. Получаем QR код, сканим его и получаем флаг 

