# Alexey Novgorodov
__Junior Frontend Developer__

## __Contacts__
- Phone: +7-977-877-06-85
- Email: [novgorodovav@gmail.com](mailto:novgorodovav@gmail.com)
- GitHub: [@novgorodovAV](https://github.com/novgorodovav)
- Telegram: [@anovgorodov](https://t.me/anovgorodov)

## __About Me__
I'm 34 years old. There is a small business that works without my participation. Therefore, I decided to set aside time to gain new programming skills. Strengths: responsible attitude to tasks, experience in his business and love for continuous learning. From training as a Frontend Developer, I expect interesting tasks and constant development. Now I am studying at RS School on the course "JavaScript/Front-end. Stage 0"

## __Skills__
* HTM, CSS
* JavaScript (Basic)
* Git, GitHub
* VS Code

## __Code Example__
```javascript
let phrases = [
    { text: 'отправить другу смешную гифку', image: 'https://code.s3.yandex.net/web-code/procrastinate/1.gif' },
    { text: 'посмотреть скидки на авиабилеты', image: 'https://code.s3.yandex.net/web-code/procrastinate/2.png' },
    { text: 'разобраться, о чём поют рэперы', image: 'https://code.s3.yandex.net/web-code/procrastinate/3.png' },
  ];
  
  function getRandomElement(arr) {
    let randIndex = Math.floor(Math.random() * arr.length);
    return arr[randIndex];
  }
  
  let button = document.querySelector('.button');
  let phrase = document.querySelector('.phrase');
  let advice = document.querySelector('.advice');
  let image = document.querySelector('.image');
  
  button.addEventListener('click', function () {
    let randomElement = getRandomElement(phrases);
    smoothly(phrase, 'textContent', randomElement.text);
    smoothly(image, 'src', randomElement.image);
  
    if (randomElement.text.length > 40) {
      advice.style.fontSize = '33px';
    } else {
      advice.style.fontSize = '42px';
    }
  });
  
  for (let i = 0; i <= 2; i = i + 1) {
    smoothly(phrase, 'textContent', phrases[i].text);
    smoothly(image, 'src', phrases[i].image);
  }
```

## __Experience__
1. Made websites on Tilda
2. Promoted website my own business (PPC advertising, SMM и SEO)
3. JavaScript application "Procrastinate" (study project) - [GitHub Pages](https://github.com/novgorodovav/practicum_procrastinate), [GitHub](https://github.com/novgorodovav/practicum_procrastinate)

## __Education__
- University degree
- Сourse "Web developer" (Yandex Practicum) - _in progress_
- Сourse " JavaScript/Front-end" (RS School) - _in progress_

## __Languages__
* English - _pre-intermediate_
* Russian - _native_