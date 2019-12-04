# Math

## 고정 소수점(toFixed)

```javascript
const x = 19.51;
x.toFixed(3); // "19.510"
x.toFixed(2); // "19.51"
x.toFixed(0); // "20", 올림이 아니라 반올림
```

## 지수 표기법(toExponential())

```javascript
const x = 3800.5;
x.toExponential(4); // "3.8005e+3"
x.toExponential(3); // "3.801e+3"
x.toExponential(0); // "4e+3" 반올림
```

## 고정 전체 자리수(toPrecision)

소수점이 어디 나타나든 관계없이 숫자 몇개로 표현하느냐가 중요하다면 toPrecision()을 사용합니다.

```javascript
let x = 1000;
x.toPrecision(5); // "1000.0"
x.toPrecision(3); // "1.00e+3"
```
