The index.html File
This updated file organizes your previous introduction page using semantic div containers, unique id values, reusable class attributes, a custom data-* attribute (data-section="profile"), and newly updated content:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Structured Personal Introduction</title>
</head>
<body data-section="profile">

    <!-- Header Section -->
    <div id="header-section" class="container header-container">
        <h1 class="main-title">Alex Johnson</h1>
        <p class="subtitle">Full-Stack Web Developer & Designer</p>
    </div>

    <hr>

    <!-- About Section -->
    <div id="about-section" class="container content-section">
        <h2 class="section-heading">About Me</h2>
        <p class="text-content">Hello! I am an updated developer profile focusing on writing clean HTML, building responsive layouts, and continuously expanding my technical skill set.</p>
    </div>

    <hr>

    <!-- Education Section -->
    <div id="education-section" class="container content-section">
        <h2 class="section-heading">Education</h2>
        <h3 class="sub-heading">Bachelor of Science in Computer Science</h3>
        <p class="text-content">
            <em class="institution">State University</em><br>
            Graduation Year: <strong class="highlight">2027</strong>
        </p>
    </div>

    <hr>

    <!-- Skills Section -->
    <div id="skills-section" class="container content-section">
        <h2 class="section-heading">Skills</h2>
        <ul class="skills-list">
            <li class="skill-item"><strong>HTML5 & CSS3</strong></li>
            <li class="skill-item"><strong>JavaScript Basics</strong></li>
            <li class="skill-item"><em>Git & GitHub</em></li>
        </ul>
    </div>

    <hr>

    <!-- Contact Section -->
    <div id="contact-section" class="container content-section">
        <h2 class="section-heading">Contact</h2>
        <p class="text-content">You can reach out to me via email at <span class="contact-email">alex.johnson@example.com</span>.</p>
    </div>

</body>
</html>