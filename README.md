<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h3>Registration Form</h3>
    <form action="/action.php">
    <input type="text" placeholder="Username">
    <br></br>
    <input type="password" placeholder="password">
    <br></br>
    <h3>Select your class :</h3>
    <label for="101">
     <input type="radio" value="class XI" name="class" id="101" >Class XI
    </label>
    <br></br>
    <label for="102">
     <input type="radio" value="class XII" name="class" id="102" >Class XII
    </label>
    <h3>Select your fav subjects :</h3>
    <lable for="Physics">
        <input type="checkbox" value="Physics" name="Class" >Physics
       </lable>
       <br>
       <br>
       <label for="Chemistry">
        <input type="checkbox" value="class XII" name="Class" >Chemistry
       </label>
       <br></br>
        <b>Select your city</b>
       <select name="city">
        <option city="Delhi">Delhi</option>
        <option city="Banglore">Banglore</option>
        <option city="Hydrabad">Hydrabad</option>
        <option city="pune">pune</option>
       </select>
       <br></br>
       <h4> Feedback:</h4>
    <textarea name="feedback" id="101" placeholder="Please give your feedback here" height="200" rows=5 >Feedback</textarea>  
    <br></br> 
    <input type ="Submit" value="Submit">
    </form>
</body>
</html>
