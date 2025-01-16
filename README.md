# RF - Requisitos Funcionais

[ ] - O usuário deve poder criar uma nova transação;
[ ] - O usuário deve poder obter um resumo da sua conta;
[ ] - O usuário deve poder listar todas as transações que já ocorreram;
[ ] - O usuário deve poder visualizar uma transação única;

# RN - Regra de Negócio

[ ] - A transação pode ser do tipo crédito que somará ao valor total, ou débito que vai subtrair;
[ ] - Deve ser possível identificarmos o usuário entre as requisições;
[ ] - O usuário só pode visualizar transações o qual ele criou;

# RFN - Requisitos não Funcionais


<!-- Comando para criar arquivo de migrations -->
-> npm run knex -- migrate:make nome-da-migration

<!-- Comando para criar migration no banco de dados -->
-> npm run knex -- migrate:latest

<!-- Comando para remover migration no banco de dados -->
-> npm run knex -- migrate:rollback