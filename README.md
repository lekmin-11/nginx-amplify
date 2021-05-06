# nginx-amplify
amplify digunakan untuk memonitoring nginx

1. referensi pada link berikut :https://github.com/nginxinc/docker-nginx-amplify#11-nginx-amplify-agent-inside-docker-container

2. masuk direktori : cd docker-nginx-amplify (kita bisa merubah image nginx pada file Dockerfile)
3. build image : sudo docker build -t nginxl-amp .
4. masuk direktori : 
5. sudo docker build -t lekmin/nginx-amplify:1.0 .
6. run image : sudo docker run -p 8082:80 --name nginx-monitor -e API_KEY=692556188791819184ff6cdfbb0b126d -e AMPLIFY_IMAGENAME=nginx-new -d lekmin/nginx-amplify:1.0  (untuk API_KEY lihat di akun Nginx Amplify kita)
