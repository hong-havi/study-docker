# NodeJs 기반 Runner 기준 실행
Swarm 빌드
``` bash
// $ docker-compose -f [yml 파일 경로] build
$ docker-compose -f docker-compose.yml --verbose build
```

Swarm Stack 배포
``` bash
// $ docker stack deploy --compose-file [ yml path ] [ Stack name ] 
$ docker stack deploy --compose-file docker-compose.yml nodeService
```
