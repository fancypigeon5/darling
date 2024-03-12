# Darling

[view the live site](https://fancypigeon5.github.io/darling/)

Darling is a software development and data analysis company that was in need for a webpage to have a professional apearance for potential clients. The site will function as a digital buisness card where potentail clients can get information about the company and most important can easily get in contact with the company.

![mockup of the site](assets/images/mockup.png)

## UX Design

___

### Strategy

We want to design a website for a belgium based software and data analysis consultancy.
the aim of the website is to create an online presence where future clients (buisnesses) can explore what is on offer and have an easy way of contacting the consultancy. The website shoud be User-friendly and clearly showcase what the client will gain from working together.


### Scope

Given the time constraints we are opting for a one page design that is divided into several sections that are easy to navigate and gives visitors the information they are looking for.
We also want to make sure it is easy to get in contact Both through a contact form and contact information that is provided.

The website should also contain a portfolio of the consultancy's previous projects to help give the visitors an understanding of the work they do.

### structure

We want the website to feel professional and to give visitors a feeling of trust. Both by providing high quality pictures and by giving the reader the information they are looking for in wel written short paragraphs of text.

### Skeleton

The website is a one-page website with the following sections:

- Home
- About
- Partners
- Previous projects
- Contact

### surface

#### Colors

The main colors of the page consist of the colors in the logo:

- The blue color (#0081c9) is an objective, calm and analythical color. This helps give the feeling os professionalism and reliability.
- The second color (#fffae6) is an off white. it gives the site a clean feeling without being to bright. It also helps smooth the contrast between with the blue color while still having enough contrast to be readable.

#### typography

For the font family we chose the Roboto (with a fallback of sans-serif) because it helps give the site the professional feeling we are looking for.
We got the font at [Google Fonts](https://fonts.google.com)

#### Images

The images used on the site are either custom made images (ex. Logo, ...) or they were created for this project using [Chatgpt 4.0](https://chat.openai.com)

## Testing

### Validators

I used the W3 validator for both HTML and CSS

-HTML: As shown in the screenshot below it passed all tests
![html test](assets/images/html-test.png)
-CSS: At first glance it might look bad (2 errors and 4 warnings) but after further inspection those are a false alarm. the errors are given because of the use of the :has() pseudo selector which is as of now not yet supported in the validator tool. but when looking at caniuse we find that there is support for all the major browsers and a 92,11% support rate which is definitly enough for our site. the warnings are because of the use of vendor prefixes which always get flagged by the validator tool.
![css test](assets/images/css-test.png)
![css has selector support](assets/images/css-has.png)

### Performance

To check the performance of the page we used PageSpeed which tests for both mobile and desktop. at first we got a lower score for performance (especially on mobile) but after getting the images all optimized and even preloading the background image for the hero section we got the performance to an acceptable score.
![mobile performance test](assets/images/performance-mobile.png)
![desktop performance test](assets/images/performance-desktop.png)

## Credits

### External links

- W3 Schools: reading their articles about elements and css selectors helped me understand problems when I got stuck.
-Stackoverflow: A few times when i was experiencing a problem, this site helped me to fix the issues i was having.
- Tinyjpeg: this was used to compress the images to a more web friendly size. 