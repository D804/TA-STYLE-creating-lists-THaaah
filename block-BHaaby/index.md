- Create a layout according to the design shown below.

![Creating lists Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/lists/ex-1.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Work on typography in detail.
<!--HTML CODE-->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Creating list</title>
    <!---Google font-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
     <link href="https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,500;0,600;0,700;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="assets/stylesheet/style.css">
    <!--Font Awesome-->
    <script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script>
    </head>
  <body>
    <header class="navigation">
        <div class="container">
           <nav class="nav">
                <ul class="flex justify-content">
                   <li>
                      <a href="#">home</a>
                   </li>
                   <li>
                      <a href="#">about</a>
                   </li>
                   <li>
                      <a href="#">faqs</a>
                   </li>
                   <li>
                      <a href="#">program</a>
                  </li>
                  <li>
                     <a href="#">contact</a>
                  </li>
               </ul>
          </nav>
       </div>
    </header>
    <main>
        <section class="section padding">
            <div class="container flex align-stretch">
                <div class="box  ">
                    <ol>
                        <li>home</li>
                        <li>page</li>
                        <li>about us</li>
                        <li>portfolio</li>
                        <li value="20">pricing</li>
                        <li>news</li>
                        <li>testimonia</li>
                        <li>contact us</li>
                    </ol>
                </div>
                <div class="box list">
                    <ul>
                        <li>home</li>
                        <li>menu
                            <ol>
                                <li>menu 1
                                    <ul class="list-style">
                                    <li>sub menu 1</li>
                                    <li>sub menu 2</li>
                                </ul>
                                <li>menu 2</li>
                                <li>menu 3</li>
                                <li>menu 4</li>
                                <li>menu 5</li>
                                </li>
                            </ol>
                        </li>
                        <li>how we work</li>
                        <li>about us</li>
                        <li>contact us</li>
                    </ul>
                </div>
                <div class="box check">
                   <ol>
                       <li>
                          <i class="fas fa-check-circle"></i>
                           home
                       </li>
                       <li>
                           <i class="fas fa-check-circle"></i>
                           page
                       </li>
                       <li>
                           <i class="fas fa-check-circle"></i>
                            services
                       </li>
                       <li>
                           <i class="fas fa-check-circle"></i>
                            about us
                       </li>
                       <li>
                           <i class="fas fa-check-circle"></i>
                           portfolio
                       </li>
                       <li>
                          <i class="fas fa-check-circle"></i>
                           pricing
                       </li>
                       <li>
                           <i class="fas fa-check-circle"></i>
                           news
                       </li>
                       <li>
                           <i class="fas fa-check-circle"></i>
                           testimonia
                      </li>
                      <li>
                          <i class="fas fa-check-circle"></i>
                           contact us
                      </li>
                   </ol> 
                </div>
            </div>
        </section>
        <section>
            <div class="container">
              <dl>
                  <dt>what is lorem ipsum?</dt>
                  <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore sunt deserunt incidunt ratione animi suscipit odio fuga recusandae maiores adipisci dolores dolore dignissimos, repudiandae id odit impedit quasi doloribus quia
                     Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore sunt deserunt incidunt ratione animi suscipit odio fuga recusandae maiores adipisci dolores dolore dignissimos, repudiandae id odit impedit quasi doloribus quia</dd>
                  </dd>
               
                  <dt>why do we use it?</dt>
                  <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore sunt deserunt incidunt ratione animi suscipit odio fuga recusandae maiores adipisci dolores dolore dignissimos, repudiandae id odit impedit quasi doloribus quia
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore sunt deserunt incidunt ratione animi suscipit odio fuga recusandae maiores adipisci dolores dolore dignissimos, repudiandae id odit impedit quasi doloribus quia</dd>
                  </dd>
               
                  <dt>lorem ipsum <br>
                        dummy text</dt>
                  <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore sunt deserunt incidunt ratione animi suscipit odio fuga recusandae maiores adipisci dolores dolore dignissimos, repudiandae id odit impedit quasi doloribus quia
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore sunt deserunt incidunt ratione animi suscipit odio fuga recusandae maiores adipisci dolores dolore dignissimos, repudiandae id odit impedit quasi doloribus quia</dd>
                  </dl>
            </div>
        </section>
    </main>
    <footer class="navigation footer">
       
        <div class="container">
            <nav class="nav">
                <ul class="flex justify-content">
                    <li>
                        <a href="#">home</a>
                    </li>
                    <li>
                        <a href="#">about</a>
                    </li>
                    <li>
                        <a href="#">faqs</a>
                    </li>
                    <li>
                        <a href="#">program</a>
                    </li>
                    <li>
                        <a href="#">contact</a>
                    </li>
                </ul>
            </nav>
        </div>
        
    </footer>
  </body>
</html>
