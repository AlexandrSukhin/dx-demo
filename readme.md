docker run --name some-postgres5 -e POSTGRES_PASSWORD=mysecretpassword -d -v /home/vasa/data/:/data/pg postgres
ls /home/vasa/data/
docker rm -f some-postgres5
cp /home/vasa/data/ /home/vasa/data10/
docker run --name some-postgres5 -e POSTGRES_PASSWORD=mysecretpassword -d -v /home/vasa/data10/:/data/pg postgres
