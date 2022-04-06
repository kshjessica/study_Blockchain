# [졸업프로젝트 Research] Blockchain

👉 Original [Source Code](https://github.com/dvf/blockchain-book)
👉 Referenced [Article](https://medium.com/@vanflymen/learn-blockchains-by-building-one-117428612f46)
👉 Organizing [notes](https://www.notion.so/Blockchain-11ffb56bac994859a60f1afed442ed6c)

## To Do

### Installation - pip

1. Install [Python 3.6+](https://www.python.org/downloads/)
2. Install [pipenv](https://github.com/kennethreitz/pipenv)

```
$ pip install pipenv
```

3. Install requirements

```
$ pipenv install
```

4. Run the server:
   - `$ pipenv run python blockchain.py`
   - `$ pipenv run python blockchain.py -p 5001`
   - `$ pipenv run python blockchain.py --port 5002`

### Installation - Docker

Another option for running this blockchain program is to use Docker. Follow the instructions below to create a local Docker container:

1. Build the docker container

```
$ docker build -t blockchain .
```

2. Run the container

```
$ docker run --rm -p 80:5000 blockchain
```

3. To add more instances, vary the public port number before the colon:

```
$ docker run --rm -p 81:5000 blockchain
$ docker run --rm -p 82:5000 blockchain
$ docker run --rm -p 83:5000 blockchain
```
