# 🚀 본인이름의 기술 블로그 & 포트폴리오

파이썬 개발자 **본인이름**의 프로젝트와 학습 기록을 담은 블로그 저장소입니다.  
이 블로그는 [Hugo](https://gohugo.io/)와 [Hugo Blox Builder](https://hugoblox.com/) (구 Wowchemy)의 Academic 테마를 기반으로 제작되었습니다.

---

## 🌐 바로가기
- **블로그 주소:** [https://본인아이디.github.io](https://본인아이디.github.io)
- **주요 관심사:** Python, Automation, Data Analysis, Web Development

---

## 🛠 Tech Stack
- **Static Site Generator:** Hugo
- **Theme:** Academic (Hugo Blox)
- **Deployment:** GitHub Pages & GitHub Actions
- **Language:** Markdown, Python

---

## 📂 폴더 구조 및 관리
- `content/post/`: 기술 블로그 포스팅 관리
- `content/project/`: 진행한 프로젝트 포트폴리오 관리
- `content/authors/admin/_index.md`: 자기소개 및 프로필 수정
- `static/uploads/`: 이력서(PDF) 및 이미지 파일 관리

---

## 📝 블로그 업데이트 방법 (로컬)

수정 사항을 반영하려면 아래 명령어를 사용합니다:

```bash
# 새로운 포스트 생성
hugo new post/my-new-post.md

# 로컬에서 실시간 미리보기
hugo server

# 깃허브에 배포
git add .
git commit -m "Add new post: [제목]"
git push origin main
