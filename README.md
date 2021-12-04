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
        - 참고 사이트: *[https://nykim.work/15]*
    
    BEM +a
        ex) .btn__price { } : element
        ex) .btn--orange { } : modifier
        - 클래스를 분리해서 사용하면 코드를 보다 쉽게 읽을 수 있다.
        - BEM은 CSS를 작성할 때 작성하려는게 id였는지 class였는지 헷갈릴 때가 많은데
          이런 문제점을 인식해 **모든 부분을 class로** 나타내려고 노력하면서 만들어 졌다.

    © 2017-2021 Nomad Coders. All rights reserved.