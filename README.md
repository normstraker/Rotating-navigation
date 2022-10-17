# Rotating navigation

https://normstraker.github.io/Rotating-navigation/

- simple effect to add to webpage, click hamburger menu and page rotates to reveal menu at bottom of screen

## CSS

- overflow-x: hidden;
- transition: transform;
- transform: rotate();
- position: fixed;
- position: relative;
- position: absolute;
- background: transparent;
- .circle button:focus {
  outline: none;
  }
- transform-origin:
- .container.show-nav + nav li {
  transform: translateX(0);
  transition-delay: 0.3s;
  }
- list-style-type: none;

## Javascript

- getElementById()
- querySelector()
- addEventListener()
- .classList.add
- .classList.remove
