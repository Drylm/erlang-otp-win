# erlang-otp-win

docker build -t gsx/otp:18.0 -f .\Dockerfile.18.0 .
docker build -t gsx/otp:20.3 -f .\Dockerfile.20.3 .

docker run --rm -ti gsx/otp:18.0 cmd
docker run --rm -ti gsx/otp:20.3 cmd

WindowsServerCore
---

  * Build
```shell
docker build --rm -t gsx/otp-servercore:18.0 -f .\nanoserver\Dockerfile.18.0 .\nanoserver\
docker build --rm -t gsx/otp-servercore:20.3 -f .\nanoserver\Dockerfile.20.3 .\nanoserver\
```

  * Run
```shell
docker run --rm -ti gsx/otp-nano:18.0 cmd
docker run --rm -ti gsx/otp-nano:20.3 cmd
```

Nanoserver
---

  * Build
```shell
docker build --rm -t gsx/otp-nano:18.0 -f .\nanoserver\Dockerfile.18.0 .\nanoserver\
docker build --rm -t gsx/otp-nano:20.3 -f .\nanoserver\Dockerfile.20.3 .\nanoserver\
```

  * Run
```shell
docker run --rm -ti gsx/otp-nano:18.0 cmd
docker run --rm -ti gsx/otp-nano:20.3 cmd
```