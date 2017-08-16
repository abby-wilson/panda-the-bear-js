<!-- QUESTION 1 -->
var div = document.querySelector('section > div')
undefined
div
<div>​…​</div>​
var bar = document.querySelectorAll('div.bar-default')
undefined
bar
(4) [div.bar-default, div.bar-default, div.bar-default, div.bar-default]
div.removeChild(bar[2])
<div class=​"bar-default">​…​</div>​

<!-- QUESTION 2 -->
document.querySelectorAll("div > img")
var picture = document.querySelectorAll("div > img")
picture
(2) [img, img]
var pikachu = picture[1]


var pikachuClone = pikachu.cloneNode(true)

document.querySelectorAll('section > div')
var divs = document.querySelectorAll('section > div')
var portfolio = divs[1]
portfolio.querySelector('div')
portfolioDiv = portfolio.querySelector('div')
portfolioDiv.appendChild(pikachuClone)

<!-- QUESTION 3 -->

for (var i=0; i<10; i++) {
  var pikachuClone = pikachu.cloneNode(true)
  portfolioDiv.appendChild(pikachuClone)
                             }
<!-- QUESTION 4 -->

var dateText = document.createTextNode(new Date());
rightSpan.appendChild(dateText)
listItem.appendChild(rightSpan);
document.querySelector('aside > ul')
var bio = document.querySelector('aside > ul')
bio.appendChild(listItem)
