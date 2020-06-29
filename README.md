# momentum-clone
Momentum Desktop Clone

### 모맨텀 데스크톱 클론
1. 위치 정보 가져오기
2. 날씨 API 사용 (Open Weather Map)
3. 랜덤 배경 이미지
4. Local storage (이름, 위치, todoList 저장)

##### 위치 정보 받아오기 
<img width="319" alt="스크린샷 2020-06-29 오후 5 16 00" src="https://user-images.githubusercontent.com/43735576/85993622-8d990100-ba31-11ea-872a-5660cd70da92.png">

##### User Name 입력
<img width="828" alt="스크린샷 2020-06-29 오후 5 18 03" src="https://user-images.githubusercontent.com/43735576/85994389-b077e500-ba32-11ea-8622-21cd92c5699f.png">

##### Todo List 
<img width="825" alt="스크린샷 2020-06-29 오후 5 17 44" src="https://user-images.githubusercontent.com/43735576/85994161-5ecf5a80-ba32-11ea-832f-f91eb2e73271.png">

<img width="835" alt="스크린샷 2020-06-29 오후 5 18 58" src="https://user-images.githubusercontent.com/43735576/85994544-e7e69180-ba32-11ea-9aa9-cababe6c7d16.png">

##### RANDOM Background Images

```
const body = document.querySelector("body");
const IMG_NUMBER = 3;

function paintImage(imgNumber) {
    const image = new Image();
    image.src = `images/${imgNumber + 1}.jpg`;
    image.classList.add("bgImage");
    body.appendChild(image);
}

function genRandom() {
    const number = Math.floor(Math.random() * IMG_NUMBER)
    return number;
}
```

<img width="496" alt="스크린샷 2020-06-29 오후 5 18 58" src="https://user-images.githubusercontent.com/43735576/85994544-e7e69180-ba32-11ea-9aa9-cababe6c7d16.png">
<img width="496" alt="스크린샷 2020-06-29 오후 5 26 04" src="https://user-images.githubusercontent.com/43735576/85994816-490e6500-ba33-11ea-800e-e39e2c8fde64.png">


##### Local storage (toDos, currentUser, coords)
<img width="1408" alt="스크린샷 2020-06-29 오후 5 19 38" src="https://user-images.githubusercontent.com/43735576/85994763-385def00-ba33-11ea-9c64-ab5b237ecea6.png">



