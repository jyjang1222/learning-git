# gitignore 작성법

## gitignore 자동생성 사이트
검색창에 운영체제, 개발환경(IDE), 프로그래밍 언어를 검색하면 .gitignore 파일을 자동으로 생성해 준다.
https://www.toptal.com/developers/gitignore

## gitignore 파일 규칙
|표현|의미|
|---|---|
|#, 빈라인|#은 주석을 의미하며, 빈라인은 아무런 영향을 주지 않습니다.|
| *.a|오른쪽정렬|
|folder_name/|해당 폴더의 모든 파일을 무시합니다.
|folder_name/*.a|해당 폴더의 확장자가 .a 인 모든 파일을 무시합니다.|
|folder_name/**/*.a|해당 폴더 포함한 하위 모든 폴더에서 확장자가 .a 인 모든 파일을 무시합니다.|
|/*.a|현재 폴더의 확장자가 .a 인 모든파일을 무시합니다.|

# readme 작성법
## table 생성 사이트
https://www.tablesgenerator.com/markdown_tables
## 코드 블럭
<code>.toString</code>
html code태그 사용
