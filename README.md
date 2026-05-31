 mvc-web-cadastrodealunos
Esse projeto foi uma atividade para, usando o padrão MVC, criar um programa que consegue realizar o cadastro de alunos e depois exibe os cadastros.

Arquitetura MVC

Model
Aluno.java
Responsável por representar a entidade Aluno e suas regras de negócio básicas, como a validação do nome.

Controller
AlunoController.java

Responsável por receber as requisições HTTP, processar os dados enviados pelo formulário e encaminhar as informações para as views.

View
alunos-form.html

Tela responsável pela entrada dos dados do aluno.

alunos-lista.html

Tela responsável pela exibição dos alunos cadastrados.

Tecnologias Utilizadas
Java
Spring Boot
Thymeleaf
Maven
Git
GitHub

Estrutura do Projeto
src
└─ main
   ├─ java
   │  └─ com.exemplo.mvc
   │      ├─ controller
   │      │   └─ AlunoController.java
   │      ├─ model
   │      │   └─ Aluno.java
   │      └─ MvcApplication.java
   │
   └─ resources
      ├─ templates
      │   ├─ alunos-form.html
      │   └─ alunos-lista.html
      └─ application.properties

Como Executar
1.Clone o repositório
git clone https://github.com/PedroTonon/mvc-web---cadastro-de-alunos
2.Abra o projeto no VS Code
3.Execute a classe MvcApplication
4.Acesse no navegador
http://localhost:8080/alunos
