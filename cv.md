# Yevgeniy Mineyev

## Contacts

- **Location**: Shymkent, Kazakhstan
- **Phone numer**: +7 (747) 9858504
- **E-mail**: fromarys@gmail.com
- **[Codewars Profile](https://www.codewars.com/users/fromarys)**

## Photo
![my photo](myphoto.jpg)

## About me
Hi! My name is Yevgeniy. At the moment I work as am HTML coder in Service Plus company in Shymkent. But my education, both Bachelor and Master degrees are related to totally different sphere - Organic Chemistry. After several years of working in Chemistry industry I decided to dedicate my life to Web-Development.

## Skills
- HTML
- CSS, SCSS
- JavaScript
- Git, GitHub
- Adobe Photoshop

## Code Example
This code is a solution for Kata "[Look and say numbers](https://www.codewars.com/kata/53ea07c9247bc3fcaa00084d)" from CodeWars
```function lookAndSay(data,len, arr = []){
  let str = '';
    if (len == 0) {
      return arr;
  } else {
      data.match(/(.)\1*/g).forEach(e => str += e.length + e[0]);
      arr.push(str);
      return lookAndSay(str, len - 1, arr);
  }
}
```