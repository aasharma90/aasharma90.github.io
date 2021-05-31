---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p style='text-align: justify;'> I'm presently working as a Scientist in the <a href="https://www.a-star.edu.sg/i2r">Institute of Infocomm Research (I2R)</a> division of A*Star, Singapore.  I obtained my Ph.D. at the National Univeristy of Singapore, under the joint supervision of Prof. <a href="http://tanrobby.github.io/">Robby T. Tan</a> and Prof. <a href="https://www.ece.nus.edu.sg/stfpage/eleclf/">Loong-Fah Cheong</a>. I've also worked in collaboration with Dr. <a href="http://www.lionel.work/">Lionel Heng</a> from DSO National Labortories, Singapore. My primary research interests include Computer Vision and Deep Learning. </p>

<p style='text-align: justify;'> Previously, I worked as a senior design engineer at Freescale Semiconductors, India. I obtained my B.Eng. from Delhi College of Engineering, University of Delhi, India. </p>


Research
======
<p style='text-align: justify;'> My current research work deals with: (1) Handling low-level vision problems such as depth from stereo and optical flow estimation, and (2) Performing visibility enhancement, under degraded visibility conditions.</p>

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
    papertitle_just {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700;
    text-align: justify
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
<!-- ################################  CONTENT START  ##################################################-->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="10">
<tbody>
<!-- ############################ Put your publications below this! ####################################-->

<!-- ###################################################################################################-->
<!-- NightEnhance, CVPR'21 -->
<tr onmouseout="cvpr21_nightenhance_stop()" onmouseover="cvpr21_nightenhance_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'cvpr21_nightenhance_image'><img src='./files/cvpr21_after.png'></div>
<img src='./files/cvpr21_before.png'>
</div>
<script type="text/javascript">
function cvpr21_nightenhance_start() {
document.getElementById('cvpr21_nightenhance_image').style.opacity = "1";
}
function cvpr21_nightenhance_stop() {
document.getElementById('cvpr21_nightenhance_image').style.opacity = "0";
}
cvpr21_nightenhance_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="">
    <papertitle_just>Nighttime Visibility Enhancement by Increasing the Dynamic Range and Suppression of Light Effects</papertitle_just>     
  </a>
  <br>
  <strong>Aashish Sharma</strong>, Robby T. Tan
  <br>
<em>Computer Vision and Pattern Recognition (CVPR)</em>, 2021, Nashville, USA <br>
<a href="">paper</a>
|
<a href="">bibtex</a>
<p></p>
<p></p>
</td>
</tr>
<!-- Cycle-Stereo DispNet, 3DV'20 -->
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- Cycle-Stereo DispNet, 3DV'20 -->
<tr onmouseout="threedv20_cstdispnet_stop()" onmouseover="threedv20_cstdispnet_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'threedv20_cstdispnet_image'><img src='./files/threedv20_after.png'></div>
<img src='./files/threedv20_before.png'>
</div>
<script type="text/javascript">
function threedv20_cstdispnet_start() {
document.getElementById('threedv20_cstdispnet_image').style.opacity = "1";
}
function threedv20_cstdispnet_stop() {
document.getElementById('threedv20_cstdispnet_image').style.opacity = "0";
}
threedv20_cstdispnet_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://ieeexplore.ieee.org/abstract/document/9320347">
    <papertitle_just>Nighttime Stereo Depth Estimation using Joint Translation-Stereo Learning: Light Effects and Uninformative Regions</papertitle_just>     
  </a><strong>[Oral]</strong>
  <br>
  <strong>Aashish Sharma</strong>, Loong-Fah Cheong, Lionel Heng, Robby T. Tan
  <br>
<em>International Conference on 3D Vision (3DV)</em>, 2020, Fukuoka, Japan <br>
<a href="https://arxiv.org/pdf/1909.13701.pdf">paper</a>
| 
<a href="./files/threedv20_cstdispnet_bibtex.txt">bibtex</a>
|
<a href="https://arxiv.org/abs/1909.13701v1">arXiv'19</a>
|
<a href="https://github.com/aasharma90/CycleStereoGAN_NighttimeDepth">code (arXiv'19)</a>
<p></p>
<p></p>
</td>
</tr>
<!-- Cycle-Stereo DispNet, 3DV'20 -->
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- CRF Estimation, ACCV'20 -->
<tr onmouseout="accv20_crfest_stop()" onmouseover="accv20_crfest_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'accv20_crfest_image'><img src='./files/accv20_crfest_after.png'></div>
<img src='./files/accv20_crfest_before.jpg'>
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
<td valign="top" width="80%">
  <a href="https://openaccess.thecvf.com/content/ACCV2020/html/Sharma_Single-Image_Camera_Response_Function_Using_Prediction_Consistency_and_Gradual_Refinement_ACCV_2020_paper.html">
  <papertitle style='text-align: justify;'>Single-Image Camera Response Function Using Prediction Consistency and Gradual Refinement</papertitle>
  </a>
  <br>
  <strong>Aashish Sharma</strong>, Robby T. Tan, Loong-Fah Cheong 
  <br>
<em>Asian Conference on Computer Vision (ACCV)</em>, 2020, Kyoto, Japan <br>
<a href="https://openaccess.thecvf.com/content/ACCV2020/papers/Sharma_Single-Image_Camera_Response_Function_Using_Prediction_Consistency_and_Gradual_Refinement_ACCV_2020_paper.pdf">paper</a>
|		
<a href="./files/accv20_crfest_bibtex.txt">bibtex</a>
<p></p>
<p></p>
</td>
</tr>
<!-- CRF Estimation, ACCV'20 -->
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- FogFlowNet, CVPR'20 -->
<tr onmouseout="cvpr20_fogflownet_stop()" onmouseover="cvpr20_fogflownet_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'cvpr20_fogflownet_image'><img src='./files/cvpr20_fogflow_after.jpg'></div>
<img src='./files/cvpr20_fogflow_before.jpg'>
</div>
<script type="text/javascript">
function cvpr20_fogflownet_start() {
document.getElementById('cvpr20_fogflownet_image').style.opacity = "1";
}
function cvpr20_fogflownet_stop() {
document.getElementById('cvpr20_fogflownet_image').style.opacity = "0";
}
cvpr20_fogflownet_stop()
</script>
</td>
<td valign="top" width="80%">
    <a href="http://openaccess.thecvf.com/content_CVPR_2020/html/Yan_Optical_Flow_in_Dense_Foggy_Scenes_Using_Semi-Supervised_Learning_CVPR_2020_paper.html">
    <papertitle style='text-align: justify;'>Optical Flow in Dense Foggy Scenes using Semi-Supervised Learning</papertitle>
  </a>
  <br>
  Wending Yan*, <strong>Aashish Sharma</strong>*, Robby T. Tan (*equal contribution)
  <br>
<em>Computer Vision and Pattern Recognition (CVPR)</em>, 2020, Seattle, USA <br>
<a href="http://openaccess.thecvf.com/content_CVPR_2020/papers/Yan_Optical_Flow_in_Dense_Foggy_Scenes_Using_Semi-Supervised_Learning_CVPR_2020_paper.pdf">paper</a>
|		
<a href="./files/cvpr20_fogflow_bibtex.txt">bibtex</a>
<p></p>
<p>Optical flow estimation under dense fog conditions via domain adaptive semi-supervised learning using labelled synthetic and unlabelled real fog data.</p>
</td>
</tr>
<!-- FogFlowNet, CVPR'20 -->
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- Joint Structure-Stereo, ECCV'18 -->
<tr onmouseout="eccv18_jss_stop()" onmouseover="eccv18_jss_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'eccv18_jss_image'><img src='./files/eccv18_pic_after.png'></div>
<img src='./files/eccv18_pic_before.png'>
</div>
<script type="text/javascript">
function eccv18_jss_start() {
document.getElementById('eccv18_jss_image').style.opacity = "1";
}
function eccv18_jss_stop() {
document.getElementById('eccv18_jss_image').style.opacity = "0";
}
eccv18_jss_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="http://openaccess.thecvf.com/content_ECCV_2018/html/Aashish_Sharma_Into_the_Twilight_ECCV_2018_paper.html">
    <papertitle style='text-align: justify;'>Into the Twilight Zone: Depth Estimation using Joint Structure-Stereo Optimization</papertitle>
  </a>
  <br>
  <strong>Aashish Sharma</strong>, Loong-Fah Cheong 
  <br>
<em>European Conference on Computer Vision (ECCV)</em>, 2018, Munich, Germany <br>
<a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Aashish_Sharma_Into_the_Twilight_ECCV_2018_paper.pdf">paper</a>
|
<a href="./files/eccv2018_poster.pdf">poster</a>
| 
<a href="./files/eccv2018_bibtex.txt">bibtex</a>
<p></p>
<p>Depth estimation for weakly-lit nighttime images by optimizing a joint structure-structure model.</p>
</td>
</tr>
<!-- Joint Structure-Stereo, ECCV'18 -->
<!-- ###################################################################################################-->

<!-- ############################ Put your publications above this! ####################################-->
</tbody></table>

Professional Services
======
Reviewer: CVPR, PSIVT, IJCV

Work Experience
======
- 2017-Present: Research Engineer at NUS, Singapore
- 2012-2016: Senior Design Engineer at Freescale Semiconductors, India
