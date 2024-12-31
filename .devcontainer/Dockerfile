# Node.js 기반 Dev Container 이미지 사용
 FROM node:20-alpine



# 추가 도구 설치 (필요에 따라 수정 가능)
RUN apt-get update && apt-get install -y git curl bash

# 작업 디렉터리 설정
WORKDIR /workspace

COPY package.json ./
RUN npm install
