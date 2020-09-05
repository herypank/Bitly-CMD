# CMD-bitly
 

## Описание проекта.   
Этот проект позволяет создать сокращённую ссылки. Посмотреть переходы по вашей сокращённой (bit.ly) ссылке через командную строку.     
## Пример использования.   

![](example.gif)  
   
## Подготовка к запуску.  
Уставновить Python 3+.
```
sudo apt-get install python3
```
Установить, создать и активировать виртуальное окружение.
```
pip3 install virtualenv
python3 -m venv env
source env/bin/activate
```
Установить библиотеки командой.  
```
pip install -r requirements.txt  
```
    
[Сервис Bitly](https://bit.ly/) — зарегистрируйтесь    
Создайте файл .env в него надо прописать ваш bitly token в переменную **BITLY_TOKEN** его можно получить [**тут**](https://bitly.com/a/oauth_apps)    
    
**Пример**  
```
BITLY_TOKEN = 6dc03540f1226195ccbc4307543df8eddb066878
```

## Запуск кода.  
```
python3 request.py https://dvmn.org/modules/
```
**После request.py должна быть ваша ссылка**
