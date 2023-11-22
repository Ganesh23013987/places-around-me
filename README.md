# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1: HTML Document Structure:
Use the <!DOCTYPE html> declaration to specify the document type.
Open the <html> tag.
Inside the <html> tag, add a <title> tag to set the title of the page.
Close the <html> tag.
### Step 2: Body Section:
Open the <body> tag.
Add an <h1> tag for the heading.
Insert an <img> tag with the src attribute pointing to an image file, and use the usemap attribute to associate an image map.
### step 3: Image Map:
Define a <map> tag with the name attribute set to "image_map."
Inside the <map> tag, use <area> tags to define clickable areas on the image.
Each <area> tag should have attributes like alt, title, href, coords, and shape to specify the details of the clickable area.
### step 4:Close HTML Tags:
Close the <body> tag.
Optionally, close the HTML document.
These steps outline the basic structure of your HTML program with an image map.
### step 5:
End program.

## Code:
```
<!DOCTYPE html>
<html>
    <title>images demo</title>
</html>
<body>
    <h1>imagemaps demo</h1>
    <img src="map.jpg" usemap="#image_map">
    <map name="image_map">
      <area alt="Railway station" title="Railway station" href="station.html" coords="949,275,1165,360" shape="rect">
      <area alt="Madras christian college" title="Madras christian college" href="college.html" coords="773,393,1102,507" shape="rect">
      <area alt="Arul Hospital" title="Arul Hospital" href="hospital.html" coords="5,416,168,513" shape="rect">
      <area alt="National Theatre" title="National Theatre" href="theatre.html" coords="663,184,903,258" shape="rect">
      <area alt="GRT jewellers" title="GRT jewellers" href="jewellers.html" coords="1010,-94,1199,13" shape="rect">
    </map>
</body>
```
## Output:
<img width="940" alt="imagemap output" src="https://github.com/Ganesh23013987/places-around-me/assets/147473768/a8b0515c-4bf2-4158-9ec7-2c844be742c7">


## Result:
Above the code is having 5 places is nearing my house.
Thus, the program code is successfully executed.
