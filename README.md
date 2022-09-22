# 42MARU_Kusitms_B
42MARU 기업프로젝트 개발과제_ B조 이정진, 박형준, 이아린, 정재희

## 목차
redis 어디에 썼는지 엔티티 분류
반환 방식 사용 목적 구분 (두개 있는거)
구조도
인풋 예시
아웃풋 예시

### 사용 방식
- Python, pytest
- 엔티티는 정규표현식을 이용해 구현
- 일부 엔티티는 Redis 사용

### Redis 사용 엔티티
- @sys.city '해외도시명'
- @sys.state '해외 주 단위'
- @sys.location '국내 지역'
- @sys.nation '국가명'
- @sys.currency.name '통화명'
- @sys.currency.code '통화 코드'
- @sys.unit.currency '통화'
Redis를 사용하면 방대한 양의 데이터를 효과적으로 가져올 수 있고 장애 상황 시 복구에 사용할 수 있기 때문에,
사전적으로 정리가 필요하고, 추가적으로 변경 가능성이 높은 엔티티 위주로 Redis를 사용


### 아웃풋 반환 형식
- pytest를 위한 각 항목별 output 반환
- 각 항목별 output을 하나의 리스트에 넣어 전체적으로 반환

### 구조도...
일단 패스...

### Input 예시
> ㅎㅎ

### Output 예시
|항목|반환 내용|
|:---:|:---:|
|*entity_name*|내용|
|value|내용|
|start_idx|내용|
|end_idx|내용|
|tagged_sentence|내용|


