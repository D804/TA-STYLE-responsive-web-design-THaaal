writeCode

- Create a responsive layout according to the design shown below.

#### Large Screen view(Above 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-2.png)

#### Small Screen view(Below 768px)

1. Figure what would be the best possible way to display the layout on small screens.

2. Create hmaburger icon to toggle menu on mobile view.

- Using CSS resets is necessary.
- Use semantic tags and keep the nesting and indentation proper.
- Pay attention to the codes, your code quality matters a lot.
- Try to implement the layout as exactly as it has been provided in the design.
- Pay attention to minor things like spacing, alignment, size, etc.
- Use "Nunito" font-family for the assignment.
- Figure out the best possible way to display the layout on small screens.
- Create hmaburger icon to toggle menu on small screen view.
- Once you are done with the assignment connect with the mentor and get the code reviewed.
<!--HTML-->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>assignment-2</title>
    <!--Css Link-->
    <link rel="stylesheet" href="assets/stylesheet/style.css">
    <!--Font Family-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200;0,300;0,400;0,600;0,700;0,800;0,900;1,200;1,300;1,400;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <!--Font Awesome--> 
    <script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script> 
</head>
  <body>
    <header class="header padding">
        <div class="container flex align-center">
            <a class="brand" href="#">Alt Events</a>
            <nav class="nav">
                <ul class="flex">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Service</a></li>
                    <li><a href="#">Contact</a></li>
                    <li><a class="btn" href="#">join Us</a></li>

                </ul>
            </nav>
            
        </div>
    </header>
    <main>
        <secion class="hero">
            <div class="container flex align">
                <div class="flex-46">
                    <h1 class="padding-bottom">Web Developer Conference<strong>2020</strong> </h1>
                    <p class="para padding-bottom">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deleniti doloribus minima accusantium, consequatur illum atque, neque  </p>
                    <a class="btn primary-btn " href="#">Register Now</a>
                </div>
                <div class="flex-46 font-0">
                    <img class="width-full img" src="assets/media/hero.png" alt="Loading error">
                </div>
           
                
            </div>
            
        </secion>
        <section class="padding">
            <article class="container flex align-center">
                <div class="flex-46">
                    <img class="width-full" src="assets/media/about.png" alt="About">
                </div>
                <div class="flex-46 ">
                    <h2 class="about-heading padding-bottom">about the event</h2>
                    <p class="para primary padding-bottom">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Facilis tempore, fugit iusto dolores necessitatibus veniam illo facere quas magni! .</p>
                    <a class="btn primary-btn" href="#">Know More</a>
                </div>
            </article>
        </section>
        <section class="join padding">
            <div class="container">
                <h3> why you should join </h3>
                <div class="flex">
                   
                    <div class="flex-30 border">                 
                        <h4>Network</h4>
                        <p class="join-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias ratione excepturi porro ducimus! Explicabo soluta mollitia, aliquam </p>
                    
                    </div>
                     <div class="flex-30 border">                 
                         <h4>Great Speakers</h4>
                         <p class="join-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias ratione excepturi porro ducimus! Explicabo soluta mollitia, aliquam</p>
                      </div>
                      <div class="flex-30 border">                 
                         <h4>Information</h4>
                         <p class="join-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias ratione excepturi porro ducimus! Explicabo soluta mollitia, aliquam</p>
                      </div>
                </div>
                

            </div>
        </section>
        <section>
           
            <div class="container schedule">
                <h3 class="padding-bottom">schedule</h3>
                <div class="flex">   
                    <div class="flex-10 center border-date">
                        <div class="schedule-date">
                          <h5>06<br> Sept</h5>
                        </div>
                        <div class="schedule-date">
                           <h5>07<br>Sept</h5>
                        </div>
                        <div class="schedule-date">
                          <h5>08<br> Sept</h5>
                        </div>
                    </div>
                        <div class="flex-20">
                            <div class="padding-bottom">
                             <img class="width-full" src="assets/media/schedule-01.jpg" alt="Loading error">
                            </div>
                            <div  class="padding-bottom">
                              <img class="width-full" src="assets/media/schedule-02.jpg" alt="Loading error">
                            </div>
                            <div  class="padding-bottom">
                               <img class="width-full"src="assets/media/schedule-03.jpg" alt="Loading error">
                            </div>
                            <div  class="padding-bottom">
                              <img class="width-full"src="assets/media/schedule-04.jpg" alt="Loading error">
                            </div>
                        </div>
                        <div class="flex-55">
                          <div class="schedule-bottom">
                             <h4>Digital World Event Conversation</h4>
                             <p class="para primary">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam hic totam nam vel? Obcaecati dicta ipsam</p>
                          </div>
                          <div class="schedule-bottom">
                            <h4>Digital World Event Conversation</h4>
                            <p class="para primary">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam hic totam nam vel? Obcaecati dicta ipsam provident</p>
                         </div>
                         <div class="schedule-bottom">
                            <h4>Digital World Event Conversation</h4>
                            <p class="para primary">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam hic totam nam vel? Obcaecati dicta ipsam provident</p>
                         </div>
                         <div class="schedule-bottom">
                            <h4>Digital World Event Conversation</h4>
                            <p class="para primary">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam hic totam nam vel? Obcaecati dicta ipsam provident</p>
                         </div>
                         <a class="btn primary-btn" href="#">Download Schedule</a>
                        </div>
                    </div>
                </div> 
            
            </div>
        </section>
        <section class="activity">
            <div class="container flex center activity-">
                <div class="flex-20 ">
                    <img class="width-full" src="assets/media/speaker.png" alt="Loading error">
                    <div>
                        <strong>20+</strong>
                        <h5>Great Speakers</h5>
                    </div>
                  

                </div>
                <div class="flex-20  idea">
                    <img class="width-full" src="assets/media/speaker.png" alt="Loading error">
                    <div class="">
                        <strong>20+</strong>
                        <h5>Great Speakers</h5>
                    </div>
                </div>
                <div class="flex-20 ">
                    <img class="width-full" src="assets/media/speaker.png" alt="Loading error">
                    <div>
                        <strong>20+</strong>
                        <h5>Great Speakers</h5>
                    </div>
                </div>
                <div class="flex-20 ">
                    <img class="width-full" src="assets/media/speaker.png" alt="Loading error">
                    <div>
                        <strong>20+</strong>
                        <h5>Great Speakers</h5>
                    </div>
                </div>


            </div>
        </section>
        <section class="padding">
            <div class="container embeded">
               <div class="media-button center">
                 <i class="fas fa-play"></i>
               </div>
            </div>
        </section>
        <section class="news padding">
            <div class="container ">
                <div class=" center">
                    <h3 class="padding-bottom">Our Latest News</h3>
                </div>
                <div class="flex">
                    <div class="flex-31">
                        <img class="width-full" src="assets/media/news-01.png" alt="Loading error">
                        <h6>How to build a great portfolio as a beginner devloper</h6>
                        <p class="news-para primary">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Asperiores in perspiciatis possimus laudantium quis illo iusto saepe velit, architecto quasi, </p>
                        <a href="#">Read More</a>
                    </div>
                    <div class="flex-31">
                        <img class="width-full" src="assets/media/news-02.png" alt="Loading error">
                        <h6>4 common situations while using Git and how to solve them</h6>
                        <p class="news-para primary">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Asperiores in perspiciatis possimus laudantium quis illo iusto saepe velit, architecto quasi, </p>
                        <a class="news-info" href="#">Read More</a>
                    </div>
                    <div class="flex-31">
                        <img class="width-full" src="assets/media/news-03.png" alt="Loading error">
                       
                        <h6>Basic Unix commands that you should know</h6>
                        <p class="news-para primary">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Asperiores in perspiciatis possimus laudantium quis illo iusto saepe velit, architecto quasi, </p>
                        <a href="#">Read More</a>
                    </div>

                </div>

            </div>
        </section>
        
    </main>
    <footer>
        <div class="foot">
            <div class="container flex padding">
                <div>
                    <img src="assets/media/footer-logo.png" alt="Loading error">
                </div>
                <div class="flex-40">
                   <strong>Quick Links</strong>
                   <nav>
                    <ul class="flex">
                       <a href="#"><li>Program</li></a> 
                       <a href="#"><li>About Us</li></a>
                       <a href="#"><li>Contact Us</li></a>
                       <a href="#"><li>Services</li></a>
                    </ul>
                   </nav>
                </div>
                <div class="flex-20">
                    <strong>Follow Us</strong>
                    <div>
                        <i class="fab fa-facebook-square"></i>
                        <i class="fab fa-twitter-square"></i>
                    </div>
                   
                </div>
            </div>
            <div class="copyright center">
                <small>&copy;AltCampus Services Pvt Ltd,2018-Present</small>
            </div>
          
        </div>
        
    </footer>
  </body>
  </html>
