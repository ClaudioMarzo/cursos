# Alura Space

### Objetivo:
-  Botar em prática python como back-end, subindo um banco local

### Tecnologias: 
- Back: Django/Python
- Front: HTML, CSS, JS

### Screen
![ALURA GIF](alura_gif.gif)
#### Atualizando pacotes do Django
- pip install django


#### Configurando e executando a API:
O bloco a seguir irá configurar um ambiente virtual python, instala as dependências e executa a API.

- python -m venv venv
- source venv/bin/activate(linux)
- venv\Scripts\activate(Windowns)
- python -m pip install -r requirements.txt
- python manage.py makemigrations
- python manage.py migrate
- python manage.py runserver