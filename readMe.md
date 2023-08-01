# Yummy Sushi is fully responsive HTML & CSS website with animations.

A project to practice CSS, tutorial by [javascriptmastery](https://www.youtube.com/watch?v=QRrPE9aj3wI)

This project covers:-

- CSS variables
- Import CSS files into other CSS files
- Use flex and position properties in CSS
- Create smooth and subtle animations
- Use the BEM naming method
- Maintain a well-organized file and folder structure
- Embrace the principles of writing clean code

## CSS stying using [BEM](https://sourcedcode.com/blog/css/what-is-bem-with-examples)

BEM stands for Block, Element, Modifier, and it is a naming convention or methodology used in CSS to create a modular and maintainable codebase.
BEM helps to organize CSS classes by providing a clear and consistent structure for naming selectors.

- Block which holds everything (elements) inside and acts as a scope.
- Element which acts as a special part of the component.
- Modifier which adds additional styles to a specific element(s).
  
  ![Breakdown of BEM](image.png)

## Animation using [AOS library](https://www.npmjs.com/package/aos)

- `npm install aos`
- import aos

```
import AOS from "aos";
import "aos/dist/aos.css";
```

- init AOS animation

```
AOS.init({
  duration: 1000,
  offset: 100,
});
```

- Eg: add `data-aos="fade-down"` to the part that animation will be added.
  `<h4 data-aos="fade-down">Yummy Sushi</h4>`