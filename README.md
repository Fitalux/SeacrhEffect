# SeacrhEffect
 <img src="https://github.com/Fitalux/SeacrhEffect/blob/main/image/display.png" />

# VIEW SITE
https://fitalux.github.io/web2023/javascript/seacrhEffect/seacrhEffect01.html

# DESC
이 프로젝트는 검색 기능을 구현하는 Javascript입니다.
웹페이지 내에서 사용자가 검색어를 입력하면 입력된 검색어와 일치하는 항목들을 보여주고 일치하지 않는 항목들을 숨기는 기능을 제공합니다.
사용자가 키워드를 입력하면 입력한 내용과 일치하는 검색 결과와 일치하는 항목의 갯수를 확인할 수 있습니다.

# SCRIPT DESC

dataset
: JAVASCRIPT DOM 요소의 속성으로, HTML 요소에 'data-'인 접두사로 정의된 사용자 정의 데이터 속성들을 가져오거나 설정하는데 사용됩니다.
'data-' 접두사를 가진 HTML 속성은 dataset 객체로 접근할 수 있습니다.

indexOf
: JAVASCRIPT의 배열 메서드로, 배열에서 특정 요소가 처음으로 등장하는 인덱스(자릿값)을 반환합니다.
해당 요소가 배열에 존재하지 않을 경우 -1을 반환합니다.

innerHTML
: JAVASCRIPT DOM 요소의 프로퍼티로 해당 요소의 HTML 내용을 가져오거나 설정하는데 사용됩니다.
HTML 태그를 포함한 문자열을 읽어내거나 삽입할 수 있습니다.

textContent
: JAVASCRIPT DOM 요소의 프로퍼티로, 해당 요소의 텍스트 내용을 가져오거나 설정하는데 사용됩니다.
HTML 태그는 무시하고 텍스트만 다룹니다.

addEventListener("keyup")
: JAVASCRIPT DOM 요소에 이벤트 리스너를 추가하는 메서드로, 특정 이벤트가 발생했을 때 실행할 함수를 등록하는데 사용됩니다.
keyup 이벤트는 키보드의 키를 눌렀다가 뗐을 때 발생하며, 이 프로젝트에서는 사용자가 input box에 검색어를 입력하고 enter 키를 눌렀을 때 검색을 실행시킵니다.

forEach
: JAVASCRIPT의 배열 메서드로, 배열의 각 요소에 대해 주어진 함수를 한 번씩 실행하는 역할을 합니다.
for 루프와 달리 간단하게 배열 요소에 접근할 수 있습니다.
