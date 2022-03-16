# Rest-Api-Documentation

## API Endpoints

- User data
  - `/users/<username>` - Retorna as infos do usuario
  - `/auth/<username>/?password=<password>` - consulta a senha do usuario (Isso e uma festa para scammers lol)

- Transactions
  - `/transactions` - retorna todas as transações.
  - `/transaction?username=<username>&password=<password>&recipient=<recipient>&amount=<amount>&memo=memo` - transfere os fundos para um usuario

- Miners
  - `/miners` - retorna todos os mineradores
  - `/miners/<username>` - retorna os mineradores de um usuario especifico

- Balances
  - `/balances` - retorna o saldo de todos os usuários
  - `/balances/<username>` - retorna um saldo de um usuário específico

- Other
  - `/statistics` - retorna as estatísticas do servidor
##
