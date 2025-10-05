FROM nginx:alpine
LABEL org.opencontainers.image.source c-cd-trp
COPY dist /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
