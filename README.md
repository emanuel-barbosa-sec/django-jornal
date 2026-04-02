# Jornal de Notícias com Django
Aplicação web desenvolvida com django que simula um jornal online.

## Funcionalidades
Lista todos os artigos publicados
Página individual de cada artigo
Sistema de comentários por artigo

## Como usar o projeto
1. Instalar as dependências:
pip install -r requirements.txt

2. Aplicar as migrações:
python manage.py migrate

3. Criar superusar para usar o painel de admin:
python manage.py createsuperuser

4. Iniciar o servidor:
python manage.py runserver

5. Abrir: http://127.0.0.1:8000/

## Painel de admin
Acessar o painel no: http://127.0.0.1:8000/admin/
Para acessar é necessário criar um superuser com o comando (passo 3) e fazer login com as credenciais criadas.

