# Dokcer
DockerFiles


#构建镜像


docker build -t shadowsocks:1.0 .

#shadowsocks

此目录为shadowsocks原始软件的镜像文件

#centos 7.6 防火墙设置

firewall-cmd --zone=public --add-port=1080/tcp --permanent

firewall-cmd --query-port=52580/tcp
