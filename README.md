# Lista de Produtos SMD

O **Lista de Produtos** é um projeto simples de CRUD (Create, Read, Update, Delete) desenvolvido em Django. Ele permite adicionar, visualizar, editar e excluir produtos, fornecendo os campos de nome, preço e descrição. O projeto utiliza Django 4, Bootstrap 4 e Postgres como banco de dados.

## Requisitos do Sistema

### Integrantes:

- Leonardo Ravanelli

Certifique-se de ter os seguintes requisitos instalados no seu sistema antes de prosseguir com a instalação do Django CRUD Example:

- Python 3.x
- Django 4
- PostgreSQL (ou outro banco de dados compatível com Django)

## Instalação

Siga as instruções abaixo para configurar o ambiente e executar o projeto Django CRUD Example em diferentes sistemas operacionais: Windows, macOS e Linux.

### Windows

1. Abra o prompt de comando ou PowerShell.
2. Navegue até o diretório raiz do projeto.
3. Instale as dependências do projeto executando o seguinte comando:

pip install -r requirements.txt

4. Execute as migrações do banco de dados para criar as tabelas necessárias:

python manage.py migrate

5. Inicie o servidor de desenvolvimento executando o seguinte comando:

python manage.py runserver

8. O projeto estará disponível em http://127.0.0.1:8000/.

### macOS e Linux

1. Abra o Terminal.
2. Navegue até o diretório raiz do projeto django-crud-example.
3. Instale as dependências do projeto executando o seguinte comando:

pip install -r requirements.txt

4. Execute as migrações do banco de dados para criar as tabelas necessárias:

python manage.py migrate

5. Inicie o servidor de desenvolvimento executando o seguinte comando:

python manage.py runserver

6. O projeto estará disponível em http://127.0.0.1:8000/.

## Uso

Após iniciar o servidor de desenvolvimento, você poderá acessar as seguintes URLs:

- Página inicial: http://127.0.0.1:8000/
- Adicionar novo produto: http://127.0.0.1:8000/new
- Editar produto existente: http://127.0.0.1:8000/edit/<product_id>
- Excluir produto existente: http://127.0.0.1:8000/delete/<product_id>

Além disso, você pode acessar a interface de administração do Django para gerenciar os produtos em http://127.0.0.1:8000/admin. Para acessar a interface de administração, é necessário criar um superusuário executando o seguinte comando:

python manage.py createsuperuser

Siga as instruções para fornecer um nome de usuário, endereço de e-mail e senha.

## Considerações Finais

O **Lista de Produtos** é um projeto simples que demonstra as operações básicas de CRUD em Django. Ele pode ser usado como ponto de partida para o desenvolvimento de aplicativos mais complexos ou como uma referência para entender como implementar o CRUD usando o Django.

Lembre-se de que este projeto utiliza o banco de dados PostgreSQL por padrão. Se preferir usar outro banco de dados suportado pelo Django, você pode fazer as alterações necessárias no arquivo settings.py.

Divirta-se explorando e personalizando!
