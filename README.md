# EmpreGO - Sistema de Gerenciamento de Vagas de Emprego

O **EmpreGO** é uma plataforma web desenvolvida para conectar empresas e candidatos, facilitando a busca e a aplicação para vagas de emprego. O sistema permite que empresas cadastradas publiquem vagas, gerenciem candidaturas e mantenham seus dados atualizados. Candidatos podem pesquisar vagas, se candidatar e enviar seus currículos.

---

## Índice
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação](#instalação)
- [Licença](#licença)

---

## Funcionalidades

### Para Empresas:
- **Cadastro**: Empresas podem se cadastrar na plataforma, fornecendo informações como nome, CNPJ, telefone e email.
- **Login**: Acesso seguro através de credenciais de login.
- **Publicação de Vagas**: Criar novas vagas de emprego, incluindo detalhes como título, descrição, tipo de vaga, local, salário e formato de trabalho.
- **Gerenciamento de Vagas**: Editar vagas existentes, alterar o status (ativa/inativa) e excluir vagas.
- **Visualização de Candidaturas**: Acesso à lista de candidatos para cada vaga, com informações de contato e currículos.
- **Gerenciamento de Status da Empresa**: A empresa pode ter seu status alterado (ativa/inativa) pelo administrador.

### Para Candidatos:
- **Busca de Vagas**: Pesquisar vagas de emprego utilizando palavras-chave (título e descrição).
- **Visualização de Detalhes da Vaga**: Acesso a informações completas sobre vagas de interesse.
- **Candidatura**: Aplicar para vagas de emprego, enviando informações pessoais e currículo.

---

## Tecnologias Utilizadas

### Backend:
- **Python**: Linguagem de programação principal.
- **Flask**: Framework web para construção da aplicação.
- **MySQL**: Sistema de gerenciamento de banco de dados relacional.
- **MySQL Connector**: Conector Python para interação com o banco de dados MySQL.

### Frontend:
![HTML5](<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>HTML5</title><path d="M1.5 0h21l-1.91 21.563L11.977 24l-8.564-2.438L1.5 0zm7.031 9.75l-.232-2.718 10.059.003.23-2.622L5.412 4.41l.698 8.01h9.126l-.326 3.426-2.91.804-2.955-.81-.188-2.11H6.248l.33 4.171L12 19.351l5.379-1.443.744-8.157H8.531z"/></svg>)
- **CSS3**: Estilização da página web.
- **JavaScript**: Lógica de interação com o usuário (apenas básico).
- **Bootstrap**: Framework CSS para responsividade e design.

---

## Instalação

Clone o repositório: git clone [URL do repositório] Substitua [URL do repositório] pela URL correta do seu repositório.

Crie um banco de dados MySQL: Crie um banco de dados com o nome especificado em config.py. Importe o esquema do banco de dados (script SQL, se existir um) para o banco criado.

Instale as dependências: pip install -r requirements.txt

Configure o arquivo config.py: Preencha as credenciais do seu banco de dados MySQL (DATABASE, USER, PASSWORD, HOST). Crie este arquivo se ele não existir, baseado no exemplo config_example.py (se existir).

Execute a aplicação: python app.py

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
