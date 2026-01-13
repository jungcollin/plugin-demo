# Personal Restaurant

요리 시뮬레이션 플러그인. 서브에이전트와 스킬의 협업 패턴을 학습하는 예제입니다.

## 구조

```
personal-restaurant/
├── agents/                  # 전문 셰프 (서브에이전트)
│   ├── wok-chef.md         # 볶음요리사
│   ├── grill-chef.md       # 그릴요리사
│   └── pastry-chef.md      # 제과제빵사
└── skills/                  # 비법 노트 (스킬)
    ├── wok-cooking/        # 볶음 전문
    ├── grill-cooking/      # 구이 전문
    ├── pastry-baking/      # 베이킹 전문
    └── kitchen-common/     # 공통 규정
```

## 설치

### 마켓플레이스에서 설치

```
/plugin marketplace add jungcollin/plugin-restaurant-examples
/plugin install personal-restaurant@jungcollin
```

### 로컬 테스트

```bash
claude --plugin-dir ~/personal-restaurant
```

## 사용 예시

```
김치볶음밥 만들어줘
스테이크 미디엄으로 구워줘
초코칩쿠키 만들어줘
```

## 개념

| 구분 | 역할 | 비유 |
|------|------|------|
| 서브에이전트 | 요리 실행 | 전문 셰프 |
| 스킬 | 기술 지식 | 비법 노트 |

> 셰프가 바뀌더라도 비법 노트(스킬)만 있다면 품질 유지!

## 라이선스

MIT
