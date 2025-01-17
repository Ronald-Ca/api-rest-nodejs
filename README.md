# RF - Requisitos Funcionais

[X] - O usuário deve poder criar uma nova transação;
[X] - O usuário deve poder obter um resumo da sua conta;
[X] - O usuário deve poder listar todas as transações que já ocorreram;
[X] - O usuário deve poder visualizar uma transação única;

# RN - Regra de Negócio

[X] - A transação pode ser do tipo crédito que somará ao valor total, ou débito que vai subtrair;
[X] - Deve ser possível identificarmos o usuário entre as requisições;
[X] - O usuário só pode visualizar transações o qual ele criou;

# RFN - Requisitos não Funcionais


<!-- Comando para criar arquivo de migrations -->
-> npm run knex -- migrate:make nome-da-migration

<!-- Comando para criar migration no banco de dados -->
-> npm run knex -- migrate:latest

<!-- Comando para remover migration no banco de dados -->
-> npm run knex -- migrate:rollback