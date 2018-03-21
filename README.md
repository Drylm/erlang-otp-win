# erlang-otp-win

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

git filter-branch --commit-filter 'if [ "$GIT_AUTHOR_NAME" = "John" ];
  then export GIT_AUTHOR_NAME="Bhaal22"; export GIT_AUTHOR_EMAIL=muller.john@gmail.com;
  fi; git commit-tree "$@"'