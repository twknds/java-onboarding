## 문제3번 기능구현사항 정리

핵심 구현 idea :  1-n까지 for문을 돌리면서 해당 숫자를 10으로 계속 나누게 되면 모든 자릿수를 구할수 있게 된다.

모든 자릿수를 비교해서 3,6,9가 존재하면 박수횟수를 증가시킨다.

필수 구현 기능 목록 : count

### 구현 메소드 명세

count : 3,6,9가 포함될때마다 카운트를 올리고 n까지 처리한 후 카운트값 리턴 