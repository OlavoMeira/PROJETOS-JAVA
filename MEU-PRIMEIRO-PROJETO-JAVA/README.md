## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).






Olavo: Infraestrutura de Conexão e ConfiguraçãoOlavo ficará responsável por preparar o terreno para que o banco de dados funcione corretamente dentro do framework.Dependências: Configurar o arquivo de build com as novas dependências (dendeframework, MySQL Connector, HikariCP e Lombok).  Properties: Criar o arquivo application.properties com as configurações de conexão fornecidas.  Mapeamento e Pool: Implementar a classe ConfigProperties (usando @Value) e a classe ConnectionPool utilizando Hikari.  Apresentação: Iniciar a elaboração do "Modelo de Apresentação" que será entregue ao tutor. 

 2. Ian: Camada de Persistência (Repositórios)Ian focará na implementação lógica do acesso aos dados, garantindo que a aplicação salve e recupere informações.Repositórios JDBC: Desenvolver todos os repositórios utilizando apenas JDBC puro e as anotações do dendewebframework (proibido o uso de Hibernate/JPA).  Interfaces: Implementar a interface CrudRepository para cada tabela do sistema.  Mapeamento de Dados: Implementar a interface RowMapper para converter os resultados do banco (Select) em objetos Java.  Versionamento: Garantir que o código final esteja na branch main para avaliação. 
 
  3. Davi: Exceções e Modelagem de ProcessosDavi cuidará da robustez do sistema e da documentação técnica visual exigida.Tratamento de Erros: Criar as exceções personalizadas (UncheckedException herdando de RuntimeException) e garantir que todas as CheckedException sejam devidamente tratadas ou relançadas.  Diagrama de Sequência: Construir o diagrama de sequência para o endpoint específico da equipe (conforme a Tabela 1 ou 2) e exportar como PDF.  Submissão: Responsável por realizar o upload dos formulários de Diagrama e Apresentação no Blackboard.