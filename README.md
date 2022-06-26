# Git_hw
 
Postman. HW_1 

Создать запросы в Postman. 
Protocol: http IP: 162.55.220.72 Port: 5005 
1. EP_1  
Method: GET  
EndPoint: /get_method  
request url params: name: str age: int  
response: [ “Str”, “Str” ]  
2. EP_2   
  Method: POST    
  EndPoint: /user_info_3    
  request form data: name: str age: int salary: int    
  response:  
  
       {'name': name,  
              'age': age,    
        'salary': salary,    
        'family': {'children':   
                      [['Alex', 24], 
                      ['Kate', 12]],    
         'u_salary_1_5_year': salary * 4}}     
           
3. EP_3   
Method: GET   
EndPoint: /object_info_1   
request url params: name: str age: int weight: int   
response:  

            {'name': name,   
           'age': age,   
           'daily_food': weight * 0.012,   
           'daily_sleep': weight * 2.5}   
4. EP_4   
Method: GET   
EndPoint: /object_info_2   
request url params: name: str age: int salary: int   
response:  

           `{'start_qa_salary': salary, 
           'qa_salary_after_6_months': salary * 2, 
           'qa_salary_after_12_months': salary * 2.7, 
           'qa_salary_after_1.5_year': salary * 3.3, 
           'qa_salary_after_3.5_years': salary * 3.8, 
            'person': {'u_name': [user_name, salary, age],  
                       'u_age': age, 
                        'u_salary_5_years': salary * 4.2} } ` 
5. EP_5   
Method: GET   
EndPoint: /object_info_3    

request url params: name: str age: int salary: int   
response:  

           `{'name': name, 
           'age': age, 
           'salary': salary, 
           'family': {'children': [['Alex', 24], ['Kate', 12]], 
                      'pets': {'cat':{'name':'Sunny', 'age': 3},  
                      'dog':{'name':'Luky', 'age': 4}}, 
                      'u_salary_1_5_year': salary * 4} }` 
6. EP_6    
Method: GET   
EndPoint: /object_info_4   
request url params: name: str age: int salary: int   
response:  

           `{'name': name,
           'age': int(age), 
           'salary': [salary, str(salary * 2), str(salary * 3)]}`  
           
7. EP_7   
Method: POST   
EndPoint: /user_info_2   
request form data: name: str age: int salary: int   
response:  

           `{'start_qa_salary': salary, 
           'qa_salary_after_6_months': salary * 2, 
           'qa_salary_after_12_months': salary * 2.7,  
           'qa_salary_after_1.5_year': salary * 3.3, 
           'qa_salary_after_3.5_years': salary * 3.8, 
           'person': {'u_name': [user_name, salary, age], 
                      'u_age': age,  
                      'u_salary_5_years': salary * 4.2} }`  
**HW_2 Postman**  


http://162.55.220.72:5005/first  
1. Отправить запрос.  
2. Статус код 200  
3. Проверить, что в body приходит правильный string.  

http://162.55.220.72:5005/user_info_3  
1. Отправить запрос.  
2. Статус код 200  
3. Спарсить response body в json.  
4. Проверить, что name в ответе равно name s request (name вбить руками.)  
5. Проверить, что age в ответе равно age s request (age вбить руками.)  
6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)  
7. Спарсить request.  
8. Проверить, что name в ответе равно name s request (name забрать из request.)  
9. Проверить, что age в ответе равно age s request (age забрать из request.)  
10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)  
11. Вывести в консоль параметр family из response.  
12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)  

http://162.55.220.72:5005/object_info_3  
1. Отправить запрос.  
2. Статус код 200  
3. Спарсить response body в json.  
4. Спарсить request.  
5. Проверить, что name в ответе равно name s request (name забрать из request.)  
6. Проверить, что age в ответе равно age s request (age забрать из request.)  
7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)  
8. Вывести в консоль параметр family из response.  
9. Проверить, что у параметра dog есть параметры name.  
10. Проверить, что у параметра dog есть параметры age.  
11. Проверить, что параметр name имеет значение Luky.  
12. Проверить, что параметр age имеет значение 4.  

http://162.55.220.72:5005/object_info_4  
1. Отправить запрос.  
2. Статус код 200  
3. Спарсить response body в json.  
4. Спарсить request.  
5. Проверить, что name в ответе равно name s request (name забрать из request.)  
6. Проверить, что age в ответе равно age из request (age забрать из request.)  
7. Вывести в консоль параметр salary из request.  
8. Вывести в консоль параметр salary из response.  
9. Вывести в консоль 0-й элемент параметра salary из response.  
10. Вывести в консоль 1-й элемент параметра salary параметр salary из response.  
11. Вывести в консоль 2-й элемент параметра salary параметр salary из response.  
12. Проверить, что 0-й элемент параметра salary равен salary из request (salary забрать из request.)  
13. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request.)  
14. Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary забрать из request.)  
15. Создать в окружении переменную name  
16. Создать в окружении переменную age  
17. Создать в окружении переменную salary  
18. Передать в окружение переменную name  
19. Передать в окружение переменную age  
20. Передать в окружение переменную salary  
21. Написать цикл который выведет в консоль по порядку элементы списка из параметра salary.  
                      
 
