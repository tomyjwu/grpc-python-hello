
# grpc-python-hello
python helloworld to grpc asyncio based on gRPC github repo
https://github.com/grpc/grpc

"hello, world" Python example:
```grpc/examples/python/helloworld```

[This code's documentation lives on the grpc.io site.](https://grpc.io/docs/languages/python/quickstart)

# installation
## Windows 10
```
python -m pip install grpcio
python -m pip install grpcio-tools
```

## linux/macos/wsl
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# run client/server
```
python async_greeter_server.py
python async_greeter_client.py
```
