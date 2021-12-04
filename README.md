# KoKoa Clone 2
    Insu's second version of kokoa clone practice

## chapter 1
    - 대부분의 웹 서버가 디폴트로 index.html 을 찾아보도록 설정되어있다.
    - class name은 길고 상세히 적는게 좋다.
        1. class name의 중복을 막는다
        2. CSS를 읽을 때 어떤 자식을 가리키는지 알기 어려운 상태를 방지한다.
            - ex) status-bar__column

## chatpter2 BEM
    BEM (Block Element Modifier)
        - 좀 더 쉽게 읽히는 CSS를 가지는 방법
        - Googling BEM CSS
        - [참고 사이트](https://nykim.work/15)
    
    BEM +a
        ex) .btn__price { } : element
        ex) .btn--orange { } : modifier
        - 클래스를 분리해서 사용하면 코드를 보다 쉽게 읽을 수 있다.
        - BEM은 CSS를 작성할 때 작성하려는게 id였는지 class였는지 헷갈릴 때가 많은데
          이런 문제점을 인식해 **모든 부분을 class로** 나타내려고 노력하면서 만들어 졌다.

## chapter3 Get Icons
    icon 구하기
        1. 직접 구하기 : 직접이미지를 만들고 추출하거나 svg파일을 이용한다.
            - svg: 픽셀이 없는 이미지 파일 형식
        2. 가져오기
            [Fontawesonme](https://fontawesome.com)
            [Heroicons](https://heroicons.dev)

## chapter4 Font
    Font 구하기
        [구글폰트](https://fonts.google.com/)
    Font 적용하기
        - css 파일에 @import로 추가하는 방식으로 적용시키는 게 좋다.

## chapter5 CSS
    CSS 기술
        > 몇몇 CSS 작업은 컨테이너를 특정위치에 놓기위해 쓰여지는데
        > 좀 이상해도 잘 적용되므로 서로 공유하여 사용하는 설정이 있음.
        > ex) status-bar
    
    reset CSS
        - 브라우저가 알아서 기본으로 html에 적용시키는 스타일이 있는데
          그 것을 제거하기 위한 방법.(대부분이 margin:0, padding:0, border:0,...등을 가진 css파일)
        - 구글에 검색해서 복사 붙여넣고 별도의 파일로 구성해서 @import로 사용하는게 좋다.

© 2017-2021 Nomad Coders. All rights reserved.