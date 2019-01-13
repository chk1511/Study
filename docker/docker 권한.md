# Docker 권한

## Docker 실행 권한
- 도커의 명령은 항상 root 권한으로 실행해야 한다.
- 그러나 아래 명령어를 통해 sudo 를 사용하지 않고 docker 를 실행할 수 있게 된다.
> sudo usermod -aG docker $USER

## volume 폴더 소유권
- 기본적으로 root 로 생성됨