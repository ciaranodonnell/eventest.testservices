# About
Test application for handling events

# To build
```
docker build -t eventtest
```

# To run
```
docker run -it --rm -p 80:80 -p 443:443 --env REDIS_CONNECTION_STRING=$rs --env SERVICEBUS_CONNECTION_STRING=$sb
```
where `$rs` and `$sb` are connection string environment variables in the local system