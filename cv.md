# Alena Sharai

### Junior Fullstack developer

### Contact Information

- **Phone:** +995 595 092569
- **E-mail:** exultantislupus@gmail.com
- **Telegram:** [@exultantislupus](https://t.me/exultantislupus)
- **Git Hub:** [@ExuLu](https://github.com/ExuLu)
- [Linkedin](https://www.linkedin.com/in/alena-sharai/)

### About me

I used to work as a copywriter in IT startup in Minsk and with grow of our company I had been growing to content manager as well. But then I realized that it was not enough for me. At least, I wanted understand what are this all technical stuff my collegues were talking about. That's why I've started my developer way. And I belive that one day my code will help save the world ;)

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

### Projects and Courses

* **The Ultimate React Course** (Georgia, Tbilisi) - React Frontend Developer 11/2023 - (in progress)

  - web development with React, using hooks as useState, useEffect and custom hooks, external libraries and APIs
  - create [Eat&Split](https://delightful-faloodeh-a5eecd.netlify.app/) app for split bill with friends, using React hooks
  - create [Weather](https://lucky-maamoul-9c3017.netlify.app/) app using previous React syntax with Classes and weather API

* **Web Development Bootcamp** (Georgia, Tbilisi) — Web Developer
  08/2023 - 10/2023

  - web development with pure HTML, CSS and Bootstrap
  - simple web games development with JavaScript, jQuery, DOM, CSS and HTML
  - restful API development using Axious and asynchronous approach
  - backend development for [ToDoList](https://todolist-gsxq.onrender.com) project with Node.js, Express.js, EJS, MongoDB (via - mongoose) and its deployment to cloud
  - development of [Blog Website](https://demoblog-i8ht.onrender.com/) using Node.js, Express.js, EJS, MongoDB (via mongoose)
  - development of [Secrets](https://secrets-ivlb.onrender.com/) web application using security instruments as Passport.js (to - realize Open Authorization standard), sessions, hashing; implementing Google and Facebook strategies for authorization
  - development of [Keeper](https://exulu-keeper-demo.netlify.app/) website using React framework and Material UI library

* **JavaScript Core Course** (Georgia, Tbilisi) — JavaScript Developer
  05/2023 – 08/2023
  - [Mapty](https://inquisitive-babka-58ac42.netlify.app/) - this app allows you log your running or cycling workouts and tag them on the map; developed with JavaScript, DOM, open source API ([Leaflet](https://leafletjs.com/reference.html)), using OOP approach
  - [Forkify](https://forkify-exulu.netlify.app/) - this app has a lot of different recipes which you can find by keywords and allows you to add your own dishes; developed with JavaScript, DOM, restful API, external libraries, using OOP approach and MVC pattern
  - work with built-in and external libraries using asynchronous JS (Promises, Async/Await, Axious, AJAX)
    implement branching strategies using Git

### Education

### Languages
