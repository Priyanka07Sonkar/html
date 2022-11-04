# FORM DESIGNING
1. form design krme ke liye sbse phle hm 
    <form> tag ka use krte hai.
2.  <from> tag mein 2 properties mainly hoti hai,
3. action-> form ke data ko kha bhejna jb form ko
    submit kiya jayega.
4. method-> ismein 2 values hoti hai
5. get-> data ko url mein show krta hai jb form ko
    submit kiya jata hai.
6. post-> data ko url mein show nhi krta hai jb form ko
    submit kiya jata hai.
```html
  <form action="" method="get/post">
  ...  
  </form>
```
1. user se string type ka kch bhi input lena hota hai
    to hm log type="text"
2. placeholder="temporay infornation batata hai user ko ki
    kya box mein fill krna hai"
3. agr hmko password input krana hota hai to hm input
    type="password" likte hai.
4. agr mujhe multiple option mein se koi ek option correct choose
    krna input type radio use krte hai. aur ismein name ki value 
    same honi chahiye.
5. agr mujhe more than one option correct krna hai to hm input type
    checkbox use krte hai.
6. input tag vo single line bs input leta hai agr mujhe multiple
    line input lena hai to hm textarea ka use krte hai.

    

```html
<html>
    <head>
        <title>
            ragistration form
        </title>
        <style>
            
        </style>
    </head>
    <body>
        <h1>Registration form</h1>
        <form action="" method="">
            <label>first Name : </label>
            <input type="text" placeholder="enter your first name" value="" required>
            <br><br>
            <label>last Name : </label>
            <input type="text" placeholder="enter your last name" value="" required>
            <br><br>
            <label>Password : </label>
            <input type="password" placeholder="enter your password" value="" required>
            <br><br>
            <label>Email add: </label>
            <input type="email" placeholder="enter your email address" value="" required>
            <br><br>
            <label>Gender : </label>
            <input type="radio" name="gender">Male
            <input type="radio" name="gender">Female
            <input type="radio" name="gender">Transgender
            <br><br>
            <label> Langauge : </label>
            <input type="checkbox">Hindi
            <input type="checkbox">English
            <input type="checkbox">C++
            <input type="checkbox">JAVA
            <input type="checkbox">PYTHON
            <br><br>
            <label>Pincode : </label>
            <input type="number">
            <br><br>
            <label>Address : </label>
            <textarea rows="5" cols="20" placeholder="enter your address"></textarea>
            <br><br>
            <label>Select your country:</label>
            <select>
                <option readonly>select city</option>
                <option>Doharighat</option>
                <option>Mau</option>
                <option>Azamgarh</option>
            </select>
            <br><br>
            <input type="submit" value="submit">
        </form>
    </body>
</html>
```
