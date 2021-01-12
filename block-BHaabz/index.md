- Create a layout according to the design shown below.

![Creating lists Assignment level 2](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/lists/ex-2.png)

**Dropdown Menu**

![Creating lists Assignment level 2](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/lists/ex-2-dropdown.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Work on typography in detail.
<!--- HTML code--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>creating list</title>
    <script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script>
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap" rel="stylesheet">
   
</head>
<body>
    <header class="header">
        <div class=" container flex">
            <a class="logo"href="#">ELEVATION</a>
            <nav>
                <ul class="flex">
                    <li>
                        <a href="#">Home</a>
                    </li>
                    <li>
                        <a href="#">Pagelayouts</a>
                    </li>
                    <li>
                        <a href="#">Elements</a>
                    </li>
                </ul> 
            </nav>
        </div>
    </header>
    <main>
     <section class="hero">
        <div class="container ">
            <h1>LOREM IPSUM DOLOR</h1>
            <h2>Sed lorem consequat feugiat</h2>
            <a class="btn hero-btn"href="#">MAGNA SED ETIAM</a>

        </div>
    
    </section>
    <section class="section padding">
        <div class="container ">
            <header>
        <h3 class="heading">magna feugiat</h3>
        <p class="paragraph">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
             praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
           
             beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
   
        </p>
    </header>
    <div class="flex">
     <div class="col-1 section-padding">
         <div class="profile">
            <i class="fas fa-user"></i>
         </div>
         <h4>aliquam tinci</h4>
         <p>Lorem ipsum dolor sit amet consectetur 
            adipisicing elit. Architecto dolorum vel,
            dolor ex eum libero vero ull voluptate tenetur.
        </p>

     </div>
     <div class="col-1 section-padding">
        <div class="profile">
           <i class="fas fa-user"></i>
        </div>
        <h4>aliquam tinci</h4>
        <p>Lorem ipsum dolor sit amet consectetur 
           adipisicing elit. Architecto dolorum vel,
           dolor ex eum libero vero ull voluptate tenetur.
       </p>

    </div>
    <div class="col-1 section-padding">
        <div class="profile">
           <i class="fas fa-user"></i>
        </div>
        <h4>aliquam tinci</h4>
        <p>Lorem ipsum dolor sit amet consectetur 
           adipisicing elit. Architecto dolorum vel,
           dolor ex eum libero vero ull voluptate tenetur.
       </p>

    </div>
   </div>
        </div>
    </section>
    <section class="section padding">
        <div class="container ">
            <header>
        <h3 class="heading">magna feugiat</h3>
        <p class="paragraph">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
             praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
           
             beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
   
        </p>
    </header>
    <div class="flex-b">
        <div class="col-1 section-padding">
            <div class="profile">
               <i class="fas fa-user"></i>
            </div>
            <h4>aliquam tinci</h4>
            <p>Lorem ipsum dolor sit amet consectetur 
               adipisicing elit. Architecto dolorum vel,
               dolor ex eum libero vero ull voluptate tenetur.
           </p>
           <!---<div class="flex">
            <div class="col-1 section-padding">
                <div class="profile">
                   <i class="fas fa-user"></i>
                </div>
                <h4>aliquam tinci</h4>
                <p>Lorem ipsum dolor sit amet consectetur 
                   adipisicing elit. Architecto dolorum vel,
                   dolor ex eum libero vero ull voluptate tenetur.
               </p>
       
   



       <!---
           <div class="flexbox">
          <div class="profile-box ">
        <h3>magna feugiat</h3>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
             praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
           
             beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
   
        </p>
   
    </div>
      
    <div class="profile-box ">
        <h3>magna feugiat</h3>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
             praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
           
             beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
   
        </p>
  
    </div>
      
    <div class="profile-box ">
        <h3>magna feugiat</h3>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
             praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
           
             beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
   
        </p>
    </div> 
   
    </div>
        </div>
               
    </section>
    <section class="function-section">
        <div class="container">
            <h3>magna feugiat</h3>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
             praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
           
             beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
   
        </p>
        <div>
            <div class="seeting-box ">
                <h3>magna feugiat</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
                     praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
                   
                     beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
           
                </p>
        </div>
        <div class="seeting-box ">
            <h3>magna feugiat</h3>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
                 praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
               
                 beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
       
            </p>
    </div>
    <div class="seeting-box ">
        <h3>magna feugiat</h3>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
             praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
           
             beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
   
        </p>
    </div>
    <div class="seeting-box ">
        <h3>magna feugiat</h3>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam voluptate officia
             praesentium error incidunt ipsa, soluta natus quisquam sapiente ipsam
           
             beatae suscipit temporibus. Harum accusantium iure natus amet reprehenderit repudiandae!
   
        </p>
</div>--->
        </div>

    </section>
</main> 
    
</body>
</html>
