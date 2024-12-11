FROM nginx
RUN mkdir /se-konnect-portal
COPY /dist /se-konnect-portal
RUN chmod -R 755 /se-konnect-portal
COPY portal_nginx.conf /etc/nginx/nginx.conf