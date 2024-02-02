<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@4.1.0/fonts/remixicon.css"
      rel="stylesheet"
    />
    <style>
     * {
     margin: 0%;
     padding: 0%;
     font-family: Calibri;
     color: #ffffff;
     text-decoration: none;
     list-style-type: none;
}

::selection {
     color: rgb(228, 153, 15);
}

*::-webkit-scrollbar {
     display: none;
}

html,
body {
     background-color: #002925;
     width: 100vw;
     height: 100vh;
}

nav {
     position: fixed;
     background-color: #0D3431;
     width: 7vw;
     height: 95vh;
     display: flex;
     padding: 2vh 5px 20px 5px;
     flex-direction: column;
     align-items: center;
     justify-content: space-between;
     border-radius: 20px;
     z-index: 99;
}

.blank {
     width: 8vw;
     position: relative;
     height: 1vh;
     background-color: transparent;
     top: 50vh;
     z-index: 0;
}
.blank1 {
     width: 1vw;
     position: relative;
     height: 1vh;
     background-color: transparent;
     top: 50vh;
     z-index: 0;
}


nav img {
     width: 100%;
     height: 100%;
     object-fit: cover;
     border-radius: 50%;
}

ul {
     display: flex;
     flex-direction: column;
     gap: 10px;
     padding: 10px 0;
}

li {
     width: 45px;
     height: 45px;
     border-radius: 10px;
     display: flex;
     align-items: center;
     justify-content: center;
     font-weight: 400;
     font-size: 1.3rem;
     position: relative;
}

li a {
     border: 1px solid #fff;
     transition: all ease 0.6s;
     width: 40px;
     height: 40px;
     text-align: center;
     display: flex;
     align-items: center;
     justify-content: center;
     border-radius: 11px;
}

li:hover a {
     height: 20px;
     position: relative;
     left: 0%;
     bottom: -10%;
     border-radius: 6px;
}

li a i {
     transition: all ease 1s;
}

li:hover i {
     position: absolute;
     bottom: 50%;
     background-color: #0D3431;
     padding: 0 4px;
     animation: glowing 2s infinite;
}

@keyframes glowing {
     50% {
          text-shadow: 0 0 10px rgb(60, 255, 0);
     }
}

.tran {
     transition: all ease 0.5s;
}

.profile {
     width: 50px;
     height: 50px;
     border-radius: 50%;
     animation: glow 2s infinite;
     border: 1px solid #ffffff;
}

@keyframes glow {
     50% {
          background-color: #1e4441;
     }
}

.profile img {
     width: 100%;
     height: 100%;
     object-fit: cover;
}

.logo {
     background-color: rgb(255, 255, 255);
     display: flex;
     align-items: center;
     justify-content: center;
     width: 55px;
     height: 55px;
     border-radius: 10px;
}

.logo img {
     width: 80%;
     height: 80%;
     object-fit: cover;
}

main {
     width: 100%;
     height: auto;
     background-color: transparent;
     display: flex;
     gap: 12px;
}

.pages {
     /* background-color: yellowgreen; */
     width: 100%;
     position: relative;
     top: 0.2vh;
     height: 99.7vh;
     border-radius: 20px;
     overflow: hidden;
     display: flex;
     flex-direction: column;
     align-items: center;
     justify-content: start;
}

.pages .innernav {
     width: 99%;
     height: 10vh;
     background-color: transparent;
     border-radius: 15px;
     position: relative;
     top: 6px;
     display: flex;
     align-items: center;
     justify-content: space-between;
     flex-direction: row;
     overflow: hidden;
}

.innernav h1 {
     margin-left: 15px;
}

.cont {
     width: 52%;
     height: 90%;
     background-color: transparent;
     margin-right: 7px;
     border-radius: 10px;
     display: flex;
     align-items: center;
     gap: 15px;
}

.search {
     background-color: #ffffffbd;
     width: 25vw;
     height: 60px;
     border-radius: 10px;
     backdrop-filter: blur(60%);
     display: flex;
     flex-direction: row;
     align-items: center;
     justify-content: space-between;
}

.bell {
     width: 50px;
     height: 50px;
     background-color: #ffffff42;
     border-radius: 10px;
}

.king {
     background-color: #9365F9;
     width: 50px;
     height: 50px;
     border-radius: 10px;
}

.instunt {
     background-color: #FEE96C;
     width: 150px;
     height: 50px;
     border-radius: 10px;
}

.instunt {
     color: #1b1b1bd5;
}

