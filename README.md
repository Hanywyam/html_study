# html 기초 수업 #
### 230824 ###

* html: 페이지 전체의 콘텐츠를 감싸며 루트(root( 최상위 변수))요소 라고 한다.

* 빈요소 =빈태그=열린태그로 종료 태그 없음

* html 성격 : 크게 1-블럭 2-인라인 두가지로 볼 수 있다.

​#### 1. 제목태그 title ####
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
* 디자인을 위해 em을 사용하지 않는다.

* 비슷한 태그
	* 강한 강조와 일반강조 초창기 요소
		* i태그: 이탤릭의 i. i는 단순 구분을 위해 사용. 
		* b태그: bold의 b. b는 굵은 글씨를 표현.

#### 6. 콘텐츠분할 div ####
* 가장 대표적인 블록요소
*  옛날부터 영역을 나눠줄때 사용하던 태그. 특별한 의미없이 나눠주고 싶을때 사용하기도 했다. id나 class 속성과 함께 사용하며, 단순히 레이아웃을 구성하기 위해 사용.
	* id : 유일한 성격을 가진 속성. id는 유일하게 단독으로 사용.
	* class : class는 어디든 사용할 수 있다.
* 구조를 나누기 위한 태그로 브라우저상에서는 특징이 없음
* 브라우저 화면에 나타나는 스타일이 없기 때문에 단순히 레이아웃을 구성하기 위해 사용.
* 브라우저 화면에 나타나는 스타일이 없기 때문에 단순히 레이아웃을 구성하기 위해 사용.

#### 7. 콘텐츠분할 span ####
* 가장 대표적인 인라인 요소
* 인라인으로 구조를 나누기 위한 태그로 브라우저 상에 나타나는 특징이 없음.
* 주로 다른 텍스트와 구분하고 싶지만 적절한 태그가 없을 때 사용.
* id, class 속성과 함께 사용.

#### textEx_오늘 배운 내용 활용해보기 ####

* entity 요소 https://entitycode.com/
* ★유효성 검증 site https://validator.w3.org/
	* 이 사이트에서 코드 작성시 유효성 검사 필수. 습관화 하기.


​### 230825 ###

1. 사용자정보 address
2. 순서 있는 목록 ol
3. 순서 없는 목록 ul
4. 정의형 목록 dl
5. 중첩 메뉴_오늘 배운 내용 활용해보기
listEx1_오늘 배운 내용 활용해보기
listEx2_오늘 배운 내용 활용해보기

### 230828 ###

1. thml5 layout
2. anchor
3. 절대 경로
4. 상대 경로