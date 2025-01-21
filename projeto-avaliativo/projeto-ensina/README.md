# upes-022024-proj-desenvolvimento-de-software-visual
Projeto acadêmico de Desenvolvimento de Software Visual do curso de Engenharia de Software, um sistema de gerenciamento escolar.


ENSINA - Sistema de Gerenciamento de Escola Quilombola

Descrição
O ENSINA (Entidade Nacional de Sistemas e Inovação para Necessidades Acadêmicas) é um sistema desenvolvido para auxiliar na gestão de escolas quilombolas, proporcionando uma gestão eficiente dos alunos e recursos educacionais. O objetivo é garantir que a administração escolar seja intuitiva e eficaz, atendendo às necessidades específicas das comunidades quilombolas.


FUNCIONALIDADES

- Cadastro e gerenciamento de alunos
- Matricula e edição de informações dos alunos
- Integração com banco de dados MySQL
- Interface intuitiva para gestão
- API documentada com Swagger


ESTRUTURA DO PROJETO

BACKEND
O backend foi desenvolvido utilizando .NET 8.0 com Entity Framework Core e banco de dados MySQL.

Principais arquivos:
- Program.cs - Configuração do servidor, CORS e Swagger
- Banco.cs - Configuração do banco de dados e entidades
- Ensina.csproj - Definição das dependências do projeto

Tecnologias utilizadas no backend:
- .NET 8.0
- Entity Framework Core
- MySQL
- Swagger para documentação da API


FRONTEND
O frontend foi desenvolvido utilizando React.js, com React Router para navegação e Axios para comunicação com a API.

Principais arquivos:
- App.jsx - Definição das rotas
- index.jsx - Ponto de entrada da aplicação
- index.html - Template principal
- layout.jsx - Estruturação das páginas com cabeçalho e rodapé

Tecnologias utilizadas no frontend:
- React 18.3.1
- React Router
- Axios
- React Scripts


INSTALAÇÃO E EXECUÇÃO

BACKEND

- Clone o repositório:
git clone https://github.com/otavio-wenzel/upes-202402-desenvolvimento-de-software-visual.git
cd projeto-avaliativo\projeto-ensina\ensina-backend

- Configure o banco de dados MySQL e aplique as migrações:
dotnet ef database update

- Execute o backend:
dotnet run


FRONTENDD

- Acesse a pasta do frontend:
cd projeto-avaliativo\projeto-ensina\ensina-frontend

- Instale as dependências:
npm install

- Inicie o frontend:
npm start



A aplicação estará disponível em http://localhost:3000.


API Endpoints

Os principais endpoints da API incluem:
- GET /alunos - Retorna a lista de alunos
- POST /alunos - Cadastra um novo aluno
- PUT /alunos/:id - Atualiza dados de um aluno existente
- DELETE /alunos/:id - Exclui um aluno

A documentação da API está disponível via Swagger em http://localhost:5120/swagger.


LICENÇA
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.


Desenvolvido por: OTAVIO WENZEL - Engenheiro de Software apaixonado por inovação e tecnologia.