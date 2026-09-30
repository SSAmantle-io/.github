# 싸맨틀

> 단어의 뜻으로 정답에 다가가는 실시간 추측 게임.
> 같은 방 친구들과 누가 먼저 정답을 맞히는지 겨뤄요.

## 이렇게 놀아요
- 닉네임으로 입장해 방을 만들거나 들어가요
- 단어를 입력하면 정답과의 **유사도**와 **순위**를 알려 줘요
- 가까울수록 뜨거워지고, 가장 먼저 맞힌 사람이 1등이에요

## 저장소
| 저장소 | 설명 | 기술 |
| --- | --- | --- |
| [frontend](https://github.com/ssamantle-io/Frontend) | 게임 화면 | React, Vite |
| [backend](https://github.com/ssamantle-io/Backend) | 게임 API, 방 관리, 실시간 전송 | Spring Boot, MySQL, WebSocket(STOMP) |
| similarity | 단어 유사도 계산 | FastAPI, fastText |

## 팀
| 이름 | 역할 |
| --- | --- |
| 김현호 | 기획 · 디자인 · 프론트엔드 · 유사도 서버 |
| 이송제 | 백엔드 |
