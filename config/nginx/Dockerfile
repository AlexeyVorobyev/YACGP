FROM nginx:latest

COPY nginx.template.conf /nginx.template.conf

ENV EXAMPLE 10.6.0.3

CMD ["/bin/sh" , "-c" , "envsubst '${EXAMPLE}' < /nginx.template.conf > /etc/nginx/nginx.conf && exec nginx -g 'daemon off;'"]
