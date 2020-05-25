---
layout: post
title:  "OSS-TeamProject"
date:   2020-05-24
---
<!--
<title> 팀프로젝트 진행사항 정리 </title>
-->

### 팀프로젝트 진행사항 정리

<h1>프로젝트 선정</h1>
<p>
 &nbsp;&nbsp;&nbsp;&nbsp; 개인별 프로젝트 조사 결과, 게임 관련한 것들, 일기예보서비스, 채팅 관련 프로그램 등이 있었다.
 나는 파이썬으로 구성되어 있는 오픈소스를 찾던 와중, 시각적으로 표현되는 것이 흥미로워 보이는 일기예보서비스 관련 오픈소스를 선정했다.
 그리고 이슈들이 번역 관련 이슈들이 반복되어서, 이미 해결된 이슈들을 분석하여 새로운 이슈를 해결하는 것이 처음 오픈소스에 참여하기 좋아보였다. 
 그 중에서 우리는 모두가 가장 쉽게 접근할 수 있는 파이썬이 주요 코드인 것들을 추렸다. 
 그 결과 일기예보서비스, 텔레그램 채팅 API, 디스코드 뮤직봇 중에서 고민을 하였는데, 투표 결과 텔레그램과 디스코드봇이 선정되었다. 
 그 이후에 이 두 오픈소스를 조사하다가, 텔레그램 관련 오픈소스는 파일이 너무 많아 더 어려워보인다는 종합적인 이유로 최종 선정 프로젝트는 디스코드 뮤직봇으로 선정되었다.

</p>


<h1>디스코드 뮤직봇 분석</h1>
<p> 
&nbsp;&nbsp;&nbsp;&nbsp;주요 이슈<br>
- 봇이 작동하지 않거나, 디스코드 자체와 충돌하는 현상이 있음<br>
- 파이썬 3.5.x이상의 버전에서 작동 오류가 날 때가 있음<br>
&nbsp;&nbsp;&nbsp;&nbsp; 기여 방안<br>
- 디스코드 버전이 업그레이드 되었을 때 호환성을 꾸준히 유지하게 하는 것<br>
- 한글로도 사용이 가능하게끔 하는 것<br>
</p>

<h1>팀 역할분담</h1>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;우리는 크게 ‘git 저장소 관리, 번역, 소스코드 분석, 소스코드 추가’로 역할을 나누었다. 
그 중 소스코드 분석과 소스코드 추가가 git관리나 번역에 비해서 어려운 것이라고 판단하였다. 
그래서 조장인 윤형호는 어려운 부분인 소스코드 분석과 소스코드 추가를 담당하고, 나머지 조원들은 각각 git 관리나 번역 중에서 하나, 소스코드 관련 역할 중 하나씩 맡아서 총 두 개씩 역할을 맡기로 하였다. 
나는 번역엔 약해서 git 저장소 관리와 소스코드 추가를 담당하였다. 자세한 내용은 아래 정리와 같다. <br>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-js3t{border-color:inherit;font-family:"Trebuchet MS", Helvetica, sans-serif !important;;font-weight:bold;text-align:center;
  vertical-align:top}
.tg .tg-2g2i{border-color:inherit;font-family:"Trebuchet MS", Helvetica, sans-serif !important;;text-align:center;vertical-align:top
  }
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-amwm">역할</th>
    <th class="tg-amwm">담당자</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-js3t">번역</td>
    <td class="tg-2g2i">이민규, 윤재식</td>
  </tr>
  <tr>
    <td class="tg-js3t">git 저장소 관리</td>
    <td class="tg-2g2i">임유진, 이황근</td>
  </tr>
  <tr>
    <td class="tg-js3t">소스 코드 분석</td>
    <td class="tg-2g2i">윤형호, 윤재식</td>
  </tr>
  <tr>
    <td class="tg-js3t">소스 코드 추가</td>
    <td class="tg-2g2i">윤형호, 이민규, 임유진, 이황근</td>
  </tr>
</tbody>
</table>

</p>

<h1>정적 페이지 구성</h1>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;깔끔하고 가독성이 좋은 지킬 테마들이 후보로 올라왔다. 조장인 윤형호씨가 만들어주시고, 다른 조원들이 텔레그램봇과 디스코드 뮤직봇 관련 라이선스 및 소개, 선정 이유, 최근 이슈를 정리해주었고, 나도 그 중에서 부족한 부분을 조금 채우고 팀 내 개인별 역할을 포스트로 작성하였다. 
깃헙 정적페이지가 마크다운 형식이라고 해서 마크다운 형식과 html 형식으로 테이블을 작성해보았는데, 내 정적페이지에서는 오류가 없었는데, 팀 정적페이지에서는 제대로 테이블이 만들어지지 않아서 어려움이 있었다. 그나마 html형식으로 만들었을 때 오류가 덜 해서 완성했지만, 아직 부족한 부분이 많은 것 같다. 그리고 작년 수업 때 선배들이 만든 정적페이지들을 살펴보았는데, 깃헙 관리도 잘 되어 있고, 페이지 정리도 잘 되어 있었다. 나도 깃허브 다루는 방법이나, 정적페이지 다루는 방법을 더 공부해야될 것 같다고 생각했다.
</p>

<h1>팀프로젝트 기여 방안 및 개선 방향</h1>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;먼저 팀 역할 4가지 ‘번역, git 저장소 관리, 소스코드 분석, 소스코드 추가’ 중에서 나는 git 저장소 관리와 소스코드 추가를 담당하였다. Git 저장소 관리 방식을 보기 위해 먼저 지난 학기 때 선배들이 만들어 놓은 페이지들을 보았다. 
이슈를 여러 개로 분류하여 팀원들이 파악하기 쉽게 하고, 팀 repository의 소통을 위해서도 이슈를 활용하며, wiki라는 것을 이용해 팀 관련 소개와 활동 내역들을 보여주고, 프로젝트를 계획 중인 프로젝트, 진행 중인 프로젝트, 작업이 끝난 프로젝트 등으로 나누어서 정리를 깔끔하게 하고 있었다. 내가 아직 큰 소스코드 관련 기여는 잘 못하더라도, git 저장소 관리 역할을 맡음으로써 팀프로젝트에 기여하고 싶다.<br>

아직 어려움이 많다. 정적 페이지를 구성과 git 저장소 관리를 실제적으로 하는 방법들을 더 공부해서 개선해야할 것 같다. 교수님께서 피피티에 올려주신 git 실습 관련 링크와 지난 학기 때 만들어진 github과 정적페이지들도 참고할 계획이다
</p>
