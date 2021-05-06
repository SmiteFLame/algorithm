# BOJ 18222번 투에-모스 문자열

## 🌈 풀이 후기
분할 정복 문제여서 가지고 왔는데<br>
비트마스크를 활용하여 꿀빨았습니다 ╰(*°▽°*)╯<br>


## 👩‍🏫 문제 풀이
<br>

### 변수
- N(long): 입력받은 문자
- cnt(cnt): 1의 개수
- flag(long): 비트마스크를 통해서 하나씩 증가되는 수


### 원리
1. 1부터 10의 18제곱까지 범위인 2의 61제곱까지 전제 비트마스크 검사를 합니다.
2. 비트 마스크에서 1의 개수를 셉니다.
3. 개수가 홀수면 1, 짝수면 0을 출력합니다.