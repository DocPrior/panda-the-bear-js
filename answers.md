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
6. var headingText = document.querySelector("h1")
undefined
headingText
<h1 class=​"highlight" style=​"background:​ blue;​">​Sara​</h1>​
headingText.style.fontFamily = "monospace"
"monospace"
7. sideButton = document.querySelectorAll(".action-icon-bg")
(2) [a.action-icon-bg, a.action-icon-bg]
sideButton.forEach(function(button) {button.style.background = "yellow"})
undefined
8. var nameText = document.querySelector('input[placeholder = "Name"]')
undefined
nameText
<input type=​"text" name=​"name" class=​"contact-info" id=​"name" placeholder=​"Name">​
nameText.placeholder = "Identify Yourself"
"Identify Yourself"
9. var messageText = document.querySelector("#message")
undefined
messageText
<textarea name=​"message" id=​"message" placeholder=​"Message">​</textarea>​
messageText.placeholder = "state your business"
"state your business"
10. var nameText = document.querySelector("#name")
undefined
nameText
<input type=​"text" name=​"name" class=​"contact-info" id=​"name" placeholder=​"Identify Yourself">​
nameText.value = "your nemesis"
"your nemesis"
11. var emailText = document.querySelector("#email")
undefined
emailText
<input type=​"email" name=​"email" class=​"contact-info" id=​"email" placeholder=​"Email">​
emailText.value = "koalathebear@gmail.com"
"koalathebear@gmail.com"
12. var sumbitButton = document.querySelector("#submit")
undefined
sumbitButton
<input type=​"submit" name=​"submit" id=​"submit" value=​"Submit">​
sumbitButton.value = "Engage!"
"Engage!"
13. sumbitButton.disabled = "true"
"true"
14. var sideBar = document.querySelectorAll(".bio-info-value")
undefined
sideBar
(3) [span.bio-info-value.bio-info-name, span.bio-info-value.bio-info-location, span.bio-info-value.bio-info-phone]
sideBar.forEach(function(bar) {bar.innerText = ''})
undefined


Part 2

1. timeTravel
<div class=​"bar-filled highlight" id=​"time-travel">​…​</div>​
timeTravel.remove()
undefined

2. var pikachu = document.querySelector("#right-image img[src]")
undefined
pikachu
<img src=​"images/​pikachu-drawing.jpg" alt=​"Pikachu" title=​"Pikachu">​
var pikachuClone = pikachu.cloneNode()
undefined
pikachuClone
<img src=​"images/​pikachu-drawing.jpg" alt=​"Pikachu" title=​"Pikachu">​
var portfolioContainer = document.querySelector(".portfolio-container")
undefined
portfolioContainer
portfolioContainer.appendChild(pikachuClone)
<img src=​"images/​pikachu-drawing.jpg" alt=​"Pikachu" title=​"Pikachu">​
for (i = 0; i < 10; i++) {portfolioContainer.appendChild(pikachu.cloneNode())}

3. var listItem = document.createElement('li');
undefined
var leftSpan = document.createElement('span')
undefined
var lastUpated = document.createTextNode('Page Last Upated On');
undefined
leftSpan.appendChild(lastUpated);
"Page Last Upated On"listItem.appendChild(leftSpan);
<span>​Page Last Upated On​</span>​
listItem.appendChild(leftSpan);
<span>​Page Last Upated On​</span>​
var rightSpan = document.createElement('span');
undefined
var date = document.createTextNode(Date.now());
undefined
var date = document.createTextNode(Date.now());
undefined
rightSpan.appendChild(date)
"1499354687813"
listItem.appendChild(rightSpan);
<span>​1499354687813​</span>​var
wholeList = document.querySelector('ul')
undefined
wholeList
<ul class=​"bio-info">​…​</ul>​
wholeList.appendChild(listItem);
<li>​…​</li>​
