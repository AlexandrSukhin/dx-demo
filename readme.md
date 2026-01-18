docker run --name some-postgres5 -e POSTGRES_PASSWORD=mysecretpassword -d -v /home/vasa/data/:/data/pg postgres
ls /home/vasa/data/
docker run --name some-postgres5 -e POSTGRES_PASSWORD=mysecretpassword -d -v /home/vasa/data2/:/data/pg postgres
