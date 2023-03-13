# 두개의 배열이 같은지 확인하기

equals() 메서드는 주소 값이 아닌 배열의 요소를 비교합니다. 
두 배열이 동일한 타입, 동일한 수의 요소 
그리고 정렬 순서가 동일한 경우 true를 반환하고 그렇지 않으면 false를 반환합니다.<br>
메인 메소드에 반환된 값을 가져와서 참과 거짓을 구별합니다
```java
 static boolean equals(int[] a, int[] b){
            if (a.length != b.length)
                return false;
            for (int i = 0; i < a.length; i++)
                if(a[i] != b[i])
                    return false;

        return true;
        }
}
```
