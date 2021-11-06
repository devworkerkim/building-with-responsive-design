# Building With Responsive Design

This is the repo for the Building With Responsive Design project in the HTML And CSS course of The Odin Project.  The project is the recreate The Next Web webpage and include a responsrive design such that the page's look changes as the size of the window changes.

## What I Learned

### Mobile First

I thought I would give mobile first design a try since I usually start my responsive design with desktop first.  The video [Are you writing responsive CSS the wrong way?](https://www.youtube.com/watch?v=0ohtVzCSHqs) from the lesson brought up some good points about doing mobile first instead of desktop first.  I thought I would give it a try and see how the CSS turned out.

Based on working with this project, I can agree with designing mobile first instead of desktop first.  I think because there was a lot more complexity in the design it would make sense to outline all the details in the beginning and then take advantage of the space as it becomes available.  If I went desktop first, I would have had to figure out how to cram everything as the space became smaller.  Going mobile first makes for a cleaner, more thoughtful use of the space while being able to carry on the simple flow as the space increases.

I would historically argue that the design should be desktop first, but I think for aestheic reasons mobile first is the better way to design.  I think I'm going to change my stance and go mobile first in my future designs.  The web may have been invented for the desktop first, but with advancements in mobile devices I think filling in the space as it increases is much easier.

### `::before` And `::after`

There is a numbered list on the page that didn't have the decimal point in the marker.  Trying to mimic the page as close as possible, I went searching for answers on how to remove the decimal point.  Essentially, I was learning how to customize the look of the numbered list.  I found this post on [Remove decimal from ordered \<ol\> list via CSS?](https://stackoverflow.com/questions/3153019/remove-decimal-from-ordered-ol-list-via-css) and the answer was only a few lines of CSS.  Part of the answer had the `::before` pseudo-element which I had seen before but didn't know what it was.

I found this article on [::before / ::after](https://css-tricks.com/almanac/selectors/a/after-and-before/) that had a really great explanation of these pseudo-elements right from the beginning.  After seeing the example and how the `::before` and `::after` elements were placed, it made complete sense.  This makes for a very clever way of adding visual content, and for good or bad it is not included in the DOM.

### Nesting Elements For Responsive Design

As I was starting to move from my mobile design to the desktop, I was starting to have issues with how certain child elements were nested in their parent element.  I tried to be thoughtful in structuring my elements so they were easy to maintain styling, but as I started moving into larger spaces some of my elements were not sizing or positioning the way I wanted them to.  A lot of the designing came down to trial and error for me.  Some of the headings, for example, have been pulled out of their respective parent element for styling reasons.  I also resorted to using specificity of elements to override styling.  I at least avoided using `important` in my CSS.

The more I was working with responsive design, the more I could see where things could possibly break just based on the nesting structure.  Solving these element structure problems involves breaking things down and trying to nest them such that the relationship between parent and child is efficient for styling.  I tried to limit as many levels of nesting as possible, but I think sometimes having more `<div>` elements is necessary.