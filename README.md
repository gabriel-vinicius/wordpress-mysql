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
![image](https://user-images.githubusercontent.com/62100022/204059980-2d486fd2-5a0c-4f21-9a50-b3758b91e1bc.png)

5. Navegar para http://localhost:80 no seu web browser para acessar WordPress.

6. Para remover os containers 
    $ docker compose down
    
7. $ docker compose down -v

Link para explicações e passo a passo que foi criado para esse projeto: https://www.canva.com/design/DAFSzg0yMBI/VTwbeFDy2M9OGmTOli6frA/edit#1
