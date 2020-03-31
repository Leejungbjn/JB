# study



1. 

```html
<!DOCTYPE html>
<!-- a_basic_mpbo.html -->
<html lang="ko-KR">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	content="IE=edge">
	<!--[if IE]>
	<script src="./ie/html5shiv/dist/html5shiv.min.js"></script>
	<![endif]-->
	<title>MPBO 이해하기</title>
	<!-- style -->
	<style> html, body{width:100% height:100%;}
		html,body,
		h1,h2,h3,h4,h5,h6,
		p,pre,div,img,ul,ol,li,dl,dt,dd{margin:0; padding:0; border:0; outline:0;}

		ul,ol,li{list-style:none;}

		/* design.css */
	</style>
</head>
<body>
	<!-- layout -->

	<!-- script -->
	<script></script>
</body>
</html>
		
```



## 3/10

**HTML**

----

**sublime**(개발자에디터)

Tool - 패키지 검색해서 설치한다 (packagecontrol.io 패키지 사이트)

IME, package Control, SideBarenhancements

list 보기 - package control list -

**[Setting]**

win+PB >> 고급시스템설정 >> 환경변수 >> 시스템변수 >> Path (편집) >> 경로 추가

[주소창실행 git bash 도동일]

subl .` - 서블실행 

`start .` - 탐색기





**웹서버 환경 설정하기**(browser-sync install)

nodejs.org 설치 >> gitbash run >> `node --version` (버전확인) >> `npm install --global browser-sync` >>>`browser-sync --version`(버전확인) >>`npm i(install) -g(--global) browser-sync`	>> 
 http://browsersync.io *에서명령어확인* >>`browser-sync start --sever`

**Design**

---

CMYK - 인쇄용 , RGB - 웹/영상용

일러스트 xidoweb.com 교육자료

## 3/11

**html**

---

entity code - 웹에 표시되는 기호

ul의 하위는 li

ol의 하위는 li

img , a href 는 무조건 div가 묶어줘야된다.

div 박스 div 고무줄



## 3/12

HTML

---

section 과 article 은 경계가 모호하다. 

class 로 아이디를 나누어서 스타일을 준다. 스페이스는 하위 에 다 적용된다는 뜻이며



css에서 @로 시작하는 명령어는 ; 붙인다

- reset css: 브라우저간  표시되는 기본 값을 초기화시켜주는 것

https://meyerweb.com/eric/tools/css/reset/  meyer <- 유명코더

UI.DAUM.NET 다음 내부 코더들을 위한 페이지



**그래픽**

---

웹스타일 사이트

- gdweb.co.kr
- cssawards.net 
- csswinner.com

참고사이트

- https://theoutpost.ru/
  oneplus.com
  apple.kr

아이콘사이트

- flaticon.com



*WEB - 웹접근성*

COLOR : 색약/색맹/난시
명도 : 글씨색, 배경[4.5:1 OR 3:1(14pt bold || 18pt)]
			

프로그램 - colour contrast analyser(https://developer.paciellogroup.com/resources/contrastanalyser/)
dmg파일 -mac 용 exe,zip,msi - 윈도우용,  yml,zip,tar.gz - 리눅스용



웹접근성 연구소](https://www.wah.or.kr:444/)

## 3/13

----

1. []layout 1~2
2. []pen tool(for illustrator)
3. []pathfinder, align...

그래픽은 pt12와 12px이 같다 
하지만 웹에서는 16px이 12pt이다. (web단위 - px, % , em, rem, vw, vh, pc ..등등)

16px = 1em

```html
float:left                  //띄워서 채워넣기
float:right					//''
clear:both					//높이를 유지하는 막
display:inline
display:block
display:none
```

```html
margin:10px 20px; // 상하 10픽셀 좌우 20픽셀
margin:10px; 		//상하좌우 10픽셀
margin:10px 20px 30px // 상 10 좌우 20 하 30
margin:10px 20px 30px 40px / 상 10,우 20,하 30, 좌 40
```

1상 2우 3하 4좌 >>> 1개값은 1개로 4개값
									2개값은 2개로 4개
									3개값은 나머지하나를 되돌려서

자손선택자 
#box #header ul li

자식선택자 
#header > h1

## 3/16
---

1. 요소와 class중 class우선 (의미없는이름x)
2. class와 ID중 class우선
3. 부모's 요소에서 부터 우선 (4단계이상x)
4. 인라인요소가우선
5. !imporfont 무조건 우선 -->생각하고 픽



**그래픽**

---

path 파인더 

ctrl +6 최근사용기능

same - fill color 같은 색 선택

ctrl + 7 클리핑 마스크 보이는 부분만 나타나게하는것

## 3/17

**html**

-------

google > html kldp 검색

css - position 은 철저히 계산하고 사용해야한다. 잘못쓰면 모든게 틀어진다.

google > css pie



## 3/18

---

minify, sassbeautify (subl) - 파일 깔금하게 정리하는 확장프로그램(install package)



## 3/23

---

background-color: RGBA(255,255,255,0.7);  ///- 배경이반투명으로 변한다
``							  : HSBA(0,50%,50%,0.5);	 ///
---A(alpha) ///A가 투명도를 결정한다.



## 3/24

---

1. html/css 레이아웃을 작업하기 위한 GRID세팅 (960px~1920px)
2. 사이트구성시 html로 어떤 순서로 구성할지 (반응형) 염두하고 순서를 정한다.

## 3/25

---

1. css layout 기능
   - 메뉴기능
   - sidebanner기능
2.  

** 웹디자인기능사 - photoshop , Illustrator, Brakets, Internet Explorer, Chrome

"#" // 임시링크라는 의미

과제
resume infographic 검색 샘플보고 스케치
-컬러선정
-서체선정(google.com/fonts, 눈누)
-사진자료(증명사진)
-경력사항 최근을 위로 배열
-주소 실제존제하는것
-2페이지짜리로
_가로로할지 세로로할지 



## 3/26

---

1. photoshop - 웹 이미지 분리하기
   - 영역구분, 레이어
   - 스마트 오브젝트
   - 가이드, 이미지 내보내기
2. coding:

assistor ps 프로그램다운



## 3/31

----

코딩기준

320px(280px)
~639px
640~1024
1025~1440
1441~  // 코딩양이적다 400~500크기값을 고려 하여 디자인이 좀 단조롭다. 약 디자인파일이 6개

~480px
481~768
768~1024
1024~1366
1361~1559
1600~ // 코딩의 양 많다. 작은 디바이스환경 (200~300)이기에 디테일이 높은 디자인이 가능 약 디자인파일이 8개

DESIGN 기준

320px   
640px   
1024px  
1440px  
1920px  






# QnA

1. jQuery 는 안배워도된다던데..?  - 아직 50%가량 사용중이기때문에 그리고 새로운 프로그램들의 수준에 접근하기위한 단계로 배워두면좋다
2. 소개된 프로그램들은 전부다 섭렵해야하는 건가?



browser-sync start --server --watch --files "jisan_web.html"

chromevox classic extension ( 접근성 음성확인)

```html
<span aria-hidden="true"> // 묵음처리태그
```



# 사이트

git-scm.com - pdf 받아서보기

----

gitmind.com, 오븐(oveapp.io) : 마인드맵사이트

---

마크다운 typora.io

----

cli= terminal =shell(리눅스)

----

nodejs.org/ko

lorem image - 더미이미지

----

웹표전 /웹전근성

http://ui.daum.net

http://nuli.navercorp.com

관련프로그램 contrastratio/snook.ca

프로그램/포토샵 플러그인 가이드라인(guideguide.me)

----

https://www.sublimetext.com/

http://brackets.io/

-----

http://brwosersync.io --  명령어 모음

http://xidoweb.com --- 교육자료

-----

https://htmlreference.io/  // css 레퍼런스도있음
https://www.w3schools.com/ 	// 로우레벨 권유하진 않음 (파악인지용도로만)
https://developer.mozilla.org/ko/  	//추천 [exam -> search ''mdn float'']

----

gdweb.co.kr
rwdb.kr      // 웹표본
***추가추천***
-pinterest, dribbble, beance, notopolio

---

emmet.io 서블 단축키 



#### Basic Setting

git setting 

---

node.js

버전확인:

``` 
$ node -v && npm -v
```

[browser-sync 설치] (http://browsersync.io)

``` 
$ npm i -g browser 
$ browser-sync --version
```

edit

---

1. 컴퓨터 시스템에 경로 지정하기

2. 팩키지컨트롤 설치
   *경로지정하는방법*

   win + pause > `고급시스템설정` >`환경변수`>**`시스템변수`**>**path**찾아 편집클릭>찾아보기'sublime text 3' 설치된 경로 선택(c://program files/sublime text 3)

3. 실제 사용 경로에서 git bash 실행 (`subl .` )

 editer setting

---

1. package controls 설치
   메뉴>tools>command palette(`ctrl shift p`)>**instal package controls**설치 
   remove package : 설치된 패키지를 제거할때
   disable package: 설치된 패키지를 사용중지할때
   enable package:사용중지된 팩키지를 다시 사용할때
2. 추가 필요앱 설치시
   `ctrl shift p` > install package 진입> 찾아설치

package 주사용목록

---

1. convert to utf-8
2. IMEsupport(mac 은 설치안함)
3. sidebarEnhancerment
4. Theme-soda(추천)
5. fileIcon
6. **INcrement selection** (ctrl alt i)
7. **alignment**(ctrl alt a)
8. **emmet**
9. **emmet css**
10. **outline**
11. **print to html**

subl

---

-setting-
```{
	"color_scheme": "Packages/Colorsublime - Themes/cache/Colorsublime-Themes-master/themes/candy-crush.tmTheme",
	"font_size": 12,
	"ignored_packages":
	[
		"Vintage"
	],
	"theme": "Soda Dark 3.sublime-theme",
	"tab_size": 2,
	"translate_tabs_to_spaces": true,
	"word_wrap": true
}
```

