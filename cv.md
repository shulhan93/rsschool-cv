# Shulhan Andrei
 - **telegram**:  [@shulhan](http:/t.me/shulhan)
 - **mail**: shulhan.andrei@gmail.com
## Skills 
- HTML
- CSS, SASS
- БЭМ
- JS, JQUERY
- GULP
- GIT

## Code examples
```sh
export default (str) => {
  let acc = 0;
  for (let i = 0; i < str.length; i += 1) {
    const symbol = str[i];
    acc = symbol === '(' ? acc + 1 : acc - 1;
    if (acc < 0) {
      return false;
    }
  }
  return acc === 0;
};
```

## Education
- Sukhoi State Technical University of Gomel
- Courses:
    - [hexlet.io](https://hexlet.io/) (frontend-end)
    - [htmlacademy.ru](https://htmlacademy.ru/) 
    - [udemy.com](https://www.udemy.com/course/webdeveloper/) (web developer)
    - [glo-academy.ru](https://glo-academy.ru/web-start/) 