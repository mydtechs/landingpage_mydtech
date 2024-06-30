<template>
  <header id="heroSection" class="header main" style="padding-top: 10px; color: white">
        <nav class="navbar navbar-expand-lg">
            <div class="container-fluid" style="display:flex; justify-content: center">
                <img src='../assets/MYD Technology Logo.png' alt="MYD Technology.">
                <button class="navbar-toggler navButton" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0 navBarOptions">
                        <li class="nav-item headerNav">
                            <a class="nav-link" href="#">Home</a>
                        </li>
                        <li class="nav-item headerNav">
                            <a class="nav-link" onclick='navigate_to("aboutUs")' href="#">About Us</a>
                        </li>
                        <li class="nav-item headerNav">
                            <a class="nav-link" href="#" onclick="navigate_to('contactUs')">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <div class="row" style="margin: 100px -12px 150px;">
            <div class="col-4">
                <h1 class="heading">
                    Your Solution for Technology Success
                </h1>
                <!-- <h1 class="heading" style="color: blue">
                    TECHNOLOGIES WITH A CREATIVE
                </h1>
                <h1 class="heading">
                    APPROACH
                </h1> -->
                <p class="subHeading">	
                    Unlock your digital potential with expert guidance and support.
                </p>
                <p class="subHeading">	
                    <a class="btn btn-primary ms-3 letsTalkBtn" href="#" style="background-color: #4E2A84; border-radius: 25px;" onclick="navigate_to('contactUs')">Contact Us</a>
                    <a class="btn btn-primary ms-3 letsTalkBtn" href="#" style="background-color: transparent; border-radius: 25px; border-color: #4E2A84" onclick="navigate_to('contactUs')">Learn More</a>
                </p>
            </div>
        </div>
    </header>

    <!-- Content Section -->
    <div id="topRated" class="main">
        <div class="col-md-12" style="margin: 0;  display: grid; justify-items: center">
            <div class="topRatedTextsContainer">
                <h1 class="topRatedTextBold" style="color: #4E2A84;">
                    What We Do
                </h1>
                <p class="topRatedText">	
                    Problems trying to resolve the conflict between the two major realms of Classical physics: Newtonian mechanics 
                </p>
            </div>
        </div>

        <div class="row topRatedCardContainer">
            <div class="col-1"></div>
            <div class="col-10">
                <div class="row" style="display: flex; justify-content: center">
                    <div class="col-3 whatWeDoCards" style="background-color: white; box-shadow: 1px 4px 10px grey;">
                        <img class="navVectors" src='../assets/training.png' alt="Vector">
                        <p>Technology Training Session</p>
                    </div>
                    <div class="col-3 whatWeDoCards" style="background-color: #4E2A84; box-shadow: 1px 4px 10px grey; color: white; margin: 0 35px">
                        <img class="navVectors" src='../assets/workshop.png' alt="Vector">
                        <p>Activities and Workshop</p>
                    </div>
                    <div class="col-3 whatWeDoCards" style="background-color: white; box-shadow: 1px 4px 10px grey;">
                        <img class="navVectors" src='../assets/supp.png' alt="Vector">
                        <p>Tech Support</p>
                    </div>
                </div>
            </div>
            <div class="col-1"></div>
        </div>
    </div>
    <div id="topRated" class="main" style="background-color: #4E2A84; color: white">
        <div class="col-md-12" style="margin: 0;  display: grid; justify-items: center;">
            <div class="topRatedTextsContainer">
                <h1 class="topRatedTextBold wwr-textBold">
                    Who We Are
                </h1>
                <p class="topRatedText">	
                    We are a dedicated technology consulting firm focused on helping individuals master digital tools. Our expert team provides personalized support to enhance your tech skills and confidence. 
                </p>
            </div>
        </div>

        <div class="row topRatedCardContainer" style="margin-top: 70px">
            <div class="col-1"></div>
            <div class="col-10">
                <div class="row" style="display: flex; justify-content: space-around; width: 100%;">
                    <div class="col-1"></div>
                    <div class="col">
                        <div style="width: 597px; background-color: transparent;">
                            <div>
                                <!-- Replace VIDEO_ID with the actual video ID from YouTube -->
                                <iframe style="width: 100%; aspect-ratio: 16/9" src="https://www.youtube.com/embed/UJScd3m6glY" allowfullscreen></iframe>
                            </div>
                        </div>
                    </div>
                    <div class="col" style="display: grid; align-content: center; padding: 0">
                        <div class="row" style="display: flex; margin: 0; width: 100%">
                            
                            <div class="col-3"></div>
                            <div class="col" style="padding: 0">
                                <h1 style="margin-bottom: 20px; font-weight: bold">Most trusted in our field</h1>
                                <div class="row" style="margin: 0; padding-bottom: 10px">
                                    <div class="col-12" style="padding: 0; align-content: center;">
                                        <ul>
                                            <li>
                                                <p style="margin: 0; font-weight: bold; font-size: 16px">Pega Business Architect</p>
                                            </li>
                                            <li>
                                                <p style="margin: 0; font-weight: bold; font-size: 16px">Supply Chain Management</p>
                                            </li>
                                            <li>
                                                <p style="margin: 0; font-weight: bold; font-size: 16px">Expert Consultants</p>
                                            </li>
                                            <li>
                                                <p style="margin: 0; font-weight: bold; font-size: 16px">Microsoft Office</p>
                                            </li>
                                            <li>
                                                <p style="margin: 0; font-weight: bold; font-size: 16px">Comprehensive Support</p>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                            <div class="col-3"></div>
                        </div>
                    </div>
                    <div class="col-1"></div>
                </div>
            </div>
            <div class="col-1"></div>
        </div>
    </div>
    <div id="about_us" style="background-color: #e3e3e3;" class="main">
        <div class="col-md-12" style="margin: 0;  display: grid; justify-items: center">
            <div class="topRatedTextsContainer">
                <h1 class="topRatedTextBold" style="color: #4E2A84;">
                    About Us
                </h1>
                <p class="topRatedText">	
                    We are a dedicated technology consulting firm focused on helping individuals master digital tools. Our expert team provides personalized  to enhance your tech skills and confidence. 
                </p>
            </div>
        </div>

        <div class="row topRatedCardContainer">
            <div class="col-1"></div>
            <div class="col-10">
                <div class="row" style="display: flex; justify-content: center; height: fit-content;">
                    <div class="col-3 aboutUsCards" style="background-color: white; box-shadow: 1px 4px 10px grey;">
                        <p style="margin: 0; color: #4E2A84">Chief Operating Officer</p>
                        <p style="font-weight: normal; color: #4E2A84">Shafique</p>
                        <p style="padding: 0 20px; font-size: 17px; color: #4E2A84">Shafique has developed an impressive track record in designing and implementing innovative and cutting-edge solutions for companies of all sizes. He has a deep understanding of various technologies and their practical applications in solving complex business challenges.</p>
                    </div>
                    <div class="col-3 aboutUsCards" style="background-color: #4E2A84; box-shadow: 1px 4px 10px grey; color: white; margin: 0 35px">
                        <p style="padding: 0; margin: 0">Chief Executive Officer</p>
                        <p style="font-weight: normal">Musa Shafique</p>
                        <p style="padding: 0 20px; font-size: 17px">Musa is dynamic leader with 20+ years in product management for defense and tech sectors, leveraging data analytics for innovation and user experience enhancement. Expert in Agile methodologies, Python, R-Studio, and ensuring compliance with DOD and GovCloud standards.</p>
                    </div>
                    <div class="col-3 aboutUsCards" style="background-color: white; box-shadow: 1px 4px 10px grey;">
                        <p style="padding: 0; margin: 0; color: #4E2A84">Business Development Manager</p>
                        <p style="font-weight: normal; color: #4E2A84">Marwah Shafique</p>
                        <p style="padding: 0 20px; font-size: 17px; color: #4E2A84">Marwah's expertise in navigating complex markets and driving business growth has been instrumental in expanding Myd Technology reach and impact. Marwahs's strategic vision and leadership are key assets in delivering exceptional value to clients and fostering long-term partnerships worldwide.</p>
                    </div>
                </div>
            </div>
            <div class="col-1"></div>
        </div>
    </div>
    <div id="contactUs" class="main row contactForm">
        <div class="contactUsCard2">
            <form method="POST" class="row form-card">
            <!-- <form method="POST" class="row form" style="width: 100%; display: flex; justify-content: center"> -->
                <!-- {% csrf_token %} -->
                <h4 style="color: #252B42; text-align: center">
                    Contact Us
                </h4>
                <div class="row" style="margin: 0;">
                    <div class="mb-3 col-12" style="padding: 0">
                        <input type="text" name="name" class="form-control forms" id="name" placeholder="Name" aria-describedby="nameHelp">
                      </div>
                      <div class="mb-3 col-12" style="padding: 0">
                        <input type="email" name="email" class="form-control forms"  placeholder="E-mail address" id="emailaddr">
                      </div>
                      <div class="mb-3 col-12" style="padding: 0;">
                        <textarea class="form-control forms" id="message" placeholder="Message" rows="4" name="message" style="min-height: 174px; max-height: 174px; border-radius: 0"></textarea>
                      </div>
                </div>
                <div>
                    <button type="submit" class="btn btn-primary msgSendBtn">
                        Send
                    </button>
                </div>
            </form>
        </div>
        <div class="contactUsCard1" style="justify-content: center">
            <h1  style="font-weight: bold; height: fit-content; font-family: Helvetica; margin: 0; text-align: center; color: white">
                Get In Touch
            </h1>
            <h5  style="font-weight: bold; font-family: Helvetica; margin: 0; text-align: center; padding: 20px 0 12px; color: white">
                musa.shafique@mydtechs.com
            </h5>
            <p style="font-weight: bold; font-family: Helvetica; margin: 0; font-size: 14px; text-align: center; color: white">
                224 730-9565
            </p>
        </div>
    </div>
    <div style="background: #11112a; padding: 60px 0">
        <div class="main" style="margin: 0 auto; display: grid">
          <div class="copyrightContainer" style="display: grid; justify-content: center; justify-items: center">
            <img src="../assets/MYD Technology Logo.png" alt="MYD Technology.">
            <p
              class="copyrightContainerText"
              style="font-family: Helvetica; text-align: center; width: 100%; margin-top: 20px">
              Copyright. All Rights Reserved
            </p>
          </div>
        </div>
    </div>
