FROM nginx
RUN apt update
RUN echo Y | apt upgrade
COPY index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]

