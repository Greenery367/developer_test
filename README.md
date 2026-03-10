# developer_test
<img width="900" height="1291" alt="image" src="https://github.com/user-attachments/assets/e6f6619e-f9be-405a-acb9-58fe505a2e0f" />
<img width="895" height="1497" alt="image" src="https://github.com/user-attachments/assets/580f60b7-3ef5-4c6a-9b9d-5210c9b4c13f" />




# 🚀 개발자 상태창: 각성 (Developer Status Window)

> **"당신은 어떤 클래스로 각성하시겠습니까?"** > 8개의 질문을 통해 숨겨진 나의 개발자 직군과 능력치를 확인하는 웹 테스트 서비스입니다.

---

## ✨ 주요 기능 (Key Features)

* **상태창 알고리즘**: 8개의 문항을 통해 `BE`, `FE`, `DevOps`, `AI`, `DBA`, `Design`, `Biz` 중 가장 적합한 클래스 산출
* **커스텀 결과 카드**: 사용자의 닉네임과 각성 등급(RANK S)이 반영된 결과 페이지 제공
* **이미지 저장 기능**: `html2canvas`를 활용하여 결과 카드를 이미지 파일로 즉시 다운로드 가능
* **데이터 분석**: Google Tag Manager(GTM) 및 GA4를 연동하여 시작수, 완독률, 인기 결과 등 추적

---

## 🛠 기술 스택 (Tech Stack)

| 구분 | 기술 |
| --- | --- |
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla JS) |
| **Library** | [html2canvas](https://html2canvas.hertzen.com/) (결과 카드 캡처) |
| **Analytics** | Google Tag Manager, Google Analytics 4 |
| **Deployment** | Netlify |

---

## 📸 스크린샷 (Screenshots)

> (여기에 실제 서비스 화면 캡처 이미지를 넣으면 더욱 좋습니다!)

1. **메인 화면**: 닉네임 입력 및 테스트 시작
2. **질문 페이지**: 진행률 바(Progress Bar)와 페이드 인 효과
3. **결과 페이지**: 캐릭터 클래스, 능력치 그래프, 칭호 확인

---

## 📈 분석 포인트 (Analytics)

현재 GTM을 통해 다음 이벤트를 추적하여 사용자 경험을 개선하고 있습니다:

* `test_start`: 테스트 시작 빈도 측정
* `question_view`: 질문별 도달률 및 이탈 구간 파악
* `test_complete`: 최종 완료 및 캐릭터 분포 확인
* `result_save`: 어떤 클래스가 가장 많이 공유/저장되는지 분석

---

## 🔗 링크 (Link)

**[지금 바로 각성하러 가기](https://www.google.com/search?q=https://developer-char-test.netlify.app)**

---


## 🤝 기여 (Contributing)

이 프로젝트는 개인 포트폴리오 및 학습용으로 제작되었습니다. 새로운 질문 아이디어나 캐릭터 제안은 언제나 환영합니다!

* Issue를 남기거나 Pull Request를 보내주세요.
