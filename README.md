# Дипломный проект по тестированию API [reqres.in](https://reqres.in/)
<p align="left">
  <img width="50%" src="logo/reqres.png"/>
</p>


## Реализованные проверки по тест-кейсам  
✓ Запрос списка пользователей  
✓ Создание пользователя при вводе валидных данных  
✓ Получаение пользователя по переданному id  
✓ Обновление пользователя  
✓ Удаление пользователя  
✓ Ошибка авторизации с пустым обязательным полем password  

## Используемый стек
<p align="center">
<code><img width="6%" title="Python" src="logo/python.svg"></code>
<code><img width="6%" title="PyCharm" src="logo/pycharm.svg"></code>
<code><img width="6%" title="PyTest" src="logo/pytest.svg"></code>
<code><img width="6%" title="Requests" src="logo/requests.png"></code>
<code><img width="6%" title="Swagger" src="logo/swagger.png"></code>
<code><img width="6%" title="GitHub" src="logo/github.png"></code>
<code><img width="6%" title="Jenkins" src="logo/jenkins.svg"></code>
<code><img width="6%" title="Allure" src="logo/allure.svg"></code>
<code><img width="6%" title="Allure" src="logo/allure_testops.png"></code>
<code><img width="6%" title="Allure" src="logo/jira.png"></code>

</p>

## <img width="3%" title="Jenkins" src="logo/jenkins.svg">Сборка в Jenkins
[JOB](https://jenkins.autotests.cloud/job/Requests_API/)
<p align="left">
  <img width="90%" src="logo/jenkins_job.png"/>
</p>

## <img width="3%" title="Jenkins" src="logo/allure.svg">Allure report
[Ссылка на отчет](https://jenkins.autotests.cloud/job/Requests_API/4/allure/)
##### После прохождения тестов, результаты можно посмотреть в Allure отчете, где так же содержится ссылка на Jenkins.
<p align="left">
  <img width="90%" src="logo/screenAllure.png"/>
</p>

##### Во вкладке Graphs можно посмотреть графики о прохождении тестов, по их приоритезации, по времени прохождения и др.

<p align="left">
  <img width="90%" src="logo/allure_graphs.png"/>
</p>

<!-- Allure TestOps -->

### <img width="3%" title="Allure TestOps" src="logo/allure_testops.png"> Интеграция с Allure TestOps
### [Dashboard](https://allure.autotests.cloud/project/3378/dashboards)
##### Так же вся отчетность сохраняется в Allure TestOps, где строятся аналогичные графики.
![This is an image](logo/testops_dashboard.png)

#### Во вкладке со сьютами, мы можем:
- Управлять всеми тест-кейсами или с каждым отдельно
- Перезапускать каждый тест отдельно от всех тестов
- Настроить интеграцию с Jira
- Добавлять ручные тесты и т.д

![This is an image](logo/testopsresults.png)

<!-- Jira -->

### <img width="5%" title="Jira" src="logo/jira.png"> Интеграция с Jira
##### Настроив через Allure TestOps интеграцию с Jira, в тикет можно пробросить результат прохождение тестов и список тест-кейсов из Allure

![This is an image](logo/jira_results.png)