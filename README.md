# TJ-Tasks-2022-MANISH_TYAGI

## Features

⚡️Simple and clean website that contains Home, About me, Skills and contact section                                  
⚡️ Fully Responsive\
⚡️ Valid HTML5, CSS3 & Js                                                                                
⚡️ Well organized documentation

To view the portfolio: **[click here](http://127.0.0.1:3004/index.html)**

---
## Why do you need a portfolio? 

- Professional way to showcase your work
- Increases your visibility and online presence
- Shows you’re more than just a resume

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites 📋

All you'll need is to installed these 2 things on your computer.
1. VS Code
2. Github Desktop (you can use it online also)

---

## How To Use 🔧

From your command line, first clone this repo:

```bash
# Clone the repository
$ git clone https://github.com/money8203/TJ-Tasks-2022-MANISH_TYAGI.git

# Move into the repository
$ cd 

Now you are good to go and make changes
```

## Template Instructions:

### Step 1 - STRUCTURE

Go to `index.html` and put your information, there are 5 sections:                                            

For navbar -
```html
<!-- **** Hero Section **** -->
    <div class="scroll-up-btn">
        <i class="fas fa-angle-up"></i>
    </div>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#">Portfo<span>lio.</span></a></div>
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#about" class="menu-btn">About</a></li>
                <li><a href="#skills" class="menu-btn">Skills</a></li>
                <li><a href="#contact" class="menu-btn">Contact</a></li>
            </ul>
            <div class="menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </nav>
    <!-- /END Hero Section -->

```

### (1) Home Section

<h2 align="center">
  <img src="https://github.com/money8203/TJ-Tasks-2022-MANISH_TYAGI/blob/main/Screenshot%20(69).png?raw=true" width ="1000"/>
  <br>
</h2>

- On `.text-2`, put your custom portfolio title.
- On `a href tag`, put your custom button label.

```html
<!-- **** Hero Section **** -->
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">Hello, my name is</div>
                <div class="text-2">Manish Tyagi</div>
                <div class="text-3">And I'm a <span class="typing"></span></div>
                <a href="#">Hire me</a>
            </div>
        </div>
    </section>
<!-- /END Hero Section -->
```

### (2) About Section

<h2 align="center">
  <img src="https://github.com/money8203/TJ-Tasks-2022-MANISH_TYAGI/blob/main/Screenshot%20(65).png?raw=true" width ="1000"/>
  <br>
</h2>

- On `<img>` tag, fill the `src` property with your profile picture path, your picture must be located inside `images/` folder.
- On `<p>` tag , include information about you, I recommend to put 2 paragraphs in order to work well and a maximum of 3 paragraphs.
- On last `<a>` tag, include your CV (.pdf) path on `href` property, your resume CV must be located inside `imagess/` folder.

```html
<!-- **** About Section **** -->
<section class="about" id="about">
        <div class="max-width">
            <h2 class="title">About me</h2>
            <div class="about-content">
                <div class="column left">
                    <img src="images/imageee.jpeg" alt="">
                </div>
                <div class="column right">
                    <div class="text">I'm Manish and I'm a <span class="typing-2"></span></div>
                    <p>I am an Open Source enthusiast who is passionate about Technology and Development. I love to explore and learn new things annd apply them to solve real world problem with like minded peers. Also I love to contributing and empowering community via open source</p>
                    <a href="#">Download CV</a>
                </div>
            </div>
        </div>
    </section>

<!-- /END About Section -->
```

### (3) Skills Section

<h2 align="center">
  <img src="https://github.com/money8203/TJ-Tasks-2022-MANISH_TYAGI/blob/main/Screenshot%20(66).png?raw=true" width ="1000"/>
  <br>
</h2>

- On `<div>` tag with class name `.text`, include your project title.
- On `<p>` tag include a short summary about your skillsets.
- On first`<span>` tags, put all your skills that you know, use frequently or expert in .
- On second `<span>` tags, put your skills percentage i.e. how efficient are you in that language.

```html
<!-- **** Projects Section **** -->
<section id="projects">
  ...
<!-- skills section start -->
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">My skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">My creative skills & experiences.</div>
                    <p>I am well aware of basics of HTML & CSS along with fundamentals of Java. Currently I am learning JavaScript with React as a part of my frontend web development course by 'Meta' along with data structure and algorithms</p>
                    <a href="#">Read more</a>
                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>HTML</span>
                            <span>50%</span>
                        </div>
                        <div class="line html"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>CSS</span>
                            <span>35%</span>
                        </div>
                        <div class="line css"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Java</span>
                            <span>45%</span>
                        </div>
                        <div class="line js"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>JavaScript</span>
                            <span>20%</span>
                        </div>
                        <div class="line php"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
```

### (4) Contact Section

<h2 align = "center">
  <img src = "https://github.com/money8203/TJ-Tasks-2022-MANISH_TYAGI/blob/main/Screenshot%20(67).png?raw=true" />
  <br>
  </h2>

- On first`<div>` tag with class name `.csub-title`, include your name.
- On second `<div>` tag with class name `.subtitle`, put your address.
- On `<div class="sub-title">` tag provide your email in `href` tag of attribute `a`

```html
<!-- **** Contact Section **** -->
 <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact me</h2>
            <div class="contact-content">
                <div class="column left">
                    <div class="text">Get in Touch</div>
                    <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Manish Tyagi</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Address</div>
                                <div class="sub-title">UP, India</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-envelope"></i>
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title"><a href="https:www.manishtyagi088@gmail.com" class="yyy">manishtyagi088@gmail.com</a></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Message me</div>
                    <form action="#">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" placeholder="Name" required>
                            </div>
                            <div class="field email">
                                <input type="email" placeholder="Email" required>
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" placeholder="Subject" required>
                        </div>
                        <div class="field textarea">
                            <textarea cols="30" rows="10" placeholder="Message.." required></textarea>
                        </div>
                        <div class="button-area">
                            <button type="submit">Send message</button>
                        </div>
                    </form>
                </div>
                
            </div>
        </div>
    </section>
<!-- /END Contact Section -->
```

### (5) Footer Section

-  Put your name in `href` attribute of the `<a>` tags.

```html
<footer>
        <span>Created By <a href="#">Manish</a> | <span class="far fa-copyright"></span> 2022 All rights reserved.</span>
    </footer>

    <script src="script.js"></script>
  ...
</footer>
```

### Step 2 - STYLES

Change the color theme of the website - (choose 2 colors to create a gradient)

Go to `style.css` and paste the code as it is only change the values with your prefered color.
If you want to get styled fonts and icons include this 

```scss
/*  import google fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Ubuntu:wght@400;500;700&display=swap');

```

---

### Step 3 - SCRIPT
- To put the website in action and make it responsive we need to add some javascript to it 

```js
$(document).ready(function(){
    $(window).scroll(function(){
        // sticky navbar on scroll script
        if(this.scrollY > 20){
            $('.navbar').addClass("sticky");
        }else{
            $('.navbar').removeClass("sticky");
        }
        
        // scroll-up button show/hide script
        if(this.scrollY > 500){
            $('.scroll-up-btn').addClass("show");
        }else{
            $('.scroll-up-btn').removeClass("show");
        }
    });

    // slide-up script
    $('.scroll-up-btn').click(function(){
        $('html').animate({scrollTop: 0});
        // removing smooth scroll on slide-up button click
        $('html').css("scrollBehavior", "auto");
    });

    $('.navbar .menu li a').click(function(){
        // applying again smooth scroll on menu items click
        $('html').css("scrollBehavior", "smooth");
    });

    // toggle menu/navbar script
    $('.menu-btn').click(function(){
        $('.navbar .menu').toggleClass("active");
        $('.menu-btn i').toggleClass("active");
    });

    // typing text animation script
    var typed = new Typed(".typing", {
        strings: ["Frontend Developer", "Open Source Developer",],
        typeSpeed: 100,
        backSpeed: 60,
        loop: true
    });

    var typed = new Typed(".typing-2", {
        strings: ["Frontend Developer", "Open Source Developer",],
        typeSpeed: 100,
        backSpeed: 60,
        loop: true
    });

    // owl carousel script
    $('.carousel').owlCarousel({
        margin: 20,
        loop: true,
        autoplay: true,
        autoplayTimeOut: 2000,
        autoplayHoverPause: true,
        responsive: {
            0:{
                items: 1,
                nav: false
            },
            600:{
                items: 2,
                nav: false
            },
            1000:{
                items: 3,
                nav: false
            }
        }
    });
});

```


## Deployment 📦

Once you finish your setup. You need to put your website online!

You can use [Netlify](https://netlify.com) or can deploy it on github

## Technologies used 🛠️

- HTML5
- CSS3
- JavaScript 


## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
