FROM nginx
LABEL "PROJECT"="Webapp"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx_app.conf /etc/nginx/conf.d/vproapp.conf
