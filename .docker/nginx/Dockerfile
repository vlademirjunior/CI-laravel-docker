FROM nginx:1.15.0-alpine

RUN rm /etc/nginx/conf.d/default.conf
# Removo o arquivo de configuração padrão do nginx que ler aquele index.html padrão do nginx
# Preciso fazer isso para configurar o meu próprio, que vai rodar meu html/index.php do laravel

COPY ./nginx.conf /etc/nginx/conf.d
