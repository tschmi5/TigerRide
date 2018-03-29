# TigerRide
COSC 412 Term Project 

<!DOCTYPE html>

<html>
    <head>
        <title>Login</title>
        <link rel="stylesheet" type="text/css" href="login_style.css">
    </head>
    <body>
        <div class="login-page">
            <div class="form">
                
                <form class="register-form">
                    <input type="text" placeholder="Username"/>
                    <input type="text" placeholder="Password"/>
                    <input type="text" placeholder="Email Address"/>
                    <button>Create</button>
                    <p class="message"> Already Registered? <a href="#">Log in</a></p>
                </form>


                <form class="login-form">
                    <input type="text" placeholder="Username"/>
                    <input type="password" placeholder="Password"/>
                    <button>login</button>
                    <p class="message"> Not Registered? <a href="#">Register</a> </p>
                </form>
                
            </div>
        </div>

        <script src='https://code.jquery.com/jquery-3.3.1.min.js'></script>

        <script>
            $('.message a').click(function () {
                $('form').animate({height: "toggle", opacity: "toggle"}, "slow");
            })
        </script>
        
    </body>
</html>
