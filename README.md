# 손 모션 인식 기기 제어

<strong>카메라를 통해 여러 가지 손모양을 인식하여 다양한 사물들을 손동작으로 제어하는 프로젝트입니다!</strong>

<br>

## 프로젝트 목표
<P>
카메라를 이용한 비전 기반 기술로서 파이썬과 미디어 파이프로 이루어진 머신러닝을 활용하여 다양한 손 모양을 카메라에 비춰 데이터를 학습을 시키고 학습된 손 모양의 데이터를 저장합니다. 학습하여 저장된 데이터를 가지고 손 모양을 인식하여 인식한 데이터 아두이노 키트로 전송합니다. 데이터를 받은 아두이노 키트는 저장된 값에 따라 결과를 출력하여 아두이노 키트를 작동시킵니다. 실제로 LED 타워, 스피커, 전광판을 활용하였고 더 나아가 활용하여 컴퓨터 화면을 제어하거나 각종 생활용품 등을 제어할 수 있습니다.

<br>
<br>
<br>

## 💻이런 기술들을 사용했어요!
<P>
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/mediapipe-0097A7?style=for-the-badge&logo=mediapipe&logoColor=white">
  <img src="https://img.shields.io/badge/tensorflow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/opencv-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
  <img src="https://img.shields.io/badge/arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=GitHub&logoColor=white">
</P>

<br>
<br>

## 구성은 이렇습니다!
<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/6434b898-2801-4e22-b7e4-b26a5ab20c1a" alt="사진1" width="400" height="250">
      <div align="center">전광판, LED 타워 OFF</div>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/4a5b1e28-f869-4bba-86e5-e8c7454ea069" alt="사진2" width="400" height="250">
      <div align="center">전광판 OFF, LED 타워 ON</div>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/dc9efca5-8ffc-4cc6-8b27-5c6511c479a1" alt="사진3" width="400" height="250">
      <div align="center">전광판 THREE, LED 타워 ON</div>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/95feb979-fa3b-4cda-9942-07bfcfee6ca2" alt="사진4" width="400" height="250">
      <div align="center">전광판 FIVE, LED 타워 OFF</div>
    </td>
  </tr>
    <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/b73c2ce6-041a-421d-9db7-35fd5c9e7ed0" alt="사진3" width="400" height="250">
      <div align="center">소리 OFF</div>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/dc04bdc7-46e7-4e0d-8083-58607b971ed0" alt="사진4" width="400" height="250">
      <div align="center">소리 ON</div>
    </td>
  </tr>
</table>

<br>

<div>
  <h4>인공지능에 학습시킨 아두이노 키트를 제어하기 위한 손모양</h4>
  <img src="https://github.com/user-attachments/assets/f62a1ade-4929-4e05-8839-b4a9e2ceecc5" width="800"/>
</div>


<br>
<br>

## 수상내역
- 경진대회(교내)
    - 11월에 개최한 교내 2202 GEM 페스티벌에 총 33개의 학과들이 참여하였고 개발한 프로젝트가 LINC3.0 & 전문대학 혁신지원 사업분야에 대표작으로 선정되어 전시하게 되었습니다.
LINC3.0 & 전문대학 혁신지원 사업분야 심사위원에게 프로젝트에 대해 소프트웨어가 필요한 이유, 개발한 목적, 산업성, 개발한 소프트웨어로 인한 앞으로의 긍정적 효과 등을 설명과 시연을 통해 심사를 받았습니다.
그 결과, 33개의 학과들의 LINC3.0 & 전문대학 혁신지원 사업분야에서 2등을 하였고 상금 500,000원을 수여받았습니다.
<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/ac491145-1a6c-45a7-9c15-b52e84920b14" alt="사진1" width="400" height="250">
      <div align="center">전광판, LED 타워 OFF</div>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/3d510736-f4a6-42c3-8719-5ec998e5c396" alt="사진2" width="400" height="250">
      <div align="center">전광판 OFF, LED 타워 ON</div>
    </td>
  </tr>
</table>

<br>
<br>

- 경진대회(교외)
   - 11월에 영남이공대학교에서 개최한 2022 디지텍 캡스톤 디자인 대회에 참여한 총 55개 팀 중 한 팀으로 참여하였습니다. 
55개 팀은 10개의 대학에서 참여하였고, 연성대학교를 비롯해 경남정보대, 동양미래대, 동의과학대, 대림대, 아주자동차대학, 울산과학대, 영남이공대학교, 인하공업전문대학, 조선이공대 등 10개교가 참여하였습니다.
심사위원은 기술신용보증기금, 대한항공, 삼성전기, 앰코테크놀로지코리아, 에스더디자인, 한국토요타자동차, 현대중공업, 효성중공업, 휴넷, LG이노텍 등의 인사부장이 심사를 맡게 되었고, 전시한 소프트웨어를 심사위원들에게 발표하여 심사를 받고 시상을 진행하였습니다.
그 결과 시상식에서 금상과 상금 500,000원을 수여받았습니다.
<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/5488c85c-fb8c-4685-b46c-0e4dad3a5a8e" alt="사진1" width="400" height="250">
      <div align="center">전광판, LED 타워 OFF</div>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/72541a18-1310-4570-9352-28ccbc7577a2" alt="사진2" width="400" height="250">
      <div align="center">전광판 OFF, LED 타워 ON</div>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/77749817-204b-43c6-b200-bb1db9300724" alt="사진2" width="400" height="250">
      <div align="center">전광판 OFF, LED 타워 ON</div>
    </td>
  </tr>
</table>


<br>

## ✅ Commit Message
- `[Add] 🌟 소스코드가 담긴 파일을 새로 추가합니다.`
- `[Update] ✨ README 파일을 수정하고 업데이트합니다.`
- `[Update] 🔥 기존 소스코드의 내용을 업데이트합니다.`
- `[Delete] 💥 필요없는 파일을 저장소에서 제거합니다.`
- `[Merge] 🌀 개인 브랜치를 공용 브랜치로 병합합니다.`
- `[Fix] 🔧 소스코드에서 발생한 버그를 수정합니다.`
- `[Chore] 🧹 빌드 업무 또는 패키지 매니저를 수정합니다.`
- `[Refact] ♻ 코드를 리팩토링합니다.`
- `[Release] 🎁 새로운 버전을 출시합니다.`