</template>

<script>
import InterviewBuilder from "@/assets/logo.svg"

import 'bootstrap/dist/css/bootstrap.min.css';

export default{
  data() {
    return{
      defaultImage: InterviewBuilder
    }
  }
}

</script>

<style scoped>

</style>
<style>

body {
    background-color: #ffffff; /* White background */
    color: #333333; /* Dark gray text for better readability */
    font-family: 'Helvetica'; /* Clean and simple font */
    margin: 0;
    padding: 0;
    
}
.form-control{
    border-radius: 50px;
}
.form-control::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
    color: #18171D;
    opacity: 1; /* Firefox */
}
.forms{
    background-color: #F5F5F5;
    height: 54px;
    border-color: white;
    color: #18171D;
    margin: 20px 0 0 0
}
.nav-item2 .nav-link{
    text-align: center;
    border: 1px solid white;
    justify-items: center;
    display: flex;
    padding: 5px 20px !important;
    border-radius: 25px;
    color: white;
    font-size: 24px;
    font-weight: normal;
}
.navbar {
    border-bottom: 1px solid #e7e7e7; /* Light border for subtle separation */
}
.nav-item{
	width: fit-content;
}
.nav-link {
    font-size: 16px; /* Comfortable size for readability */
    margin-right: 20px; /* Space between links */
    width: fit-content;
    font-weight: bold;
    color: white
}

