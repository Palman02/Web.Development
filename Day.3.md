Day 3
===
Today I studied with the video in englsih too   

English class is hard but really cool   
My computer professor, Indian, says that all about computer should be learned in english   
Now I got some reason why he say that   
If we learn in some technology in other language like korean, we should learn it again when we work on forguin people   
anyway, todays video was this   

https://www.youtube.com/watch?v=gBi8Obib0tw   

* * *

Start to learn about CSS
---
   
If you says that HTML is boon of human, CSS is skin   
It can design how your website is looked by others   
Content of HTML was ended in a day but CSS isn't   
HTML include about 10~20 tag but CSS is different because almost all of design of web is developed in CSS
So CSS need a lot of tags   

```
body{
	background: #999;
	font-family: arial;
}

h1, h2, li{
	color: #555;
}

a{
	color: green;
}

p{
	background: #666;
	color: white;
	padding: 10px;
}

.secondary{
	background: none;
	color: #777;
}

#special{
	background: red;
	color: white;
}
```

* * *

How to put the CSS code to HTML
---

There is two way to put CSS code to your HTML code   

* Put on HTML code
  you can put the CSS code to your HTML code line directly   
  That it, simple way but when you need to change the design, you have to change all of the code used such CSS code   
  
  ```
  <style type="text/css">
  ##Your CSS code
  </style>
  ```      
  
     
  * * *

  
* Link your CSS code   
     
  Way that link the CSS code   
  You can fix all of desigh what CSS code is linked   
  
 
  ```
  <link href="style/CSScodefilename.css"
  rel="stylesheet"
  type="text/css"
  />
  ```   
  
  * * *

  
Tags
--- 
  
   
  * * *

* ```background:#color```   
  code that makes your website color
  if you use this on words, It change word background color
     
  * * *
 
* ```<font-family>```   
  property specifies the font for an element.
     
  * * *

* ```<Color>```   
  make font color   
     
  * * *

Class, id
--- 

* ```.ClassName```   
  Class combine codes in one and change it   
  You can combine those like this   
  
  ```
  <p class="ClassName">
  Content
  </p>
  ```
  
  And you can set the design that like this
  
  
  ```
  .ClassName{
  color= #999;
  }
  ```

* ```#IdName```
  
  Id is same to class but it can be used one each code   
  
  ```
  <p Id="IdName">
  Content
  </p>
  ```
  
  And you can set the design that like this
  
  
  ```
  #IdName{
  color= #999;
  }
  ```
