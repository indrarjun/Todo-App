# Todo-App

This is a Todo app which stores the given task in a table when pressed on <img src='Screenshots/plus-icon.png' width=20> icon and deletes certain task when pressed on <img src='Screenshots/trash-icon.png' width=20>.<br>
We used [![Libraries](https://skills.thijs.gg/icons?i=django,html,bootstrap,postgresql)](https://skills.thijs.gg)
_____
## Sample Image
<img src='Screenshots/sample-image.png'>

## Prerequisists

Download and install Python and PostgreSQL<br>
Install django and psycopg2

```python
pip install django 
pip install psycopg2
```

After downloading the file from git.
Change the settings.py file according to your DB credentials
<img src='Screenshots/change access to db.png'>
 
 Finally run the below command in cmd or powershell
 ```python
 python manage.py runserver
 ```
 After that copy the link and add /Todos/list at the end.<br>
 
 <img src='Screenshots/after running python manage.py runserver.png'>
  Example:
  
 ```html
 http://127.0.0.1:8000/Todos/list/
 ```
