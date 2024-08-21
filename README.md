<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="mycs.css">
</head>
<body>
    <div class="center">
        <h1 id="had">Registration Form</h1>
        <div class="sub class">
        <form action="/server">
        <label for="name">Name:</label>
        <input type="text" name="name" id="name" placeholder="Enter Name"><br><br>
        <label for="rollno">Roll Number:</label>
        <input type="text" name="rollno" id="rollno" placeholder="Enter RollNumber"><br><br>
        <label for="phno">Phone Number : </label>
        <input type="number" name="phno" id="phno" placeholder="Enter Phone Number"><br><br>
        <label for="age">Age:</label>
        <input type="number" name="age" id="age" placeholder="Enter age"><br><br>
        <label for="gender">Gender:</label>
        <input type="radio" name="gender" id="male" value="male">
        <label for="male">Male</label>
        <input type="radio" name="gender" id="female" value="female">
        <label for="female">Female</label>
        <input type="radio" name="gender" id="transgender" value="transgender">
        <label for="transgender">transgender</label><br><br>
        <label for="emil">Enter EmailId:</label>
        <input type="text" name="email" id="emil" placeholder="ex:abc@gmail.com"><br><br>
        <label for="country">Country:</label>
        <select name="country" id="country">
            <option> </option>
           <option value="India">India</option>
           <option value="Usa">Usa</option>
           <option value="Nepal">Nepal</option>
        </select><br><br>
        <label for="area">Enter Address : </label><br>
        <textarea name="area" id="area" rows="2" cols="30"></textarea><br><br>
        <button>Submit</button>
      </div>
    </form>
    </div>
</body>
</html>
