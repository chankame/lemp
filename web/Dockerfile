FROM nginx:1.27

# 環境変数（TZ）を定義
ENV TZ=UTC

# nginx config file,  Nginxの設定ファイルをコンテナ内にコピーして対応づける
COPY ./web/*.conf /etc/nginx/conf.d/

WORKDIR /var/www/html
