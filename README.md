<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be Part of Riza's 'libre' Music Video!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #f7d6f2;
            color: #6a1b9a;
            text-align: center;
            padding: 20px 10px;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        h1, h2, h3 {
            color: #6a1b9a;
        }
        .step {
            margin-bottom: 20px;
            padding: 10px;
            border-left: 5px solid #6a1b9a;
            background-color: #f7f7f7;
        }
        .instructions {
            padding: 10px;
            border: 1px solid #ddd;
            margin-bottom: 20px;
            background-color: #fafafa;
        }
        .form-link {
            text-decoration: none;
            color: white;
            background-color: #6a1b9a;
            padding: 10px 20px;
            display: inline-block;
            border-radius: 5px;
        }
        footer {
            background-color: #6a1b9a;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .upload-section {
            margin-bottom: 20px;
            background-color: #f7f7f7;
            padding: 15px;
            border: 1px solid #ddd;
        }
        .contact {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Be Part of Riza's 'libre' Music Video!</h1>
        <p><strong>A Message from Riza:</strong></p>
        <p>Hey Bestie!!! As you know, you have been so special to me and our journey together. Well bestie, I have good news! Our song ‘libre’ is coming soon, and I want YOU to be featured in the official fan video! Below are the steps to submit your video, along with some important filming tips and legal forms. I am so excited to see this come together!! Te amoooo!!</p>
    </header>

    <section>
        <h2>How to Participate</h2>

        <div class="step">
            <h3>Step 1: Record Your Video</h3>
            <p>Use your iPhone, Android, or any smartphone (see detailed filming instructions below).</p>
            <p>Show your love for the song! Sing along, dance, react, or create something unique.</p>
            <p>Keep your video between 15-30 seconds and record in landscape mode.</p>
        </div>

        <div class="step">
            <h3>Step 2: Submit Your Video</h3>
            <p>Upload your video using the form below. Make sure to include your signed forms!</p>
        </div>

        <div class="step">
            <h3>Step 3: Sign the Required Forms</h3>
            <p>These forms are necessary to include your video in the project:</p>
            <ul>
                <li><a href="#" class="form-link">Talent Release Form</a></li>
                <li><a href="#" class="form-link">Location Release Form</a></li>
            </ul>
        </div>

        <h2>Detailed Filming Instructions by Phone Type</h2>

        <div class="instructions">
            <h3>iPhone Users</h3>
            <ul>
                <li>Open the Camera app and switch to Video Mode.</li>
                <li>Set resolution to 4K/30fps or HD/60fps.</li>
                <li>Ensure good lighting and avoid backlighting.</li>
                <li>Use a tripod or steady surface for stability.</li>
                <li>Tap and hold on your face to lock focus & exposure.</li>
                <li>Press record and have fun!</li>
            </ul>
        </div>

        <div class="instructions">
            <h3>Android Users</h3>
            <ul>
                <li>Open your Camera app and select Video Mode.</li>
                <li>Go to Settings and set resolution to 1080p or 4K.</li>
                <li>Use a stable surface or tripod to keep the shot steady.</li>
                <li>Adjust exposure by tapping the screen to brighten/darken.</li>
                <li>Start recording and make it awesome!</li>
            </ul>
        </div>

        <div class="instructions">
            <h3>Other Phones</h3>
            <ul>
                <li>Select HD or 4K settings in your camera.</li>
                <li>Avoid using the front camera (rear cameras usually have better quality).</li>
                <li>Film in good lighting and keep the camera stable.</li>
            </ul>
        </div>

        <h2>Submit Your Video</h2>
        <div class="upload-section">
            <p>Upload your video and signed forms using the form below:</p>
            <form action="/submit" method="post" enctype="multipart/form-data">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br><br>
                <label for="video">Upload Your Video:</label><br>
                <input type="file" id="video" name="video" accept="video/*" required><br><br>
                <label for="forms">Upload Signed Forms:</label><br>
                <input type="file" id="forms" name="forms" accept="application/pdf,image/*" required><br><br>
                <button type="submit">Submit</button>
            </form>
        </div>

        <h2>Questions?</h2>
        <p class="contact">If you have any questions, reach out to <a href="mailto:intern@miamiart.house">intern@miamiart.house</a>.</p>
    </section>

    <footer>
        <p>Let’s make this something special for Riza! 💜🎶</p>
    </footer>
</body>
</html>
