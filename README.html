<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script> -->
    <title>test</title>
    <style>
        :root{--gauge-width : 100%;}
        *{margin : 0; padding : 0; text-decoration : none; list-style : none;}
        button{background : none; border-style : none;}
        .hide{display : none !important;}
        .wrap{padding : 20px;}
        /*  */
        .fold-btn-wrap{display : flex; align-items : center; justify-content : flex-start; gap : 12px; padding : 24px 20px 0;}
        .fold-btn-wrap button{border-radius : 8px; padding : 6px 12px; font-weight : bold; box-shadow : 2px 2px 2px rgba(0, 0, 0, 0.05);}
        .fold-btn-wrap button:active{box-shadow : inset 4px 4px 4px rgba(0, 0, 0, 0.3);}
        .fold-btn-wrap button:first-of-type{background : yellow;}
        .fold-btn-wrap button:nth-of-type(2){background : darkcyan; color : #fff;}
        .fold-btn-wrap button:nth-of-type(3){background : pink;}
        /*  */
        h1{font-size : 18px; text-align : center; margin : 0 0 20px; padding : 12px 0;}
        .btn-line ul{display : flex; align-items : center; justify-content : center;}
        .btn-line li{margin : 0 12px;}
        .btn-line button .btn-style{border-radius : 8px; background : #eee; display : inline-block; padding : 8px 8px; box-shadow : 4px 4px 4px rgba(0, 0, 0, 0.06); font-size : 16px;}
        .btn-line li:active .btn-style{box-shadow : inset 4px 4px 4px rgba(0, 0, 0, 0.1);}
        .btn-line li:nth-child(2) button .btn-style{background : #ffdbe0;}
        .btn-line li:nth-child(3) button .btn-style{background : #daecff;}
        .btn-line button .btn-style span{display : block; font-size : 12px; margin-top : 2px;}
        .coin-count{text-align : center; margin-top : 24px;}
        .coin-count em{font-style : normal;}
        .mileage{margin : 12px 0; display : flex; align-items : center; justify-content : flex-start; gap : 4px;}
        .mileage p{flex-shrink : 0;}
        .mileage .gauge-wrap{display : inline-flex; align-items : center; justify-content : flex-start; height : 22px; flex : 1; border-radius : 50px; overflow : hidden; border : 2px solid #b9b9b9;}
        .mileage .gauge-wrap #gauge{display : block; width : 100%; height : 100%; background : linear-gradient(90deg, rgba(82,134,240,1) 0%, rgba(106,230,255,1) 100%); position :relative;}
        .mileage .gauge-wrap #gauge::after{content : ""; width : var(--gauge-width); height : 100%; position : absolute; right : 0; top : 0; z-index : 1; background : #fff;}
        .resulte{margin : 24px 0 0;}
        .img-wrap{width : 100%; height : 500px; overflow : hidden; display : flex; align-items : flex-start; position : relative; object-fit: contain;}
        .img-wrap .label{position : absolute; width : 55px; height : 55px; border-radius : 50%; background : none; top : 4px; right : 4px; display : inline-flex; align-items : center; justify-content : center; box-shadow : 4px 4px 4px rgba(0, 0, 0, 0.1); z-index : 1; background : rgba(255, 255, 255, 0.3); backdrop-filter : blur(3px);}
        .img-wrap .grade{right : auto; left : 4px; font-weight : 500;}
        .img-wrap .grade.S{background-color : rgba(252, 199, 255, 0.5)}
        .img-wrap .grade.A{background-color : rgba(248, 255, 199, 0.5); }
        .img-wrap .grade.B{background-color : rgba(241, 241, 241, 0.5); }
        .img-wrap .grade.C{background-color : rgba(198, 224, 214, 0.5); }
        .img-wrap .label span{font-size : 14px; font-weight : 500;}
        .img-wrap img{display : block; width : 100%;}
        /*  */
        .copy-obj{text-align : center;}
        .copy-obj p{font-size : 14px; line-height : 22px; display : flex; flex-direction : column;}
        /*  */
        :root{--scaled-x : 0; --scaled-y : 0; --scaled-z : 0;}
        .card-wrap{padding : 24px 20px 0;}
        .card-wrap #card{width : 300px; height : 450px; margin : 0 auto; transition : 0.2s all; position : relative;}
        .card-wrap #card:hover{transform : rotate3d(var(--scaled-x), var(--scaled-y), 0, var(--scaled-z)) scale3d(1.05, 1.05, 1.05);}
        .card-wrap #card .img-wrap{display : flex; align-items : center; background : #fff; border : 1px solid #6a85b5; border-radius : 24px; box-sizing : border-box; box-shadow : 6px 6px 6px rgba(0, 0, 0, 0.3); height : inherit;}
        .card-wrap #card .light{position : absolute; width : 100%; height : 100%; z-index : 1; border-radius : 24px;}
        /*  */
        .showcase{overflow : hidden; display : flex; align-items : flex-start; justify-content : flex-start; flex-wrap : nowrap;}
        .showcase-page{flex : 0 0 90%; border-radius : 12px; border : 2px solid #6a85b5; overflow : hidden; box-sizing : border-box; padding : 16px; margin-right : 10%;}
        .showcase-page .inner{display : grid; grid-template-columns : repeat(4, 1fr); gap : 14px;}
        .showcase-page .item{height : 99px; position : relative; transition : transform 0.1s; border : 1px solid #cecece; border-radius : 8px;}
        .showcase-page .item:hover{transform : scale(1.1); }
        .showcase-page .item:hover .label{font-size : 14px; color : #000;}
        .showcase-page .item button{display : block; height : inherit;}
        .showcase-page .item .img-wrap{width : 100%; height : inherit; overflow : hidden; object-fit : fill; display : inline-flex; align-items : center; justify-content : center; border-radius : 8px; position : relative; z-index : 1;}
        .showcase-page .item img{display : block; width : 120%;}
        .showcase-page .item::after {content : ""; position : absolute; display : block; width : 94%; border-radius : 20%; height : 4px; background : rgba(0, 0, 0, 0.4); filter : blur(4px); bottom : -1px; left : 3%;}
        .showcase-page .item .label{position : absolute; width : 100%; bottom : 0; left : 0; z-index : 2; font-size : 12px; letter-spacing : -1px; border-radius : 4px; padding : 4px 0; backdrop-filter : blur(5px); transition : all 0.1s;}
        .showcase-page .label.cost-1900{background : rgba(255, 197, 232, 0.5); color : #666; border-bottom-right-radius : 8px; border-bottom-left-radius : 8px;}
        .pagenation{display : flex; align-items : center; justify-content : flex-end; margin : 20px 0; gap : 24px;}
        .pagenation button{display : inline-flex; align-items : center; justify-content : center; border-radius : 50%; box-shadow : 2px 2px 2px rgba(0, 0, 0, 0.1); width : 45px; height : 45px; font-size : 20px; transition : all 0.15s; font-weight : bold;}
        .pagenation button:hover{background:#000; color : #fff; box-shadow : inset 3px 3px 6px rgba(255, 255, 255, 0.6);}
        .pagenation button:active{box-shadow : none;}
        .pagenation .prev{background : yellow;}
        .pagenation .next{background : rgb(214, 175, 250);}
    </style>
</head>
<body>
    <div class="fold-btn-wrap">
        <button type="button" aria-controls="fold01" onclick="foldControlsButton()">1번 섹션 접기</button>
        <button type="button" aria-controls="fold02" onclick="foldControlsButton()">2번 섹션 접기</button>
        <button type="button" aria-controls="fold03" onclick="foldControlsButton()">3번 섹션 접기</button>
    </div>
    <section id="fold01" hidden>
        <div class="wrap">
            <h1>가챠 스크립트 만들기</h1>
            <div class="btn-line">
                <ul>
                    <li>
                        <button type="button" id="btn-d"><span class="btn-style">가챠 뽑기<span>(확률 기본)</span></span></button>
                    </li>
                    <li>
                        <button type="button" id="btn-m" data-name="minji"><span class="btn-style">가챠 뽑기<span>(민지 확률 업)</span></span></button>
                    </li>
                    <li>
                        <button type="button" id="btn-dn" data-name="daniel"><span class="btn-style">가챠 뽑기<span>(다니엘 확률 업)</span></span></button>
                    </li>
                </ul>
            </div>
            <div class="coin-count">
                <p>사용 코인 : <em>0</em></p>
            </div>
            <div class="mileage">
                <p>천장 게이지 : </p><span class="gauge-wrap"><span id="gauge"></span></span>
            </div>
            <div class="resulte">
                <div class="img-wrap">
                    <div class="label grade"><span></span></div>
                    <div id="grade-up" class="label hide"><span>확률 업</span></div>
                    <img src="" alt="">
                </div>
            </div>
            <div id="repeat">
                <p id="first"></p>
                <p id="second"></p>
            </div>
        </div>        
    </section>
    
    <section id="fold02" hidden>
        <div class="card-wrap">
            <div id="card">
                <div class="light"></div>
                <div class="img-wrap">
                    <img src="https://i.namu.wiki/i/GI6X4TltM0KYpcIhA6E2_rTNSKPDAPdtdCRASCWGtUNOouBuMskWDM1jnq4KCbnGcSFpLRUCQRjhsLho9F8MUyv3fTIx1XPcTvIa5Kz_lBPnFRSGdN2VFk3nIJQJ98hvg24jPOoLLOuskhsyF5FQmg.webp" alt="">
                </div>
            </div>
        </div>
    </section>

    <section id="fold03">
        <div class="wrap">
            <div class="showcase">
                <div class="showcase-page" data-page-number="p-01">
                    <ul class="inner">
                        <li class="item">
                            <button type="button" data-price="4500" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/6a06b22d195eeca9cc7e3e9a72bbdbd3.png?q=95&w=320" alt="">
                                </div>
                                <div class="label"></div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/2be7779d1626cf33827d20b6329b146d.png?q=95&w=" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/eb5c0ace6f5c3a9032aa455e7cb533fa.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/6fdf1762876e986169020bf1a0de512a.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/a08a1797a31ed13ceef05f379c3efbce.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/a04ce2a66b0c14517d6ad8b0a69b15c5.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/cc70b24dba514d907cb836bdd61eaf11.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/20a6bd9c62d2b9561dfea6cb56375c67.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/eb19bd1ddc3fc81ff1d7f06bb30eb2db.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/c4136b0c6e9bca33988c77215f315975.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/442ce423bb69e853e036ac011f90b364.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/8761efd5aa60e96753b33136e5d49565.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                    </ul>
                </div>
                <div class="showcase-page" data-page-number="p-02">
                    <ul class="inner">
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/6a06b22d195eeca9cc7e3e9a72bbdbd3.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/2be7779d1626cf33827d20b6329b146d.png?q=95&w=" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/eb5c0ace6f5c3a9032aa455e7cb533fa.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/6fdf1762876e986169020bf1a0de512a.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/a08a1797a31ed13ceef05f379c3efbce.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/cc70b24dba514d907cb836bdd61eaf11.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/20a6bd9c62d2b9561dfea6cb56375c67.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/eb19bd1ddc3fc81ff1d7f06bb30eb2db.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/c4136b0c6e9bca33988c77215f315975.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/442ce423bb69e853e036ac011f90b364.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/8761efd5aa60e96753b33136e5d49565.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/f7a2d323b37319387c9a7a43796ebc92.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                    </ul>
                </div>
                <div class="showcase-page" data-page-number="p-03">
                    <ul class="inner">
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/6a06b22d195eeca9cc7e3e9a72bbdbd3.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/2be7779d1626cf33827d20b6329b146d.png?q=95&w=" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/eb5c0ace6f5c3a9032aa455e7cb533fa.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/6fdf1762876e986169020bf1a0de512a.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/a08a1797a31ed13ceef05f379c3efbce.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/cc70b24dba514d907cb836bdd61eaf11.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/20a6bd9c62d2b9561dfea6cb56375c67.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/eb19bd1ddc3fc81ff1d7f06bb30eb2db.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/c4136b0c6e9bca33988c77215f315975.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/442ce423bb69e853e036ac011f90b364.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/8761efd5aa60e96753b33136e5d49565.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                        <li class="item">
                            <button type="button" data-price="1900" onclick="itemChoiceFunction()">
                                <div class="img-wrap">
                                    <img src="https://cdn-contents.weverseshop.io/public/shop/f7a2d323b37319387c9a7a43796ebc92.png?q=95&w=320" alt="">
                                </div>
                                <div class="label cost-1900">1,900원</div>
                            </button>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="pagenation">
                <button type="button" class="prev" aria-label="" onclick="showcasePagenation()"> ← </button>
                <button type="button" class="next" aria-label="" onclick="showcasePagenation()"> → </button>
            </div>
        </div>
    </section>
    <!-- 재귀함수 연습 -->
    <script>
        const _box = document.getElementById('repeat');

        const _arr = [
            { text : `Hani` },
            { text : `Minji`},
            { text : `Daniel`},
            { text : `Haerin`},
            { text : `Hyein`}
        ]
        let _arr_copy = {};
        
        const copyObj = (obj) =>{
            const _first = document.querySelector('#first');
            let type = typeof(obj);
            // let _print = value[_key];
            // console.log(_print)
            
            if(type == 'object'){
                // _arr_copy = JSON.parse(JSON.stringify(obj));
                // _arr_copy = [...obj];
                if(Array.isArray(obj)){
                    _arr_copy = [];

                    Object.keys(obj).forEach(e => _arr_copy[e] = copyObj(obj[e]));

                    for(var i = 0; i < _arr_copy.length; i++){
                        let _key = _arr_copy[Object.keys(_arr_copy)[i]];
                        let _keyname = _key[Object.keys(_key)];

                        let _span = document.createElement('span');
                        _span.innerHTML = `We love ${_keyname}<br>`;
                        _first.appendChild(_span)
                    }
                }
            }else{
                _arr_copy = obj;
            }
            return _arr_copy
            
            console.log(_arr_copy)
        }

        copyObj(_arr)
    </script>
    <!-- 가챠이벤트 -->
    <script>
        const _prizes = [
            {
                grade : `S`,
                photo : [
                    {
                        name : `minji`,
                        src : `https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNXJobDNyYzRuMTlseGRsenBxM2kydmFscnV4aDg4MW9sdDQ4bTd6diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/AGVLIUlVtIURRMhqOg/giphy.gif`
                    },
                    {
                        name : `hani`,
                        src : `https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZXk3ZmR2NmNzZDE3Z3E0MTh3MG13OTllaWlxNG5hdDB0ZTZyaWFyciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ay5OgdGOI4df9UYEgw/giphy.gif`
                    },
                    {
                        name : `haerin`,
                        src : `https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExd2RkYWd4ZDFleG9qa3ZrcDVtc3lvdGc5NHhrNnBwbnd5OWxqNG9nZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/44FKixtOQ9HmodXKf8/giphy.gif`
                    },
                    {
                        name : `hyein`,
                        src : `https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbjh4NXE5Mm44ajA5dG1oZTJoMTBiZDAwMXk0a2QxbGlndjNka3g4MCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/tcXSEwXqkLc57KIjxI/giphy.gif`
                    },
                    {
                        name : 'daniel',
                        src : `https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExaWhwcDhkaG9veTYzNXNpOXpvd2l6YzFndjh5anNnczY4bHloM3pxaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/VtquEUCQw4rrZGCZ3w/giphy.gif`
                    }
                ],
                percentage : 5
            },
            {
                grade : `A`,
                photo : [
                    {
                        name : `grade-a`,
                        src : `https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZDBucWMxa2Npbjc5dDR3N3V1ejZxMXlwc3BnOXIyenhwaWpxMWgwMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/pO4UHglOY2vII/giphy.gif`
                    },
                    {
                        name : `grade-a`,
                        src : `https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExYjB5ZG9yMDF6OGxuYnNnbWlrZmptdmVuc3Ixc2o3N3MzamltdjAwaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3eKdC7REvgOt2/giphy.gif`
                    },
                    {
                        name : `grade-a`,
                        src : `https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExODg4NzJ4aWNibnJ3dXQ0cWtrM2s3MTFmYmU3Y3A1dGszZWZqenRnZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/L2UdIWuCRbUL6/giphy.gif`
                    },
                    {
                        name : `grade-a`,
                        src : `https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExdjVobnhyczFsZzY3eXZiaTJwNzduMWMzejE5enkzMjY1b2MzaTJzcSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/R1MYZBEos2qyI/giphy.gif`
                    },
                    {
                        name : `grade-a`,
                        src : `https://media0.giphy.com/media/nJZxhesBFKbCw/giphy.gif?cid=ecf05e47aj07finekqejt2myrdb71wf6i7dkdcsu9iwugaxx&ep=v1_gifs_related&rid=giphy.gif&ct=g`
                    },
                ],
                percentage : 15
            },
            {
                grade : `B`,
                photo : [
                    {
                        name : `grade-b`,
                        src : `https://img.freepik.com/free-photo/wet-vietnam-mountain-flow-stream-rural_1417-1357.jpg?w=1380&t=st=1689837370~exp=1689837970~hmac=6f68691678632810567bf6ee20fb073f44cd27064fcacc9183d386b3c51d02dd`
                    },
                    {
                        name : `grade-b`,
                        src : `https://img.freepik.com/free-photo/koh-nangyuan-surat-thani-thailand_1258-729.jpg?w=740&t=st=1689837416~exp=1689838016~hmac=fd1888f59e9671e8d268f99d7cd3bcd4cb4462415c3be3a0d8c1156dbe2a962f`
                    },
                    {
                        name : `grade-b`,
                        src : `https://img.freepik.com/free-photo/beautiful-tree-middle-field-covered-with-grass-with-tree-line-background_181624-29267.jpg?w=900&t=st=1689837429~exp=1689838029~hmac=6c7e033a736defa325cb82db2a26b5393b92af3468ac567135f29f59320eef48`
                    },
                    {
                        name : `grade-b`,
                        src : `https://img.freepik.com/free-photo/forest-trees-filtered-image-processed-vintage-effect_1232-2798.jpg?w=1060&t=st=1689837441~exp=1689838041~hmac=ad125d2bd1bd6aca84d5f47c7822984d7ac1c06dea87d27407504375081cb4de`
                    },
                    {
                        name : `grade-b`,
                        src : `https://img.freepik.com/free-photo/city-park-blue-sky-with-downtown-skyline-background_1127-2298.jpg?w=1380&t=st=1689837451~exp=1689838051~hmac=35169ed4fb87b05930998951d673f557120c43265e0b4222f80c161b83835482`
                    },
                    {
                        name : `grade-b`,
                        src : `https://img.freepik.com/free-photo/beautiful-view-mesmerizing-nature-traditional-styled-japanese-adelaide-himeji-gardens_181624-40920.jpg?w=740&t=st=1689837468~exp=1689838068~hmac=77a778dc5ee691d5d09f4545f40464fca8690b53be9b64b15c20f91e8349114f`
                    },
                ],
                percentage : 35
            },
            {
                grade : `C`,
                photo : [
                    {
                        name : `grade-c`,
                        src : `https://as2.ftcdn.net/v2/jpg/00/74/15/95/1000_F_74159556_67n5823V7Ei87a4g6JJnYHC0yMSo1AEy.jpg`
                    },
                    {
                        name : `grade-c`,
                        src : `https://as1.ftcdn.net/v2/jpg/03/96/11/60/1000_F_396116072_vIWsiyjs1K62BEgn601Ta9k8xLftu4Ff.jpg`
                    },
                    {
                        name : `grade-c`,
                        src : `https://as2.ftcdn.net/v2/jpg/00/41/28/31/1000_F_41283164_VwIoJkj9cnsEuCOcUOhk2NDC0A70TWXo.jpg`
                    },
                    {
                        name : `grade-c`,
                        src : `https://as1.ftcdn.net/v2/jpg/03/77/56/40/1000_F_377564091_N26SiT8j0YzDFesm8pSEAzwYWhqoNBvb.jpg`
                    },
                    {
                        name : `grade-c`,
                        src : `https://as2.ftcdn.net/v2/jpg/00/04/65/23/1000_F_4652352_C6bqQNUlk6k6KDS8GsNWqifaYz8GQ26T.jpg`
                    },
                    {
                        name : `grade-c`,
                        src : `https://as2.ftcdn.net/v2/jpg/01/36/91/57/1000_F_136915769_OJOj7wL8kyBBkFm8BiYOBc1RSwYVRz6f.jpg`
                    },
                    {
                        name : `grade-c`,
                        src : `https://as1.ftcdn.net/v2/jpg/02/83/82/76/1000_F_283827610_cvNXOdc6CqXaLJnZBHQozk45usWSR4Rt.jpg`
                    },
                ],
                percentage : 100
            }
        ]

        let _addArr = [];
        const _body = document.querySelector('.img-wrap');
        const _add = document.querySelector('#grade-up');

        const _reaulte = document.querySelector('.img-wrap img');
        const _label = document.querySelector('.label.grade');
        const _charge = document.querySelector('.coin-count em');
        const _gauge = document.querySelector('#gauge');
        const GAUGE_KEY = 70;

        let _coin = 0;
        let _gaugeCount = GAUGE_KEY;

        const pushMemver = (arr, m) =>{
            arr.push(m);
            arr.push(m);
        }
        const rouletteRunFunctionMember = () =>{
            let _member = event.target.closest('button').getAttribute('data-name');

            _addArr = JSON.parse(JSON.stringify(_prizes));

            let _gradeArr = _addArr.find(e => e.grade === 'S');
            let _pushArr = _gradeArr.photo;
            let _name = _pushArr.find(e => e.name == _member);
            let _push = _pushArr.filter(e => e.name == _member);

            if(_push.length <= 1){
                pushMemver(_pushArr, _name)

            }else if(_push.length >= 3){

            }

            rouletteRunFunction(_addArr);
        }

        const rouletteRunFunctionNormal = () =>{
            rouletteRunFunction(_prizes);
        }

        const rouletteRunFunction = (arr) =>{
            let _score =+ Math.floor(Math.random() * 101)//.toFixed(1);
            _coin++;
            _gaugeCount--;
            _charge.innerText = _coin;
            _gauge.style = '--gauge-width : ' + (100 - ((100 / GAUGE_KEY) * (GAUGE_KEY - _gaugeCount))) + '%';
            function mileageCount(e){
                if(_score > 3 && _gaugeCount == 0){
                        _gaugeCount = GAUGE_KEY;
                        _gauge.style = '--gauge-width : 100%' ;
                        _score = 0;
                    }
            }
            for(var i=0; i<=arr.length; i++){
                // if(i == 1){
                //     continue;  //작동 [0,2,3,4]
                // }
                // console.log("i: ", i);

                // if(i == 3){
                //     break; //작동 [0,2,3]
                // }

                let e = arr[i];                

                mileageCount(e);
                if(_score <= e.percentage){
                    let _count = e.photo.length;
                    let _num = Math.floor(Math.random() * _count);
                    let _grade = e.grade;
                    let _prizeName = e.photo[_num].name;
                    let _prizeImg = e.photo[_num].src;

                    _reaulte.setAttribute('src', _prizeImg);
                    _label.classList.remove(`S`, `A`, `B`, `C`);
                    _label.classList.add(_grade);
                    _label.innerHTML = _grade;
                    
                    if(e.grade == 'S'){
                        _coin = 0;
                        _charge.innerText = _coin;
                        _gaugeCount++;
                    }
                    //console.log(_num)
                    if(_score <= 3 && e.photo.length >= 7 && _num > 4){
                        _add.classList.remove('hide')
                    }else{
                        _add.classList.add('hide');
                    }
                    break;
                }

            }

        }

        const _btn_D = document.querySelector('#btn-d');
        const _btn_M = document.querySelector('#btn-m');
        const _btn_DN = document.querySelector('#btn-dn');
        _btn_D.addEventListener('click', rouletteRunFunctionNormal);
        _btn_M.addEventListener('click', rouletteRunFunctionMember);
        _btn_DN.addEventListener('click', rouletteRunFunctionMember);
    </script>
    <!-- 섹션 접기 -->
    <script>
        const foldControlsButton = ()=>{
            let _foldBox = event.target.closest('button').getAttribute('aria-controls');
            let _Box = document.querySelector(`#${_foldBox}`);

            _Box.toggleAttribute('hidden');
        }
    </script>
    <!-- 카드 이벤트 -->
    <script>
        const _frame = document.querySelector('.card-wrap');
        const _card = document.querySelector('#card');
        const _cardBox = document.querySelector('#card .img-wrap');
        const _light = document.querySelector('.light');

        let { x, y, width, height } = _frame.getBoundingClientRect();

        const mouseMove = (e)=>{
            const left = e.clientX - x;
            const top = e.clientY - y;
            const _centerX = left - width / 2;
            const _centerY = top - height / 2;
            const d = Math.sqrt(_centerX**2 + _centerY**2);

            _card.style = `--scaled-x : ${-_centerY / 100}; --scaled-y : ${_centerX / 100}; --scaled-z : ${d / 10}deg;`
            _light.style.backgroundImage = `radial-gradient(circle at ${left}px ${top}px, rgba(255,255,255,0.4) 0%, rgba(93,255,249,0.05) 70%, rgba(255,255,255,0.08587184873949583) 100%)`
            
            _cardBox.style = `box-shadow : ${-_centerX / 10}px ${-_centerY / 10}px 10px rgba(0, 0, 0, 0.15);`
            // console.log(_cardBox)
        }

        _card.addEventListener('mouseenter', ()=>{
            _card.addEventListener('mousemove', mouseMove)
        })

        _card.addEventListener('mouseleave', ()=>{
            _card.removeEventListener('mousemove', mouseMove)
            _cardBox.style.boxShadow = '';
            _card.style.transform = '';
            _light.style.backgroundImage = '';
        })
    </script>
    <!-- 옹스마켓 -->
    <script>
        let _itemAll = document.querySelectorAll("li.item");
        for(var i = 0; i < _itemAll.length; i++){
            let _btn = Number(_itemAll[i].querySelector('button').getAttribute('data-price'));
            let _label = _itemAll[i].querySelector('.label');
            _label.classList.add(`cost-${_btn}`);
            _label.innerText = _btn.toLocaleString('ko-KR') + '원';
        }
    </script>
</body>
</html>
