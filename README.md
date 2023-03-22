# registerform-porfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="form.css">
    <title>Register  Form</title>
</head>
<body>
    <h1>Register Form</h1>
    <form class="form">
        <fieldset>
            <label><b> Name</b></label><br>
            <input type="text"><br>
            <label><b> E-mail id</b></label><br>
            <input type="email"><br>
            <label><b> Phone Number</b></label><br>
            <input type="text"><br>
            <label><b> DOB</b></label><br>
            <input type="date"><br>
            <label><b>Mother tongue</b></label>
            <input type="radio" name="Mother">
            <label> <b>Tamil</b></label>
            <input type="radio" name="Mother">
            <label><b>English</b></label><br>
            <label><b>Computer Languge</b></label><br>
            <label><b> HTML</b></label>
            <input type="checkbox">
            <label><b>CSS</b></label>
            <input type="checkbox">
            <label><b>JavaScript</b></label>
            <input type="checkbox"><br>
            <label> <b>Upload Resume</b></label><br>
            <input type="file"><br>
            <label><b>OTB</b></label><br>
            <div class="input">
                <input type="text">
                <input type="text">
                <input type="text">
                <input type="text">
                <input type="text">
            </div>
        </fieldset>
    </form>
</body>
</html>
css;
h1{
    text-shadow: 2px 2px 3px;
    background-color: rgba(200, 43, 240, 0.726);
    text-align: center;
}
.form{
   font-size: normal;
  font-family: 'Times New Roman', Times, serif;
}
