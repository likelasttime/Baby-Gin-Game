# Baby-Gin-Game

🎁 문제 출처 : SW expert academy

0~9 사이의 숫자 카드에서 임의의 카드 6장을 뽑았을 때, 3장의 카드가 연속적인 번호를 갖는 경우를 run이라 하고, 3장의 카드가 동일한 번호를 갖는 경우를 tripletes이라고 한다. 그리고, 6장의 카드가 run과 tripletes로만 구성된 경우를 Baby-Gin이라고 하는데, 6자리의 숫자를 입력 받아 Baby-Gin 여부를 판단하는 프로그램을 작성해 보자.

 
**예)**<br>
667767은 두 개의 triplet이므로 Baby-Gin이다.(666, 777) <br>
054060은 한 개의 run과 한 개의 triplet이므로 Baby-Gin이다. (456, 000)<br>
101123은 한 개의 triplet가 존재하나, 023이 run이 아니므로 Baby-Gin이 아니다.

 
**입력**
첫 번째 줄에 전체 테스트 케이스의 수 T(1<=T<=100)가 주어진다. 각 테스트 케이스는 6자리의 숫자가 들어온다.

 
**입력 예시**<br>
3     // 전체 테스트 케이스의 수<br>
667767<br>
054060<br>
101123

 

**출력**
입력된 테스트 케이스가 Baby-Gin이면 Baby Gin, 아니면 Lose 출력



**출력 예시**<br>
Baby Gin<br>
Baby Gin<br>
Lose
