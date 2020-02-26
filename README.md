Docker-Compose.yml

Instalação Intersystems IRIS for UNIX (Ubuntu Server LTS for x86-64 Containers) 2019.4 (Build 383U) 

Executar no host:
        
        mkdir -p /opt/ISC/key
    
Fazer o scp do arquivo .key para o diretório /opt/ISC/key

     scp /Licences/iris.key user@ip_do_host:.
     docker-compose config
     docker-compose up
