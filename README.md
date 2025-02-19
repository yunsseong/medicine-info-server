# 서비스 개요
병용금기약물을 조회할 수 있는 서비스 입니다.

# 주요 기능
## 병용금기약물
### 조회
1. 사용자가 약물의 제품명 또는 성분명을 입력한다.
2. 사용자 입력을 바탕으로 약물을 찾아 목록으로 보여준다.
3. 목록에서 조회를 원하는 약물을 선택한다.
4. 조회를 원하는 약물이 더 있을 경우 1번으로 돌아가 반복한다.
5. 사용자가 검색 버튼을 누른다.
6. 병용 금지 약물을 보여준다.

### 저장
1. 공공데이터포털에서 병용금기약물 액셀 데이터를 다운로드한다.
2. 필요한 정보를 읽어서 저장한다.

## 추가 사항
- 차기 등록 예정일 기준 데이터 자동 최신화 기능
- 딥러닝을 통한 알약 이미지 인식 기능
- 약물 이미지 표시
- 금기, 주의 약물 정보 추가
    - [연령금기](https://www.data.go.kr/data/15089531/fileData.do)
    - [노인주의약물](https://www.data.go.kr/data/15089521/fileData.do)
    - [효능군중복주의약물](https://www.data.go.kr/data/15089542/fileData.do)
    - [임부금기약물](https://www.data.go.kr/data/15089735/fileData.do)
    - [투여기간주의약물](https://www.data.go.kr/data/15089541/fileData.do)
    - [용량주의약물](https://www.data.go.kr/data/15089533/fileData.do)
    - [마약류 약물 및 오남용 정보](https://www.data.go.kr/data/15058963/openapi.do)
    - [의약품 성분별 1일 최대투여량 정보](https://www.data.go.kr/data/15098095/openapi.do)