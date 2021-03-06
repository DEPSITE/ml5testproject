# ml5.js 딥러닝 라이브러리를 이용해<br>손의 움직임으로 게임을 조작하는것에 대한 연구
<br>
<table>
  <h2>6팀</h2>
  <tr>
    <td>
      구분
    </td>
    <td>
      이름
    </td>
    <td>
      학과
    </td>
    <td>
      학년
    </td>
    <td>
      휴대폰
    </td>
    <td>
      담당업무
    </td>
  </tr>
  <tr>
    <td>
      팀장
    </td>
    <td>
      서인교
    </td>
    <td>
      컴퓨터공학과
    </td>
    <td>
      4
    </td>
    <td>
      010-9014-7630
    </td>
    <td>
      레퍼런스 조사 및 테스트
    </td>
  </tr>
  <tr>
    <td>
      팀원
    </td>
    <td>
      박성국
    </td>
    <td>
      컴퓨터공학과
    </td>
    <td>
      4
    </td>
    <td>
      010-2798-6852
    </td>
    <td>
      자바스크립트 코딩 및 유지보수
    </td>
  </tr>
</table>
<br>
<hr>
<br>
<h2>과제 요약</h2> 
<h3>ml5.js를 이용해 사용자의 손을 인식하고, 인식한 손을 토대로 게임을 조작하는 것을 
  구현하여<br>실제 게임과 인공지능을 엮는 방법에 대해서 연구하도록 함.</h3>
<br>
<hr>
<br>
<h2>과제 개요</h2>
<div>
  <h3>과제 배경</h3>
  <h4>
    딥러닝이란 여러 층을 가진 인공신경망을 사용하여 기계를 학습시키는 머신 러닝의 일종이며<br>
    딥러닝은 현대 인공지능 기술의 핵심이자 앞으로 더더욱 각광받게 될 기술이다.<br>
    또한 딥러닝 데이터로 영상, 사진 또는 그래픽까지 많이 활용하고 있기 때문에<br>
    딥러닝과 컴퓨터 그래픽스를 결합하여 과제를 수행하고자 한다.
  </h4>
  
</div>
<br>
<div>
  <h3>과제 필요성</h3>
  <h4>
      이번 프로젝트에서는 단순히 손의 제스쳐만을 구분해서 게임을 조작하지만<br>
      연구를 거듭한다면 조금 더 나아가서 몸짓 전체를 구분하도록 발전할 수 있을 것이라고 생각한다.<br>
      이렇게 된다면 사람의 행동을 딥러닝을 이용해서 학습하고 게임 뿐만이 아니라 현실에서도<br>
      보안과 관련된 부분이라던가, 범죄를 저지르는 사람들의 행동을 학습해서 범죄를 예방하는 등 여러곳에 사용될 수 있을것 같다.  
  </h4>
</div>
<br>
<div>
  <h3>과제 선택 동기</h3>
  <h4>
    현재에도 시중에는 사용자의 음성를 이용하여 진행하는 게임을 쉽게 찾아 볼 수 있다<br>
    그렇지만 몸짓을 이용하여 게임을 진행하는 게임은 잘 없다는 것을 확인했다.<br>
    그렇기에 움직이기도 가장 쉽고, 표현력이 뛰어난 손을 이용해서 게임에 손짓을 한번 적용해 보도록 했다.
  </h4>
</div>
<br>
<h2>과제 목표 및 내용</h2>
<br>
<div>
  <h3>목표</h3>
  <h4>
    엄지나 검지를 이용하여 원하는 방향을 짚었을 때, 그 방향을 제대로 인지하는것을 목표로 한다.<br>
    또한 손이 멈춰있지 않고 움직이더라도 해당 방향을 최대한 제대로 인지할 수 있도록 한다.
  </h4>
</div>
<br>
<div>
  <h3>내용</h3>
  <h4>
    <img width=25% src="https://user-images.githubusercontent.com/62496275/168791976-9d94dca7-6bc5-4521-8aa8-133222b31f8e.png"><br>
    기본 뼈대가 되는 게임은 오픈 소스로 업로드 되어있는 카약 게임을 이용한다<br>
    카약 게임에서 캔버스 크기를 조금 조절하고 사용자의 웹캠 화면을 받아오도록 한다<br>
    웹캠 화면에서의 손짓을 인식하여 게임의 캐릭터를 상하좌우로 이동할 수 있도록 한다.
  </h4>
</div>
<br>
<h2>예상되는 결과물</h2>
<div>
  <h3>
    프로토타입
  </h3>
  <img width=40% src="https://user-images.githubusercontent.com/62496275/168790843-e5e9b481-427f-40a1-b8b9-f8f7434b58e1.JPG">
  <h3>
    기대효과 및 활용방안
  </h3>
  <h4>
     과제에서는 손짓만을 이용하여 진행한다. 만약 연구가 순조롭게 진행된다면<br>
     조금 더 나가가서 전체 몸짓을 이용한 게임 등에도 적용할 수 있지 않을까 생각한다.
  </h4>
</div>
<br>
<h2>수행 일정</h2>
<br>
<img src="https://user-images.githubusercontent.com/62496275/168782016-19f266ba-ad85-4b32-8c3c-5e1c44e9d415.png">
<br>
<h2>참고 문헌</h2>
<br>
https://wikidocs.net/103185 - ml5.js 사용법<br>
https://codepen.io/fleemaja/pen/jOPmXyZ Kayak Game - open source<br>
http://news.bizwatch.co.kr/article/industry/2022/04/22/0033 Hand Tracking - News<br>
https://www.koreascience.or.kr/article/JAKO201919866854640.pdf Real-Time Hand Gesture Recognition Based on Deep Learnin - Paper
