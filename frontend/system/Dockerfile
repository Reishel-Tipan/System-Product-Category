FROM nginx:alpine

COPY nginx.conf /etc/nginx/conf.d/default.conf

# Aquí copiarás la carpeta dist SYSTEM ya compilada localmente
COPY dist/system /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
