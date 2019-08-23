<style>
.flexContainer {
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
}

.project {
  display:flex;
  margin: 20px auto;
  padding: 20px;
  max-width: 75%;
  flex:1;
}

.project:hover {
  background-color: #eee;
  cursor: pointer;
}

h3 {
  font: bold 20px/1.5 Helvetica, Verdana, sans-serif;
}

div img {
  float: left;
  width: 25%;
  height: auto;
  padding: 0 20px 0 15px;
  position:relative;
}


@media only screen and (max-width: 850px) {
	.project p {
    padding-top: 50px;
    padding-left: 30px;
    padding-right: 30px;    
    }
    .project h3 {
    padding-top: 5%;
    }
}

@media only screen and (max-width: 680px) {
	.project p {
    padding-top: 45px;
    padding-left: 30px;
    padding-right: 30px;
    }
    .project h3 {
    padding-top: 5%;
    font-size: 16px;
    }
}

@media only screen and (max-width: 500px) {
	.project p {
    padding-top: 20px;
    padding-left: 30px;
    padding-right: 30px;
    }
    .project h3 {
    padding-top: 3%;
    font-size: 16px;
    }
}

</style>

# Projects


<div class = "flexContainer">

  <div class = "project">
    <a href="https://www.kaggle.com/dcstang/bqml-bikeshare-deep-dive">
    <img class="projImg" src="http://dcstang.github.io/assets/blog_pics/kaggleicon.jpg" >
    <h3>Bikeshare Geospatial Visualization</h3>
    <p>Kaggle Kernel on Google Open Bikeshare dataset in Austin, Tx from 2013-2019 | Total 1.1M rows<br>
        Technologies incorporated: Bigquery, SQL, Pandas, Matplotlib, Geopandas, Python </p>
    </a>
  </div>

  <div class = "project">
    <a href="https://github.com/dcstang/posture-detection">
    <img src="http://dcstang.github.io/assets/blog_pics/opencv_logo.png">
    <h3>Posture Detection with Python</h3>
    <p>Work in progress - done live face detection via computer webcam access. Working on image segmentation and masking, and incorporating posture calculation.
        Technologies incorporated: Python, OpenCV, HaarCascades, Machine Learning
      </p>
  </div>
</div>

<!--
<li>
  <img src="http://lorempixum.com/100/100/nature/3" >
  <h3>Smoke On The Water</h3>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent euismod ultrices ante, ac laoreet nulla vestibulum adipiscing. Nam quis justo in augue auctor imperdiet.</p>
</li>

<li>
  <img src="http://lorempixum.com/100/100/nature/4" >
  <h3>Headline</h3>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent euismod ultrices ante, ac laoreet nulla vestibulum adipiscing. Nam quis justo in augue auctor imperdiet.</p>
</li>
-->
