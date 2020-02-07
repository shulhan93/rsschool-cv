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