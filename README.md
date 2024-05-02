# <img src="assets/readme/safari-technology-preview-logo.png" width="50" height="50"/>&nbsp; nsswifter.github.io

This [GitHub Webpage](https://nsswifter.github.io/) serves as a portfolio showcasing various aspects of who I am :}

Explore this space to discover more about me and enjoy glimpses of some interesting facets of my work and interests.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Layout</title>
    <style>
        .wide {
            display: flex;
            flex-direction: row;
        }
        .small {
            display: flex;
            flex-direction: column;
        }
        /* Additional CSS for styling */
        .box {
            width: 100px;
            height: 100px;
            margin: 10px;
            background-color: skyblue;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="box">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
    </div>
    <script>
        function adjustLayout() {
            var container = document.querySelector('.container');
            if (window.innerWidth >= 768) { // Adjust this value according to your design
                container.classList.remove('small');
                container.classList.add('wide');
            } else {
                container.classList.remove('wide');
                container.classList.add('small');
            }
        }

        // Call adjustLayout on page load and resize
        window.onload = adjustLayout;
        window.onresize = adjustLayout;
    </script>
</body>
</html>
