# grpc-pingpong

A simple grpc test experiment

## Local Setup
```bash
git clone https://github.com/kashvigarg/grpc-pingpong.git
$ virtualenv venv
$ source venv/Scripts/activate
$ pip install grpcio
$ pip install grpcio-tools
```

## Starting the Server
```bash
python server.py
```

## Starting the Client
```bash
python client.py
```

## Synopsis
The server receives a series of pings from the client, and logs the number of pings after recieving some set 'n' number of requests.
