# Projeto desenvolvido com Angular e Java

### Pré-requisitos

- Git
- Node
- Java 11
- Mysql
- Angular 8

### Como rodar a API

Para rodar a api no eclipse, habilitar a opção ([X] Refresh using native hooks or polling) em
Window->Preferences->Workspace, para refresh automático no diretório de imagens após o upload no cliente web. A migração de dados será executada assim que o projeto for iniciado.

**Especificar usuário e senha do banco de dados**

Em `src/main/resources/application.properties` as propriedades `spring.datasource.username` e
`spring.datasource.password`.

### Rotas 

CRUD de produtos - URL: http://localhost:8080/admin <br />
Lista de produtos - URL: http://localhost:8080/  <br />
Carrinho de compras - URL: http://localhost:8080/cart

![screenshot01](screenshots/screenshot01.png)

![screenshot02](screenshots/screenshot02.png)

![screenshot03](screenshots/screenshot03.png)

![screenshot03](screenshots/screenshot04.png)

