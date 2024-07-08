# Algorithm 정리 (개인)

<br>

## 제출 형식
1. 풀이 코드 커밋
2. 경로 및 파일명: `/src/week**/B_{문제 번호}.java`(예시: `/src/week01/B_1000`)
3. 커밋 메시지: `solve: week**-B*`(예시: `solve: week01-B1`)

## 코드 작성 가이드

풀이 코드와 함께 아래의 내용을 주석으로 작성.

- 코드 앞 부분에 문제 링크 / 메모리 / 시간 / 시간복잡도 / 공간복잡도 작성
- 주요 알고리즘과 문제에서 중요한 부분 설명
- 필요한 경우 코드 내에 주석 추가

```java
/**
 * 문제 링크: https://www.acmicpc.net/problem/1000
 * 메모리: 14448 KB
 * 시간: 132 ms
 * 시간 복잡도: O(1)
 * 공간 복잡도: O(1)
 */

/*
1. 두 정수 A와 B를 입력받은 후
2. A+B 계산
3. 결과 출력
 */

import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;

public class Main {

    public static void main(String[] args) throws IOException {
        BufferedReader bufferedReader = new BufferedReader(new InputStreamReader(System.in));

        // 입력을 받아 공백으로 분리
        String[] input = bufferedReader.readLine().split(" ");

        // 분리 된 문자열을 정수로 변환
        int a = Integer.parseInt(input[0]);
        int b = Integer.parseInt(input[1]);

        System.out.println(a + b);
    }
}
```


readme 참고: https://github.com/Ogu-Family/algorithm
