# BOJ 5567번 [결혼식](http://noj.am/5567)

## 🌈 풀이 후기
- 친구의 친구까지만 부른다는 걸 못보고 처음에 이상하게 풀었습니다.
## 👩‍🏫 문제 풀이
- 2중 포문을 돌면서
    - 내 친구라면
        - 그 친구의 친구까지 조사.
- visit체크는 `friends[i][i]`로 대신하였습니다.