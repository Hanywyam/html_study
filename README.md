# html 기초 수업 #
### 230824 ###

* html: 하이퍼텍스트 마크업 랭귀지로 웹문서의 구조를 담당한다. 페이지 전체의 콘텐츠를 감싸며 루트(root( 최상위 변수))요소 라고 한다.

* 빈요소 =빈태그=열린태그로 종료 태그 없음

* html 성격 : 크게 1-블럭 2-인라인 두가지로 볼 수 있다.

#### 1. 제목태그 title ####
* 인라인 태그.
* `<h1>~<h6>` 제목 태그로 사용.
	* h1 태그: 문서의 메인 제목, 한 문서에 한번만 사용하는 것을 권장. 주로 로고에 사용한다.<br>
	* h2~h6 태그: 제목 태그로 한 문서 안에 여러 번 사용 가능. 제목은 순서대로 사용하지 않아도 된다.<br>태그가 갖고 있는 성격/의미에 따라 사용할 수 있다.

#### 2. 문단태그 p ####
* 블록 태그. 
* 블록 요소이나 문단 태그는 또 다른 블록 요소를 포함하지 않는다. 주로 인라인 요소에만 넣음.
* 문단을 나눌 때 사용. 문단으로 나눠 구분하기 때문에 행간이 넓게 보인다.(여백이 많은편)
* 문단은 하나 이상의 문장으로 구성되며 이야기의 독립적인 단위를 형성. 문단의 시작은 새로운 줄로 나타낸다.

#### 3. 줄바꿈 br ####
* 빈 요소, 혹은 열린 태그로 종료 태그가 없다.
* 인라인 태그의 줄을 바꿀때 사용. 단순히 줄만 바뀌기 때문에 블록 태그에 비해 행간이 좁다.(여백이 좁은편)
* 인위적인 여백을 만들기 위해 사용하지 않으며 꼭 필요한 곳에만, 이 위치에 반드시 줄바꿈이 필요한 경우에만 사용한다.
* 반응형 웹에서는 br 태그를 이용해 줄바꿈을 하기 보다 span태그를 이용해 줄바꿈을 하는 편.

#### 4. 강한 강조 태그 strong ####
* 인라인 요소
* 굵은 글씨로 일반적인 강조를 하는 효과를 준다.
* 논리적인 흐름에 맞게 구성해야하기 때문에 strong 안에 문단을 넣을 수 없다.

#### 5. 일반 강조 em ####
* 인라인 요소
* 일반적인 강조의 의미로 사용
* 주로 기울여져서 표현
* 단순히 디자인을 위해 em을 사용하지 않는다.

* [참고]비슷한 태그
	* 강한 강조와 일반강조 초창기 요소로 현재 사용하지 않는다.
		* i태그: 이탤릭의 i. i는 단순 구분을 위해 사용. 
		* b태그: bold의 b. b는 굵은 글씨를 표현.

#### 6. 콘텐츠분할 div ####
* 가장 대표적인 블록요소
*  옛날부터 영역을 나눠줄때 사용하던 태그. 특별한 의미없이 나눠주고 싶을때 사용하기도 했다. id나 class 속성과 함께 사용하며, 단순히 레이아웃을 구성하기 위해 사용.
	* id : 유일한 성격을 가진 속성. id는 유일하게 단독으로 사용.
	* class : class는 어디든 사용할 수 있다.
* 구조를 나누기 위한 태그로 브라우저상에서는 특징이 없음
* 브라우저 화면에 나타나는 스타일이 없기 때문에 단순히 레이아웃을 구성하기 위해 사용.

#### 7. 콘텐츠분할 span ####
* 가장 대표적인 인라인 요소
* 인라인으로 구조를 나누기 위한 태그로 브라우저 상에 나타나는 특징이 없음.
* 주로 다른 텍스트와 구분하고 싶지만 적절한 태그가 없을 때 사용.
* id, class 속성과 함께 사용.

#### textEx.html_오늘 배운 내용 활용해보기 ####

> entity 요소 https://entitycode.com/<br>
> ★유효성 검증 site https://validator.w3.org/<br>
> 이 사이트에서 코드 작성시 유효성 검사 필수. 습관화 하기.



### 230825 ###

* 인용의 출처`<blockquote>`: 인용 블록 요소
* `<p>` 태그 안에는 인라인 태그(input, image, a...등) 빼고 들어갈 수 없다.

#### 1. 사용자정보 address ####
* 블록 요소.
* 사용자의 정보를 입력하는 태그.
* 연락처, url, 주소, sns, 사업자명, 사업자번호 등등

#### 2. 순서 있는 목록 ol ####
* 블록 요소.
* 순서가 필요한 리스트에 사용한다.
* ol 안에 있는 li태그는 자동으로 순서가 적용된다.
* li와 반드시 함께 사용하며, 둘 중 하나만 사용할 수 없다.
* ol과 li 사이에는 다른 태그는 절대 올 수 없다.
	* ol의 자식으로 다른 태그가 올 수 없다.
	* li의 형제로 다른 태그가 올 수 없다.
