# bingo
# 1차원 빙고만들기 
# 실행화면
![실행화면](https://user-images.githubusercontent.com/104752580/183351263-78181d4e-f8de-4d9c-858d-4c238d840b7e.PNG)

입력한 숫자가 0으로 바뀌면서 좌우상하 대각선으로 3개가 동시에 나열되면 빙고가 나오게 됩니다.
# 빙고 코드
![배열](https://user-images.githubusercontent.com/104752580/183351613-fd8517e2-9973-46dd-9991-91246e7cee02.PNG)
### 메인 클래스 밖에 map3라는 빙고판 배열과 map4라는 6개에 숫자를 입력받는 배열을 만듭니다.
![메인 1](https://user-images.githubusercontent.com/104752580/183352289-bdc5f1c0-d250-4004-bf45-4dff12e0a13a.PNG)
![메인2](https://user-images.githubusercontent.com/104752580/183352296-49f194a4-4b1e-4843-b6c1-1434daefedd7.PNG)
### 메인 클래스 안에는 값을 랜덤으로 꽂게 해주는 랜덤함수를 사용하여 map3 배열에 값을 랜덤으로 출력하는 반복문을 만들고 중복값을 받지않게 이중 for으로 감싸줍니다.
### 그리고 숫자를 map4 배열만큼 입력하는 출력문을 사용하고 map4에서 입력받은 값이 map3에 있는 동일한 값을 0으로 출력받는 반복문을 사용합니다.
### 마지막으로 빙고라는 변수와 cnt라는 변수를 만들고 map3에 있는 0이 0번째부터 3번째까지 나열되어 있으면 빙고를 할 수 있게 해주는 반복문을 만듭니다.
### 이 반복문을 좌우상하 대각선까지 조금씩 숫자를 바꾸며 만듭니다.
# 출력문
![출력문](https://user-images.githubusercontent.com/104752580/183354015-8256f2ad-2e4c-4d7b-8e5f-eedaaeca8576.PNG)
### 숫자를 입력받고 출력하는 출력문은 1차원 배열이기 때문에 if를 사용하여 map3만큼에서 3씩 나눠 2번씩 끊어서 출력할 수 있게 하는 반복문을 만듭니다.
