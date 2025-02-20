# 논리 연산자 연습

```
#include <stdio.h> 

int main () {

    int A = 10;
    int B = 20;
    int x , y , z ;

    x = (A==10 && B==20);
    y = (A<20 || B>20);
    z = (!A);

    printf("x : %d\n" , x);
    printf("y : %d\n", y);
    printf("z : %d\n", z);
    return 0 ;

};
왼쪽 예제에서 A은 0이 아니므로 참과 거짓의 관계로
본다면 거짓에 해당한다. 따라서 ! 연산의 결과로 참을 의
미하는 1이 반환되는 것이다.
```

<figure><img src="../../../../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>
