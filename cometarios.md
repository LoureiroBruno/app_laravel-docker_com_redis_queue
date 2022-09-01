1 baixado setup laravel
1 baixando imagem laravel 9
2 cp .env.example .env
3 definir nome aplicação - APP_NAME="exemplo"
e dedinir a senha do DB_PASSWORD=root
4 definir - APP_URL="http://localhost:porta definida docker compose yml"
5 subir os containers baseado no docker-compose e soltar o processo 
# docker-compose up -d
ou
# docker-compose build nome do container
# docker-compose up -d
6 docker ps (rodando containers)
7 acessar container da aplicação laravel - docker-compose exec nome_do_container bash
dentro do projeto - composer install
8 continuando dentro da aplicação, gerar a key - 
# php artisan key:generate