.instunt i {
     color: #1b1b1bd5;

}

.icons {
     background-color: #ffffffe3;
     width: 50px;
     height: 50px;
     border-radius: 10px;
     margin-right: 5px;
}

.icons i {
     color: #000;
}

.search input {
     background-color: transparent;
     border: none;
     width: 79%;
     height: 90%;
     margin-left: 3px;
     border-radius: 10px;
     font-size: 1.1rem;
     padding-left: 10px;
     overflow: hidden;
     color: #002925;
     font-weight: 500;
}

.flex-center {
     display: flex;
     align-items: center;
     justify-content: center;
}

.page1 {
     background-color: transparent;
     width: 99%;
     height: 86vh;
     margin-top: 3vh;
     border-radius: 20px;
     overflow: hidden;
     display: flex;
     flex-direction: row;
     justify-content: space-between;
     align-items: center;
}

.contrghtsd {
     background-color: transparent;
     height: 100%;
     width: 64%;
     border-radius: 10px;
     overflow: hidden;
     display: flex;
     flex-direction: column;
     align-items: center;
     justify-content: center;
     gap: 3%;
}


.cnttp {
     width: 100%;
     height: 48%;
     background-color: transparent;
     border-radius: 10px;
     display: flex;
     align-items: center;
     justify-content: space-between;
}

.cntlft {
     width: 48%;
     height: 100%;
     backdrop-filter: blur(10px);
     background-color: #e7e7e71f;
     border-radius: 20px;
     position: relative;
     transition: all ease 0.5s;
}
.cntlft:hover ,.cntrght:hover{
     background-color: #00ceb928;
}

.cntrght {
     position: relative;
     backdrop-filter: blur(10px);
     background-color: #e7e7e72f;
     width: 48%;
     height: 100%;
     border-radius: 20px;
     transition: all ease 0.5s;
}

.cntbtm {
     width: 100%;
     height: 48%;
     background-color: #7474743b;
     backdrop-filter: blur(8px);
     border-radius: 10px;
}

.cnttp1 {
     position: relative;
     background-color: transparent;
     width: 100%;
     height: 12%;
     border-radius: 50px;
     display: flex;
     align-items: center;
     justify-content: center;
     gap: 54%;
}

.viewall {
     color: yellow;
}

.cnttp1 h2 {
     font-weight: 500;
}

.cntbtm1 {
     display: flex;
     gap: 2px;
     align-items: center;
     justify-content: start;
     background-color: transparent;
     width: 100%;
     height: 85%;
     border-radius: 10px;
     position: absolute;
     bottom: 0%;
     left: 0%;
     overflow-x: auto;
     margin-right: 10px;
     overflow-y: hidden;
}

.cnts {
     position: relative;
     background-color: rgba(117, 117, 117, 0.26);
     backdrop-filter: blur(10px);
     width: 20vw;
     height: 97%;
     margin-left: 10px;
     border-radius: 20px;
     border: 1px solid #858484;
     display: flex;
     align-items: center;
     justify-content: center;
}

.rap01 {
     position: relative;
     width: auto;
     height: 100%;
     display: flex;
     align-items: center;
     justify-content: space-between;
}

