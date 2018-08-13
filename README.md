# Univem Aula 2018
Disciplina de [Teste de Software (Pós Univem)](http://poswebmovel.compsi.univem.edu.br) - Ferramentas e Referências

## Ferramentas
* IDE JAVA: [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
* VM Java: [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* API Manual: [Postman](https://www.getpostman.com/apps)
* Docker (Mac/Windows/Linux): 
    * https://store.docker.com/editions/community/docker-ce-desktop-windows
    * https://store.docker.com/editions/community/docker-ce-desktop-mac
    * https://docs.docker.com/install/linux/docker-ce/ubuntu/
    * https://kitematic.com (GUI - Windows/Linux)
      * Ubuntu: https://github.com/docker/kitematic/releases

## Prática 1 – Técnicas Funcionais (JUnit IR)
* **Assunto:** Testes Unitários (Técnicas Funcionais)
* **GitHub:**  https://github.com/andvicente/JUnit_ImpostoRenda
* **Ferramenta(s):**
  * [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
  * [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
  * JUnit
* **Exercício**
  * **( 1 )** Testes do Salário Líquido (Professor e Funcionário) 
## Prática 2 – JUnit + Cobertura 
* Testes Cartão (Validação - Luhn e BIN)
* **GitHub:** https://github.com/andvicente/Cartoes-CodeCoverage 
* **Ferramenta(s):**
  * [JaCoco](https://github.com/jacoco/jacoco)
  * [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
  * Habilitar Code Coverage
    * [Preferences >> Build, Execution, Deployment >> Coverage]()
* **Exercícios**
  * **( 1 )** Criar um Fork do Projeto
  * **( 2 )** Corrigir Caso de Teste Falhando
  * **( 3 )** Verificar Cobertura (Run >> Run ... >> Code Coverage >> Tracing Mode)
  * **( 4 )** Implementar Caso de Teste Dinners 
  * **( 5 )** Branch Coverage - melhorar cobertura condicional - Mastercard
## Prática 3 – Selenium Webdriver
* **GitHub:** https://github.com/andvicente/SeleniumWebdriver-AulaUnivem 
* **Ferramenta(s):**
  * [Selenium Webdriver](https://www.seleniumhq.org/projects/webdriver)
  * [Chromedriver](http://chromedriver.chromium.org)
* **Exercícios**
  * **( 1 )** Busca Google (Exemplo)
  * **( 2 )** Câmbio de Moedas (UOL Economia)
    * Limite Cota Viagens Exterior
  * **( 3 )** Campeonato Brasileiro
    * Classificados Brasileiro e UEFA Champions League
## Prática 4 – Testes de API e BDD (Cadastro Estudantes)
* **GitHub:** https://github.com/andvicente/SpringBoot2_Rest_Tests 
* **Ferramenta(s) / Links:**
  * Spring Boot 2 (https://spring.io/projects/spring-boot)
  * Spring Data JPA - Banco H2 (In Memory)
  * Swagger - Rest API Documentation (https://swagger.io/tools/swagger-ui)
  * Cucumber-JVM - BDD Testing (https://cucumber.io)
  * Gherking (https://docs.cucumber.io/gherkin/reference)
  * Rest-Assured - API Testing (http://rest-assured.io)
* **Exercícios**
  * **Rest-Assured:**
  ```registerStudent( )e removeStudent( )```
  * **Cucumber:**
  ```Consultar Estudantes usando PassportID```
## Prática 5 – Testes de API (Rest-Assured)
* **GitHub:** https://github.com/andvicente/API-Testing_Rest-Assured 
* **Ferramenta(s) / Links:**
  * Spotify Developers (https://developer.spotify.com/web-api)  
  * PagSeguro Developers (https://dev.pagseguro.uol.com.br)
  * PagSeguro Sandbox (https://sandbox.pagseguro.uol.com.br)
  * Rest-Assured - API Testing (http://rest-assured.io)
* **Exercícios**
  * **Spotify API:** 
  ```playlistHasTracks( )```
  * **Sandbox PagSeguro:**
  ```Pagamento com Cartão de Crédito (Selenium)```
## Prática 6 – Continuous Integration
* JUnit+ JaCoCo + Slack integration
* Build Pipeline (Pipeline as Code)
* **GitHub:** https://github.com/andvicente/Cartoes-CodeCoverage 
* **Ferramenta(s) / Links:**
  * **Docker**
    * https://docs.docker.com/docker-for-windows
    * https://docs.docker.com/docker-for-mac
    * https://kitematic.com (GUI)
  * **Jenkins**
    1. Configurar senha inicial
      ```/var/jenkins_home/secrets/initialAdminPassword```
    2. Plugins e usuario admin
      * https://plugins.jenkins.io/slack
    3. Mapear Volume (persistir jobs, etc)
    4. Manual: https://dzone.com/articles/get-started-with-jenkins-20-with-docker 
  * **Slack:** https://testesw-univem.slack.com
