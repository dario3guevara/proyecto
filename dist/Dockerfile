FROM nginx:alpine
 # use a volume is mor efficient and speed that filesystem
VOLUME /tmp
RUN rm -rf /usr/share/nginx/html/*
COPY nginx.conf /etc/nginx/nginx.conf
COPY app /usr/share/nginx/html/app
#COPY ecuador /usr/share/nginx/html/ecuador
#expose app and 80 for nginx app
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
