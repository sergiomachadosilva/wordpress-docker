# Wordpress Dockerizado

Neste kit de ferramentas contém os seguinte pacotes:

Wordpress  | latest
------------- | -------------
mysql  | 5.7
phpmyadmin  | --- 

## Instalação

Para instalar o wordpress através do docker basta baixar o arquivo docker-compose.yml dentro de um diretório vazio em sua máquina, e rodar o comando abaixo: 

```shell
docker-compose up -d
```

## Uso

Depois que o container subir acesse o endereço [http://localhost](http://localhost) e conclua a instalação do wordpress.
Para acessar o banco de dados através do phpmyadmin, acesse o endereço [http://localhost:8080/](http://localhost:8080/).

Por por padrão o acesso ao banco de dados está configurado com as seguintes credenciais:

- **Host**: db
- **Usuário**: wordpress
- **Senha**: wordpress
- **Banco**: wordpress

Lembrando que todas as configurações podem ser alteradas no arquivo docker-compose.yml.