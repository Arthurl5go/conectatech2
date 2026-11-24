# ConectaTech — Conecta Soluções Digitais

## Sobre o projeto

O **ConectaTech** é um site institucional desenvolvido para a empresa fictícia Conecta Soluções Digitais, como parte de um projeto acadêmico.

O site apresenta a empresa, seus serviços, notícias, equipe e canais de contato, além de possuir uma área restrita para usuários cadastrados.

## Tecnologias utilizadas

- **CMS:** Joomla 6.2.0
- **Servidor local:** Laragon
- **Linguagem:** PHP 8.3.33
- **Banco de dados:** MySQL
- **Versionamento:** Git e GitHub

## Funcionalidades

- Página inicial com apresentação institucional.
- Página sobre a empresa.
- Apresentação dos serviços oferecidos.
- Seção de notícias e artigos.
- Página da equipe.
- Página de contato com formulário.
- Área restrita para usuários cadastrados.
- Controle de acesso para diferentes tipos de usuários.
- Envio e aprovação de artigos.

## Estrutura do projeto

O repositório contém os arquivos do Joomla e a exportação do banco de dados:

- `administrator/` — área administrativa do Joomla.
- `components/` — componentes do sistema.
- `images/` — imagens utilizadas no site.
- `modules/` — módulos do Joomla.
- `plugins/` — plugins do sistema.
- `templates/` — modelos visuais.
- `conectatech.sql` — exportação do banco de dados.
- `README.md` — documentação do projeto.

## Como executar o projeto localmente

### 1. Preparar o ambiente

Instale e inicie o Laragon com PHP e MySQL.

### 2. Colocar os arquivos no servidor local

Copie os arquivos do projeto para a pasta:

`C:\laragon\www\conectatech`

### 3. Criar o banco de dados

No MySQL Workbench, crie um banco de dados chamado `conectatech`.

### 4. Importar o banco de dados

Utilize o MySQL Workbench para importar o arquivo `conectatech.sql` para o banco criado.

### 5. Configurar a conexão

Configure o arquivo `configuration.php` do Joomla com os dados da conexão local do MySQL, incluindo nome do banco, usuário, senha e caminhos necessários.

Esse arquivo é específico de cada ambiente e não está incluído no repositório.

### 6. Acessar o site

Com o Laragon e o MySQL em execução, acesse:

`http://localhost/conectatech`

## Banco de dados

O arquivo `conectatech.sql` contém a exportação do banco de dados utilizado pelo projeto, incluindo conteúdos, categorias, menus, usuários e configurações armazenadas pelo Joomla

## Desenvolvido para fins acadêmicos

**Projeto:** ConectaTech — Conecta Soluções Digitais  
**Plataforma:** Joomla  
**Repositório:** https://github.com/Arthurl5go/conectatech2