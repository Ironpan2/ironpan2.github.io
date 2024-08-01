<p>Hello welcome to my website</p>
<!DOCTYPE html>
<html lang="en">

<head>
    <title>
        How to Create Fullscreen Video 
        Background with HTML and CSS?
    </title>
    
    <style>
        .video-container {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            overflow: hidden;
        }

        video {
            position: absolute;
            z-index: 10;
            width: 100%;
            height: 100vh;
            max-width: none;
        }
    </style>
</head>

<body>
    <div class="video-container">
        <video src=
"bg-main.mp4"
            autoplay loop muted>
        </video>
    </div>
</body>

</html>
