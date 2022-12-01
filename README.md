<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Kasun's Projects</title>
    <link rel="stylesheet" href="main.css" />
    
    
  </head>
  <body>
    <div class="topic">
      <h1>Kasun Kalhara's Research & Projects</h1>
    </div>

    <div class="project-preview">
      <div class="project-picture">
        <img class="mySlides" src="Pictures/Overall system.png"/>
        <img class="mySlides" src="Pictures/F1.png"/>
        <img class="mySlides" src="Pictures/F2.png"/>
        <img class="mySlides" src="Pictures/F3.png"/>
        <img class="mySlides" src="Pictures/F4.png"/>
        <img class="mySlides" src="Pictures/F5.JPG"/>
        <img class="mySlides" src="Pictures/F6.JPG"/>
        <img class="mySlides" src="Pictures/F7.JPG"/>


        <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">
        &#10094;
        </button>
        <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">
        &#10095;
        </button>
        <script>
          var slideIndex = 1;
            showDivs(slideIndex);
            
            function plusDivs(n) {
            showDivs((slideIndex += n));
            }
            
            function showDivs(n) {
            var i;
            var x = document.getElementsByClassName("mySlides");
            if (n > x.length) {
            slideIndex = 1;
            }
            if (n < 1) {
            slideIndex = x.length;
            }
            for (i = 0; i < x.length; i++) {
            x[i].style.display = "none";
            }
            x[slideIndex - 1].style.display = "block";
            }
        </script> 
        
    </div>

      <div class="project-description">
        <h2>
          A Fire Detection and Extinguishing Mobile Robot for Industrial
          Environments.
        </h2>
        <p>
          Kasun Kalhara Designed and developed a fire detection algorithm and self-navigation mobile robot algorithm to detect and extinguish the primary stage of fire flames in high priority industrial area.
        </p>
        <br />

        <p>DOI : <a href="https://ieeexplore.ieee.org/document/9606174" target="_blank"> 10.1109/ICIAfS52090.2021.9606174:</a
        ></p>
        <br />
        <button type="button" onclick="location.href='https://drive.google.com/file/d/1gm1WPj-Pxeknt3BXg4nVfHtGr2Cj8UgE/view?usp=sharing'">Video - 01</a></button>
        <button type="button" onclick="location.href='https://drive.google.com/file/d/1rmdZXv1ye25bmb2XPGXsTwtn9L26H4w6/view?usp=sharing'">Video - 02</a></button>
        <button type="button" onclick="location.href='https://drive.google.com/file/d/189ywYWMfI4x0MvQ7rxwoUTKCifEKuX98/view?usp=sharing'">Video - 03</a></button>
        <button type="button" onclick="location.href='https://drive.google.com/file/d/1WUZBlHaeBKAqTIu7plMqJjhiDzqubfjc/view?usp=sharing'">Video - 04</a></button>
        <button type="button" onclick="location.href='https://drive.google.com/file/d/1oYRM6TBDIcMa9_bQDwZ2qdUM9Gn7b_XV/view?usp=sharing'">Video - 05</a></button>
      </div>
    </div>
    <br/><hr>

    <!-- Second one-->
    <h2 class="related">Ongoing Research</h2>
    <div class="project-preview">
      <div class="project-picture">
        <img class="mySlides_02" src="Pictures/k01.jpg"/>
        <img class="mySlides_02" src="Pictures/k02.jpg"/>
        <img class="mySlides_02" src="Pictures/k04.jpg"/>
        <img class="mySlides_02" src="Pictures/k05.jpg"/>
        <img class="mySlides_02" src="Pictures/k06.jpg"/>
        <img class="mySlides_02" src="Pictures/k07.jpg"/>
        
        <button class="w3-button w3-black w3-display-left" onclick="plusDivs_02(-1)">
        &#10094;
        </button>
        <button class="w3-button w3-black w3-display-right" onclick="plusDivs_02(1)">
        &#10095;
        </button>

        <script>
          var slideIndex = 1;
            showDivs_02(slideIndex);
            
            function plusDivs_02(n) {
            showDivs_02((slideIndex += n));
            }
            
            function showDivs_02(n) {
            var i;
            var x = document.getElementsByClassName("mySlides_02");
            if (n > x.length) {
            slideIndex = 1;
            }
            if (n < 1) {
            slideIndex = x.length;
            }
            for (i = 0; i < x.length; i++) {
            x[i].style.display = "none";
            }
            x[slideIndex - 1].style.display = "block";
            }
        </script>
      </div>

      <div class="project-description">
        <h2>
          Design and develop an instrument to assess the emissions of greenhouse gases from Karadiyana open dumpsite and prepare an inventory.
        </h2>
        <p>
          This group research conducted by civil engineering department (OUSL) and national building research organization Sri Lanka. Kasun Kalhara innovated a power backup for this instrument to provide the real time data transferring.</p>
        
      </div>
    </div>
    <br/><hr>

    <!-- Third one-->
    <div class="project-preview">
      <div class="project-picture">
        <img class="mySlides_03" src="Pictures/sun02.jpg"/>
        <img class="mySlides_03" src="Pictures/sun01.jpg"/>
        
          <button class="w3-button w3-black w3-display-left" onclick="plusDivs_03(-1)">
          &#10094;
          </button>
          <button class="w3-button w3-black w3-display-right" onclick="plusDivs_03(1)">
          &#10095;
          </button>
          <script>
            var slideIndex = 1;
              showDivs_03(slideIndex);
              
              function plusDivs_03(n) {
              showDivs_03((slideIndex += n));
              }
              
              function showDivs_03(n) {
              var i;
              var x = document.getElementsByClassName("mySlides_03");
              if (n > x.length) {
              slideIndex = 1;
              }
              if (n < 1) {
              slideIndex = x.length;
              }
              for (i = 0; i < x.length; i++) {
              x[i].style.display = "none";
              }
              x[slideIndex - 1].style.display = "block";
              }
          </script>

      </div>

      <div class="project-description">
        <h2>
          Develop a control system and mathematical model for kinematics of sun tracking solar system. 
        </h2>
        <p>
          This system usesto provide the remote laboratory session for master of energy management 
