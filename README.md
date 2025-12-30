# movement_service_tunnel
for moving service in a tunnel to new tunnel

--------------------------------------------------------------------------------
in source(origin) server :

```rsync -avz /etc/systemd/system/udp*.service root@DEST_IP:/tmp/udp_import/```

all service move to destination server in folder /tmp/udp_import
-------------------------------------------------------------------------------
in destination server :

1. nano /usr/local/bin/udp-import.sh
2. paste script or use below command for it 
3. chmod +x /usr/local/bin/udp-import.sh
4. udp-import.sh
