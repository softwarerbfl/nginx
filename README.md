# 리드미

## MYSITE

---

- 클라이언트에게 전송해줄 정적 웹 콘텐츠를 담고 있는 프로젝트 폴더
- 프로젝트 실행 시에 `C:/TAcademy/nginx/MYSITE` 해당 위치에 존재

## nginx-1.24.0

---

- NGINX에 대한 설정 파일, 실행 파일 등을 담고 있는 폴더
- Docker로 4개의 포트를 열고 Round robin알고리즘을 적용하여 클라이언트의 요청을 분산시켜준다.
- `nginx-1.24.0/nginx-1.24.0/conf/nginx.conf` 이 주요 설정 파일 ⭐
    - upstream
    - proxy_pass
    - rewrite
    - location
    - root
    - alias
    - try_files
- `nginx-1.24.0/nginx-1.24.0/nginx.exe` 이 nginx를 실행하는 실행 파일 ⭐