---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p style='text-align: justify;'> I am a Ph.D. student at the National Univeristy of Singapore, under the joint supervision of Prof. <a href="http://tanrobby.github.io/">Robby T. Tan</a> and Prof. <a href="https://www.ece.nus.edu.sg/stfpage/eleclf/">Loong-Fah Cheong</a>. My primary research interests include Computer Vision, Image Processing and Machine Learning.  </p>

<p style='text-align: justify;'> I obtained my B.Eng. at Delhi College of Engineering (University of Delhi) in 2012, and then spent four years at Freescale Semiconductors (now, NXP Semiconductors), India, before coming to Singapore for higher education. </p>



Research
======
<p style='text-align: justify;'> My current research work aligns with handling low-level vision problems such as depth from stereo and optical flow estimation, under degraded visibility conditions. Related publications are presented below. </p>

<style type="text/css">
    /* Color scheme stolen from Sergey Karayev */
    a {
    color: #1772d0;
    text-decoration:none !important;
    }
    a:focus, a:hover {
    color: #f09228;
    text-decoration:none !important;
    }
    table,td,th,tr{
    	border:none !important;
    }
    body,td,th,tr,p,a {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px
    }
    strong {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    }
    heading {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 22px;
    }
    papertitle {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700
    }
    name {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 32px;
    }
    .one
    {
    width: 160px;
    height: 160px;
    position: relative;
    }
    .two
    {
    width: 160px;
    height: 160px;
    position: absolute;
    transition: opacity .2s ease-in-out;
    -moz-transition: opacity .2s ease-in-out;
    -webkit-transition: opacity .2s ease-in-out;
    }
    .fade {
     transition: opacity .2s ease-in-out;
     -moz-transition: opacity .2s ease-in-out;
     -webkit-transition: opacity .2s ease-in-out;
    }
    span.highlight {
        background-color: #ffffd0;
    }
</style>
<!-- ################################  CONTENT START  #######################################-->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="10">
		
	<!-- CRF Estimation, ACCV'20 -->
	<tr onmouseout="accv20_crfest_stop()" onmouseover="accv20_crfest_start()" >
        <td width="25%">
        <div class="one">
        <div class="two" id = 'accv20_crfest_image'><img src='pics/accv20_crfest_after.png'></div>
        <img src='pics/accv20_crfest_before.jpg'>
        </div>
        <script type="text/javascript">
        function accv20_crfest_start() {
        document.getElementById('accv20_crfest_image').style.opacity = "1";
        }
        function accv20_crfest_stop() {
        document.getElementById('accv20_crfest_image').style.opacity = "0";
        }
        accv20_crfest_stop()
        </script>
        </td>
        <td valign="top" width="75%">
	  <a href=>
          <papertitle>Single-Image Camera Response Function Using Prediction Consistency and Gradual Refinement</papertitle>
	  </a>
	  <br>
          <strong>Aashish Sharma</strong>, Robby T. Tan, Loong-Fah Cheong 
	  <br>
        <em>Asian Conference on Computer Vision (ACCV)</em>, 2020, Kyoto, Japan <br>
        <a href=>paper</a>
        |		
        <a href=>bibtex</a>
        <p></p>
        <p>Estimating the Camera Response Function (CRF) from a single image using the ideas of prediciton consistency and gradual refinement.</p>
        </td>
        </tr>
	<!-- CRF Estimation, ACCV'20 -->






