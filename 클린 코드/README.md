# Clean Code - 로버트C. 마틴

## 2장 의미 있는 이름
- 의도가 드러나는 이름 e.g. daysSinceCreation, daysSinceModification, elapsedTimeInDays (o)
- 그릇된 정보를 피하라
- 의미 있게 구분하라 e.g. Prodcut/ProductInfo/ProductData (x)
- 의미 있는 맥락을 추가하라  e.g. addr 접두어

## 3장 함수
- 함수는 작고 한 가지 일만 하도록
- 위에서 아래로 코드 읽기: 내려가기 규칙
- 함수 인수는 적어야 함
- 부수 효과를 피하라 e.g. 이름으로 드러나지 않은 부수효과, session initialize
- 명령과 조회를 분리하라: 뭔가를 수행하거나 반환하거나 둘 중 하나만
- try catch 블록 별도 함수로 (logError도 따로)
- Error code 대신 Exception으로
- 중복 제거

## 4장 주석
- 주석으로 코드 처리하지 말아라
- 
