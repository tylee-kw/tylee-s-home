<!DOCTYPE html>
<html lang="en">
  <head>
    <!--글씨 안깨지게-->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>LeeTaeYeon intro</title>
    <!--링크에 아이콘 걸기-->
    <link rel="icon" type="image/jpg" href="imgs/realme.jpg" />
    <link rel="stylesheet" href="style.css" />
  </head>

  
  <body id="home">
    <header>
      <a href="인터렉티브_기말_이태연.html" class="logo">TaeYeon introduction</a>
      <nav>
        <ul>
          <li><a href="#home">Home🏠</a></li> <!-- 누르면 Home으로 돌아오기 -->
          <li><a href="https://github.com/KcNewbee/KcNewbee">GitHub💻</a></li> <!-- 누르면 github로 이동 링크 -->
          <li><a href="https://blog.naver.com/dlxodus890" target="_blank">->Blog</a></li> <!--블로그 링크 걸기, 새창에서 열기-->
        </ul>
      </nav>
    </header>

    <section class="home">
      <div class="home__text eng">
        <!--div는 줄바뀜 되지만 span은 줄바꿈 안됨-->
        <!-- 의미 강조 strong 태그 사용 -->
        <p>
          hello! my name is <strong>TaeYeon Lee.</strong>
        </p>
        <p>
          I am <strong>21 years</strong> old.
        </p>
        <p>
            I am studying at Kwangwoon University in<a href="#about__major"><span>'Information Convergence'</span></a>.
          </p>
        <p> 
          I love Playing <a href="#about__tennis"><span>tennis</span></a> and
          Playing <a href="#about__game"><span>game</span></a>!
        </p>
        <p>
            Thank you to <a href="#about__everyone"><span>everyone</span> around me.😊
        </p>
        <p>
            <em>Now I'm getting to know what I want to do :)</em>
        </p>
      </div>
      <img class="home__picture" src="./imgs/skdisk.jpg" alt="이태연 얼굴 사진" /> <!--alt넣어주기-->
      <div class="home__text kor">
        <p>
          안녕하세요! 저는 <strong>이태연</strong></a
          >입니다.
        </p>
        <p>
          저는 올해로 <strong>21살</strong>이에요.
        </p>
        <p>
          저는 광운대학교<a href="#about__major"><span>'정보융합학부'</span></a
          >에 재학중입니다.
        </p>
        <p>
          <a href="#about__tennis"><span>테니스</span></a
          >치는 것과 <a href="#about__game"><span>게임</span></a
          >하는 것을 좋아해요!
        </p>
        <p>
            제 주변에 있는 <a href="#about__everyone"><span>모든 이들</span></span>에게 감사해요😊
        </p>
        <p>
          <em>현재는 내가 하고 싶은 것이 무엇인지 알아가고 있습니다 :)</em>
        </p>
      </div>
    </section>
    <section class="about">
        <p><h1>Information Convergence</h1></p>
        <div id="about__major" class="about__major">
            <img src="./imgs/kwuni_ic.png" alt="광운대학교 로고 사진" style="width: 25vw; min-width: 140px;"/>
            <img src="./imgs/ic_class.jpg" alt="광운대학교 정보융합학부 이수 과목 커리큘럼 이미지" style="width: 25vw; min-width: 140px;"/>
            <img src="./imgs/AImath.jpg" alt="AI수학 강의 중 필기한 내용들 사진" style="width: 25vw; min-width: 140px;"/>
        </div>

        <p><h1>Tennis</h1></p>
        <div id="about__tennis" class="about__tennis">
            <img src="./imgs/tennis01.jpg" alt="테니스부 친구와 같이 찍은 사진" />
            <img src="./imgs/tennis02.jpg" alt="이태연이 백핸드 스토로크 구사하려고 준비하고 있는 사진" />
            <img src="./imgs/tennis03.jpg" alt="테니스 코트에서 라켓을 손에 들고 라켓만 찍은 사진" />
        </div>

        <p><h1>Game</h1></p>
        <div id="about__game" class="about__game">
            <img src="./imgs/lol02.gif" alt="LoL게임에서 탑 제이스로 타워 끼고 미니언을 못 먹는 움짤" />
            <img src="./imgs/lol03.gif" alt="LoL게임에서 사미라로 모데카이저 1대1 솔킬을 따는 움짤" />
        </div>

        <p><h1>precious people</h1></p>
        <div id="about__everyone" class="about__everyone">
            <img src="./imgs/myfam.jpg" alt="가족들과 함께 제주도에서 찍은 단체 사진" />
            <img src="./imgs/mansik03.jpg" alt="친구들과 롯데월드에서 전망이 다 보이게 찍은 단체 사진" />
            <img src="./imgs/twopic.jpg" alt="재훈이라는 친구와 둘이서 사진관에서 찍은 사진" />
            <img src="./imgs/concert01.jpg" alt="천성윤이라는 친구와 둘이 콘서트 놀러가서 찍은 사진" />
        </div>

        <p><h1>등장인물 정보</h1></p>
        <div id="about__ttable" class="about__ttable">
            <table>
                <caption>*사진에 나오는 인물 설명*</caption>
                <thead>
                    <tr align="center">
                        <th scope="col" width="150">사진명</th>
                        <th scope="col" width="400">등장인물 이름</th>
                        <th scope="col" width="150">장소</th>
                    </tr>
                </thead>
                <tbody>
                    <tr align="center">
                       <td>Tennis-Picture 01</td>
                       <td>백근형</td>
                       <td>서울테니스클럽</td>
                    </tr>
                    <tr align="center">
                       <td>Tennis-Picture 02</td>
                       <td>이태연</td>
                       <td>서울테니스클럽</td>
                    </tr>
                    <tr align="center">
                        <td>Game 01</td>
                        <td>Player: 이태연</td>
                        <td>.</td>
                    </tr>
                    <tr align="center">
                        <td>Game 02</td>
                        <td>Player: 박재훈</td>
                        <td>.</td>
                    </tr>
                    <tr align="center">
                       <td>Precious People 01</td>
                       <td>아버지, 어머니, 누나, 이태연</td>
                       <td>제주도</td>
                    </tr>
                    <tr align="center">
                        <td>Precious People 02</td>
                        <td>박재훈, 문예창, 김도우, 김기오, 이태연</td>
                        <td>롯데월드</td>
                     </tr>
                     <tr align="center">
                        <td>Precious People 01</td>
                        <td>천성윤, 이태연</td>
                        <td>난지한강공원</td>
                     </tr>
                </tbody>
            </table>
        </div>
    </section>
    <footer>
      <ul>
        <li><p>@ 인터렉티브 미디어 개론 기말 과제_2021204058_이태연</p></li>
        <!-- 링크걸 때 _top으로 창 새로 열기 -->
        <li> <!-- 연락처 의미 표기 adress 사용 -->
          <a href="mailto:dlxodus890@gmail.com" target="_top"
            ><adress>Mail : dlxodus890@gmail.com</adress></a>
        </li>
        <li> 
            <a href="https://www.instagram.com/elinyeon715/" target="_top">
                <adress>instagram : elinyeon715</adress></a>
        </li>
      </ul>
      <!-- form 필수 -->
    </br>
      <ul>
        <li>
            <form action="____" method="post">    <!--페이지 평가 제출 받는 곳 주소 적어넣기-->
                <p>Estimate page
                    <input type="radio" name= "estimate" value="Good" checked="checked" />Good
                    <input type="radio" name= "estimate" value="Soso" /> Soso
                    <input type="radio" name= "estimate" value="Bad" /> Bad
                    <input type="submit" value="submit"/>
                </p>
            </form>
        </li>
      </ul>
    </footer>
  </body>
</html>
