
# 도커 설치
https://goddaehee.tistory.com/251
# 도커 이미지 & 컨테이너 설치
 ```    
     $ docker-compose up -d --build
```

# 실행
contianer를 실행
 ```    
     $ docker-compose up -d
```

container 실행
 ```    
     $ docker exec -i -t ubuntu-dev /bin/bash
```

p.s apt update, apt upgrade 해주세요ㄴ
우분투 종료

 ```    
     $ exit
```

container 종료


 ```    
     $ docker-compose stop
```

p.s docker (compose) 파일 내용 수정하면 우분투 환경 리셋됩니다.

## 주피터 
 ```    
     $ jupyter notebook --ip='0.0.0.0' --port=8080 --allow-root
```

