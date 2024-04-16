# Projeto Pass-in

> Estudo de java no evento NLW Unite Rocketseat

### Tecnologias

> Java 17
> Spring Boot 3.2.4
> Maven

### Dependências
> JPA
> Lombok
> Flyway
> Spring WEB
> Dev Tools
> Banco de dados hsqldb (https://hsqldb.org/)

### Sobre o projeto

> Aplicação de gestão de participantes em eventos presenciais
> Parcipantes inscritos podem emitir uma credencial para check-in no dia do evento
> O sistema fará um scan da credencial do participante para permitir a entrada do evento.

### Requisitos Funcionais

- O organizador deve poder cadastrar um novo evento;
- O organizador deve poder visualizar dados de um evento;
- O organizador deve poder visualizar a lista de participantes;
- O participante deve poder se inscrever em um evento;
- O participante deve poder visualizar seu crachá de inscrição;
- O participante deve poder realizar check-in no evento;

### Regras de negócio

- O participante só pode se inscrever em um evento uma única vez;
- O participante só pode se inscrever em eventos com vagas disponíveis;
- O participante só pode realizar check-in em um evento uma única vez;

### Requisitos não-funcionais

- O check-in no evento será realizado através de um QRCode;

Estrutura do banco 
![image](https://github.com/thiagogimenes/pass-in/assets/59589489/417c9be5-990b-4ac9-a8ec-fcf9417b38af)
