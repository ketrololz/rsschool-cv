# Bogdan Nurgatin #
## Contacts: ##
* **telegram:** [@ketrolz](https://t.me/ketrolz)
* **mail:** ketrolzzz@gmail.com
* **discord:** ketrolz

## A few words about me: ##

![me](/rsschool-cv/IMG_0759_3.jpg)

At the moment I am a graphic and web designer, but soon you will know me as a front-end developer, I hope :) Self—study and discipline are my strengths, I also get along with people easily and like to work in a team.

## Skills: ##

* **HTML**
* **CSS**
* **Figma**
* **Adobe PS, AI, InDesign, After Effects**
* **C# (basic)**
* **Git (learning)**
* **JavaScript (learning)**

## Code example: ##
*А small mini-game in which you need to calculate the sum of two numbers:*
```
const getNumber = () => Math.round(Math.random() * 100);

const playRound = () => {
  const numberOne = getNumber();
  const numberTwo = getNumber();
  const sum = numberOne + numberTwo;

  const userAnswer = prompt(`Enter the sum of the numbers: ${numberOne} and ${numberTwo}`);

if (Number(userAnswer) === sum) {
  return true;
} else {
  return false;
}
}
  
const playGame = () => {
for (let i = 0; i < 3; i++) {
const isCorrect = playRound();
if (isCorrect) {
  alert('Right!');
} else {
  alert('It seems you made a mistake :(');
  return;
}
}
  alert('You won!');
}

const button = document.querySelector('button');
button.addEventListener('click', playGame);
```

## Projects: ##
* **[CV](https://ketrololz.github.io/rsschool-cv/cv)**

## Education: ##

* **Hexlet:** The preparatory course of the FRONTEND DEVELOPER
* **FreeCodeCamp:** [Responsive Web Design](https://www.freecodecamp.org/certification/fcc8e58e9dd-edd4-4172-aa3e-9d986a35b0cd/responsive-web-design)

## English level: ##
* **B1/B2** (I can read English quite well, but I have great difficulty communicating)