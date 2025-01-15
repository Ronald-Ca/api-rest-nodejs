<!-- Comando para criar arquivo de migrations -->
-> npm run knex -- migrate:make nome-da-migration

<!-- Comando para criar migration no banco de dados -->
-> npm run knex -- migrate:latest

<!-- Comando para remover migration no banco de dados -->
-> npm run knex -- migrate:rollback