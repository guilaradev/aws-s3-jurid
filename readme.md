# Sistema simples de galeria de fotos

Teste para desenvolvedor Jurid.
Criar um app que tenha conexao com o AWS S3 usando Python.

Para poder rodar esse sistema basico, precisa de alguns passos.

 - 1: Instalar as bibliotecas:
   - ```pip install django django-storages Pillow boto3 ```

- 2 : Ter um ambiente para Python(Spawning environment shell)
   - ```pipenv shell```
   
- 3 : Para rodar o servidor:
   - ``` python manage.py runserver```
- 4: Subir os arquivos estaticos(caso seja necessario):
   - ``` python manage.py collectstatic```


Para acessar o /admin do Sistema, indico criar um novo usuário pelo seguinte comando :
``` python manage.py createsuperuser ```

