- Create a layout according to the design shown below.

![Creating lists Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/lists/ex-1.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Work on typography in detail.
<!-------HTML CODE-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
   <link rel="stylesheet" href="style.css">
   <link rel="preconnect" href="https://fonts.gstatic.com">
   <link href="https://fonts.googleapis.com/css2?family=Lato&family=Roboto:wght@300&display=swap" rel="stylesheet">
    <title>Creating list</title>
</head>
<body>
    <header>
        <div class="container ">
            <nav class="nav-background ">
                <ul class="flex">
                    <li>
                        <a href="#">Home</a>
                    </li>
                    <li>
                        <a href="#">About</a>
                    </li>
                    <li>
                        <a href="#">Faqs</a>
                    </li>
                    <li>
                        <a href="#">Program</a>
                    </li>
                    <li>
                        <a href="#">Contact</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
    <main class="inner-body">
        <section>
            <div class="container">
            <div class=" box ">
                <ol class="list-style">
                    <li>Home</li>
                    <li>menu</li>
                    <li>Services</li>
                    <li>About us</li>
                    <li>Portfolio</li>
                    <li value="20">Pricing</li>
                    <li>News</li>
                    <li>Testimonia</li>
                    <li>Contact Us</li>

                </ol>
            </div>
            <div class="box unorder-box">
                <ul class="list-style-2 ">
                    <li>Home</li>
                    <li>
                        Menu
                    <ol>
                        <li>
                            Menu 1
                            <ol>
                                <li>Sub Menu 1</li>
                                <li>Sub Menu 2</li>
                            </ol>

                          <li>Menu 2</li>
                          <li>Menu 3</li>
                          <li>Menu 4</li>
                          <li>Menu 5</li>
                          </li>
                        </li>
                    </ol>
                </li>
                          
                    
                     <li>How we work</li>
                     <li>About us</li>
                     <li>Contact Us</li>
                          </ul>
                        </li>
                      <li>Menu 2</li>
                      <li>Menu 3</li>
                      <li>Menu 4</li>
                      <li>Menu 5</li>
                    <li>How We Work</li>
                    <li>About us</li>
                    <li>Contact Us</li>

                </ul>
            </div>
            <div class="box image-box">
                <ol class="list-style-none ">
                    <li> <img class="check" src="check.svg" alt="Loading error">  Home</li>
                    <li> <img class="check" src="check.svg" alt="Loading error">  Page</li>
                    <li> <img class="check"src="check.svg" alt="Loading error">   Services</li>
                    <li> <img class="check"src="check.svg" alt="Loading error">   About us</li>
                    <li> <img  class="check"src="check.svg" alt="Loading error">  Portfolio</li>
                    <li> <img class="check" src="check.svg" alt="Loading error">  Pricing</li>
                    <li> <img class="check" src="check.svg" alt="Loading error">  News</li>
                    <li> <img class="check" src="check.svg" alt="Loading error">  Testimonia</li>
                    <li> <img class="check"src="check.svg" alt="Loading error">   Contact Us</li>

                </ol>
            </div>
        </section>
        <section>
            <div class="container">
            <div>
                <h2>What is Lorem Ipsum? </h2>
               <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has </p>
               <p>been the industry's standard dummy text ever since the 1500s, when an unknown printer </p>
               <p>took a galley of type and scrambled it to make a type specimen book. It has survived not</p>
               <p>only five centuries, but also the leap into electronic typesetting, remaining essentially</p>
               <p> unchanged. It was popularised in the 1960s with the release of Letraset sheets containing</p>
               <p> Lorem Ipsum passages, and more recently with desktop publishing software like Aldus</p> 
               <p>PageMaker including versions of Lorem Ipsum.</p>
               
            </div>
            <div>
                <h2>Why do we use it? </h2>
               <p>It is a long established fact that a reader will be distracted by the readable content of </p>
                <p>a page when looking at its layout. The point of using Lorem Ipsum is that it has a </p>
                <p>more-or-less normal distribution of letters, as opposed to using 'Content here, content</p>
                <p> here', making it look like readable English. Many desktop publishing packages and web page</p>
                <p> editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will/<p>
                <p> uncover many web sites still in their infancy. Various versions have evolved over the years,</p>
                <p> sometimes by accident, sometimes on purpose (injected humour and the like).</p>
               
            </div>
            <div>
                <h2>Lorem Ipsum <br>
                Dummy Text</h2>
                <p class="para">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
                et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
                aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
                dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia
                deserunt mollit anim id est laborum.</p>
               
            </div>
        </div>
        </section>

    </main>
    <footer>
        <div class="container ">
            <nav class="nav-background ">
                
                <ul class="flex">
                    <li>
                        <a href="#">Home</a>
                    </li>
                    <li>
                        <a href="#">About</a>
                    </li>
                    <li>
                        <a href="#">Faqs</a>
                    </li>
                    <li>
                        <a href="#">Program</a>
                    </li>
                    <li>
                        <a href="#">Contact</a>
                    </li>
                </ul>
           
            </nav>
        </div>
    </footer>
</body>
</html>