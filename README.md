# self-study

CSS 우선순위

        1.속성 값 뒤에 !important 를 붙인 속성
        2.HTML에서 style을 직접 지정한 속성
        3.#id 로 지정한 속성
        4..클래스, :추상클래스 로 지정한 속성
        5.태그이름 으로 지정한 속성
        6.상위 객체에 의해 상속된 속성
        
        ✔기본적으로 뒤에 나오는 css가 우선순위가 높음
        ✔우선순위가 같다면 개수가 많은 css가 우선순위가 높음
        

클래스 이름을 부를 때는 더 우선수위를 가지면서 더 디테일하게 들어간 것이 우선순위다.

가령 똑같은 p 태그를 입력했는데 어떤 것은 .box p {} 라고 입력을 하고 어떤 것은 p {} 라고 입력을 했다 하자

그러면 우선 순위로 먹는 것은 .box p {}이다.




ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ




justify-content

: 요소들의 수평(->) 방향 정렬 방식을 설정하는 속성

flex-start : 컨테이너 앞쪽부터 배치 (왼 → 오, 위 → 아래), (default)

flex-end : 컨테이너의 뒤쪽부터 배치 (오 → 왼, 아래 → 위)
(순서는 그대로, 통채로 위치만 바뀜! flex-direction의 reverse는 순서가 바뀜)

center : 컨테이너 가운데서부터 배치

space-around : 앞, 뒤, 요소들 사이 모두 여유 공간을 두고 배치

space-evenly : 동일 간격으로 공간 확보

space-between : 요소들 사이에만 여유 공간을 두고 배치

https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbbpMKe%2FbtqPZJBlLWm%2F2lkHw2KsAspMrkVu02WKC0%2Fimg.png





ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ




flex-direction

: 요소들을 배열하는 순서와 축을 지정하는 속성 
row : 행방향으로 정렬
row-reverse : 행방향으로 정렬 + 반대 순서
column : 열방향으로 정렬
column-reverse : 열방향으로 정렬 + 반대 순서

https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbPCwpK%2FbtqP0tkE9oq%2FjkiIvQAOTyWeKmF3dpnn40%2Fimg.png





ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ




flex-wrap
: 줄바꿈 기준

nowrap : 모양을 변경하면서 줄 유지 (default)
wrap : 모양을 유지하며 다음줄로 넘김 + 위에서 아래 순으로
wrap-reverse : 모양을 유지하며 다음줄로 넘김 + 아래서 위 순으로

https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FCdY51%2FbtqPQs14yYU%2FoBP6ek4r0ptBRcOEAizth0%2Fimg.png




ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
