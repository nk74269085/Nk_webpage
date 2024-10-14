# Nk_webpage
My personal Webpage  backup files (html,css, js)

############################  html  ####################################

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Dr. Narayan Kundu</title>

    <link rel="stylesheet" href="styles.css">

</head>

<body>

    <header>

        <div class="banner">

        <div id="particle-container"></div>

            <h1>Dr. Narayan Kundu</h1>

            <p>Welcome to my personal webpage</p>

        </div>

        <nav>
            <button class="tab-button active" data-tab="home">Home</button>
            
            <button class="tab-button" data-tab="research">Research Interests</button>
            
            <button class="tab-button" data-tab="publications">Publications</button>
            
            <button class="tab-button" data-tab="achievements">Achievements</button> <!-- Use lowercase ID -->
            
            <button class="tab-button" data-tab="collaborations">Collaborations</button>
            
            <button class="tab-button" data-tab="gallery">Gallery</button>
            
            <button class="tab-button" data-tab="downloads">Downloads</button>
            
            <button class="tab-button" data-tab="contact">Contact Me</button>
            
            <button class="tab-button" data-tab="hobby">Hobby</button>
        </nav>

    </header>

    

    <main id="home" class="active gradient1">

    <h2>About Me</h2>

    <div class="about-container">

        <img src="IMG-20240929-WA0008.jpg" alt="Dr. Narayan Kundu" class="profile-pic">

        <p>Hello! I'm Narayan Kundu, an accomplished physicist specializing in Atomic, Molecular, and Optical Physics. 

           I am currently employed as a Postdoctoral Research Fellow at the University of Kassel, Germany; 

           aiming to learn state-of-the-art techniques of attosecond [10<sup>-18</sup> sec] sciences.</p>

    </div>

    </main>





    <main id="research" class="gradient3">

        <h2>Research Interests</h2>

        <ol class="research-list">

            <li> Ultrafast Time-resolved Dynamics of Atoms, Molecules and Clusters</li>

            <li> Coulomb Explosion Imaging (CEI)</li>

            <li> Strong Field Ionization (SFI) and Non-Linear Optics</li>

            <li> High Intensity Laser Ion Trap Experiment (HILITE)</li>

            <li> Dissociative Electron Attachment (DEA) </li>

            <li> Ion Pair Dissociation (IPD)</li>

        </ol>

    </main>





    <main id="publications" class="gradient1">

        <h2>Publications</h2>

        <ul>

            <li>Link to my Google Scholar - <a href="https://scholar.google.com/citations?user=X_a8w1cAAAAJ&hl=en">Google Scholar</a></li>

            <li>Link to my Research Gate - <a href="https://www.researchgate.net/profile/Narayan-Kundu">ResearchGate</a></li>

        </ul>

    </main>



    <main id="achievements" class="gradient3">

        <h2>List of My Achievements</h2>

        <ul>

            <li> 2024: Doctor of Philosophy in Physical Sciences.</li>

            <li> 2018: Qualified JEST in Physical Science (All India Rank 156).</li>

            <li> 2018: Qualified NET-LS in Physical Science (All India Rank 75).</li>

            <li> 2012-2017: INSPIRE Fellowship for Pursuing PhD in Physics.</li>

            <li> 2012-2017: INSPIRE Scholarship for top 1% rank in State Board.</li>

            <li> 2010-2012: Scholarship from Indian Oil Corporation Limited (IOCL).</li>

            <li> 2010-2012: Scholarship from Steel Authority of India Limited (SAIL).</li>

            <li> 2010-2012: Swami Vivekananda Merit Cum Means (MCM) Scholarship.</li>

        </ul>

    </main>



    <main id="collaborations" class="gradient1">

        <h2>List of my Collaborators</h2>

        <ol>

            <ol>1. Prof. Dhananjay Nandi, Department of Physical Sciences, IISER Kolkata, India.</ol>

            <ol>2. Prof. Jochen Mikosh, Hisenberg Professor, University of Kassel, Geramny.</ol>

            <ol>3. Prof. Ashwani K. Tiwari, Department of Chemical Sciences, IISER Kolkata, India.</ol>

            <ol>4. Dr. Minaxi Vinod Kumar, V. P. & R. P. T. P. Science College, Sardar Patel University, India.</ol>

            <ol>5. Dr. Soumen Ghosh, Deapartment of Physics, Ahmedabad University, India.</ol>

        </0l>

    </main>



    <main id="gallery" class="gradient3">

        <h2>Photo Gallery</h2>

        <div class="gallery">

            <div class="gallery-item">

                <img src="IMG-20240929-WA0008.jpg" alt="Photo 1" class="gallery-thumbnail" data-full="IMG-20240929-WA0008.jpg">

            </div>

            <div class="gallery-item">

                <img src="photo2.jpg" alt="Photo 2" class="gallery-thumbnail" data-full="photo2-large.jpg">

            </div>

            <div class="gallery-item">

                <img src="photo3.jpg" alt="Photo 3" class="gallery-thumbnail" data-full="photo3-large.jpg">

            </div>

        </div>

    </main>



    <main id="downloads" class="gradient1">

        <h2>Downloads</h2>

        <div class="link-box">

            <p>Available file types:</p>

            <div class="textbox"><a href="https://github.com/nk74269085/Nk_webpage/blob/main/Resonance_multiphoton_tunelling.pdf" class="download-link" download>Resonance_multiphton_tunelling.pdf</a></div>

            <div class="textbox"><a href="textfile.txt" class="download-link" download>Download Text File</a></div>

            <div class="textbox"><a href="document.docx" class="download-link" download>Download DOCX Document</a></div>

            <div class="textbox"><a href="spreadsheet.xlsx" class="download-link" download>Download Excel Spreadsheet</a></div>

            <div class="textbox"><a href="presentation.pptx" class="download-link" download>Download PowerPoint Presentation</a></div>

            <div class="textbox"><a href="audio.mp3" class="download-link" download>Download Audio File</a></div>

            <div class="textbox"><a href="video.mp4" class="download-link" download>Download Video File</a></div>

        </div>

    </main>



