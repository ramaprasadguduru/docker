FROM        ubuntu
RUN         apt update -y
RUN         apt install nginx -y
CMD         ["nginx", "-g", "daemon off;"]
LABEL       Owner="ZelarSoft" \
            Maintainer="DevOps Team"\
            ProjectName="styra"
EXPOSE      80

### we are adding port numbers here