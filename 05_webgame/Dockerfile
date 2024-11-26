# Python 3.9 슬림 이미지 사용
FROM python:3.9-slim

# 웹 애플리케이션 파일을 /app 디렉토리로 복사
COPY . /app

# 작업 디렉토리 설정
WORKDIR /app

# 필요한 포트 8080을 노출
EXPOSE 8080

# Python HTTP 서버 실행
CMD ["python3", "-m", "http.server", "8080"]

