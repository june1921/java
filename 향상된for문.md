장점
1. 가독성이 향상된다.
2. 배열인덱스 오류를 피할수 있음.

단점
1. int i=0 같이 인덱스 활용 안됨. 그러나 대체할 방법이 없는건 아님
2. 배열이나 ArrayList값을 활용할 수 있지만 절대 수정 할 수 없다.

```
for(자료형 변수명 : 배열명) {
  statement
}

//ex
int[] arr = {1,2,3,4};
int sum = 0;
for (int i:arr) {
  System.out.println("i = " + i);
  sum = sum + i;
}
System.out.println("sum = " + sum);
```
