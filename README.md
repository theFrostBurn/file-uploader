# File Uploader

파일 업로드를 쉽게 할 수 있는 웹 애플리케이션입니다.

## 주요 기능

- 드래그 앤 드롭으로 파일 업로드
- 다중 파일 업로드 지원
- 업로드 진행률 표시
- 허용된 파일 형식 표시
- 업로드된 파일 목록 관리
- 파일 삭제 기능

## 지원하는 파일 형식

- 문서: txt, pdf, doc, docx, xls, xlsx
- 이미지: png, jpg, jpeg, gif
- 코드: json, js, py, html, css, md
- 설정: xml, yaml, yml, ini, conf
- 압축: zip, rar, 7z, tar, gz

## 설치 방법

1. Python 가상환경 생성 및 활성화:
   ```bash
   python -m venv file-uploader
   cd file-uploader
   Scripts\activate
   ```

2. 필요한 패키지 설치:
   ```bash
   pip install flask werkzeug
   ```

3. 프로젝트 실행:
   ```bash
   python app.py
   ```

## 프로젝트 구조

file-uploader/
├── app.py              # Flask 애플리케이션 메인 파일
├── templates/          # HTML 템플릿
│   └── index.html     # 메인 페이지
└── static/            # 정적 파일
    └── uploads/       # 업로드된 파일 저장 폴더

## 사용 방법

1. 웹 브라우저에서 `http://localhost:5000` 접속
2. 파일을 드래그 앤 드롭하거나 클릭하여 선택
3. 업로드 진행률 확인
4. 업로드된 파일 목록에서 파일 관리

## 기술 스택

- Backend: Flask (Python)
- Frontend: HTML, CSS, JavaScript
- 파일 업로드: XMLHttpRequest
- 스타일링: 순수 CSS

## 라이선스

이 프로젝트는 MIT 라이선스 하에 있습니다. 