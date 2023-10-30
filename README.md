# fiddler_sniffer_example
Пример работы со сниффером Fiddler.

## 1 задание
![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/1dd2320b-5eee-4dda-86a6-0517df3c7503)

Ссылка: http://task.test.ivi.ru/login
1. Откроем Fiddler.

2. Откроем ссылку http://task.test.ivi.ru/login.
   
3. Введем любые данные в поля формы (например login - 1, password - 1).
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/ddcd442c-c6e3-47e0-9a42-c18e0ae6e42a)
   
4. Перейдем в Fiddler и посмотрим на Headers в response.
   
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/9e4d80da-5dc9-4c59-9b2c-b0a9dfade258)
   
5. Нашли надпись **curl /get_login to get your login and password**, которая означает, что для получения логина и пароля необходимо перейти по ссылке http://task.test.ivi.ru/get_login.
   
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/f4d5bff2-499c-411b-9e8b-9109f6c60f7c)

6. Перейдем по ссылке **http://task.test.ivi.ru/get_login**, чтобы получить логин и пароль.
   
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/710fc79a-f97a-4ce1-af0d-7e80d5b2d4cc)

7. Вернемся назад и введем данные в форму.
   
    ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/0feaeb31-2ef7-4c4b-9b40-8714be0baac0)
    
8. Нажмем на кнопку "вход". Перешли к следующему заданию.

## 2 задание
![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/97efd83f-dcd0-44d9-be35-aa088065f5dd)


1. Выберем любой вариант, чтобы получить подсказку.
   
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/74a31fff-75d1-4ad8-bc10-5872a30ca7d9)
   
2. Откроем Fiddler и найдем запрос.
   
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/3fb254ed-ff71-4243-b2e2-535c5792dbb5)
   
3. Поставим breakpoint на request, т.е. на запрос. Перейдем в Rules -> Automatic Breakpoints и выберем "Before requests". 
   
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/84eb8ac0-c759-4e6f-8d6c-6c1e0404d685)
   
4. Выполним запрос еще раз и откроем Fiddler. Request запроса отображается справа. Его можно отредактировать.
   
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/ea24693a-af96-4c75-96d7-7111c2ccb653)

5. Изменим в данных выбранный ответ на "да".
    
    ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/6bdb0a07-9492-4821-987e-98a9cc2c3a1a)

6. Для того, чтобы отправить запрос, нажмем Run to Completion.
    
7. Посмотреть в response Headers.
    
    ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/58461089-1b54-4ca4-8ef1-786950d9a48a)

8. Перейти по ссылке **http://task.test.ivi.ru/wanna_finish**.

## 3 задание
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/9a6136e5-9da3-4a9b-897e-7d20345f2d89)
   
1. Скопировать json и вставить в любой json редактор.
2. Найти необходимую информацию о платформах. Было найдено 4 платформы.
   
   ![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/846be3d4-8746-4726-8924-4282354c4e09)
   
3. Написать в поле ввода цифру 4 и нажать "вход".

   
## Результат
![image](https://github.com/Prostotina/fiddler_sniffer_example/assets/40625180/0a7ce438-1583-4f22-86e1-4c372f121367)

   