* li태그 안에는 다양한 다른 태그들 작성 가능하다.

#### 3. 순서 없는 목록 ul ####
* 블록 요소.
* 블릿 기호로 표기된다.
* li와 반드시 함께 사용하며 ul 안에 있는 li태그는 자동으로 블릿 기호가 적용된다.
* ul과 li 사이에는 다른 태그는 절대 올 수 없다.
	* ul의 자식으로 다른 태그가 올 수 없다.
	* li의 형제로 다른 태그가 올 수 없다.
* li태그 안에는 다양한 다른 태그들 작성 가능하다.


#### 4. 정의형 목록 dl ####
* 블록 요소.
* 정의형 목록 태그로 용어의 정의, 설명, 참고문헌, 메타데이터 등 다양하게 사용 가능
* dl/dt/dd는 항상 같이 사용한다. dl안에서 dd없이 dt단독사용도 가능하다.
* 일부 os에서 dl의 정의가 다르기 때문에 접근성이 좋지 않음
	* dt : 항목의 제목, 용어 ..등등</dt>
	* dd : 위의 제목이나 용어의 설명을 작성하는 부분<br>dd는 하나 이상 작성 가능

#### listEx1.html_오늘 배운 내용 활용해보기 ####
#### listEx2.html_오늘 배운 내용 활용해보기 ####
#### 중첩 메뉴.html_오늘 배운 내용 활용해보기 ####



### 230828 ###

#### 1. thml5 layout ####
* html5 기본 구성
	* 헤더 
	* 메인컨텐츠
	* 푸터 - 바닥글
* 크게 3분할로 구성되어 있다.
* 코드 파일에서 자세히 확인하기.

#### 2. 앵커 anchor ####
* href 속성을 이용하여 하이퍼 텍스트 설정
* 인라인 요소로 `<p>`태그를 이용하여 블럭설정하여 스타일을 주기도 한다.
* 임시 링크 기호 `#` 는 특별하게 주소를 작성 못하는 경우`""`는 빈칸으로 둘 수 없으며. 반드시 `#`를 이용하여 채운다. `#`는 `a태그`에서만 사용이 가능하다.

* **URL이란?**

: 특정 파일을 가리키는 주소 및 이름으로 URL은 세상에 하나만 존재하며 동일 URL이 두 개 이상의 데이터를 가리킬 수 는 없다.<br>

#### 3. 절대 경로 ####
* 외부 사이트로의 이동시 사용 
* 반드시 `http://` 혹은 `https://`로 시작하는 주소로 작성


### 230829 ###

#### 4. 상대 경로 ####
* 상대경로 : 내 도메인 안에서 돌아다닐 때 사용.
* 사이트의 내비게이션 =메뉴역할
* 현재 작업중인 문서 기준. 동일한 사이트 안에서의 이동 시 사용.(내부 이동)

* 상대경로는 2가지가 있다?
	* root 상대경로
	* 이름만 쓰는 상대경로

* 기준 문서

	* 기준 파일과 같은 위치에 있는 파일로 이동 : `./파일명.html` (혹은 `파일명.html` 잘사용하지 않음.)
	* 기준 파일보다 하위에 있는 파일로 이동 : `./디렉토리명/파일명.html`
	* 기준 파일보다 상위에 있는 파일로 이동 : `../파일명.html`

* index.thml : 모든 웹 문서의 첫 페이지로 약속됨. 임의 변경 불가. <br>
다른 디렉토리에 동일한 index.thml를 사용할 수 있지만, 최상위 root 폴더 바로 아래 있는 index.html 문서만 첫페이지로 인식.<br>


### 230830 ###

#### 1. 건너띄기 링크 ####
﻿* 특정 위치로 이동하는 태그
* anchor : 이동 태그
	* `"#"` 임시링크 기호
	* `href="#title"` 을 값으로 작성하면 동일한 이름을 가진 id 속성이 있는 태그 위치로 이동
		* ex) `<a href="#title1">초판 바로가기</a>`
	* 페이지 상단으로 이동하고자 할때
		* `<a href="#top">맨위로 #top</a>`
		* `<a href="#">맨위로 #</a></p>`

#### 2. 서브페이지 연결 ####
* `<a href="./1_건너띄기링크.html">메인으로 돌아가기</a>` ->메인 페이지 상단 이동
* `<a href="./1_건너띄기링크.html#title5">메인의 제5판 바로가기</a>` ->문단으로 바로 이동

#### 3. ﻿새창으로 열기 ####
* ﻿a태그 뒤에 `target="_blank"` 추가
* `<a href="https://developer.mozilla.org/ko/docs/Web/HTML/Element/a" target="_blank">MDN 바로가기</a>`