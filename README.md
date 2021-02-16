# README.md

# HTML, CSS 복습용

> 이 저장소는 HTML, CSS 연습파일 단순 복습용입니다...

### WebApp01

- **Test001.html**
    - 주석문 표시 태그 `<!— —>`
    - `<p>` 태그로 문단 구성
    - 개행은 `<br>`이라는 단독 태그
    - 영역 구성은 `<div>` 로 한다.
    - `<span>` 태그는 문장의 일부 단어나 문장을 특별히 강조할 경우 사용함.
- **Test002.html**
    - 순서가 있을 경우 
      ```html
	<ol>
	    <li>안녕하세요. 순서 있는 태그에요.</li>
	    <li>전 왜 안나오나요?</li>
	</ol>
      ```
	사용함.

    - 순서가 없을 경우 
      ```html
         <ul>
             <li>안녕하세요. 순서가 없는 태그에요.</li>
	     <li>저는 나오나요?</li>
         </ul>
      ```
	사용함.

    - '<dl>' '<dt>'태그는 대상을 정의할 경우에 많이 사용함.

    ```html
    <dl>
    	<dt>나 : </dt>
    	<dd>코딩 복습중</dd>
    </dl>
    ```

    위와 같이 대상을 정의하는 형태로 자주 사용하는데, 개행이 일어나지 않는 점만 이용하여 의미와 다르게 사용할 뻔 했다...

- ** Test003.html **
    - 'bgcolor' 속성으로 '<body>' 태그의 색상 변경.
    - 'background' 속성으로 이미지 변경.
    - 'text', 'leftmargin', 'topmargin' 등의 속성 이용하였으나 웹표준에 맞지 않으므로 설명은 생략한다.
- ** Test004.html **
    - Test003.html과 같은 페이지로 '<input>' 태그 구성해봄.
- ** Test005.html **
    - 자바스크립트를 이용하여 국어, 영어, 수학 점수를 받고 총점과 평균을 계산하여 페이지에 표시한다.