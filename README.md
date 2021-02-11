## DevOps 1주차 과제 

[주제] GitHub 구성 flask-app Docker build

1) Python+Flask 혹은 리엑트 통해 간단한 웹어플리케이션을 작성
2) 웹어플리케이션을 Docker로 빌드 하여 DockerHub에 이미지 등록
3) 소스 코드를 GitHub에 등록
4) 깃 브랜치와 브랜치 관리 전략을 수립

## DevOps 2주차 과제 
[주제] 개발 빌드 환경 구성 및 Docker 빌드 자동화
CI 도구를 통해 소스 관리 하고 master로 Pull Request가 되면 어플리케이션을 도커로 빌드 자동화, 레지스트리에 등록

1) GitHub 레포지토리에 Continuous integration 연동
2) 소스코드가 변경이 되면 CI도구(AWS CodeBUild)가 자동으로 도커로 빌드
3) 빌드 된 도커 이미지를 자동으로 DockerHub레포지토리에 등록

과제: 기존에 작성한 코드, 다커를 AWS CodeBuild에 연동하여 Docker 빌드 및 DockerHub에 Image 업로드 자동화