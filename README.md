<div align="center">
<img width=600 src="https://www.defensenews.com/resizer/8QfEfijKyi5oJzflfuRRfyUobh8=/1024x0/filters:format(jpg):quality(70)/cloudfront-us-east-1.images.arcpublishing.com/archetype/QPVEISVJEJGSFBFCV2FQR3XZAQ.jpeg" /> 

  <div>
<a href="https://www.linkedin.com/in/george-arvanitis-b25367280/" target="_blank">
<img width=70 src="https://img.shields.io/badge/linkedin-blue"/> 
</a> 

<a href="https://www.youtube.com/channel/UCJIZe9277-JD9GGzMVaXvfA" target="_blank"> 
<img width=70 src="https://img.shields.io/badge/youtube-red"/> 
</a> 
</div>

![](https://komarev.com/ghpvc/?username=georgerv85-github-username&style=flat-square)
</div>

---

### 👮 About me: 

- <ins>**I work as Airspace Defense Officer At Hellenic Air Force  <img width=30 src="https://yened.files.wordpress.com/2012/12/ceb3ceb5ceb1-small.jpg?w=388&h=400&crop=1" /> and i am Junior Web Developer**<ins>
            <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-original.svg" /> 
            <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/woocommerce/woocommerce-original.svg" />
            <img width=40 height=30 src="https://w7.pngwing.com/pngs/914/758/png-transparent-github-social-media-computer-icons-logo-android-github-logo-computer-wallpaper-banner-thumbnail.png" /> <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain-wordmark.svg" /> <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />  <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" /> <img width=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" />
         
- *I have:*
  
 1. Over 16 years expierence as Tactical Control Officer of Patriot Air and Missile Defense System <img width=30 src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQe_PQWIhtKjaFDtWvga82BhOO1_k4iOXpLAGRIvmc2cnzsXj09KcoCtYCGUJgJk8NN4eU&usqp=CAU">
 2. two years expirence as Pilot at Hellenic Air Force
 3. two years experience as Air Traffic Controller
 4. two years expirience as Instructor of Fighter Weapon School (Air Tactics Center)
 5. Over 3 years as Lecturer of Hellenic Air Force NCO Academy
 6. Over 8 years Chief Of Τraining and Standardization at Patriot Air and Missile Defense System
  

 - <ins>**education and courses:**<ins>

   1. I graduated from Hellenic Air Force Academy
   3. Αccident Prevention Officer (course)
   4. Air Traffic Controller (course)
   5. Patriot Air and Missile Defense (course)
   6. Ground Instructor (course)
   7. Interdisciplinary Air Defense School (course)
   8. Εnergy and Εnvironmental Μanagement of Αrmed Forces Units (course)
    
 - <ins>**Web Developer (current courses**)<ins>
 
   - [x] <ins>**Completed<ins>**: <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-original.svg" /> 
            <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/woocommerce/woocommerce-original.svg" /> <img width=40 height=30 src="https://w7.pngwing.com/pngs/914/758/png-transparent-github-social-media-computer-icons-logo-android-github-logo-computer-wallpaper-banner-thumbnail.png" /> <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain-wordmark.svg" /> <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" /> <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" /> <img width=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" /> <img width=30 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-plain.svg" />  
   - [ ] <ins>**In progress courses<ins>**: Angular-js
             
   
  ---

  💻 My stats
    
  [![GitHub Streak](https://streak-stats.demolab.com?user=georgerv85)](https://git.io/streak-stats) 

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=georgerv85&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats) 

---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solar Sistem</title>
    <link rel="shortcut icon" href="../favicon.png" type="image/x-icon" />
    <style>
        body{
            margin: 0;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            background-color: black;
            overflow: hidden;
        }
        .container{
            font-size: 10px;
            width: 40em;
            height: 40em;
            position: relative;
        }
        .sun{
            position: absolute;
            top: 15em;
            left: 15em;
            width: 10em;
            height: 10em;
            background-color: yellow;
            border-radius: 50%;
            box-shadow: 0 0 3em white;
        }
        .earth, .moon{
            position: absolute;
            border-style: solid;
            border-color: white transparent transparent transparent;
            border-width: 0.1em 0.1em 0 0;
            border-radius: 50%;
        }
        .earth{
            top: 5em;
            left: 5em;
            width: 30em;
            height: 30em;
            animation: orbit 36.5s linear infinite;
        }
        .moon{
            top: 0;
            right: 0;
            width: 8em;
            height: 8em;
            animation: orbit 2.7s linear infinite;
        }
        .earth::before, .moon::before{
            content: ''; 
            position:absolute;
            border-radius: 50%;
        }
        .earth::before{
            top: 2.8em;
            right: 2.8em;
            width: 3em;
            height: 3em;
            background-color: aqua;            
        }
        .moon::before{
            top: 0.8em;
            right: 0.2em;
            width: 1.2em;
            height: 1.2em;
            background-color: silver;      
        }
        @keyframes orbit {
            to{ transform: rotate(360deg);}
        } 

        /* Footer */
        footer{
            color:#fff;
            font-size: 3rem;
        }


    </style>
</head>
<body>
    <div class="container">
        <div class="sun"></div>
        <div class="earth">
            <div class="moon"></div>
        </div>
    </div>

    <footer>
        
    </footer>
    
</body>
</html>
