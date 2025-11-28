# 🎓 Gemini 교육용 프롬프트 생성 스킬

> **깊이 있는 수업과 평가를 위한 PARTS 프레임워크 기반 프롬프트 가이드**

교사, 학생, 교육 연구자를 위한 **107개 이상의 Gemini 프롬프트 템플릿**을 제공합니다.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📌 소개

이 스킬은 Google의 **PARTS 프레임워크**(Persona-Act-Recipient-Theme-Structure)를 기반으로 교육 현장에서 바로 사용할 수 있는 Gemini 프롬프트를 체계적으로 제공합니다.

### 주요 특징

- ✅ **2022 개정 교육과정** 및 한국 교육 맥락 반영
- ✅ **8가지 핵심 영역** 107개+ 프롬프트 템플릿
- ✅ **복사-붙여넣기** 즉시 사용 가능
- ✅ **Gemini 고급 기능** 연계 (Deep Research, Canvas, Gems, NotebookLM)
- ✅ 교사, 학생, 연구자 **모든 사용자 지원**

---

## 📂 파일 구조

```
gemini-education-prompts/
├── SKILL.md                 # 메인 스킬 파일 (전체 개요)
├── LICENSE                  # MIT 라이선스
├── README.md                # 이 파일
└── references/              # 영역별 상세 프롬프트
    ├── category1-planning.md                    # 수업 설계
    ├── category2-assessment.md                  # 평가 개발
    ├── category3-instructional-materials.md     # 수업 자료
    ├── category4-differentiation.md             # 개별화
    ├── category5-student-use.md                 # 학생 활용
    ├── category6-deep-research.md               # 심층 연구
    ├── category7-administrative-communication.md # 행정/소통
    ├── category8-gems-templates.md              # Gems 템플릿
    ├── parts-framework.md                       # PARTS 프레임워크 가이드
    ├── usage-guide.md                           # 활용 가이드
    ├── advanced-features.md                     # Gemini 고급 기능
    └── notebooklm-integration.md                # NotebookLM 연계
```

---

## 🎯 8가지 핵심 영역

| 영역 | 프롬프트 수 | 주요 내용 |
|------|-----------|----------|
| **1. 수업 설계** | 9개 | 수업 계획, 단원 설계, 교과 연계, 교사 연수 |
| **2. 평가 개발** | 10개 | 퀴즈, 수행과제, 루브릭, 데이터 분석 |
| **3. 수업 자료** | 10개 | 읽기 자료, 학습지, 실험 가이드, 토론 자료 |
| **4. 개별화** | 9개 | 맞춤 피드백, 수준별 활동, UDL, 다문화 지원 |
| **5. 학생 활용** | 12개 | 개념 이해, 시험 준비, 글쓰기, 코딩 학습 |
| **6. 심층 연구** | 6개 | 문헌 검토, 교수법 비교, 정책 분석 |
| **7. 행정/소통** | 17개 | 가정통신문, 공문, 추천서, 회의록, 뉴스레터 |
| **8. Gems 템플릿** | 15개 | 맞춤형 AI 어시스턴트 지시사항 |

---

## 🔧 PARTS 프레임워크

모든 프롬프트는 Google의 PARTS 프레임워크를 따릅니다:

| 요소 | 의미 | 예시 |
|------|------|------|
| **P**ersona | AI 역할 설정 | "당신은 중학교 과학 교육과정 설계 전문가입니다" |
| **A**ct | 수행할 과제 | "5E 모형으로 수업을 설계해주세요" |
| **R**ecipient | 대상 | "중학교 2학년 학생들을 위한" |
| **T**heme | 주제/개념 | "세포 분열과 유전" |
| **S**tructure | 출력 형식 | "표 형식으로, 차시별로 구분하여" |

### 프롬프트 예시

```
당신은 중학교 과학 교육과정 설계 전문가입니다. (Persona)
중학교 2학년 학생들을 위한 (Recipient)
'세포 분열과 유전' 단원의 (Theme)
2차시 수업을 5E 모형으로 설계해주세요. (Act)
각 단계별 활동과 시간 배분을 표로 정리해주세요. (Structure)
```

---

## 🚀 사용 방법

### 방법 1: 직접 복사-붙여넣기

1. 필요한 영역의 파일 열기 (예: `category1-planning.md`)
2. 원하는 프롬프트 템플릿 찾기
3. `[괄호]` 안의 내용을 본인 상황에 맞게 수정
4. Gemini에 붙여넣기

### 방법 2: Claude 스킬로 활용

Claude Desktop 또는 Claude.ai에서 스킬로 등록하여 사용:

1. `SKILL.md` 파일을 Claude 스킬 폴더에 복사
2. `references` 폴더도 함께 복사
3. Claude에게 "Gemini 프롬프트 만들어줘"라고 요청

---

## 🔗 관련 리소스

- [Google - 100+ ways to use Gemini in Education](https://edu.google.com/gemini/)
- [Gemini for Education 공식 문서](https://support.google.com/edu/gemini)
---

## 📜 라이선스

이 프로젝트는 [MIT 라이선스](LICENSE)를 따릅니다. 자유롭게 사용, 수정, 배포할 수 있습니다.

---

## 🤝 기여하기

프롬프트 개선, 새로운 영역 추가, 오류 수정 등 모든 기여를 환영합니다!

1. 이 저장소를 Fork
2. 새 브랜치 생성 (`git checkout -b feature/new-prompts`)
3. 변경사항 커밋 (`git commit -m 'Add new prompts'`)
4. 브랜치에 Push (`git push origin feature/new-prompts`)
5. Pull Request 생성


---

**⭐ 이 프로젝트가 도움이 되셨다면 Star를 눌러주세요!**
