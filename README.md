# Lectrue HTML & CSS #

## Requirements in Detail

### Header
- Always at the upper part of the window, even when you scroll.
- The logo is on the left.
- Navigation points are placed on the right:
  - Each link should have a class `menu__link`.
  - When hovering over a menu item, an animated underline should appear.
  - The last link is a Subscribe button with appropriate design styles (Subscribe button should also have a `menu__link` class).
  - On mobile devices and tablets, the menu items must be hidden and instead there must be a burger-menu button — a paw icon (`menu__button` class).
- **EXTRA POINT:** Implement a Burger Menu (menu example).

### Intro Section
- Inside the container, there must be a block with text (`intro__content`) and a block with a picture (`intro__image`).
- `intro__content` has all the styles specified in the design (border-radius, padding, background, etc.).
- `intro__content` block should contain:
  - The title with the class `intro__title` with all the styles specified in the design.
  - The subtitle should contain the image (`intro__subtitle-image`) and the text (`intro__subtitle-text`).
  - `intro__subtitle-image` shouldn’t be visible on mobile devices.
  - Two buttons with the class `intro__button` should be displayed and have all the styles specified in the design.

### Info Section
- Inside the container, there should be two blocks for statistics and comments.
- The statistics block should contain:
  - Three sections with the class `stat_item`.
  - Each `stat_item` should contain `stat__item-title`, `stat__item-icon`, and `stat__item-value`.
- The comments block should contain:
  - The comment component.
  - The comment should contain the photo (`comment__photo`) and text info (`comment__info`).
  - The photo should be rounded and the exact size.
- **EXTRA POINT:** Implement the slider for 3 comments (the design you can find in Figma).

### Opportunities Section
- Inside the container, the title should have the class `opportunities__title` with the context, width, and all the styles specified in the design.
- Inside the container, the subtitle should have the class `opportunities__subtitle` with the context, width, and all the styles specified in the design.
- Inside the container, 3 cards with the class `opportunity` should be present.
  - Every card should have the image (`opportunity__image`), the title (`opportunity__title` with the corresponding styles and text), and the description.

### Gallery Section
- Inside the container, the title should have the class `gallery__title` with the context, width, and all the styles specified in the design.
- Inside the container, the subtitle should have the class `gallery__subtitle` with the context, width, and all the styles specified in the design.
- Inside the container, there should be at least 5 cards with the class `photo` and all the styles specified in the design (also pay attention to the hover effect).

### Subscribe Section
- Inside the container, the title should have the class `subscribe__title` with the context and all the styles specified in the design.
- Inside the container, the subtitle should have the class `subscribe__subtitle` with the context and all the styles specified in the design.
- Inside the container, the input to enter the email should have the class `subscribe__email` and all the styles specified in the design.
- Inside the container, the Subscribe button should have the class `subscribe__button` and all the styles specified in the design.
- The image with the class `subscribe__image` should be visible.

### Footer
- Always at the bottom of the page (even if you have no content on the page).
- It should have 3 icons — links to social networks (each link has a class `social__link`).
- It should have 4 navigation links (each link has a class `footer__link`).

## General Recommendations
- Don’t forget to change the cursor type when hovering over elements.
- Pay attention to all hover effects.
- If there are the same elements on the page, make sure to reuse the styles.
- For the icons, use the Icon Font approach.

## What Affects Your Mark
- **Markup:** It should be structured, clean, and valid. You can use these style guides: [HTML Style Guide](https://www.w3schools.com/html/html5_syntax.asp)
- **BEM Naming Convention**
- **Styles:** Selectors usage (types, class names, length). Keep your styles organized by using dedicated files and folders.
- **Responsive/Adaptive Design**

## What is Forbidden
- Don’t use any programming languages. Only HTML and CSS are allowed.
- Don’t use libraries and frameworks.
- Don’t publish your homework on GitHub! Please, submit it in the form of a link to a BitBucket repository, where there are all your `.html` and `.css` files.

## What is Allowed
- Using any CSS preprocessor.
- Using the latest CSS features. You don’t have to support IE.
- If there are problems with creating an Icon Font with the icons given in the design, you can replace them with your own suitable ones.

## Useful Links
- [Lecture Presentation](#)
- [The Difference Between Responsive and Adaptive Design](https://www.smashingmagazine.com/2018/01/understanding-responsive-adaptive-images/)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Color Palettes](https://www.color-hex.com/)
- [Npm http-server](https://www.npmjs.com/package/http-server)
- [Semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html)
- [HTML Style Guide](https://www.w3schools.com/html/html5_syntax.asp)
- [BEM Naming Convention](https://en.bem.info/methodology/naming-convention/)

## How to Get a 10 (For Those Who Managed to Read This Till the End)
- Follow the requirements specified above.
- Keep your code clean.
- Don’t forget about git flow (commits + branches).
- Add the slider for comments in the Info section.
- Add the Burger menu.
- Use IconFont for your icons.
- Follow the BEM Naming conventions.