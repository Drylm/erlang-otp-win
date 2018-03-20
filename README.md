# erlang-otp-win

docker build -t gsx/otp:18.0 -f .\Dockerfile.18.0 .
docker build -t gsx/otp:20.3 -f .\Dockerfile.20.3 .

docker run --rm -ti gsx/otp:18.0 cmd
docker run --rm -ti gsx/otp:20.3 cmd
