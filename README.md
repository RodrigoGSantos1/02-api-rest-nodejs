# 02-api-rest-nodejs

# Run project: npm run dev

# Run tests: npm test

# MIGRATIONS

# Run migrations end upate dataBase: npm run knex migrate:latest 
# To rollback the last batch of migrations: npm run knex migrate:rollback
# To rollback all the completed migrations: npm run knex migrate:rollback


# RF

- [X] O usuário deve poder criar uma nova transação;
- [ ] O usuário deve poder obter um resumo da sua conta;
- [X] O usuário deve poder listar todas atransações quer já ocorreram;
- [X] O usuário deve poder visualizar uma transação única;

# RN

- [X] A transação pode ser do tipo crédito que somará ao valor total, ou débito subtrairá;
- [ ] Deve ser possível identificarmos o usuário entre as requisições;
- [ ] Ousuário só pode visualizar transações a qual ele criou;

# RNF