# About this Repo

修改Dockerfile文件，将ENTRYPOINT ["/docker-entrypoint.sh"]改为ENTRYPOINT ["sh", "/docker-entrypoint.sh"]，此处不改的话镜像启动时会报错。
制作镜像，docker build -t nginx:1.23.1-0.2 -f Dockerfile .
