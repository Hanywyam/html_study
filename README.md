# html 기초 수업 #
### 230824 ###

html: 페이지 전체의 콘텐츠를 감싸며 루트(root( 최상위 변수))요소 라고 한다.

​

* 빈요소 =빈태그=열린태그로 종료 태그 없음

* html 성격 : 1-블럭 2-인라인 두가지로 볼 수 있다.

​

* 기본 태그

​

<!DOCTYPE html>

<thml lang="ko">

    <head>

        <meta charset="utf-8">

        <title></title> 

    </head>

​

    <body>

    </body>

</html>


* 제목 태그<h1>~<h6> : 제목 태그로 사용.

​

<!DOCTYPE html>

<thml lang="ko">

<head>

<meta charset="utf=8">

<title>제목 태그</title>

</head>

​

<body>

<h1>h1 태그: 문서의 메인 제목, 한 문서에 한 번만 사용하는 것을 권장. 주로 로고에 사용</h1>

<h2>h2 ~ h6 태그: 제목 태그로 한 문서 안에 여러 번 사용 가능</h2>

<h2>의미없이 제목 단계를 건너띄지 않음. 순차적 기입.</h2>

<h3>인라인 태그로 중첩 작성 가능</h3>

<h4>h4 태그</h4>

<h5>h5 태그</h5>

<h6>h6 태그</h6>

<!-- 태그가 갖고 있는 성격/의미를 기억해두고 사용. 보여지는 건 의미없다?

html 성격 1-블럭 2-인라인 두 가지. h1~h6 태그는 블럭 성격을 가지고 있다.

-->

</body>

​

</thml>

​

* 문단 태그<p> : 문단을 나눌 때 사용. 문단으로 나눠 구분하기 때문에 행간이 넓다.(여백이 많은편)

​

<!DOCTYPE html>

<html lang="ko">

<head>

<meta charset="utf-8">

<title>문단 태그</title>

</head>

​

<body>

<h1>문단 태그p</h1>

<h2>문단을 정의하는 요소</h2>

<h3>블록 요소이나 문단 태그는 또 다른 블록 요소를 포함하지 않는다. 주로 인라인 요소에만 넣음.</h3>

<p>문단은 하나 이상의 문장으로 구성되며 이야기의 독립적인 단위를 형성. 문단의 시작은 새로운 줄로 나타낸다.</p>

<p>태그 구성: <요소 Element 속성 Attribute="값valye"></p>

<h2>시맨틱 마크업 Semantic Markup</h2>

<p>태그가 가진 의미에 집중하여 컨텐츠 자체에 의미를 부여하는 것. 웹접근성 부분에서도 중요</p>

</body>

</html>

​

* 줄바꿈 태그<br> : 단순히 줄바꿀때 사용. 줄만 바뀌기 때문에 행간이 좁다.(여백이 좁은편)

​

<!DOCTYPE html>

<html lang="ko">

<head>

<meta charset="utf-8">

<title>줄바꿈 태그 br</title> 

</head>

​

<body>

<h1>줄바꿈 태그 br</h1>

​

<h2>빈 요소, 혹은 열린 태그로 종료 태그 없음</h2>

​

<p>인위적인 여백을 만들기 위해 사용하지 않으며 꼭 필요한 곳에만, <br>이 위치에 반드시 줄바꿈이 필요한 경우에만 사용한다.<br>반응형 웹에서는 br 태그를 이용해 줄바꿈을 하기 보다 span태그를 이용해 줄바꿈을 하는 편.</p>

</body>

</html>

​

* 강한 강조 태그<strong> : 굵은 글씨로 일반적인 강조를 하는 효과를 준다.

​

<!DOCTYPE html>

<html lang="ko">

<head>

<meta charset="UTF-8">

<title>강한 강조 태그 strong</title>

</head>

<body>

<h1>강한 강조 태그 strong</h1>

<h2>인라인 요소</h2>

<!--

<strong><p>논리적인 흐름에 맞게 구성해야하기 때문에 strong 안에 문단을 넣을 수 없다.</p></strong>

​

<p><h2>의미상 문단 안에 제목을 쓸 수 없기 때문에 오류</h2></p>

-->

​

<p><strong>주의:</strong> 소매치기가 이 지역에서 발생하고 있습니다.</p>

<p>이 인형은 작은 조각이 많이 있으므로 <strong>5세 미만의 아이들</strong>에게 적합하지 않습니다.</p>

</body>

</html>

​

* 일반 강조 <em> : 일반적인 강조의 의미로 사용

​

<!DOCTYPE html>

<html lang="ko">

<head>

<meta charset="utf-8">

<title>일반 강조em</title>

</head>

​

<body>

<h1>일반강조 em</h1>

<h2>인라인 요소 </h2>

<p>일반적인 강조의 의미로 사용</p>

<p>1. <em>em</em>은 주로 기울여져서 표현 됩니다.</p>

<!-- inline 요소 안에 block 요소를 사용할 수 없기 때문에 아래의 구조는 오류 -->

<em><p>2. 디자인을 위해 em을 사용해서는 안됩니다.</p></em>

<p>3. <b>비슷한 태그로 i가 있습니다.</b> <i>i는 단순 구분을 위해 사용합니다.</i> </p> <!-- 이 두 태그는 지금은 쓰지 않는다. -->

</body>

</html>

* 콘텐츠 분할 <div> : 옛날부터 영역을 나눠줄때 사용하던 태그. 특별한 의미없이 나눠주고 싶을때 사용하기도 했다. id나 class 속성과 함께 사용하며, 단순히 레이아웃을 구성하기 위해 사용.

​

- id : 유일한 성격을 가진 속성. id는 유일하게 단독으로 사용.

- class : class는 어디든 사용할 수 있다.

​

<!DOCTYPE html>

<html lang="ko">

<head>

<meta charset="UTF-8">

<title>콘텐츠 분할 div</title>

</head>

​

<body>

<h1>콘텐츠 분할 div</h1>

<h2>가장 대표적인 블록요소<br>

구조를 나누기 위한 태그로 브라우저상의 특징이 없음</h2>

<!--

<p>브라우저 화면에 나타나는 스타일이 없기 때문에 단순히 레이아웃을 구성하기 위해 사용.<br>

<p>id, class 속성과 함께 사용.</p>

-->

<div id="txt1">브라우저 화면에 나타나는 스타일이 없기 때문에 단순히 레이아웃을 나누기 위해 사용.</div>

<div class="txt1">id, class 속성과 함께 사용.</div>

</body>

</html>

​

* 콘텐츠분할 <span> :

​

<!DOCTYPE html>

<html lang="ko">

<head>

<meta charset="UTF-8">

<title>콘텐츠 분할 span</title>

<style>

@media screen and (max-width: 414px) {

.wrap { display: block; }

}

</style>

</head>

​

<body>

<h1>콘텐츠 분할 span</h1>

<h3>가장 대표적인 인라인 요소</h3>

<h2>인라인으로 구조를 나누기 위한 태그 /

<span class="wrap">브라우저 상에 나타나는 특징이 없음.</span>

</h2>

<!-- 

제목 태그 사용에 순서는 상관없다. 

제목에 줄바꿈을 해주고 싶을때 span을 사용한다.

-->

​

<span class="txt">주로 다른 텍스트와 구분하고 싶지만 적절한 태그가 없을 때 사용.</span>

<span class="txt">id, class 속성과 함께 사용.</span>

​

</body>

</html>

​

