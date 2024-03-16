
<h1>Project 개요</h1>

<h3> 💡 아이디어 </h3>

* OECD 국가 중 자살률 1위 대한민국
* 투신자살 시도자는 한번 실패시 다시 자살시도를 할 확률 📉 (출처:한국보건사회연구원)
* 다리 투신 자살 추정자를 AI가 포착해서 뛰어내리기 전에 조치
* YOLOv8로 사람과 난간을 감지하여 알고리즘을 통해 사람과 난간 사이의 거리를 계산
* 사람이 난간에 일정수준 이상 다가갈 경우 그 사람을 확대해 빠른 조치


  
<h3> 👩‍💻 역할 </h3>

* 총 인원 5명 중 조장
* 난간과 사람의 polygon 데이터셋 수집 및 어노테이션
* 전처리 및 데이터 증강
* YOLOv8 Segmentation 학습
* YOLOv8 Detection 학습
* 퍼블리싱 및 프론트 앤드 개발
* PPT 제작 및 발표


 
<h3>📌 사용 데이터셋 </h3>  
<img src="https://github.com/Aribabo/CAIROSS/assets/137020870/d26283c3-9d19-47c5-8b48-36cdf8923014" width="700">
<img src="https://github.com/Aribabo/CAIROSS/assets/137020870/05e82fcd-3e0a-4b75-86ce-fbbe3d8f1d62" width="700" >


<h3>✨ 매커니즘 </h3>

1. CCTV 화면 송출
2. YOLOv8-segmentation을 통해 사람과 난간 감지
3. 난간의 정확한 형태와 사람의 바운딩 박스 사이의 거리 계산
4. 사용자에게 전체 CCTV 화면과 위험한 행동을 하는 사람 확대 화면 노출


<h3>💻 서비스 화면</h3>
<p>
  <img src="https://github.com/Aribabo/CAIROSS/assets/137020870/d929fa11-fed8-4901-8984-ab7853a7edaf" width="700">
  <img src="https://github.com/Aribabo/CAIROSS/assets/137020870/92ea4966-e7d9-4721-86c3-a5ed9487abca" width="700">

</p>
<h3> 🛠️ 개발환경 및 툴 </h3>
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white"/>&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white"/>&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/JavaScript-gray?style=flat&logo=JavaScript&logoColor=F7DF1E"/>&nbsp;&nbsp;
</p>

<p>
  
  <img src="https://img.shields.io/badge/Google Colab-F9AB00?style=flat-square&logo=Google Colab&logoColor=white"/>&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/pyCharm-000000?style=flat&logo=pycharm&logoColor=white"/>&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/VScode-007ACC?style=flat&logo=visualstudiocode&logoColor=white"/>&nbsp;&nbsp;
  
</p>

