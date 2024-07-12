1 - instalar python 3.6.2 en su sistema

2 - ejecute en su terminal los siguientes: 
3 - .\Venv\Bin\Activate
4 - pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host=files.pythonhosted.org -r requirements.txt
5 - cd api => Ingresa a la carpeta api

6 - Tener instalado de preferencia PostgresSQL 10.23 enlace de descargar(https://www.filehorse.com/download-postgresql/84316/download/)
7 - Verifica el archivo settings.py este configurado con sus credenciales DB
8 - py manage.py migrate => ejecutar las migraciones
9 - py manage.py runserver => levante el proyecto