.callftsd {
     width: 34%;
     height: 100%;
     background-color: transparent;
     border-radius: 10px;
     display: flex;
     align-items: center;
     flex-direction: column;
     gap: 10px;
}
.caltp{
     width: 97%;
     height: 58%;
     background-color: #e4e4e417;
     border-radius: 20px;
     margin-top: 8px;
     padding-bottom: 15px;
}
.calbtm{
     background-color: rgba(0, 128, 0, 0.822);
     width: 95%;
     height: 35%;
     border-radius: 20px;
}
.img1{
     width: 70px;
     height: 70px;
     border-radius: 10px;
     object-fit: cover;
     margin-left: 1.4vw;
}
.cnttplft{
     width: 100%;
     height: fit-content;
     display: flex;
     align-items: center;
     flex-direction: row;
     justify-content: space-between;
     margin-top: 3.3vh;
}
.an1{
     background-color: rgba(255, 153, 0, 0.87);
     width: 55px;
     height: 55px;
     border-radius: 50%;
     display: flex;
     align-items: center;
     justify-content: center;
     margin-right: 2.3vw;
}
.an1 i{
     font-size: 1.6rem;
     font-weight: 500;
      
}
.cnttpbtmcnt{
     width: 100%;
     height: 62%;
     border-radius: 20px;
     position: absolute;
     bottom: 0%;
     left: 0%;
     overflow: hidden;
}
.cntrltv{
     position: relative;
     width: 100%;
     height: auto;
}
.cntrltv h1{
     font-family: 700;
     width: 100%;
     background-color: transparent;
     text-align: start;
     margin-left: 1vw;
     line-height: 4.7vh;
}
progress{
     margin-left: 2vw;
     width: 73%;
     height: 2vh;
}
.prgresdv{
     width: 100%;
     overflow: hidden;
     font-size: 1.2rem;
     display: flex;
     align-items: center;
     justify-content: center;
     gap: 15px;
}
.cntbtmbtm{
     width: 100%;
     height: 39%;
     position: absolute;
     bottom: 5%;
     left: 0%;
     display: flex;
     flex-direction: row;
}
.lftcnt02{
     width: 45%;
     height: 100%;
     display: flex;
     flex-direction: row;
     align-items: center;
     justify-content: start;
     gap: 2px;
     position: relative;

}
.rghtcnt02{
     width: 55%;
     height: 100%;
     display: flex;
     align-items: center;
     justify-content: center;
}
.profiles{
     width: 40px;
     height: 40px;
     border-radius: 50%;
     position: absolute;
     left: 1vw;
     overflow: hidden;
     border: 1px solid #fff;
}
.profiles img{
     width: 100%;
     height: 100%;
     object-fit: cover;
     border-radius: 50%;
}
.profiles1{
     z-index: 1;
}
.profiles2{
     z-index: 2;
     left: 3vw;
}
.profiles3{
     z-index: 3;
     left: 4.9vw;
}
.profiles4{
     z-index: 4;
     left: 6.9vw;
}
.profiles5{
     background-color: #eed54a;
     left: 9vw;
     z-index: 5;
     display: flex;
     align-items: center;
     justify-content: center;
}
.profiles h3{
     color: #141414d5;
}
.profiles:hover{
     z-index: 6;
     transition: all ease 0.3s;
     scale: 1.3;
     cursor: pointer;
}
.rghtcnt02 a{
     background-color: rgba(70, 70, 70, 0.151);
     backdrop-filter: blur(10px);
     width: 90%;
     height: 80%;
     border-radius: 15px;
     display: flex;
     align-items: center;
     justify-content: center;
     gap: 10px;
     font-size: 1.2rem;
     border: 1px solid #fff;
}
.rghtcnt02 a:hover i{
     /* font-size: 1.5rem; */
     transition: all ease 0.3s;
     scale: 1.2;
}
i{
     transition: all ease 0.6s;
     font-size: 1.3rem;
}
.mncnt{
     width: 90%;
     height: 90%;
     display: flex;
     flex-direction: column;
     align-items: center;
     justify-content: start;
}
.mnimg{
     width: 100%;
     height: 75%;
}
.mncnt img{
     object-fit: cover;
     height: 100%;
     width: 100%;
     border-radius: 10px;
}
.strcnt{
     background-color: #ffffff;
     width: fit-content;
     position: absolute;
     top: 12%;
     display: flex;
     align-items: center;
     border-radius: 0 5px 5px 0;
     padding-right: 10px;
     color: #222222e0;
     font-weight: 600;
     gap: 3px;
     padding-left: 5px;
}
.strcnt i{
     color: #3a2a00e5;
}
.lssnshrsdv{
     width: 100%;
     display: flex;
     align-items: center;
     justify-content: start;
     gap: 7px;
     padding-top: 8px;
     color: #000000b7;
}
.lssnshrsdv p{
     color: #d3d3d3ab;
     font-weight: 600;
}
.mncnt>p{
     width: 100%;
     font-weight: 600;
     padding-top: 4px;
     font-size: 1.1rem;
}
.calrapr{
     background-color: transparent;
     overflow: hidden;
     width: 100%;
     height: 100%;
     display: flex;
     align-items: center;
     justify-content: start;
     flex-direction: column;
}
.caltpdv{
     background-color: transparent;
     width: 100%;
     display: flex;
     gap: 4px;
     align-items: center;
     justify-content: center;
}
.daycaldv{
     background-color: #ffffff31;
     backdrop-filter: blur(20px);
     width: 50px;
     display: flex;
     flex-direction: column;
     justify-content: space-around;
     align-items: center;
     height: 65px;
     border-radius: 50px;
     padding-top: 5px;
     padding-bottom: 15px;
     border: 1px solid #fff;
}
.daycaldv p{
     font-size: 1.2rem;
     font-weight: 600;
     color: #e4e4e4;
}
.todaycalmddv{
     background-color: transparent;
     width: 100%;
     height: auto;
}
.todaycalmddv p{
     font-size: 1.3rem;
     padding-top: 7px;
     padding-left: 10px;
     font-weight: 600;
}
.todolstcaldv{
     background-color: transparent;
     width: 90%;
     height: auto;
     margin-top: 5px;
     border-bottom: 1px solid #fff;
     border-left: 5px solid rgba(127, 26, 221, 0.945);
}
.todolstcaldv p{
     color: #e2e2e2e0;
     font-weight: 500;
     margin-left: 2vw;
     font-size: 1.17rem;
}
.todolstcaldv h2{
     font-weight: 600;
     margin-left: 10px;
     font-size: 1.24rem;
     letter-spacing: 1px;
}
.callstrapr{
     width: 100%;
     display: flex;
     flex-direction: column;
     align-items: center;
     gap: 10px;
     background-color: transparent;
     height: auto;
     overflow-y: scroll;
}
.calhrdv{
     background-color: transparent;
     width: 100%;
     height: 1px;
     overflow: hidden;
     margin-top: 3px;
}
.todolstcaldvstrt{
     background-color: transparent;
     width: 40px;
     height: 40px;
     position: absolute;
     right: 3%;
     top: 10%;
     overflow: hidden;
}
.todolstcaldvstrt a{
     background-color: rgba(216, 216, 216, 0.192);
     width: 100%;
     height: 100%;
     display: flex;
     align-items: center;
     justify-content: center;
     font-size: 1.2rem;
     border-radius: 50%;
}
.todolstcaldv{
     background-color: transparent;
     position: relative;
}
    </style>
  </head>

  <body>
    <main>
      <nav>
        <div class="logo">
          <img
            src="./data/Images/png/creative-creator-low-resolution-logo-black-on-transparent-background.png"
          />
        </div>
        <ul>
          <li>
            <a target="_blank" href="#"><i class="tran ri-apps-2-line"></i></a>
          </li>
          <li>
            <a target="_blank" href="#"
              ><i class="tran ri-book-open-line"></i
            ></a>
          </li>
          <li>
            <a target="_blank" href="#"
              ><i class="tran ri-file-paper-line"></i
            ></a>
          </li>
          <li>
            <a target="_blank" href="#"
              ><i class="tran ri-calendar-line"></i
            ></a>
          </li>
          <li>
            <a target="_blank" href="https://abhay7111.github.io/portfolio"
              ><i class="tran ri-contacts-book-line"></i
            ></a>
          </li>
          <li>
            <a target="_blank" href="#"><i class="tran ri-message-line"></i></a>
          </li>
          <li>
            <a target="_blank" href="#"
              ><i class="tran ri-settings-2-line"></i
            ></a>
          </li>
        </ul>
        <div class="profile">
          <img src="./data/Images/gif/New-file.gif" />
        </div>
      </nav>
      <div class="blank"></div>
      <div class="pages">
        <div class="innernav">
          <h1>Hello, Johnson!!</h1>
          <div class="cont">
            <div class="search">
              <input type="text" placeholder="Search here" />
              <div class="flex-center icons">
                <i class="ri-search-line"></i>
              </div>
            </div>
            <div class="flex-center bell">
              <i class="ri-notification-3-line"></i>
            </div>
            <div class="flex-center king">
              <i class="ri-vip-crown-2-line"></i>
            </div>
            <a href="#" id="">
              <div class="flex-center instunt">
                <i class="ri-linkedin-fill"></i>Linked in
              </div>
            </a>
          </div>
        </div>
        <div class="page1">
          <div class="contrghtsd">
            <div class="cnttp">
              <div class="cntlft">
                <div class="cnttplft">
                  <img
                    class="img1"
                    src="https://cdn.pixabay.com/photo/2012/12/27/19/41/halloween-72939_640.jpg"
                  />
                  <a class="an1" href="#"
                    ><i class="ri-arrow-right-up-line"></i
                  ></a>
                </div>
                <div class="cnttpbtmcnt">
                  <div class="cntrltv">
                    <h1>How Design Make More <br />Beautiful.</h1>
                    <div class="prgresdv">
                      <progress
                        class="progress"
                        id="file"
                        value="40"
                        max="100"
                      ></progress>
                      40%
                    </div>
                  </div>
                  <div class="cntbtmbtm">
                    <div class="lftcnt02">
                      <div class="profiles profiles1">
                        <img
                          src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8cHJvZmlsZSUyMHBpY3R1cmV8ZW58MHx8MHx8fDA%3D"
                        />
                      </div>
                      <div class="profiles profiles2">
                        <img
                          src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8cHJvZmlsZSUyMHBpY3R1cmV8ZW58MHx8MHx8fDA%3D"
                        />
                      </div>
                      <div class="profiles profiles3">
                        <img
                          src="https://images.unsplash.com/photo-1544723795-3fb6469f5b39?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTV8fHByb2ZpbGUlMjBwaWN0dXJlfGVufDB8fDB8fHww"
                        />
                      </div>
                      <div class="profiles profiles4">
                        <img
                          src="https://images.unsplash.com/photo-1639747280804-dd2d6b3d88ac?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTR8fHByb2ZpbGUlMjBwaWN0dXJlfGVufDB8fDB8fHww"
                        />
                      </div>
                      <div class="profiles profiles5">
                        <h3>1K</h3>
                      </div>
                    </div>
                    <div class="rghtcnt02">
                      <a href="#"
                        ><i class="ri-book-open-line"></i> 30 Lessons</a
                      >
                    </div>
                  </div>
                </div>
              </div>
              <div class="cntrght">
                <div class="cnttplft">
                  <img
                    class="img1"
                    src="https://cdn.pixabay.com/photo/2017/04/03/15/52/for-you-2198772_640.png"
                  />
                  <a class="an1" href="#"
                    ><i class="ri-arrow-right-up-line"></i
                  ></a>
                </div>
                <div class="cnttpbtmcnt">
                  <div class="cntrltv">
                    <h1>Basic JavaScript Full<br />Developer</h1>
                    <div class="prgresdv">
                      <progress
                        class="progress"
                        id="file"
                        value="22"
                        max="100"
                      ></progress>
                      22%
                    </div>
                  </div>
                  <div class="cntbtmbtm">
                    <div class="lftcnt02">
                      <div class="profiles profiles1">
                        <img
                          src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8cHJvZmlsZSUyMHBpY3R1cmV8ZW58MHx8MHx8fDA%3D"
                        />
                      </div>
                      <div class="profiles profiles2">
                        <img
                          src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8cHJvZmlsZSUyMHBpY3R1cmV8ZW58MHx8MHx8fDA%3D"
                        />
                      </div>
                      <div class="profiles profiles3">
                        <img
                          src="https://images.unsplash.com/photo-1488426862026-3ee34a7d66df?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTh8fHByb2ZpbGUlMjBwaWN0dXJlfGVufDB8fDB8fHww"
                        />
                      </div>
                      <div class="profiles profiles4">
                        <img
                          src="https://images.unsplash.com/photo-1521252659862-eec69941b071?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjZ8fHByb2ZpbGUlMjBwaWN0dXJlfGVufDB8fDB8fHww"
                        />
                      </div>
                      <div class="profiles profiles5">
                        <h3>1K</h3>
                      </div>
                    </div>
                    <div class="rghtcnt02">
                      <a href="#"
                        ><i class="ri-book-open-line"></i> 26 Lessons</a
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="cntbtm">
              <div class="cnttp1">
                <h2>Recommended Courses</h2>
                <a class="viewall" href="#">View All</a>
              </div>
              <div class="cntbtm1">
                <div class="rap01">
                  <div class="cnts cnts1">
                    <div class="mncnt">
                      <div class="mnimg">
                        <img
                          src="https://plus.unsplash.com/premium_photo-1683121710572-7723bd2e235d?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8QXJ0aWZpY2lhbCUyMEludGVsbGlnZW5jZXxlbnwwfHwwfHx8MA%3D%3D"
                        />
                        <div class="strcnt">
                          <i class="ri-star-s-line"></i>4.8
                        </div>
                      </div>
                      <div class="lssnshrsdv">
                        <p>45 Lessons</p>
                        |
                        <p>48 Hours</p>
                      </div>
                      <p>Artificial Intelligence for begin...</p>
                    </div>
                  </div>
                  <div class="cnts cnts1">
                    <div class="mncnt">
                      <div class="mnimg">
                        <img
                          src="https://images.unsplash.com/photo-1682687220247-9f786e34d472?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHw2fHx8ZW58MHx8fHx8"
                        />
                        <div class="strcnt">
                          <i class="ri-star-s-line"></i>4.8
                        </div>
                      </div>
                      <div class="lssnshrsdv">
                        <p>45 Lessons</p>
                        |
                        <p>48 Hours</p>
                      </div>
                      <p>Artificial Intelligence for begin...</p>
                    </div>
                  </div>
                  <div class="cnts cnts1">
                    <div class="mncnt">
                      <div class="mnimg">
                        <img
                          src="https://images.unsplash.com/photo-1706730949208-c99b056eb80b?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxOXx8fGVufDB8fHx8fA%3D%3D"
                        />
                        <div class="strcnt">
                          <i class="ri-star-s-line"></i>4.8
                        </div>
                      </div>
                      <div class="lssnshrsdv">
                        <p>45 Lessons</p>
                        |
                        <p>48 Hours</p>
                      </div>
                      <p>Artificial Intelligence for begin...</p>
                    </div>
                  </div>
                  <div class="cnts cnts1">
                    <div class="mncnt">
                      <div class="mnimg">
                        <img
                          src="https://images.unsplash.com/photo-1683009426952-13567b4fa28b?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHwyMXx8fGVufDB8fHx8fA%3D%3D"
                        />
                        <div class="strcnt">
                          <i class="ri-star-s-line"></i>4.8
                        </div>
                      </div>
                      <div class="lssnshrsdv">
                        <p>45 Lessons</p>
                        |
                        <p>48 Hours</p>
                      </div>
                      <p>Artificial Intelligence for begin...</p>
                    </div>
                  </div>
                  <div class="cnts cnts1">
                    <div class="mncnt">
                      <div class="mnimg">
                        <img
                          src="https://images.unsplash.com/photo-1682687982360-3fbab65f9d50?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHw5Nnx8fGVufDB8fHx8fA%3D%3D"
                        />
                        <div class="strcnt">
                          <i class="ri-star-s-line"></i>4.8
                        </div>
                      </div>
                      <div class="lssnshrsdv">
                        <p>45 Lessons</p>
                        |
                        <p>48 Hours</p>
                      </div>
                      <p>Artificial Intelligence for begin...</p>
                    </div>
                  </div>
                  <div class="blank1"></div>
                </div>
              </div>
            </div>
          </div>
          <div class="callftsd">
            <div class="caltp">
              <div class="calrapr">
                <div class="caltpdv">
                  <div class="daycaldv">
                    <p>S</p>
                    <h2>06</h2>
                  </div>
                  <div class="daycaldv">
                    <p>M</p>
                    <h2>07</h2>
                  </div>
                  <div class="daycaldv">
                    <p>T</p>
                    <h2>08</h2>
                  </div>
                  <div class="daycaldv">
                    <p>W</p>
                    <h2>09</h2>
                  </div>
                  <div class="daycaldv">
                    <p>T</p>
                    <h2>10</h2>
                  </div>
                  <div class="daycaldv">
                    <p>F</p>
                    <h2>11</h2>
                  </div>
                  <div class="daycaldv">
                    <p>S</p>
                    <h2>12</h2>
                  </div>
                </div>
                <div class="calhrdv"><hr /></div>
                <div class="todaycalmddv">
                  <p>Today's Class</p>
                </div>
                <div class="callstrapr">
                  <div class="todolstcaldv">
                    <div class="todolstcaldvcnt">
                      <div class="timecaldv"><p>9:00AM - 10:00AM</p></div>
                      <div class="todonmcaldv">
                        <h2>UI UX Basic Learning in Figma</h2>
                      </div>
                    </div>
                    <div class="todolstcaldvstrt">
                      <a href="#"><i class="ri-play-fill"></i></a>
                    </div>
                  </div>
                  <div class="todolstcaldv">
                    <div class="timecaldv"><p>9:00AM - 10:00AM</p></div>
                    <div class="todonmcaldv">
                      <h2>UI UX Basic Learning in Figma</h2>
                    </div>
                  </div>
                  <div class="todolstcaldv">
                    <div class="timecaldv"><p>9:00AM - 10:00AM</p></div>
                    <div class="todonmcaldv">
                      <h2>UI UX Basic Learning in Figma</h2>
                    </div>
                  </div>
                  <div class="todolstcaldv">
                    <div class="timecaldv"><p>9:00AM - 10:00AM</p></div>
                    <div class="todonmcaldv">
                      <h2>UI UX Basic Learning in Figma</h2>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="calbtm"></div>
          </div>
        </div>
      </div>
    </main>
    <script type="module" src="script.js"></script>
  </body>
</html>
