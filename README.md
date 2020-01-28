# Imagine Beyond

### Camadas necessárias (backend)

  - WebApi      (Necessário implementar)
  - Application 
  - Domain      (Aplicar validação de e-mail)
  - Repository  (Necessário implementar)
  - Test        (Necessário Implementar)

### Regra de negócio

Será necessário criar uma API que permita realizar cadastro, edição, exclusão e visualização de um cliente, seguem abaixo os requisitos mínimos:

  - Campos mínimos:
    - Nome;
    - Sobrenome;
    - E-mail;
        -  Validar o e-mail
    - Data de nascimento;
    - Data de criação;
    - Data da última atualização;

### Requisitos necessários e comandos 

   - .NET Core 3.1 ou superior;

Abra o terminal de sua preferencia na pasta src:
    dotnet build - buildar o projeto
    dotnet run   - Iniciar o projeto na porta localhost://5001 (terminal dentro da pasta src/ImagineBeyond.UI.Web)
    dotnet test  - Roda seus teste (terminal dentro da pasta src/ImagineBeyond.Test)
    
Mais detalhe sobre, você encontra na documentação oficial da [Microsfot](https://docs.microsoft.com/pt-br/dotnet/core/tools/?tabs=netcore2x)
    
  
### Banco de dados (aceitos)

 - Banco de dados:
   - SQL Server;
   - Oracle;
   - MongoDB;

### Padrões desejavéis

 - Injeção de dependência (DI)
 - WebApi (Back-end)
 - Utilização de ValueObject

### Documentação

Será necessário criar markdown expicando como execultar o seu projeto em nossa máquina, como ser executado, porta que deve ser configurado e etc, seguiremos seu tutorial para rodar e testar sua aplicação. Inclua também nessa documentação bibliotecas utilizadas, versão dos framework utilizado e etc.

Para ajudar a criar um markdown recomendo ser utilizar [Dillinger](https://dillinger.io/)
