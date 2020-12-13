# 옷장 관리 프로그램
2020년 2학기 프로그래밍 및 실습 (가) 기말 프로젝트
20203078 이수현

## 실행 방법
git clone https://github.com/suh9023/c_project_20 

cd c_project_20

make

./main

## 기능 구현
1.옷 추가, 삭제
    - 옷의 이름, 색, 사이즈, type(shirts, pants, dress, outer, pajamas), 옷을 입을 계절을 입력
    
2. 옷 리스트 전체 출력
    
3. 계절 순서대로 옷 정렬
    - spring,summer,fall,winter 순으로 옷을 정렬
    - 새로 옷의 정보를 추가할 때에 맞는 위치를 찾아서 추가
    
4. 옷 검색 (검색어와 일치하는 정보를 가지는 옷 전체 출력)
    - 이름, 색, 사이즈 등에 상관없이 원하는 검색어 입력시 해당 검색어를 정보에 포함하는 모든 옷의 정보를 출력

5. 옷 정보 수정
    -저장된 옷 중 정보를 수정할 옷을 검색하고 수정 정보를 다시 입력
    
6. 현재 계절에 맞는 옷 추천
    - 현재 계절을 입력하고 계절에 맞는 복장을 추천 
    - 있는 경우에 한하여 랜덤한 shirts, pants, dress, outer를 출력
    
7. 저장된 텍스트 파일 읽어오기/ 저장하기
    - closet.txt 파일에 데이터를 저장하고 프로그램 실행 시 closet.txt 파일의 데이터를 읽어온다.
