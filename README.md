# Design of a Standard Calculator

## AIM:
To design a web application for a standard calculator

## DESIGN STEPS:

### Step 1:
Clone the github repository and create a new django project.

### Step 2:
Make Changes in settings.py

### Step 3:
Create a new html file and use a CSS for colours

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:

Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
``` html
<!DOCTYPE html>
<html>
    <head>
        <title>AR Calculator</title>
        <style type="text/css">
        table{
            border: 1px solid black;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 1px solid black;
            padding: 20px 45px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color:rgb(130, 193, 238);
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:rgba(255, 64, 0, 0.396);">Simple Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="+" onclick="result.value+='+'"/></td>
                <td><input type="button" value="1" onclick="result.value+='1'"/></td>
                <td><input type="button" value="2" onclick="result.value+='2'"/></td>
                <td><input type="button" value="3" onclick="result.value+='3'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="-" onclick="result.value+='-'"/></td>
                <td><input type="button" value="4" onclick="result.value+='4'"/></td>
                <td><input type="button" value="5" onclick="result.value+='5'"/></td>
                <td><input type="button" value="6" onclick="result.value+='6'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="*" onclick="result.value+='*'"/></td>
                <td><input type="button" value="7" onclick="result.value+='7'"/></td>
                <td><input type="button" value="8" onclick="result.value+='8'"/></td>
                <td><input type="button" value="9" onclick="result.value+='9'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="Clear All" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```
### Server Output:
![Screenshot 2023-05-21 122530](https://github.com/Gokul0117/standard-calculator/assets/121165938/e1c7f4c3-3bd2-4184-86e2-f85a54fabd04)


## OUTPUT:
![Screenshot 2023-05-21 122701](https://github.com/Gokul0117/standard-calculator/assets/121165938/9b090cfe-557c-4f4d-9dfb-66e73e5e9a83)




## Result:
Simple Calculator is ready to use.
