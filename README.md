# geoservice


oc new-app postgresql-persistent -e POSTGRESQL_USER=user -e POSTGRESQL_PASSWORD=pass -e POSTGRESQL_DATABASE=cafe 

oc new-app postgresql-persistent -e DATABASE_SERVICE_NAME=postgresqlq -e POSTGRESQL_USER=user -e POSTGRESQL_PASSWORD=pass -e POSTGRESQL_DATABASE=cafereview

mvn spring-boot:run -DDB_HOST=postgresql-cafe.192.168.99.100.nip.io -DDB_PORT=5432 -DDB_SCHEMA=cafe -DDB_USER=user -DPASSWORD=pass

https://access.redhat.com/documentation/en-us/red_hat_fuse/7.0/html/fuse_on_openshift_guide/get-started-admin

