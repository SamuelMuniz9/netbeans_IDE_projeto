
# Sistema Web Java: Gestão e Persistência de Dados

Status: Concluído (Fase de análise de performance)

## Sobre o Projeto


Este projeto foi desenvolvido utilizando o ecossistema clássico do Java Web para aplicar conceitos de manipulação de dados em larga escala e integração com servidores de aplicação. O foco principal foi a construção de um sistema robusto capaz de realizar operações complexas de CRUD (Create, Read, Update, Delete) integradas a um banco de dados relacional.

A aplicação utiliza o Tomcat como servidor e o XAMPP para gestão do ambiente local, simulando um cenário real de desenvolvimento corporativo.
## Tecnologias e Ferramentas

 - Linguagem: Java

- Interface: HTML5, CSS3 e Bootstrap (Garantindo responsividade)

- Servidor de Aplicação: Apache Tomcat

- Banco de Dados: MySQL (via XAMPP)

- IDE: NetBeans Apache
## Funcionalidades Principais

- Gestão de Entidades: CRUDs completos para diferentes módulos do sistema.

- Persistência de Dados: Integração ativa com banco de dados para armazenamento seguro de informações.

- Interface Web Dinâmica: Páginas renderizadas no servidor com foco em usabilidade.
## Estudo de Caso: Performance e Aprendizados




Durante a fase de testes, adotei uma postura de Engenheiro de Software para analisar o comportamento da aplicação. Identifiquei pontos de latência na comunicação entre o servidor e o banco de dados, o que me proporcionou valiosos aprendizados em:

Otimização de Queries: Necessidade de índices e refinamento de comandos SQL.

Gestão de Recursos: A importância do Connection Pooling para evitar sobrecarga no Tomcat.

Arquitetura: Reflexões sobre refatoração para padrões como DAO (Data Access Object) para desacoplar a lógica.
## Instalação

Como rodar o projeto


```bash
Certifique-se de ter o JDK e o Apache Tomcat instalados.

Inicie o MySQL e o Apache através do painel do XAMPP.

Importe o banco de dados (arquivo .sql incluso no repositório).

Abra o projeto no NetBeans e execute o comando Clean and Build.

Inicie o servidor e acesse via localhost
```



   <img width="1400" height="819" alt="image" src="https://github.com/user-attachments/assets/341b6cbb-cb0f-4fb8-9d34-a44f9f629fe6" />

