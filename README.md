# docker-Practice
# repository 내용물의 사용 방법
- 각각의 .yaml file은 개별적 docker container를 service하는 file이다.
1. docker와 docker-compose가 설치된 Linux 환경에 원하는 file을 옮긴다.
2. docker-compose_xxx.yaml file을 docker-compose.yaml로 rename한다.
3. rename한 docker-compose.yaml file이 있는 directory에서 docker-compose up 커맨드를 사용한다.
4. shutdown을 위해서는 docker-compose stop 커맨드를 사용한다.