students. This course is conducted by department of mechanical engineering, faculty of 
engineering technology the open university of Sri Lanka.</p>
        
      </div>
    </div>
    <br/><hr>

    <!-- fourth one-->
    <div class="project-preview">
      <div class="project-picture">
        <img class="mySlides_04" src="Pictures/s02.jpg"/>
        <img class="mySlides_04" src="Pictures/s01.jpg"/>
        <img class="mySlides_04" src="Pictures/s03.jpg"/>
        <img class="mySlides_04" src="Pictures/s04.jpg"/>
        <img class="mySlides_04" src="Pictures/s05.jpg"/>
        
        <button class="w3-button w3-black w3-display-left" onclick="plusDivs_04(-1)">
          &#10094;
          </button>
          <button class="w3-button w3-black w3-display-right" onclick="plusDivs_04(1)">
          &#10095;
          </button>
          <script>
            var slideIndex = 1;
              showDivs_04(slideIndex);
              
              function plusDivs_04(n) {
              showDivs_04((slideIndex += n));
              }
              
              function showDivs_04(n) {
              var i;
              var x = document.getElementsByClassName("mySlides_04");
              if (n > x.length) {
              slideIndex = 1;
              }
              if (n < 1) {
              slideIndex = x.length;
              }
              for (i = 0; i < x.length; i++) {
              x[i].style.display = "none";
              }
              x[slideIndex - 1].style.display = "block";
              }
          </script>

      </div>

      <div class="project-description">
        <h2>
          RRT algorithm implementation with computer vision based mobile robots. 
        </h2>
        <p>
          Rapidly-exploring Random Tree (RRT) is a motion planning algorithm that find the 
feasible path from an initial state to a goal state by building a graph. This methodology will 
be implemented with mobile robot applications to obtain the obstacle avoiding facility with 
overhead mounted wireless camera.</p>
        
      </div>
    </div>
    <br/><hr>

    <!-- fifth one-->
    <h2 class="related">Industrial Related Projects</h2>
    <div class="project-preview">
      <div class="project-picture">
        <img class="mySlides_05" src="Pictures/16.png"/>
        <img class="mySlides_05" src="Pictures/17.png"/>
        
        <button class="w3-button w3-black w3-display-left" onclick="plusDivs_05(-1)">
          &#10094;
          </button>
          <button class="w3-button w3-black w3-display-right" onclick="plusDivs_05(1)">
          &#10095;
          </button>
          <script>
            var slideIndex = 1;
              showDivs_05(slideIndex);
              
              function plusDivs_05(n) {
              showDivs_05((slideIndex += n));
              }
              
              function showDivs_05(n) {
              var i;
              var x = document.getElementsByClassName("mySlides_05");
              if (n > x.length) {
              slideIndex = 1;
              }
              if (n < 1) {
              slideIndex = x.length;
              }
              for (i = 0; i < x.length; i++) {
              x[i].style.display = "none";
              }
              x[slideIndex - 1].style.display = "block";
              }
          </script>
      </div>

      <div class="project-description">
        <h2>
          Forward Kinematics Model for TURIN TKB1210 Industrial Scale Robotic Manipulator.</h2>
        <p>
          This mathematical model has developed to design the industrial manipulators for Sri Lankan 
industries without importing. The simulation model has successfully tested. TURIN TKB1210 
Robotic manipulator was imitated for the designing. </p>

