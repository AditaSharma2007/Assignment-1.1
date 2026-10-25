
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio - Images</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            text-align: center;
        }

        h1 {
            color: #333;
        }

        p {
            color: #555;
        }

        .images-section {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
        }

        .image-card {
            background-color: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 8px #ccc;
        }

        .image-card img {
            width: 250px;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
        }

        h2 {
            color: #444;
            font-size: 20px;
        }
    </style>
</head>
<body>

    <h1>My Portfolio</h1>
    <p>Welcome to my portfolio. Here are some images that represent me and my interests.</p>

    <h2>My Images</h2>

    <section class="images-section">

        <div class="image-card">
            <img src="images/profile.jpg"
                 alt="Portrait photo of me for my portfolio"
                 width="250"
                 height="180">
            <h2>My Profile</h2>
        </div>

        <div class="image-card">
            <img src="images/project.jpg"
                 alt="Screenshot of a project I created"
                 width="250"
                 height="180">
            <h2>My Project</h2>
        </div>

        <div class="image-card">
            <img src="images/nature.jpg"
                 alt="Beautiful green trees and natural scenery"
                 width="250"
                 height="180">
            <h2>Nature</h2>
        </div>

    </section>

</body>
</html>
