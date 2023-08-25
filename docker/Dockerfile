FROM nginx:1.24.0-alpine

COPY . .
RUN ls -lha

COPY codebase/rdicidr-0.1.0/build/ /usr/share/nginx/html
COPY docker/default.conf /etc/nginx/conf.d/default.conf
