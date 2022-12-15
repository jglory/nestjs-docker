# Nginx Reverse Proxy for Docker

## 사용환경
- 맥 또는 윈도우 (리눅스 환경 불가)
- docker 18.03 이후 버전 (host.docker.internal 도메인 지원)

## 서비스
- 프론트 웹
- API

# vhost
```text
# front
127.0.0.1 local.nestjs.jglory.io

# api
127.0.0.1 local-api.nestjs.jglory.io
```