<main id="contact" class="gradient3">
    <h2>Contact Me</h2>
    <div class="contact-box">
        <p>You can reach me directly by filling out the form below:</p>
        
        <form id="contact-form">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="message">Your Query:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send Message</button>
        </form>

        <p id="status-message"></p> <!-- Display success/error messages here -->
    </div>
</main>




    <main id="hobby" class="gradient1">

        <h2>Hobbies</h2>

        <p>My enthusiasm for cricket, football, badminton, and mobile photography enriches my life.

            These activities provide a perfect blend of physical engagement and creative expression, keeping me motivated and inspired.

            Whether I’m playing on the field, cheering for Liverpool, or capturing beautiful moments through my camera,

            I embrace every opportunity to indulge in my passions.</p>

    </main>



    <footer>

        <p>&copy; 2024 Dr. Narayan Kundu. All rights reserved.</p>

    </footer>



    <script src="script.js"></script>

    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>



    <script>

    particlesJS("particle-container", {

        "particles": {

            "number": {

                "value": 100,

                "density": {

                    "enable": true,

                    "value_area": 800

                }

            },

            "color": {

                "value": "#ffffff"

            },

            "shape": {

                "type": "circle",

                "stroke": {

                    "width": 0,

                    "color": "#000000"

                },

                "polygon": {

                    "nb_sides": 5

                }

            },

            "opacity": {

                "value": 0.5,

                "random": false

            },

            "size": {

                "value": 3,

                "random": true

            },

            "line_linked": {

                "enable": true,

                "distance": 150,

                "color": "#ffffff",

                "opacity": 0.4,

                "width": 1

            },

            "move": {

                "enable": true,

                "speed": 6,

                "direction": "none",

                "random": false,

                "straight": false,

                "out_mode": "out",

                "bounce": false

            }

        },

        "interactivity": {

            "detect_on": "canvas",

            "events": {

                "onhover": {

                    "enable": true,

                    "mode": "repulse"

                },

                "onclick": {

                    "enable": true,

                    "mode": "push"

                },

                "resize": true

            }

        },

        "retina_detect": true

    });

</script>

<script type="text/javascript" src="https://cdn.emailjs.com/dist/email.min.js"></script>
<script type="text/javascript">
    (function(){
        emailjs.init("YOUR_USER_ID"); // Replace with your EmailJS User ID
    })();
</script>


</body>

</html>
