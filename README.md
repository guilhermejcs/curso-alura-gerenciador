# Curso Alura Java Servlet
## Tecnonlogias:

- Java Open JDK 16
- TomCat 10

## Trabalhando com Post e Get

### Aula 1

- Configuração do ambiente
  - Java SKD
  - IDE Eclipse
  - Servidor TomCat

- Conceitos básicos de servlet
- Criação de um servlet "Oi Mundo"

* Criação de uma servlet pelo comando "New"
* Passagem de parâmetros

### Aula 4

* Passagem de parâmetros utilizando os métodos Get e Post

* Criação do formulário para envio de dados

* Diferenças na forma de envio dos dados utilizandos os métodos Get e Post

### Aula 7

* Limitando o serviço apenas ao método Post



## Definindo o nosso modelo

### Aula 2

* Criação das classes:
  * Empresa
    * é o objeto que representará o modelo
  * Banco
    * simula o banco de dados que vai receber as informações

### Aula 5

* Criação do servlet para listar as empresas cadastradas

## Páginas dinâmicas com JSP

### Aula 2

* Tirando o código html de dentro da classe java
* Criação de um arquivo JSP (Java Server Page)
* Usando scriptlet para fazer páginas dinâmicas  <% %>

### Aula 6

* Passando informações para a JPS com o método Dispatcher
* Retirando o código html da classe NovaEmpresaServlet

### Aula 8

* Retirando o código html da classe ListaEmpresasServlet

## JSTL e Expression Language

### Aula 2

* Substituindo scriptlet por Expression Language
  * <% %> vs ${ }

### Aula 5

* Alteração do Tomcat 10 para o 9 por incompatibilidade com a lib JSTL
* Alteração das importações do jackarta para javax
* Refatoração do arquivo listaEmpreas para substituir os scriptlet pelas funcionalidades da lib JTSL

### Aula 8

* Utilização dos comandos da lib JSTL core
  * c:url - cria uma variável que pode ser utilizada como link
  * c:if - cria uma ação condicional

### Aula 10

* Utilização dos comandos da lib JSTL fmt
  * fmt - formatação de datas

## Redirecionando o fluxo

### Aula 2

* Enviando um informação de uma Servlet para outra Servlet utilizando o Dispatcher

### Aula 5

* Usando o redirecionamento response.sendRedirect

## Completando o CRUD

### Aula 2

* Explicação dos métodos a serem implementados

### Aula 4

* Utilizando Iterator
* Removendo uma empresa
* Usando o redirecionamento

### Aula 6

* Criando o formulário de alteração da empresa

### Aula 7

* Editando os dados da empresa