<br />
        <button type="button" onclick="location.href='https://drive.google.com/file/d/1Vynb2yvJ1BkHrNkxisAiPXphysTfYHD2/view?usp=sharing'">Video</a></button>
        
      </div>
    </div>
    <br/><hr>


    <!-- sixth one-->

    <div class="project-preview">
      <div class="project-picture">
        <img class="mySlides_06" src="Pictures/ss01.png"/>
        <img class="mySlides_06" src="Pictures/ss02.png"/>
        <img class="mySlides_06" src="Pictures/ss03.png"/>
        <img class="mySlides_06" src="Pictures/ss04.png"/>
        <img class="mySlides_06" src="Pictures/ss05.png"/>
        
        <button class="w3-button w3-black w3-display-left" onclick="plusDivs_06(-1)">
          &#10094;
          </button>
          <button class="w3-button w3-black w3-display-right" onclick="plusDivs_06(1)">
          &#10095;
          </button>
          <script>
            var slideIndex = 1;
              showDivs_06(slideIndex);
              
              function plusDivs_06(n) {
              showDivs_06((slideIndex += n));
              }
              
              function showDivs_06(n) {
              var i;
              var x = document.getElementsByClassName("mySlides_06");
              if (n > x.length) {
              slideIndex = 1;
              }
              if (n < 1) {
              slideIndex = x.length;
              }
              for (i = 0; i < x.length; i++) {
              x[i].style.display = "none";
              }
              x[slideIndex - 1].style.display = "block";
              }
          </script>

      </div>

      <div class="project-description">
        <h2>
         Three Axis Cartesian Robot for High-Speed Stampings.
        </h2>
        <p>
          Kasun Kalhara modelled a 3axis Cartesians Robot. This cartesian robot has been modeled to 
implement the high-speed stamping on a sealing sheet. 3 servo motors are performing the task 
by reducing the unnecessary movements.</p>
        
      </div>
    </div>
    <br/><hr>

    <!-- seventh one-->
    <div class="project-preview">
      <div class="project-picture">
        <img class="karadiyana" src="Pictures/14.png"/>
        
      </div>

      <div class="project-description">
        <h2>
          Tube Climbing Robot</h2>
        <p>
          Kasun Kalhara innovated a cost-effective robotic mechanism for climbing inside a vertical 
pipe, this pipe task has been given by university to evaluate the mechatronics product design
course module.
 </p>

<br />
        <button type="button" onclick="location.href='https://drive.google.com/file/d/1BOobyBnGxmZlhqk01ve4tEUc3MDujTii/view?usp=sharing'">Video</a></button>
        
      </div>
    </div>
    <br/><hr>

    <!-- eight one-->
    <div class="project-preview">
      <div class="project-picture">
        <img class="karadiyana" src="Pictures/13.JPG"/>
        
      </div>

      <div class="project-description">
        <h2>
          Quad Copter for Pick and Place Applications</h2>
        <p>
          Kasun Kalhara designed a quad copter for perform pick and place tasks. Re-designed the 
structure of the classical quad copter frame to increase the performance and play load.

 </p>

<br />
        <button type="button" onclick="location.href='https://drive.google.com/file/d/1eTpkWGeNpEKOo5OHj_q8yE1mMKD3JQfG/view?usp=sharing'">Video</a></button>
        
      </div>
    </div>
    <br/><hr>

  <div class="academic">
    <h2 class="related">Academic related videos (2021)</h2>
    <p><b>Control System Engineering Laboratory Demonstration Videos.</b></p>
    <p>In COVID 19 period, the control system laboratory course module was conducted by video-based sessions. In that case, all the laboratory tasks were recorded and delivered to the students
      via online platforms. Kasun Kalhara demonstrated and delivered SIMO systems and MIMO 
      control systems laboratory sessions by creating the attractive video series.</p>
  </div>
      <!--Youtube lessons 01-->
      <div class="project-preview">
        <div class="project-picture">
          <iframe width="450" height="300" src="https://www.youtube.com/embed/UR5qFa-heu0" class="karadiyana">
          </iframe>
          
        </div>
  
        <div class="project-description">
          <h2>
            Digital Pendulum Control Experiment.
          </h2>
          <p>
            Instructed and created By: R.A.K.K.Perera</p> <br/> <br/>

          <p>(For more videos please visit my <a href="https://youtube.com/@mechatube1270" target="_blank">YouTube</a> channel)</p>
          
        </div>
      </div>
      <br/><hr>

      <!--Youtube lessons 02-->
      <div class="project-preview">
        <div class="project-picture">
          <iframe width="450" height="300" src="https://www.youtube.com/embed/1vr9qMT5iT4" class="karadiyana">
          </iframe>
          
        </div>
  
        <div class="project-description">
          <h2>
            Magnetic Levitation Control Experiment.
          </h2>
          <p>
            Instructed and created By: R.A.K.K.Perera</p> <br/> <br/>

            <p>(For more videos please visit my <a href="https://youtube.com/@mechatube1270" target="_blank">YouTube</a> channel)</p>
          
        </div>
      </div>
      <div class="foot">
        <footer>
          <p class="mail">©<a href="mailto:kalhara95k@gmail.com">Kasun Kalhara</a> | All Rights Received.</p>
        </footer>
      </div>
      
     
  </body>
</html>