.nav-link:hover {
    color: #4E2A84; /* Black color on hover for emphasis */
}

.container {
    padding: 40px 15px; /* Adequate padding for content section */
}

.main{
	padding: 50px 100px
}

h1 {
    font-size: 2.5rem; /* Large heading for main title */
    margin-bottom: 20px; /* Space below the heading */
}

p {
    font-size: 1.1rem; /* Slightly larger paragraph text for readability */
    line-height: 1.6; /* Better line spacing */
    margin-bottom: 20px; /* Space below the paragraph */
}

.btn-primary {
    background-color: #007bff; /* Bootstrap primary color */
    border-color: #007bff;
}

.btn-primary:hover {
    background-color: #0056b3;
    border-color: #0056b3;
}

.social-icons i {
    font-size: 1.2rem; /* Adjust icon size */
    color: #555555; /* Gray color for icons */
}

.social-icons i:hover {
    color: #000000; /* Black color on hover */
}

#heroSection{
    background-image: url('../assets/backgroundheader.png') !important; 
    background-size: 100% 100%; 
    background-position: center;
}
#projectSection{
    background-image: url('../assets/back3.png') !important; 
    background-size: 100% 100%; 
    background-position: center; 
    color: white;
}
#topRated {
    background-color: #F3F3F3;
    background-size: 100% 100%; 
    background-position: center;
    padding: 125px 0 !important
}

