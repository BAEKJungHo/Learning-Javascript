# Learning-Javascript
Learning Javascript 책을 보면서 공부한 내용을 정리

## 주석 

  ```javascript
  console.log("echo") // 콘솔에 echo를 출력
  
  /*
  자바스크립트 주석
  자바의 주석과 동일
  */
  ```
 
## HTML에서 CSS와 JavaScript, JQuery 불러오는 방법 
 
  ```html 
<!doctype html>
<html>
    <head>
        <!-- CSS 파일을 문서로 불러오는 링크 -->
        <link rel="stylesheet" href="main.css">
    </head>
    <body>
        <!-- JQuery 파일을 문서로 불러오는 링크 -->
        <script src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
        <!-- JavaScript 파일을 문서로 불러오는 링크 -->
        <script src="main.js"></script>
    </body>
</html>
  ```
  
 ## console 
 
  cosole은 프로그램을 진단할 때 사용하는 텍스트 전용 도구입니다. console은 개발자 도구(F12)에 내용을 출력하고 싶을 경우 사용할 수 있습니다.
  console에 지정할 수 있는 속성이 여러가지 있는데 대표적으로 `log`와 `dir`가 있습니다.

  console을 사용하고나서 개발자 도구(F12)를 눌러서 console에 들어가면 console로 출력한 내용을 볼 수 있습니다.
  
  - console.log
  
   ```javascript
   console.log(document.querySelector('.inner'));
   ```
   
   - 개발자 화면에 출력되는 모양 
   
   ```html
  <table class="table">
      <thead>
            <tr>
                <th>수정 날짜</th>
                <th>복구</th>
            </tr>
        </thead>
  </table>
  ```
  
  - console.dir 
  
  ```javascript
  console.dir(document.querySelector('.inner'));
  ```
  
   - 개발자 화면에 출력되는 모양(객체형식)
   
   ```
  accessKey: ""
  align: ""
  assignedSlot: null
  attributeStyleMap: StylePropertyMap {size: 0}
  attributes: NamedNodeMap {0: class, class: class, length: 1}
  ```
