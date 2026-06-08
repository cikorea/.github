<!-- 이 파일은 cikorea/.github repo의 profile/README.md 경로에 두어야 org 프로필 상단에 표시됩니다. -->

<div align="center">

# CodeIgniter Korea

**CodeIgniter 4 한국 사용자 커뮤니티**

가볍고 빠른 PHP 프레임워크, CodeIgniter를 함께 배우고 나누는 공간입니다.

[![CodeIgniter](https://img.shields.io/badge/CodeIgniter-4-EF4223?logo=codeigniter&logoColor=white)](https://codeigniter.com)
[![PHP](https://img.shields.io/badge/PHP-8.1+-777BB4?logo=php&logoColor=white)](https://www.php.net)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

</div>

---

## 🧭 우리가 하는 일

- **CI4 한글 문서/가이드** 정리 및 공유
- 실무에서 검증된 **예제·보일러플레이트** 제공
- MSA·API 설계 등 **백엔드 아키텍처** 노하우 공유
- 입문자 질의응답과 코드 리뷰

## 📦 주요 저장소

### CI4 Board — CodeIgniter 4 기반 게시판 프로젝트

tab bbs (배강민, 전상민 제작) 의 DB 스키마를 기반으로 Claude Code를 이용해 CI4로 재작성한 게시판 시스템입니다.
API 서버, 사용자 프론트, 관리자 대시보드 총 3개의 저장소로 구성됩니다.

| 저장소 | 역할 | 기술 스택 | 포트 |
| --- | --- | --- | --- |
| [`ci4-board`](https://github.com/cikorea/ci4-board) | REST API 서버 | PHP · CodeIgniter 4 · Swagger | :8080 |
| [`ci4-board-web`](https://github.com/cikorea/ci4-board-web) | 사용자 프론트엔드 (SSR/ISR) | Next.js 16 · TypeScript · Tailwind CSS v4 | :3000 |
| [`ci4-board-admin`](https://github.com/cikorea/ci4-board-admin) | 관리자 대시보드 (SPA) | React 18 · Vite · Ant Design 5 · TypeScript | :5173 |

#### 개발 환경 빠른 시작

```bash
# 세 저장소를 나란히 클론 후 각각 실행
cd ci4-board       && php spark serve    # API 서버 (:8080)
cd ci4-board-admin && npm run dev        # 관리자 대시보드 (:5173)
cd ci4-board-web   && npm run dev        # 사용자 프론트 (:3000)
```

> API 문서: 서버 실행 후 `http://localhost:8080/swagger` 접속

## 🚀 시작하기

```bash
composer create-project codeigniter4/appstarter myproject
cd myproject
php spark serve
```

## 🤝 참여 방법

1. 관심 있는 저장소를 Fork
2. 브랜치 생성 후 작업 (`feat/your-feature`)
3. Pull Request 등록
4. 이슈·토론 참여도 언제나 환영합니다

## 🔗 링크

- 공식 사이트: https://codeigniter.com
- 공식 문서: https://codeigniter.com/user_guide/
- 커뮤니티 포럼: https://forum.codeigniter.com
- CI4 한글 가이드 (CodeIgniter 4): https://cikorea.net/docs/ci4-guide-ko/Codeigniter4/index.html
- CI4 한글 가이드 (CodeIgniter 3): https://cikorea.net/docs/ci4-guide-ko/Codeigniter3/index.html
- CI4 플레이그라운드: https://playground.cikorea.net/
- CodeIgniter 한국 사용자 포럼: https://cikorea.net/

---

<div align="center">
<sub>Made with ☕ by the CodeIgniter Korea community</sub>
</div>
