1. var pic = document.querySelector('img[src]')
undefined
pic
<img src=​"images/​self-portrait-grassbg.jpg" alt=​"Self Portrait" title=​"Self Portrait" class=​"profile-image">​https://placebear.com/200/300​</img>​
pic.src = "https://placebear.com/200/300"
"https://placebear.com/200/300"

1. var skyPic = document.querySelector("#left-image")
undefined
skyPic.firstElementChild.src = "https://placebear.com/200/300"
"https://placebear.com/200/300"

2. var myHeading = document.querySelector("h1")
undefined
myHeading
<h1 class=​"highlight">​Panda The Bear​</h1>​
myHeading.innerText = "Sara"
"Sara"

3. var employment = document.querySelector("#employment .info-title")
undefined
employment
<h3 class=​"info-title">​<i class=​"icon-suitcase">​…​</i>​" &nbsp; Employment"</h3>​
employment.innerText = "something else"
"something else"

4. document.body.style.background ="pink"
"pink"
5. var highlight = document.querySelectorAll(".highlight")
undefined
highlight.forEach(function(light) {light.style.background = "blue"})
