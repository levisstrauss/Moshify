# Moshify Website Project

This is a sample website made as part of learning HTML and CSS lessons.

## Table of Contents

- [Component](#component)
- [Technologies](#technologies)
- [Animation](#animation)
- [Search Engine Optimization](#search-engine-optimization)
- [Validation of the Website](#validation-of-the-website)
- [Measure the Performance of the Website](#measure-the-performance-of-the-website)
- [Screenshot](#screenshot)

## Component

During the building process, I first built all components separately and then combined them together to form the final website.

## Technologies

- HTML
- CSS
- Git
- GitHub

## Animation

AOS (Animate On Scroll) library was used to animate the website.

- Website: [AOS Library](https://michalsnik.github.io/aos/)
- GitHub: [AOS GitHub](https://github.com/michalsnik/aos)

### Usage

- Add the `aos.css` file to your project.
- Add the `aos.js` file to your project after your js file.
- Initialize AOS:

```javaScript
<script>AOS.init();</script>
```

- Adding animation:
  Let's say we want to add animation to a content:

```html
  <div data-aos="fade-up">
      Content here...
  </div>
```

The list of all animations is on the GitHub page.

## Search Engine Optimization

- To specify the character encoding for the HTML document:

```html
<meta charset="UTF-8" />
```

- To specify how the browser should control the page's dimensions and scaling:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

- Description of the website:

```html
<meta name="description" content="Deploy your websites in less than 60 seconds." />
```

- Title of the website:

```html
<meta property="og:title" content="Moshify - Deploy your websites in less than 60 seconds." />
```

- Description and content of the website:

```html
<meta property="og:description" content="Moshify is an imaginary cloud hosting company. It's designed to teach people how to build modern websites using HTML5 and CSS3. To learn how to build this website from scratch, get the Ultimate HTML and CSS course on codewithmosh.com." />
```

- Type of the website:

```html
<meta property="og:type" content="website" />
```

- Image of the website:

```html
<meta property="og:image" content="http://moshified.com/moshify.jpg" />
```

- URL of the website:

```html
<meta property="og:url" content="http://moshified.com" />
```

## Validation of the Website

- HTML: [W3C Validator](https://validator.w3.org/)
- CSS: [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

## Measure the Performance of the Website

- [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
- [GTmetrix](https://gtmetrix.com/)
- [Pingdom Tools](https://tools.pingdom.com/)
- [WebPageTest](https://www.webpagetest.org/)
- [Dotcom-Tools Website Speed Test](https://www.dotcom-tools.com/website-speed-test.aspx)
- [Uptrends Website Speed Test](https://www.uptrends.com/tools/website-speed-test)
- [Monitis Website Load Test](https://www.monitis.com/free-tools/website-load-test)

## Screenshot

![Screenshot of Moshify](img/screenshot.png)
