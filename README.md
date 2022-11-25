Nome:
Gabriel Vinícius de Oliveira
Leonardo Grotto
Kauã Daneli

Exemplo de definição das configurações básicas do WordPress

Estrutura do projeto:

-compose.yaml
-README.md

1. Fazer o download dos arquivos, exemplo no ubuntu git clone https://github.com/gabriel-vinicius/wordpress-mysql.git

2. No diretório do  projeto escrever o comando:
    $ docker compose up -d
    
 Ele vai instalar os arquivos e requerimentos.
 
3. Resultados esperados:
4. $ docker ps
CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS              PORTS                 NAMES
5fbb4181a069        wordpress:latest    "docker-entrypoint.s…"   35 seconds ago      Up 34 seconds       0.0.0.0:80->80/tcp    wordpress-mysql_wordpress_1
e0884a8d444d        mysql:8.0.19        "docker-entrypoint.s…"   35 seconds ago      Up 34 seconds       3306/tcp, 33060/tcp 

5. Navegar para http://localhost:80 no seu web browser para acessar WordPress.

6. Para remover os containers 
    $ docker compose down
    
7. $ docker compose down -v
