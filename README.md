# 📝 AI 할일 관리자

자연어로 할일을 추가할 수 있는 CLI 도구입니다.  
"내일 오후 3시에 팀 회의" 같이 입력하면 AI가 날짜와 시간을 자동으로 파싱해서 저장해줍니다.

## 사용 기술
- Python
- OpenAI API (gpt-4o-mini)

## 기능
- 자연어로 할일 추가
- 할일 목록 조회
- 할일 삭제

## 사용법
- add 내일 오후 3시에 팀 회의 		  # 할일 추가
- list                          # 목록 조회
- delete 1                      # 1번 삭제
- quit                          # 종료

## 실행 방법
1. OpenAI API 키 발급
2. Colab Secrets에 `Open_AI_Key` 로 저장
3. 노트북 실행
