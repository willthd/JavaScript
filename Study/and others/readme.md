## and others
---

> interpreter vs compiler
* interpreter
  code 한 줄 한 줄마다 바로 실행. 따라서 에러 나기 직전까지 실행한다

* compiler
  code 통째로 하나의 파일을 만들어 실행. 따라서 하나의 에러라도 있으면 실행되지 않는다



> 문자열 특징
* 문자열은 immutable !
  따라서 값 자체를 바꿀 수 없다

*일반 자료형*
b의 값이 3에서 5로 변경된다
```
var b = 3;
var b = 5;
```

*문자열*
값이 바뀌지 않는다. 첫 번째와 두 번째 값을 저장할 떄마다 메모리의 일정 영역을 따로 차지하며, 이후에 garbage collector에 의해 쓰지 않는 data를 정리한다
```
var a = "Will";
var a = "Honux";
```


> XOR, XNOR 진리표

![XOR](https://homepages.inf.ed.ac.uk/rbf/HIPR2/figs/ttabxor.gif)



> NaN
* not a number



> break;
* break문은 if문이 아니라 반복문을 빠져나오는 것



> %8.1f의 의미
* 소수점이상 최소 6자리, 소수점 이하 1자리. 출력될 자리수를 최소 8자리(소수점포함)를 확보. 빈자리는 공백으로 채움(오른쪽 정렬)

ex) var f = 1234.56789;
1234.6 출력