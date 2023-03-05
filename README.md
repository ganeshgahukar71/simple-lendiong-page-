# simple-lendiong-page-
hello I   make a simple lending page using html and css
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>simple navigation page</title>
    <link rel="stylesheet" href="navi.css">
    <style type="text/css">
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        
        header {
            width: 100%;
            height: 100vh;
            background: darkgrey url(p5.jpg.jpg);
            background-size: cover;
            font-family: sans-serif;
        }
        
        nav {
            width: 100%;
            height: 100px;
            color: white;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        
        .logo {
            font-size: 2em;
            letter-spacing: 2px;
            color: brown;
        }
        
        .menu a {
            text-decoration: none;
            color: rgb(23, 20, 20);
            padding: 10px 20px;
            font-size: 20px;
        }
        
        .register a {
            text-decoration: none;
            color: white;
            padding: 10px 20px;
            font-size: 20px;
            background: indianred;
            border-radius: 8px;
        }
        
        .h-test {
            max-width: 650px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: rgb(15, 15, 11);
            text-align: center;
        }
        
        .h text span {
            letter-spacing: 5px;
        }
        
        .h-test h1 {
            font-size: 3.5em;
            color: rgb(0, 0, 0)4, 22, 22);
        }
        
        .h-test a {
            text-decoration: none;
            background: indianred;
            color: white;
            padding: 10px 20px;
            letter-spacing: 5px;
        }
    </style>

</head>

<body>
    <header>
        <nav>
            <div class="logo">
                pizza
            </div>
            <div class="menu">
                <a href="#"> home</a>
                <a href="#"> about</a>
                <a href="#"> best offer</a>
                <a href="#"> contect</a>

            </div>
            <div class="register">
                <a href="#">register</a>

            </div>
        </nav>
        <section class="h-test">
            <span>Enjoy</span>
            <h1>welcome to online pizaa order</h1>

            <br>
            <a href="#">pizaa order online </a>
        </section>

    </header>

</body>

</html>
