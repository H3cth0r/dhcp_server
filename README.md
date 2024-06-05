# dhcp_server
user: redes

sudo docker run -it --rm  --init --net=host  -v "$(pwd)/data":/data networkboot/dhcpd 
