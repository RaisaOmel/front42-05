# Работа с графикой
## img
- единственный тег сохраняющий пропорционально изменяется по 1 из сторон
- object-fit -растяивание img по блоку (нужно обязательно указать ширину и высоту картинки)
    width: 100%;
    height: 160px;
    object-fit: cover;
    object-position - позиционирование
## фон
- bgc ( background-color ) - заливка фона 1 цветом
- bgi (background-image: url("../img/Screenshot_1.jpg")) - на фон устанавливаем картинку. по умолчению картинку кланирует по горизонтали и по вертикали (отключить background-repeat: no-repeat;).
- bgr (background-repeat)  управляем кланирование патерна (картинкой)
- bgs (background-size) - изменяем размер фоновой картинки
- bgp (background-position) -позиционируем фоновой картинкой (0 0 -позиция верх и лево)
- bga (background-attachment: fixed)  - фиксация фоновой картинки
  
