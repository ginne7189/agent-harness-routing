# Routing Workflow

```text
고객 문의 → 문의 유형 분류
             ├─ billing
             ├─ technical
             ├─ account
             └─ general
```

Router는 답변을 모두 만들지 않습니다. 요청을 분류하고 선택된 담당 역할에 필요한 입력만 전달합니다.
