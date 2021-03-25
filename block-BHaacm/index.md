writeCode

- Create a responsive layout according to the design shown below.

#### Large Screen view(Above 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-1-desktop-view.png)

#### Small Screen view(Below 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-1-mob-view.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Pay attention to the codes, your code quality matters a lot.

- Try to implement the layout as exactly as it has been provided in the design.

- Pay attention to minor things like spacing, alignment, size, etc.

- Use any font-family which suits better for the assignment.

- Once you are done with the assignment connect with the mentor and get the code reviewed.
<!--HTML-->
<!DOCTYPE html>
<html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive</title>
    <link rel="stylesheet" href="assets/stylesheet/style.css">
    <!--Font Awesome-->
    <script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script>
    <!--Font-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet"> 

 </head>
 <body>
    <header class="header center padding">
        <div class="container flex ">
            <a href="#"><img src="assets/media/logo.png" alt="loading error"></a>
            <nav class="nav">
                <ul class="flex">
                    <li><a href="#">home</a></li>
                    <li><a class="active" href="#">blog</a></li>
                    <li><a href="#">about</a></li>
                    
                </ul>
            </nav>
        </div>
    </header>  
    <main>
        <section class="article padding">
            <article>
                <div class="container flex direction alignment">
                    <div class="flex-48">
                        <img class="img-width" src="assets/media/01.png" alt="loading error">
                    </div>
                    <div class=" flex-48">
                      <h2>what is lorem ipsum ?</h2>
                      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Unde mollitia enim, voluptates quasi, voluptate molestias itaque rem error commodi, illum maxime repellendus totam? Sed repudiandae minus in,illum maxime repellendus totam? Sed repudiandae minus in voluptate molestias itaque rem error minus in voluptate molestias itaque rem error .</p>
                      <a class="btn primary-btn" href="#">Read More</a>
                    </div>
                </div> 
            </article>
        </section>
        <section>
            <div class="container">
                <h3>Our Blog</h3>
                <div class="flex alignment">
                    <div class="flex-30">
                      <img class="img-width" src="assets/media/02.png" alt="loading error">
                      <h4>Why do we use it ?</h4>
                      <p class="para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem harum aliquid est nihil ratione vel architecto earum ut illum consequatur  </p>
                      <a class="btn secondary-btn" href="#">Read More</a> 
                    </div>
                    <div class="flex-30">
                      <img class="img-width" src="assets/media/03.png" alt="loading error">
                      <h4>Where does it come from ?</h4>
                      <p class="para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem harum aliquid est nihil ratione vel architecto earum ut illum consequatur .</p>
                      <a class="btn secondary-btn" href="#">Read More</a> 
                    </div>
                    <div class="flex-30">
                       <img class="img-width" src="assets/media/04.png" alt="loading error">
                       <h4>Where can i get some ?</h4>
                       <p class="para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem harum aliquid est nihil ratione vel architecto earum ut illum consequatur .</p>
                       <a class="btn secondary-btn" href="#">Read More</a> 
                    </div>
                </div>
        </section>
    </main> 
    <footer class="footer padding">
        <div class="container center flex">
            <small>&copy;Alt Campus</small>
            <div class="icon">
              <i class="fab fa-facebook-square"></i>
              <i class="fab fa-twitter-square"></i>
            </div>
        </div>
    </footer>
 </body>
</html>
