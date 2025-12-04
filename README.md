<!DOCTYPE html>
<html lang="en">
<head>
    
 <title>Document</title>
    <link rel="stylesheet" href="form.css">
</head>
<body>
    <div class="container"></div>
    <form action=" " method="post">
        <fieldset>
        <legend> <u><h3><b>Personal Information</b></h3></u></legend>
        <label for="USERNAME">USERNAME:</label></br>
        <input type="text" id="USERNAME" name="USERNAME" rows="1" required></br>

        <label for="EMAIL">EMAIL:</label></br>
        <input type="email" id="EMAIL" name="EMAIL" rows="1" required></br>

        <label for="PASSWORD">PASSWORD:</label></br>
        <input type="password" id="PASSWORD" name="PASSWORD" rows="1" required></br>
        <label for="gender">GENDER:</label></br>

        <input type="radio" name="GENDER" value="male"> Male</br>
        <input type="radio" name="GENDER" value="female"> Female</br>
        <label for="city">CITY:</label></br>
        <select id="city" name="city"></br>
            <option value="Mohali">Mohali</option>
            <option value="Chandigarh">Chandigarh</option>
            <option value="Jalandhar">Jalandhar</option>
        </select><br>
        <label for="ADDRESS">Address:</label></br>
        <textarea id="ADDRESS" name="ADDRESS" rows="3" cols="30">



        </textarea><button type="submit">Submit</button><br>
       <b>For more info visit</b> <a href="https://www.lpu.in/">LPU</a><br>

         </fieldset>
    </form>

</body>
</html>
h2 {
    color: rgb(84, 71, 122);
    
    background-color: chartreuse;
}
p {
    color: rgb(21, 5, 69);
    
    font-size: 16px;
    line-height: 1.5;
    
}
body{
    background-color: rgb(113, 199, 171);
    text-align: center;
    
}

.box{
    width: 300px;
    height: 300px;
    background-color: rgb(255, 255, 255);

}
th, td {
    color: rgb(21, 5, 69);
    border: 1px solid rgb(132, 38, 214);
    font-size: 20px;
    text-align: center;
    /*background-color: rgb(7, 132, 227);*/
}
    
tr:nth-child(even)
 {
    background-color: rgb(7, 132, 227);
}
tr:nth-child(odd)
 {
    background-color: rgb(255, 255, 255);
}
tr:hover
 {
    background-color: rgb(255, 255, 0);
}

# css
