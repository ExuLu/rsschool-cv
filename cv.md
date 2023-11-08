# Alena Sharai

### Junior Fullstack developer

### Contact Information

- **Phone:** +995 595 092569
- **E-mail:** exultantislupus@gmail.com
- **Telegram:** [@exultantislupus](https://t.me/exultantislupus)
- **Git Hub:** [@ExuLu](https://github.com/ExuLu)
- [Linkedin](https://www.linkedin.com/in/alena-sharai/)

### About me

I used to work as copywriter in IT startup in Minsk and with grow of our company I had been growing to content manager as well. But then I realized that it was not enough for me. At least, I wanted understand what are this all technical stuff my collegues were talking about. That's why I've started my developer way. And I belive that one day my code will help save the world ;)

And, you know:

> "With great power comes great responsibility." © Uncle Ben

### My Skills

- HTML, CSS
- JavaScript
- Git, GitHub
- Node.js, Express.js
- MongoDB
- React

### Code Examples

**Task description:**

Write a function named `first_non_repeating_letter` that takes a string input, and returns the first character that is not repeated anywhere in the string.

**My solution**

```
function stringRepeat(s) {
  const array = s.split('');
  const comparedArray = [...array];
  let newArray = [...array];

  array.forEach((element, elementIndex) => {
    comparedArray.forEach((item, itemIndex) => {
      if (
        element.toLowerCase() === item.toLowerCase() &&
        elementIndex !== itemIndex
      )
        newArray = newArray.filter((letter) => letter !== item);
    });
  });

  return newArray.length > 0 ? newArray.at(0) : '';
}
```

_More code examples you can see on my [GitHub](https://github.com/ExuLu)_

### Work Experience

### Education

### Languages
