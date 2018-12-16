# Hanqi Zhu
# SI 539 Final Project

## A description of the responsive design.

The responsive design is based on the width of the viewport.

1. I have 2 kinds of grid design, and they are all responsive. (In page [Sapporo](https://hanqizhu.github.io/ResponsiveTest/sapporo.html), [Otaru](https://hanqizhu.github.io/ResponsiveTest/otaru.html), and [Hakodate](https://hanqizhu.github.io/ResponsiveTest/hakodate.html)):

  * First the image divs will become smaller and smaller, then they will change from 3 or 4 items per line to 2 items per line.

2. Also, the images linked with pages in the home page are also responsive.  

   * Similarly, they will become smaller and smaller at first, then they changes from 4 items per line to 2 items per line.

3. The navigation bar will also change to 2 lines when the viewport width becomes small.

4. And the font sizes of the text in my pages will be smaller.

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

3. I also made the lightbox photo gallery, which is similar to the last assignment. It is applied in each page except the homepage, because the images of this page are linked to the sub pages.
  This both makes my pages look good and interactive.

4. I used jQuery to make Accordion on page [Noboribetsu](https://hanqizhu.github.io/ResponsiveTest/noboribetsu.html)
  This is because the paragraph here is quite long, but adding sub headings would be a little bit plain, while adding an Accordion makes it fancier.
  I learned it from [jQueryUI](https://jqueryui.com/accordion/). I just use the jQuery scripts, but I wrote the code, including CSS styles totally on my own.

## Other basic requirements.
All are satisfied.

When I firstly demo to Colleen, I haven't done "jump to content" or passed the aXe/W3, and they are fixed now.

### Contrast Error and Warnings

1. For

## Extras

1. Accessibility Checklist

  * Is color alone used to convey important information?
    Yes,  view the page in gray-scale. I can still understand all the information and perform all page functions.

  * Is the color contrast of text readable by people with low-vision?
    Yes. aXe did not detect any issues related to color contrast.

  * Do all images have alternative text?
    Yes, they do.

  *  Does the alternative text make sense?
    Yes, I can understand what the picture is.

  * If the image is a link, does the alternative text clearly identify the link destination?
    Yes, in the home page there are four pictures linked to the sub pages, and the alt text says it is a link. And in the footer of each page there are four icons to social media websites, which is also easy to understand.

  * Are all CSS background images either pure decoration or have alternative text?
    Yes, if I hide all background images, I still have access to all information and functionality.

  * Is any text embedded in images?
    No. There isn't any text that can not be read by a Voice Over or Screen Reader.

  * Does the tab order make sense?
    Yes,  if you tab through the page using only your keyboard, the navigation order is logical and intuitive.

  * Can you always see where the keyboard focus is?
    Yes.

  * Does the user have access to the full functionality of the page or application using a keyboard alone?
    All functions and contents are able to be seen. You can fully interact with every interactive aspect of a web page using keyboard alone.

  * Do all form felds have appropriate labels?
    Yes, aXe did not detect any issues related to labels.

  * Is all content and functionality available to a screen reader?
    Yes, I used MacBook, and it is available to the Voice Over function of my laptop.

2. I used carousel to make a slider in the [home page](https://hanqizhu.github.io/ResponsiveTest/index.html)

3. I used lightboxes in three pages: [Sapporo](https://hanqizhu.github.io/ResponsiveTest/sapporo.html), [Otaru](https://hanqizhu.github.io/ResponsiveTest/otaru.html), and [Hakodate](https://hanqizhu.github.io/ResponsiveTest/hakodate.html).

4. I used jQuery to make Accordion on page [Noboribetsu](https://hanqizhu.github.io/ResponsiveTest/noboribetsu.html).

5. I used Flip Card on on page [Noboribetsu](https://hanqizhu.github.io/ResponsiveTest/noboribetsu.html).
  __This is really an interesting part of my website!__ Please take a look at it there. Hover on it to see a very funny picture!
  I learned this from [w3schools](https://www.w3schools.com/howto/howto_css_flip_card.asp)
  I used part of the code there, changed the content and the background colors because I don't need that.

6. As I showed my demo to Colleen, she agreed that I have a good command of designing the grid.
