# MaSiSong

## Project Information
- MaSiSong은 음악 관련 정보를 제공하는 서비스입니다.

## Project Architecture
- 프로젝트는 Frontend와 Backend Mono Repository로 구성되어 있습니다.

## Project Tech Stack & Version & Tool
- Java 17
- Spring Boot 3.3.1

## Git Commit Message Template 설정하기
- Git Commit Message Template을 설정하여, Commit Message Convention을 준수하도록 합니다.
- 현재 Project에서는 Udacity Git Commit Message Style을 사용하고 있습니다.
- Git 설정에 `.githooks/.gitmessage` 파일을 커밋 메시지 템플릿으로 사용하도록 지정합니다. 이를 위해 터미널에서 다음 명령어를 실행합니다:

```bash
git config --local commit.template .githooks/.gitmessage