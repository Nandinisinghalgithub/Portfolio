# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/a7dd30b0cf.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="th.jpeg" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-solid fa-rectangle-xmark" onclick="closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>Web Developer</p>
                <h1>Hi, I'm <span>Nandini</span> <br>Singhal From Gwalior</h1>
            </div>
        </div>
   </div>

    <!---------------about---------- -->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="IMG_20210630_203328_893.jpg">
                </div>
                <div class="about-col-2"> 
                    <h1 class="sub-title">About Me</h1>
                    <p>I'm a computer Science and Engineering (CSE) B.Tech student from Institute Of Technology and Management with excellent academic background and diverse skillset.Experienced in Web Development.I am versed in C,C++,HTML,CSS and Javascript. <br>
                        Flair for creating Impressive Visuals Can Lead and Execute all Visuals Design stages from concept to completion.Self-Motivated and Proactive.Can work well in a Team. <br>
                        Be Happy, It Drives People Crazy...
                    </p>

                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links active-link" onclick="opentab('projects') ">Projects</p>
                        <p class="tab-links active-link" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>c/c++</span><br>Earning other Programming Languages</li>
                            <li><span>Web Development</span><br> Web app interfaces</li>
                            <li><span>Project Management</span><br>Handling projects</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="projects">
                        <ul>
                            <li><span>Calculator</span><br>used for performing basic mathematical operations</li>
                            <li><span>Temperature Converter</span><br>convert temperatures between different units,such as Cel,Fah,& Kel</li>
                            <li><span>Netflix Clone</span><br>the landing page of Netflix</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2018-High School Examination</span><br>Delhi Public School</li>
                            <li><span>2020-Higher Secondary Examination</span><br>Delhi Public School</li>
                            <li><span>Present-B.Tech</span><br>ITM Gwalior</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ----------skills---------- -->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Skills</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Web Design</h2>
                    <p>Web design refers to the design of websites. It usually refers to the user experience aspects of website development rather than software development. Web design used to be focused on designing websites for desktop browsers; however, since the mid-2010s, design for mobile and tablet browsers has become ever-increasingly important.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-crop-simple"></i> 
                    <h2>Computer Programming</h2>
                    <p>Computer programming is the process of designing and writing computer programs. As a skill set, it includes a wide variety of different tasks and techniques, but our tutorials are not intended to teach you everything. Instead, they are meant to provide basic, practical skills to help you understand and write computer code that reflects things you see and use in the real world.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-app-store"></i>
                    <h2>Project Management</h2>
                    <p>Project Management is the application of specific knowledge, skills, methodologies, and techniques aimed at achieving specific and measurable project goals, including, ultimately, successful project completion. It differs from general “management” because project management relates directly to the goals and time-bound objectives achieved within the scope of a project itself, on a limited timeline, rather than an ongoing one.</p>
                    <a href="#">Learn more</a>
                </div>
            </div>

        </div>
    </div>

    <!-- -------projects--------- -->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Projects</h1>
            <div class="work-list">
                <div class="work">
                    <img src="work-1.png">
                    <div class="layer">
                        <h3>Calculator</h3>
                        <p>HTML calculator is used for performing basic mathematical operations like Addition, subtraction, multiplication, and division.</p>
                        <a href="#"><i class="fa-solid fa-link"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="work-2.png">
                    <div class="layer">
                        <h3>Temperature Converter</h3>
                        <p>A temperature converter is a tool used to convert temperatures, to and from Celsius, Fahrenheit, and Kelvin.</p>
                        <a href="#"><i class="fa-solid fa-link"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="work-3.png">
                    <div class="layer">
                        <h3>Netflix Clone</h3>
                        <p>If you're familiar with Netflix, one of the world's major movie content streaming platforms, it's easier to understand. A Netflix clone is a web app that, just like Netflix does, provides users with a database of movies (or TV series) that they can watch whenever they want</p>
                        <a href="#"><i class="fa-solid fa-link"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See more</a>
        </div>
    </div>

    <!-- -------contact----------- -->
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fa-solid fa-envelope"></i>nandini.singhal29@gmail.com</p>
                    <p><i class="fa-solid fa-phone-volume"></i>8815155984</p>
                    <div class="social-icons">
                        <a href=""><i class="fa-brands fa-facebook"></i></a>
                        <a href=""><i class="fa-brands fa-linkedin"></i></a>
                        <a href=""><i class="fa-brands fa-instagram"></i></a>
                        <a href=""><i class="fa-brands fa-github"></i></a>
                        <a href=""><i class="fa-brands fa-whatsapp"></i></a>
                    </div>
                    <a href="my-cv.pdf" download class="btn btn2">Download CV</a>
                </div>
                    <div class="contact-right">
                        <form name="submit-to-google-sheet">
                            <input type="text" name="Name" placeholder="Your Name" required>
                            <input type="email" name="Email" placeholder="Your Email" required>
                            <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                            <button type="submit" class="btn btn2">submit</button>
                            
                        </form>
                        <span id="msg"></span>
                    </div>
            </div>
        </div>
        <div class="copyright">
            <p>copyright &copy;nandini. Follow for more <i class="fa-solid fa-heart"></i> @NandiniSinghal</p>
        </div>
    </div>

    <script>

        var  tablinks = document.getElementsByClassName("tab-links");
        var  tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname){
            for(tablink of tablinks){
                tablink.classList.remove("active-link");
            }
            for(tabcontent of tabcontents){
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }

    </script>

    <script>

        var sidemenu = document.getElementById("sidemenu");

        function openmenu(){
            sidemenu.style.right = "0";
        }
        function closemenu(){
            sidemenu.style.right = "-200px";
        }
    </script>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbwBaJkdXKUaytWPTVGDbL26-IGkN_QQzNzqJ1J65kMfPZcbVlxlIpIUD9pMAx2k5oP-qQ/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")
      
        form.addEventListener('submit', e => {
          e.preventDefault()
          fetch(scriptURL, { method: 'POST', body: new FormData(form)})
            .then(response => {
                msg.innerHTML = "Message sent successfully"
                setTimeout(function(){
                    msg.innerHTML = ""
                },5000)
                form.reset()
            })
            .catch(error => console.error('Error!', error.message))
        })
      </script>
</body>
</html>
