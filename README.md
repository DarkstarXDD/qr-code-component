## Frontend Mentor Challenge 01 - QR Code Component

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.


### Screenshot of my solution
![](./screenshot_v2.png)
#


### Links
- Live Site URL: https://qr-code-component-darkstarxdd.vercel.app/
- Solution URL: https://www.frontendmentor.io/solutions/qr-code-component-nzRrmva-BD
#


### Built with
- HTML5 / CSS
- CSS Flexbox
- CSS Grid
#


### Feedback & further development
After sharing my initial solution i got some feedback on areas i could improve. So below are some changes i made on the second commit.

#### HTML
- Changed the `.container` from `<div>` to a `<main>` so the document has a landmark element. [Resource](https://dequeuniversity.com/rules/axe/4.6/landmark-one-main?application=axeAPI)
- I initially had a `<h2>` and a `<h4>`. Changed those to `<h1>` and `<p>` respectively. [Resource](https://dequeuniversity.com/rules/axe/4.6/heading-order?application=axeAPI)
- Updated the `alt` text of the image to be more descriptive.

#### CSS
- Removed the fixed `width` of the container, and added a `max-width` so the container won't be too big on larger screens.
- Changed the `height` of the container to be `min-height`.
- Changed `img` element `width` to a `max-width` and set it to `display: block`
#


- My Frontend Mentor Profile - [@DarkstarXDD](https://www.frontendmentor.io/profile/DarkstarXDD)
