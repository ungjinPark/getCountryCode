# getCountryCode.js
어떤분을 위해 만든 허접한 라이브러리

## 주의

대충 국가코드 긁어다가 만든 것이기 때문에 유지보수 문제로 인한 국가 누락이 있을 수 있습니다.
뭐, 있을만한 국가는 다 있으니 쓰셔도 별 문제는 없지만요.

## 사용 방법

### 정해진 select 태그 안에 HTML option 태그 생성

```javascript
generateCountryOptionElement(selectElement,iso_string);
```

### 데이터 구조만 가져오기

```javascript
getCountryCode(iso_string);
```

### iso_string이 뭔데?

대충, kr, us, jp같은 국가 코드를 말함, 이정도는 구글링해서 찾아봐요.

### 왜 필요한데?

위에 데이터를 보면 전부 영어인걸 볼 수 있죠? 당신이 영어권 서비스를 지원할거라면 괜찮지만, 이 글을 보는 당신은 한국인일 거 뻔하니까, 번역을 위한 코드를 넣어준겁니다.
