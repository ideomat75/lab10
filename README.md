# lab10
1)создаем папкуи перехом в нее
![image](https://user-images.githubusercontent.com/90716549/169365023-120a011c-66cb-454f-9a9b-27ad97037fe2.png)

2)создаем пхп файл 

3) создаем рабочее окружение(vagrant file) c помощью команды vagrant init -m bento/ubuntu-20.04

![image](https://user-images.githubusercontent.com/90716549/169365799-1337f698-2ffd-431d-a77c-f99d457705ab.png)

![image](https://user-images.githubusercontent.com/90716549/169365878-2e709ed8-1c86-4762-8f34-91bcadd61bbd.png)

4)пример vagrant файла 

![image](https://user-images.githubusercontent.com/90716549/169366054-1f248267-938d-4497-a23a-d2e608a2a786.png)

5)продолжаем работу с vagrant файлом

![image](https://user-images.githubusercontent.com/90716549/169368063-13a66600-9a43-4892-8224-b6aed2376d36.png)

6)создаем файл provision.sh для удобства настроки системы куда пишем настроку и запуск nginei X

![image](https://user-images.githubusercontent.com/90716549/169370140-476b02b0-db12-47b1-b4e8-7fcc9293d8a4.png)

7)далее запускаем команду vagrant up 

7.1) неболшая проьлема из СВО vagrant не может подгружать образы для этого надо использовать прокси, но всеравно работа не корректна

8) проверка работы нашей виртуальной машины  

![image](https://user-images.githubusercontent.com/90716549/169371824-57e02fb5-4a55-4188-8cf2-f30fbb76874d.png)

через ssh (сетевой протокол) подключаемся к нашей виртуальной машине 

![image](https://user-images.githubusercontent.com/90716549/169372081-80dec554-63fd-438a-88f3-f569ff679bf5.png)

проверяем работу нашего ngine X

![image](https://user-images.githubusercontent.com/90716549/169372272-c774e094-b3ce-4519-b140-d7de509e68d5.png)

