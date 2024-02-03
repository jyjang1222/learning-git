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

# 마크다운 코드블록
| 언어 |  Markdown | 언어  | Markdown  |
|:-:|:-:|:-:|:-:|
| Bash | bash  |  JSON | json  |
| C#  |  cs |  Java | java  |
|  C++ |  cpp | JavaScript  | javascript  |
|  CSS |  css |  PHP |  php |
|  Diff |  diff |  Perl |  perl |
|  HTML, XML |  html | Python  | python  |
|  HTTP |  http | Ruby  | ruby |
|  Ini |  ini | SQL  | sql  |

# readme 작성법
## table 생성 사이트
https://www.tablesgenerator.com/markdown_tables
## 코드 블럭
<code>.toString</code>
html code태그 사용

# github desktop
## 커밋 되돌리기
1. 왼쪽 사이드바에서 **기록**을 클릭합니다.
<img src="/assets/cb-130307/images/help/desktop/history-tab-in-commit-sidebar.png" alt="사이드바의 &quot;기록&quot; 탭 스크린샷. 커밋 목록 위에 &quot;기록&quot; 탭 단추가 주황색 윤곽선으로 강조 표시됩니다.">
2. 되돌리려는 커밋을 마우스 오른쪽 단추로 클릭하고 커밋에서 **변경 내용 되돌리기**를 클릭합니다.
<img src="/assets/cb-146981/images/help/desktop/commit-revert-mac.png" alt="&quot;기록&quot; 탭의 커밋 목록 스크린샷. 커밋 옆에 있는 상황에 맞는 메뉴에서 커서가 &quot;커밋 변경 내용 되돌리기&quot;에 있습니다.">
