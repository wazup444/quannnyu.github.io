<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
</head>
<body>

<div class="container">
    <div class="left-image">
        <img src="left-image.jpg" alt="左側圖片">
    </div>
    <div class="right-content">
        <h2>About Me</h2>
        <p>Your self-introduction text goes here. You can talk about your background, skills, interests, and goals.</p>

        <h2>My Work</h2>
        <p>Here, you can showcase your work, projects, or experiences. You can use images and text to describe them.</p>

        <h2>Contact Me</h2>
        <p>If you wish to get in touch with me, please use the following methods:</p>
        <ul>
            <li>Email: your.email@example.com</li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile">LinkedIn Profile</a></li>
            <li>Twitter: <a href="https://twitter.com/yourusername">Twitter Profile</a></li>
        </ul>
    </div>
</div>

<script>
    $(document).ready(function() {
        // 更改容器的背景顏色
        $('.container').css('background-color', '#f0f0f0');
    });
</script>

</body>
</html>
