문제 푼 날짜 : 2021.8.8

<h2>문제 : 순회하는 리스트</h2>

<h3>내가 푼 방식</h3>
<div>1. ary.slice()을 이용해 사본을 만든다.</div>
<div>2. 사본.splice(ary.length - n(순회횟수))의 값을 저장한다.</div>
<div>3. 2번에서 저장한 값을 순회하면서 사본에 unshift한다.</div>
<div>4. 3번의 결과가 원본에서 n번 순회한 배열이다.</div>
<div>5. 원본 배열과 순회한 배열을 사용하여 결과를 도출한다.</div>


<h4>기억하기</h4>
<div>원본과 사본을 만들고 싶을때 -> slice()</div>
<div>splice() 사용법 익숙해지기</div>
<div>splice는 원본에 반영이 되며, slice는 원본에 반영이 안된다.</div>
