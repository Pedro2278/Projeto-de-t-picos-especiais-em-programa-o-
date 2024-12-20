# Escola App

**Escola App** é uma aplicação web desenvolvida em Ruby on Rails para gerenciar o cadastro e visualização de alunos. Este projeto foi criado com o objetivo de fornecer uma interface simples e funcional para gerenciamento de informações relacionadas aos alunos.

## 📋 Funcionalidades

- Listagem de alunos com visualização detalhada.
- Cadastro de novos alunos com informações como nome, idade, CPF, telefone, e-mail, endereço, entre outros.
- Exibição de uma página inicial com a tabela de todos os alunos cadastrados.
- Validação de dados no formulário para garantir consistência nas informações.
- Interface amigável utilizando `Bootstrap`.

## 🛠️ Tecnologias Utilizadas

- **Ruby on Rails**: Framework principal para o desenvolvimento da aplicação.
- **SQLite3**: Banco de dados usado no ambiente de desenvolvimento.
- **Bootstrap**: Para estilização e melhoria da experiência do usuário.
- **HTML** e **ERB**: Para renderização das views.

## 🚀 Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter os seguintes softwares instalados na sua máquina:

- [Ruby](https://www.ruby-lang.org/) (versão 3.0 ou superior recomendada)
- [Ruby on Rails](https://rubyonrails.org/) (versão 7.0 ou superior recomendada)
- [Node.js](https://nodejs.org/) e [Yarn](https://yarnpkg.com/) para gerenciamento de pacotes JavaScript

### Passos para execução

### Passos para execução

1. **Descompacte o arquivo zipado:**

   O projeto está compactado em um arquivo `.zip`. Extraia o conteúdo em uma pasta de sua preferência antes de continuar.

2. **Acesse a pasta do projeto:**

   ```bash
   cd escola_app
   
Instale as dependências do projeto:
bundle install
yarn install

Crie e migre o banco de dados:
rails db:create db:migrate

Inicie o servidor:
rails server
Acesse a aplicação:

Abra o navegador e vá para http://localhost:3000.

🗂️ Estrutura do Projeto
app/controllers: Contém os controladores que gerenciam a lógica da aplicação.
app/models: Contém os modelos que representam as entidades do sistema (como o modelo Aluno).
app/views: Contém as views responsáveis pela interface do usuário.
db/migrate: Contém os arquivos de migração para o banco de dados.


📄 Cadastro de Alunos
Os alunos podem ser cadastrados com as seguintes informações:
Nome: Nome completo do aluno.
Idade: Idade do aluno.
CPF: Cadastro de Pessoa Física, único para cada aluno.
Telefone: Contato telefônico.
E-mail: Endereço de e-mail para comunicação.
Data de Aniversário: Data de nascimento do aluno.
Endereço: Localização do aluno.
Observação: Campo adicional para informações relevantes.
Status: Indica se o aluno está ativo ou inativo.

🎨 Interface do Usuário
A interface foi projetada para ser simples e intuitiva:
Página Inicial: Exibe uma tabela com todos os alunos cadastrados, com botões para visualizar detalhes e cadastrar novos alunos.
Formulário de Cadastro: Uma página dedicada para adicionar informações de novos alunos.

📝 Licença
Este projeto está licenciado sob a MIT License.

