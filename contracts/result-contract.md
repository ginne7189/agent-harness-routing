# 공통 Result Contract

각 단계 또는 역할은 다음 값을 같은 형식으로 반환합니다.

| 필드 | 의미 |
| --- | --- |
| `role` | 결과를 만든 단계 또는 역할 |
| `task` | 맡은 작업 |
| `status` | `completed`, `needs_input`, `blocked`, `human_review` |
| `result` | 확인하거나 작성한 결과 |
| `evidence` | 결과의 근거와 출처 |
| `next_action` | 다음 단계·재시도·중단·사람 확인 |

다음 단계는 앞 단계의 자연어 전체가 아니라 이 Contract의 값을 입력으로 받습니다.

