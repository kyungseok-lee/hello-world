# AI Codegen Examples

AI 코드 생성 예제

## Supported Languages

이 문서는 다양한 언어에 대한 개발 환경 설정 예시를 제공합니다.  
(추후 필요에 따라 TypeScript, Kotlin, Java 등의 설정 예시도 추가할 예정입니다.)

### Python

#### Virtual Environment Setup

아래 명령어들을 사용하여 Python 가상 환경을 설정하고, 필요한 패키지를 설치할 수 있습니다.

```bash
# 가상 환경 생성
python -m venv .venv

# pip 업그레이드
pip install --upgrade pip    # 또는: python -m pip install --upgrade pip

# 필요한 패키지 설치 (예: pygame)
pip install pygame           # 또는: python -m pip install pygame

# 실행
python main.py
```

### Golang

#### Environment Setup

```bash
go mod init spinning-hexagon-go

# module 설치
go mod tidy

# 개별 module 설치 시
go get github.com/hajimehoshi/ebiten/v2

# 바로 실행
go run main.go

# build 후 실행
go build -o spinning-hexagon-go
./spinning-hexagon-go
```

### TypeScript

#### Environment Setup

현재 준비 중입니다.  
곧 TypeScript 개발 환경 설정 예시를 추가할 예정입니다.

### Kotlin

#### Environment Setup

현재 준비 중입니다.  
곧 Kotlin 개발 환경 설정 예시를 추가할 예정입니다.

### Java

#### Environment Setup

현재 준비 중입니다.  
곧 Java 개발 환경 설정 예시를 추가할 예정입니다.
