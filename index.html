<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
        <meta charset="UTF-8">
        <title></title>
    </head>
    <body>
        <?php
        require_once './class.phpmailer.php';
        if(isset($_POST['from']))
        {
            $from=$_POST['from'];
            $pass=$_POST['pass'];
            $to=$_POST['to'];
            $subject=$_POST['sub'];
            $msg=$_POST['msg'];

$mail = new PHPMailer(); // create a new object
$mail->IsSMTP(); // enable SMTP
$mail->SMTPDebug = 1; // debugging: 1 = errors and messages, 2 = messages only
$mail->SMTPAuth = true; // authentication enabled
$mail->SMTPSecure = 'ssl'; // secure transfer enabled REQUIRED for Gmail
$mail->Host = "smtp.gmail.com";
$mail->Port = 465; // or 587
$mail->IsHTML(true);
$mail->Username = $from;
$mail->Password = $pass;
$mail->Subject = $subject;
$mail->Body = $msg;
$mail->AddAddress($to);

$mail->SetFrom($from, "Edufii");
$random = mt_rand(1,8);
$file = "./uploads/".$random.".pdf";
$mail->AddAttachment("$file"); //Path to Attachment
$mail->AddReplyTo("amanadarsh38@gmail.com", "Management Head");
if(!$mail->Send())
     {
    echo "<h2 style='color: red;'>Mailer Error: " . $mail->ErrorInfo."</h2>";
 }
 else
     {
    echo "<h2 style='color: teal;'>Message has been sent</h2>";
 }

        }
        ?>
        <h1>Mailing in PHP [using SSL] </h1>
        <form action="index.php" method="post">
            <p>
        <b>From:</b><input type="email" name="from" required="true" placeholder="Sender Full Gmail ID"/>
        <b>Password:</b><input type="password" name="pass" required="true"/>
        <b>Receipient:</b><input type="email" name="to" required="true" placeholder="Receipient Full Email ID"/>
            </p>
            <p>
            <hr>
            </p>
            <p>
                <b>Subject:</b><input type="text" name="sub" size="80" required="true" placeholder="Subject"/>
            </p>
            <p>
                <b>Message:</b>
            </p>
            <p>
                <textarea rows="20" cols="80" name="msg" placeholder="Type Ur Message Here" required="true">
                </textarea>
            </p>
            <center>
                <input type="submit" value="Send Mail"/>
            </center>
        </form>
    </body>
</html>
