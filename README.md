<style>
     @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
* {
  margin:0;
  padding:0;
}
html {
  scroll-behavior: smooth;/* 스크롤 이동을 부드럽게*/
}
body {
  font-family: "Roboto", sans-serif;
  margin: 0;
  background: #faf7fc;
  color:#222;
}
     /*main*/
.main {
  position:relative;
  margin-left:300px;
  max-width: 100%;
  padding: 30px 40px;
}
#main_profile {
  height:100vh;
  width:100%;
}
#main_profile .profile_img {
 width: 240px;
 height:240px;
 border-radius:50%;
 object-fit: fill;
 margin-top:150px;
 border:2px solid #fff;
}
#main_profile h1 {
  color:#555;
  margin-bottom: 4px;
  font-size:105px;
}
#main_profile h1 span {
  color:#35aff5;
}
#main_profile p {
  font-size: 20px;
  margin-bottom: 30px;
  color:#333;
}
#main_profile .info {
  color:#9c9595;
  font-weight:bold;
  padding-top:20px;
}
#main_profile .info span {
  color:#35aff5;
  font-size: 1.2em;
}
/*main_profile .social*/
#main_profile .social a {
  margin-right:30px;
  color:#484848;
  text-decoration:none;
  font-size: 40px;
}
/*#main_profile .aboutme*/
#main_profile .aboutme {
  display: block;
  color:#1594e3;
  padding-top: 20px;
}
#main_profile .aboutme h2 {
  font-size:30px;
  margin-top: 20px;
}
#main_profile .aboutme ul {
  margin-top: 10px;
}
#main_profile .aboutme ul li {
  font-size:20px;
  list-style:none;
  color:#333;
}
</style>
<div class="main">
     <div id="main_profile">
      <img src="images/img1.jpg" alt="사진" class="profile_img">
      <h1>SANG HYEOK <span>LEE :) </span></h1>
      <p class="info"><span>TEL. </span>010-1234-7898  |<span> E-mail. </span>web123@gmail.com
                     <span> Address. </span>10-1, Baengnyong-ro, Dong-gu, Daejeon
      </p>
      <p>스프링 프레임 워크를 활용하여 높은 수준의 개요에 대한 강력한 시놉십스를 제공한 경험이 있습니다.<br>
         기업 전략에 대한 반복적인 접근 방힉은 전체적인 가치 제안을 추진하기 위한 협업적 사고를 촉진합니다.
      </p>
