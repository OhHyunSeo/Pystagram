<h1 align="center">📸 Pystagram</h1>
<p align="center">
    <b>Instagram 클론 프로젝트</b><br>
    Django를 활용한 미니 SNS - 사진 업로드, 좋아요, 팔로우까지 구현 완료!
</p>


---
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Django-4.x-success?logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/SQLite-DB-%2307405e?logo=sqlite&logoColor=white">
  <img src="https://img.shields.io/badge/HTML-5-orange?logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS-3-blue?logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=black">
</p>

## 🚀 소개

**Pystagram**은 Django 기반으로 구축된 미니 인스타그램 프로젝트입니다.  
이미지 게시물 업로드, 사용자 인증, 팔로우 시스템, 해시태그 검색 등 SNS의 핵심 기능을 담았습니다.  
UI는 기본 HTML/CSS와 Splide.js 슬라이더를 활용하여 심플하게 구현되었습니다.

---

## 🎯 핵심 기능

- 🖼️ 게시물 업로드, 수정, 삭제
- ❤️ 좋아요 & 해시태그 기능
- 👤 회원가입 / 로그인 / 프로필 수정
- 🔍 태그 기반 검색
- 🔄 팔로우 / 언팔로우

---

## 📁 디렉토리 구조

```
📁 Pystagram-master/
├── config/                # Django 설정
├── users/                 # 사용자 앱 (인증, 프로필, 팔로우 등)
├── posts/                 # 게시물 앱 (피드, 해시태그 등)
├── templates/             # HTML 템플릿들
├── static/                # CSS, JS
├── media/                 # 업로드된 이미지 저장소
├── db.sqlite3             # SQLite DB
└── manage.py
```

---

## 🧑‍💻 설치 및 실행

### 1. 프로젝트 클론 및 가상환경 생성

```bash
git clone https://github.com/yourusername/pystagram.git
cd pystagram
python -m venv venv
source venv/bin/activate
```

### 2. 패키지 설치 및 마이그레이션

```bash
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
```

### 3. 서버 실행

```bash
python manage.py runserver
```

접속 주소: [http://127.0.0.1:8000](http://127.0.0.1:8000)


---

## 🛠️ 기술 스택

- Python 3.11
- Django 4.x
- SQLite
- HTML / CSS / JavaScript
- Splide.js (슬라이드)

---



<p align="center">Made with ❤️ in Django</p>
