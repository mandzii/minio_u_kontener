# minio_u_kontener
Cist kratak kod 



 
 sudo docker run \
  -p 5555:9000 \
  -p 2222:9001 \
  -e "MINIO_ROOT_USER=marijan" \
  -e "MINIO_ROOT_PASSWORD=marijan8888" \
  minio/minio server /data --console-address ":9001"
  
  
  netstat -lnp  sve zauzeto (levo frontend desno moja)
 
