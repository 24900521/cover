# Ex.05 Book Front Cover Page Design
## Date:08-04-25

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
<title>Book cover page</title>

```
<style>
    body {
        background-size: 494px;
        background-image: url('bake.jpg');
        background-position:center;
        width: 400px;
        height: 650px;
        margin-left: auto;
        margin-right: auto;
        
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-repeat: no-repeat;
    }

    h1 {
        text-align: center;
        color: black;
    } 
    .imge > img {
        height: 250px;
        width: 250px;
        float: right;
    }.word{
        padding-top: 2cm;
        padding-left:1 ;
    }
    .iyal{
        padding-left: 8cm;
        margin: top 20px;;
    }
    .second-image{
        border: 5px solid #336699; /* Set the border width, style, and color */
        border-radius: 8px;
        border-color:orangered;
        float: left;
    }
     .last{
  text-align: left;
  padding-right:270px;
  padding-bottom: 40x;
  margin-bottom:100px;

}
</style>
```
SEC INSITE
```
<h1><b>Full Stack Development<br><br>
    For beginners</b></h1>
<div class="imge">
    <img src="./cov5.webp"  alt="">
</div>
<div class="word">
    <h3>
        <ul> <li>Front end</li>
            <br>
            <li>Back end</li>
            <br>
            <li>Database</li>
        </ul>
    </h3>
</div>
<div class="iyal"><img class="second-image" src="./,...jpg" alt="" height="100" width="80" allign="right">

</div>

<div class="last"><h1>Vignesh V</h1>
</div>
```
## OUTPUT:

![Add a subheading](https://github.com/user-attachments/assets/60b0ccd1-959d-4a0d-b403-aaed15c3d656)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
