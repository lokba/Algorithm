문제 푼 날짜 : 2021.8.5

<h2>문제 : 가장 긴 공통 부분 문자열</h2>

<h3>내가 푼 방식</h3>
<div>1. for~in 문으로 b 문자열에 접근한다.</div>
<div>2. 접근한 각 인덱스(v)를 기준으로 b.slice(v,idx)를 한다. 3,4번 프로세스로 넘어간다.(idx=v+1)</div>
<div>3. slice한 문자열이 a 문자열에 포함되어 있으면, idx++ 한뒤, 2번을 다시 실행한다.</div>
<div>4. slice한 문자열이 a 문자열에 포함되어 있지 않으면, (idx-v)의 값을 res 배열에 집어넣는다.</div>
<div>5. res에서 가장 큰 값을 도출하여 해결.</div>


<h3>다른 방식</h3>
<div>1. a 문자열을 1 ~ a.length 까지 문자열을 쪼갠다.</div>
<div>2. b 문자열을 1 ~ b.length 까지 문자열을 쪼갠다.</div>
<div>-> 예시 : "abc" -> "abc", "ab", "bc", "a", "b", "c"</div>
<div>3. 쪼갠 b 문자열의 집합소에서 쪼갠 a 문자열에 집합소에 포함된 것만 추출하여 해결.</div>
<div>내 생각 : 좋은 풀이방식은 아니라고 생각하지만, 이런 방식으로도 풀 수 있다는 생각이 들었다.</div>
