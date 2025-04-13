# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![Screenshot](./screenshots\Screenshot-html-qr-code.png)
![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- HTML, I was advised to always wrap my content with the main element to start. Next a div element was placed for the container. Inside the container the img, h1, and p elements were placed in that order.
- CSS, Following the style guide I provided the appropriate imported font, set up colors in root, and reset the default HTML styling. For the body element the font-family and font-size were applied according to the style guide.
  Styled the div and the elements nested within it starting at the top and working my way down.
- Final, Played around with the values of some CSS properties to get a match to the design .jpg file.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

How to center the div element on the screen vertically. I could not get the "margin: auto;" to work. So i resorted to using flex.

```html
<body>
  <main>
    <div class="container">
      <img src="images\image-qr-code.png" alt="qr code" />
      <h1 class="outfit-bold">
        Improve your front-end skills by building projects
      </h1>
      <p class="outfit-regular">
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </main>
</body>
```

```css
main {
  height: 100vh;
  width: 100vw;
  /* ||||  |||| */
  /* Centers the div element */
  display: flex;
  justify-content: center;
  align-items: center;
  /* ||||  |||| */
}
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

To continue improving my HTML and CSS skills.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [W3Schools](https://www.w3schools.com/css/css_align.asp) - This helped me to place the div element in the center of the screen.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

I have done most of my learning at FreeCodeCamp.org. It is a great community. I am excited to start Frontend Mentor projects.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
