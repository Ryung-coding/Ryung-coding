👾 About me 👾
<br/><br/>
<img src="https://ryung-lab.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F66526435-28f0-4b66-b95f-d057d2702e4b%2FUntitled.png?id=bde6cf86-7cb2-4990-8e48-2323a8d73b9e&table=block&spaceId=5928c9b4-fc01-4de3-a0d5-47b0faef430f&width=2000&userId=&cache=v2" width="200" height="200" align="left" hspace="5" vspace="5">
| ㅤName 🧑‍ ㅤ| ㅤShin Han-ryung <br/><br/>
| ㅤAge 💀 ㅤㅤ| ㅤ22 (born 2002) <br/><br/>
| ㅤE-mail 📧 ㅤ| ㅤryung9514@naver.com <br/><br/>
| ㅤState 🌏ㅤㅤ|ㅤ Republic of Korea (ROK)
<br/><br/> </p>

<br/> 
👨‍🎓 Record 👨‍🎓 
<br/>
<br/>
2018.03.02 ~ 2021.03.02ㅤ:ㅤ  Graduated from Sejong Science High School 📚 
<br/> <br/> 
2021.03.02 ~ㅤㅤㅤㅤㅤㅤ: ㅤ Seoul National University of Science and Technology | Major : Mechanical System Design Engineering 🔧
<br/> <br/> 
2022.04.11 ~ㅤㅤㅤㅤㅤㅤ: ㅤ Joined Mobile Robot Research Institute (MRL) 👉 <a href="https://mrl.seoultech.ac.kr/index.do">[SEOULTECH MRL]</a>
<br/>
<br/> 
📄 My Papers 📄 
<br/>
<br/>
"Difficulty in ground ball defense in baseball games after rain" ㅤ ㅤ  ㅤ ㅤㅤ| ㅤ👉🏻  <a href="https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11168399">[paper link]</a>
<br/> <br/> 
"Hardware and Control Method for Counter-rotating Coaxial Multirotor "   ㅤ| ㅤ👉🏻 <a href="https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11168399">[paper link]</a>
<br/> <br/>
 
💻 Activity & Study 💻 
<br/>
<br/>
 🎥 My video ㅤㅤ| ㅤ👉🏻  <a href="https://www.youtube.com/channel/UCc9LB4PyAS6IN5NbVJkC0cQ">[Ryung's home]</a>
<br/> <br/> 
🤳 My account  ㅤ| ㅤ👉🏻  <a href="https://www.instagram.com/ryung_official/">[instagram]</a>
<br/> <br/> 
👨🏻‍🏫 My blog  ㅤ ㅤ | ㅤ👉🏻  <a href="https://ryung-lab.notion.site/Ryung-s-LAB-b479d7a127e441a9bb0b32c8d52f48ea">[Ryung's LAB]</a>
<br/>
<br/>
<br/>
<br/>
<a href="https://github.com/Ryung-coding/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api?username=Ryung-coding&show_icons=true&include_all_commits=true&theme=dark&hide_border=true" alt="Anurag's github stats" /></a><a href="https://github.com/Ryung-coding/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ryung-coding&layout=compact&theme=dark&hide_border=true" /></a>



<div id="map" style="width:100%;height:500px;"></div>
<script>
var mapContainer = document.getElementById('map'), // 지도를 표시할 div  
    mapOption = { 
        center: new kakao.maps.LatLng(37.631597, 127.076290), // 지도의 중심좌표
        level: 2 // 지도의 확대 레벨
    };

var map = new kakao.maps.Map(mapContainer, mapOption); // 지도를 생성합니다
 
// 마커를 표시할 위치와 title 객체 배열입니다 
var positions = [
{latlng: new kakao.maps.LatLng(37.631137, 127.075706)},
    

];

// 마커 이미지의 이미지 주소입니다
var imageSrc = "https://cdn-icons-png.flaticon.com/512/868/868876.png"; 
    
for (var i = 0; i < positions.length; i ++) 
{
    // 마커 이미지의 이미지 크기 입니다
    var imageSize = new kakao.maps.Size(15, 15); 
    // 마커 이미지를 생성합니다    
    var markerImage = new kakao.maps.MarkerImage(imageSrc, imageSize); 
    // 마커를 생성합니다
    var marker = new kakao.maps.Marker({
        map: map, // 마커를 표시할 지도
        position: positions[i].latlng, // 마커를 표시할 위치
        title : positions[i].title, // 마커의 타이틀, 마커에 마우스를 올리면 타이틀이 표시됩니다
        image : markerImage // 마커 이미지 
    });
}
    
</script>
