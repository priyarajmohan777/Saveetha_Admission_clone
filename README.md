# Saveetha_Admission_clone
## Date: 09-07-2025

## Objective:
To design a landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS. This activity reinforces skills in layout design, form creation, user input handling, responsive structure, and visual styling based on a real-world example.

## Tasks:
#### 1. Analyze the Landing Page Layout:
Observe the split-screen layout with a promotional section on the left and a form on the right.

Note the use of background images, text styling, and branding elements.

#### 2. Create the HTML Structure:
Use semantic tags like ```<section>, <header>, <form>, and <footer>``` to organize content.

Structure the form with input fields such as name, email, phone, password, city, state, course, specialization, captcha, and checkbox.

#### 3. Add Form Functionality:
Include appropriate input types (text, email, tel, password, select, etc.) with placeholders and labels.

Use the <button> element for the "APPLY NOW" action.

#### 4. Apply CSS Styling:
Implement a split layout using flexbox or grid.

Style the form elements with padding, shadows, background colors, and rounded borders.

Include hover effects and button transitions to match the original look.

#### 5. Incorporate Images and Branding:
Add the institution logo and use matching fonts and colors.

Place a background image or blurred overlay behind the form content if needed.

#### 6. Ensure Responsiveness:
Make sure the page adapts to different screen sizes using media queries.

Maintain readability and layout integrity on both desktop and mobile.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Saveetha Admission Enquiry</title>
        <link rel="stylesheet" href="styles.css">
    </head>

    <body>
        <div class="bg">
          <div class="admission-card">
          <form>
            <h2>Admissions Open 2025</h2>
            <input type="text" name="name" placeholder="Enter Name" required>

            <input type="text" name="email" placeholder="Enter Email Address" required>

           <div class="row">
                  <select class="phone-code" required>
                        <option value="+91">+91</option>
                        <option value="+93">+93</option>
                        <option value="+61">+61</option>
                        <option value="+60">+60</option>
                        <option value="+65">+65</option>
                 </select>

                <input type="text" name="mobile number" placeholder="Enter Mobile Number" required>
          </div>


            <input type="text" name="mobile number" placeholder="Enter Mobile Number" required>

            <input type="password" name="password" placeholder="Any Password of Your Choice" required>

            <div class="row">
            <select required>
                <option value="Tamil Nadu">Tamil Nadu</option>
                <option value="Kerala">Kerala</option>
                <option value="Andhra Pradesh">Andhra Pradesh</option>
                <option value="Delhi">Delhi</option>
                <option value="Odisha">Odisha</option>
                <option value="" selected>State *</option>
            </select>

            <select required>
                <option value="Chennai">Chennai</option>
                <option value="Alapuzha">Alapuzha</option>
                <option value="Vijayawada">Vijayawada</option>
                <option value="North Delhi">North Delhi</option>
                <option value="Bhubaneswar">Bhubaneswar</option>
                <option value="" selected>City *</option>
            </select>
            </div>

            <div class="row">
            <select>
                <option value="B.E. or B.Tech">B.E. or B.Tech</option>
                <option value="M.E.">M.E.</option>
                <option value="MBA">MBA</option>
                <option value="Lateral Entry">Lateral Entry</option>
                <option value="" selected>Course *</option>
            </select>

            <select required>
                <option value="CSE">CSE</option>
                <option value="AIDS">AIDS</option>
                <option value="AIML">AIML</option>
                <option value="IT">IT</option>
                <option value="CSE(CS)">CSE(CS)</option>
                <option value="ECE">ECE</option>
                <option value="EEE">EEE</option>
                <option value="MECH">MECH</option>
                <option value="BIOMED">BIOMED</option>
                <option value="" selected>Specialization *</option>
            </select>
            </div>

            <input type="text" name="captcha" placeholder="Enter Captcha">
            
            <label class="checkbox">
            <input type="checkbox"> I authorise Saveetha Engineering College & its representatives to contact me with updates and notifications via Email/SMS/What'sApp/Call. This will override DND/NDNC *
            </label>
            <input type="submit" value="Apply Now" class="apply"> 
            
            <p>Already have an Account? <a href="index.html">Login</a></p>
              <p>Resend Verification Email</p>

             
            
         </div>
         
       </div>

      
           </form>
    </body>
</html>
```

## CSS Code:
```
body
{
    display:flex;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-image: url(banner1.png);
    background-repeat: no-repeat;
    background-size:contain;
    justify-content: flex-end;
    height: 100vh; 
    overflow:hidden;
    margin:0;
    
}


.bg
{
   width: 28%;
   height: max-content;
   margin:20px 0px 0px 20px;
}

.admission-card
{
    overflow-y: auto;
    max-height:70vh;
    border: 5px s rgba(21, 22, 22, 0.763);
    border-radius:20px;
    justify-content: flex-end;
    margin-left: auto; 
    padding: 20px;
    background-color: rgba(21, 22, 22, 0.763);
    box-shadow:0px 0px 6px 10px rgba(23, 23, 23, 0.6);
   
    
}

input, select {
    display: block;
    width: 100%;
    margin: 10px 0;
    padding: 8px;
    box-sizing: border-box;
}

h2
{
    text-align:center;
    color:azure;
}

.row
{
    display:flex;
    gap:10px;
}

.phone-code {
  width: 30%;
}

.row input[type="text"] {
  width: 70%;
}

.checkbox {
  display: flex;
  align-items: flex-start;
  font-size: 14px;
  color: white;
  line-height: 1.4;
  margin-top: 10px;
}

.checkbox input {
  width: auto;
  margin-right: 8px;
  margin-top: 3px;  
}


.apply
{
    background-color: darkgoldenrod;
    font-weight: bold;
    
}

p
{
    text-align: center;
    color:azure;
    font-weight:bold;
}
```
## Output:
![image](https://github.com/user-attachments/assets/bcbf9625-b12a-4614-af8f-fee0463612df)


## Result:
A landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS is designed successfully.
