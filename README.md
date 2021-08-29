## Mongodb from docker. 
## Raspberry pi4 (Ubuntu server ARM64) only "Bionic" version supported

* [Mongo](https://hub.docker.com/_/mongo/)

## Start using it

1. Download it :

    ```sh
    $ git clone https://github.com/fraktalov/mongodb-docker.git
    ```

2. Run :

    ```sh
    $ docker-compose up -d
    ```

3. Open your favorite browser :

    * [http://localhost:27017](http://localhost:27017/)


## MongoDB compass connect

mongodb://mongodb0.example.com:27017


## Directory tree

```sh
mongodb-docker
├── README.md
├── data
│   └── db
├── docker-compose.yml
```
