<html lang="ko">
    <!--head, style, body 나중에 다시 정리하기-->
    <head>
        <meta charset="utf-8" />
        <title>Langs-R</title>
        <!--통일성을 위해 무조건 글씨는 3개 이하, color=0:f6e1fc,30:9d7dd1,100:3e64c9, linear-gradient랑 transparent 조금 더 공부한 뒤에 api 사용하지 말고 내가 원하는 포맷으로 만들기_색상 변환 너무 도른자같음_-->
        <script type="text/x-mathjax-config">

            MathJax.Hub.Config({
            
              tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}
            
            });
            
        </script>
        <script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-MML-AM_CHTML' async></script>
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Changa+One&family=Poiret+One&family=Nanum+Gothic+Coding&display=swap');
            body {
                width: 800px;
                margin: 0;
                padding: 0;
                background: rgb(248, 248, 255);
                color: rgb(63, 60, 60);
            }
            h1 {
                color:#195daf;
                font-family:'Changa One'; font-weight:bolder;
                margin: 0px 0px 10px 50px;
            }
            hr {
                align-items: center;
                width: 700px;
            
            }
            hr.h1 {color:#195daf; border:double;}
            h2 {
                text-align: center;
                font-family: 'Poiret One'; font-weight: 900;
            }
            h2 span {
                background : linear-gradient(to right, #aaaab4, #195daf);
                -webkit-background-clip: text;
                -webkit-text-fill-color: transparent;
            }
            hr.h2 {
                border: 2%;
                background : linear-gradient(to right, #aaaab4, #195daf);
                -webkit-background-clip: border-box;
                -webkit-border-before: transparent;
            }
            div {
                align-content: left;
                font-weight: bold;
                margin: 5% 0% 10% 10%;
            }
            h3 {
                font-family: 'Poiret One';
            }
            li {
                list-style-type:decimal-leading-zero;
                font-family: 'Nanum Gothic Coding';
                font-weight: 300;
            }
            .detail li {
                list-style-type: circle;
            }
        </style>
    </head>
    <body>
        <!--header-->
        <img src="https://capsule-render.vercel.app/api?type=waving&color=0:195daf,100:aaaab4&height=250&section=header&text=Langs&fontSize=80&fontAlign=20&fontAlignY=30&desc=Programing%20Language%20%3A%20%20R&descSize=20&descAlign=80&descAlignY=60&&fontColor=fff" />
        <!--contents-->
        <h1 id="Langs"><b>R</b></h1><hr class="h1"/>
        <h2><span>Steps</span></h2><hr class="h2"/>
        <div>
            <li><a href="">Introduction</a></li>
            <li>Programming in R</li>
            <li>Data Structures</li>
            <li>Analyzing Data with R</li>
            <li>Visualization</li>
        </div>
        
        <h2><span>Tip</span></h2><hr class="h2"/>
        <div>
            <h3>with colab</h3>
            <div class="detail">
                <li></li>
            </div>
        </div>

        <h2><span>LaTex</span></h2><hr class="h2"/>
        $$R + Python = Awesome$$
        <!--footer-->
        <img src="https://capsule-render.vercel.app/api?type=waving&color=0:195daf,100:aaaab4&height=250&section=footer&text=Thank%20You&fontSize=50&fontAlignY=70&fontColor=fff"/>
    </body>
</html>