# Django-with-MySql-Database

steps:
   1 . pip install mysql-connector
   2.  pip install pymySql
   
   
   configuring data base into settings.py:
   
       from pathlib import Path
       import pymysql
       pymysql.version_info=(1,4,2,'final',0)
       pymysql.install_as_MySQLdb()
       
       
    DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'Database name',
        'USER':'username',
        'PASSWORD':'userpassword',
        'HOST': 'localhost',
        
    }
}   
