<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Self Introduction Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
        }

        .left-image, .right-content {
            flex: 1;
            padding: 10px;
        }

        .left-image img {
            max-width: 100%;
            height: auto;
            display: block;
            border-radius: 5px;
        }

        .slider {
            max-width: 100%;
            height: auto;
        }

        .right-content p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Self Introduction Website</h1>
    </header>

    <div class="container">
        <div class="left-image">
            <img class="slider" src="left-image1.jpg" alt="Left Image">
        </div>
        <div class="right-content">
            <h2>About Me</h2>
            <p>Your self-introduction text goes here. You can talk about your background, skills, interests, and goals.</p>

            <h2>My Work</h2>
            <p>You can showcase your work, projects, or experiences here. You can use images and text to describe them.</p>

            <h2>Contact Me</h2>
            <p>If you'd like to get in touch with me, please use the following methods:</p>
            <ul>
                <li>Email: your.email@example.com</li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile">LinkedIn Profile</a></li>
                <li>Twitter: <a href="https://twitter.com/yourusername">Twitter Profile</a></li>
            </ul>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
        $(document).ready(function () {
            // Image slider
            let images = ['left-image1.jpg', 'left-image2.jpg', 'left-image3.jpg'];
            let currentIndex = 0;
            let slider = $('.slider');

            function changeImage() {
                slider.fadeOut(500, function () {
                    slider.attr('src', images[currentIndex]);
                    slider.fadeIn(500);
                });

                currentIndex = (currentIndex + 1) % images.length;
            }

            setInterval(changeImage, 3000); // Change image every 3 seconds
        });
    </script>
</body>
</html>
