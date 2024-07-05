- To stop PostgreSQL `sudo systemctl stop postgresql`
- To start PostgreSQL `sudo start some-postgres`
- If there is no image `docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres`
- To run postures in terminal `docker exec -it my-postgres1 psql -U postgres -d postgres`