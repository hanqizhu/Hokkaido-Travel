# Hanqi Zhu
# SI 539 Final Project

## A description of the responsive design.

The responsive design is based on the width of the viewport.

1. I have 2 kinds of grid design, and they are all responsive. (In page [Sapporo](https://hanqizhu.github.io/ResponsiveTest/sapporo.html), [Otaru](https://hanqizhu.github.io/ResponsiveTest/otaru.html), and [Hakodate](https://hanqizhu.github.io/ResponsiveTest/hakodate.html)):

  * First the image divs will become smaller and smaller, then they will change from 3 or 4 items per line to 2 items per line.

2. Also, the images linked with pages in the [home page](https://hanqizhu.github.io/ResponsiveTest/index.html) are also responsive.  

   * Similarly, they will become smaller and smaller at first, then they changes from 4 items per line to 2 items per line.

3. For all pages, the navigation bar will also change to 2 lines when the viewport width becomes small.

4. For all pages, the font sizes of the text in my pages will be smaller and adjusted with width.

5. In addition, the background image will change when the orientation is landscape.

__How my code improves the page:__

  My code ensures that user can see clearly of anything no matter what the viewport is like, and it keeps the pages clean and neat.

## A description of where to find uses of grid.

Please find my grid designs in page [Sapporo](https://hanqizhu.github.io/ResponsiveTest/sapporo.html), [Otaru](https://hanqizhu.github.io/ResponsiveTest/otaru.html), and [Hakodate](https://hanqizhu.github.io/ResponsiveTest/hakodate.html).

One of them is initially grid of 3, the other is initially grid 4. And they are designed to be responsive(Please refer to the first section).

I design them based on my number of photos, I also added a div named "Photo Gallery" to indicate it.

Especially in the page of [Otaru](https://hanqizhu.github.io/ResponsiveTest/otaru.html), the 2 grid designs are combined, so they looked better.

## A description of where to find at least two uses of javaScript and/or jQuery.

1. I used jQuery and javascript to make the slider in the [home page](https://hanqizhu.github.io/ResponsiveTest/index.html).
  I learned it from [this website](https://www.jssor.com/), but generate the code totally on my own, since it is not very difficult.
  This makes my page look better.

2. I used jQuery to generate a form that user can send me messages. They are at the bottom of each page in the footer.
  I used the action given by Colleen from [Formspree](https://formspree.io/)
  This helps because my pages become more interactive with users.

3. I also made the lightbox photo gallery, which is similar to the last assignment. It is applied along with my grid designs on page [Sapporo](https://hanqizhu.github.io/ResponsiveTest/sapporo.html), [Otaru](https://hanqizhu.github.io/ResponsiveTest/otaru.html), and [Hakodate](https://hanqizhu.github.io/ResponsiveTest/hakodate.html).
  This both makes my pages look good and interactive.

4. I used jQuery to make Accordion on page [Noboribetsu](https://hanqizhu.github.io/ResponsiveTest/noboribetsu.html)
  This is because the paragraph here is quite long, and simply adding sub headings would be a little bit plain. Adding an Accordion makes it fancier!
  I learned it from [jQueryUI](https://jqueryui.com/accordion/). I just use the jQuery scripts, but I wrote the HTML code and CSS styles totally on my own.

## Other basic requirements.
All are satisfied.

When I firstly demo to Colleen, I haven't done "jump to content" or passed the aXe/W3, and they are fixed now.

### Contrast Errors Explanation

1. The WAVE reported errors caused by lightbox, which are the same to the Lightbox assignment. I did not fixed it because the instructor has confirmed that this could be ignored.

2. The contrast error. I have 3 main colors on my websites: dark grey(#2d2d2d), black(#000000), and pink(#f38094). WAVE and aXe mainly report 2 color contrast problems:

  * The current page indicator: the background color is pink, and the frontground text color is white, though I have even made the font bold.

  * The pink texts and the background: the background image is a picture with very light grey color, and the default background color is nearly white, while some of the highlight texts are in pink color.

  I've tried to make the pink color darker, but it either contrats with white or with the dark grey color in the footer. In addition, I really like the combination of the colors I used, so I decided not to change them. So there exist these contrast

## Extras

### Accessibility Checklist

1. Is color alone used to convey important information?

    Yes,  view the page in gray-scale. I can still understand all the information and perform all page functions.

2. Is the color contrast of text readable by people with low-vision?

    Not sure. aXe did detect issues related to color contrast, please refer to last section about __Contrast Error and Warnings__.

3. Do all images have alternative text?

    Yes, they do.

4.  Does the alternative text make sense?

    Yes, I can understand what the picture is.

5. If the image is a link, does the alternative text clearly identify the link destination?

    Yes, in the home page there are four pictures linked to the sub pages, and the alt text says it is a link. And in the footer of each page there are four icons to social media websites, which is also easy to understand.

6. Are all CSS background images either pure decoration or have alternative text?

    Yes, if I hide all background images, I still have access to all information and functionality.

7. Is any text embedded in images?

    No. There isn't any text that can not be read by a Voice Over or Screen Reader.

8. Does the tab order make sense?

    Yes,  if you tab through the page using only your keyboard, the navigation order is logical and intuitive.

9. Can you always see where the keyboard focus is?

    Yes.

10. Does the user have access to the full functionality of the page or application using a keyboard alone?

    Yes. All functions and contents are able to be seen. You can fully interact with every interactive aspect of a web page using keyboard alone.

11. Do all form felds have appropriate labels?

    Yes, aXe did not detect any issues related to labels.

12. Is all content and functionality available to a screen reader?

    Yes, I used MacBook, and it is available to the Voice Over function of my laptop.

### Other Extras
* I used carousel to make a slider in the [home page](https://hanqizhu.github.io/ResponsiveTest/index.html)

* I used lightboxes in three pages: [Sapporo](https://hanqizhu.github.io/ResponsiveTest/sapporo.html), [Otaru](https://hanqizhu.github.io/ResponsiveTest/otaru.html), and [Hakodate](https://hanqizhu.github.io/ResponsiveTest/hakodate.html).

* I used jQuery to make Accordion on page [Noboribetsu](https://hanqizhu.github.io/ResponsiveTest/noboribetsu.html).

* I used Flip Card on on page [Noboribetsu](https://hanqizhu.github.io/ResponsiveTest/noboribetsu.html).
  __This is really an interesting part of my website!__ Please take a look at it there. Hover on it to see a very funny picture!
  I learned this from [w3schools](https://www.w3schools.com/howto/howto_css_flip_card.asp).

  I used part of the code there, changed the content and the background colors because I don't need that.

* As I showed my demo to Colleen, she agreed that I have a good command of designing the grid.