.headerNav :hover{
    border-bottom: #000000 solid 1px;
}

.headerNav :active{
    border-bottom: #000000 solid 1px;
}
.navBarOptions{
    justify-content: right;width: 100%; margin-left: 40px;
}
.aboutUsImages{
    justify-content: space-between; 
    display: flex
}
.aboutUSImg1{
    height: 270px; width: 69%; border-radius: 5%; padding: 40px 20px
}
.aboutUSImg2{
    width: 30%;
}
.aboutUSImg4{
    height: 556px; 
    width: 100%;
}
.aboutUSImg1TextBold{
    font-size: 28px; line-height: 36px;
}
.aboutUSImg1Text{
    font-size: 18px; line-height: 26px;
    margin-top: 5px;
}
.aboutUSImg2TextBold{
    font-size: 128px; line-height: 150px;
}
.aboutUSImg2Text{
    font-size: 18px; line-height: 26px; margin-top: 5px
}
.visionCardsContainer{
    display: flex; justify-content: space-between; padding: 22px; margin-top: 50px
}
.visionCard1{
    width: 48%;
    padding: 20px;
    background-image: url('../assets/card-left.png'); background-size: 100% 100%; background-position: center;
}
.visionCard2{
    width: 48%;
    padding: 20px;
    background-image: url('../assets/card-right.png'); background-size: 100% 100%; background-position: center
}
.visionCardTitle{
    text-align: left; font-size: 20px; line-height: 22px; font-weight: bold; text-decoration: underline
}
.visionCardHeading{
    text-align: left; font-size: 32px; line-height: 35px
}
.visionCardText{
    text-align: left; font-size: 16px; line-height: 23px
}
.visionCardImageContainer{
    justify-content: center;
    display: flex
}
.topRatedTextsContainer{
    padding: 0; width: 60%;
}
.topRatedTextBold{
    font-weight: bold; font-size: 48px; line-height: 58px; padding: 0; text-align: center
}
.topRatedText{
    font-size: 18px; line-height: 30px; text-align: center
}
.topRatedCardContainer{
    width: 100%; display: flex; justify-content: center;
}
.topRatedCardContainerMargin{
    margin-top: 30px;
}
.topRatedCard{
    width: 30%; object-fit: contain; padding: 0
}
.topRatedCardMid{
    margin: 0 20px;
    width: 30%;
}
.contactBtn{
    width: 274px; height: 80px;  background-color: #004CB4; color: white;
    font-weight: bold; display: grid; padding: 22px; font-size: 24px;
    text-align: center; border-radius: 10px
}
.projectHeadingsContainer{
    margin: 0; display: flex; justify-content: space-between;
}
.projectHeading{
    font-weight: bold; font-size: 80px; width: 40%
}
.projectSubHeading{
    font-size: 26px; line-height: 31px; text-align: right; width: 40%; color: grey
}
.projectNavBar{
    justify-content: left; width: 100%;
}
.footerHeading{
    font-size: 48px;
    font-weight: 400;
    line-height: 57.26px;
    letter-spacing: -0.01em;
    text-align: left;
    color: #ffffff;
    max-width: 345px;
}
.emailField{
    max-width: 400px;
    width: 100%;
    height: 80px;
    padding: 22px 24px 22px 24px;
    opacity: 0px;
    background-color: #11112a !important;
    color: white;
    margin-right: 18px;
    border-color: grey;
}
.navVectors{
    height: 48px;
    aspect-ratio: 1/1;
    margin-bottom: 10px !important
}
.statusBar{
    font-size: 18px; max-width: 41% !important;
}
.contactForm{
    display: flex; justify-content:space-between; margin: 0;
    background-color: #4E2A84;
}
.form-card{
    width: 55%; display: flex; 
    justify-content: center; margin: 0; 
    background-color: white; padding: 50px 30px;
    border-radius: 15px;
}
.contactUsCard1{
    color: #737373; width: 48%; 
    border-radius: 25px; display: grid; align-content: center
}
.badgeForm{
    position: relative; right: 0
}
.projectLeftFormCardContainer{
    padding: 0; width: 66%
}
.projectLeftFormBadgeContainer{
    padding: 0; justify-content: left; display: grid; width: 34%
}
.contactUsCard2{
    display: flex;
    padding: 30px; width: 48%; border-radius: 25px;
    justify-content: center;
}
.msgSendBtn{
    width: 100%; height: 48px; 
    background-color: #4E2A84; color: white; 
    font-size: 18px;
    border-radius: 25px;
    margin-top: 20px;
}
.footerContactBlockIcons{
    display: flex; justify-content: right; align-content: center
}
.copyrightContainerText{
    font-size: 16px;
    font-weight: 400;
    line-height: 26px;
    text-align: left;
    color: #ffffff;
}
.carousalHeadingText{
    font-weight: bold; font-size: 64px; line-height: 68px
}
.whatWeDoCards{
    display: grid;
    justify-items: center;
    align-content: center;
    align-items: center;
    width: 325px;
    height: 190px;
    color: #4E2A84;
    font-weight: bold;
}
.aboutUsCards{
    display: grid;
    justify-items: center;
    align-content: center;
    align-items: center;
    width: 325px;
    height: 450px;
    color: #4E2A84;
    font-weight: bold;
}
@media only screen and (max-width: 1080px) {
    .main{
        padding: 10px;
    }
    .navButton{
        position: absolute;
        right: 0;
        top: 0;
    }
    .navBarOptions{
        justify-content: right;width: 100%; margin-left: 0px;
    }
    .letsTalkBtn{
        margin-left: 0 !important;
    }
    .letsTalkContainer{
        margin: 0 !important;
        width: 100% !important;
        display: flex;
        justify-content: space-between;
    }
    .navbar-toggler-icon{
        font-size: 12px;
    }
    .statusBar{
        font-size: 13px;
    }
    .navVectors{
        height: 20px; width: 30px;
    }
    .navbarImagesContainer{
        width: 100%;
        display: grid;
        justify-items: center;
        margin: 0;
    }
    .navbarImage{
        height: 300px;
        width: 80%;
        margin: 10px 0;
    }
    .navbarExternalImages{
        height: 300px;
        width: 80%;
    }
    .heading{
        font-weight: bold;
        font-size: 20px;
        line-height: 8px
    }
    .subHeading{
        max-width: 260px;
        text-align: left;
        font-size: 11px;
        line-height: 18px
    }
    .aboutUsHeading{
        font-size: 30px;
        line-height: 65px;
    }
    .aboutUsTexts{
        justify-content: space-between !important;
        display: grid !important;
        margin: 0 !important;
    }
    .aboutUsBoldTextCol{
        width: 100%;
        display: flex;
    }
    .aboutUsTextCol{
        justify-items: right;
        display: grid;
        width: 100%;
        padding: 0
    }
    .aboutUsBoldText{
        font-size: 33px;
        line-height: 34px;
        padding: 0;
    }
    .aboutUsText{
        text-align: left;
        font-size: 14px;
        line-height: 22px;
    }
    .aboutUsImages{
        justify-content: center;
        justify-items: center;
        display: grid
    }
    .aboutUSImg1{
        height: 270px; width: 80%; border-radius: 5%; padding: 40px 20px
    }
    .aboutUSImg2{
        width: 69%;
        margin-top: 10px;
        margin-bottom: 10px;
        height: fit-content;
        padding-top: 20px;
        padding-bottom: 20px;
        display: flex;
        flex-direction: column;
        align-items: center;
        align-content: center;
    }
    .aboutUSImg3{
        display: none !important;
    }
    .aboutUSImg4Cotainer{
        display: flex;
        justify-content: center;
    }
    .aboutUSImg4{
        height: 500px; width: 85%;
    }
    .aboutUSImg1TextBold{
        font-size: 20px; line-height: 22px;
    }
    .aboutUSImg1Text{
        font-size: 15px; line-height: 20px;
        margin-top: 10px;
    }
    .aboutUSImg2TextBold{
        font-size: 100px; line-height: 100px;
        text-align: center;
    }
    .aboutUSImg2Text{
        font-size: 15px; line-height: 20px; margin-top: 5px
    }
    .visionCardsContainer{
        display: grid; justify-content: center; justify-items: center; padding: 10px; margin-top: 50px
    }
    .visionCard1{
        width: 100%;
        padding: 20px;
        background-image: url('../assets/card-left.png'); background-size: 100% 100%; background-position: center;
    }
    .visionCard2{
        width: 100%;
        padding: 20px;
        margin-top: 10px;
        background-image: url('../assets/card-right.png'); 
        background-size: 100% 100%; background-position: center
    }
    .visionCardTitle{
        text-align: left; font-size: 18px; line-height: 22px; font-weight: bold;
        text-decoration: underline; margin-bottom: 5px
    }
    .visionCardHeading{
        text-align: left; font-size: 25px; line-height: 28px
    }
    .visionCardText{
        text-align: left; font-size: 16px; line-height: 23px; margin-bottom: 0;
    }
    .visionCardImageContainer{
        justify-content: left;
        display: flex
    }
    .topRatedTextsContainer{
        padding: 0; width: 100%;
    }
    .topRatedTextBold{
        font-weight: bold; font-size: 28px; line-height: 35px; padding: 0; text-align: center
    }
    .topRatedText{
        font-size: 15px; line-height: 22px; text-align: center
    }
    .topRatedCardContainer{
        width: 90%; display: grid; justify-content: center; justify-items: center; padding: 0;
    }
    .topRatedCardContainerMargin{
        margin-top: 10px;
    }
    .topRatedCard{
        width: 100%; object-fit: contain; padding: 0
    }
    .topRatedCardMid{
        margin: 10px 0; padding: 0;
        width: 100%;
    }
    #topRated{
        display: grid;
        justify-items: center;
    }
    .contactBtn{
        width: 200px; height: 60px;  background-color: #004CB4; color: white;
        font-weight: bold; display: grid; padding: 22px; font-size: 20px;
        text-align: center; border-radius: 10px; align-content: center;
    }
    .projectHeadingsContainer{
        margin: 0; display: grid; justify-content: space-between;
    }
    .projectHeading{
        font-weight: bold; font-size: 40px; width: 100%;
    }
    .projectSubHeading{
        font-size: 18px; line-height: 26px; text-align: right; width: 100%; color: grey
    }
    .projectNavBar .nav-link{
        font-size: 15px;
        width: fit-content;
        margin-right: 0 !important;
    }
    .projectNavBar{
        justify-content: center;
        max-width: 100%;
        display: flex !important;
        flex-direction: row;
        flex-wrap: wrap;
    }
    .footerContainer{
        display: grid !important;
        justify-content: center !important;
    }
    .footerHeading{
        font-size: 30px;
        font-weight: 400;
        line-height: 57.26px;
        letter-spacing: -0.01em;
        text-align: left;
        color: #ffffff;
        max-width: 100%;
    }
    .emailField{
        max-width: 100%;
        width: 100%;
        height: 80px;
        padding: 22px 24px 22px 24px;
        opacity: 0px;
        background-color: #11112a !important;
        color: white;
        margin-right: 0px;
        border-color: grey;
    }
    .subscribeBtn{
        width: Hug (235px) px;
        height: Hug (80px) px;
        padding: 22px 60px;
        gap: 0px;   
        border-radius: 20px;
        opacity: 0px;
        background: #004cb4;
        font-size: 24px;
        font-weight: 700;
        line-height: 36px;
        letter-spacing: -0.01em;
        text-align: center;
        color: #ffffff;
    }
    .projectLeftFormCardContainer{
        padding: 0; width: 75%
    }
    .projectLeftFormBadgeContainer{
        padding: 0; justify-content: left; display: grid; width: 25%
    }
    .projectLeftFormCard{
        font-size: 50px;
        line-height: 70px;
    }
    .contactForm{
        display: grid; 
        justify-items: center;
        justify-content: center;
        margin: 0;
    }
    .contactUsCard1{
        background-color: #11112A; color: white; min-width: 97%;
        border-radius: 25px; display: grid; align-content: center;
        padding: 35px 10px !important
    }
    .badgeForm{
        position: relative;
        right: 0;
        height: 80px;
        width: 80px;
    }
    .contactUsCard2{
        background-color: #004CB4; padding: 40px 20px; min-width: 97%; border-radius: 25px; margin-top: 20px
    }
    .form{
        margin: 0;
    }
    .msgSendBtn{
        margin-top: 20px;
        width: 93%; height: 60px; 
        font-weight: bold; font-size: 30px
    }
    .footerCol1{
        min-width: 32vw !important;
    }
    .footerCol2{
        min-width: 32vw !important;
    }
    .footerCol3{
        min-width: 32vw !important;
    }
    .footerCol4{
        min-width: 100vw !important;
        display: flex !important;
        margin-left: 9px
    }
    .footerCol4Container{
        color: #ffffff; text-align: right;
        display: grid;
        justify-items: center;
    }
    .footerCol4Logo{
        width: 60%;
        margin-top: 40px;
    }
    .footerCol4Contact{
        margin-top: 20px; text-align: left;
        margin-bottom: 40px
    }
    .footerContactBlock1{
        min-width: 97vw;
        display: grid;
        margin-left: -10px;
        justify-items: center;
        justify-content: center;
    }
    .footerContactBlock1Content{
        min-width: 250px !important;
        margin-bottom: 10px;
    }
    .footerContactBlockIcons{
        display: flex; justify-content: center; align-content: center;
        margin-top: 20px;
    }
    .copyrightContainer{
        display: grid !important;
        justify-content: center !important;
        justify-items: center !important;
        padding: 0;
    }
    .copyrightContainerText{
        font-size: 15px;
        font-weight: 400;
        line-height: 26px;
        text-align: left;
        color: #ffffff;
    }
    .copyrightContainerList{
        padding: 0;
    }
    .carouselDesktop{
        display: none;
    }
    .carousalHeadingText{
        font-weight: bold; 
        font-size: 40px; 
        line-height: 30px;

    }
}
@media only screen and (min-width: 720px) and  (max-width: 1080px) {
    .carouselMobile{
        display: none;
    }
    .projectLeftFormCard{
        font-size: 52px;
    }
    .statusBar{
        font-size: 18px;
    }
    .navbarImagesContainer{
        justify-content: space-between !important;
        display: flex;
    }
    .navbarImage{
        height: 300px;
        width: 26%;
    }
    .navbarExternalImages{
        height: 300px;
        width: 36%;
    }
    .heading{
        font-weight: bold;
        font-size: 30px;
        line-height: 13px
    }
    .subHeading{
        max-width: 260px;
        text-align: left;
        margin-top: -32px;
        font-size: 15px;
        line-height: 18px
    }
    .aboutUsHeading{
        font-size: 30px;
        line-height: 65px;
    }
    .aboutUsTexts{
        justify-content: space-between !important;
        display: grid !important;
        margin: 0 !important;
    }
    .aboutUsBoldTextCol{
        width: 100%;
        display: flex;
    }
    .aboutUsTextCol{
        justify-items: right;
        display: grid;
        width: 100%;
        padding: 0
    }
    .aboutUsBoldText{
        font-size: 50px;
        line-height: 50px;
        padding: 0;
    }
    .aboutUsText{
        text-align: left;
        font-size: 17px;
        line-height: 22px;
    }
}
@media only screen and (min-width: 1200px) and (max-width: 1440px) {
    .carouselMobile{
        display: none;
    }
    .projectLeftFormCard{
        font-size: 70px;
    }
    .statusBar{
        font-size: 27px;
    }
    .navbarImagesContainer{
        justify-content: space-between !important;
        display: flex;
    }
    .navbarImage{
        height: 550px;
        width: 26%;
    }
    .navbarExternalImages{
        height: 550px;
        width: 36%;
    }
    .heading{
        font-weight: bold;
        font-size: 64px;
        line-height: 68px
    }
    .subHeading{
        max-width: 320px;
        text-align: left;
        margin-top: -30px;
        font-size: 20px;
        line-height: 22px
    }
    .aboutUsHeading{
        font-size: 40px;
        line-height: 65px;
    }
    .aboutUsTexts{
        justify-content: space-between !important;
        display: flex !important;
        margin: 0 !important;
    }
    .aboutUsBoldTextCol{
        width: 60%;
        display: flex
    }
    .aboutUsTextCol{
        justify-items: right;
        display: grid;
        width: 40%
    }
    .aboutUsBoldText{
        font-size: 64px;
        line-height: 68px;
        padding: 0
    }
    .aboutUsText{
        text-align: left;
        font-size: 20px;
        line-height: 22px
    }
}
@media only screen and (min-width: 1450px){
    .carouselMobile{
        display: none;
    }
    .projectLeftFormCard{
        font-size: 96px;
    }
    .statusBar{
        font-size: 27px;
    }
    .navbarImagesContainer{
        justify-content: space-between !important;
        display: flex;
    }
    .navbarImage{
        height: 550px;
        width: 26%;
    }
    .navbarExternalImages{
        height: 550px;
        width: 36%;
    }
    .heading{
        font-weight: bold;
        font-size: 64px;
        line-height: 68px
    }
    .subHeading{
        max-width: 320px;
        text-align: left;
        font-size: 20px;
        line-height: 22px;
    }
    .aboutUsHeading{
        font-size: 40px;
        line-height: 65px;
    }
    .aboutUsTexts{
        justify-content: space-between !important;
        display: flex !important;
        margin: 0 !important;
    }
    .aboutUsBoldTextCol{
        width: 60%;
        display: flex
    }
    .aboutUsTextCol{
        justify-items: right;
        display: grid;
        width: 40%
    }
    .aboutUsBoldText{
        font-size: 64px;
        line-height: 68px;
        padding: 0
    }
    .aboutUsText{
        text-align: left;
        font-size: 20px;
        line-height: 22px
    }
    .topRatedTextsContainer{
        padding: 0; width: 60%;
    }
    .topRatedTextBold{
        font-weight: bold; font-size: 48px; line-height: 58px; padding: 0; text-align: center
    }
    .topRatedText{
        font-size: 18px; line-height: 30px; text-align: center
    }
    .topRatedCardContainer{
        width: 100%; display: flex; justify-content: center
    }
    .topRatedCardContainerMargin{
        margin-top: 30px;
    }
    .topRatedCard{
        width: 30% !important; object-fit: contain; padding: 0
    }
    .topRatedCardMid{
        margin: 0 20px;
        width: 30% !important; object-fit: contain; padding: 0
    }
    .aboutUSImg1TextBold{
        font-size: 45px !important; line-height: 45px;
    }
    .aboutUSImg1Text{
        font-size: 20px; line-height: 28px;
        margin-top: 10px;
    }
    .aboutUSImg2TextBold{
        font-size: 128px; line-height: 150px;
    }
    .aboutUSImg2Text{
        font-size: 20px; line-height: 28px; margin-top: 5px
    }
}
@media only screen and (min-width: 2000px){
    .carouselMobile{
        display: none;
    }
    .projectLeftFormCard{
        font-size: 120px;
    }
    .statusBar{
        font-size: 27px;
    }
    .navbarImagesContainer{
        justify-content: space-between !important;
        display: flex;
    }
    .navbarImage{
        height: 550px;
        width: 26%;
    }
    .navbarExternalImages{
        height: 550px;
        width: 36%;
    }
    .heading{
        font-weight: bold;
        font-size: 64px;
        line-height: 68px
    }
    .subHeading{
        max-width: 320px;
        text-align: left;
        font-size: 20px;
        line-height: 22px
    }
    .aboutUsHeading{
        font-size: 40px;
        line-height: 65px;
    }
    .aboutUsTexts{
        justify-content: space-between !important;
        display: flex !important;
        margin: 0 !important;
    }
    .aboutUsBoldTextCol{
        width: 60%;
        display: flex
    }
    .aboutUsTextCol{
        justify-items: right;
        display: grid;
        width: 40%
    }
    .aboutUsBoldText{
        font-size: 64px;
        line-height: 68px;
        padding: 0
    }
    .aboutUsText{
        text-align: left;
        font-size: 20px;
        line-height: 22px
    }
    .aboutUSImg1TextBold{
        font-size: 200px !important; line-height: 36px;
        color: red !important;
    }
    .aboutUSImg1Text{
        font-size: 200px; line-height: 26px;
        margin-top: 5px;
    }
    .aboutUSImg2TextBold{
        font-size: 128px; line-height: 150px;
    }
    .aboutUSImg2Text{
        font-size: 18px; line-height: 26px; margin-top: 5px
    }
}
.footerIcons i{
    font-size: 20px !important; /* Adjust icon size */  
    border-radius: 50%;
    border: 1px solid white;
    color: white; /* Gray color for icons */
    opacity: 0.70;
    height: 45px;
    width: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.footerIcons i:hover{
    background-color: white;
    color: black
}

.imgProject{
    height: fit-content;
    width: 32%;
    border-radius: 12px;
}

h2 {
	color: #000;
	font-size: 26px;
	font-weight: 300;
	position: relative;
	margin: 0 0 50px 0;
	text-transform: uppercase;
	display: inline-block;
}
h2::after {
	content: "";
	width: 50%;
	position: absolute;
	height: 4px;
	border-radius: 1px;
	background: #ff5555;
	left: 0;
	bottom: -20px;
}
.userContainer{
    display: flex;
    justify-content: left !important;
    align-content: center;
    align-items: center;
    height: fit-content;
    padding: 0 !important;
    margin-left: 0 !important;
}
</style>
