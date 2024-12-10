<!DOCTYPE html>
<html lang="en">
<head>
    <title>Appoinment form</title>
</head>
<body bgcolor="pink" >
    <style>
        body{
            background-image: url(image.jpg);
            background-repeat: no-repeat;
        }
        .center{
            color: maroon;
            text-align: center;
            text-size-adjust: 200;
            font-style: italic;
        }
        input[type=text],select{
            width: 30%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type=email],select{
            width: 30%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type=date],select{
            width: 30%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type=number],select{
            width: 30%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type=submit]{
            width: 15%;
            background-color:steelblue;
            padding: 14px 20px;
            margin: 8px;
            border: none;
            color: azure;  
        }
        input[type=reset]{
            width: 15%;
            background-color: steelblue;
            padding: 14px 20px;
            margin: 8px;
            border: none;
            color: azure;  
        }
    </style>
        <h1 class="center">APPOINMENT REGISTRATION FORM !</h1>
        <form>
            <label for="name">Name</label><br>
            <input type="text" id="name" name="Name" placeholder="Enter your name..."><br>
            <label for="email">Email</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email..."><br>
            <label for="service">Service</label><br>
            <select id="service" name="service" >
                <option value="consultation">Consultation</option>
                <option value="checkup">Checkup</option>
                <option value="treatement">Treatement</option>
            </select><br>
            <label for="mobile number">Mobile number</label><br>
            <input type="number" id="mobile number" placeholder="Enter your number"><br>
            <label for="date">Date</label><br>
            <input type="date" id="date"><br>
            <label for="gender">Gender</label><br>
            <input type="radio" id="Male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <label for="reach">What is the best way for reaching you ?</label><br>
            <input type="checkbox" id="Phone" name="reach" value="phone">
            <label for="phone">Phone</label><br>
            <input type="checkbox" id="email" name="reach" value="email">
            <label for="email">Email</label><br>
            <label for="time">Best time of day for your appoinment :</label><br>
            <input type="checkbox" id="morning" name="time" value="morning">
            <label for="time">Morning</label><br>
            <input type="checkbox" id="afternoon" name="time" value="afternoon">
            <label for="time">After noon</label><br>
            <label for="day">Days of the week yo are available for your appoinment :</label><br>
            <input type="checkbox" id="mond" name="day" value="monday">
            <label for="day">Monday</label><br>
            <input type="checkbox" id="tue" name="day" value="Tuesday">
            <label for="day">Tuesday</label><br>
            <input type="checkbox" id="wed" name="day" value="wednesday">
            <label for="day">Wednesday</label><br>
            <input type="checkbox" id="thur" name="day" value="Thursday">
            <label for="day">Thursday</label><br>
            <input type="checkbox" id="fri" name="day" value="friday">
            <label for="day">friday</label><br>
            <input type="checkbox" id="sat" name="day" value="saturday">
            <label for="day">Saturday</label><br>
            <input type="submit" value="Submit"><input type="reset" value="reset">
        </form>
    </div>
</body>
</html>
