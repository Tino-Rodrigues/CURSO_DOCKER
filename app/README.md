Dockerfile

Comandos

docker build -t Tino/nginx:v20

docker run -d -p 8080:80 Tino/nginx:v21

docker push Tino/nginx:v22

FROM nginx:latest

EXPOSE 80

CMD ["nginx","-g", "daemon off";]