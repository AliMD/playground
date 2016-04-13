##Classing Block Elements  
The HTML class attribute makes it possible to define equal styles for "equal" <div> elements:  
###London  
>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.
Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.  

###Paris
>Paris is the capital and most populous city of France.
Situated on the Seine River, it is at the heart of the Île-de-France region, also known as the région parisienne.
Within its metropolitan area is one of the largest population centers in Europe, with over 12 million inhabitants.  


###Tokyo
>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.
It is the seat of the Japanese government and the Imperial Palace, and the home of the Japanese Imperial Family.
The Tokyo prefecture is part of the world's most populous metropolitan area with 38 million people and the world's largest urban economy.  

####Example  
```html
<!DOCTYPE html>
<html>
<head>
<style>
div.cities {
    background-color:black;
    color:white;
    margin:20px;
    padding:20px;
}
</style>
</head>
<body>

<div class="cities">
<h2>London</h2>
<p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over  13 million inhabitants.</p>
</div>

<div class="cities">
<h2>Paris</h2>
<p>Paris is the capital and most populous city of France.</p>
</div>

<div class="cities">
<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area,
and the most populous metropolitan area in the world.</p>
</div>

</body>
</html>
```
###[try it yourself] (http://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_capitals)  
##Classing Inline Elements

The HTML class attribute also makes it possible to define equal styles for "equal" <span> elements:
####Example
```html
<!DOCTYPE html>
<html>
<head>
<style>
span.note {font-size:120%;color:red;}
</style>
</head>
<body>

<h1>My <span class="note">Important</span> Heading</h1>
<p>This is some <span class="note">important</span> text.</p>

</body>
</html>
```
###[try it yourself] (http://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_span)  



