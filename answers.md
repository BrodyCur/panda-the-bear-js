1. 
var img = document.querySelector('.profile-image')

img.src = "images/pikachu-drawing.jpg"

1b.
var photo = document.querySelector('.photography')

photo.src = "https://picsum.photos/id/942/325/225"

2. 
var heading = document.querySelector('h1.highlight')

heading.innerText = "Brody Currie"

3.
var title = document.querySelector('#employment .info-title')

title.innerText = 'Something Else'

4. 
var body = document.querySelector('body')

body.style.backgroundColor = 'red'

5. 
var highlights = document.querySelectorAll('.highlight')

highlights.forEach(element => element.style.backgroundColor = 'red')

6. 
var header = document.querySelector('h1')

header.style.fontFamily = 'monospace'

7. 
var action = document.querySelectorAll('.action-container .action-icon-bg')

action.forEach(element => element.style.backgroundColor = 'purple')

8. 
var enterName = document.querySelector('.contact-info')

enterName.placeholder = 'State yourself'

9. 
var enterMsg = document.querySelector('#message')

enterMsg.placeholder = 'state your business'

10. 
var enterName = document.querySelector('.contact-info')

enterName.value = 'your nemesis'

11. 
var enterEmail = document.querySelector('#email')

enterEmail.value = 'koalathebear@gmail.com'

12. 
var button = document.querySelector('#submit')

button.value = 'en garde!'

13. 
var button = document.querySelector('#submit')

button.disabled = true

14. 
var bio = document.querySelector('.bio-info')

bio.parentNode.removeChild(bio)




Part 2
Removing
1. 
var timeTravel = document.querySelector('#time-travel').parentNode

timeTravel.parentNode.removeChild(timeTravel)

Adding
1. 
var pika = document.querySelector('#right-image').firstElementChild

var clone = pika.cloneNode()

document.querySelector('.portfolio-container').appendChild(clone)

2. 
var pika = document.querySelector('#right-image').firstElementChild

var clone = pika.cloneNode()

for (i = 0; i < 10; i++){document.querySelector('.portfolio-container').appendChild(clone)}

3. 
document.querySelector('ul').appendChild(listItem)

const rightSpan = document.createElement('span')

const date = document.createTextNode(Date())

rightSpan.appendChild(date)

listItem.appendChild(rightSpan)

leftSpan.className = 'bio-info-title'

rightSpan2.className = 'bio-info-value'