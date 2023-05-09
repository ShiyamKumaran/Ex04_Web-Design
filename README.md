# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```
<html>


<body>
    <h1> Agricultural Search</h1>
<h1>Rice crop</h1>
<a href="https://www.google.com/search?channel=fs&client=ubuntu&q=rice+crop#imgrc=mjXrdZntoLNJHM">
<img src="001.jpg"
width="200" height="200"></a>
<br>
<br>
<h1>Wheat Crop</h1>
<a href="https://www.google.com/search?channel=fs&client=ubuntu&q=wheat+crop">
<img src="002.jpg"  width="200" height="200"></a>
<br>
<br>
<h1>Plougher</h1>
<a href="https://www.google.com/search?channel=fs&client=ubuntu&q=plougher">
<img src="003.jpg"
width="200" height="200"></a>
<br>
<br>
<br>
<h1>Seeder</h1>
<a href="https://www.google.com/search?channel=fs&client=ubuntu&q=seeder">
<img src="004.jpg"
width="200" height="200"></a>
<br>
<br>
<br>
<h1>Fertilizer</h1>
<a href="https://www.google.com/search?channel=fs&client=ubuntu&q=fertilizer">
<img src="005.jpg"
width="200" height="200"></a>
</body>
</html>
```


## OUTPUT
![1](https://user-images.githubusercontent.com/127816458/236993894-039430e4-ab31-4535-9ad6-cba3ca954ae4.png)
![2](https://user-images.githubusercontent.com/127816458/236993908-e5222009-5b76-44c7-b58b-419cb0f94ffb.png)


## RESULT
 Images as hyperlinks is implemented successfully.
