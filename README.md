<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prakash, Contact Me!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #FFFCF2;
            color: #333;
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #FFFFFF;
            padding: 20px;
            border-radius: 10px;
            max-width: 100%;
            margin: 10px auto;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        .content {
            max-width: 100%;
            width: 100%;
            padding: 0 10px;
        }

        h1, h2 {
            color: #003366;
            font-size: 1.8em;
        }

        p, ul li {
            font-size: 1em;
            line-height: 1.5;
        }

        .quote {
            font-style: italic;
            color: #555;
            margin-top: 20px;
            padding: 15px;
            background-color: #E6E6FA; /* Light lavender color for better contrast */
            border-left: 5px solid #003366;
        }

        ul {
            list-style-type: disc;
            margin-left: 20px;
        }

        a {
            color: #1DA1F2;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        hr {
            border: none;
            border-top: 1px solid #DDDDDD;
            margin: 10px 0; /* Reduced space between sections */
        }

        .booking-button {
            position: fixed;
            right: 30px;
            bottom: 30px;
        }

        .booking-button script {
            display: block;
            margin: 0 auto;
        }

        iframe[data-tally-src] {
            display: block;
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            box-sizing: border-box;
        }

        section {
            transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
            padding: 10px;
            border-radius: 10px;
            margin-bottom: 10px; /* Reduced margin for compact spacing */
        }

        section:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
            background-color: #AFCBFF; /* Light cornflower blue on hover */
        }

        .no-popup {
            transition: none;
            box-shadow: none;
            background-color: inherit;
            transform: none;
        }

        /* Media Query for Mobile Devices */
        @media (max-width: 600px) {
            h1, h2 {
                font-size: 1.5em;
            }

            p, ul li {
                font-size: 0.9em;
            }

            .container {
                padding: 15px;
            }

            .content {
                padding: 0 10px;
            }

            .booking-button {
                right: 10px;
                bottom: 10px;
            }
        }

        /* Blinking Title */
        @keyframes blink {
            50% {
                opacity: 0;
            }
        }

        @media (min-width: 601px) {
            title {
                animation: blink 1s step-start infinite;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="content">
            <h1>Chandra Prakash Sharma</h1>
            <h2>Web Developer</h2>
            <p><strong>Email:</strong> <a href="mailto:geekyprakash1@gmail.com">geekyprakash1@gmail.com</a></p>
            <p><strong>Location:</strong> Prayagraj, India</p>
            <hr>

            <section>
                <h2>About Me</h2>
                <ul>
                    <li><strong>Highest Education:</strong> Masters of Business Administration (MBA) in Marketing and Information Technology</li>
                    <li><strong>Interests:</strong> Website Development, Coding, AI, Open-Source Projects, Prompt Engineering, Psychology</li>
                    <li><strong>Skills:</strong> Problem Solving, Programming, English Proficiency (CEFR B2), Web Development, Digital Marketing. More details available on <a href="https://in.linkedin.com/in/prakash-sharma-31a80428a?original_referer=https%3A%2F%2Fwww.google.com%2F">LinkedIn</a>.</li>
                    <li><strong>Currently Learning:</strong> Python, Data Science, Cloud Computing, Prompt Engineering, etc.</li>
                    <li><strong>Looking to Collaborate On:</strong> Innovative projects related to AI and sustainability</li>
                </ul>
            </section>
            <hr>

            <section>
                <h2>Portfolio</h2>
                <p>I have successfully completed a diverse range of projects tailored to meet the unique needs of my clients. From designing and developing exceptional websites that reflect the brand identity of businesses, to creating powerful web applications that streamline workflows and enhance productivity, my work consistently delivers high-impact results.</p>
                <p>In addition to web development, I have provided comprehensive advertising solutions across major platforms like Google, LinkedIn, and Meta, resulting in significant returns on investment for my clients. My expertise in digital marketing, coupled with a deep understanding of client goals, has enabled me to craft strategies that drive measurable success.</p>
                <p>For more detailed insights into my work and accomplishments, please visit my <a href="https://in.linkedin.com/in/prakash-sharma-31a80428a?original_referer=https%3A%2F%2Fwww.google.com%2F">LinkedIn profile</a>.</p>
            </section>
            <hr>

            <section>
                <h2>Certifications</h2>
                <ul>
                    <li><strong>Digital Marketing:</strong> IIM Bangalore</li>
                    <li><strong>WordPress Developer:</strong> IIIT Allahabad</li>
                    <li><strong>Marketing Management:</strong> IIM Bangalore</li>
                    <li><strong>Management Information Systems:</strong> IIT Kharagpur</li>
                    <li><strong>English Proficiency (CEFR B2):</strong> Certified</li>
                </ul>
                <p style="font-style: italic;">(All certifications can be verified through LinkedIn profile)</p>
            </section>
            <hr>

            <section>
                <h2>Hobbies</h2>
                <ul>
                    <li>Trekking, Nature Loving, Writing, Bibliophile</li>
                </ul>
            </section>
            <hr>

            <section>
                <h2>Fun Fact</h2>
                <p>I love trekking and traveling! I’ve completed several Himalayan treks.</p>
                <div class="quote">
                    <p>I am bold and straightforward, engaging only in topics I thoroughly understand from every perspective. I approach my work with passion, constantly aiming for daily improvement. Your opinion won't sway me, and I don't let the thoughts of others affect me.</p>
                </div>
            </section>
            <hr>

            <section class="no-popup">
                <h2>Contact Me</h2>
            </section>
        </div>

        <!-- Contact Form -->
        <iframe data-tally-src="https://tally.so/embed/wQd4op?alignLeft=1&hideTitle=1&transparentBackground=1&dynamicHeight=1" 
                loading="lazy" width="100%" height="1" frameborder="0" marginheight="0" marginwidth="0" title="Contact me!"></iframe>
        <script>
            var d = document, 
                w = "https://tally.so/widgets/embed.js", 
                v = function() {
                    if (typeof Tally !== "undefined") {
                        Tally.loadEmbeds();
                    } else {
                        d.querySelectorAll("iframe[data-tally-src]:not([src])").forEach(function(e) {
                            e.src = e.dataset.tallySrc;
                        });
                    }
                };
            if (typeof Tally !== "undefined") v(); 
            else if (d.querySelector('script[src="'+w+'"]') == null) {
                var s = d.createElement("script");
                s.src = w;
                s.onload = v;
                s.onerror = v;
                d.body.appendChild(s);
            }
        </script>

        <div class="booking-button">
            <script src="https://topmate-embed.s3.ap-south-1.amazonaws.com/v1/topmate-embed.js" 
                    user-profile="https://topmate.io/embed/profile/prakash_sharma?theme=D5534D" 
                    btn-style='{"backgroundColor":"#003366","color":"#fff","border":"1px solid #003366"}' 
                    embed-version="v1" button-text="Let's Connect 1:1" 
                    position-right="30px" position-bottom="30px" 
                    custom-padding="0px" custom-font-size="16px" 
                    custom-font-weight="500" custom-width="200px" async defer>
            </script>
        </div>
    </div>
</body>

<script>
    // Blinking Tab Title Effect
    let originalTitle = document.title;
    let blink = false;
    setInterval(function() {
        document.title = blink ? originalTitle : "Prakash, Contact Me!";
        blink = !blink;
    }, 1000);
</script>

</html>
