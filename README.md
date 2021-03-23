# Login_Page.html
<!DOCTYPE html>
<html>
<head>
    <title>login</title>
</head>
    <style type="text/css">

        div{
            width: 500px;
            height: 500px;
            border: 1px solid red;
            margin: 0 auto;
            padding: 120px;
            box-sizing: border-box;
        }

    </style>


<body>
    <center><h1>Welcome to Login Page</h1></center>
    <hr>

    <div>
        username:<br>
        <input type="text" name="text" id="username">
        <br></br>

        password:<br>
        <input type="password" name="text" id="password">
        <br></br>

        <button onclick="login()">Submit</button>
    


    </div>
<script type="text/javascript">
    function login()
    {
        var uname=document.getElementById('username').value;
        var pass=document.getElementById('password').value;

        if(uname=="world" && pass=="123")
        {
            location.assign("file:///C:/Users/My%20Dell/Desktop/HTML,CSS,JS/login_page.html");
        }
        else
        {
            window.alert("login failed");
        }
    }
    </body>
    </html>
