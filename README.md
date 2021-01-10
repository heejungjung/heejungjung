<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
    <meta name="description" content="" />
    <meta name="author" content="" />
    <link href="https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900" rel="stylesheet" />
    <title>HuijeongJeong</title>
	<!-- Reflux Template https://templatemo.com/tm-531-reflux -->
    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet" />
	<link rel="shortcut icon" href="assets/images/icon.ico">

    <!-- Additional CSS Files -->
    <link rel="stylesheet" href="assets/css/fontawesome.css" />
    <link rel="stylesheet" href="assets/css/templatemo-style.css" />
    <link rel="stylesheet" href="assets/css/owl.css" />
    <link rel="stylesheet" href="assets/css/lightbox.css" />
    <style>
	.timeline {
	    padding: 50px 0;
	    position: relative;
	}
	.timeline-nodes {
	        padding-bottom: 25px;
	        position: relative;
	    }
	.timeline-nodes:nth-child(even) {
	    flex-direction: row-reverse;
	}
	.timeline h3, .timeline p {
	    padding: 5px 15px;
	} 
	.timeline h3{
	    background: #3c4d3e;
	}
	.timeline p, .timeline time {
	    color: #fff;
	}
	.timeline::before {
	    content: "";
	    display: block;
	    position: absolute;
	    top: 0;
	    left: 50%;
	    width: 0;
	    border-left: 2px dashed #3c4d3e;
	    height: 100%;
	    z-index: 1;
	    transform: translateX(-50%);
	}
	.timeline-content {
	    border: 1px solid #3c4d3e;
	    position: relative;
	    border-radius: 0 0 10px 10px;
	    box-shadow: 0px 3px 25px 0px rgba(10, 55, 90, 0.2)
	}
	.timeline-nodes:nth-child(odd) h3,
	.timeline-nodes:nth-child(odd) p {
	    text-align: right;
	}
	.timeline-nodes:nth-child(odd) .timeline-date {
	    text-align: left;
	}
	 
	.timeline-nodes:nth-child(even) .timeline-date {
	    text-align: right;
	}
	.timeline-nodes:nth-child(odd) .timeline-content::after {
	    content: "";
	    position: absolute;
	    top: 5%;
	    left: 100%;
	    width: 0;
	    border-left: 10px solid #3c4d3e;
	    border-top: 10px solid transparent;
	    border-bottom: 10px solid transparent;
	}
	.timeline-nodes:nth-child(even) .timeline-content::after {
	    content: "";
	    position: absolute;
	    top: 5%;
	    right: 100%;
	    width: 0;
	    border-right: 10px solid #3c4d3e;
	    border-top: 10px solid transparent;
	    border-bottom: 10px solid transparent;
	}
	.timeline-year {
	    position: relative;
	    z-index: 100;
	    text-align: center;
	}
	.timeline-year::before {
	    content: "";
	    width: 80px;
	    height: 80px;
	    border: 2px dashed #3c4d3e;
	    border-radius: 50%;
	    display: block;
	    position: absolute;
	    top: 50%;
	    left: 50%;
	    transform: translate(-50%,-50%);
	    background-color: #fff;
	    z-index: 1;
	    text-align: center;
	}
	.timeline-year h6 {
	    position: relative;
	    z-index: 100;
	    color: #3c4d3e;
	    margin:0;
	    padding:0;
	    text-align: center;
	}
	/*small device style*/
	@media (max-width: 767px) {
	    .timeline-nodes:nth-child(odd) h3,
	    .timeline-nodes:nth-child(odd) p {
	    text-align: left
	}
	.timeline-nodes:nth-child(even) {
	    flex-direction: row;
	}
	    .timeline::before {
	    content: "";
	    display: block;
	    position: absolute;
	    top: 0;
	    left: 4%;
	    width: 0;
	    border-left: 2px dashed #3c4d3e;
	    height: 100%;
	    z-index: 1;
	    transform: translateX(-50%);
	}
	.timeline-year {
	    position: absolute;
	    left: 0%;
	    top: 60px;
	}
	.timeline-nodes:nth-child(odd) .timeline-content::after {
	    content: "";
	    position: absolute;
	    top: 5%;
	    left: auto;
	    right: 100%;
	    width: 0;
	    border-left: 0;
	    border-right: 10px solid #3c4d3e;
	    border-top: 10px solid transparent;
	    border-bottom: 10px solid transparent;
	}
	.timeline-nodes:nth-child(even) .timeline-content::after {
	    content: "";
	    position: absolute;
	    top: 5%;
	    right: 100%;
	    width: 0;
	    border-right: 10px solid #3c4d3e;
	    border-top: 10px solid transparent;
	    border-bottom: 10px solid transparent;
	}
	.timeline-nodes:nth-child(even) .timeline-date {
	    text-align: left;
	}
	.timeline-year::before {
	    width: 65px;
	    height: 65px;
	}
	}
	
	/*extra small device style */
	@media (max-width: 575px) {
	    .timeline::before {
	    content: "";
	    display: block;
	    position: absolute;
	    top: 0;
	    left: 3%;
	}
	.timeline-year {
	    position: absolute;
	    left: -5%;
	    }
	.timeline-year::before {
	    width: 60px;
	    height: 60px;
	}
	}
	</style>
  </head>

  <body>
    <div id="page-wraper">
      <!-- Sidebar Menu -->
      <div class="responsive-nav">
        <i class="fa fa-bars" id="menu-toggle"></i>
        <div id="menu" class="menu">
          <i class="fa fa-times" id="menu-close"></i>
          <div class="container">
            <div class="image">
              <a href="#"><img src="assets/images/Christmas.JPG" alt="" /></a>
            </div>
            <div class="author-content">
              <h4>정희정</h4>
              😄<span>Huijeong Jeong</span>😄
            </div>
            <nav class="main-nav" role="navigation">
              <ul class="main-menu">
                <li><a href="#section1">자기 소개</a></li>
                <li><a href="#section2">언어</a></li>
                <li><a href="#section2-1">개발 기술</a></li>
                <li><a href="#section2-2">개발 도구</a></li>
                <li><a href="#section3">포트폴리오</a></li>
                <li><a href="#section4">메일</a></li>
              </ul>
            </nav>
            <div class="social-network">
              <ul class="soial-icons">
                <li>
                  <a href="https://github.com/heejungjung"><i class="fa fa-github"></i></a>
                </li>
                <li>
                  <a href="https://www.instagram.com/j.amy_jeong/"><i class="fa fa-instagram"></i></a>
                </li>
                <li>
                  <a href="https://www.linkedin.com/in/huijeong-jeong-519a0017b/"><i class="fa fa-linkedin"></i></a>
                </li>
              </ul>
            </div>
            <div class="copyright-text">
              <p>Copyright 2019 Reflux Design</p>
              <p>Icon:Pixel perfect from www.flaticon.com</p>
            </div>
          </div>
        </div>
      </div>

      <section class="section about-me" data-section="section1">
        <div class="container">
          <div class="section-heading">
            <h1>자기 소개</h1>
            <div class="line-dec"></div><br>
            <h4>안녕하세요, 저는 정희정입니다.😀</h4><br>
		    <p>👉 저는 풀스택 개발자를 목표로 하고 있습니다.</p>
			<p>👉 데이터 분석,백엔드,웹 개발 등 코딩으로 무엇인가를 만들고 결과를 도출해내는 것을 즐깁니다.</p>
			<p>👉 배움을 멈추지 않고 계속 도전해나가는 삶을 살고 싶습니다.</p>
          </div>
          
          <div class="right-image-post">
          <div class="container">
		      <div class="timeline">
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">👩‍🎓 경북대학교 통계학 전공</h3>
		            <p>👉 빅데이터 연계전공</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>2015</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2015-02 ~ 2019-08</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">👩‍🏫 입시 학원 강사</h3>
		            <p>👉 고등 입시수학 강사</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2015-02 ~ 2016-11</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">👩‍💼 뉴욕뉴욕 웨딩</h3>
		            <p>👉 조명 및 음향 관리</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>2017</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2017-01 ~ 2017-12</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">🥇 통계 분석 대회 수상</h3>
		            <p>👉 최우수상</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2017-11-22</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">👩‍💼 Geo C&I 계약직</h3>
		            <p>👉 산림 데이터 정리</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>2018</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2017-01 ~ 2017-12</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">👭 외국인 버디</h3>
		            <p>👉 교내 외국인 입학생들이 적응할 수 있도록 도와주는 활동</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2018-03 ~ 2018-06</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">🏫 통계청 재능 기부</h3>
		            <p>👉 중-고등학생들에게 통계 및 빅데이터 특별 수업 진행</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2018-03 ~ 2018-11</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">📃 사회조사분석사 2급</h3>
		            <p>👉 최종합격</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2018-08</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">📃 SAS Advanced</h3>
		            <p>👉 최종합격</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2018-08</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">📃 TOEIC Speaking</h3>
		            <p>👉 140</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>2019</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2019-06-16</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">👩‍💼 한국감정원</h3>
		            <p>👉 부동산 데이터 전산입력 및 서류 검토</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2018-11 ~ 2018-12</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">👩‍💼 한국감정원</h3>
		            <p>👉 부동산 데이터 전산입력 및 서류 검토</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2019-08 ~ 2019-09</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">👩‍💼 Grand SK</h3>
		            <p>👉 supply 소싱 및 인보이싱</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>&nbsp;&nbsp;&nbsp;&nbsp;</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2019-10 ~ 2020-04</time>
		          </div>
		        </div>
		        <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
		          <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
		            <h3 class=" text-light">📃 TOEIC</h3>
		            <p>👉 870</p>
		          </div>
		          <div class="col-2 col-sm-1 px-md-3 order-2 timeline-year text-md-center">
		            <h6>2020</h6>
		          </div>
		          <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
		            <time>2020-09-13</time>
		          </div>
		        </div>
		      </div>
			</div>
          </div>
        </div>
      </section>

      <section class="section my-services" data-section="section2">
        <div class="container">
          <div class="section-heading">
            <h2>언어</h2>
            <div class="line-dec"></div>
          </div>
          <div class="row">
            <div class="col-md-3">
              <div class="service-item">
                <div class="r-service-icon service-icon"></div>
                <h4>R</h4>
              </div>
            </div>
            <div class="col-md-3">
              <div class="service-item">
                <div class="java-service-icon service-icon"></div>
                <h4>Java</h4>
              </div>
            </div>
            <div class="col-md-3">
              <div class="service-item">
                <div class="mysql-service-icon service-icon"></div>
                <h4>MySQL</h4>
              </div>
            </div>
            <div class="col-md-3">
              <div class="service-item">
                <div class="sas-service-icon service-icon"></div>
                <h4>SAS</h4>
              </div>
            </div>
            <div class="col-md-3">
              <div class="service-item">
                <div class="py-service-icon service-icon"></div>
                <h4>Python</h4>
              </div>
            </div>
            <div class="col-md-3">
              <div class="service-item">
                <div class="js-service-icon service-icon"></div>
                <h4>Javascript</h4>
              </div>
            </div>
            <div class="col-md-3">
              <div class="service-item">
                <div class="html-service-icon service-icon"></div>
                <h4>HTML5</h4>
              </div>
            </div>
            <div class="col-md-3">
              <div class="service-item">
                <div class="css-service-icon service-icon"></div>
                <h4>CSS3</h4>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section my-services" data-section="section2-1">
        <div class="container">
          <div class="section-heading">
            <h2>개발 기술</h2>
            <div class="line-dec"></div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <div class="service-item">
                <div class="springboot-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="springsecurity-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="springsockets-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="maven-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="tomcat-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="jpa-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="thymeleaf-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="bootstrap-service-icon service-icon2"></div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section my-services" data-section="section2-2">
        <div class="container">
          <div class="section-heading">
            <h2>개발 도구</h2>
            <div class="line-dec"></div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <div class="service-item">
                <div class="github-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="sourcetree-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="eclipse-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="rstudio-service-icon service-icon2"></div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="service-item">
                <div class="visualstudio-service-icon service-icon2"></div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section my-work" data-section="section3">
        <div class="container">
          <div class="section-heading">
            <h2>포트폴리오</h2>
            <div class="line-dec"></div>
          </div>
          <div class="row">
            <div class="isotope-wrapper">
              <form class="isotope-toolbar">
                <label>
                	<input type="radio" data-type="*" checked="" name="isotope-filter"/>
                  <span>전체보기</span></label>
                <label>
                	<input type="radio" data-type="analysis" name="isotope-filter"/>
                  <span>데이터 분석</span></label>
                <label>
                	<input type="radio" data-type="project" name="isotope-filter"/>
                  <span>프로젝트</span></label>
                <label>
                	<input type="radio" data-type="contest" name="isotope-filter"/>
                  <span>공모전</span></label>
              </form>
              <div class="isotope-box">
                <div class="isotope-item" data-type="project">
                  <figure class="snip1321">
                    <img src="assets/images/ttt.JPG" alt="Talk To Talk"/>
                    <figcaption>
                      <a href="assets/images/ttt.JPG" data-lightbox="Talk To Talk" data-title="Caption">
                      <i class="fa fa-search"></i></a>
                      <h4>Talk To Talk</h4>
                      <span>직업 훈련 과정에서 작업한 Talk To Talk이라는 채팅 웹사이트 입니다.
	                  MySQL과 연결하여 DB에 회원정보 및 채팅방 정보,채팅 메시지를 저장하여 후에 데이터 분석에 이용할 수 있도록 설정하였습니다.
	                  (후에 페이스톡 및 다양한 채팅 통계 자료를 추가하여 기능을 완성시킬 예정입니다.)</span>
	                  <div class="white-button">
	                    <a href="https://github.com/heejungjung/TalkToTalk">Visit</a>
	                  </div>
                    </figcaption>
                  </figure>
                </div>
                <div class="isotope-item" data-type="analysis">
                  <figure class="snip1321">
                    <img src="assets/images/comento.jpg" alt="Comento"/>
                    <figcaption>
                      <a href="assets/images/comento.jpg" data-lightbox="Comento" data-title="Caption">
                      <i class="fa fa-search"></i></a>
                      <h4>Comento</h4>
                      <span>데이터 분석가로서의 실무를 경험하고자 온라인 직무 체험 캠프에 참가하였습니다.
	                  총 한달 간의 직무 체험 캠프를 통해서 복잡한 실무 데이터에 대한 대처 방법과 적절한 문서화 방법을 배울 수 있었습니다.
	                  또한 현직 멘토님으로부터 좋은 데이터 분석가가 되기 위한 조언을 얻어 앞으로의 방향성을 수립하는 데 좋은 경험이 되었습니다.</span>
                    </figcaption>
                  </figure>
                </div>
                <div class="isotope-item" data-type="analysis">
                  <figure class="snip1321">
                    <img src="assets/images/MathematicalBigdata.JPG" alt="MathematicalBigdata"/>
                    <figcaption>
                      <a href="assets/images/MathematicalBigdata.JPG" data-lightbox="효율적 선거운동 지역 모색" data-title="Caption">
                      <i class="fa fa-search"></i></a>
                      <h4>효율적 선거운동 지역 모색</h4>
                      <span>QGis, Gephi, Python을 이용한 network를 통해 선거운동을 위한 가장 효율적인 장소 분석 : 
                      	사이트(http://nodelink.its.go.kr/)에서 다운로드 받은 node와 link 파일을 이용,
						A 지역의 중요성을 보기 위해서는 A 지역을 제외한 지역을 지나는 사람들이 다른 지역으로 이동할 때 얼마나 A를 거쳐 가는 지를 살펴보는 아이디어를 바탕으로
						노드들 간의 최단 경로를 계산하는 Betweenness Centrality를 구하였다.</span>
                    </figcaption>
                  </figure>
                </div>
                <div class="isotope-item" data-type="contest">
                  <figure class="snip1321">
                    <img src="assets/images/drama.JPG" alt="Stat"/>
                    <figcaption>
                      <a href="assets/images/drama.JPG" data-lightbox="통계 분석 공모전" data-title="Caption">
                      <i class="fa fa-search"></i></a>
                      <h4>StatAnalysisContest</h4>
                      <span>교내 통계 분석 공모전에서 '드라마 시청률 예측'을 주제로 최우수상을 수상하였습니다.
                      사이트 DAUM에서 드라마 정보를 크롤링하여 데이터 세트를 만들어 분석하였습니다.</span>
                    </figcaption>
                  </figure>
                </div>
                <div class="isotope-item" data-type="analysis">
                  <figure class="snip1321">
                    <img src="assets/images/datamining.JPG" alt="datamining"/>
                    <figcaption>
                      <a href="assets/images/datamining.JPG" data-lightbox="유기동물 입양 예측" data-title="Caption">
                      <i class="fa fa-search"></i></a>
                      <h4>유기동물 입양 예측</h4>
                      <span>공공데이터 포털의 유기동물 데이터를 이용하여 유기동물의 품종,외향상태,질병여부 등 여러 요소가 입양여부에 어떤 영향을 미치는지 분석한 프로젝트입니다.</span>
                    </figcaption>
                  </figure>
                </div>
                <div class="isotope-item" data-type="analysis">
                  <figure class="snip1321">
                    <img src="assets/images/timeseries.JPG" alt="timeseries"/>
                    <figcaption>
                      <a href="assets/images/timeseries.JPG" data-lightbox="출생률 예측" data-title="Caption">
                      <i class="fa fa-search"></i></a>
                      <h4>출생률 예측</h4>
                      <span>시계열 분석을 통하여 대한민국의 월별 출생률을 예측하는 프로젝트입니다.</span>
                    </figcaption>
                  </figure>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section contact-me" data-section="section4">
        <div class="container">
          <div class="section-heading">
            <h2>메일</h2>
            <div class="line-dec"></div>
          </div>
          <div class="row">
            <div class="right-content">
              <div class="container">
                <form id="contact" action="mailto:junghee528@naver.com" method="post" enctype="multipart/form-data" name="EmailForm">
                  <div class="row">
                    <div class="col-md-6">
                      <fieldset>
                        <input name="name" type="text" class="form-control" id="name" placeholder="Your name..." required=""/>
                      </fieldset>
                    </div>
                    <div class="col-md-6">
                      <fieldset>
                        <input name="email" type="text" class="form-control" id="email" placeholder="Your email..." required=""/>
                      </fieldset>
                    </div>
                    <div class="col-md-12">
                      <fieldset>
                        <input name="subject" type="text" class="form-control" id="subject" placeholder="Subject..." required=""/>
                      </fieldset>
                    </div>
                    <div class="col-md-12">
                      <fieldset>
                        <textarea name="message" rows="6" class="form-control" id="message" placeholder="Your message..." required=""></textarea>
                      </fieldset>
                    </div>
                    <div class="col-md-12">
                      <fieldset>
                        <button type="submit" id="form-submit" class="button">메일 보내기</button>
                      </fieldset>
                    </div>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>

    <!-- Scripts -->
    <!-- Bootstrap core JavaScript -->
    <script src="vendor/jquery/jquery.min.js"></script>
    <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

    <script src="assets/js/isotope.min.js"></script>
    <script src="assets/js/owl-carousel.js"></script>
    <script src="assets/js/lightbox.js"></script>
    <script src="assets/js/custom.js"></script>
    <script>
      //according to loftblog tut
      $(".main-menu li:first").addClass("active");

      var showSection = function showSection(section, isAnimate) {
        var direction = section.replace(/#/, ""),
          reqSection = $(".section").filter(
            '[data-section="' + direction + '"]'
          ),
          reqSectionPos = reqSection.offset().top - 0;

        if (isAnimate) {
          $("body, html").animate(
            {
              scrollTop: reqSectionPos
            },
            800
          );
        } else {
          $("body, html").scrollTop(reqSectionPos);
        }
      };

      var checkSection = function checkSection() {
        $(".section").each(function() {
          var $this = $(this),
            topEdge = $this.offset().top - 80,
            bottomEdge = topEdge + $this.height(),
            wScroll = $(window).scrollTop();
          if (topEdge < wScroll && bottomEdge > wScroll) {
            var currentId = $this.data("section"),
              reqLink = $("a").filter("[href*=\\#" + currentId + "]");
            reqLink
              .closest("li")
              .addClass("active")
              .siblings()
              .removeClass("active");
          }
        });
      };

      $(".main-menu").on("click", "a", function(e) {
        e.preventDefault();
        showSection($(this).attr("href"), true);
      });

      $(window).scroll(function() {
        checkSection();
      });
    </script>
  </body>
</html>
