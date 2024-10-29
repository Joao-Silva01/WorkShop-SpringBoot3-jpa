# WorkShop
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Joao-Silva01/WorkShop-SpringBoot3-jpa/blob/main/LICENSE)
# Descrição
Este projeto é um serviço web utilizando Spring Boot, JPA e Hibernate, estruturado em camadas lógicas 
(resource, service, repository). O projeto utiliza um banco de dados H2 para testes e implementa operações CRUD (Create, Retrieve, Update, Delete) com tratamento de exceções.

# Como iniciar o projeto
### Pré-requisitos
- ter instalado o [Java development kit (JDK23)](https://www.oracle.com/br/java/technologies/downloads/)
  <br>Comando para verificar se você tem o JDK instalado
  ```
  javac -version
  ```
- ter instalado o [Maven](https://maven.apache.org/download.cgi)
  <br>Comando para verificar se você tem o Maven instalado
  ```
  mvn -v
  ```

### Passo a passo
1. Clone o repositório
```
git clone https://github.com/Joao-Silva01/WorkShop-SpringBoot3-jpa.git
```
2. Entre no repositório
```
cd ./WorkShop-SpringBoot3-jpa
```
3. Faz a compilação do projeto
```
mvn compile
```
4. Execute o projeto
```
mvn spring-boot:run
```
5. Para dar stop na aplicação é só apertar o **Ctrl+C**

# Tecnologias
- Spring Boot
- JPA/Hibernate
- Maven
- H2
