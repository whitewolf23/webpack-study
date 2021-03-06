# Webpack에 대해 알아보자

![webpack](https://i.imgur.com/Iyajj8b.png)
<center> Webpack 의 개념 </center>

webpack은 자바스크립트 모듈이며, 수 많은 javascript라이브러리들과 소스코드들을 번들링해주는 녀석입니다.
웹서비스를 하는데에 있어서 번들링의 의미는, 한번에 여러개의 파일을 클라이언트에서 로드를 하게 될 경우, 여러번의 요청을 통해서
자바스크립트 리소스를 이용하기 떄문에 네트워크 자원의 비용을 지불하게 됩니다.
또한, 각 파일은 서로의 스코프를 침범하지 않아야 하는데, 잘못 작성할 경우 충돌의 위험성도 있습니다.

이렇게 모듈을 최소한의 리소스로 번들링해서 클라이언트에게 제공하는것이 네트워크 비용을 최소화 할 수 있는 도구가 바로 webpack입니다.

webpack은 API(프로그래밍 라이브러리)그리고 CLI(커멘드 프로그램) 두 형태로 제공됩니다.
현재 웹펙은 4.10.2버전이 나왔으며 리엑트의 boilerplate 생성기인 `create-react-app` 은 webpack을 사용합니다.



## Webpack의 개념

![Webpack](https://i.imgur.com/7X5JxZl.png)
<center> Webpack에 대한 거시적 프로세싱 과정</center>


#### 엔트리

엔트리 포인트는, 웹팩 모듈이 번들링 할 수 있는 시작점을 의미한다. 처음에 로드한 자바스크립트 소스코드가, 

웹팩에서 모든 것은 모듈이다. 자바스크립트(JS), 스타일시트(CSS), 이미지(Image)이 모든것들을 자바스크립트의 모듈로써 로딩해서 사용한다.



# 참고

1. http://blog.jeonghwan.net/js/2017/05/15/webpack.html
2. https://imskojs.github.io/webpack-concept/