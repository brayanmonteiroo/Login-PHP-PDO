# Login-PHP-PDO
Sistemas de login feito com PHP, PDO,  Mysql e Bootstrap.
## Criação do Banco de dados e a tabela:
* 1º Para funcionar na sua máquina, seguindo o meu exemplo, crie uma base de dados no phpMyAdmin chamada 'sistema-de-login-bd'.
* 2º Crie a tabela com seguinte código:
```
CREATE TABLE users (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR(50) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    created_at DATETIME DEFAULT CURRENT_TIMESTAMP
);
```

