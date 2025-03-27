# Module 2 Coding Assignment

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module 2 Assignment</title>
    <link rel="stylesheet" href="css/styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        h1 {
            margin: 20px 0;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 10px;
        }
        .box {
            position: relative;
            width: 30%;
            background-color: #f4a261;
            border: 1px solid black;
            margin: 10px;
            padding: 20px;
            box-sizing: border-box;
        }
        .title {
            position: absolute;
            top: 0;
            right: 0;
            background-color: #264653;
            color: white;
            padding: 5px 10px;
            border: 1px solid black;
        }
        @media (max-width: 991px) {
            .box {
                width: 45%;
            }
            .box:last-child {
                width: 100%;
            }
        }
        @media (max-width: 767px) {
            .box {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <h1>Our Menu</h1>
    <div class="container">
        <section class="box">
            <div class="title">Chicken</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </section>
        <section class="box">
            <div class="title">Beef</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </section>
        <section class="box">
            <div class="title">Sushi</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </section>
    </div>
</body>
</html>
