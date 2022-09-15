# PrototypeOnlineSchool

Feito por Vitor Campos

Figma Wireframe com páginas do sistema projetado:

https://www.figma.com/file/LSOGLCUygaZixfuiDAsEGR/Prototype-Online-School?node-id=0%3A1


Tecnologias que seriam utilizadas:


Nodejs
CSS
HTML
React
React-router
Express
TypeScript
MySQL
JWT
Axios
Lint
Jest
Mocha
Chai
Sinon
Sequelize
bcrypt
dotenv

Métodos:

TDD
SOLID

Desenho do sistema de database:

![alt text](https://github.com/Vitor-742/PrototypeOnlineSchool/blob/main/Desenho_database.png?raw=true)

---- ENDPOINTS DO BACKEND ----

POST /Login - 
  Recebe email e senha e faz login no banco de dados retornando informações do usuário com JWT de validação.
  
GET /Lessons/(id) -
  Com id do aluno retorna as aulas que estão programadas para ele.
  
GET /FixedLessons/(id) - 
  Com o id do aluno retorna as aulas fixadas na home.
  
POST /FixedLessons -
  Recebe o id do vídeo e o coloca em destaque na home.

GET /Projects/(id) -
  Com o id do aluno, retorna projetos que estão pendentes para ele.
  
POST /Projects - 
  Com nome e dados do projeto e id do facilitador, o projeto é criado e colocado em andamento para todos os alunos.
  
GET /Absences/(id) - 
  Com o id do aluno, retorna a quantidade de faltas dele.
  
POST /Absences -
  Recebe o id do aluno e insere a falta para ele.
  
GET /FullLessons - 
  Retorna todas as aulas do momento.
  
GET /ProductsDone/(id) -
  Com o id do facilitador, recebe os projetos criados por ele e já entregues pelos alunos.
  
GET /AllAbsences/(id) - 
  Com id do facilitador, retorna as faltas de todos seus alunos.
  
GET /Video -
  Retorna todos os vídeos da tabela Videos.
  
GET /Users - 
  Retorna todos os users e as suas informações.
  
PUT /Users -
  Recebe informações novas do usuário e as atualiza.
  
