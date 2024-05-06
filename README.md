<html>
  <link href="20243515노주현css과제.css" type="text/css" rel="stylesheet">
<head>
  <!--자기소개 페이지 만들기-->
  <title>자기소개페이지</title>
</head>

<body>
  <!--자기소개 페이지 내용-->
  <h2><div id="a">자기 소개 페이지</div></h2>
  
  <nav><div id = "e">
   <ul>
    <li><a href="사진들/드론.jpg">취미</a></li>
    <li><a href="사진들/고민하는 사진.jpg">꿈</a></li>
    <li><a href="사진들/항공기 조종사 책.jpg">좋아하는 책</a></li>
    <li><a href="사진들/이메일 사진.jpg">이메일 주소</a></li>
    <li><a href="사진들/시간표.jpg">시간표</a></li>
  </ul>
  </div></nav>
  <hr>
  <h3><img src="사진들/노주현 증명사진.jpg" width="120", height="150"/>
  <div id = "b">안녕하세요! 저는 노주현입니다.</div></h3>
  <p><div id = "c">순천향대학교에서 컴퓨터소프트웨어공학과에서 공부하고있는 1학년 학생입니다. 
    <br>솔직히 오기 전에는 코딩을 잘 알지 못해 두려웠지만 공부하다보니 재밌어지고 <br>관심이 높아져 열심히 노력하고있습니다.</div></p>
  <br><hr>
  
  <div class="container">
    <div class="combined-div">
  <h4><div id = "f">[취미]</div></h4>
  <p>제 취미는 드론 날리기입니다. 어릴 적부터 드론을 <br>많이 조종해봤기 때문에 가끔 생각을 비우거나 심심할 때 드론 조종을 합니다.<br>초경량비행장치 지도조종자 자격증도 보유하고 있습니다. <br>기회가 온다면 진로로도 연결해보고 싶습니다.</p>
  <h4><div id ="g">[꿈]</div></h4>
  <p>제 꿈은 하고싶은 일을 하며 사는 것인데 그 하고싶은 일은 아직 찾지 못한 것 같습니다. <br>형식상 있는 꿈은 돈 많이 벌기, 행복한 가정 꾸리기 입니다.</p>
   </div>
  </div>
  
  <h4><div id = "h">[좋아하는 책]</div></h4>
  <ul>
    <li>항공기 조종사 (박지청)   (꿈이 항공기 조종사일때 정말 재밌게 읽음)</li>
    <li>축구를 하며 생각한 것들 (손흥민)   (손흥민의 엄청난 팬인 내가 손흥민의 이야기를 들은 책)</li>
    <li>미움 받을 용기1 (이치로)   (처음으로 이런 내용의 책을 재밌게 읽음)</li>
  </ul>  
  <h4><div id = "i">[이메일 주소]</div></h4>
  <a href="mailto:shwngus18@naver.com">노주현에게 이메일 보내기!</a><hr>
  <table border ="3">
    <caption><div id = "j"><노주현의 시간표></div></caption>
    <tbody>
      <tr>
        <td>시간\요일</td>
        <td>월</td>
        <td>화</td>
        <td>수</td>
        <td>목</td>
        <td>금</td>
      </tr>
      <tr>
        <td>9시</td>
        <td rowspan="3">웹프로그래밍<br>(M503)</td>
        <td rowspan="2">컴퓨터개론<br>(M503)</td>
        <td></td>
        <td rowspan="2">글쓰기<br>(U636)</td>
        <td></td>
      </tr>
      <tr>
        <td>10시</td>
        <td></td>
        <td></td>
        
      </tr>
      <tr>
        <td>11시</td>
        <td></td>
        <td rowspan="3">파이썬<br>프로그래밍<br>(M503)</td>
        <td></td>
        <td></td>
    
      </tr>
      <tr>
        <td>12시</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
     
      </tr>
      <tr>
        <td>1시</td>
        <td></td>
        <td></td>
        <td></td>
        <td rowspan="3">컴퓨터코딩과<br>문제해결<br>(6104)</td>
        
      </tr>
      <tr>
        <td>2시</td>
        <td></td>
        <td></td>
        <td rowspan="2">파이썬<br>프로그래밍<br>실습<br>(M518)</td>
        <td rowspan="3">일반수학<br>(M503)</td>
      
      </tr>
      <tr>
        <td>3시</td>
        <td rowspan="2">컴퓨터개론<br>(M503)</td>
        <td></td>
        
      </tr>
      <tr>
        <td>4시</td>
        <td></td>
        <td></td>
        <td></td>
        
      </tr>
      <tr>
        <td>5시</td>
        <td></td>
        <td>자기개발과<br>전공탐색<br>(M503)</td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
    </tbody>
  </table><hr>
  <footer>
    <p><div id = "k">제 간단한 자기소개서를 읽어주셔서 감사합니다! 방명록을 남겨주세요.</div></p>
</footer>
<form>
  <input type="text" placeholder="ex) 재밌게 잘 봤어요" name="방명록">
</textarea><br><br>
<button type="submit">완료</button>
<button type="reset">지우기</button><hr>
</form>

<h3></h3><div id = "l">링크를 복사해서 크롬으로 접속해보세요 !</div></h3><br>
<button id="copyButton">링크 복사하기</button>

<script>
document.getElementById('copyButton').addEventListener('click', function() {
  var linkToCopy = 'file:///C:/Users/solan/Desktop/20243515%20%EB%85%B8%EC%A3%BC%ED%98%84/20243515%20%EB%85%B8%EC%A3%BC%ED%98%84.html';
  
  var tempInput = document.createElement('input');
  tempInput.value = linkToCopy;
  document.body.appendChild(tempInput);
  tempInput.select();
  document.execCommand('copy');
  document.body.removeChild(tempInput);
  
  alert('링크가 복사되었습니다: ' + linkToCopy);
});
</script>

</body>
</html>
