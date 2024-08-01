# use an official nginx image as a base
FROM nginx:alpine

# copy the static content file to nginx HTML dir
COPY public /usr/share/nginx/html

# expose port 80
EXPOSE 80

# start nginx
CMD ["nginx", "-g", "daemon off;"]
