Frontend Mentor - Social Links Profile Solution

This is a solution to the Social Links Profile challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.
Table of contents

    Overview
        The challenge
        Screenshot
        Links
    My process
        Built with
        What I learned
        Continued development
        Useful resources
    Author
    Acknowledgments

Overview
The challenge

Users should be able to:

    See hover and focus states for all interactive elements on the page

Screenshot

Screenshot
Links

    Solution URL: Solution URL
    Live Site URL: Live Site URL

My process
Built with

    Semantic HTML5 markup
    CSS custom properties
    Flexbox
    Mobile-first workflow

What I learned

During this project, I learned how to effectively use CSS Flexbox to center elements both horizontally and vertically within a container. I also gained experience in creating responsive designs using media queries.

Here are some code snippets I'm particularly proud of:

html

<div class="container">
  <div class="image">
    <img src="/images/profile-pic.jpg" alt="Profile Picture" />
  </div>
  <div class="info">
    <h2>Sahar Ali</h2>
    <h3>Riyadh, Saudi Arabia</h3>
    <p>"Front-end Developer"</p>
  </div>
  <nav class="nav">
    <a href="https://github.com/saharrrrr" target="_blank">GitHub</a>
    <a href="https://www.frontendmentor.io/profile/saharrrrr" target="_blank">Frontend Mentor</a>
    <a href="https://www.linkedin.com/in/sahar-alii/" target="_blank">LinkedIn</a>
    <a href="https://x.com/saharr_kamil?t=OSqdmGpt098dRgb_6VIGrQ&s=03" target="_blank">X</a>
    <a href="https://www.instagram.com/sahar_jr?igsh=MXR2cHNycW1uOWNzYw==">Instagram</a>
  </nav>
</div>

css

.container {
width: 25%;
max-width: 400px;
display: flex;
justify-content: center;
align-items: center;
flex-direction: column;
margin: auto;
background-color: var(--color-primary);
border-radius: 15px;
padding: 20px;
}

.image img {
width: 150px;
border-radius: 50%;
}

Continued development

In future projects, I want to continue focusing on improving accessibility and performance. I also aim to refine my skills in using CSS Grid for more complex layouts.
Useful resources

    MDN Web Docs - A comprehensive resource for learning about CSS properties and best practices.
    CSS Tricks - This site has a plethora of articles and tutorials on various CSS techniques.

Author

    Frontend Mentor - https://www.frontendmentor.io/profile/saharrrrr
    GitHub - https://github.com/saharrrrr
    Twitter - https://x.com/saharr_kamil?t=OSqdmGpt098dRgb_6VIGrQ&s=03"

Acknowledgments

Thanks to the Frontend Mentor community for providing feedback and inspiration throughout this project.
