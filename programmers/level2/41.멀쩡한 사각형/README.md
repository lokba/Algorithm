문제 푼 날짜 : 2021.9.30

<h2>문제 : 멀쩡한 사각형</h2>

<h3>내가 푼 방식</h3>
<div>1. 간단한 로직이기에 풀이 생략.</div>

<h3>알게 된 점</h3>
<div>1. JS는 소수점을 가진 값의 계산이 조금 부정확합니다.</div>
<div>2. 예를 들면 0.1 + 0.2 = 0.300000000000000000004처럼 나온다.</div>
<div>3. 2번이 말하는 것은, 소수점을 가진 값을 계산을 할수록 더 부정확해진다는 것이다.</div>
<div>4. (h / w) * i -> (h * i) / w로 하는 것이 더 정확해진다.</div>

<br>
https://programmers.co.kr/learn/courses/30/lessons/62048