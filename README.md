# 📘 프로젝트명: Study With U

## 1. 🧩 주제 (Project Topic)
스터디 매칭 서비스를 제공하는 웹사이트

✅ 디렉터리 구조
아래와 같이 설정해 해주세요.
login_app/
│
├── app.py
├── templates-
│   ├── login.html
│   └── home.html

✅ 실행방법
python app.py
웹 브라우저에서 http://127.0.0.1:5000 접속

✅ 참고
보안 강화를 위해 비밀번호는 실제 배포 시 hashlib 또는 bcrypt 등으로 암호화 필요

CSRF 보호를 위해 Flask-WTF 도입 추천

DB는 SQLite → MySQL, PostgreSQL 등으로 확장 가능
