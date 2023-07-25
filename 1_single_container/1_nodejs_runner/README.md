# NodeJs 기반 Runner 기준 실행
컨테이너 빌드
``` bash
// $ docker build --tag <container-name>[:tag_version] [Dockerfile Path]
$ docker build --tag node-runer:latest .
```

컨테이너 실행
``` bash
// $ docker run --name <컨테이너 이름> -p <호스트포트>:<컨테이너포트> <실행할 이미지명>[:tag_version]
$ docker run --name node-runner \
-p 3001:3001 \
node-runner:latest
```
