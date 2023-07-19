# Travel_Log
Django를 사용하여 여행 블로그 개발 repo

## 진행상황

## 목표 (2단계: 로그인/회원가입 기능을 이용하여 블로그 구현하기)

로그인, 회원가입 기능을 추가하여 블로그를 구현해봅니다. 인증(Authorization)기능이 추가됩니다.

- 요구사항
    
    <aside>
    💡 이전 단계에서 추가된 기능은 밑줄이 쳐져있습니다.
    
    </aside>
    
    ~~- [x]  **메인페이지 구현**(7월 18일)~~
       ~~- [x]  url : `/`(7월 18일)~~
       ~~- [x]  페이지 제목과 블로그 입장하기 버튼이 있습니다. (7월 17일)~~
       ~~- [x]  회원가입/로그인 버튼이 있습니다. (7월 17일)~~
       ~~- [x]  회원가입 버튼을 클릭하면 회원가입 페이지로 이동합니다.(7월 18일)~~
       ~~- [x]  로그인 버튼을 클릭하면 로그인 페이지로 이동합니다.(7월 18일)~~
   ~~- [x]  **회원가입 기능 구현**(7월 18일)~~
       ~~- [x]  url : `/register`(7월 18일)~~
       ~~- [x]  회원가입을 할 수 있는 페이지가 있어야합니다.(7월 18일)~~
       ~~- [x]  입력받는 값은 id, password입니다.(7월 18일)~~
   ~~- [x]  **로그인 기능 구현**(7월 18일)~~
       ~~- [x]  url : `/login`(7월 18일)~~
       ~~- [x]  로그인을 할 수 있는 페이지가 있어야합니다.(7월 18일)~~
       ~~- [x]  입력받는 값은 id, password입니다.(7월 18일)~~
   ~~- [x]  **게시글 작성 기능 구현**(7월 18일)~~
       ~~- [x]  **로그인을 한 유저만 해당 기능을 사용 할 수 있습니다.**(7월 18일)~~
           ~~- [x]  url : `/blog/write`(7월 18일)~~
           ~~- [x]  게시글 제목과 내용을 작성 할 수 있는 페이지가 있어야 합니다.(7월 18일)~~
           ~~- [x]  작성한 게시글이 저장되어 게시글 목록에 보여야 합니다.(7월 18일)~~
    - [ ]  **게시글 목록 기능 구현**
       ~~- [x]  url : `/blog`(7월 18일)~~
       ~~- [x]  **모든 사용자들이 게시한 블로그 게시글들의 제목을 확인 할 수 있습니다.** (7월 17일)~~
       ~~- [x]  목록 페이징 기능을 추가합니다. (7월 17일)~~
        - [ ]  목록 조회순, 최신순으로 정렬기능 추가합니다.
        - [ ]  조회한 게시물의 총 수를 보여줍니다.
        - [ ]  작성 일의 날짜를 yy-mm-dd로 보여준다
        - [ ]  게시글 클릭 시 조회수 증가 기능 구현
   ~~- [x]  게시글 상세보기 기능 구현(7월 18일)~~
       ~~- [x]  url : `/blog/<int:id>` ex)`/blog/1, /blog/2,...(7월 18일)~~
       ~~- [x]  게시글의 제목/내용을 보는 기능입니다.(7월 18일)~~
    - [ ]  게시글 검색 기능 구현
        - [ ]  url : `/blog/search/<str:tag>`
        - [ ]  주제와 태그에 따라 검색이 가능하게 합니다.
        - [ ]  검색한 게시물은 시간순에 따라 정렬이 가능해야 합니다.
    - [ ]  **게시글 수정 기능 구현**
       ~~- [x]  **로그인을 한 유저만 해당 기능을 사용 할 수 있습니다.**(7월 18일)~~
        - [ ]  **본인의 게시글이 아니라면 수정이 불가능합니다.**
       ~~- [x]  url : `/blog/edit/<int:id>`(7월 18일)~~
       ~~- [x]  게시글의 제목 또는 내용을 수정 하는 기능입니다.(7월 18일)~~
       ~~- [x]  게시글 제목과 내용을 수정 할 수 있는 페이지가 있어야합니다.(7월 18일)~~
       ~~- [x]  수정된 내용은 게시글 목록보기/상세보기에 반영되어야합니다.(7월 18일)~~
    - [ ]  **게시글 삭제 기능 구현**
        - [ ]  **로그인을 한 유저만 해당 기능을 사용 할 수 있습니다.**
        - [ ]  **본인의 게시글이 아니라면 수정이 불가능합니다.**
       ~~- [x]  url : `/blog/delete/<int:id>`(7월 17일)~~
        - [ ]  게시글을 삭제하는 기능입니다.
        - [ ]  삭제를 완료한 이후에 게시글 목록 화면으로 돌아갑니다.
        - [ ]  **삭제된 게시글은 게시글 목록보기/상세보기에서 접근이 불가능하며,
        접근 시도 시 <존재하지 않는 게시글입니다> 라는 페이지를 보여줍니다.**
