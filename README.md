<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meet the Team</title>
    <link rel="stylesheet" href="./mtt_styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap" rel="stylesheet">
  <style>
    *{
    text-decoration: none;
    margin: 0;
    padding: 0;
    font-family: 'poppins', Calibri;
    box-sizing: border-box;
}
/* styles for the h1 */

 h1{
    text-align: center;
    font-size: 30px;
    margin: 13.2%;
}
/* the mother container effects */
.meettheteam-container{
    margin:15%;
    padding: 5%;
}

:root{
    --membernamefontsize: 150%;
    --memberpositioncolor: navy;
}

/* effects for each member's box */
.team-details{
    text-align: center;
}

.member-name{
    font-size: var(--membernamefontsize);
    font-weight: bold;
    font-family: Calibri;
}

.member-position{
    font-size: 70%;
    color: var(--memberpositioncolor);
    font-weight: bold;
}

/* set ayo's position font size */
#ayo{
    font-size: 60%;
}

button{
    width: 200px;
    height: 30px;
    background-color: blue;
    color: white;
    font-size: larger;
    font-family: Calibri;
    border-radius: 15px;
    margin-bottom: 83px;
    outline: none;
    cursor: pointer;
}

.member-location{
    font-family: calibri;
    font-size: 85%;
}
/* set the image border to round */
img{
    border-radius: 100%;
}
/* make the image glow on hover */
img:hover{
    animation-name: glow;
    animation-duration: 5s;
    animation-iteration-count: infinite;
}

/* define the animation called glow */
@keyframes glow {
    25% {box-shadow: 15px 8px 15px gold;}
    50% {box-shadow: 15px 8px 15px goldenrod;}
    55% {box-shadow: 15px 8px 13px rgb(236, 233, 36);}
    100% {box-shadow: 15px 10px 14px orange;}

}

/* make the button glow on hover */
button:hover{
    animation-name: shineBright;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    box-shadow: 3px 5px 4px purple;
    color: olive;
}

/* define the animation named shineBright */
@keyframes shineBright{
    0% {background: navy;}
    25% {background: purple;}
    50% {background: violet;}
    55% {background: pink;}
    100% {background: plum;}
}

/* effects for when the screen is more than 950px */
@media(min-width:950px){
    .meettheteam-container{
        max-width: 1075px;
        display: flex;
        flex-flow: row wrap;
        justify-content: space-between;
        margin: 0 9%;
    }

   .team-details{
        width: 28.42%;
    }

   h1{
        margin-top: 20px;
        margin-bottom: 28px;
        font-family: Calibri;
    }
}
  </style>
</head>
<body>
    <h1>Meet The Team</h1>
    <div class="meettheteam-container">
        <div class="team-details">
            <img src="./images/daniel_headshot.png" alt="Daniel Sumah's picture">
            <p class="member-name">Daniel Sumah</p>
            <p class="member-position">Founder | Web Development Tutor</p>
            <p class="member-location">University of Lagos, Akoka</p>
            <a href="https://www.linkedin.com/mwlite/in/daniel-sumah-44796368" target="_blank"><button>View on LinkedIn</button></a>
        </div>

   <div class="team-details">
            <img src="./images/promise.png" alt="Promise Shittu's picture">
            <p class="member-name">Promise Shittu</p>
            <p class="member-position">CoFounder | Python Tutor</p>
            <p class="member-location">Obafemi Awolowo University, Ife</p>
            <a href="https://www.linkedin.com/in/promise-shittu-436951124" target="_blank"><button>View on LinkedIn</button></a>
        </div>

  <div class="team-details">
            <img src="./images/zion.png" alt="Zion Shittu's picture">
            <p class="member-name">Zion Shittu</p>
            <p class="member-position">Public Relations Officer</p>
            <p class="member-location">Obafemi Awolowo University, Ife</p>
            <a href="https://www.linkedin.com/in/zion-shittu-9703011a1" target="_blank"><button>View on LinkedIn</button></a>
        </div>


   <div class="team-details">
            <img src="./images/ayo-headshot.png" alt="Ayodeji Areago's picture">
            <p class="member-name">Ayodeji Areago</p>
            <p class="member-position" id="ayo">Brand Manager | Graphic Design Tutor</p>
            <p class="member-location">Obafemi Awolowo University, Ife</p>
            <a href="https://www.linkedin.com/in/ayodeji-areago-a6a33611b" target="_blank"><button>View on LinkedIn</button></a>
        </div>


   <div class="team-details">
            <img src="./images/precious-headshot.png" alt="Precious Asunmo's picture">
            <p class="member-name">Precious Asunmo</p>
            <p class="member-position">Public Relations Officer</p>
            <p class="member-location">Obafemi Awolowo University, Ife</p>
            <a href="https://www.linkedin.com/in/precious-asunmo-7349251a2" target="_blank"><button>View on LinkedIn</button></a>
        </div>


   <div class="team-details">
            <img src="./images/chidera-headshot.png" alt="Chidera Umeadi's picture">
            <p class="member-name">Chidera Umeadi</p>
            <p class="member-position">Web Developer</p>
            <p class="member-location">University of Lagos, Akoka</p>
            <a href="https://www.linkedin.com/in/chidera-umeadi-76a9751a6" target="_blank"><button>View on LinkedIn</button></a>
        </div>


        
   </div>
</body>
</html>
