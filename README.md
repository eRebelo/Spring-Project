# Java Spring - Maven Project
  Aplicação Java que demonstra o uso do framework Spring MVC utlizando Hibernate + JPA para persistência de dados.
  - Baixar o arquivo README.pdf para mais instruções.

## JBoss Forge
  Framework para criação da estrutura de um projeto Maven Java EE.
  - Baixar o [JBoss Forge][1] para sistema operacional de preferência
  - Descompactá-lo no workspace
  - Navegar pelo terminal até a pasta /bin
  - Inicializar o terminal JBoss Forge executando o bat forge
    ```bash
    forge
    ```
  - Criar um projeto
     ```bash
     project-new --named casadocodigo
     ```    

## Projetos
- Tomcat-Project: dependências do projeto configuradas para executar no servidor Tomcat.
- WildFly-Project: dependências do projeto configuradas para executar no servidor WildFly (configurações do datasource incluídas no arquivo standalone-full.xml).

[1]: https://forge.jboss.org/download
